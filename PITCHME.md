### Tim Banten Development

##### Pengantar Praktis Markdown Presentasi Online

---
@title[PITCHME.md]

#### GitPitch mengubah <span class="gold">PITCHME.md</span> menjadi
#### interactive online and offline slideshows.
<br>
<span class="aside">Just like this one...</span>
---
#### Tidak lagi <span class="gray">Menggunakan Keynote</span>.
#### Tidak lagi <span class="gray">Menggunakan Powerpoint</span>.
<br>
#### Menulis dengan <span class="gold">Markdown</span>.
#### Kemudian  <span class="gold">Git-Commit di Github</span>.
---

@title[Fork Repository]

#### Membuat slideshow konten dengan GitHub Flavored Markdown.
#### Pada repository Pemerintah Provinsi Banten.

Step 1. clone repository github
> https://github.com/bantenprov/presentasi-online

<span style="font-size:0.6em; color:gray">Selanjutnya.</span>
@fa[arrow-down]
+++
@title[Buat branch]

Step 2. Membuat branch untuk presentasi anda
```shell
$ git checkout -b NAMA-PRESESNTASI-ANDA .
```
<span style="font-size:0.6em; color:gray">Selanjutnya.</span>
@fa[arrow-down]
+++
@title[Konten Slideshow]

Step 3. Membuat file PITCHME.md
```
# Hello, World!  ---  ## The End.
```
<span style="font-size:0.6em; color:gray">Selanjutnya.</span>
@fa[arrow-down]
+++
Step 4. Commit di Github
```shell
$ git add PITCHME.md
$ git commit -m "New slideshow content."
$ git push

Done!
```
<span style="font-size:0.6em; color:gray">Selanjutnya.</span>
@fa[arrow-down]
+++
Step 5. GET THE WORD OUT!
```
https://gitpitch.com/bantenprov/presentasi-online/$branch
```
---
@title[Tips]
## Tips!
Untuk *best viewing experience*   
tekan **F** key untuk fullscreen slideshow.

---
@title[Slide Gambar]
### Slide Gambar
## [ Inline ]
<span style="font-size:0.6em; color:gray">Selanjutnya.</span>
@fa[arrow-down]
+++
#### Membuat Visual konten
Gunakan gambar untuk memberikan visualisasi di presentasi slideshow Anda.
<span style="font-size:0.6em; color:gray">Contoh Gambar.</span>
@fa[arrow-down]
+++

```
![contoh](/assets/image/gambar.jpg)
```
<br>
![gambar](/assets/image/wps-office.png)

---
@title[slide Video]
## Video Slides
## [ Inline ]
<span style="font-size:0.6em; color:gray">Press Down key for examples.</span> |
<span style="font-size:0.6em; color:gray">See <a href="https://github.com/gitpitch/gitpitch/wiki/Video-Slides" target="_blank">GitPitch Wiki</a> for details.</span>

#VSLIDE

#### Bring Your Presentations Alive

<br>

Embed *YouTube*, *Vimeo*, *MP4* and *WebM* inline on any slide.

#VSLIDE

![YouTube Video](https://www.youtube.com/embed/dNJdJIwCF_Y)

#VSLIDE

![Vimeo Video](https://player.vimeo.com/video/125471012)

#VSLIDE

![MP4 Video](http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4)

## Terimakasih
