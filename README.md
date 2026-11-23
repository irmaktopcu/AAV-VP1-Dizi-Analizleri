<div align="center">

# AAV VP1 Karşılaştırmalı Analizi

**AAV1–AAV9 VP1 dizilerinin hizalama, filogenetik ve bileşim çıktıları**

**Araştırmacı:** Alperen Göçmen  ·  **Yürütücü:** Irmak Şevval Topçu

[![Dil](https://img.shields.io/badge/dil-Türkçe-2E7D32)](#)
[![Durum](https://img.shields.io/badge/durum-keşifsel%20analiz-6A5ACD)](#)
[![İçerik](https://img.shields.io/badge/içerik-hizalama%20%7C%20filogeni%20%7C%20bileşim-1565C0)](#)

</div>

## Proje hakkında

Bu depo, AAV VP1 dizileri için hazırlanmış hizalama dosyalarını ve bunlardan elde edilmiş filogenetik ağaç, bileşim ve seçilim testi çıktılarının düzenli bir arşivini içerir. Amaç; AAV kapsid dizileri arasındaki benzerlikleri ve farklılıkları incelemek, analiz materyalini okunabilir ve izlenebilir biçimde bir arada tutmaktır.

> **Analiz notu:** Depodaki PDF ve metinler dışa aktarılmış sonuçlardır. Kaynak dizi kayıtları, kullanılan yazılım sürümü ve tüm analiz parametreleri henüz belgelenmediğinden bu depo şu an tam olarak yeniden üretilebilir bir analiz iş akışı değildir.

## Proje ekibi

| Görev | İsim |
|---|---|
| Araştırmacı | Alperen Göçmen |
| Yürütücü | Irmak Şevval Topçu |

## Depo yapısı

```text
.
├── alignments/       # VP1 nükleotit ve protein hizalamaları
├── composition/      # Amino asit ve nükleotit bileşim raporları
├── figures/          # Seçilim testi ekran görüntüsü
├── literature-review/ # Türkçe literatür taraması
└── trees/            # NJ ve ML filogenetik ağaç PDF'leri
```

## İçerik rehberi

| Klasör | İçerik |
|---|---|
| [`alignments/`](alignments/) | AAV VP1 hizalamaları (`.mas`) |
| [`trees/`](trees/) | Neighbor-Joining (NJ) ve Maximum Likelihood (ML) ağaçları |
| [`composition/`](composition/) | Amino asit/nükleotit bileşimi ve değişken konum raporları |
| [`figures/`](figures/) | MEGA Z-test of Purifying Selection ekran görüntüsü |
| [`literature-review/`](literature-review/) | [Türkçe literatür taraması ve proje için metodolojik değerlendirme](literature-review/literature-review-tr.md) |

### Öne çıkan çıktılar

- [Neighbor-Joining ağacı](trees/aav-vp1-neighbor-joining.pdf)
- [Maximum Likelihood ağacı](trees/aav-vp1-maximum-likelihood.pdf)
- [Amino asit bileşimi](composition/amino-acid-composition.txt)
- [Değişken konumlarda amino asit bileşimi](composition/amino-acid-composition-variable-sites.txt)
- [Nükleotit bileşimi](composition/nucleotide-composition.txt)
- [Değişken konumlarda nükleotit bileşimi](composition/nucleotide-composition-variable-sites.txt)

## Mevcut materyale ilişkin notlar

- Bileşim raporlarının üstbilgileri veri dosyası olarak protein hizalamasının adını gösteriyor; bu durum nükleotit bileşim raporları için de geçerli. Raporları yorumlamadan önce kullanılan giriş hizalamasının türü doğrulanmalı ve gerekiyorsa analiz doğru nükleotit hizalamasıyla yeniden üretilmelidir.
- Ekran görüntüsü MEGA'da bir saflaştırıcı seçilim Z-testinin yürütüldüğünü gösterir. Test modeli, hipotez kapsamı, boşluk işleme seçeneği ve tam istatistik tablosu bu görselden kesin olarak belirlenemediğinden görsel tek başına sonuç kanıtı sayılmamalıdır.
- NJ ve ML PDF'leri görsel çıktılardır. Ağaçların yöntem/model ayarları, dal desteği ve köklendirme bilgileri ayrıca kaydedilmelidir.
- Bileşim farkları tek başına seçilim mekanizmasını veya biyolojik işlevi kanıtlamaz. Yorumlar hizalama kalitesi, kodon yapısı, rekombinasyon ve uygun istatistiksel testlerle birlikte yapılmalıdır.

## Yeniden üretilebilirlik için önerilen kayıtlar

Analizin bağımsız olarak tekrarlanabilmesi için aşağıdaki bilgilerin depoya eklenmesi önerilir:

1. Her dizinin veri tabanı erişim numarası, sürümü ve indirme tarihi.
2. Ham diziler ve analizde kullanılan hizalamaların kaynakları.
3. MEGA ve diğer yazılımların sürümleri.
4. Ağaç kurma, bootstrap/dal desteği, boşluk işleme ve evrim modeli ayarları.
5. Seçilim testinin hipotezi, yöntemi, kapsamı ve tam sonuç tablosu.
6. Analiz adımlarını çalıştıran komutlar veya betikler.

## Atıf ve kaynaklar

AAV VP1 biyolojisi, kapsid evrimi, rekombinasyon ve seçilim yöntemleri için Türkçe kaynaklı değerlendirme ve seçilmiş birincil yayınlar [literatür taramasında](literature-review/literature-review-tr.md) yer almaktadır.

---

<div align="center">

*Düzenli analiz materyali · Açık ve dikkatli yorum · İzlenebilir bilimsel çalışma*

</div>
