JAVA

Java Nedir?

Java, 1995 yılında ortaya çıkan popüler bir programlama dilidir.

Oracle'a ait olup 3 milyardan fazla cihazda Java kullanılıyor.

Şunun için kullanılır:

Mobil uygulamalar (özellikle Android uygulamaları)

Masaüstü uygulamaları

Web uygulamaları

Web sunucuları ve uygulama sunucuları

Oyunlar

Veritabanı bağlantısı

Ve çok daha fazlası!



Neden Java Kullanmalısınız?

Java farklı platformlarda çalışır (Windows, Mac, Linux, Raspberry Pi, vb.)

Dünyanın en popüler programlama dillerinden biridir

Mevcut iş piyasasında büyük bir talep var

Öğrenmesi kolay ve kullanımı basittir

Açık kaynaklı ve ücretsizdir

Güvenli, hızlı ve güçlüdür

Çok büyük bir topluluk desteği var (on milyonlarca geliştirici)

Java, programlara net bir yapı kazandıran ve kodun yeniden kullanılmasına izin vererek geliştirme maliyetlerini düşüren nesne yönelimli bir dildir

Java, C++ ve C# dillerine yakın olduğundan , programcıların Java'ya veya tam tersine geçişini kolaylaştırır



I. Temel Java Kavramları (Dilin Temelleri)



Sınıf (Class): Nesneler oluşturmak için kullanılan bir şablondur. Her Java programı sınıflar etrafında kurulur.

Nesne (Object): Bir sınıfın somutlaşmış halidir, bir örneğidir.

Metot (Method): Bir sınıf içinde belirli bir görevi yerine getiren kod bloğudur.

Değişken (Variable): Veri depolamak için kullanılan adlandırılmış bellek konumudur.

Veri Tipleri (Data Types): Verilerin sınıflandırılmasıdır (örneğin, tam sayılar için int, metin için String, doğru/yanlış için boolean).

İlkel Veri Tipleri (Primitive Data Types): int, double, boolean, char gibi temel veri tipleridir.

Referans Veri Tipleri (Reference Data Types): Nesnelere referans veren veri tipleri (örneğin, String, özel sınıflar).

Anahtar Kelimeler (Keywords): Java'da özel anlamı olan ayrılmış kelimelerdir (örneğin, public, private, static, void, if, else, for, while, return, new).

Operatör (Operator): Değerler üzerinde işlemler gerçekleştiren sembollerdir (örneğin, +, -, *, /, =, ==, &&, ||).

Kontrol Akışı İfadeleri (Control Flow Statements): Kodun yürütülme sırasını kontrol eden ifadelerdir (örneğin, if-else, for döngüsü, while döngüsü, switch).

Döngü (Loop): Bir kod bloğunu tekrar tekrar yürüten bir kontrol akışı ifadesidir.

Koşullu İfade (Conditional Statement): Belirli bir koşul karşılandığında bir kod bloğunu yürüten ifadedir.

Paket (Package): İlgili sınıfları ve arayüzleri düzenlemenin bir yoludur.

İçe Aktarma (Import): Diğer paketlerdeki sınıfları mevcut dosyanıza getirmek için kullanılır.

Kalıtım (Inheritance): Bir sınıfın başka bir sınıfın özelliklerini ve davranışlarını miras alması mekanizmasıdır.

Çok Biçimlilik (Polymorphism): Bir nesnenin birçok form alabilme yeteneğidir.

Soyutlama (Abstraction): Uygulama ayrıntılarını gizleyip sadece temel özellikleri göstermektir.

Kapsülleme (Encapsulation): Verileri ve veriler üzerinde çalışan metotları tek bir birim (sınıf) içinde bir araya getirmektir.

Arayüz (Interface): Bir sınıfın uygulaması gereken bir dizi metodu tanımlayan bir sınıf taslağıdır.

Soyut Sınıf (Abstract Class): Örneği oluşturulamayan ve soyut metotlar içerebilen bir sınıftır.

İstisna (Exception): Bir programın normal akışını bozan bir olaydır.

Try-Catch Bloğu (Try-Catch Block): İstisnaları ele almak için kullanılır.

Dizi (Array): Aynı türdeki elemanların sabit boyutlu sıralı bir koleksiyonunu depolayan bir veri yapısıdır.

Koleksiyon (Collection): Nesne koleksiyonlarını temsil etmek ve manipüle etmek için birleşik bir mimari sağlayan bir çerçevedir (örneğin, List, Set, Map).

JVM (Java Virtual Machine): Java bytecode'unu yürüten sanal makinedir.

JRE (Java Runtime Environment): Java programlarını çalıştırmak için gereken kütüphaneleri ve JVM'yi sağlar.

JDK (Java Development Kit): JRE'yi ve geliştirme araçlarını (derleyici, hata ayıklayıcı vb.) içerir.

II. IntelliJ IDEA'ya Özgü Terimler



IDE (Integrated Development Environment - Entegre Geliştirme Ortamı): Yazılım geliştiricilere yazılım geliştirme için kapsamlı olanaklar sağlayan bir yazılım uygulamasıdır. IntelliJ IDEA bir IDE'dir.

Proje (Project): IntelliJ IDEA'daki en üst düzey organizasyon birimi olup, modüller, kütüphaneler ve diğer yapılandırmaları içerir.

Modül (Module): Bir proje içindeki ayrı bir işlevsellik birimidir. Bir projede birden fazla modül bulunabilir (örneğin, bir backend modülü, bir frontend modülü).

Çalıştırma Yapılandırması (Run Configuration): Uygulamanızı nasıl çalıştıracağınızı tanımlar (örneğin, hangi ana sınıfın çalıştırılacağı, komut satırı argümanları).

Hata Ayıklayıcı (Debugger): Kodunuzdaki hataları adım adım ilerleyerek bulmanıza ve düzeltmenize yardımcı olan bir araçtır.

Kesme Noktası (Breakpoint): Hata ayıklayıcının yürütmeyi duraklatacağı kodunuzdaki bir işarettir.

Yeniden Düzenleme (Refactoring): Mevcut bilgisayar kodunu dış davranışını değiştirmeden yeniden yapılandırma sürecidir. IntelliJ'in güçlü yeniden düzenleme araçları vardır.

Kod Tamamlama (Code Completion): Siz yazarken kodunuz için olası tamamlamaları öneren özelliktir.

Canlı Şablonlar (Live Templates): Hızlıca ekleyebileceğiniz özelleştirilebilir kod parçacıklarıdır (örneğin, psvm kısayolu public static void main metodu için).

Eklentiler (Plugins): Yeni özellikler ekleyen veya diğer araçlarla entegre olan uzantılardır.

VCS (Version Control System - Sürüm Kontrol Sistemi): Kod sürümlerini yönetmek için Git gibi sistemlerle entegrasyonu ifade eder.

Terminal (Terminal): IntelliJ içinde entegre bir komut satırı arayüzüdür.

Maven/Gradle: Java projeleriyle yaygın olarak kullanılan derleme otomasyon araçlarıdır. IntelliJ, bunlarla mükemmel entegrasyona sahiptir.

POM (Project Object Model): Maven tarafından bir projeyi tanımlamak için kullanılan XML dosyasıdır.

build.gradle: Gradle tarafından kullanılan derleme betik dosyasıdır.

SDK (Software Development Kit - Yazılım Geliştirme Kiti): IntelliJ içinde yapılandırılmış JDK'yi ifade eder.

Faset (Facet): Yapılandırılmış belirli bir çerçeve, teknoloji veya dil desteğini temsil eder. 

 

 