# C++
# Using Visual Studio Community 2022
# DM for questions, suggestions or issues

# TR - Basit otonom arabalar için geliştirilmiş bir şerit takip yazılımı.

Öncelikle [buraya](https://sourceforge.net/projects/opencvlibrary/files/4.5.1/opencv-4.5.1-vc14_vc15.exe/download) tıklayarak setup dosyasını indirin ve çalıştırın. 
Ardından kurulum klasörünü seçin ve klasörün dosya yolunu not alın.
Daha sonrasında extract tuşuna basın ve indirme işleminin bitmesini bekleyin.

Sırada kurduğunuz OpenCV pakedini PATH'e eklemeniz gerekiyor.
Bunun için:
  Arama kısmına sistem değişkenleri yazın ve uygulamayı açın.
  
  
  Sistem değişkenleri yazdığınızda sonuç alamıyorsanız:
  Bu bilgisayar / Özellikler
  ![](https://i.imgur.com/Ynr9X2o.png)
    
  Gelişmiş Sistem Ayarları
  ![](https://i.imgur.com/xTfub8t.png)
    
  Ortam Değişkenleri
  
  ![](https://i.imgur.com/9O8SUg0.png)
    
 
 Sistem değişkenlerine girdiğimizde:
 
 Alt kısımda Path değişkenine tıklayıp düzenle diyoruz
 
 ![](https://i.imgur.com/kxOCf7r.png)
    
 Ardından "Yeni" butonuna tıklayıp "kurulum_yolu\opencv\build\x64\vc15\bin" yolunu ekliyoruz (Örneğin benim için C:\opencv\build\x64\vc15\bin)
  

Artık Visual Studio'ya OpenCV kütüphanelerini ekleme zamanı:

Visual Studio'da yeni bir "C++ Konsol Uygulaması" projesi oluşturuyoruz.

Projemizi oluşturduktan sonra çözüm gezgini kısmında projemize sağ tıklayıp seçenekler diyoruz.
![](https://mertmekatronik.com/uploads/images/2021/04/image_750x_606aca01af032.jpg)

Daha sonra gelen ekranda VC++ Dizinlerine tıklıyoruz, bu kısımda ekleme kodu dizinlerine "kurulum_yolu\opencv\build\include" dosya yolunu, kitaplık dizinlerine de "kurulum_yolu\OpenCV\opencv\build\x64\vc15\lib" dosya olunu ekliyoruz.
![](https://mertmekatronik.com/uploads/images/2021/04/image_750x_6068d2ca3cf93.jpg)

Son olarak bağlayıcı kısmında girişe geliyoruz ve ek bağımlılıklara "opencv_world460d.lib" ekliyoruz.
![](https://i.imgur.com/mTgEYe0.png)

OpenCV kurulumunu tamamladınız!
Artık bir kaç satır yazmaya başlayabilirsiniz.


# EN - A line tracking software for basic autonomous vehicles.

Translate coming soon
