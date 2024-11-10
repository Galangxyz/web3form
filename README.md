# Web3form

![snake_gif](https://github.com/Galangxyz/Galangxyz/blob/output/github-snake-dark.svg)

## 🌐 Socials:
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/https://www.facebook.com/fathir.bimo.7?mibextid=ZbWKwL) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/https://www.instagram.com/galngfp) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/galang-febriansyah-pratama-17035b32b) [![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?logo=Pinterest&logoColor=white)](https://pinterest.com/https://pin.it/18iUlLoIs) [![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?logo=TikTok&logoColor=white)](https://tiktok.com/@https://www.tiktok.com/@lusaha.s1h?_t=8rFkSFC18Ku&_r=1) 

</h3>
<p align="left">
<a href="https://twitter.com/gsap_05" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="gsap_05" height="30" width="40" /></a>
<a href="/https://feeds.feedburner.com/mataberita" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/rss.svg" alt="https://feeds.feedburner.com/mataberita" height="30" width="40" /></a>
</p>

# Form Kontak
Form kontak sangat penting karena memungkinkan pengunjung menghubungi Anda langsung melalui situs tanpa harus membuka email. Berikut langkah-langkah mudah untuk memasangnya.

# Apa Itu Web3Forms?
Web3Forms adalah layanan API gratis yang memungkinkan Anda menambahkan form kontak ke website tanpa memerlukan backend atau server-side scripting. Layanan ini ideal untuk platform statis seperti Blogger atau GitHub Pages.

# Langkah-langkah Memasang Form Kontak
Daftar di [Web3Forms](https://web3forms.com/#start)
Langkah pertama adalah membuat akun di Web3Forms. Proses pendaftarannya mudah dan gratis.

Setelah berhasil mendaftar, Anda akan diberikan Access Key yang akan digunakan pada form kontak Anda nanti.


# Buat Formulir HTML
Setelah mendapatkan Access Key, buat form kontak di halaman HTML Anda. Berikut contoh form sederhana:
 ```
<form action="https://api.web3forms.com/submit" method="POST">
    <input type="hidden" name="access_key" value="ACCESS_KEY_ANDA">
   
    <div class="field">
        <label for="name">Nama</label>
        <input type="text" name="name" id="name" placeholder="Masukkan Nama Anda" required>
    </div>
    
    <div class="field">
        <label for="email">Email</label>
        <input type="email" name="email" id="email" placeholder="Masukkan Email Anda" required>
    </div>
    
    <div class="field">
        <label for="subject">Subjek</label>
        <input type="text" name="subject" id="subject" placeholder="Judul Pesan Anda" required>
    </div>
    
    <div class="field">
        <label for="message">Pesan</label>
        <textarea name="message" id="message" rows="5" placeholder="Tulis Pesan Anda" required></textarea>
    </div>
    
    <button type="submit">Kirim Pesan</button>
</form>
```
Jangan lupa mengganti ACCESS_KEY_ANDA dengan Access Key yang telah Anda dapatkan.

Tambahkan Opsi Pengalihan Setelah Pengiriman
Untuk mengalihkan pengunjung ke halaman "terima kasih" setelah pengiriman form berhasil, tambahkan input tersembunyi seperti ini:
```
<input type="hidden" name="redirect" value="https://domainanda.com/thank-you">
```
Hal ini memastikan pengunjung tahu bahwa pesan mereka telah berhasil dikirim.

## Fitur Tambahan
Email Konfirmasi Otomatis: Anda dapat mengirim salinan pesan ke pengirim dengan menambahkan kode ini:
```
<input type="hidden" name="reply_to" value="%email%">
Kustomisasi Tampilan Form: Tambahkan CSS untuk mempercantik tampilan form sesuai desain situs Anda. Contoh sederhana:

css
.field {
    margin-bottom: 15px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    padding: 10px 15px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}
```
# Kesimpulan
Dengan Web3Forms, Anda bisa memasang form kontak dengan mudah tanpa perlu coding backend atau server tambahan. Prosesnya cepat, gratis, dan mudah diintegrasikan dengan platform statis seperti Blogger dan GitHub Pages.

Selamat mencoba!
