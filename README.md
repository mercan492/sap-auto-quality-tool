# sap-auto-quality-tool
Bu proje, otomotiv üretim hatlarından gelen ham verileri işleyerek anlamlı kalite metriklerine dönüştüren bir SAP ABAP raporlama aracıdır.
Proje, ham verinin stratejik kararlara nasıl dönüştürülebileceğini "Data Storytelling" prensipleriyle ele alır.

🎯 Projenin Amacı
Otomotiv sektöründe üretim verimliliği ve hata takibi kritiktir. Bu araç:

    Ham üretim ve hata sayılarını kullanarak Gerçek Zamanlı Hata Oranı (Defect Rate) hesaplar.

    Belirlenen eşik değerlerine göre parçaları Kritik, Optimal ve Kusursuz olarak sınıflandırır.

    Üretim yönetiminin odaklanması gereken "Top-N" (En Kritik Parçalar) analizini sunar.
    

🛠 Teknik Yetkinlikler & Optimizasyon

Kod geliştirilirken modern ABAP standartları ve performans kriterleri ön planda tutulmuştur:

    Bellek Yönetimi (Performance First): Büyük veri setlerinde veri kopyalama maliyetini sıfıra indirmek için FIELD-SYMBOLS kullanılmıştır.

    Modern Mimari: Eski fonksiyon modülleri yerine CL_SALV_TABLE sınıfı ile nesne tabanlı (Object Oriented) bir raporlama arayüzü sunulmuştur.

    Clean Code: Kod, okunabilirliği ve bakımı kolaylaştırmak adına modüler FORM yapılarına bölünmüştür.

    S/4HANA Uyumluluğu: VALUE # ve DATA(...) gibi modern satır içi (inline) deklarasyonlar kullanılmıştır.
    

🚀 Kurulum ve Kullanım

    z_automotive_quality_analysis.abap dosyasındaki kodu kopyalayın.

    SAP sisteminizde SE38 işlem koduna gidin.

    Yeni bir program oluşturun ve kodu yapıştırın.

    Pretty Printer (Shift+F1) ile formatı düzenleyin ve aktifleştirin (Ctrl+F3).
    

📊 Örnek Çıktı Analizi

Program çalıştığında aşağıdaki metrikleri otomatik olarak hesaplar:

    Toplam Üretim Sağlığı (General KPI): Fabrika genelindeki hata ortalaması.

    Durum Sınıflandırması: Hata oranı %5'in (dinamik parametre) üzerindeki parçaların "KRITIK" olarak işaretlenmesi.
![Z_AUTO_QUALITY_ANALYSER 6](https://github.com/user-attachments/assets/fd5e07b0-85a7-4262-9934-d931fa9b87cf)

![Z_AUTO_QUALITY_ANALYSER 7](https://github.com/user-attachments/assets/e9d966a0-42fb-4a09-96a3-3a5a4c5cad6d)



