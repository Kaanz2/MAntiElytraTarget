# MAntiElytraTarget

MAntiElytraTarget, Elytra PvP sırasında kullanılan **Elytra Target** hilesini tespit etmek ve engellemek amacıyla geliştirilmiştir.

Plugin; oyuncuların Elytra ile uçarken yaptığı şüpheli saldırıları ve normal dışı hızlı slot değişimlerini takip eder. Oyuncu belirlenen log sınırına ulaştığında, config dosyasında ayarlanan ceza komutu konsol üzerinden otomatik olarak çalıştırılır.

Ayrıca oyuncunun ana elinde veya sol elinde havai fişek bulunuyorsa başka bir oyuncuya vurması engellenir ve hasar işlemez.

## Özellikler

- Elytra Target saldırılarını tespit eder.
- Uçarken yapılan şüpheli hızlı slot değişimlerini kontrol eder.
- Ana veya sol elde havai fişek varken oyuncuya vurulmasını engeller.
- Yetkililere anlık tespit logları gönderir.
- Log miktarı ve sıfırlanma süresi ayarlanabilir.
- Uygulanacak ceza komutu tamamen değiştirilebilir.
- Yetkililer uyarıları açıp kapatabilir.
- Ayarlar sunucuyu yeniden başlatmadan yenilenebilir.

## Komutlar

- `/maet alerts` - Elytra Target uyarılarını açar veya kapatır.
- `/maet reload` - Config ayarlarını yeniler.

## Yetkiler

- `maet.alerts` - Tespit loglarını görme ve uyarıları açıp kapatma yetkisi.
- `maet.reload` - Plugin ayarlarını yenileme yetkisi.

## Uyumluluk

- Paper 1.21.4
- Java 21 - 25

Hata bildirimi ve öneriler için Discord: **sindellz2**
