# TestTraining

Yazılım test süreçleri hakkında genel bilgilerden oluşan eğtimdir. 
Burdaki eğitim dökümanlarının bir kısmı:
UDEMY Platformundan aldığım "Yazılım Test Uzmanlığı Eğitimi: Sıfırdan İleri Seviye" adlı eğitimdendir.

Eğitim içeriğinin özetini aşağıdadır.

Bölüm 1 içeriği:

1-Yazılım Geliştirme yaşam döngüsü (Software Development Life Cycle SDLC)  
  Planlama <-> Analiz <-> Geliştirme <-> Test <-> Bakım ve Destek

2-Yazılım Test Uzmanı Sorumlulukları
  >Yazılım geliştirme yaşam döngüsünün her aşamasında yazılım test uzmanları etkin şekilde 
  görev alır ve uygulamanin kaliteli bir şekilde son kullanıcıya ulaştırılmasını sağlarlar.

  > *Planlama *Tanımlama (Specification) *Test Koşumu *Testin tamamlanması

3-Yazılımda Hata Raporlaması
  Görsel Hatalar: Kesilmiş görüntüler, hizalama sorunları
  Fonksiyonel Hatalar: Kullanıcı bir sonraki sayfaya geçememesi
  Performans Hataları: Sitenin açılmasının 10sn den fazla sürmesi

4-Yazılım Gereksinim analizi
  Yazılım gereksinimleri geliştirilmesi, istenen üründen nelerin beklendiğinin net açık bir şekilde ifade edilmesidir!
  Genellikle İş Analisti ve Ürün Sahipleri(Product Owner) tarafından gerçekleştirilir.
5-Test Senaryosu ve Test kontrol Listesi
  Test senaryosu, bir uygulamayı test etmek amacıyla, analiz dokümanı baz alınarak oluşturulan adımlarıdır.  
  Test senaryolari, uygulamanin beklenen sonucu verip vermediğini bulmak icin kullanilir.
  Test Senaryosu:
    Test Açıklaması, Test Adımları, Önşartlar, Test Datası
    Beklenen Sonuç, Öncelik ve Test koşum ortamları   dikkate alınarak oluşturulur.
    
Bölüm-2 İçeriği:

1-Yazılım Test Seviyeleri:
  >Birim Testleri : Kodu yazan yazılımcı tarafında kodlanır ve koşulur.
  >Entegrasyon Testleri : Bu testlerde sistemin işleyişi değil, diğer sistemlerle nasıl entegre olduğu test edilmelidir.
  >Otomatize Kullanıcı Arayüz Testleri : Bu testler uygulamanızın önyüzünün doğru şekilde çalıştığını otomatize şekilde kontrol eder.
  Bu tip testler kodlanırken kullanıcının adımları oluşturulur ve uygulamada bu adımlar takip edilir.
  >Sistem Testi : Sistem testleri, bütün bir sistemin veya ürünün davranış ve yeteneklerine odaklanır ve genellikle sistemin 
  gerçekleştirebileceği uçtan uca işleri ve bu işleri gerçekleştirirken gösterdiği fonksiyonel olmayan davranışları ele alır!
  >Kabul Testi Sistemin fonksiyonel ve fonksiyonel olmayan davranışlarının gereksinimlerde belirtildiği gibi olup olmadığının doğrulanması.
2-Kara Kutu ve Beyaz Kutu Test Teknikleri
  Kara Kutu : Bu testlerde kodun dahili olarak nasıl çalıştığı bilinmeden, sistem testi gerçekleştirilir.
    Fonksiyonel Testler : Sistem Testidir
      >Duman testi, Regresyon testi gibi testleri kapsar.
    Fonksiyonel Olmaya Testler : Sistem Testidir
      >Yük testi, performans testi, güvenlik testi gibi testleri kapsar.

  Beya Kutu :Beyaz kutu testlerinde, uygulamanın nasıl çalıştığı ve kod yapısı test uzmanı tarafından bilinir.
3-Kara Kutu Test Teknikleri
  Test edilen sistemin detaylı kod yapısının test uzmanı tarafından bilinmeden, sadece input(girdi) ve outputların (çıktı) kontrol edilmesidir.
  Denklik Payları Ayırma (Equivalence Partitioning)
  Sınır Değer Analizi (Boundary Value Analysis)
  Karar Tablosu Testleri (Decision Table Testing)
  Durum Geçiş Testleri (State Transition Testing)
  Kullanım Senaryosu Testleri (Use Case Testing)
4-Tecrübeye Bağlı Test Teknikleri
  Hata Tahminleme (Error Guessing)
  Keşif Testi (Explaratory Testing)
  Kontrol Listesine Dayalı Testler (Checklist Testing)


Bölüm-3 İçeriği:

1- Negatif Tesrler
2- Duman ve Mantıklılık Tetleri
  Duman testi (smoke testing), bir uygulamanın en önemli fonksiyonlarının çalışıp çalışmadığını anlamak amacıyla, 
  detaylara girmeden yapılan teste denir. 
  Duman testi genellikle uygulamanın yeni sürümünün yayınlanması sonrasında kritik fonksiyonların kontrolü için gerçekleştirilir. 

3- Rergresyon Testleri
  Regresyon testi, yazılım üzerinde yapılan herhangi bir değişiklik sonrası, bu değişikliğin yazılımın 
  diğer alanlarını etkilemediğini test etmek amacıyla kullanılan bir test tipidir.

4- Risk Bazlı Testler
  Regresyon testi, yazılım üzerinde yapılan herhangi bir değişiklik sonrası, bu değişikliğin yazılımın 
  diğer alanlarını etkilemediğini test etmek amacıyla kullanılan bir test tipidir.
  rİSK = Etki X Olma olasılığı

5- Statik Testler 
  Statik testlerin çalışma ürünlerinin tutarlılığını ve  iç kalitesini iyileştirmek için kullanılır, 
  dinamik testlerin ise genellikle dışarıdan görülebilen davranışlara odaklanır.
  İş gereksinmi ve analizi, Üst Düzen Tasarım, Detaylı Tasarım, Geliştirme bu evrelerde statik tesler gerçekleştirilir.
  
6- Test planlaması ve tahminlemesi(***)
  >Test planı, yazılım geliştirme ve bakım projeleri için test aktivitelerini özetler.
  >Planlama; kurumun test politikası ve test stratejisinden, kullanılan yazılım geliştirme 
  yaşam döngülerinden ve yöntemlerinden, testlerin kapsamından, hedeflerden, risklerden, kısıtlamalardan, 
  kritiklik durumundan, test edilebilirlik ve kaynakların kullanılabilirliği den etkilenir.
  >Yazılım testi öncesinde, ‘Hangi alan test edilecek’ , ‘Nasıl test edilecek’ ve ‘Ne kadar zaman harcanacak’ soruları yanıtlanmalıdır.

7- Yazılım Geliştirme ve Test Ortamları
  Geliştirme ortamı: Statik gözden geçirmeler test uzmanları tarafından kontrol edilir.
  >Test ortamı: Yazılan test adımları bu ortamda koşulur ve yeni fonksiyonların kontrolü sağlanır. 
  Ayrıca hata çıkma olasılığı yüksek fonksiyonların regresyonları da bu ortamda kontol edilir.
  >Canlı-öncesi ortamda: son regresyon adımları koşulur ve BETA test grubundan uygulama ile ilgili geri bildirim alınır.
  >Canlı ortama: kritik bir fonksiyon aktarıldıysa, bu ortamda duman test koşumu yapılır ve genel olarak uygulamanın çalıştığının kontrolü gerçekleştirilir.

8- Risk Bazlı Testler Alıştırması

Bölüm-4 İçeriği:

1- API Testleri
2- Web Uygulama Testleri
3- Mobil UYgulama Testleri

Bölüm-5 İçeriği






