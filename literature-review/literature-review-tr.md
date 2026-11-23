# AAV VP1 dizileri: literatür taraması ve analiz çerçevesi

**Dil:** Türkçe  
**Kapsam:** AAV1–AAV9 VP1 hizalamaları, amino asit/nükleotit bileşimi, NJ ve ML filogenileri, MEGA Z-test ekran görüntüsü  
**Araştırmacı:** Alperen Göçmen  
**Yürütücü:** Irmak Şevval Topçu  
**Durum:** Literatüre dayalı arka plan ve mevcut dosyalar için yorumlama çerçevesi. Bu belge yeni bir biyoinformatik analiz sonucu değildir.

## 1. Özet

Adeno-associated virus (AAV; adeno-ilişkili virüs), Parvoviridae içinde küçük, zarfsız ve tek iplikli DNA genomu taşıyan, yardımcı virüs işlevlerine bağımlı bir virüstür. AAV kapsidinin üç yapısal proteini VP1, VP2 ve VP3 aynı `cap` gen bölgesinden üretilir ve C-terminal dizilerinin büyük kısmını paylaşır. VP1, ortak kapsid gövdesine ek olarak N-terminal VP1-unique (VP1u) bölgesini taşır. Bu bölge enfeksiyon döngüsünde rol alan fosfolipaz A2 (PLA2) işlevi ve hücre içi taşınmayla ilişkili sinyaller içerir. Bu nedenle VP1, hem kapsid yapısının hem de viral giriş/taşınmanın işlevsel açıdan önemli bir parçasıdır.

Doğal AAV çeşitliliği kapsid geninde eşit dağılmaz. Özellikle yüzeye açık değişken bölgelerdeki amino asit farklılıkları reseptör etkileşimi, doku tropizmi ve antikor tanınmasıyla ilişkili olabilir. Bununla birlikte, AAV `cap` dizilerinde rekombinasyon yaygındır. Tek bir tam-gen ağacının bütün gen bölgesi için tek evrimsel geçmiş varsayımı bu nedenle yanıltıcı olabilir. Dizi hizalaması, okuma çerçevesi, boşluklar, rekombinasyon, model seçimi ve destek değerleri; ağaçların ve seçilim sonuçlarının yorumunu belirler.

Bu klasörde AAV1–AAV9 VP1 `.mas` hizalamaları, NJ ve ML ağaç PDF'leri, MEGA bileşim raporları ve Z-test ekran görüntüsü bulunmaktadır. Raporların üstbilgileri, nükleotit bileşim raporları dâhil veri dosyası olarak protein hizalamasının adını göstermektedir. Mevcut materyal, bu raporların doğru veri türü/analiz ayarlarıyla üretildiğini tek başına doğrulamaya yetmez. Bu nedenle mevcut sonuçlar nihai evrimsel çıkarım değil, kontrol edilmesi gereken analiz çıktıları olarak ele alınmalıdır.

## 2. AAV genomu ve VP1'in biyolojik rolü

AAV genomu yaklaşık 4,7 kb uzunluğunda tek iplikli DNA'dır. Genomun `rep` bölgesi replikasyon ve paketlemeyle ilişkili proteinleri, `cap` bölgesi ise kapsid proteinlerini kodlar. VP1, VP2 ve VP3 aynı kapsid kodlama bölgesinden üretilen, örtüşen proteinlerdir. VP3 dizisi ortak C-terminal gövdeyi oluşturur; VP2 bunun N-terminal uzantısını, VP1 ise daha uzun bir N-terminal bölgeyi içerir. Literatürde bu uzantılar VP1/VP2 ortak bölgesi ve VP1'e özgü VP1u bölgesi olarak adlandırılır. Kapsid 60 VP alt biriminden oluşur; VP1:VP2:VP3 oranı çoğu zaman yaklaşık 1:1:10 olarak verilir, ancak kapsid oluşumu ve alt birim bileşimi biyolojik/deneysel koşullardan etkilenebilir.

VP1u'nun PLA2 işlevi endozomal membran geçişi ve hücre içi taşınma bağlamında incelenmiştir. AAV1 VP1u üzerinde yapılan yapısal ve biyofiziksel çalışma, VP1u'nun pH değişimleriyle düzen ve ikincil yapı değişikliği gösterebildiğini, kapsid bütünlüğü korunurken N-terminal bölgenin dışa açılmasının mümkün olduğunu ortaya koymuştur ([Popa-Wagner ve ark., 2012](https://journals.asm.org/doi/full/10.1128/jvi.02524-12)). AAV8 kapsid yapısı çalışması, ortak C-terminal kapsid topolojisinin korunurken serotipler arasında reseptör bağlanması, transdüksiyon ve antikor tanınmasıyla bağlantılı yüzey bölgelerinin farklılaşabildiğini göstermiştir ([Nam ve ark., 2007](https://journals.asm.org/doi/10.1128/JVI.01304-07)). Bu bulgular, VP1 dizisi karşılaştırmasının yalnızca toplam benzerlik üzerinden değil, hangi bölgenin incelendiği dikkate alınarak yapılması gerektiğini destekler.

VP1'in işlevsel önemine rağmen, VP1'in tamamı yüksek çözünürlüklü kapsid yapılarında eşit ölçüde gözlenmeyebilir; esnek veya kapsid içinde saklı N-terminal kesimler yapısal haritalarda çözülemeyebilir. Dolayısıyla bir hizalamadaki her amino asit konumunu doğrudan yüzeyde, reseptörle temas eden veya antikorca erişilebilir bir bölge olarak tanımlamak doğru değildir. Yapısal yorum için referans serotipe ait deneysel yapı, kullanılan kalıntı numaralandırması ve VP1/VP2/VP3 başlangıç koordinatları eşleştirilmelidir.

## 3. Serotip çeşitliliği, filogeni ve rekombinasyon

Primate AAV izolatları incelendiğinde kapsid dizilerinde beklenenden yüksek çeşitlilik, özellikle hiperdeğişken bölgelerde yoğunlaşan farklılıklar ve eş enfeksiyonlar sırasında oluşabilecek homolog rekombinasyon bildirilmiştir ([Gao ve ark., 2003](https://doi.org/10.1073/pnas.0937739100)). Daha sonraki analizler `cap` genini bölümlere ayırıp VP1u, VP2/VP3 başlangıç çevresi ve ortak VP3 kapsid bölgesinin farklı ağaçlar verebildiğini göstermiştir ([Schmidt ve ark., 2008](https://pmc.ncbi.nlm.nih.gov/articles/PMC2238796/)). Bu, tek bir `cap` ağacının her bölgede aynı geçmişi temsil etmeyebileceğine dair doğrudan bir uyarıdır.

2024 tarihli kapsamlı bir AAV evrimi çalışması, farklı AAV soylarında seçilim sinyallerini ve olası immünolojik etkileri incelerken MEME ve diğer dizi-temelli yöntemleri kullanmış; seçilim işareti bulunan konumların çoğunun kapsid yüzeyinde veya biyolojik açıdan ilgi çekici bölgelerde yer alabildiğini raporlamıştır ([Zhang ve ark., 2024](https://doi.org/10.1371/journal.ppat.1012260)). Yazarlar bu konumları işlevsel hipotezler olarak tartışır; biyolojik işlevin kesin kanıtı için deneysel doğrulama gerekir. Gifford’un 2025 tarihli çalışması, AAV kapsid çeşitliliğinin farklı `rep` soyları ve konaklar arasında tekrarlayan rekombinasyon/yatay aktarım ile şekillenmiş olabileceğini savunmaktadır ([Gifford, 2025](https://doi.org/10.1073/pnas.2505928122)). Yeni sonuç, tam-gen ağaçlarını ihtiyatla ele alma gerekçesini güçlendirir.

AAV serotipleri arasındaki yakınlık, kullanılan dizi bölgesine ve örnekleme kapsamına bağlıdır. AAV1 ve AAV6 gibi birbirine çok yakın kapsid dizileri birden fazla konumda az sayıda amino asit değişikliğiyle ayrılabilir; bu nedenle yalnızca etiketlerden beklenen ağaç topolojisini varsaymak yerine hizalamadan hesaplanan uzaklık, model ve dal destekleri raporlanmalıdır. Ayrıca GenBank erişim numarasının, dizinin hangi izolata/serotipe ait olduğunun ve kullanılan sürümün kaydı önemlidir.

## 4. Seçilim testlerinin anlamı ve sınırları

Kodlayan dizilerde eşanlamlı olmayan (dN) ve eşanlamlı (dS) değişimlerin oranı/karşılaştırması, protein düzeyinde seçilim hakkında bilgi verir. Basit sezgisel çerçevede dN < dS saflaştırıcı (purifying) seçilimle, dN > dS pozitif seçilimle uyumlu olabilir. Ancak bunlar doğrudan her kalıntının işlevsel önemini kanıtlamaz; sonuç dizi örneklemesi, zaman ölçeği, kodon hizalaması, model varsayımları ve istatistiksel güce bağlıdır.

MEGA'nın kodon temelli Z-test belgeleri, Nei–Gojobori yöntemiyle dN ve dS tahminlerini, test edilen hipotezi, kapsamı (genel ortalama veya dizi çiftleri) ve boşluk verisini ele alma seçeneğini açıkça tanımlamayı gerektirir. MEGA yardımına göre `Prob` değeri seçilen anlamlılık eşiğinin altındaysa test edilen sıfır hipotezi reddedilir; test alternatifinin `dN > dS` mi yoksa `dN < dS` mi olduğu ayrıca belirtilmelidir ([MEGA: Testing for Selection](https://www.megasoftware.net/web_help_12/Part_I_Getting_Started/A_Walk_Through_MEGA/Testing_for_Selection.htm), [Nei–Gojobori yöntemi](https://megasoftware.net/web_help_12/Nei-Gojobori_Method.htm)). Ekran görüntüsünde başlık “Z-Test of Purifying Selection” olsa da yalnız görüntüden kullanılan model, kapsam, boşluk ayarı ve hücrelerin hangi istatistiği gösterdiği kesinleştirilemez. Sarı hücrelerde görülen sıfırlar tek başına “saflaştırıcı seçilim kanıtı” olarak raporlanmamalıdır; test ayarları ve dışa aktarılmış tam sonuç dosyası gereklidir.

Z-test genel/ikili karşılaştırma düzeyinde bir özet verir; belirli kodonlarda veya belirli dallarda gerçekleşen epizodik pozitif seçilimi yakalamak için tasarlanmamıştır. HyPhy yöntemleri farklı sorulara yanıt verir: FEL bir konum için soy ağacı boyunca sabit seçilim varsayımıyla dN/dS tahmin eder; FUBAR benzer şekilde konum düzeyinde yaygın seçilimi Bayesçi çerçevede değerlendirir; MEME bazı dallarda ortaya çıkan epizodik pozitif seçilimi arar. Rekombinasyon, tek ağaç varsayımını bozduğu için seçilim analizinde yalancı pozitifleri artırabilir. HyPhy dokümantasyonu, seçilim analizinden önce GARD ile rekombinasyon taramasını önerir ([HyPhy selection methods](https://www.hyphy.org/methods/selection-methods/)).

Bu nedenle çalışmada “saflaştırıcı seçilim vardır” gibi bir sonuç ancak önceden belirlenmiş hipotez, kodon hizalaması, test adı/modeli, p-değeri ve mümkünse birden fazla yöntemle tutarlılık belirtilerek yazılmalıdır. Bir genel Z-test sonucu, yüzey döngülerindeki lokal pozitif seçilimi dışlamaz; birkaç değişken konum da bütün proteinde pozitif seçilim olduğunu göstermez.

## 5. Filogenetik ağaçların okunması

Neighbor-joining (NJ), dizi çiftleri arasındaki evrimsel uzaklıklardan hızlı bir ağaç kurma yaklaşımıdır. Maximum likelihood (ML), seçilen evrim modeline göre gözlenen hizalamanın olasılığını en yüksek yapan ağaç/model parametrelerini arar. Her ikisi de hizalama ve model varsayımlarına bağlıdır. PDF'de yalnız ağaç çizimi bulunması, dal desteği, kullanılan ikame modeli, boşlukların işlenmesi, bootstrap tekrar sayısı veya dış grup bilgisini doğrulamaya yetmeyebilir.

Raporlanması gereken temel noktalar şunlardır: dizi bölgesi ve uzunluğu; analizde kalan hizalı konum sayısı; protein veya kodon/nükleotit verisi; boşluk ve eksik verilerin ele alınışı; model seçimi; ağaç yöntemi; dal desteği (ör. bootstrap veya uygun başka destek ölçüsü); köklendirme/dış grup; kullanılan program ve sürüm. NJ ile ML ağaçlarının topolojisi benzerse bu bir tutarlılık göstergesidir, fakat rekombinasyon varsa yine de tek bir evrimsel geçmişi kanıtlamaz. Topoloji uyuşmazlıkları, zayıf destekli dallar veya uzun dallar ayrıca incelenmelidir.

Seçilim analizi için protein hizalamasının nükleotit hizalamasına basitçe çevrilmesi yeterli değildir. Kodonların korunması için önerilen yaklaşım, nükleotit dizilerini protein düzeyinde hizalamak ve bu hizalamayı kodon sınırlarına geri projekte etmektir. Başlangıç/stop kodonları, okuma çerçevesi, iç boşlukların üçlü kodon sınırları ve kısmi diziler kontrol edilmelidir. Aksi durumda yanlış kodon karşılaştırmaları dN/dS tahminlerini bozabilir.

## 6. Bileşim çıktıları nasıl yorumlanmalı?

Amino asit bileşimi; proteinin hangi amino asitlerden ne oranda oluştuğunu betimler. Nükleotit bileşimi baz yüzdelerini verir; kodlayan dizilerde üç kodon pozisyonunun ayrı ayrı raporlanması, eşanlamlı kodon kullanımı ve baz bileşimi farklarını ayırt etmeye yardımcı olur. Genel frekans, korunmuş konumlara ait frekans ve değişken konumlara ait frekans aynı soruyu yanıtlamaz. Değişken bölgelerdeki kompozisyon, diziler arası işlevsel veya evrimsel farkları özetleyebilir; tek başına seçilim testi değildir.

Bu projedeki dört çıktı dosyası şu başlıkları içeriyor: amino asit bileşimi, amino asit değişken konum bileşimi, nükleotit bileşimi ve nükleotit değişken konum bileşimi. Dosyaların üstbilgileri `AAV_VP1_PROTEİN_ALİGNED.mas` adını veri dosyası olarak kaydetmiş. Nükleotit raporunda da her konum için T/C/A/G ve kodon pozisyonu (1/2/3) sütunları bulunuyor; bu, raporun kaynak hizalamasının gerçekten nükleotit mi yoksa amino asit mi olduğunu dosya başlığından tek başına anlamayı imkânsız kılıyor. Dosyadaki satır adları AAV1–AAV9 VP1 ve referans erişim numaralarını taşıyor.

Görünen rapor üstbilgilerinde amino asit hizalaması 751 konum, nükleotit hizalaması 2253 konum olarak özetleniyor; 2253 = 751 × 3 olduğundan bu boyutlar birbiriyle aritmetik olarak uyumlu. Raporlarda değişken konumlar sırasıyla 409/751 amino asit ve 1284/2253 nükleotit; korunmuş konumlar 331/751 amino asit ve 939/2253 nükleotit olarak etiketlenmiş. Bu sayılar rapor çıktısındaki site sınıflandırmasını aktarır; hizalama doğruluğunu veya seçilim mekanizmasını kanıtlamaz. Aynı erişim numarasına ait nükleotit ve protein dizileri, beklenen translasyon ve kodon konumları bakımından ayrıca kontrol edilmelidir.

## 7. Bu projeye özel değerlendirme ve yapılacak kontroller

1. **Girdi eşleştirmesi:** `alignments/` içindeki `.mas` dosyalarının dizi türünü ve içerdiği satırları açıp doğrulayın. Amino asit bileşimi, protein hizalamasından; nükleotit bileşimi ve dN/dS testleri ise karşılık gelen kodlayan nükleotit dizilerinden üretilmelidir. Rapor üstbilgisi kaynak dosya adını yanlış/yanıltıcı gösteriyorsa MEGA'da doğru girdiyle yeniden dışa aktarın.
2. **Dizi provenansı:** Her AAV1–AAV9 dizisinin tam erişim numarasını, kayıt sürümünü, izolat bilgisini ve indirme tarihini ekleyin. Sadece kısaltılmış NC/AF kodlarıyla yeniden üretilebilirlik sınırlıdır.
3. **VP1 tanımı:** Tüm diziler aynı protein sınırlarını mı kapsıyor, VP1u dâhil mi, başlangıç/stop ve eksik uçlar var mı kontrol edin. Aynı “VP1” adı farklı kayıt sınırlarıyla kullanılmış olabilir.
4. **Hizalama kalite kontrolü:** Kodon hizalamasını amino asit referanslı kurun; çok değişken uçlar, belirsiz karakterler ve uzun boşluk bloklarını gözden geçirin. Ham dizileri ve analizde kullanılan hizalamayı birlikte saklayın.
5. **Rekombinasyon:** Tam `cap` hizalamasında rekombinasyon taraması yapın. Sinyal varsa segment bazında ağaç ve seçilim analizini değerlendirin; rekombinasyonlu tek bir hizalamadan tek bir ağaçla güçlü evrimsel iddia kurmayın.
6. **Ağaç raporu:** NJ ve ML ağaçlarının modelini, destek değerlerini, tekrar sayısını ve dış grup/kök kararını not edin. PDF dışa aktarımında bunlar görünmüyorsa MEGA proje dosyasından ayarları ve sonuçları yeniden dışa aktarın.
7. **Z-test raporu:** Hipotez yönünü (dN < dS veya dN > dS), test kapsamını, Nei–Gojobori veya kullanılan diğer modeli, boşluk işleme seçeneğini, dN/dS, Z ve p değerlerini raporlayın. Ekran görüntüsü yerine tabloyu CSV/TSV veya MEGA sonuç dosyası olarak ekleyin.
8. **Çoklu test ve kapsam:** Çok sayıda ikili karşılaştırma/konum test ediliyorsa çoklu sınama düzeltmesi ve hipotezin önceden belirlenmiş olup olmadığı açıklansın. Genel ortalama testinin tüm site düzeyindeki evrimi temsil etmediği belirtilsin.
9. **İşlevsel yorum:** Seçilim olduğu düşünülen kalıntılar, serotipe özgü numaralandırmayla kapsid yapısı üzerinde eşleştirilmeden reseptör/antikor/tropizm açıklaması yapılmamalıdır. Biyolojik etki iddiası deneysel doğrulama gerektirir.
10. **Sürüm ve tekrar üretim:** MEGA sürümü, kullanılan diğer yazılımlar, model ayarları, komutlar ve tarih `methods.md` veya README'ye eklenmelidir. Mümkünse FASTA ham dizileri, hizalama, analiz yapılandırması ve dışa aktarılan tablolar depoya konmalıdır.

## 8. Makale/rapor için ölçülü sonuç cümlesi taslağı

> “AAV1–AAV9 VP1 dizileri amino asit ve kodon düzeyinde karşılaştırılmış; dizi bileşimi ile NJ ve ML filogenetik çıktıları betimsel olarak değerlendirilmiştir. Seçilim sonuçları, test edilen kodon hizalaması ve MEGA ayarlarına bağlıdır. AAV `cap` geninde bildirilen rekombinasyon nedeniyle bütün-gen filogenisi tek bir evrimsel geçmiş varsayımı olarak yorumlanmamış; bileşim farklılıkları tek başına seçilim kanıtı sayılmamıştır.”

Bu metin, girdiler ve analiz ayarları doğrulanmadan sonuç bölümüne doğrudan konulmamalıdır.

## 9. Seçilmiş kaynakça

1. Gao G. ve ark. 2003. *Adeno-associated viruses undergo substantial evolution in primates during natural infections.* PNAS 100(10):6081–6086. [https://doi.org/10.1073/pnas.0937739100](https://doi.org/10.1073/pnas.0937739100)
2. Schmidt M. ve ark. 2008. *Recombination and population mosaic of a multifunctional viral gene, adeno-associated virus cap.* Journal of Virology 82(11): 5349–5358. [https://pmc.ncbi.nlm.nih.gov/articles/PMC2238796/](https://pmc.ncbi.nlm.nih.gov/articles/PMC2238796/)
3. Popa-Wagner R. ve ark. 2012. *Structure and dynamics of adeno-associated virus serotype 1 VP1-unique N-terminal domain and its role in capsid trafficking.* Journal of Virology 86(23): 12887–12896. [https://doi.org/10.1128/JVI.02524-12](https://doi.org/10.1128/JVI.02524-12)
4. Nam HJ. ve ark. 2007. *Structure of adeno-associated virus serotype 8, a gene therapy vector.* Journal of Virology 81(22): 12260–12271. [https://doi.org/10.1128/JVI.01304-07](https://doi.org/10.1128/JVI.01304-07)
5. Li L. ve ark. 2024. *Dissecting positive selection events and immunological drives during the evolution of adeno-associated virus lineages.* PLOS Pathogens 20(6):e1012260. [https://doi.org/10.1371/journal.ppat.1012260](https://doi.org/10.1371/journal.ppat.1012260)
6. Gifford RJ. 2025. *Pervasive horizontal transfer of adeno-associated virus capsid genes.* PNAS 122(32):e2505928122. [https://doi.org/10.1073/pnas.2505928122](https://doi.org/10.1073/pnas.2505928122)
7. Nei M, Gojobori T. 1986. *Simple methods for estimating the numbers of synonymous and nonsynonymous nucleotide substitutions.* Molecular Biology and Evolution 3(5):418–426. [https://doi.org/10.1093/oxfordjournals.molbev.a040410](https://doi.org/10.1093/oxfordjournals.molbev.a040410)
8. Kosakovsky Pond SL. ve ark. 2006. *Automated phylogenetic detection of recombination using a genetic algorithm.* Molecular Biology and Evolution 23(10):1891–1901. [https://doi.org/10.1093/molbev/msl051](https://doi.org/10.1093/molbev/msl051)
9. Murrell B. ve ark. 2012. *Detecting individual sites subject to episodic diversifying selection.* PLOS Genetics 8(7):e1002764. [https://doi.org/10.1371/journal.pgen.1002764](https://doi.org/10.1371/journal.pgen.1002764)
10. Murrell B. ve ark. 2013. *FUBAR: a fast, unconstrained Bayesian approximation for inferring selection.* Molecular Biology and Evolution 30(5):1196–1205. [https://doi.org/10.1093/molbev/mst030](https://doi.org/10.1093/molbev/mst030)
11. MEGA Software. *Testing for Selection* ve *Nei–Gojobori Method* çevrimiçi yöntem dokümantasyonu. [Test kılavuzu](https://www.megasoftware.net/web_help_12/Part_I_Getting_Started/A_Walk_Through_MEGA/Testing_for_Selection.htm), [yöntem](https://megasoftware.net/web_help_12/Nei-Gojobori_Method.htm).
12. HyPhy. *Selection methods* dokümantasyonu: FEL, FUBAR, MEME, GARD ve RELAX. [https://www.hyphy.org/methods/selection-methods/](https://www.hyphy.org/methods/selection-methods/)

---

### Kaynak kullanım notu

Öncelik özgün araştırma makalelerine ve yöntemlerin birincil/dokümantasyon kaynaklarına verilmiştir. Bu tarama AAV biyolojisi ve dosyalardaki analiz türleriyle sınırlı, proje bağlamına yönelik bir başlangıç literatürüdür; sistematik derleme değildir. Kaynakça künyeleri, metin gönderimi öncesinde dergi biçimine göre son kez kontrol edilmelidir.
