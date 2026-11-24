# CODING AGENT RULES - YOMETAGENCY.COM

Projek ini akan dipakai untuk Wordpress Elementor HTML Element dan Site Custom CSS untuk yometagency.com. Oleh karena itu, projek ini WAJIB mengikuti konfigurasi ini:

- Setiap page adalah HTML.
- Setiap HTML page punya Javascriptnya sendiri dan WAJIB INTERNAL JAVASCRIPT di akhir <body>.
- Untuk design WAJIB pakai CSS EXTERNAL (style.css), TIDAK BOLEH CSS INTERNAL dan INLINE.
- Saat membuat Header (Nav) dan Footer, WAJIB DIBUAT HTML TERPISAH (header.html dan footer.html). Jangan satukan dengan HTML PAGE.
- Custom Font wajib dari Google Font via CSS @import.
- Mengikuti Aturan Detail dibawah ini.

## Aturan Penulisan Konten
- Jangan pernah mengubah copywriting yang diberikan user.
- Jangan menambahkan atau mengurangi apapun yang diberikan user.
- Copywriting harus 100% tepat karena sudah disesuaikan untuk SEO.

## Aturan Projek
- Pastikan struktur projeknya rapih, assets ditempatkan di tempatnya (`assets/images/`).
- Semua page HTML dan CSS ada di root (`yometagency/`), jangan masukkan ke dalam sub-folder.

## Aturan HTML
- Setiap Page = 1 Full HTML Standalone.
- Wajib mengikuti best-practice SEMANTIC HTML agar SEO-nya bagus.
- Wajib mengisi semua ALT IMAGE dengan isi sesuai dengan konteksnya.
- Tidak boleh mengimport Custom Font di HTML karena Custom Font Wajib di CSS.
- Tiap Link Internal untuk navigasi one-page menggunakan anchor link (#what-is-agency, #host, #registration, #withdrawal, #commission, #faqs, #footer).
- Untuk External Link open in new tab (`target="_blank" rel="noopener noreferrer"`).
- Header dan Footer dipisah, dengan membuat `header.html` dan `footer.html`.

## Aturan CSS
- CSS masuk ke Global CSS Elementor yang berlaku sitewide (`style.css`).
- CSS hanya ada 1 dan UNTUK SEMUA PAGE termasuk Header dan Footer.
- Pastikan mengikuti best-practice CSS dengan mendefinisikan variabel berulang dengan `:root { --<property-css> }`.
- Saat menggunakan Custom Font wajib mengimport dari CSS menggunakan CSS `@import`.
- Pastikan Mobile-First Responsive Breakpoint.

## Aturan JS
- Semua TAG script JS harus inline di dalam body TAG HTML (di akhir sebelum `</body>`).
- Menerapkan Internal JS.
- Tidak ada file .js terpisah.
- Dilarang menaruh script di dalam head.

# Aturan Accessibility dan Performa
- Semua img wajib ada alt dan ada isinya sesuai konteksnya.
- loading="lazy" untuk semua gambar di bawah fold.
- Semua img wajib ada attribute width dan height untuk mencegah layout shift (CLS).
- Gunakan fetchpriority="high" untuk aset gambar hero (LCP).

## List Link & Informasi Utama yometagency.com
- Website: https://yometagency.com
- Become Agent Link: https://olamet-client.olamet.net/build2/index.html#/subagentRegister?key=6c46753b47532ae24bd082a7c2810610&guildName=We&nick=We&lang=en
- Become Host Link: https://olamet-client.olamet.net/build2/index.html#/memberInvitation?key=6c46753b47532ae24bd082a7c2810610&guildName=We&nick=We&lang=en
- Host CTA Website: https://yometlive.app
- Telegram Support: https://telegram.me/yometappservice
- WhatsApp Support: https://web.whatsapp.com/send?phone=60182470950&text=
- Instagram: https://www.instagram.com/olametagency
- Facebook Support: https://www.facebook.com/profile.php?id=61587048279977

