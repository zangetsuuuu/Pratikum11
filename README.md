Nama : Rafif Isdarufa Athallah

NIM : 312210299

Kelas : TI.22.A3

---

## Web Scraping

Web scraping adalah proses pengambilan data dari sebuah website dengan menggunakan script atau program. Scraper mengambil informasi dari halaman website dan menyimpan informasi tersebut ke dalam database atau file. Web scraping digunakan untuk mengumpulkan data dari website yang tidak menyediakan API atau untuk mengambil data dalam jumlah besar yang tidak dapat diunduh dengan cara manual. Namun, web scraping dilakukan sesuai dengan peraturan dan perjanjian penggunaan website yang bersangkutan.

## Challenge

![WebScraping(1)](https://user-images.githubusercontent.com/115514467/213097631-ba74ef19-637f-42bf-8ae3-ef774b5c4db9.jpg)

- `!pip install request` digunakan untuk menginstall library Python yang bernama "requests". Library ini digunakan untuk melakukan HTTP requests pada sebuah website. Setelah diinstall, kode Python dapat menggunakan fungsi-fungsi dari library tersebut untuk mengirim permintaan ke website, seperti permintaan GET untuk mengambil data dari sebuah halaman atau permintaan POST untuk mengirim data ke sebuah halaman. Dengan library requests, kita dapat melakukan web scraping, mengambil data dari API, mengirim data ke formulir, dll.
- `!pip install pandas` digunakan untuk menginstall library Python yang bernama "pandas". Library ini digunakan untuk melakukan manipulasi data dan analisis data. Setelah diinstall, kode Python dapat menggunakan fungsi-fungsi dari library tersebut untuk memanipulasi dan menganalisis data. Pandas menyediakan struktur data yang disebut DataFrame, yang mirip dengan tabel pada database relasional atau spreadsheet pada aplikasi seperti Microsoft Excel.
- `!pip install BeautifulSoup4` digunakan untuk menginstall library Python yang bernama "BeautifulSoup4". Library ini digunakan untuk parsing dan mengekstrak data dari HTML dan XML. Setelah diinstall, kode Python dapat menggunakan fungsi-fungsi dari library tersebut untuk mengekstrak data dari website yang di-scrape. Beautiful Soup menggunakan sintaks berbasis elemen HTML atau XML untuk mengekstrak data yang diinginkan, seperti tag spesifik, class, atau id. Library ini sangat membantu dalam tugas web scraping, karena memudahkan untuk mengekstrak data dari halaman web yang di scrape.

---

![WebScraping(2)](https://user-images.githubusercontent.com/115514467/213097615-1b505752-b4ee-4bb7-abae-f40bb6e45366.jpg)

- Mendapatkan data lowongan kerja dari situs web Glints dengan mengirim permintaan GET menggunakan library Python `requests` ke halaman web yang berisi informasi lowongan kerja. Kemudian menganalisis konten halaman web yang didapat dari permintaan GET tersebut menggunakan library `BeautifulSoup` dan parser HTML.
- Selanjutnya, mencari semua elemen HTML dengan atribut `div` dan `id` yang sesuai, yaitu `__next`, dari elemen-elemen tersebut, mengekstrak informasi pekerjaan, lokasi, dan nama perusahaan dengan mencari elemen yang memiliki atribut `class` yang sesuai. Kemudian menyimpan informasi yang diambil dalam sebuah list yang sesuai.
- Kemudian, mengubah list yang didapat menjadi DataFrame dengan menggunakan library `pandas` dan menyimpannya dalam variabel `df` dan menampilkan DataFrame tersebut, sehingga kita dapat melihat informasi lowongan kerja yang diambil dari situs web Glints.

---

### Sekian, terimakasih
