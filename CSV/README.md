# Krakow Public Transport

## TEAM
1. Mahir Şahin – GitHub: [MahirSahin8](https://github.com/MahirSahin8) – 
Tasks: 1,6  
2. Aykut – Tasks: 2,3  
3. Charaf – Tasks: 4,5  

## INTRODUCTION
Krakow’un toplu taşıma sistemi günlük hayatın merkezinde yer alır ve şehrin 
hem tarihi çekirdeğini hem de yeni gelişen bölgelerini birbirine bağlar. 
Omurgayı elektrikli tramvaylar oluşturur; yoğun saatlerde kısa aralıklarla 
sefer yapar ve karbon ayak izini düşük tutar. Otobüsler ise tramvayın 
ulaşmadığı mahalleleri ve banliyöleri besler. Biletler otomatlardan, mobil 
uygulamalardan veya sürücülerden temin edilebilir; saatlik ve aktarmalı 
seçenekler yaygındır. Ağın okunabilirliği ve dakikliği, öğrenciler ve 
ziyaretçiler için öğrenme eşiğini düşürür.

Bu projede veriyi üç yaygın formatta temsil ediyoruz: **CSV**, **XML** ve 
**JSON**. CSV, tablo benzeri verileri hızlıca işlemek için idealdir; 
Excel/Numbers ile kolayca açılır. XML, etiket tabanlı hiyerarşiyle yapıyı 
açık eder; nitelikler (attributes) ile ek bağlam taşır. JSON ise modern web 
servislerinin tercihidir; listeler ve iç içe nesnelerle zengin veri 
modelleri kurmayı kolaylaştırır. Üç formatı aynı konu üzerinde yan yana 
koymak, biçimlerin güçlü ve zayıf yönlerini sezgisel olarak görmeyi sağlar.

Çalışma akışı yazılım ekibindeki gerçek işleyişi taklit eder. Her görev ayrı 
bir **branch** üzerinde geliştirilir; tamamlanınca **commit** edilir, ana 
dala (**main**) **merge** edilir ve GitHub’a **push** edilir. Böylece kimin 
neyi, ne zaman eklediği izlenir; çakışmalar minimize edilir. Sınavda 
beklenti; bu temel akışı uygulayarak, istenen klasör yapısını kurmak, 
dosyaları doğru biçimde doldurmak ve projenin teslim adımlarını hatasız 
şekilde tamamlamaktır.

## DATA
Aşağıdaki tablo, CSV dosyasındaki örnek verinin küçük bir özetidir.

| line | type | length_km | stops |
|-----:|------|----------:|------:|
| 1 | tram | 10 | 15 |
| 2 | bus  | 8  | 12 |
| 3 | tram | 6  | 10 |

## IMAGES
- Tram (online): 
https://upload.wikimedia.org/wikipedia/commons/8/8a/Krak%C3%B3w_tram_line_50.jpg  
- Bus  (online): 
https://upload.wikimedia.org/wikipedia/commons/1/19/Krak%C3%B3w_bus_501.jpg  

Yerel görsel: `IMG/krakow-transport.jpg`  

