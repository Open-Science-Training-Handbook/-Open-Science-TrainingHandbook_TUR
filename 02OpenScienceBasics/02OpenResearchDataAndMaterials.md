## <img src="/Images/Icons/open_data.png" width="200" height="200" />
## 2. Açık Araştırma Verileri ve Materyaller

### Nedir?

Açık araştırma verileri, akademik araştırma ve öğretim amaçlarının yanı sıra başka amaçlar için de serbestçe erişilebilen, yeniden kullanılabilen, düzenlenebilen ve dağıtılabilen verilerdir. İdeal olarak, açık verilerin yeniden kullanım veya dağıtımı konusunda herhangi bir kısıtlama yoktur ve buna uygun şekilde lisanslanmışlardır. İnsan deneklerin kimliğini korumak gibi istisnai durumlarda özel veya sınırlı erişim kısıtlamaları belirlenir. Verileri açık bir şekilde paylaşmak, araştırmaların doğrulanması ve tekrarlanabilirliği için temel oluşturarak verilerin incelenmesini sağlar ve daha kapsamlı işbirlikleri için bir yol açar. Açık veriler, en fazla, atıf yapma (attribute) ve aynı lisansla paylaşma (sharealike) şartına tabi olabilir \(bkz. [Açık Veri El Kitabı](http://opendatahandbook.org/guide/en/what-is-open-data)\).

## <img src="/Images/Icons/data2.png" width="150" height="150" />
### Gerekçe

Birçok araştırma projesinin genellikle en değerli çıktısı olan araştırma verileri, bilimsel araştırmaya dayanak oluşturan ve teorik veya uygulamalı bulguların türetilmesini sağlayan birincil kaynak olarak kullanılır. Bulguları/çalışmaları yinelenebilir ya da en azından tekrarlanabilir ya da farklı şekillerde yeniden kullanılabilir \(bkz. [Tekrarlanabilir Araştırma ve Veri Analizi](https://github.com/Open-Science-Training-Handbook/-Open-Science-TrainingHandbook_TUR/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md)\) hale getirmek için en iyi uygulama önerisi araştırma verilerinin, hassas veya kişiye özel verilerle ilgili etik, ticari ve gizlilik kısıtlamalarını dikkate alarak mümkün olduğunca açık ve [FAIR](https://www.force11.org/fairprinciples) ilkelerine uyumlu olmasıdır.

## <img src="/Images/Icons/finish.png" width="150" height="150" />

### Öğrenme hedefleri

1. Başkalarının alternatif yöntemlerle anlamasını, çoğaltmasını ve yeniden kullanmasını sağlamak için uygun paketleme ve dokümantasyon da dahil olmak üzere açık ve FAIR araştırma verilerinin temel özelliklerini ve ilkelerini anlamak.

2. Hassas olarak kabul edilebilecek veri türleri ve bunların açık bir şekilde paylaşılmasına ilişkin kısıtlamalar veya engeller hakkında bilgi.

3. Uygun veri yönetimi ve üst verilerle bir veri yönetimi planında gereken tedbirleri alarak ‘kapalı’ bir veri setini ‘açık’ hale dönüştürebilmek. 

4. Veri yönetim planını kullanabilmek ve araştırma sonuçlarınızı hassas veri içeriyor olsa dahi keşfedilebilir ve erişilebilir hale getirebilmek.

5. Farklı veri türlerini açıkça paylaşmanın artılarını ve eksilerini anlamak \(örneğin, gizlilik, hassasiyet, kimlik gizleme, aracılı erişim\).

6. Araştırma verilerinin sürdürülebilir şekilde arşivlenmesi için uygun üst verilerin önemini anlamak.

7. Araştırma verilerinin paylaşımı için temel iş akışlarını ve araçları anlamak.

### Temel unsurlar
## <img src="/Images/Icons/brain.png" width="150" height="150" /><img src="/Images/Icons/gears.png" width="150" height="150" />
#### Bilgi ve Beceriler
##### FAIR ilkeleri
2014 yılında, araştırma verilerinin yeniden kullanılabilirliğini optimize etmek için [FAIR Veri İlkeleri](https://www.force11.org/group/fairgroup/fairprinciples) adında bir dizi temel ilke taslağı oluşturulmuştur. Bu ilkeler, verilerin veya herhangi bir dijital nesnenin keşfedilebilir (**F**indable), erişilebilir (**A**ccessible), birlikte çalışabilir (**I**nteroperable) ve yeniden kullanılabilir (**R**e-usable) olduğundan emin olmak için topluluk tarafından geliştirilmiş bir dizi yönergeyi ve en iyi uygulamaları temsil ederler:

**Keşfedilebilir:** Verileri yeniden kullanılabilir hale getirmek için yapılması gereken ilk şey, onları bulma imkanını yaratmaktır. Hem insanlar hem de bilgisayarlar için verilerin ve üst verilerin bulunması kolay olmalıdır. Veri setlerinin ve hizmetlerin otomatik ve güvenilir şekilde keşfi makinaca okunabilir sabit/kalıcı tanımlayıcıların (persistent identifiers - PIDs) ve üst verilerin olmasına bağlıdır.  

**Erişilebilir:** \(Üst\) veriler, mümkünse doğrulama ve yetkilendirme içeren standart ve açık bir iletişim protokolü kullanılarak tanımlayıcıları tarafından çekilebilir olmalıdır. Ayrıca, verilerin artık mevcut olmadığı durumlarda dahi üst verilere erişilebilir olmalıdır.

**Birlikte çalışılabilir:** Veriler, diğer veriler veya araçlarla birleştirilip kullanılabilir olmalıdır. Bu nedenle verilerin formatı, diğer veri kayıtları da dahil olmak üzere çeşitli araçlar için açık ve yorumlanabilir olmalıdır. Birlikte çalışabilirlik kavramı hem veri hem de üst veri düzeyinde geçerlidir. Örneğin, \(üst\) veriler için FAIR ilkelerine uyumlu sözlükler (vocabularies) kullanılmalıdır.

**Yeniden kullanılabilir:** FAIR, en nihayetinde, verilerin yeniden kullanımını optimize etmeyi amaçlar. Bunu başarmak için üst veriler ve veriler, farklı ortamlarda çoğaltılabilmeleri ve/veya birleştirilebilmeleri için iyi tanımlanmış olmalıdır. Ayrıca, üst verilerin yeniden kullanım durumu açık/net ve erişilebilir lisanslar ile belirtilmelidir.

Bilim insanlarına odaklanan hakemlik girişimlerinden farklı olarak, FAIR ilkeleri, insanlar tarafından yeniden kullanımını desteklemenin yanı sıra, makinelerin verileri veya herhangi bir dijital nesneyi otomatik olarak bulma ve kullanma yeteneğini geliştirmenin özellikle üzerinde durmaktadır. FAIR ilkeleri standartlar değil, yol gösterici ilkelerdir. FAIR verileri en üst düzeyde yeniden kullanılabilir hale getirmek için gereken nitelikleri ve tutumları tanımlar \(örneğin, tanımlama, atıf\). Bu niteliklere farklı standartlarla ulaşılabilir.

![](/Images/02%20Open%20Science%20Basics/02_open_research_data_material.png)

##### Veri yayımlama

Çoğu araştırmacı, araştırma makalelerinin ve kitaplarının Açık Erişim yayıncılığına az çok aşinadır \(bkz. Bölüm 5\). Daha yakın zamanlarda ve yukarıda belirtilen nedenlerden dolayı veri yayımlama giderek artan bir ilgi görmeye başlamıştır. Gittikçe daha fazla fon sağlayıcı, finanse ettikleri araştırma projeleri kapsamında üretilen verilerin keşfedilebilir, erişilebilir ve mümkün olduğunca açık olmasını beklemektedir.

Araştırma verilerini erişilebilir yapmanın aşağıdakileri de içeren birçok farklı yolu vardır \([Wikipedia](https://en.wikipedia.org/wiki/Data_publishing)\):

* Verilerin, [araştırma makalesi](https://en.wikipedia.org/wiki/Research_article) ile ilişkili ek materyal olarak, genellikle makalenin yayıncısı tarafından tutulan veri dosyaları ile birlikte yayımlanması.

* Verileri, indirilebilecek dosyalarla birlikte, kamuya açık bir web sitesinde tutma.

* Verileri, veri yayımlamayı desteklemek için oluşturulmuş bir veri havuzunda depolama. Örneğin, [Dataverse](https://en.wikipedia.org/wiki/Dataverse), [Dryad](https://en.wikipedia.org/wiki/Dryad_(repository)), [figshare](https://en.wikipedia.org/wiki/Figshare), [Zenodo](https://en.wikipedia.org/wiki/Zenodo).

* Araştırmacılara verilerini depolarken ek destek sağlayabilecek çok sayıda genel ve alana veya konuya özel veri havuzu mevcuttur.

* Veri seti ile ilgili, bir dergide veya veri makalelerini (data paper) desteklemeye ayrılmış bir veri dergisinde ön baskı olarak yayımlanabilecek bir veri makalesi (data paper) yayımlamak. Veriler dergi tarafından veya bir veri havuzunda ayrı olarak tutulabilir. Veri dergilerine \(SpringerNature'ın\) [Scientific Data](https://www.nature.com/sdata/) dergisi ile \(CODATA'nın\) [Data Science Journal](http://www.codata.org/publications/data-science-journal) adlı dergisi örnek verilebilir. Veri dergilerinin daha kapsamlı bir değerlendirmesi için bkz. [Candela ve diğerleri](https://doi.org/10.1002%2Fasi.23358).

CESSDA ERIC [Veri Yönetimi konusunda uzman tur rehberi](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Data-publishing-routes), farklı veri yayımlama yollarının artıları ve eksileri ile ilgili genel bir bakış sağlamaktadır. Bazen fon sağlayıcınız ya da diğer bir harici taraf belli bir veri havuzunu kullanmanızı gerektirebilir. Seçim konusunda özgürseniz, [OpenAIRE önerilerindeki](https://www.openaire.eu/opendatapilot-repository-guide) tercih sırasını göz önünde bulundurabilirsiniz:

1. Verileri kendi disiplininizde tanınan standartlara göre korumak amacıyla araştırma alanınız için önceden kurulmuş harici bir veri arşivi veya havuzu kullanın.

2. Eğer mevcutsa, kurumsal bir araştırma veri havuzu ya da araştırma grubunuzun varolan veri yönetimi olanaklarını kullanın.

3. [Dataverse](https://dataverse.org/), [Dryad](https://datadryad.org/pages/faq#depositing-cost), [figshare](https://figshare.com/) ya da [Zenodo](https://zenodo.org/) gibi ücretsiz bir veri havuzu kullanın.

4. [re3data](https://www.re3data.org/)'daki diğer veri havuzlarını araştırın. re3data'da FAIR ilkelerini kapsayan tek bir filtreleme seçeneği yoktur, ancak şu filtreleme seçeneklerini göz önünde bulundurmak FAIR uyumlu veri havuzlarını bulmanıza yardımcı olacaktır: erişim kategorileri, veri kullanım lisansları, güvenilir veri havuzları \(sertifika ile ya da doğrudan arşiv standartlarına bağlı kalarak\) ve havuzun verilere kalıcı tanımlayıcı \(persistent identifier - PID\) verip vermediği. Dikkate alınması gereken bir diğer husus havuzun farklı dosya sürümleri oluşturmayı (versioning) destekleyip desteklemediğidir.

## <img src="/Images/Icons/archive.png" width="150" height="150" />
Araştırma veri yönetim planınızda verilerinizi nerede depolayacağınızı ve yayımlayacağınızı düşünmüş olmalısınız. CESSDA, gözününde bulundurulması önerilen bazı uygulamaya yönelik sorular sunmaktadır. Örneğin: Hangi veriler, ilişkili üst veriler, dokümanlar ve kodlar depolanacak? Verilerin ne kadar süre saklanması gerekiyor? Veriler ne kadar süreyle yeniden kullanılabilir durumda kalmalıdır? Veriler nasıl kullanıma sunulacak? Hangi erişim kategorisini seçeceksiniz? Daha fazla soru için bkz. [Adapt your DMP: part 6](https://www.cessda.eu/Research-Infrastructure/Training/Expert-Tour-Guide-on-Data-Management/6.-Archive-Publish/Adapt-your-DMP-part-6). Diğer taraftan, seçilen bir veri havuzunun araştırmanız ve fon sağlayıcınız için gereklilikleri karşılayıp karşılamadığını kontrol etmeyi unutmayın. Bazı veri havuzları halihazırda güvenilir olduklarını ve Temel Güvenilir Veri Havuzu Gereksinimlerini karşıladıklarını onaylayan CoreTrustSeal gibi sertifikaları almışlardır. Bazı alana özgü veri havuzlarının, yalnızca yeniden kullanım potansiyeli olan ve herkese açık olarak paylaşılabilen yüksek kalitedeki verileri kabul edeceğini belirtmekte fayda vardır.

Verilerinizi yayımlamanın birçok yolu olduğundan, bir veri setinin yayın olarak "sayılması" için bir makaleye benzer bir yayın sürecini izlemesi gerekmekte \([Brase ve diğerleri, 2009](https://doi.org/10.3233/ISU-2009-0595)\) ve:

* Üst verilerle birlikte uygun şekilde dokümante edilmiş;

* Nitelik yönünden gözden geçirilmiş, örneğin çalışmanın içeriği, metodoloji, ilgililik, yasal uygunluk ve materyallerin dokümantasyonu;

* Kataloglarda \(ya da veri tabanlarında\) aranabilir ve keşfedilebilir;

* Makalelerde atıf yapılabilir olmalıdır.

## <img src="/Images/Icons/metadata.png" width="150" height="150" />
##### Veri atıfı

Veri atıf hizmetleri/faaliyetleri, araştırma topluluklarının araştırma verilerini \(ve genellikle diğer araştırma objelerini\) güvenle keşfetmesine, tanımlamasına ve bunlara atıf yapmasına yardımcı olur. Bu genellikle, digital nesne tanımlayıcıları \(Digital Object Identifiers - DOIs\) ve veriye eşlik eden üst verilerin [DataCite](https://www.datacite.org) gibi hizmetler aracılığıyla oluşturulması ve tahsisini/atanmasını içerir ve araştırma iş akışları ve standartlar ile entegre edilebilir. Bu, gelişmekte olan bir alandır ve makalelerde verilere uygun şekilde atıf yapmanın önemini dergi yayıncılarına iletmek ve aynı zamanda araştırma makalelerinin araştırmanın verileri ile ilişkilendirilmesinin sağlanması gibi konuları kapsar. Bu sayede, atıf yapılabilir veriler bilimsel iletişim sürecine yerinde katkılar haline gelir ve veri paylaşımını tanıyan ve ödüllendiren yeni ölçevler ve yayın modellerinin önünü açmaya yardımcı olabilir.

Veri atıfı için iyi uygulamaya yönelik ilk adım  olarak, FORCE11'in Veri Atıf Sentezi Grubu (Data Citation Synthesis Group), hem araştırmacıları hem de veri hizmet sağlayıcılarını hedef alan [Veri Atıf İlkeleri Ortak Bildirisini - Joint Declaration of Data Citation Principles](https://doi.org/10.25490/a97f-egyk) önermiştir. Bu ilkelere bağlı kalarak, veri havuzları genellikle araştırmacılara belirli bir veri setine atıfta bulunurken kullanabilecekleri bir dayanak/örnek sunar.

## <img src="/Images/Icons/database.png" width="150" height="150" />
##### Veri paketleme

Veri paketleri, verilere eşlik eden veri dosyalarının tanımlanması ve paylaşılmasına yönelik veri konteynerleri olup ve tipik olarak bir veri setinin özelliklerini ve içeriğini açıklayan bir üst veri dosyası içerirler. Veri paketleri, veri oluşturma komut dosyaları veya metin belgeleri gibi ilgili içerik dosyalarının yanı sıra veri setini oluşturma ile ilgili bilgileri, provenans, verinin boyutu, formatı/türü, alan tanımları gibi hususları içerebilir. [Veri Paketleme Rehberinde](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md) belirtildiği üzere:

* Veriler sonsuza dek yaşar: Veri setleri ortaya çıkış amaçlarından daha uzun ömürlüdür.
* Verilerin sınırlılıkları, bir kütüphane kataloğu gibi asıl ortamları içinde göze çarpabilir, ancak veriler oluşturuldukları kullanım amacının dışına çıktığında belirgin olmayabilir.

* Veri tek başına olamaz: Verinin içeriği ve provenansı hakkındaki bilgi--nasıl ve neden oluşturulduğu, hangi gerçek dünya nesneleri ve kavramlarını temsil ettiği, değerler üzerindeki kısıtlamalar--kullanıcıların veriyi sorumlu bir şekilde yorumlamalarına yardımcı olmak için gereklidir.

* Veri setleri ile ilgili üst verileri standart, makinece okunabilir şekilde yapılandırmak verilerin tanıtımını, paylaşılabilirliğini ve yeniden kullanımını teşvik eder. 

## <img src="/Images/Icons/privacy.png" width="150" height="150" />
##### Hassas ve kişisel verilerin paylaşılması

Uygun bir veri yönetim planlaması ile çok hassas ve kişisel/özel veriler paylaşılabilir, yeniden kullanılabilir ve FAIR ilkelerine uyumlu olabilir. Üst veriler neredeyse her zaman paylaşılabilir. Hassas verilerin paylaşılmasına yönelik rehberlik ve en iyi uygulamalar, farklı düzenlemeler dolayısıyla zorunlu olarak bölgeye özgüdür \(örneğin bkz. UKDS’nin [Araştırma Verilerini Yönetme ve Paylaşma el kitabı yardımcı materyali](https://www.fosteropenscience.eu/content/managing-and-sharing-data-handbook)\). [Uluslararası Sosyal Bilimler Bilgi Hizmetleri ve Teknoloji Derneği (International Association for Social Science Information Services & Technology)](https://iassistdata.org/) iyi bir başlangıç noktası olan veri yönetiminde uluslararası rehberlik listesini tutmaktadır. Araştırmacıların veri yönetimini başarıyla yapmasına yardımcı olacak çeşitli yaklaşım ve girişimler vardır. [DCC’nin DMPonline aracı](http://www.dcc.ac.uk/dmponline) fon sağlayıcılar için bir dizi şablon içerir. [CESSDA Veri Yönetimi Uzman Tur Rehberi](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection) Avrupa ülkelerinde kişisel verilerin nasıl paylaşılacağı ve telif hakkı ve veri tabanı konuları ile ilgili bilgi ve pratik örnekler sağlar. Tur Rehberi aynı zamanda Avrupa'daki kişisel veri mevzuatını \(Mayıs 2018\) uyumlu hale getirecek olan GDPR'nin etkisi ve [Veri korumasında AB çeşitliliği](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection) hakkında güncellenmiş bir genel bakış sunar.[ ](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection)

###### Veri simsarlığı

Veri simsarları, hassas veriler için veri sorumlusu (data steward) olarak hareket eden bilgili, bağımsız taraflardır. Araştırmacılar, hassas verilerini ve bu verilere erişim üzerindeki yetkilerini veri simsarlarına aktarabilir. Bu özellikle klinik çalışmalardan elde edilen hasta düzeyindeki veriler için yaygındır. Veri simsarları, taleplerin bilimsel olarak geçerli olduğu değerlendirmelerde belirli bir düzeyde bağımsızlık sağlar ve araştırma katılımcılarının mahremiyetini ihlal etmez. Veri simsarlığı örnekleri olarak [The YODA Project](http://yoda.yale.edu/), [ClinicalStudyDataRequest.com](https://www.clinicalstudydatarequest.com/), [National Sleep Research Resource](https://sleepdata.org/) ve [Supporting Open Access for Researchers \(SOAR\)](https://dcri.org/our-approach/data-sharing/) verilebilir.

## <img src="/Images/Icons/data.png" width="150" height="150" />
##### Analiz portalları
Analiz portalları, tam erişime izin vermeksizin \(görüntüleme ya da indirme\) veya nereden kimin eriştiğini kontrol ederek, verilerin onaylı analizine izin veren portallardır. Bazı veri simsarları da bu analiz portallarını kullanmaktadır. Analiz portalları, yeniden yapılan analizlerde kişisel bilgilerin açığa çıkmamasını garanti etmek için hangi analizlerin yapılabileceğinin yanı sıra, hassas verilerle hangi ek veri setlerinin biraraya getirilebileceğini kontrol ederler. Sanal veri analiz portallarına örnek olarak [Project Data Sphere](https://www.projectdatasphere.org/projectdatasphere/html/home), [Vivli](http://vivli.org/), [RAIRD](http://raird.no/), [Corpuscle](http://clarino.uib.no/korpuskel/page) ve [INESS](http://clarino.uib.no/iness/page) verilebilir.

Hassas verilere sahip sosyal bilim araştırmacıları ve diğer araştırmacılar sadece kontrollü bir sistemle erişilebilen tek taraflı (single-site) bir analiz portalı kullanırlar. Onaylanmış araştırmacılar bilimsel amaçlarla verilere yerinde, güvenli bir odada erişebilirler. Ancak, verileri tanımlayan üst veriler açık erişimli ve FAIR ilkelerine uyumlu olmalıdır.

##### Kimliği gizlenmiş ve yapay veriler

Katılımcı düzeyinde kişisel bilgiler içeren birçok veri seti, kimlikler gizlendikten (kimliksizleştirildikten) \(Güvenli Liman yöntemi\) ya da bir uzman, kimliklerin ortaya çıkarılamayacağını belirledikten \(Uzman Belirleme yöntemi\) sonra paylaşılabilir. Veriniz için bunu nasıl yapabileceğinizi öğrenmek için Araştırma Etik Kurulunuza / Kurumsal Değerlendirme Kurulunuza danışın. Kişisel verilerin nasıl paylaşılacağına ilişkin bilgi ve pratik örnekler içeren [CESSDA Veri Yönetimi Uzman Tur Rehberini](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection) de öneririz. Ancak bazı veri setlerinde kimlikler güvenli bir şekilde gizlenemez ve bu veri setleri paylaşılamaz. Araştırmacılar yine de söz konusu veri seti üzerinden yapay veri oluşturup paylaşarak araştırmanının açıklığına katkı sunabilir. Yapay veriler, yapı, içerik ve dağılım bakımından gerçek veriye benzer ve "analitik geçerlilik" elde etmeyi amaçlar:  istatistiksel analizler yapay veriler için de gerçek verilerle aynı sonuçları verir. Örneğin, Amerika Birleşik Devletleri Nüfus Bürosu (The United States Census Bureau), yüksek düzeyde hassas verilerin yeniden kullanımına olanak vermek için [yapay verileri ve analiz portallarını](https://census.gov/content/dam/Census/programs-surveys/sipp/methodology/SSBdescribe_nontechnical.pdf) birlikte kullanmaktadır.

###### Veri Etiketleri

[VeriEtiketleri](https://datatags.org/) veri paylaşımı ile ilgili kararları yönlendiren yasal, sözleşmeden doğan kısıtlamalar ile politika kısıtlamalarının bilgisayar destekli değerlendirmelerini sağlamak için tasarlanmış bir çerçevedir. VeriEtiketleri (DataTags) sistemi, belirli bir veri setinin temel özelliklerini ortaya çıkarmak için bir kullanıcıya bir dizi soru sorar ve hangi yasaların, sözleşmelerin ve en iyi uygulamaların geçerli olduğunu belirlemek için çıkarım kurallarını uygular. Çıktı insan tarafından okunabilir ve makine tarafından eyleme geçirilebilir bir veri politikasını temsil eden bir dizi önerilen VeriEtiketleri kümesi ya da basit, simgesel etiketler ve bireysel veri setine göre uyarlanmış bir lisans anlaşmasıdır. VeriEtiketleri sistemi veri havuzu yazılımı ile entegre olacak şekilde tasarlanmış olup, ayrıca bağımsız bir araç olarak da çalışacaktır. VeriEtiketleri Harvard Üniversitesinde geliştirilmiştir. Avrupa'da DANS, VeriEtiketlerini Avrupa mevzuatına / Genel Veri Koruma Yönetmeliğine uyarlamak için çalışmaktadır \([GDPR](https://www.eugdpr.org/)\) \(cf. [DANS GDPR VeriEtiketleri](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)\).

Yukarıda belirtildiği gibi, araştırma verilerinizi paylaşmanın nihai amacı onları en üst düzeyde yeniden kullanılabilir hale getirmektir. Bu amaçla, verilerinizi paylaşmadan önce en iyi uygulamalara göre yönetmelisiniz. Bu, örneğin, dokümantasyonu ve açık dosya formatlarının ve lisanların seçimini kapsar. Bu konularla ilgili olarak daha fazla bilgiyi [Bölüm 4: Tekrarlanabilir Araştırma ve Veri Analizi](https://github.com/Open-Science-Training-Handbook/-Open-Science-TrainingHandbook_TUR/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md) ve aynı zamanda [Bölüm 6: Açık Lisanslama ve Dosya Formatları](https://github.com/Open-Science-Training-Handbook/-Open-Science-TrainingHandbook_TUR/blob/master/02OpenScienceBasics/06OpenLicensingAndFileFormats.md) bölümlerinde bulabilirsiniz.


## <img src="/Images/Icons/usb.png" width="150" height="150" />
##### Açık Materyaller

Veri paylaşımına ek olarak, araştırmaların açıklığı materyallerin paylaşımına da dayanmaktadır. Araştırmacıların hangi materyalleri kullandığı disipline ve bazen de laboratuvara özgüdür. Aşağıda paylaşabileceğiniz materyal örnekleri yer almaktadır, ancak hangi havuzların kullanıldığını belirlemek için her zaman kendi disiplininizdeki meslektaşlarınıza danışın. Aynı araştırma projesinden farklı depolarda paylaşılmış materyalleriniz, verileriniz ve yayınlarınız olduğunda, kolayca bulunabilmeleri için bir bağlantı ve tekil tanımlayıcı ile çapraz bağlantı verin.

###### Reaktif/Ayıraç (Reagent)

Reaktifler, kimyasal veya başka bir reaksiyon oluşturmak için bir sisteme eklenebilen bir madde, bileşen veya karışımdır. Reaktifler, diğer araştırmacılar için kolayca erişilebilir hale getirilmek üzere [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/) ve [ATCC](https://www.atcc.org/) gibi havuzlarda depolanabilir. Materyallerinizi, diğer araştırmacıılar tarafından kullanılabilmeleri için lisanslayın.

###### Protokoller

Bir protokol, yapılandırılmış bir formattaki bilimsel içerikli deneysel gözlemlerin resmi ya da biçimsel kaydını tanımlar. Atıf, uyarlama  ve yeniden kullanım sanal protokollerini [Protocols.](https://www.protocols.io/)[io](https://www.protocols.io/) ile depolayın.

###### Not defterleri, konteynerler, yazılım ve donanım

Tekrarlanabilir analizler, kolay anlaşılır (literate) programlama, konteyner teknolojisi ve sanallaştırma kullanımıyla desteklenir. Kodlarınızı ve verilerinizi paylaşmanın yanı sıra, Jupiter not defterlerinizi, Docker imajlarınızı veya analiz materyalleri ya da yazılım destek dosyalarını da paylaşın. Not defterlerini, paylaşılan kaynakların tümünü herkesin görüntülemesine ve düzenlemesine izin veren [mybinder](http://mybinder.org) gibi açık servislerle paylaşın. Konteynerler ve not defterleri [Rocker](https://arxiv.org/abs/1710.03675) ya da [Code Ocean](https://codeocean.com/) ile paylaşılabilir. Araştırmanızda kullanılan yazılım ve donanım, [Bölüm 3'te](https://github.com/Open-Science-Training-Handbook/-Open-Science-TrainingHandbook_TUR/blob/master/02OpenScienceBasics/03OpenResearchSoftwareAndOpenSource.md) özetlendiği gibi dokümantasyon için en iyi uygulamalar izlenerek paylaşılmalıdır. Salt okunur protokoller, [ClinicalTrials.gov](https://clinicaltrials.gov/) ve [SocialScienceRegistry](https://www.socialscienceregistry.org/) gibi disipline özgü veri tabanlarında ya da [Open Science Framework](https://osf.io/) gibi genel veri tabanlarında depolanmalıdır. [Trials](https://trialsjournal.biomedcentral.com/), [JMIR Research Protocols](https://www.researchprotocols.org/) ya da [Bio-Protocol](https://bio-protocol.org/) gibi birçok dergi protokolünüzü yayımlayacaktır. Protokolünüzü açık erişimli yayımlamak için en iyi uygulamalar, raporunuzu açık erişim yayımlamak için olanlarla aynıdır \(bkz. [Bölüm 5](https://github.com/Open-Science-Training-Handbook/-Open-Science-TrainingHandbook_TUR/blob/master/02OpenScienceBasics/05OpenAccessToPublishedResearchResults.md)\).


## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Sorular, engeller ve yaygın yanlış anlamalar

Q: "Verilerimi açık erişimli yapmam yeterli midir?"

A: "Hayır—Açıklık, en üst düzeyde yeniden kullanım için gerekli ancak yeterli olmayan bir koşuldur. Veriler açık olmasının yanı sıra FAIR olmalıdır."

Q: "FAIR ilkeleri farklı paydaşlar/hedef kitleler için ne anlama gelir?"

A: "Bu tartışma için harika bir konu!"

Engel: Araştırmacılar verilerini paylaşmak için gönülsüz olabilirler çünkü kendileri verileri en üst düzeyde fayda elde etmeden başkalarının yeniden kullanmasından ya da verileri tam olarak anlayamayabileceğinden ve bu nedenle kötüye kullanabileceğinden korkarlar.

\(öneri\) A: Verilerinizi keşfedilebilir kılmak için üst verilerle birlikte paylaşabilir, ancak önce kendi makale\(lerinizi\) yayımlayabileceğinizden emin olmak için veriye bir ambargo süresi koyabilirsiniz.

Q: "Verilerimi FAIR yapmam çok fazla ek iş yaratır mı?"

A: "Tam olarak değil! Verilerin FAIR yapılması sadece bireysel olarak araştırmacıların değil tüm grubun sorumluluğundadır. Verilerinizin FAIR olduğundan emin olmak için en iyi yol bir Veri Yönetim Planı hazırlayarak herşeyi önceden planlamaktır. Veri toplama ve veri işleme esnasında bir veri havuzu tarafından önerilen disiplinin standartlarına ya da önlemlere uyun.

Q: "Verilerimi paylaşmak istiyorum. Nasıl lisanslamalıyım?"

A: "Bu güzel bir soru. Öncelikle verinin sahibinin kim olduğunu düşünün. Bir araştırma fonlayıcı mı ya da çalıştığınız kurum mu? Sonrasında, yazarlığı düşünün. Uygun bir lisans kullanmak, verilerinizi yeniden kullanılanilir kılmak için çok önemlidir. Lisanslama hakkında daha fazla bilgi için lütfen bkz. [6. Açık Lisanslama ve Dosya Formatları](https://github.com/Open-Science-Training-Handbook/-Open-Science-TrainingHandbook_TUR/blob/master/02OpenScienceBasics/06OpenLicensingAndFileFormats.md).

Q: "Verilerimi doğrudan erişilebilir hale getiremiyorum—rahatça paylaşılamayacak kadar büyük / gizlilik konularıyla ilgili kısıtlamalar söz konusu. Ne yapmalıyım?"

A: "Alana özgü veri havuzlarındaki uzmanlarla, verilerinizi keşfedilebilir ve erişilebilir hale getirmek için uygun talimatların nasıl sağlanacağı konusunda konuşmalısınız."


## <img src="/Images/Icons/output.png" width="150" height="150" />
### Öğrenme çıktıları

1. Açık verinin özelliklerini ve özellikle FAIR ilkelerini anlamak.

3. Açık verilerin lehine ve aleyhine olan bazı argümanlara aşina olmak.

3. Hassas verileri ve opFAIR verileri ayırt edebilme ve adresleyebilme; bu iki kategori mutlaka uyumsuz değildir.

4. Bir veri setini, açık paylaşıma uygun \(telif ile korunmayan format\), FAIR ilkelerinin standartlarını karşılayan ve uygun üst veri sağlayarak en üst düzeyde erişilebilirlik, şeffaflık ve yeniden kullanım için tasarlanmış bir veri setine dönüştürebilmek.

6. Ham ve işlenmiş \(veya temizlenmiş\) veriler arasındaki farkı ve sürüm etiketlerinin önemini bilmek.

6. En üst düzeyde yeniden kullanım için yaygın kullanılan dosya formatlarını ve topluluk standartlarını öğrenmek.

7. Bir veri yönetim planı yazabilmek.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Ek okuma listesi
* Averkamp ve diğerleri. (2018). Data packaging guide. [github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md).

* Barend ve diğerleri. (2017). Cloudy, increasingly FAIR; revisiting the FAIR Data guiding principles for the European Open Science Cloud. [doi.org/10.3233/ISU-170824](https://doi.org/10.3233/ISU-170824)

* Brase ve diğerleri. (2009). Approach for a joint global registration agency for research data. [doi.org/10.3233/ISU-2009-0595](https://doi.org/10.3233/ISU-2009-0595)

* Candela ve diğerleri. (2015). Data journals: A survey. [doi.org/10.1002/asi.23358](https://doi.org/10.1002/asi.23358)

* CESSDA Training Working Group (2017-2018a). CESSDA Data Management Expert Guide. Bergen, Norway: CESSDA ERIC. [cessda.eu/DMGuide](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management)

* CESSDA Training Working Group (2017-2018b). CESSDA Data Management Expert Guide: Citing your data. Bergen, Norway: CESSDA ERIC.[cessda.eu/DMGuide/citingdata](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Publishing-with-CESSDA-archives/Citing-your-data)

* FAIRsharing.org (2016). FAIR. The FAIR Principles. [doi.org/10.25504/FAIRsharing.WWI10U](https://doi.org/10.25504/FAIRsharing.WWI10U)

* Force 11 (n.y.). Guiding principles for Findable, Accessible, Interoperable, and Re-usable data publishing Version B1.0. [force11.org/fairprinciples](https://www.force11.org/fairprinciples)

* Gorgolewski ve diğerleri. (2013). Making data sharing count: a publication-based solution. [doi.org/10.3389/fnins.2013.00009](https://doi.org/10.3389/fnins.2013.00009)

* Kratz ve Strasser (2015). Making Data Count. [doi.org/10.1038/sdata.2015.39](https://www.nature.com/articles/sdata201539) 

* Piwowar ve Vision (2013). Data reuse and the open data citation advantage. [doi.org/10.7717/peerj.175](https://doi.org/10.7717/peerj.175)

* Wilkinson ve diğerleri. (2016). The FAIR Guiding Principles for scientific data management and stewardship. [doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)

* Wilkinson ve diğerleri. (2918). A design framework and exemplar metrics for FAIRness. [doi.org/10.1038/sdata.2018.118](https://doi.org/10.1038/sdata.2018.118)


#### Girişimler ve projeler

* DANS GDPR DataTags. [zingtree.com](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)

* FAIR Metrics. [fairmetrics.org](http://fairmetrics.org/)

* GO FAIR Initiative. [go-fair.org](https://www.go-fair.org/)

*  The FAIR Data Principles explained. [go-fair.org](https://www.go-fair.org/fair-principles/)

*  5★ OPEN DATA. [5stardata.info](http://5stardata.info/en/)


