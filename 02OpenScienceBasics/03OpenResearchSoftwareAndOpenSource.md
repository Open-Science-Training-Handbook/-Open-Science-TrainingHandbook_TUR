<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Açık Araştırma Yazılımları ve Açık Kaynak

### Nedir?

Açık araştırma yazılımları ya da açık kaynak araştırma yazılımları, analiz, simulasyon ve görselleştirme vb. için tüm kaynak kodlarının erişilebilir olduğu yazılımların kullanılması ve geliştirilmesi anlamına gelir. Aynı zamanda, [Open Source Definition](https://opensource.org/osd) tanımına göre, açık kaynak yazılımlar kaynak dosya biçiminde ve/veya derlenmiş biçimde \(ikinci durumda kaynak kodu erişilebilir olacak şekilde\) dağıtılmalı ve değişiklik, türetme ve yeniden dağıtıma izin veren bir lisans ile paylaşılmalıdır.

### Gerekçe

Modern araştırmalar yazılıma dayanır ve bu araştırmalar üzerine inşa edilmiş ya da türetilmiş—yazılımın ardındaki tam kaynak koduna erişimi gerektirir \([Barnes, 2010](https://doi.org/10/cj8t6n); [Morin et al., 2012](https://doi.org/10/m5t); [Ince et al., 2012](https://doi.org/10/hqg); [Prins et al. 2015](https://doi.org/10/f3mn4p); [Lowndes et al., 2018](https://doi.org/10/gc4jb3)\). Buckheit ve Donoho'nun Jon Claerbout'tan alıntı yaparak belirttiği gibi, ‘‘Hesaplamaya dayanan bir sonuçla ilgili bir makale reklamdır, bilim değil. Asıl bilim, sonucu üreten tam yazılım ortamı, kod ve verilerdir’’ \([Buckheit & Donoho, 1995](https://doi.org/10.1007/978-1-4612-2544-7_5)\). Araştırma yazılımlarının kaynak koduna açık erişim araştırmanın etkisini de artırır \([Vandewalle, 2012](https://doi.org/10/gc5sjp)\).

Araştırma için kullanılan yazılımların paylaşılması \(doğası gereği hesaplamalı veya herhangi bir yazılım tabanlı analize/yoruma dayalı olsun olmasın\) tekrarlanabilirlik için yeterli olmasa da gerekli bir koşuldur. Bunun nedeni, yazılımı doğal dil kullanarak, örneğin bir kağıtta tam olarak tanımlamaya çalışırken ortaya çıkan kaçınılmaz belirsizliktir  \([Ince et al., 2012](https://doi.org/10/hqg)\). Ayrıca, \(pek çoğu olmasa da\) çoğu yazılım programı tespit edilmemiş hatalar içerebilir \([Soergel, 2015](https://doi.org/10/gc5sjg)\), bu nedenle yazılımın "mükemmel" bir yazılı açıklaması dahi tüm sonuçları açıklayamayabilir.

Tekrarlanabilirliğe ek olarak, yazılımı açık bir şekilde paylaşmak, geliştiricilerin çabaları karşılıdığında doğrudan atıf \([Smith et al., 2016] ya da [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) veya [Journal of Open Source Software](http://joss.theoj.org) gibi dergilerde yayımlanmış yazılım meta-makaleleri (software meta-articles) aracılığyla \([Smith et al., 2018](https://doi.org/10/gc5sjf)\) kariyer kredisi almalarına olanak sağlar. Neil Chue Hong, yazılım makaleleri yayımlayan maintains a [birçok alana özgü derginin listesini](https://www.software.ac.uk/which-journals-should-i-publish-my-software) tutmaktadır.

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

The open source principles above extend to hardware. Researchers often use proprietary instrumentation or hardware in their research that is not freely accessible, reusable, or adaptable. Scientific hardware includes everything from sequencing tools and microscopes to specialized testing equipment and particle colliders. Open Science Hardware \(OScH\) community, for example, is leading a push for the open source movement to include scientific tools, hardware, and research infrastructures through their [Global Open Science Hardware Roadmap](http://openhardware.science/global-open-science-hardware-roadmap/).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Beceriler

* Create a repository on GitHub, and enable the integration with Zenodo. Mint the first release of the software.

* Choose a software license using \(e.g.\) [choosealicense](https://choosealicense.com) or the [Open Source Initiative](https://opensource.org/licenses).

* Create documentation for a software package, including README, comments, and examples.

* Appropriately cite software used for a paper.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Sorular, engeller ve yaygın kavramsal yanılgılar

Q: "I can’t share my software—it’s too messy / it doesn’t have good documentation / I didn’t leave good comments!"

A: Developers of research software around the world empathize with this feeling—people rarely feel like their code is "ready" to publicly share or that it is “finished”. However, as [Barnes \(2010\)](https://doi.org/10/cj8t6n) put it, “if your code is good enough to do the job, then it is good enough to release—and releasing it will help your research and your field.” In other words, if you feel comfortable enough with your software to publish a study or report results, then the code is sufficiently developed to share with your colleagues. \(In the other direction, if you don’t feel comfortable sharing the code, then perhaps it requires more development or testing before using in a publication\). Plus, sharing your code allows others to improve and build upon it, leading to even greater impact and innovation \(and citations for you!\).

Q: "What if someone takes the code I have shared and uses it for nefarious purposes, or claims they wrote it?"

A: Selecting an appropriate license for your software will help protect you from any uses of your software by others; for example, the common [MIT License](https://choosealicense.com/licenses/mit/) includes both limitations of liability and states that no warranty is provided. If someone else tries to claim that they wrote the software you made available, then you can point to the timestamps on your repository or archived versions as proof of your prior work.

Q: "If I share my code in an online repository, I will be deluged with requests for user support."

A: Although potential users may ask you for help, either via email or \(e.g.\) issues filed on the online repository, you are under no obligation to provide support if you prefer not to or cannot do so. An appropriate license even provides you with legal protection for this \(e.g., the no-warranty clause of the [MIT License](https://choosealicense.com/licenses/mit/)\).

Common misconception: simply putting code online makes it open-source software. In fact, unless the software is accompanied by a license that grants permission for others to use, copy, modify, and/or distribute, then the developer\(s\) retain exclusive copyright. A open-source license needs to accompany the code to make it open-source software.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Öğrenme çıktıları

1. Be able to share software under the most appropriate license \(i.e., both the tools and the licensing\).

2. Be able to upload, version, and register a piece of code under a persistent identifier.

3. Be able to cite software used for a research article.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Ek okuma listesi

* Balasegaram et al. (2017). An open source pharma roadmap. [doi.org/10.1371/journal.pmed.1002276](https://doi.org/10.1371/journal.pmed.1002276) 

* Dryden et al. (2017). Upon the Shoulders of Giants: Open-Source Hardware and Software in Analytical Chemistry. [doi.org/10.1021/acs.analchem.7b00485](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.7b00485) 

* Ince et al. (2012). The case for open computer programs.[doi.org/10.1038/nature10836](https://doi.org/10.1038/nature10836)

* Iskoujina and Roberts (2015). Knowledge sharing in open source software communities: motivations and management. [PDF](https://pdfs.semanticscholar.org/f2a2/c5129cf5656af7acc7ffaf84c9c9bafe72c5.pdf)

* Jiménez et al. (2017).Four simple recommendations to encourage best practices in research software. [doi.org/10.12688/f1000research.11407.1](https://doi.org/10.12688/f1000research.11407.1) 

* Martinez-Torres and Diaz-Fernandez (2013).Current issues and research trends on open-source software communities [PDF](https://idus.us.es/xmlui/bitstream/handle/11441/32245/Current%20issues%20and%20research%20trends.pdf?sequence=1) 

* Morin et al. (2012). Shining Light into Black Boxes. [PDF](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4203337/pdf/nihms588981.pdf)

* Oishi et al. (2018). Perspectives on Reproducibility and Sustainability of Open-Source Scientific Software from Seven Years of the Dedalus Project. [arXiv:1801.08200v1 [astro-ph.IM]](https://arxiv.org/abs/1801.08200)

* Scacchi (2010). The Future of Research in Free/Open Source Software Development. [PDF](http://www.ics.uci.edu/~wscacchi/Papers/New/FoSER-Scacchi-2010.pdf)

* Sandve et al. (2013). Ten simple rules for reproducible computational research [doi.org/10.1371/journal.pcbi.1003285](https://doi.org/10.1371/journal.pcbi.1003285) 

* Shamir et al. (2013).Practices in source code sharing in astrophysics. [arXiv:1304.6780v1 [astro-ph.IM]](https://arxiv.org/abs/1304.6780) 

* Steinmacher et al. (2014). A systematic literature review on the barriers faced by newcomers to open source software projects. [PDF](http://igor.pro.br/publica/papers/IST_SysReview_PrePrint.pdf) 

* Stodden (2010). The Scientific Method in Practice: Reproducibility in the Computational Sciences.[PDF](http://datascienceassn.org/sites/default/files/The%20Scientific%20Method%20in%20Practice%20-%20Reproducibility%20in%20the%20Computational%20Sciences.pdf)

* Vandewalle (2012). Code Sharing Is Associated with Research Impact in Image Processing. [PDF](https://infoscience.epfl.ch/record/206184/files/Vandewalle12.pdf) 
