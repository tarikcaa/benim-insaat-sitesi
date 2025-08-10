SANCAKLAR YAPI - Static site bundle
----------------------------------

Dosya yapısı:
  index.html
  assets/
    logo.jpg (şirket logosu)
    style.css
    projects/
      project1.jpg
      project2.jpg
      project3.jpg
      project4.jpg

Nasıl deploy edilir:
  1) Bu klasörü olduğu gibi bir sunucuya kopyala veya bir Git repo oluşturup GitHub/GitLab'a push et.
  2) GitHub Pages, Netlify veya Vercel gibi servislere bağlayarak hızlıca yayınlayabilirsiniz.
  3) Alan adı (domain) bağlamak isterseniz DNS ayarlarından A veya CNAME yönlendirmesi yapın.

Proje fotoğrafı ekleme:
  - assets/projects/ içine resim yükle (ör. project5.jpg).
  - index.html içindeki ilgili bölüme yeni bir <article class="project-card"> ... </article> ekle (ör mevcut card'ları kopyala).
  - Resimleri web için sıkıştır (1200x800 ve 200-400KB ideal).

Form gönderimi:
  - Şu an demo: form gerçek bir backend'e gönderilmiyor.
  - Gerçek e-posta almak için Formspree / Getform / Netlify Forms veya küçük bir backend (Node/Express + nodemailer) ekleyin.

İletişim:
  - Bana bu dosyaları zip'leyip vermemi istersen, gönderirim.
