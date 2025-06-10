# Membaca Data: Mengungkap Distribusi Rating dan Genre Buku di GoodReads
## 📔 Tentang GoodReads
![1_N1k6cmyD9h99w4S-CEaKXw](https://github.com/user-attachments/assets/a11b923c-1839-4be7-a67b-63e7c9d9865a)

GoodReads ([https://www.goodreads.com/](https://www.goodreads.com/)) adalah situs terbesar di dunia bagi para pembaca dan rekomendasi buku. Misi situs ini adalah membantu pembaca menemukan buku yang mereka sukai dan mendapatkan lebih banyak manfaat dari membaca. GoodReads menyediakan ribuan judul buku dengan berbagai informasi sehingga banyak hal yang dapat diungkap dari scraping data pada situs tersebut. Salah satu fitur dari GoodReads adalah **List** yang memungkinkan pembaca melakukan voting pada buku sesuai dengan kriteria tertentu.

## 📈 Tentang Data
Dalam proyek ini, kami melakukan scrapping data dari 2 list pada website GoodReads:
- 🌎 [Best books ever (worldwide)](https://www.goodreads.com/list/show/1.Best_Books_Ever?page=)
- 🆔 [Buku Indonesia Terbaik Sepanjang Sejarah](https://www.goodreads.com/list/show/1572.Buku_Indonesia_Sepanjang_Masa?page=)

Tahapan pengerjaan adalah sebagai berikut

<img width="260" alt="image" src="https://github.com/user-attachments/assets/c5d00d80-91ee-4ca9-9fa2-95708c857d03" />

### Scrapping Data
Scrapping dilakukan menggunakan Python dengan library BeautifulSoup. Python digunakan agar proses scraping dapat dikustomisasi sesuai dengan kebutuhan analisis.

[Link program scraping data](https://github.com/logankusuma/goodreads_scrape/blob/main/Scrape_Goodreads.ipynb?short_path=8506729)


### Penyimpanan MongoDB
Data hasil Scrapping selanjutnya disimpan dalam MongoDB untuk pengolahan dan agregasi lebih lanjut. MongoDB dipilih karena mampu menangani data besar dan semi-terstruktur secara fleksibel dan efisien.

Data yang disimpan dalam MongoDB adalah sebagai berikut

<img width="290" alt="Screenshot 2025-06-10 220307" src="https://github.com/user-attachments/assets/d8326d00-5490-40bd-bf57-530e53112dd0" />

## 📚 Tentang Buku
Berikut hasil analisis agregasi dan text analysis yang kami lakukan seputar rating dan genre buku di GoodReads

[Link Canva](https://www.canva.com/design/DAGp9nwnbxQ/OM4MGuziG6Dk56XFr7plcw/edit?utm_content=DAGp9nwnbxQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)


## 🧑‍💻 Tentang Kami
Anggota Kelompok:
- Andi Illa Erviani Nensi (M0501241035)
- [Jasmin Nur Hanifa](https://github.com/heyitsjasmin) (M0501241060)
- [Logananta Puja Kusuma](https://github.com/logankusuma) (M0501241028)
- [Meavi Cintani](https://github.com/meavi2501cintani) (M0501241040)
- [Yeky Abil Nizar](https://github.com/Yekyabilnizar) (M0501241043)
