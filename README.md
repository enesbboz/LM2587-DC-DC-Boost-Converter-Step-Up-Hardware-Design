# LM2587-DC-DC-Boost-Converter-Step-Up-Hardware-Design
Bu proje, giriş gerilimini daha yüksek bir çıkış gerilimine regüle etmek amacıyla tasarlanmış, LM2587 tabanlı bir DC-DC Boost  Konvertör donanım uygulamasıdır. Tasarım süreci Altium Designer kullanılarak gerçekleştirilmiş olup, güç elektroniği PCB tasarım standartlarına uygun olarak dizayn edilmiştir.
Sistem, Texas Instruments'ın "Flyback/Boost" regülatör ailesinden olan LM2587 entegresi baz 
alınarak yapılmıştır. 
Topoloji: Boost ConverterAnahtarlama Frekansı: 100 kHz

Endüktör (L1): Yüksek doygunluk akımına sahip güç bobini.  

Diyot (D1): SURS8360T3 (Ultra-Fast Recovery) diyot kullanılarak anahtarlama kayıpları minimize edilmiştir.  

Geri Besleme (Feedback) Ağı: R1 (56 kΩ) ve R2 (2 kΩ) dirençlerinden oluşan gerilim bölücü ile regüle edilmektedir. 

