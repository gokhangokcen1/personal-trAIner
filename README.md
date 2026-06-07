# personal-trAIner
Egzersiz esnasında kişinin formunu takip eden ve sesli uyarı veren bir AI kişisel antrenör. 

## Tekrar sayıcı
[pull-up-tekrar-aci.webm](https://github.com/user-attachments/assets/f66e2119-6466-4357-8dea-d742a92c0300)

# Hareket sınıflandırma 
[egilme_tahmin.webm](https://github.com/user-attachments/assets/6d99fbf8-dd2d-4f1d-b231-04ce4e6ff939)






# TO - DO 
- [X] `Classification:` Kişi harekete başladığında hangi harekete başlandığının tespiti
  - [X] Fotoğraf üzerinde deneme
  - [X] Video üzerinde deneme
  - [ ] Canlıda deneme   
- [ ] `Anlık Uyarı:` Yapılan hatayı sesli olarak söyleyen (ör. squatta gerekli minimum paralellik elde edilmediğinde) ve düzeltilmesini sağlayan ses.
- [ ] `Biyomekanik:` Bazı hareketlerin doğruluğu ve güvenliği eklem açılarından farklı parametrelerle de ölçülür, bunları da ekleyerek hareketlerin farklı açılardan doğruluğunu test et. (Ör. pull up yaparken çenenin barı geçmesi)
- [ ] `ADV - Görüntü iyileştirme:` Ortam parlaklığı iskelet yapısının tespiti için yeterli değilse anlık olarak görüntü üzerinde oynama ve düzenlemeler yapma.


 # DONE 
 - [X] `MediaPipePoseEstimation:` MediaPipe ile iskelet çıkar ve birkaç temel hareket için bilek, dirsek, omuz açısındaki açıya bak.
 - [X] `Tekrar Sayıcı:` Gerekli şartlar sağlandığında tekrarı artır.
