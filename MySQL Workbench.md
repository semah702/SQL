#**MySQL Workbench Tanıtımı ve Başlıca Özellikleri**

![MySQL Workbench](https://www.muratoner.net/wp-content/uploads/2016/01/mysql-logo.jpg)


- ER Diagramming (Entity-relationship model – varlık-bağıntı modeli) wiki: en / tr
- Sürükle-bırak yöntemi ile görsel database tasarımı
- Reverse Engineering özelliği ile mevcut veritabanınızın şemasını çıkarma (InnoDB kullanıyorsanız foreign-key (yabancı anahtar) tanımlarını algılayıp diyagramda gösteriyor)
- Forward Engineering ile tasarladığınız şema ile veritabanı oluşturuyor veya yaptığınız değişiklikleri veritabanına uyguluyor. (Gerekli kontrolleri otomatik yapıp ALTER scriptini otomatik oluşturuyor)
- Trigger, Partitioning ve Privileges gibi bir çok özelliği tablolara çok rahat tanımlayabilmeniz ve yönetebilmeniz
- Açıkçası PhpMyAdmin kadar başarılı olmasada Query Browser özelliğide unutulmamış
- Son versiyonlarda eklenen bir diğer özellik ise Server Administration (MySQL sunucusunun yükünü grafiksel olarak gösteriyor)
- Ücretli versiyonunda veritabanı dökümantasyonuda çıkartıyor


##**Neden Kullanmalıyız?**

Veritabanı tasarım araçlarının kullanımı söz konusu olduğunda PhpMyAdmin ‘den de tablo/veritabanı oluşturabiliyorum neden yeni bir program kurup kullanayım şeklinde bir soru akıllara geliyor. Şüphesiz bu yazımızda veritabanı tasarım araçlarının gerekliliğini tartışmayacağız ama elimizden geldiği kadar avantajlarını anlatmaya çalışacağız.
Bir veritabanını veritabanı tasarım aracı ile oluşturduğunuzda size sağlayacağı en büyük avantaj veritabanı haritanızın olmasıdır.


##**Neden MySQL Workbench ?**
- MySQL ile çalışıyorsanız MySQL ‘i en yakından tanıyan araç (aynı firmaya ait olmasından dolayı)
- Partitioning gibi yeni özellikleri bile barındırması
- Bir çok platformda çalışabilmesi (Windows, Linux<Fedora, Ubuntu, Suse, Redhat>, Mac OS X)
- Açık kaynak olması

###**Kaynakça**

[MySQL Workbench](https://blog.mustafakirimli.com/mysql-workbench-tanitimi-ve-baslica-ozellikleri/333)
