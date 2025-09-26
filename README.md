Prisma: Neural Style Transfer with TensorFlow

📌 Proje Hakkında

Bu proje, Neural Style Transfer tekniğini kullanarak içerik ve stil görüntülerini birleştirmeyi amaçlamaktadır.
Örneğin bir fotoğrafı (içerik) alıp, ünlü bir tablonun (stil) dokunuşlarını ekleyerek yeni bir görsel üretir.

Projede TensorFlow, TensorFlow Hub ve önceden eğitilmiş derin öğrenme modelleri (VGG19, ResNet50) kullanılmaktadır.

🚀 Özellikler
	•	Google Colab + Drive entegrasyonu ile kolay kullanım
	•	TensorFlow Hub’dan hazır stil aktarım modeli (magenta/arbitrary-image-stylization-v1-256)
	•	VGG19 ve ResNet50 mimarileri ile denemeler
	•	Görselleri yükleme, işleme ve görselleştirme fonksiyonları
	•	Çeşitli içerik ve stil kombinasyonlarıyla deneme imkânı

📂 Proje Yapısı

Prisma.ipynb   # Jupyter Notebook (Colab üzerinde çalıştırılabilir)

Kurulum

Proje Google Colab üzerinde çalıştırılmak üzere tasarlanmıştır.
	1.	Bu depoyu veya sadece Prisma.ipynb dosyasını Colab’e yükleyin.
	2.	Gerekli kütüphaneleri yükleyin:

  pip install tensorflow tensorflow_hub matplotlib

  Notebook içindeki hücreleri sırayla çalıştırın.

🖼️ Kullanım
	•	İçerik görseli: Kendi fotoğrafınızı veya seçtiğiniz bir görseli kullanabilirsiniz.
	•	Stil görseli: Bir tablo veya istediğiniz farklı bir görsel seçebilirsiniz.
	•	Notebook içerisinde:

  content_image = load_img('/content/drive/My Drive/style/Photos.jpg')
style_image = load_img('/content/drive/My Drive/style/starry_night.jpg')

Hücreleri çalıştırdıktan sonra model, yeni stilize edilmiş bir görsel üretir.

📊 Örnek

İçerik: Bir fotoğraf
Stil: Van Gogh - Starry Night
Çıktı: Fotoğraf + Starry Night dokunuşu ile yeni bir resim

🔮 Geliştirme Fikirleri
	•	Farklı stil transfer algoritmalarını denemek
	•	Gerçek zamanlı kamera görüntülerine uygulamak
	•	Çıktı kalitesini artırmak için hiperparametre ayarları yapmak

📜 Lisans

Bu proje eğitim ve araştırma amaçlıdır.


