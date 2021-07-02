## <img src="/Images/Icons/open_data.png" width="200" height="200" />
## 2. Açık Araştırma Verileri ve Materyaller

### Nedir?

Açık araştırma verileri, akademik araştırma ve öğretim amaçlarının yanı sıra başka amaçlar için de serbestçe erişilebilen, yeniden kullanılabilen, düzenlenebilen ve dağıtılabilen verilerdir. İdeal olarak, açık verilerin yeniden kullanım veya dağıtımı konusunda herhangi bir kısıtlama yoktur ve buna uygun şekilde lisanslanmışlardır. İnsan deneklerin kimliğini korumak gibi istisnai durumlarda özel veya sınırlı erişim kısıtlamaları belirlenir. Verileri açık bir şekilde paylaşmak, araştırmaların doğrulanması ve tekrarlanabilirliği için temel oluşturarak verilerin incelenmesini sağlar ve daha kapsamlı işbirlikleri için bir yol açar. Açık veriler, en fazla, atıf yapma (attribute) ve aynı lisansla paylaşma (sharealike) şartına tabi olabilir \(bkz. [Açık Veri El Kitabı](http://opendatahandbook.org/guide/en/what-is-open-data)\).

## <img src="/Images/Icons/data2.png" width="150" height="150" />
### Gerekçe

Birçok araştırma projesinin genellikle en değerli çıktısı olan araştırma verileri, bilimsel araştırmaya dayanak oluşturan ve teorik veya uygulamalı bulguların türetilmesini sağlayan birincil kaynak olarak kullanılır. Bulguların/çalışmaların yinelenebilir ya da en azından tekrarlanabilir ya da farklı şekillerde yeniden kullanılabilir \(bkz. [Tekrarlanabilir Araştırma ve Veri Analizi](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md)\) hale getirmek için en iyi uygulama önerisi araştırma verilerinin, hassas veya kişiye özel verilerle ilgili etik, ticari ve gizlilik kısıtlamalarını dikkate alarak mümkün olduğunca açık ve [FAIR](https://www.force11.org/fairprinciples) ilkelerine uyumlu olmasıdır.

## <img src="/Images/Icons/finish.png" width="150" height="150" />

### Öğrenme hedefleri

1. Başkalarının alternatif yöntemlerle anlamasını, çoğaltmasını ve yeniden kullanmasını sağlamak için uygun paketleme ve dokümantasyon da dahil olmak üzere açık ve FAIR araştırma verilerinin temel özelliklerini ve ilkelerini anlamak.

2. Hassas olarak kabul edilebilecek veri türleri ve bunların açık bir şekilde paylaşılmasına ilişkin kısıtlamalar veya engeller hakkında bilgi.

3. Uygun veri yönetimi ve üst verilerle bir veri yönetimi planında gereken tedbirleri alarak ‘kapalı’ bir veri setini ‘açık’ hale dönüştürebilmek 

4. Veri yönetim planını kullanabilmek ve araştırma sonuçlarınızı hassas veri içeriyor olsa dahi keşfedilebilir ve erişilebilir hale getirebilmek.

5. Farklı veri türlerini açıkça paylaşmanın artılarını ve eksilerini anlamak \(örneğin, gizlilik, hassasiyet, kimlik gizleme, aracılı erişim\)Understand the pros and cons of openly sharing different types of data \(e.g., privacy, sensitivity, de-identification, mediated access\).

6. Araştırma verilerinin sürdürülebilir şekilde arşivlenmesi için uygun üst verilerin önemini anlamak.

7. Araştırma verilerinin paylaşımı için temel iş akışlarını ve araçları anlamak.

### Temel unsurlar
## <img src="/Images/Icons/brain.png" width="150" height="150" /><img src="/Images/Icons/gears.png" width="150" height="150" />
#### Bilgi ve Beceriler
##### FAIR ilkeleri
2014 yılında, araştırma verilerinin yeniden kullanılabilirliğini optimize etmek için [FAIR Veri İlkeleri](https://www.force11.org/group/fairgroup/fairprinciples) adında bir dizi temel ilke taslağı oluşturulmuştur. Bu ilkeler, verilerin veya herhangi bir dijital nesnenin keşfedilebilir (**F**indable), erişilebilir (**A**ccessible), birlikte çalışabilir (**I**nteroperable) ve yeniden kullanılabilir (**R**e-usable) olduğundan emin olmak için topluluk tarafından geliştirilmiş bir dizi yönergeyi ve en iyi uygulamaları temsil ederler:

**Keşfedilebilir:** Verileri yeniden kullanılabilir hale getirmek için yapılması gereken ilk şey, onları bulma imkanını yaratmaktır. Hem insanlar hem de bilgisayarlar çin verilerin ve üst verilerin bulunması kolay olmalıdır. Veri setlerinin ve hizmetlerin otomatik ve güvenilir şekilde keşfi makinaca okunabilir sabit/kalıcı tanımlayıcıların (persistent identifiers - PIDs) ve üst verilerin olmasına bağlıdır.  

**Erişilebilir:** \(Üst\) veriler, mümkünse doğrulama ve yetkilendirme içeren standart ve açık bir iletişim protokolü kullanılarak tanımlayıcıları tarafından çekilebilir olmalıdır. Ayrıca, verilerin artık mevcut olmadığı durumlarda dahi üst verilere erişilebilir olmalıdır.

**Birlikte çalışılabilir:** Veriler, diğer veriler veya araçlarla birleştirilip kullanılabilir olmalıdır. Bu nedenle verilerin formatı, diğer veri kayıtları da dahil olmak üzere çeşitli araçlar için açık ve yorumlanabilir olmalıdır. Birlikte çalışabilirlik kavramı hem veri hem de meta veri düzeyinde geçerlidir. Örneğin, \(üst\)veriler için FAIR ilkelerine uyumlu sözlükler (vocabularies) kullanılmalıdır.

**Yeniden kullanılabilir:** FAIR, en nihayetinde, verilerin yeniden kullanımını optimize etmeyi amaçlar. Bunu başarmak için üst veriler ve veriler, farklı ortamlarda çoğaltılabilmeleri ve/veya birleştirilebilmeleri için iyi tanımlanmış olmalıdır. Ayrıca, üst verilerin yeniden kullanım durumu açık/net ve erişilebilir lisanslar ile belirtilmelidir.

Bilim insanlarına odaklanan hakemlik girişimlerinden farklı olarak, FAIR ilkeleri, insanlar tarafından yeniden kullanımını desteklemenin yanı sıra, makinelerin verileri veya herhangi bir dijital nesneyi otomatik olarak bulma ve kullanma yeteneğini geliştirmenin özellikle üzerinde durmaktadır. FAIR ilkeleri standartlar değil, yol gösterici ilkelerdir. FAIR verileri en üst düzeyde yeniden kullanılabilir hale getirmek için gereken nitelikleri ve tutumları tanımlar \(örneğin, tanımlama, atıf\). Bu niteliklere farklı standartlarla ulaşılabilir.

![](/Images/02%20Open%20Science%20Basics/02_open_research_data_material.png)

##### Veri yayımlama

Çoğu araştırmacı, araştırma makalelerinin ve kitaplarının Açık Erişim yayıncılığına az çok aşinadır \(bkz. Bölüm 5\). Daha yakın zamanlarda ve yukarıda belirtilen nedenlerden dolayı veri yayımlama giderek artan bir ilgi görmeye başlamıştır. Gittikçe daha fazla fon sağlayıcı, finanse ettikleri araştırma projeleri kapsamında üretilen verilerin keşfedilebilir, erişilebilir ve mümkün olduğunca açık olmasını beklemektedir.

Araştırma verilerini erişilebilir yapmanın aşağıdakileri de içeren birçok farklı yolu vardır\([Wikipedia](https://en.wikipedia.org/wiki/Data_publishing)\):

* Verilerin, [araştırma makalesi](https://en.wikipedia.org/wiki/Research_article) ile ilişkili ek materyal olarak, genellikle makalenin yayıncısı tarafından tutulan veri dosyaları ile birlikte yayımlanması.

* Verileri, indirilebilecek dosyalarla birlikte, kamuya açık bir web sitesinde tutma.

* Verileri, veri yayımlamayı desteklemek için oluşturulmuş bir veri havuzunda depolama. Örneğin, [Dataverse](https://en.wikipedia.org/wiki/Dataverse), [Dryad](https://en.wikipedia.org/wiki/Dryad_(repository)), [figshare](https://en.wikipedia.org/wiki/Figshare), [Zenodo](https://en.wikipedia.org/wiki/Zenodo).

* Araştırmacılara verilerini depolarken ek destek sağlayabilecek çok sayıda genel ve alana veya konuya özel veri havuzu mevcuttur.

* Veri seti ile ilgili, bir dergide veya veri makalelerini (data paper) desteklemeye ayrılmış bir veri dergisinde ön baskı olarak yayımlanabilecek bir veri makalesi (data paper) yayımlamak. Veriler dergi tarafından veya bir veri havuzunda ayrı olarak tutulabilir. Veri dergilerine örnek olarak \(SpringerNature'ın\) [Scientific Data](https://www.nature.com/sdata/) dergisi ile \(CODATA'nın\) [Data Science Journal](http://www.codata.org/publications/data-science-journal) adlı dergisi örnek verilebilir. Veri dergilerinin daha kapsamlı bir değerlendirmesi için bkz. [Candela et al](https://doi.org/10.1002%2Fasi.23358).

CESSDA ERIC [Veri Yönetimi konusunda uzman tur rehberi](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Data-publishing-routes), farklı veri yayımlama yollarının artıları ve eksileri ile ilgili genel bir bakış sağlamaktadır. Bazen fon sağlayıcınız ya da diğer bir harici taraf belli bir veri havuzunu kullanmanızı gerektirebilir. Seçim konusunda özgürseniz, [OpenAIRE önerilerindeki](https://www.openaire.eu/opendatapilot-repository-guide) tercih sırasını göz önünde bulundurabilirsiniz:

1. Verileri kendi disiplininizde tanınan standartlara göre korumak için araştırma alanınız için önceden kurulmuş harici bir veri arşivi veya havuzu kullanın.

2. Eğer mevcutsa, kurumsal bir araştırma veri havuzu ya da araştırma grubunuzun varolan veri yönetimi olanaklarını kullanın.

3. [Dataverse](https://dataverse.org/), [Dryad](https://datadryad.org/pages/faq#depositing-cost), [figshare](https://figshare.com/) ya da [Zenodo](https://zenodo.org/)gibi ücretsiz bir veri havuzu kullanın.

4. [re3data](https://www.re3data.org/)'daki diğer veri havuzlarını araştırın. re3data'da FAIR ilkelerini kapsayan tek bir filtreleme seçeneği yoktur, ancak filtreleme şu seçeneklerini göz önünde bulundurmak FAIR uyumlu veri havuzlarını bulmanıza yardımcı olacaktır: erişim kategorileri, veri kullanım lisansları, güvenilir veri havuzları \(sertifika ile ya da doğrudan arşiv standarlarına bağlı kalarak\) ve havuzun verilere kalıcı tanımlayıcı \(persistent identifier - PID\) verip vermediği. Dikkate alınması gereken bir diğer husus havuzun farklı dosya sürümleri oluşturmayı (versioning) destekleyip desteklemediğidir.

## <img src="/Images/Icons/archive.png" width="150" height="150" />
Araştırma veri yönetim planınızda verilerinizi nerede depolayacağınızı ve yayımlayacağınızı düşünmüş olmalısınız. CESSDA, gözününde bulundurulması önerilen bazı uygulamaya yönelik sorular sunmaktadır. Örneğin: For example: Hangi veriler, ilişkili üst veriler, dokümanlar ve kodlar depolanacak? Verilerin ne kadar süre saklanması gerekiyor? Veriler ne kadar süreyle yeniden kullanılabilir durumda kalmalıdır? Veriler nasıl kullanıma sunulacak? Hangi erişim kategorisini seçeceksiniz? Daha fazla soru için bkz. [Adapt your DMP: part 6](https://www.cessda.eu/Research-Infrastructure/Training/Expert-Tour-Guide-on-Data-Management/6.-Archive-Publish/Adapt-your-DMP-part-6). Diğer taraftan, seçilen bir veri havuzunun araştırmanız ve fon sağlayıcınız için gereklilikleri karşılayıp karşılamadığını kontrol etmeyi unutmayın. Bazı veri havuzları halihazırda güvenilir olduklarını ve Temel Güvenilir Veri Havuzu Gereksinimlerini karşıladıklarını onaylayan CoreTrustSeal gibi sertifikaları almışlardır. Bazı alana özgü veri havuzlarının, yalnızca yeniden kullanım potansiyeli olan ve herkese açık olarak paylaşılabilen yüksek kalitedeki verileri kabul edeceğini belirtmekte fayda vardır.

Verilerinizi yayımlamanın birçok yolu olduğundan, bir veri setinin yayın olarak "sayılması" için bir makaleye benzer bir yayın sürecini izlemesi gerektiğine \([Brase et al., 2009](https://doi.org/10.3233/ISU-2009-0595)\) ve:

* Üst verilerle birlikte uygun şekilde dokümante edilmiş;

* Nitelik yönünden gözden geçirilmiş, örneğin çalışmanın içeriği, metodoloji, ilgililik, yasal uygunluk ve materyallerin dokümantasyonu;

* Kataloglarda \(ya da veri tabanlarında\) aranabilir ve keşfedilebilir;

* Makalelerde atıf yapılabilir olmalıdır.

## <img src="/Images/Icons/metadata.png" width="150" height="150" />
##### Veri atıfı

Veri atıf hizmetleri/faaliyetleri, araştırma topluluklarının araştırma verilerini \(ve genellikle diğer araştırma objelerini\) güvenle keşfetmesine, tanımlamasına ve bunlara atıf yapmasına yardımcı olur. Bu genellikle, digital nesne tanımlayıcıları Digital Object Identifiers \(Digital Object Identifiers - DOIs\) ve veriye eşlik eden üst verilerin [DataCite](https://www.datacite.org) gibi hizmetler aracılığıyla oluşturulması ve tahsisini/atanmasını içerir ve araştırma iş akışları ve standartlar ile entegre edilebilir.   Bu, gelişmekte olan bir alandır ve makalelerde verilere uygun şekilde atıf yapmanın önemini dergi yayıncılarına iletmek ve aynı zamanda araştırma makalelerinin araştırmanın verileri ile ilişkilendirilmesinin sağlanması gibi konuları kapsar. Bu sayede, atıf yapılabilir veriler bilimsel iletişim sürecine yerinde katkılar haline gelir ve veri paylaşımını tanıyan ve ödüllendiren yeni ölçevler ve yayın modellerinin önünü açmaya yardımcı olabilir.

Veri atıfı için iyi uygulamaya yönelik ilk adım  olarak, FORCE11'in Veri Atıf Sentezi Grubu (Data Citation Synthesis Group), hem araştırmacıları hem de veri hizmet sağlayıcılarını hedef alan [Veri Atıf İlkeleri Ortak Bildirisini - Joint Declaration of Data Citation Principles](https://doi.org/10.25490/a97f-egyk) önermiştir. Bu ilkelere bağlı kalarak, veri havuzları genellikle araştırmacılara belirli bir veri setine atıfta bulunurken kullanabilecekleri bir dayanak/örnek sunar.

## <img src="/Images/Icons/database.png" width="150" height="150" />
##### Veri paketleme

Veri paketleri,  verilere eşlik eden veri dosyalarının tanımlanması ve paylaşılmasına yönelik paketler olup ve tipik olarak bir veri setinin özelliklerini ve içeriğini açıklayan bir üst veri dosyası içerirler. Veri paketleri, veri oluşturma komut dosyaları veya metin belgeleri gibi ilgili içerik dosyaların yanı sıra veri setini oluşturma ile ilgili bilgileri, provenans, verinin boyutu, formatı/türü, alan tanımları gibi kaynak, boyut, biçim türü, alan tanımları gibi hususları içerebilir. [Veri Paketleme Rehberinde](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md) belirtildiği üzere:

* Veriler sonsuza dek yaşar: Veri setleri ortaya çıkış amaçlarından daha uzun ömürlüdür. context
* Verilerin sınırlılıkları, bir kütüphane kataloğu gibi asıl ortamları içinde göze çarpabilir, ancak veriler oluşturuldukları kullanım amacının dışına çıktığında belirgin olmayabilir.

* Veri tek başına olamaz: Verinin içeriği ve provenansı hakkındaki bilgi--nasıl ve neden oluşturulduğu, hangi gerçek dünya nesneleri ve kavramlarını temsil ettiği, değerler üzerindeki kısıtlamalar--kullanıcıların veriyi sorumlu bir şekilde yorumlamalarına yardımcı olmak için gereklidir.

* Veri setleri ile ilgili üst verileri standart, makinaca okuanbilir şekilde yapılandırmak verilerin tanıtımı, paylaşılabilirliğini ve yeniden kullanımını teşvik eder. 

## <img src="/Images/Icons/privacy.png" width="150" height="150" />
##### Hassas ve kişisel verilerin paylaşılması

With appropriate data management planning much sensitive and proprietary data can be shared, reused, and FAIR. The metadata can almost always be shared. Guidance and best practices for sharing sensitive data are necessarily region-specific because of differing regulations \(see for example UKDS’[Companion material for Managing and Sharing Research Data handbook](https://www.ukdataservice.ac.uk/manage-data/handbook)\). [International Association for Social Science Information Services and Technology](http://www.iassistdata.org/resources/data-management/best-practices) keeps a list of international guidance in data management that is a good starting point. There are several approaches and initiatives to help researchers achieve this. [DCC’s DMPonline tool](http://www.dcc.ac.uk/dmponline) includes a number of templates for funders. [The CESSDA Expert Tour Guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection) provides information and practical examples on how to share personal data and on copyright and database issues across the European countries. The Tour Guide also gives an overview on the impact of the GDPR which will harmonize personal data legislation in Europe \(May 2018\), and provides an updated overview on [EU diversity on data protection](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection).[ ](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection)

###### Veri simsarlığı

Veri simsarları Data brokers are knowledgeable, independent parties who act as data stewards for sensitive data. Researchers can transfer their sensitive data and jurisdiction over access to that data to the broker. This is especially common with patient-level data from clinical studies. Brokers provide a level of independence in the evaluation of whose data requests are scientifically valid and will not violate the privacy of research participants. Examples of data brokers include [The YODA Project](http://yoda.yale.edu/), [ClinicalStudyDataRequest.com](https://www.clinicalstudydatarequest.com/), [National Sleep Research Resource](https://sleepdata.org/) and [Supporting Open Access for Researchers \(SOAR\)](https://dcri.org/our-approach/data-sharing/).

## <img src="/Images/Icons/data.png" width="150" height="150" />
##### Analiz portalları
Analysis portals are platforms that allow approved analysis of data without allowing full access \(viewing or downloading\) or controlling where and who gets access. Some data brokers also use analysis portals. Analysis portals control what additional datasets can be pooled with the sensitive data as well as what analyses can be run to ensure that personal information is not revealed during reanalysis. Examples of virtual analysis portals include [Project Data Sphere](https://www.projectdatasphere.org/projectdatasphere/html/home), [Vivli](http://vivli.org/), [RAIRD](http://raird.no/), [Corpuscle](http://clarino.uib.no/korpuskel/page), and [INESS](http://clarino.uib.no/iness/page).

Social science and other researchers with sensitive data use a single-site analysis portal that can be accessed only under controlled regime. Approved researchers can access the data on-site, in a safe room, for scientific purposes. However, the metadata describing the data should be openly available and adhering to the FAIR principles.

##### Kimliği gizlenmiş ve yapay veriler De-identified and synthetic data

Many datasets containing participant-level private information can be shared once the dataset has been de-identified \(Safe Harbor method\) or a expert has determined that the dataset is not individually identifiable \(Expert Determination method\). Consult with your Research Ethics Board / Institutional Review Board to learn how to do this with your data. We also recommend [the CESSDA Expert Tour Guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection), which provides information and practical examples on how to share personal data. However, some datasets cannot be safely de-identified and shared. Researchers can still improve the openness of research on such data by creating and sharing synthetic data. Synthetic data is similar in structure, content, and distribution to the real data and aims to attain "analytic validity": statistical analysis will return the same results for the synthetic data as the real data. The United States Census Bureau, for example, uses [synthetic data and analysis portals](https://census.gov/content/dam/Census/programs-surveys/sipp/methodology/SSBdescribe_nontechnical.pdf) in combination to allow reuse of highly sensitive data.

###### Veri Etiketleri

[DataTags](https://datatags.org/) is a framework designed to enable computer-assisted assessments of the legal, contractual, and policy restrictions that govern data sharing decisions. The DataTags system asks a user a series of questions to elicit the key properties of a given dataset and applies inference rules to determine which laws, contracts, and best practices are applicable. The output is a set of recommended DataTags, or simple, iconic labels that represent a human-readable and machine-actionable data policy, and a license agreement that is tailored to the individual dataset. The DataTags system is being designed to integrate with data repository software, and it will also operate as a standalone tool. DataTags is being developed at Harvard University. In Europe, DANS is working on adjusting DataTags to European legislation / General Data Protection Regulation \([GDPR](https://www.eugdpr.org/)\) \(cf. [DANS GDPR DataTags](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)\).

As mentioned above, the ultimate goal of data sharing your research data is to make them maximally reusable. To that end, before sharing your data you should manage them according to best practice. This includes, i.a., documentation and the choice of open file formats and licenses. You can read more about these issues in [Section 4: Reproducible Research and Data Analysis](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md) as well as [Section 6: Open Licensing and File Formats](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/06OpenLicensingAndFileFormats.md).


## <img src="/Images/Icons/usb.png" width="150" height="150" />
##### Açık Materyaller

In addition to data sharing, the openness of research relies on sharing of materials. What materials researchers use is discipline-specific and sometimes unique to a lab. Below are examples of materials you can share, although always confer with peers in your discipline to identify which repositories are used. When you have materials, data, and publications from the same research project shared in different repositories, cross-reference them with a link and a unique identifier so they can be easily located.

###### Reagents

A reagents is a substance, compound or mixture that can be added to a system in order to create a chemical or other reaction. Reagents can be deposited with repositories like [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/), and [ATCC](https://www.atcc.org/) to make them easily accessible to other researchers. License your materials so they can be reused by other researchers.

###### Protocoller

A protocol describes a formal or official record of scientific experimental observations in a structured format. Deposit virtual protocols for citation, adaptation, and reuse using [Protocols.](https://www.protocols.io/)[io](https://www.protocols.io/).

###### Notebooks, containers, software, and hardware

Reproducible analysis is aided by the use of literate programming, container technology, and virtualization. In addition to sharing your code and data, also share your Jupyter notebooks, Docker images, or other analysis materials or software dependencies. Share notebooks with Open services such as [mybinder](http://mybinder.org) that allow for public viewing and execution of the entire notebook on shared resources. Containers and notebooks can be shared with [Rocker](https://arxiv.org/abs/1710.03675) or [Code Ocean](https://codeocean.com/). Software and hardware used in your research should be shared following best practices for documentation as outlined in [Section 3](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/03OpenResearchSoftwareAndOpenSource.md). Read-only protocols should be deposited in your disciplines registry such as [ClinicalTrials.gov](https://clinicaltrials.gov/) and [SocialScienceRegistry](https://www.socialscienceregistry.org/) or a general registry like [Open Science](https://osf.io/)[ Framework](https://osf.io/). Many journals, such as [Trials](https://trialsjournal.biomedcentral.com/), [JMIR Research Protocols](https://www.researchprotocols.org/), or [Bio-Protocol](https://bio-protocol.org/), will publish your protocol. Best practices for publishing your protocol open access are the same as publishing your report open access \(see [Section 5](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/05OpenAccessToPublishedResearchResults.md)\).


## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Sorular, engeller ve yaygın kavramsal yanılgılar

Q: "Is it sufficient to make my data openly available?"

A: "No—openness is a necessary but not sufficient condition for maximum reuse. Data have to be FAIR in addition to open."

Q: "What do the FAIR principles mean/imply for different stakeholders/audiences?"

A: "This is a great topic for discussion!"

Obstacle: Researchers may be reluctant to share their data because they are afraid that others will reuse them before they have extracted the maximum usage from them, or that others might not fully understand the data and therefore mis-use them.

\(suggested\) A: You may publish your data to make them findable with metadata, but set an embargo period on the data to make sure that you can publish your own article\(s\) first.

Q: "Is making my data FAIR a lot of extra work?"

A: "Not necessarily! Making data FAIR is not only the responsibility of the individual researchers but of the whole group. The best way to ensure that your data is FAIR is to create a Data Management Plan and plan everything beforehand. During the data collection and data processing follow the discipline standards and measures recommended by a repository.

Q: "I want to share my data. How should I license them?"

A: "That’s a good question. First of all think about who owns the data? A research funder or an institution that you work for. Then, think about authorship. Applying a suitable license to your data is crucial in order to make them reusable. For more information about licensing, please see [6. Open Licensing and File Formats](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/tree/master/02OpenScienceBasics/06OpenLicensingAndFileFormats).

Q: "I cannot make my data directly available—they are too large to share conveniently / have restrictions related to privacy issues. What should I do?"

A: "You should talk to experts in domain specific repositories on how to provide sufficient instructions to make your data findable and accessible."


## <img src="/Images/Icons/output.png" width="150" height="150" />
### Öğrenme çıktıları

1. Understand the characteristics of open data, and in particular the FAIR principles.

2. Be familiar with some of the arguments for and against open data.

3. Be able to differentiate and address sensitive data and opFAIR data; these two categories are not necessarily incompatible.

4. Be able to transform a dataset into one that is sufficient for open sharing \(non-proprietary format\), meets the standards of the FAIR principles, and is designed for maximized accessibility, transparency and re-use by providing sufficient metadata.

5. Know the difference between raw and processed \(or cleaned\) data, and the importance of version labels.

6. Know commonly used file formats and community standards for maximum re-usability.

7. Be able to write a data management plan.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Ek okuma listesi
* Averkamp et al. (2018). Data packaging guide. [github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md).

* Barend et al. (2017). Cloudy, increasingly FAIR; revisiting the FAIR Data guiding principles for the European Open Science Cloud. [doi.org/10.3233/ISU-170824](https://doi.org/10.3233/ISU-170824)

* Brase et al. (2009). Approach for a joint global registration agency for research data. [doi.org/10.3233/ISU-2009-0595](https://doi.org/10.3233/ISU-2009-0595)

* Candela et al. (2015). Data journals: A survey. [doi.org/10.1002/asi.23358](https://doi.org/10.1002/asi.23358)

* CESSDA Training Working Group (2017-2018a). CESSDA Data Management Expert Guide. Bergen, Norway: CESSDA ERIC. [cessda.eu/DMGuide](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management)

* CESSDA Training Working Group (2017-2018b). CESSDA Data Management Expert Guide: Citing your data. Bergen, Norway: CESSDA ERIC.[cessda.eu/DMGuide/citingdata](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Publishing-with-CESSDA-archives/Citing-your-data)

* FAIRsharing.org (2016). FAIR. The FAIR Principles. [doi.org/10.25504/FAIRsharing.WWI10U](https://doi.org/10.25504/FAIRsharing.WWI10U)

* Force 11 (n.y.). Guiding principles for Findable, Accessible, Interoperable, and Re-usable data publishing Version B1.0. [force11.org/fairprinciples](https://www.force11.org/fairprinciples)

* Gorgolewski et al. (2013). Making data sharing count: a publication-based solution. [doi.org/10.3389/fnins.2013.00009](https://doi.org/10.3389/fnins.2013.00009)

* Kratz and Strasser (2015). Making Data Count. [doi.org/10.1038/sdata.2015.39](https://www.nature.com/articles/sdata201539) 

* Piwowar and Vision (2013). Data reuse and the open data citation advantage. [doi.org/10.7717/peerj.175](https://doi.org/10.7717/peerj.175)

* Wilkinson et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship. [doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)

* Wilkinson et al. (2918). A design framework and exemplar metrics for FAIRness. [doi.org/10.1038/sdata.2018.118](https://doi.org/10.1038/sdata.2018.118)


#### Girişimler ve projeler

* DANS GDPR DataTags. [zingtree.com](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)

* FAIR Metrics. [fairmetrics.org](http://fairmetrics.org/)

* GO FAIR Initiative. [go-fair.org](https://www.go-fair.org/)

*  The FAIR Data Principles explained. [go-fair.org](https://www.go-fair.org/fair-principles/)

*  5★ OPEN DATA. [5stardata.info](http://5stardata.info/en/)


