🛒 Müşteri Alışveriş Davranışı Analizi
Bu proje, 3.900 işlemlik bir veri kümesini kullanarak müşteri harcama alışkanlıklarını, segmentasyon stratejilerini ve abonelik davranışlarını analiz eder. Python ile temizlenen veri, MySQL üzerinde sorgulanmış ve Power BI ile görselleştirilmiştir.

📊 Proje Özeti

Veri Seti: 3,900 Satır, 18 Sütun.


Teknoloji Yığını: Python (Pandas), SQL (MySQL), Power BI.
+2


Temel Hedef: Müşteri segmentasyonu ve gelir artırıcı stratejiler için veri odaklı içgörüler sağlamak.

🛠️ Veri İşleme Süreci (Python)

Temizlik: Review Rating sütunundaki eksik veriler kategori bazlı medyan değerler ile dolduruldu.


Feature Engineering: * Yaş grupları (age_group) oluşturuldu.

Satın alma sıklığı gün cinsinden hesaplandı.


Veritabanı Entegrasyonu: Temizlenen veri MySQL'e aktarıldı.

🔍 SQL Analizlerinden Önemli Bulgular

Gelir Dağılımı: Erkek müşteriler ($157,890) kadın müşterilere ($75,191) kıyasla yaklaşık 2 kat daha fazla gelir üretmiştir.
+1


Müşteri Sadakati: Veri seti %80 oranında "Loyal" (Sadık) müşterilerden oluşmaktadır (3,116 müşteri).


Abonelik Etkisi: İlginç bir şekilde, abone olmayanların ortalama harcaması ($59.87), abonelerden ($59.49) çok az da olsa daha yüksektir.


Kritik Ürünler: En çok indirim oranına sahip ürünler %50 ile "Hat" ve %49.66 ile "Sneakers" olmuştur.

📈 Power BI Dashboard
Dashboard şunları içerir:

Kategori bazlı gelir dağılımı (Giyim en yüksek paya sahip).
+1

Yaş gruplarına göre satış performansı.

Abonelik durumuna göre müşteri yüzdeleri (%73 Abone Değil).
