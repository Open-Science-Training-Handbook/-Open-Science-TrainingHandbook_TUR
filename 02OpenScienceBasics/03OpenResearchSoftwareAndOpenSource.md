<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Açık Araştırma Yazılımları ve Açık Kaynak

### Nedir?

Açık araştırma yazılımları ya da açık kaynak araştırma yazılımları, analiz, simulasyon ve görselleştirme vb. için tüm kaynak kodlarının erişilebilir olduğu yazılımların kullanılması ve geliştirilmesi anlamına gelir. Aynı zamanda, [Open Source Definition](https://opensource.org/osd) tanımına göre, açık kaynak yazılımlar kaynak dosya biçiminde ve/veya derlenmiş biçimde \(ikinci durumda kaynak kodu erişilebilir olacak şekilde\) dağıtılmalı ve değişiklik, türetme ve yeniden dağıtıma izin veren bir lisans ile paylaşılmalıdır.

### Gerekçe

Modern araştırmalar yazılıma dayanır ve bu araştırmalar üzerine inşa edilmiş—ya da türetilmiş—yazılımın ardındaki tam kaynak koduna erişimi gerektirir \([Barnes, 2010](https://doi.org/10/cj8t6n); [Morin ve diğerleri, 2012](https://doi.org/10/m5t); [Ince ve diğerleri, 2012](https://doi.org/10/hqg); [Prins ve diğerleri, 2015](https://doi.org/10/f3mn4p); [Lowndes ve diğerleri, 2018](https://doi.org/10/gc4jb3)\). Buckheit ve Donoho'nun Jon Claerbout'tan alıntı yaparak belirttiği gibi, ‘‘Hesaplamaya dayanan bir sonuçla ilgili bir makale reklamdır, bilim değil. Asıl bilim, sonucu üreten tam yazılım ortamı, kod ve verilerdir’’ \([Buckheit ve Donoho, 1995](https://doi.org/10.1007/978-1-4612-2544-7_5)\). Araştırma yazılımlarının kaynak koduna açık erişim, araştırmanın etkisini de artırır \([Vandewalle, 2012](https://doi.org/10/gc5sjp)\).

Araştırma için kullanılan yazılımların paylaşılması \(doğası gereği hesaplamalı veya herhangi bir yazılım tabanlı analize/yoruma dayalı olsun olmasın\) tekrarlanabilirlik için yeterli olmasa da gerekli bir koşuldur. Bunun nedeni, yazılımı doğal dil kullanarak, örneğin bir kağıtta tam olarak tanımlamaya çalışırken ortaya çıkan kaçınılmaz belirsizliktir  \([Ince ve diğerleri, 2012](https://doi.org/10/hqg)\). Ayrıca, \(pek çoğu olmasa da\) çoğu yazılım programı tespit edilmemiş hatalar içerebilir \([Soergel, 2015](https://doi.org/10/gc5sjg)\), bu nedenle yazılımın "mükemmel" bir yazılı açıklaması dahi tüm sonuçları açıklayamayabilir.

Tekrarlanabilirliğe ek olarak, yazılımı açık bir şekilde paylaşmak, geliştiricilerin çabaları karşılıdığında doğrudan atıf \([Smith ve diğerleri, 2016] ya da [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) veya [Journal of Open Source Software](http://joss.theoj.org) gibi dergilerde yayımlanmış yazılım meta-makaleleri (software meta-articles) aracılığyla \([Smith ve diğerleri, 2018](https://doi.org/10/gc5sjf)\) kariyer kredisi almalarına olanak sağlar. Neil Chue Hong, yazılım makaleleri yayımlayan maintains a [birçok alana özgü derginin listesini](https://www.software.ac.uk/which-journals-should-i-publish-my-software) tutmaktadır.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Öğrenme hedefleri

1. Açık yazılımların özelliklerini öğrenmek; açık yazılımların lehine ve aleyhine olan etik, yasal, ekonomik ve araştırma etkisi argümanlarını anlamak ve açık kodların kalite koşullarını daha iyi anlamak.

2. Mevcut açık yazılımları nasıl kullanacağını ve uygun şekilde nasıl niteleyeceğini \(atıf yapacağını\) öğrenmek.

3. Araştırma kodlarını açık bir biçimde paylaşamk için yaygın araç ve hizmetleri nasıl kullanacağını öğrenmek.

4. Yazılımı için uygun lisansı seçebilmek ve izin veren ve izin vermeyen lisanslar arasındaki farkı anlayabilmek.

### Temel unsurlar

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Bilgi

Yazılım, araştırma veya başka konularda açık paylaşımı ve işbirliğini destekleyen birçok farklı platform vardır. Öncelikle, mevcut araştırma yazılımının açıklığını değerlendiirmek için şu kontrol listesini kullanabiilirsiniz:

* Yazılım indirilebilir ve yüklenebilir/kurulabilir mi?

* Yazılım farklı platformlara kolayca kurulabilir mi?

* Yazılımın kullanım şartları var mı? 

* Kaynak kodu inceleme/kontrol için mevcut mu?

* Kaynak kodunun tüm geçmişi herkesçe erişilebilir bir sürüm geçmişi (version history) ile inceleme/kontrol için mevcut mu?

* Yazılım gereklilikleri \(donanım ve yazılım\) açık bir şekilde tanımlanıyor mu? Gereklilikleri temin etmek ve kullanmak için gereken çaba maakul ölçüde az mı?

Bu nitelikler, [Açık Kaynak Tanımı](https://opensource.org/osd) ile ilgilidir ve bunun üzerine inşa edilmiştir.

[GitHub](www.github.com) sürüm kontrolüne (belirli bir yazılım parçasındaki değişikliklerin yönetimi ve genel takibi) olanak sağlayan popüler bir yazılımdır. Services such as [GitHub](www.github.com), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/) gibi hizmetler ve diğerleri araştırma yazılımını sürdürmek, paylaşmak ve üzerinde işbirliği yapmak için kullanılabilecek uzaktan depolama hizmetlerinin yanı sıra geliştirilen araca bir arayüz sağlar. Github, bir araç olarak oldukça yaygındır ve bir başlangıç öğrenme eğrisine sahip olmasına rağmen, açık ve tekrarlanabilir bir araştırma iş akışı oluşturmak için çok değerli olduğu kanıtlanmıştır.

Araştırma yazılımının Github üzerinde olması işin yalnızca ilk adımıdır; DOI gibi yazılım ile ilişkilendirilmiş, yayınlanmış ve sabit bir tanımlayıcısının olması eşit düzeyde önem taşımaktadır. DOI'yi GitHub ile ilişkilendirmenin birçok yolu bulunmaktadır; [Figshare](https://figshare.com/) gibi yazılım arşivlemek ve DOI almak için başka havuzlar olmasına rağmen, bu iş için en kolay yol [Zenodo](www.https://zenodo.org/) kullanmaktır \([OpenAIRE](https://www.openaire.eu/) ve [CERN](https://home.cern/) tarafından oluşturulmuş ücretsiz, kapsayıcı bir havuz\). Zenodo, yazılımı arşivlemek ve geliştiriciler GitHub'da resmi bir yayın yaptığında bir DOI sağlamak için [GitHub ile entegre çalışır](https://guides.github.com/activities/citable-code/).

Herkesle paylaşılmış yazılımlar uygun bir lisansla lisanslanmadıkça gerçek anlamda açık kaynak değildir, çünkü yazılımın \(diğer yaratıcı çalışmalar gibi\), kimsenin kullanamayacağı, kopyalayamayacağı, dağıtamayacağı ve değiştiremeyeceği anlamına gelen yaratıcısının münhasır telif hakkı kapsamında olduğu varsayılır \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(Kodunuzu herhangi bir kısıtlama olmaksızın tamamen paylaşmak istiyorsanız, [onu kamu malı olarak tahsis edebilirsiniz](https://choosealicense.com/licenses/#unlicense).\) Bunun yerine, diğer kişilerin kodlarınız ile ne yapmasına izin vermeyi \(veya ne yapmasını engellemeyi\) tercih ettiğinize göre yazılımınız için uygun bir lisans seçmelisiniz; [choosealicense.org](https://choosealicense.com) sitesi [mevcut veya popüler her açık kaynak lisansını](https://opensource.org/licenses) içermese de, lisanslar arasında ayrım yapmak için yararlı bir sitedir. Bir lisans seçtikten sonra, —yazar ad\(lar\)ı ve yılı içerecek şekilde düzenlenmiş— metni, düzmetin LİSANS dosyası (plaintext LICENSE file) biçiminde yazılım havuzuna koyun.

![](/Images/02%20Open%20Science%20Basics/02_open_research_software_open_source.png)

Yazılımı herhangi bir formda paylaşmanın hiç paylaşmamaktan daha iyi olmasına rağmen, yazılım ile ilgili dokümantasyonu eklerseniz yazılımınız daha fazla etkiye sahip olacak ve başkaları —ve gelecekteki kendiniz— tarafından daha kolay kullanılacaktır. Bu dokümantasyon, \(zaten açık olması gereken yaptığınız şeyden ziyade\) birşeyi **neden** yaptığınızı açıklayan koddaki faydalı yorumları, yazılımınızın ne yaptığını anlatan ve bazı faydalı bilgiler veren \(örneğin, nasıl yükleneceği, nasıl atıf yapılacağı, nasıl çalıştırılacağı, önemli ek yazılımlar gibi\) bilgilendirici bir BENİOKU dosyası, pratik bilgi sağlayan dokümanlar (tutorials)/örnekler ve/veya API dokümantasyonunu \(koddaki uygun şekilde biçimlendirilmiş komutlardan otomatik olarak oluşturulabilen\) içerebilir.

Eksik verilen ya da erişilemeyen ek yazılımlar ya da hesaplama ortamı ile ilgili yetersiz dokümantasyon yeniden kullanım ve tekrarlanabilirlik için çok yaygın engellerdir. Bu engelleri adreslemenin bir yolu, kodunuzu konteyner teknolojisini kullanarak hesaplama ortamınızla paylaşmaktır. Başkalarının analizlerinizi kolaylıkla çalıştırabilmesi için, konteynerler kodları ek gereklilikler ve hesaplama ortamı ile birlikte paketler. araştırmalarda kullanıan konteyner uygulama örnekleri arasında [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/) ve [Code Ocean](https://codeocean.com/) yer almaktadır.

Bir yazılım kullandığınızda — ister kendiniz yazmış oluni ister başkası yazıp kullanıma sunmuş olsun — tekrarlanabilirlik açısından uygun şekilde atıf yapmak \([Bölüm 4'te](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md) daha fazla tartışılmıştır; kısaca, kullanılan sürüm sonuçlarınızı ve yorumlarınızı değiştirebilir\) ve yazılımın geliştiricilerini kredi vermek önemlidir \([Niemeyer 2016](doi.org/10/gc5sjd), [Smith 2016](https://doi.org/10/bw3g)\). Yazılıma ne zaman atıf yapılacağı araştırmacı olarak size bağlı olmakla birlikte, yazılım bulgular, yorumlama ya da sonuçlar dahilinde her kullanıldığında atıf yapılmasını öneririz. _Kodlarınızın_ kolaycadaha önce anlatılan atıf yapılabilir hale gelmesini sağlamak için en iyi yol daha önce anlatılan GitHub–Zenodo entegrasyonunu kullanmak ve atanan DOI numarasını yazılımın BENİOKU dosyası gibi belirgin bir yerde, muhtemelen önerilen atıf formatı ile birlikte tutmaktır. Herhangi bir yazılıma atıf yaparken, en azından yazar ad\(lar\)ını, yazılım başlığını, sürüm numarasını ve tekil tanımlayıcıyı belirtmelisiniz \([Smith 2016](https://doi.org/10/bw3g)\). Başka birinin yazılımını kullandınız ve hali hazırda bir DOI varsa, bunu kolaylıkla yazılımı tanımlamak ve göstermek için kullanabilirsiniz; yazılım arşivlenmemişse, yazılımın bulunabileceği URL ve sürüm numarası ya da \(örneğin\) değişiklik/düzenleme numarasına (commit hash) yer verilebilir.

Ek olarak, daha karmaşık kavramlar arasında yazılımım otomatik olarak test edilmesi ve sürekli entegrasyonu, yazılımın ikili biçimlerde paketlenmesi ve çok kişiden oluşan açık kaynaklı projelerin kontrol ve yönetimi yer alır \(yani, etik davranış ilkeleri, yardımcı rehberler\). Bu konulardan bazıları [Scopatz and Huff \(2015\)](http://lilith.fisica.ufmg.br/~dickman/transfers/comp/textos/Effective%20Computation%20in%20Physics%20(Python).pdf) tarafından açıklanmıştır. Aynı zamanda [Wilson et al. \(2017\)](https://doi.org/10/gbkbwp) özellikle araştırma yazılımı geliştirme konusunda tavsiyeler içeren, bilimsel hesaplama için en iyi uygulamalara yönelik pratik bir rehber sunmaktadır.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Açık Kaynak Donanımı

Yukarıdaki açık kaynak ilkeleri donanıma kadar uzanır. Araştırmacılar, araştırmalarında genellikle özgürce erişilemeyen, yeniden kullanılamayan ve uyarlanamayan araçlar veya donanımlar kullanır. Bilimsel donanım, sıralama araçlarından ve mikroskoplardan özel test ekipmanlarına ve parçacık çarpıştırıcılarına kadar her şeyi içerir. Örneğin, Açık Bilim Donanım topluluğu \(Open Science Hardware community - OScH\), [Küresel Açık Bilim Yol Haritası (Global Open Science Hardware Roadmap)](http://openhardware.science/global-open-science-hardware-roadmap/) aracılığıyla, açık bilim hareketinin bilimsel araçları, donanımı ve araştırma altyapılarını içerecek şekilde yürütülmesine öncülük ediyor.

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Beceriler

* GitHub üzerinde bir havuz oluşturma ve Zenodo ile etkileşimini sağlama. Yazılımın ilk versiyonunu yayınlama.

* \(Örneğin\) [choosealicense](https://choosealicense.com) ya da [Open Source Initiative](https://opensource.org/licenses) platformlarını kullanarak bir yazılım lisansı seçme.

* Bir yazılım paketi için, BENİOKU dosyasını, açıklamaları ve örnekleri içeren dokümantasyon oluşturma.

* Bir yayın için kullanılan yazılıma uygun şekilde atıf yapma.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Sorular, engeller ve yaygın kavramsal yanılgılar

Q: "Yazılımımı paylaşamıyorum—çok karışık / iyi dokümantasyona sahip değil / iyi açıklamalar yapmadım!"

A: Dünyanın dört bir yanındaki araştırma yazılımı geliştiricileri bu his ile empati kuruyor—insanlar çok nadir olarak kodlarının herkesle paylaşmaya "hazır" ya da "tamamlanmış" olduğunu hissediyorlar. Ancak, [Barnes \(2010\)](https://doi.org/10/cj8t6n)'in belirttiği gibi, “eğer kodunuz iş görecek kadar iyiyse, yayınlamak için yeterince iyidir—ve kodu yayınlamak araştırmanıza ve alanınıza katkı sağlayacaktır.” Başka bir ifadeyle, bir çalışma yayımlamak ya da sonuçları raporlamak anlamında yazılımınız konusunda içiniz yeterince rahatsa, yazılım meslektaşlarınızla paylaşmak için yeterince geliştirilmiş demektir. \(Diğer taraftan bakınca, kodu paylaşamk konusunda rahat hissetmiyorsanız, bir yayında kullanılmadan önce muhtemelen daha fazla geliştirilmesi ya da test edilmesi gerekiyordur\). Ek olarak, kodlarınızı paylaşamk diğerlerinin geliştirmesine ve üzerine eklemesine olanak vererek daha büyük etki ve yeniliklere \(ve daha fazla atıfa!\) öncülük eder.

Q: "Birileri paylaştığım kodları alır ve kötü amaçlarla kullanır ya da kendisinin yazdığını iddia ederse ne olacak?"

A: Yazılımınız için uygun bir lisans seçmek, yazılımınızın başkalarınca herhangi bir şekilde kullanımına karşı korunmanıza yardımcı olacaktır; örneğin, yaygın [MIT Lisansı](https://choosealicense.com/licenses/mit/) sorumluluğun sınırlandırılmasını içerir ve hiçbir garanti verilmediğini belirtir. Eğer herhangi birisi sizin erişime açtığınız kodu kendisinin yazdığını iddia etmeye çalışırsa, önceki çalışmanızın kanıtı olarak deponuzdaki veya arşivlenmiş sürümlerinizdeki zaman damgalarını gösterebilirsiniz.

Q: "Kodumu çevrimiçi bir havuzda paylaşırsam, kullanıcı destek taleplerine maruz kalacağım."

A: Potansiyel kullanıcılar e-posta ya da \(örneğin\) çevrimiçi havuzlarda açılan konu başlıkları aracılığıyla sizden yardım isteyebilecek olsa da, istemiyor ya da yapamıyorsanız destek vermekle yükümlü değilsiniz. Uygun bir lisans, size bunun için yasal koruma dahi sağlar \(örneğin, [MIT Lisansının](https://choosealicense.com/licenses/mit/) garanti dışı maddesi\).

Yaygın kavram yanılgısı: Kodu sadece çevrimiçi hale getirmek onu açık kaynaklı yapar. Gerçekte, yazılımın diğerleri tarafından kullanıma, kopyalanmasına, uyarlanmasına ve/veya dağıtımına izin veren bir lisans eşlik etmiyorsa, geliştiriciler münhasır telif hakkını elinde tutar. Açık kaynaklı yazılım yapmak için kodla birlikte bir açık kaynak lisansının olması gerekir.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Öğrenme çıktıları

1. Yazılımı en uygun lisansla paylaşabilmek \(yani, hem araçlar hem de lisanslama\).

2. Bir kod parçasını kalıcı bir tanımlayıcı ile yükleyebilmek, sürümlendirebilmek ve kaydedebilmek.

3. Bir araştırma makalesinde kullanılan yazılıma atıf yapabilmek.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Ek okuma listesi

* Balasegaram ve diğerleri. (2017). An open source pharma roadmap. [doi.org/10.1371/journal.pmed.1002276](https://doi.org/10.1371/journal.pmed.1002276) 

* Dryden ve diğerleri. (2017). Upon the Shoulders of Giants: Open-Source Hardware and Software in Analytical Chemistry. [doi.org/10.1021/acs.analchem.7b00485](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.7b00485) 

* Ince ve diğerleri. (2012). The case for open computer programs.[doi.org/10.1038/nature10836](https://doi.org/10.1038/nature10836)

* Iskoujina ve Roberts (2015). Knowledge sharing in open source software communities: motivations and management. [PDF](https://pdfs.semanticscholar.org/f2a2/c5129cf5656af7acc7ffaf84c9c9bafe72c5.pdf)

* Jiménez ve diğerleri. (2017).Four simple recommendations to encourage best practices in research software. [doi.org/10.12688/f1000research.11407.1](https://doi.org/10.12688/f1000research.11407.1) 

* Martinez-Torres ve Diaz-Fernandez (2013).Current issues and research trends on open-source software communities [PDF](https://idus.us.es/xmlui/bitstream/handle/11441/32245/Current%20issues%20and%20research%20trends.pdf?sequence=1) 

* Morin ve diğerleri. (2012). Shining Light into Black Boxes. [PDF](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4203337/pdf/nihms588981.pdf)

* Oishi ve diğerleri. (2018). Perspectives on Reproducibility and Sustainability of Open-Source Scientific Software from Seven Years of the Dedalus Project. [arXiv:1801.08200v1 [astro-ph.IM]](https://arxiv.org/abs/1801.08200)

* Scacchi (2010). The Future of Research in Free/Open Source Software Development. [PDF](http://www.ics.uci.edu/~wscacchi/Papers/New/FoSER-Scacchi-2010.pdf)

* Sandve ve diğerleri. (2013). Ten simple rules for reproducible computational research [doi.org/10.1371/journal.pcbi.1003285](https://doi.org/10.1371/journal.pcbi.1003285) 

* Shamir ve diğerleri. (2013).Practices in source code sharing in astrophysics. [arXiv:1304.6780v1 [astro-ph.IM]](https://arxiv.org/abs/1304.6780) 

* Steinmacher ve diğerleri. (2014). A systematic literature review on the barriers faced by newcomers to open source software projects. [PDF](http://igor.pro.br/publica/papers/IST_SysReview_PrePrint.pdf) 

* Stodden (2010). The Scientific Method in Practice: Reproducibility in the Computational Sciences.[PDF](http://datascienceassn.org/sites/default/files/The%20Scientific%20Method%20in%20Practice%20-%20Reproducibility%20in%20the%20Computational%20Sciences.pdf)

* Vandewalle (2012). Code Sharing Is Associated with Research Impact in Image Processing. [PDF](https://infoscience.epfl.ch/record/206184/files/Vandewalle12.pdf) 
