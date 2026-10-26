# MES Signature Studio

Ücretsiz, statik, GitHub Pages uyumlu kurumsal Gmail imza oluşturucu.

## Logo değiştirme

`assets/mes-logo.png` dosyası **geçici MES logosudur**. Kulübün gerçek PNG logosunu aynı dosya adıyla değiştirin. Kod değiştirmeniz gerekmez. Tercihen kare, şeffaf arka planlı PNG kullanın.

LinkedIn ve Instagram ikonları `assets/linkedin.png` ve `assets/instagram.png` dosyalarıdır. İkonlar sabit bağlantılara tıklanabilir şekilde bağlanmıştır.

## Ücretsiz GitHub Pages kurulumu

1. GitHub hesabınızla giriş yapın ve yeni **Public** repository oluşturun: örn. `mes-signature-studio`.
2. Bu ZIP'in içindeki `index.html`, `README.md` ve `assets` klasörünü repository köküne yükleyin. ZIP dosyasını tek başına yüklemeyin.
3. Repository → **Settings → Pages** → Source: **Deploy from a branch** → `main` ve `/(root)` → Save.
4. GitHub Pages'in verdiği site bağlantısını açın (genellikle `https://KULLANICI.github.io/mes-signature-studio/`).
5. Üyelere site bağlantısını gönderin. Siteyi kullanmak için üyelerin GitHub hesabı gerekmez.

## Gmail'e ekleme

Formu doldurun → **İmzayı kopyala** → Gmail → Ayarlar → Tüm ayarları görüntüle → Genel → İmza → Yeni imza oluştur → yapıştır → kaydet.

**Önemli:** HTML kopyalama en iyi GitHub Pages üzerindeki HTTPS adresinde çalışır. HTML dosyasını bilgisayarda doğrudan açarsanız otomatik kopyalama tarayıcı tarafından engellenebilir. Kopyalama engellenirse imza seçilir; Ctrl+C ile kopyalayabilirsiniz. Logo ve ikonlar Gmail'de görünsün diye önce GitHub Pages'e yüklenmiş olmalıdır. Gmail veya alıcının e-posta istemcisi uzak resimleri engellerse ikonlar gösterilmeyebilir; bağlantılar ve resim yükleme davranışı alıcıya göre değişir.

## Sabit bağlantılar

- LinkedIn: https://www.linkedin.com/company/marmarames/posts/?feedView=all
- Instagram: https://www.instagram.com/marmarames/

Bağlantılar `index.html` içinde `LINKEDIN` ve `INSTAGRAM` sabitleriyle tanımlanır. Üyeler form üzerinden değiştiremez. Repo dosyalarını düzenleme yetkisi olan yöneticiler değiştirebilir.

## Gizlilik

Form bilgileri sunucuya gönderilmez ve yerel depolamaya kaydedilmez. Tamamen istemci tarafında çalışır. Hosting ve site kullanımı için ücretli servis, veritabanı veya API anahtarı gerekmez.
