# 🏋️ Kişiye Özel Spor Antrenman Planlayıcı (Personal Workout Planner)

Bu proje, kullanıcıların fiziksel özelliklerine ve spor geçmişine göre dinamik olarak **kişiye özel antrenman programı** oluşturan bir C# konsol uygulamasıdır.

## 📖 Proje Hakkında

Uygulama, kullanıcıdan aldığı temel verileri (yaş, cinsiyet, spor seviyesi vb.) işleyerek, haftalık antrenman yoğunluğunu ve program içeriğini otomatik olarak belirler. Belirli bir gün sonrası için (örneğin 10 gün sonra) hangi antrenmanın yapılacağını hesaplar.

## 🚀 Özellikler

* **Kişiselleştirilmiş Hitap:** Cinsiyet bilgisine göre "Bey" veya "Hanım" hitabı.
* **Yaş Bazlı Yoğunluk:**
    * 30 yaş altı: Haftada 4 antrenman günü.
    * 30 yaş ve üzeri: Haftada 3 antrenman günü.
* **Cinsiyet Bazlı Program:**
    * Erkekler: 7 günlük döngü.
    * Kadınlar: 6 gün program + 1 gün tatil döngüsü.
* **Seviye Kontrolü:** Başlangıç, Orta ve İleri seviyeye göre değişen egzersiz tipleri.
* **Dinamik Gün Hesaplama:** Kullanıcının spora başlayacağı günü baz alarak, ileri bir tarihteki antrenman türünü (Kardiyo, Güç, Esneme vb.) matematiksel modülüs işlemi ile hesaplar.

## 🛠️ Kullanılan Teknolojiler

* C# Programming Language
* .NET Framework / .NET Core
* Console Application

## 📸 Örnek Çıktı

```text
Adınız: Ahmet
Soyadınız: Yılmaz
Cinsiyetiniz: erkek
Doğduğunuz yıl: 2000
Spor Seviyeniz: orta
Kaç gün sonra spora başlayacaksınız? 5

Sayın Ahmet Yılmaz Bey 25 yaşındasınız. 
5 gün sonrası için planlanan antrenman: Dinlenme olacaktır.
