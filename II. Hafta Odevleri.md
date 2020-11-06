# **Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?**

## **MIT**

MIT lisansı ile lisanslanan projelerde, ilgili programın dosyalarına ulaşan her kullanıcı için proje hakkında kopyalama, kullanım, birleştirme ve değiştirme gibi çeşitli faaliyetler yapılabilir. Ticari ve hususi kullanımlar için uygun bir lisans tipidir.

## **Apache**

Apache lisansı ile lisanslanan projelerde ortaya koyulan ürünlerin lisanslarını da projeye eklenmesi gerekdiği gibi projede yapılan düzeltmelerde veya değiştirmelerde belirtilmesi gereklidir. Aynı zamanda ticari kullanıma da imkan verir.

## GPL (Genel Kamu Lisansı)

1989 yılında yayımlanan Genel Kamu Lisansı(GPL) halen günümüzde GPL V3 versiyonu ile kullanılmaktadır. GPL lisansı sunduğu imkanlar ile açık kaynaklı program geliştiricileri ve kullanıcıları tarafından büyük bir ilgi gören lisanstır. 

GPL lisansı ile lisanslanan bir proje kopyalanabilir, değiştirilebilir ve çeşitli faaliyetlerde kullanılabilir. Ancak kopyalanan projenin de GPL lisansı olmalıdır. Ayrıca bu lisansın ticari faaliyetlerde  kullanılarak elde edilecek gelirden herhangi bir pay verilme zorunluluğu da yoktur. Bu nedenle GPL lisansı hem program geliştiricileri için hem de kullanıcılar için teşvik edici bir lisanstır.

Ancak GPL lisansı kullanılarak geliştirilen ticari bir proje bir başkası tarafından kopyalanabilir ve bu proje üzerinden gelir elde edilebilir. Bu durumdan dolayı ticari faaliyetler içeren projelerde kullanılması pek doğru bir karar olmayacaktır.

## LGPL (Kısıtlı Genel Kamu Lisansı)

Çoğunlukla kütüphane olarak kullanılacak yazılımlarda kullanılan Kısıtlı Genel Kamu Lisansı (LGPL)   , GPL lisansının aksine kütüphaneyi yazılım içerisine kapalı kaynak olarak yerleştirebilirsiniz. Ancak LGPL lisansı kullanılarak hazırlanan bir kütüphanenin bir bölümünde veya bir kısmında herhangi bir değişiklik yapılması durumunda bu kısmının açılması gerekmektedir.

## BSD Lisansı

Berkeley Software Distribution (BDL) özgür yazılım lisans ailesinden olup projeler üzerinde herhangi bir sınırlama olmaksızın kullanılabilir. Bu lisans ile kullanıcılar istedikleri gibi projeleri kopyalayabilir ve ticari faaliyetlerde kullanabilir.

## MPL (Mozilla Kamu Lisansı)

Mozilla Kamu Lisansı (MPL) genel olarak BSD lisansı ile GPL lisansının bir araya getirilmesi ile oluşturulan bir lisanstır.

[Kaynak](https://medium.com/@AntriKod/%C3%B6zg%C3%BCr-yaz%C4%B1l%C4%B1m-lisanslar%C4%B1-%C3%BCzerine-c28e66c2b6ef)

---------------------------------------------------------------------------------------

# Merge - Squash-Rebase arasındaki farklar nelerdir?

## Tanımlar

Git merge ile yapılan birleştirilmede yeni bir *commit* yaratılır ve yeni *branchde ki* tüm history verileri korunarak birleştirme işlemi gerçekleştirilir.

Git rebase ile yapıla birleştirilmelerde ise *branch* içerisindeki *commitleri* tek tek istenile *branch* üzerine eklenebilir. Böylece tek bir history oluşturulabilecektir.

     

Git squash komutu ise rebase komutu ile benzer şekilde geçmişte oluşturulan *commitlerin* düzenlenmesi, değiştirilmesi gibi çeşitli yerlerde kullanılır.

  

## Farklar

 Git rebase ile git merge karşılaştırıldığında temel olarak komutların aynı işlevi yerine getirmek için kullanıldığı görülmektedir. Ancak komutların işlem süreçleri farklıdır. *Git merge* ile history korunarak birleştirme işlemi yapılabildiği gibi *Git rebase* işleminde ise fazlalık olan historylerin temizlenerek birleştirme işlemi yapılabildiği görülmektedir. *Git squash* ise *rebase* komutuna benzer olarak geçmişte oluşturulan commitler üzerinde değişikliklerin yapılabilmesine olanak vermektedir.

[Kaynak](https://medium.com/neyasistechnology/git-rebase-squash-ile-ge%C3%A7mi%C5%9Fi-yeniden-d%C3%BCzenlemek-9de36441f947)

--------------------------------------------------------------------------------------------------------------------------

# Agile-Scrum-Kanban Kavramları

## Agile

Agile, yazılım geliştirme süreçlerinde karşılaşılan problemlerin çözümlerine yönelik olarak tekrarlanan yazılım geliştirme modeli baz alınarak hazırlanan ve zaman yönetimi olarak kısa zaman dilimlerinde yazılım parçalarının hazırlanması yada değiştirilmesine yönelik yazılım geliştirme modelidir.

## Scrum

Scrum, kendi rehber tanımlamasına göre “İnsanların mümkün olan en yüksek değere sahip ürünleri üretken ve yaratıcı bir şekilde geliştirirken, karmaşık ve adaptasyona açık sorunları ele alabildikleri bir çerçeve” olarak tanımlanmıştır. Scrum, yazılım süreçlerinde detaylara ve ihtiyaçlara yönelik olarak üretilen çözüm yöntemleri ve metodolojisidir.

## Kanban

Kanban, "Kanban işlerimizin nasıl işlediğini bize gösteren bir metottur." olarak tanımlanmaktadır.  Kanban metodolojsinde ilk etapta sistem izlenir, çöp veri veya bekleme noktası oluşturulan yerler tespit edilir. Tespit edilen bu noktolar yok edilerek sistemin hafiflemesi ve iyileştirilmesi hedeflenir.

[Kaynak I.](https://medium.com/@PeopleBox/agile-nedir-scrum-nedir-ba%C5%9Far%C4%B1l%C4%B1-proje-y%C3%B6netimi-y%C3%B6ntemleri-nelerdir-64c4ae723496)

[Kaynak II.](https://www.donusumdanismanlik.com/kanban-nedir-uygulama-rehberi/)

[Kaynak III.](https://www.acmagile.com/kanban-nedir/)

-------------------------------------------------------------------------------------------------------------------------

# Gang Of Four (GOF)

Eric Gamma, Richard Helm, Ralph Johnson ve John Vlissides yazarlardan oluşan ve dörtlü çete olarakda bilinen yazarlar 1994 yılında *"Tasarım Desenleri: Yeniden Kullanılabilir Nesne Tabanlı Yazılımın Unsurları"* kitap yayınlanmıştır. 

Yazarlar aslında hangi dilde olursa olsun nesne yönelimli programlamalarda ortak sorunlar mevcuttur. Yazılımcılar nesneleri nasıl yaratmalıyız, nesneler arası iletişim ve nesne yönetimi gibi belirli başlıklarda ortak sorunlar yaşadıkları görülmüştür.

Yazarlar ortaya koydukları bu çalışma ile ortak karşılaşılan bu problemlere karşı ortak çözüm önerileri getirmişlerdir. Ortaya koyulan bu çözüm önerileri tasarım kalıplarını meydana getirmektedir.

*"Daha net bir ifadeyle Tasarım kalıpları, nesne yönelimli programlamada, programlama dili gözetmeksizin; sınıf ve nesneler arasındaki ilişkilerin en iyi şekilde nasıl olmaları gerektiğini açıklayan yöntemlerdir."*

Tasarım kalıpları 3 ana başlık altında incelenebilir;

**Creational Design Patterns ( Yaratımsal Tasarım Kalıpları ) :** İlgili nesnelerin oluşturulması ve yönetilmesi ile ilgili olan tasarım kalıplarıdır. Nesneler üzerinde yapılabilecek değişikliklere karşı sorun çıkmayacak şekilde nesnelerin nerede ve nasıl ortaya konması konusunda yardımcı olurlar.

**Structural Patterns (Yapısal Kalıplar) :** Nesneler arası ilişkileri düzenleyen tasarım kalıplarıdır. Sınıflar ve nesneleri birleştirerek daha geniş alanda yazılım gruplarının kurulabilmesine imkan verilir.

**Behavioral Patterns (Davranışsal Kalıplar)** : Sınıfların bir işi yerine getirirken aralarındak çalışma düzenini ve nasıl davranılacağını belirleyen tasarım kalıplarıdır.

[Kaynak I.](https://deryacakmak.medium.com/tasar%C4%B1m-kal%C4%B1plar%C4%B1-nelerdir-cd216ba47921)

[Kaynak II.](https://en.wikipedia.org/wiki/Design_Patterns)
