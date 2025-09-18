🖨️ Yazıcı İzleme Paneli

Bu proje, kurum veya şirket ortamındaki yazıcıların durumunu ve kullanım istatistiklerini takip etmek amacıyla geliştirilmiş bir Windows Forms uygulamasıdır.
Veri erişim katmanında Entity Framework Code First yaklaşımı kullanılmıştır.

🚀 Teknolojiler

C# (.NET Framework)

Windows Forms

Entity Framework (Code First)

MSSQL Server

⚙️ Kurulum

Bu projeyi klonlayın:

git clone https://github.com/uğur161/YaziciIzlemePaneli.git


App.config dosyasında bulunan connection string ayarını kendi SQL Server bilgilerinizle güncelleyin.

<connectionStrings>
  <add name="YaziciContext"
       connectionString="Data Source=.;Initial Catalog=YaziciDB;Integrated Security=True"
       providerName="System.Data.SqlClient" />
</connectionStrings>


Entity Framework Code First migration işlemini çalıştırın:

Visual Studio Package Manager Console’u açın.

Şu komutu çalıştırın:

Update-Database


Projeyi F5 ile çalıştırarak uygulamayı başlatın.

📌 Özellikler

Yazıcıların durumunu gerçek zamanlı izleme

Kullanım loglarını kayıt altına alma

Kullanıcı bazlı giriş ve yetkilendirme

İstatistik ve raporlama ekranları

👤 Geliştirici

İsim: Uğurcan Gürler

İletişim: ugurcangurlerr@gmail.com
