# MELD-MultiModal-Emotion-Analysis
# MELD ile Çok Modlu Duygu Analizi

## Genel Bakış
Lisans bitirme tezim kapsamında, [MELD](https://github.com/declare-lab/MELD) veri setini kullanarak çok modlu duygu analizi yapılmıştır.
MELD veri seti, Friends dizisinden elde edilen ve çeşitli duygularla etiketlenmiş veriler içermektedir. Veri seti, duygu tanıma görevleri için zengin çok modlu bilgi sunar.
Çok modlu veri, birden fazla modaliteden (örneğin, metin, ses, görüntü) elde edilen bilgileri içeren verileri ifade eder. Bu tür veriler, farklı modaliteler arasındaki ilişkileri ve etkileşimleri analiz ederek daha zengin ve anlamlı bilgiler sağlar. Friends dizisinden elde edilen videolardan oluşan MELD veri setinden elde edilen metin ve ses modaliteleri üzerinde pencereleme tekniği kullanılarak multimodal duygu analizi için dört farklı teknik incelenmiştir: 
- **Erken Füzyon**
- **Geç Füzyon**
- **Hibrit Füzyon**  (Ara Katmanlardan Birleştirme Yaparak Hibrit Füzyon & Dikkat Mekanizmaları Kullanılarak Çapraz Füzyon)
Bu çalışmada kullanılan pencereleme yöntemi, performansı önemli ölçüde artırmıştır. Pencereleme yöntemi, duygu sınıflandırmasında F1 skorlarının iyileştirilmesini sağlamıştır. MELD verisiyle kurulan 4 modelin karşılaştırılmaları yapılmıştır.

## Çalışma Akışı
![image](https://github.com/ilkedercan/MELD-MultiModal-Emotion-Analysis/blob/main/ak%C4%B1%C5%9Fdiyagram%C4%B1.png)
