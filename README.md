![kitapproje](https://github.com/user-attachments/assets/1cb5d6ab-da3f-4eb8-968c-c03e2117e3f3)

📚 Library - Kütüphane Otomasyon Uygulaması
Library, C# ve Windows Forms kullanılarak geliştirilmiş temel bir kütüphane otomasyon sistemidir. Bu uygulama, kitap ve kullanıcı yönetimi gibi temel işlemleri gerçekleştirmek için tasarlanmıştır. Eğitim amaçlı geliştirilmiş olup, C# ve .NET teknolojilerine giriş yapmak isteyenler için ideal bir örnektir.

🚀 Başlarken
Gereksinimler
.NET Framework 4.7.2 veya üzeri

Visual Studio 2019 veya üzeri

SQL Server (Express veya tam sürüm)

Kurulum
Bu repoyu klonlayın:


git clone https://github.com/onursaltoparlak/Library.git

Visual Studio ile Library.sln dosyasını açın.

App.config dosyasındaki bağlantı dizesini kendi SQL Server ayarlarınıza göre güncelleyin.

Gerekli NuGet paketlerini yükleyin:

System.Data.SqlClient

Dapper (varsa)

Veritabanını oluşturun ve gerekli tabloları ekleyin. (Veritabanı şeması ConnectionString klasöründe yer alabilir.)

Uygulamayı başlatın ve test edin.

🛠️ Proje Yapısı
Dtos/: Veri transfer nesneleri (DTO'lar) bu klasörde bulunur.

Repositories/: Veritabanı işlemlerini yöneten sınıflar burada yer alır.

Form1.cs: Ana kullanıcı arayüzü formu.

Program.cs: Uygulamanın giriş noktası.

⚙️ Özellikler
Kitap ekleme, güncelleme ve silme

Kullanıcı ekleme ve yönetimi

Kitap ödünç verme ve iade işlemleri

Basit ve kullanıcı dostu arayüz

🧪 Kullanım
Uygulama başlatıldığında, ana form üzerinden kitap ve kullanıcı işlemlerini gerçekleştirebilirsiniz. Her işlem için ilgili butonlar ve formlar mevcuttur.

