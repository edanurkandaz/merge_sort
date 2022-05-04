# merge_sort
www.patika.dev

MERGE SORT: Diziyi sürekli bir şekilde ikiye bölerek yapılan sonrasında ise bunları merge ederek yani birleştirerek ortaya çıkan dizimize ise merge sort ile sıralanmış dizi diyoruz.

Dizimiz [16,21,11,8,12,22] olsun:
ikiye böldüğümüz zaman: [16,21,11] ve [8,12,22] olacaktır.
Sonrasında ise tekli olarak bakmaya devam edeceğiz. İlk olarak birinci yarıma bakıyoruz. [16]-[21,11] olarak bölüyoruz. sonra [21,11] i kıyaslayıp sort ediyoruz. yani yeni dizi [11,21] oluyor. Sonrasında ise bu dizinin içine 16 yı ekliyoruz. [11,16,21] elde ediyoruz.

Aynı adımlar ikinci yarıda da kullanıyoruz. Ve sonuc [8,12,22] olarak aynı kalıyor.

Sonuç olarak bu iki yarımı karşılaştırmalı olarak birlestirip dizimizin sort edilmiş halini bulabiliyoruz. Mesela iki dizinin de ilk elemanına bakarak hangisi küçük ise bizim oluşacak dizimizin ilk üyesini belirlemiş oluyoruz.
[11,16,21]-[8,12,22]--> [8,11,12,16,21,22]

Karmaşıklığına bakacak olursak: yarım haline bölünmesi n kadar karmaşıklık oluor. Ama sonrasında bu iki yarımın birleşmesi logn olduğu için karmaşıklık nlogn olarak karşımıza çıkıyor.
