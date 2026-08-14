# Kurulum

Bu paket bir GitHub **profil README reposu** olarak hazırlandı. Çalışması için ekstra servis, sayaç veya üçüncü taraf görsel bağlantısı gerekmez.

## 1. Profil reposunu oluştur

GitHub'da adı kullanıcı adınla **birebir aynı** olan yeni bir `Public` repo oluştur.

Örnek: GitHub kullanıcı adın `bedirhanxyz` ise repo adı da `bedirhanxyz` olmalı.

## 2. Dosyaları yükle

Bu paketteki aşağıdaki yapıyı repo köküne olduğu gibi yükle:

```text
README.md
SETUP.md
assets/
  divider.svg
  noir-avatar.png
  noir-istanbul-banner.png
  stack.svg
  status-line.svg
```

Profil README'si otomatik olarak GitHub profilinde görünür.

## 3. Avatarı kullan

`assets/noir-avatar.png` dosyasını GitHub profil fotoğrafı olarak yükle. Dairesel kırpma için güvenli boşluğu hazırdır.

## 4. İstersen kişiselleştir

`README.md` içinde yalnızca şu alanları değiştirmen yeterli:

- İsim veya yaş
- `Yekta v5` açıklaması
- Teknoloji listesi
- İletişim / web sitesi bağlantıları

Tasarımın bozulmaması için banner ve SVG dosyalarının adlarını değiştirme; değiştirirsen README içindeki yolları da güncelle.

## Tasarım notu

- Tüm görseller repoda yerel tutulur; dış servis kapanınca profil bozulmaz.
- Görsel dil yalnızca siyah, beyaz ve gri tonlarından oluşur.
- Anime karakter tamamen özgündür; bilinen bir seriden veya karakterden kopyalanmamıştır.
- README, GitHub'ın desteklediği standart Markdown ve güvenli HTML özellikleriyle hazırlanmıştır.

