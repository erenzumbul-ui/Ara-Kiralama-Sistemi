# Araç Kiralama Sistemi

# ★ Araç Yönetimi Sayfası

Bu sayfa programı açtığımızda karşımıza çıkan ilk sayfadır.

Kiralanabilecek araçları bu kısımdan ekliyoruz.

Araç markası, araç modeli, araç yılı, araç plakası ve bu aracaın günlük kira fiyatını giriyoruz. Sonrasında "Aracı Ekle" butonuna basarak aracı ekliyoruz.

Eğer eklediğimiz araçları görüntülemek istersek yine aynı sayfanın alt kısmından görüntüleyebiliyoruz. Aracı silmek istersek de mevcut araçlar kısmından seçerek "Seçili Aracı Sil" butonundan silebiliyoruz.

Sayfanın genel görünümü şu şekildedir:

![image](https://github.com/user-attachments/assets/39c02db5-c4d5-40bd-bb90-e852ce83ab79)

# ★ Müşteri Yönetimi Sayfası

Bu sayfadan araç kiralayacak müşterileri ekliyoruz.

Müşteri eklemek için müşteri adı, soyadı, tc kimlik numarası (11 sayıdan oluşacak şekilde), telefon numarası ekliyoruz. Gerekli bilgileri yazdıktan sonra "Müşteri Ekle" butonuna basarak müşteri ekliyoruz.

Eğer müşteriyi silmek istersek alttaki "Kayıtlı Müşteriler" kısmından müşteri seçtikten sonra "Seçili Müşteriyi Sil" butonuna basıp siliyoruz.

![image](https://github.com/user-attachments/assets/439bb4e4-2399-419e-98f1-038dc7d17ed2)

# ★ Kiralama İşlemleri Sayfası

Bu sayfadan eklediğimiz araçlar ve müşterileri kullanarak kiralama işlemlerini yapıyoruz.

Yeni bir kiralama oluşturmak için kira süresi devam etmeyen müsait bir araç ve bir müşteri seçiyoruz. Araç ve müşteri seçtikten sonra aracın kaç günlüğüne kiralanacağını yazıyoruz.

Kaç gün kiralanacağını da yazdıktan sonra "Kirala" butonuna basarak kiralıyoruz.

Kiralama yaptıktan sonra devam eden kiralamalar kısmından devam eden kiralamaları görüntüleyebiliyor, süresi tamamen dolmadan kalan süreyi ödeyerek iade edebiliyoruz.

![image](https://github.com/user-attachments/assets/1cad6737-6c3b-4c0f-9e92-ff4c5265629c)

# ★ Veriler Kaydediliyor mu?

Evet, veriler kaydediliyor ancak ek bir klasör olarak değil kodun içine kaydediliyor. Program kapatılıp / açıldığında eklenen müşteriler, araçlar ve devam eden kiralamalar gözükmeye devam ediyor.

# ★  Uygulama nasıl kurulur?

1) Visual studio code programını kurup eklentiler kısmından Python eklentisini kuruyoruz.
2) Sonrasında projeyi indiriyoruz ve kullanmak istediğimiz herhangi biryere rar'dan çıkartıyoruz.
3) arackiralama.py dosyasını Visual Studio Code ile açıyoruz.
4) Sağ üstte çalıştır tuşuna basıyor ve uygulamamızı çalıştırıyoruz.
