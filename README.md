TopDownZombie projesi, Unreal Engine 5 ile geliştirilmiş, hayatta kalma temalı bir yukarıdan bakış (top-down) shooter projesidir.

Bu proje, oyun mekanikleri, yapay zeka davranışları ve bölüm tasarımları dahil olmak üzere Solo Geliştirici olarak tarafımca hazırlanmıştır. 
Proje içerisinde geliştirilen temel sistemler aşağıda detaylandırılmıştır:

Character Movement & Top-Down Kontroller (Blueprint)
* Top-down perspektife uygun karakter hareket sistemi.
* Yön bağımsız hareket ve mouse tabanlı nişan alma.
* Karakter rotasyonunun nişan yönüne göre dinamik olarak güncellenmesi.
* Kamera takip davranışı ve temel smoothing ayarları.
* Enhanced Input sistemi kullanılarak yapılandırılmış input akışı.

Health, Damage ve Death Sistemi (Blueprint)
* Bileşen (Component) tabanlı sağlık sistemi.
* Hasar alma ve hasar iletme mantığı.
* Can değerine bağlı durum kontrolü (alive / dead).
* Ölüm durumunda karakter ve AI mantıklarının devre dışı bırakılması.
* Yeniden başlatma ve state reset akışı.

Combat ve Silah Mekanikleri (Blueprint)
* Ateş etme sistemi ve temel silah davranışları.
* Line Trace tabanlı vuruş tespiti.
* Vurulan hedefe hasar iletimi ve etkileşim kontrolü.
* Hit algılama sonrası geri bildirim mantığı.
* Genişletilebilir silah ve hasar yapısı.

 Zombie AI Sistemi (Behavior Tree + Blueprint)
* Oyuncuyu algılama ve takip etme davranışı.
* NavMesh tabanlı pathfinding.
* Mesafeye bağlı saldırı kararları.
* Cooldown ve state kontrolü.
* Blueprint üzerinden AI durum yönetimi.

 Spawn ve Oyun Akışı Sistemi (Blueprint)
* Belirlenen noktalardan kontrollü düşman üretimi.
* Zaman veya koşul bazlı ilerleme mantığı.
* Oynanış temposuna göre zorluk ayarlamaları.
* Temel oyun döngüsünün Blueprint üzerinden yönetilmesi.

 Spline Tabanlı Sistemler (Blueprint)
* Spline üzerinde hareket eden actor mantığı.
* Hız ve yön kontrolü.
* Spline event noktaları üzerinden tetiklenen oynanış olayları.
* Oyun içi akış veya çevresel hareket sistemleri için kullanılabilir yapı.

Kurulum

Proje dosyalarını incelemek veya test etmek için:

1. Repoyu klonlayın:
   git clone https://github.com/omeratali/TopDownZombie.git

2. TopDownZombie.uproject dosyasını Unreal Engine 5 ile açın.

---
Geliştirici: Ömer Atalı
