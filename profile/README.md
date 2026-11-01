# 🌊 İTÜ AS

**İTÜ Otonom Tekne Takımı**

## Hakkımızda

Çalışmalarını Doç. Dr. Derya Ahmet Kocabaş danışmanlığında, İTU ELMAKLAB ve İTÜ Gölet kıyısındaki konteynerında çalışmalarını sürdüren İTÜ AS (İTÜ Otonom Tekne Takımı) farklı disiplinlerden bir araya gelen öğrencilerin oluşturduğu insansız su üstü deniz aracı takımıdır. Yeni gelişen insansız deniz araçları alanında çalışan, Ar-Ge odaklı yapısıyla ulusal ve uluslararası alanda yarışma ve fuarlara katılım sağlayan takım; hem su üstü hem de su altı aracı bulunan tek İTÜ takımıdır.

## Misyonumuz

Atalarımızın bize, gençlere bıraktığı değerli hazineyi değerlendirmekten ve damarlarımızda akan asil kanın verdiği güçle bu hazineyi büyütmekten onur duyuyoruz. Biz gençler, geleceği aydınlatmak için gece gündüz çalışmaktan onur duyuyoruz.

## Vizyonumuz

Farklı dallardaki mühendislerin fikirlerini tek bir çatı altında toplayarak, sahada kazanılan deneyimleri paylaşmak ve farklı düşünce yapılarının ortak mimarisini benimseyen mühendisler yetiştirmektir.

## Çalışma Alanlarımız

- Simülasyon ve test altyapısı
- Algılama: lidar, stereo kamera ve görüntü işleme
- Konum kestirimi, navigasyon ve kontrol
- Gömülü sistemler ve yer istasyonu
- Elektronik kart tasarımı

## Repolar

| Repo | Açıklama | Durum |
|---|---|---|
| [ituas-sim-2026](https://github.com/ITU-ASTEAM/ituas-sim-2026) | 2026 sezonu simülasyon ve geliştirme ortamı. Şu an Ubuntu 24.04 için kurulum scriptlerini içerir. | Aktif |
| [ituas_sim_2025](https://github.com/ITU-ASTEAM/ituas_sim_2025) | 2025 sezonunun Python + Gazebo prototipi: tekne modeli, Nav2, görüntü işleme, yer istasyonu. | Arşiv, geliştirilmiyor |

Donanım, elektronik ve saha çalışmalarına ait repolar ekip içinde (private) tutulmaktadır.

## Geliştirme Ortamı

| Alan | Kullanılanlar |
|---|---|
| İşletim sistemi | Ubuntu 24.04 LTS |
| Robotik ara katman | ROS 2 Jazzy |
| Simülasyon | Gazebo Harmonic + `ros_gz` |
| Diller | C++, Python |
| Görüntü ve nokta bulutu | OpenCV, PCL |
| Matematik | Eigen |

Kurulum adımları: [ituas-sim-2026 / kurulum](https://github.com/ITU-ASTEAM/ituas-sim-2026/tree/main/kurulum)

## Katkıda Bulunun

1. İlgili repoyu kendi hesabınıza fork edin.
2. Değişiklikleriniz için ayrı bir dal açın.
3. Değişikliği açıklayan bir Pull Request ile `main` dalına gönderin.
4. Hataları ve önerileri Issue olarak bildirin.

`main` dalına doğrudan push ve force push yapılmaz; her değişiklik Pull Request üzerinden gelir.

## Repo Standartları

- Büyük dosyalar (model ağırlıkları, mesh'ler, veri setleri, loglar) repoya değil Release'e ya da ekip depolamasına konur; repoda bağlantısı ve sürümü belirtilir.
- Derleme çıktıları (`build/`, `install/`, `log/`, `__pycache__`) commit edilmez.
- Kodda kişisel bilgisayara özgü mutlak yollar (`/home/...`) kullanılmaz.
- Aynı kodun kopyası farklı klasörlerde tutulmaz; sürümler dal ve tag ile ayrılır.
- Başka projelerden alınan kodun lisansı korunur ve kaynağı belirtilir.
- Şifre, token gibi gizli bilgiler repoya eklenmez.

## Lisans

Her reponun lisansı kendi `LICENSE` dosyasında belirtilmiştir.
