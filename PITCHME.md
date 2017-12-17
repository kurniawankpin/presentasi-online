## Banten OS

#### Banten Government Open Source

---

### BantOS !

- BantOS merupakan sistem operasi komputer berbasis open source yang dikembangkan oleh Tim Development Pemerintah Provinsi Banten untuk mendukung penerapan teknologi informasi di Pemerintahan Provinsi Banten. |
- Sistem operasi ini telah dilengkapi dengan aplikasi perkantoran lengkap, WPS Office dan Only Office. Kedua aplikasi tersebut tersedia dalam sekali instal BantOS |
---

### BantOS Features

- Ramah untuk pengguna linux pemula |
- Memiliki koleksi perangkat lunak tersendiri yang sangat lengkap untuk kebutuhan perkantoran |
- BantOS bisa didapatkan secara bebas tanpa perlu membayar lisensi |
- Lebih aman terhadap virus |
- Menerapkan Tema Seni dan Budaya Khas Banten |
- Panduan, bantuan dan dukungan penggunaan BantOS mudah diperoleh. |
---

### Rilis Versi BantOS
BantOS 1.0 (Leuit), diturunkan dari Linux Ubuntu 16.04 LTS, dirilis pada Desember 2017
```
Distributor ID:	Bantos
Description   :	linux bantos 1.0
Release       :	1.0
Codename      :	leuit
``` 
---
BantOS 1.0 Nama kode Leuit
- LEUIT dalam kosa kata bahasa Sunda artinya adalah :  LUMBUNG PADI yaitu sebuah bangunan yang letaknya terpisah dari Imah Gede / Rumah Induk yang digunakan untuk penyimpanan padi. |
- Leuit yang dibangun secara sederhana sejatinya memiliki filosofi dan fungsi tersendiri, Penyimpanan padi di leuit mengajarkan kita tentang menjaga keberlangsungan sesuatu yang berguna dalam jangka waktu yang lama. |

---

#### Tujuan Pengembangan BantOS
- Tujuan pengembangan BantOS adalah menghasilkan distro Linux yang sesuai dengan kebutuhan pengguna linux pemula, khususnya untuk dunia pendidikan, dan pemerintahan. |
- Menghasilkan distro linux yang didesain dengan tampilan grafis dan tema yang menampilkan ciri khas Banten. |
- Adanya Pengembangan distro linux yang akan terus dilakukan secara terbuka kepada publik. |
---

#### Mengenal Sistem Operasi Linux

- Linux merupakan sistem operasi yang barbasis UNIX.  UNIX sendiri adalah sebuah sistem operasi komputer yang diawali dari project Multics (Multiplexed Information and Computing Service) pada tahun 1965.
- UNIX didesain sebagai Sistem operasi yang portabel, multi-tasking dan multi-user. Unix mengubah proses komputasi secara terpusat dalam jaringan dari pada proses tunggal di komputer.

+++
- Linux menggunakan sebuah license yang bernama GNU General Public License(GNU/GPL). Dengan GNU General Public License ini suatu aplikasi ( termasuk sistem operasi ) secara bebas digunakan dan disebarluaskan dimana pengguna bisa mendapatkan program baik dalam bentuk source code  maupun binary code.
- Linux merupakan system operasi yang gratis, terbuka dan tentunya legal karena dibawa lisensi GNU/GPL.
---
#### Aplikasi Perkantoran di BantOS
WPS Office

- WPS Office Writter
![WPS Writter](/assets/image/wps-office.png)
+++
- WPS Office spreadsheets
![WPS Spreadsheets](/assets/image/wps-xls.png)
+++
- WPS Office Presentation
![WPS Presentation](/assets/image/wps-presentation.png)
---
---?code=src/go/server.go&lang=golang&title=Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

---

@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

---

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Image](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Slide-specific Background Images](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting), [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents), and [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

### Template Versions

- #### [Base Template  @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/blue)
- #### [Code Maximized @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/blue?p=codemax)
- #### [Speaker Notes @fa[external-link gp-download]](https://gitpitch.com/gitpitch/templates/blue?p=speaker)

---

### Questions?

<br>

@fa[twitter gp-contact](@gitpitch)

@fa[github gp-contact](gitpitch)

@fa[medium gp-contact](@gitpitch)

---?image=assets/image/gitpitch-audience.jpg

@title[Download this Template!]

### <span class="white">Get your presentation started!</span>
### [Download this template @fa[external-link gp-download]](https://gitpitch.com/template/download/blue)

