WiFi Profilleri ve Şifreleri Görüntüleyici
Bu Python betiği, Windows işletim sisteminde kayıtlı WiFi profillerini ve şifrelerini görüntülemek için tasarlanmıştır.

Özellikler
Kayıtlı tüm WiFi ağlarını listeler

Her ağ için kayıtlı şifreyi gösterir (erişilebilirse)

Basit ve kullanımı kolay komut satırı arayüzü

Nasıl Kullanılır
Python'un sisteminizde yüklü olduğundan emin olun

Betiği çalıştırın: python wifi.py

Çıktıyı kontrol edin - WiFi adları ve karşılarında şifreler görüntülenecektir

Örnek Çıktı
text
WiFi_Adi_1                | sifre123
WiFi_Adi_2                | 
Cafe_WiFi                 | ERROR OCCURRED
Gereksinimler
Python 3.x

Windows işletim sistemi

Yönetici hakları (bazı şifreleri görüntülemek için gerekli olabilir)

Açıklama
Bu betik, Windows'un netsh komut satırı aracını kullanarak kayıtlı WiFi profillerini ve şifrelerini çeker. Betik, her profil için "key=clear" parametresiyle şifre içeriğini görüntülemeye çalışır. Şifreler yalnızca kullanıcının daha önce bağlandığı ve Windows'un şifreyi kaydettiği ağlar için görüntülenebilir.

Önemli Not
Bu betik yalnızca kendi bilgisayarınızdaki kayıtlı WiFi şifrelerini görüntülemek içindir. Başka birinin WiFi şifrelerini izinsiz almak yasa dışıdır ve etik değildir. Bu betiği yalnızca kendi ağlarınızın şifrelerini unuttuğunuzda kurtarmak amacıyla kullanın.
