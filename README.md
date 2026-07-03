# bldc-motor-driver-design
# 1 kW Fırçasız Doğru Akım (BLDC) Motor Sürücü Tasarımı ve Gerçeklemesi

Bu depo, lisans bitirme projem kapsamında tasarlanan ve fiziksel olarak üretilen **1 kW gücündeki BLDC motor sürücü** kartının donanım, simülasyon ve rapor dosyalarını içermektedir. Proje, Prof. Dr. Mehmet Bayrak danışmanlığında başarıyla tamamlanmıştır.

Sistem, geri besleme mekanizması olarak **Hall sensörleri** (sensörlü yapı) kullanılarak tasarlanmış olup, 3 fazlı inverter topolojisi ile motorun sürülmesini sağlamaktadır. 

##  Proje İçeriği

* **`bldcmotorsurucusimulasyon/`**: Proteus üzerinden gerçekleştirilen devre şeması  tasarımı ve sistem simülasyon dosyaları.
* **`bldcmotorsurucutasarimrapor/`**: Komponent seçimleri, matematiksel analizler, güç hesaplamaları ve donanım geliştirme süreçlerini detaylandıran kapsamlı proje raporu.
* **`surucugerceklemeresimler/`**: PCB dizgi, lehimleme aşamaları ve test süreçlerini içeren tamamlanmış fiziksel sürücü kartı fotoğrafları.

##  Teknik Özellikler ve Araçlar
* **Güç Kapasitesi:** 1 kW
* **Kontrol Tipi:** Sensörlü (Hall-Effect Sensor)
* **Tasarım ve Simülasyon:** Proteus (ISIS/ARES)
