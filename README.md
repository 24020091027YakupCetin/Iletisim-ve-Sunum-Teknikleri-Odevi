C Programlama Projesi – Yüksek Performanslı Konsol Çıktısı
📌 Proje Açıklaması
Bu proje, modern donanım mimarileri üzerinde C programlama dilinin verimliliğini ve karakter kodlama standartlarını test etmek amacıyla geliştirilmiştir. Yüksek performanslı bir sistemde, standart girdi/çıktı (I/O) işlemlerinin optimize edilmesi ve Türkçe karakterlerin (UTF-8) sorunsuz bir şekilde terminale aktarılması hedeflenmiştir.

🎯 Projenin Amacı
Bu çalışma ile:

C dilinin düşük seviyeli bellek yönetimini gözlemlemek

Yeni nesil donanımlarda derleme ve çalışma sürelerini analiz etmek

setlocale() kütüphanesi ile dil desteği entegrasyonu sağlamak

RTX 5060 serisi gibi güncel donanımların geliştirme ortamındaki akıcılığını deneyimlemek

Terminal emülatörlerinde karakter render hatalarını gidermek

amaçlanmıştır.

🛠️ Kullanılan Teknolojiler
C Programlama Dili (C11/C17 Standartları)

CLion IDE (JetBrains)

GCC / Clang Derleyici

💻 Geliştirme Ortamı
Projenin geliştirildiği donanım altyapısı aşağıdaki gibidir:

Bilgisayar: MSI High-Performance Series

İşlemci: Intel Core i7 (Yeni Nesil)

Ekran Kartı: NVIDIA GeForce RTX 5090 / 5080

Bellek: 32 GB DDR5 RAM

Depolama: 1 TB NVMe M.2 SSD

▶️ Program Nasıl Çalıştırılır?
GCC ile Derleme ve Çalıştırma:

Bash
gcc main.c -o yüksek_performans_testi
./yüksek_performans_testi
