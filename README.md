PHP, HTML5 ve CSS3 ile YAPILAN FULL-STACK PROJE 


Proje Açıklaması-------------------------- 

Bu proje, kullanıcıların oturum açabilmesi ve sadece giriş yapmış kullanıcıların belirli sayfalara erişebilmesini sağlayan bir sistem geliştirmek üzere PHP, HTML5 ve CSS3 kullanılarak oluşturulmuştur.
Proje, XAMPP üzerinde lokal olarak çalıştırılmaktadır.

Geliştirme Ortamı
PHP'nin çalışabilmesi için bir sunucuya ihtiyaç vardır. Bu projede, internet üzerinden bir sunucu almak yerine, yerel bir geliştirme ortamı olan XAMPP kullanılmıştır. XAMPP, Apache web sunucusu ve MySQL veritabanı yönetim sistemini içerir, bu da projeyi yerel bir makinede çalıştırmak için ideal bir çözümdür.

Proje Yapısı
Proje dosyaları XAMPP'in htdocs dizininde saklanmalıdır. Bu dizin, Apache sunucusu tarafından sunulan kök dizindir. Projeyi çalıştırmak için, xampp/htdocs/proje yolunu izleyerek dosyalar yerleştirilmelidir.

Veritabanı Bağlantısı,PhpMyadmin Kullanılarak veritabanı oluşturuldu ve bunun içine bir tablo oluşturuldu.
Veritabanı bağlantısı, baglan.php dosyası içerisinde yapılır. Bu dosya, veritabanı sunucusuna bağlanmak için gerekli PHP kodlarını içerir. Veritabanına yapılan tüm bağlantılar ve sorgular, projedeki diğer dosyalar (index.html, panel.php, panelgiris.php) bu bağlantı dosyasını dahil ederek gerçekleştirilir.

Güvenli Giriş Sistemi
Proje, kullanıcı adı ve şifre ile giriş yapılan bir sistem içerir. Kullanıcı adı ve şifre kontrolü, PHP ile gerçekleştirilir ve doğru giriş yapan kullanıcılar belirli sayfalara yönlendirilir. Örneğin, panel.php sayfasına sadece giriş yapmış kullanıcılar erişebilir. Doğru kimlik bilgileri sağlanmadan bu sayfalara erişim mümkün değildir.

Kullanıcı Adı: admin
Şifre: 12345
Projeyi Çalıştırma
Projeyi çalıştırmak için XAMPP uygulamasını başlatın ve Apache ile MySQL servislerini aktif hale getirin. Proje dosyaları htdocs dizinine yerleştirildikten sonra, tarayıcı üzerinden http://localhost/proje/panel.php adresine giderek projeyi çalıştırabilirsiniz. Ancak, panel.php sayfasına erişim sağlanabilmesi için öncelikle panelgiris.php sayfası üzerinden doğru kullanıcı adı ve şifre ile giriş yapılmalıdır.

Kullanıcı Girişi İşlemleri
Kullanıcı giriş işlemleri panelgiris.php sayfasında gerçekleştirilir. Giriş işlemi başarılı olduğunda, kullanıcı panel.php sayfasına yönlendirilir. Başarısız giriş denemeleri, kullanıcıya bir uyarı mesajı ile bildirilir.

XAMPP Kullanımı
Projenin sorunsuz çalışabilmesi için XAMPP'in Apache ve MySQL servislerinin aktif olması gerekmektedir. Bu servislere XAMPP kontrol panelinden kolayca erişebilir ve başlatabilirsiniz.



PROJENİN EKRAN GÖRÜNTÜSÜ:


![Ekran görüntüsü 2024-09-03 211438](https://github.com/user-attachments/assets/2067bd5e-3bc2-4119-8801-e90de181f4d3)

Form Alanı: 

![Ekran görüntüsü 2024-09-03 211502](https://github.com/user-attachments/assets/1676f683-e245-45df-ae83-17c8f8212bda)


Panel Sayfası: 



![Ekran görüntüsü 2024-09-03 212803](https://github.com/user-attachments/assets/53158442-5c21-45c9-ae59-3c2522807455)




PanelGiriş Sayfası :

![Ekran görüntüsü 2024-09-03 212628](https://github.com/user-attachments/assets/00e7d119-f0da-4bf8-8fea-f75e196e9ff4)




-----------------------------------------------------PROJENİN  CANLI HALİ -------------------------------------------

linki : http://elcinsite.rf.gd/
