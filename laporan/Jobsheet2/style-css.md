## Penjelasan CSS

### Reset & Base

| Kode | Penjelasan |
|---|---|
| `/* ===== Reset & Base ===== */` | Komentar untuk menandai bagian pengaturan dasar CSS. |
| `* {` | Memilih seluruh elemen HTML pada halaman. |
| `box-sizing: border-box;` | Membuat ukuran elemen sudah termasuk padding dan border. |
| `margin: 0;` | Menghilangkan margin bawaan dari semua elemen. |
| `padding: 0;` | Menghilangkan padding bawaan dari semua elemen. |
| `}` | Menutup aturan CSS. |
| `body {` | Memilih elemen body sebagai bagian utama halaman. |
| `font-family: "Segoe UI", Arial, sans-serif;` | Menentukan jenis font yang digunakan pada halaman. |
| `color: #3d2525;` | Menentukan warna teks utama menjadi cokelat gelap. |
| `background-color: #f8f1f2;` | Memberikan warna latar belakang halaman dengan warna pink muda. |
| `line-height: 1.5;` | Mengatur jarak antarbaris teks agar lebih mudah dibaca. |
| `}` | Menutup aturan CSS untuk body. |
| `a {` | Memilih semua elemen link atau tautan. |
| `color: #7b1e2b;` | Memberikan warna maroon pada link. |
| `text-decoration: none;` | Menghilangkan garis bawah pada link. |
| `transition: 0.2s;` | Membuat perubahan tampilan menjadi lebih halus selama 0,2 detik. |
| `}` | Menutup aturan CSS untuk link. |
| `a:hover {` | Mengatur tampilan link ketika kursor diarahkan ke link. |
| `color: #a83244;` | Mengubah warna link ketika hover. |
| `text-decoration: underline;` | Menambahkan garis bawah pada link ketika hover. |
| `}` | Menutup aturan a:hover. |

### Header & Navbar

| Kode | Penjelasan |
|---|---|
| `/* ===== Header & Navbar ===== */` | Komentar untuk menandai bagian header dan navbar. |
| `header {` | Memilih elemen semantic header. |
| `background: linear-gradient(135deg, #7b1e2b, #a83244);` | Memberikan background gradasi warna maroon pada header. |
| `color: #fff;` | Mengatur warna teks header menjadi putih. |
| `padding: 1rem 1.5rem;` | Memberikan jarak bagian dalam header secara vertikal dan horizontal. |
| `display: flex;` | Menggunakan Flexbox untuk mengatur posisi isi header. |
| `align-items: center;` | Membuat isi header berada di tengah secara vertikal. |
| `justify-content: space-between;` | Memberikan jarak antara judul aplikasi dan navbar. |
| `flex-wrap: wrap;` | Memungkinkan isi header berpindah baris jika ruang tidak mencukupi. |
| `border-bottom: 4px solid #d8a0a8;` | Memberikan garis bawah berwarna pink muda pada header. |
| `box-shadow: 0 3px 8px rgba(90, 20, 30, 0.2);` | Memberikan efek bayangan pada header. |
| `}` | Menutup aturan CSS untuk header. |
| `header h1 {` | Memilih elemen h1 yang berada di dalam header. |
| `font-size: 1.4rem;` | Mengatur ukuran tulisan judul aplikasi. |
| `letter-spacing: 0.5px;` | Memberikan sedikit jarak antarhuruf pada judul. |
| `}` | Menutup aturan header h1. |
| `header nav ul {` | Memilih daftar menu yang berada di dalam navbar. |
| `list-style: none;` | Menghilangkan tanda bullet pada daftar menu. |
| `display: flex;` | Menyusun menu navbar secara horizontal menggunakan Flexbox. |
| `gap: 0.7rem;` | Memberikan jarak antar menu navbar. |
| `}` | Menutup aturan header nav ul. |
| `header nav a {` | Memilih link yang terdapat di dalam navbar. |
| `color: #fff;` | Membuat warna tulisan menu menjadi putih. |
| `font-weight: 500;` | Membuat tulisan menu sedikit lebih tebal. |
| `padding: 0.4rem 0.8rem;` | Memberikan ruang di sekitar tulisan menu. |
| `border-radius: 20px;` | Membuat area menu memiliki sudut yang sangat melengkung. |
| `transition: 0.2s;` | Membuat perubahan tampilan menu menjadi lebih halus. |
| `}` | Menutup aturan header nav a. |
| `header nav a:hover {` | Mengatur tampilan menu ketika kursor diarahkan ke menu. |
| `background-color: rgba(255, 255, 255, 0.15);` | Memberikan warna putih transparan pada menu ketika hover. |
| `text-decoration: none;` | Menghilangkan garis bawah pada menu ketika hover. |
| `}` | Menutup aturan header nav a:hover. |

### Main Layout

| Kode | Penjelasan |
|---|---|
| `/* ===== Main Layout ===== */` | Komentar untuk menandai bagian pengaturan layout utama. |
| `main {` | Memilih elemen semantic main. |
| `max-width: 1000px;` | Membatasi lebar maksimal konten utama sebesar 1000 piksel. |
| `margin: 2rem auto;` | Memberikan jarak atas dan bawah serta membuat main berada di tengah halaman. |
| `padding: 0 1.5rem;` | Memberikan jarak bagian dalam pada sisi kanan dan kiri main. |
| `}` | Menutup aturan CSS untuk main. |
| `section {` | Memilih seluruh elemen section. |
| `background-color: #fff;` | Memberikan warna putih pada background section. |
| `border-radius: 14px;` | Membuat sudut section menjadi melengkung. |
| `padding: 1.5rem;` | Memberikan jarak antara isi section dengan tepinya. |
| `margin-bottom: 1.5rem;` | Memberikan jarak di bawah setiap section. |
| `box-shadow: 0 4px 12px rgba(90, 20, 30, 0.08);` | Memberikan efek bayangan tipis pada section. |
| `border: 1px solid #ead4d7;` | Memberikan garis tepi tipis pada section. |
| `transition: 0.2s;` | Membuat perubahan efek section menjadi lebih halus. |
| `}` | Menutup aturan CSS untuk section. |
| `section:hover {` | Mengatur tampilan section ketika kursor diarahkan ke atasnya. |
| `box-shadow: 0 6px 16px rgba(90, 20, 30, 0.12);` | Membuat bayangan section lebih terlihat saat hover. |
| `}` | Menutup aturan section:hover. |
| `section h2 {` | Memilih judul h2 yang berada di dalam section. |
| `margin-bottom: 1rem;` | Memberikan jarak di bawah judul section. |
| `color: #7b1e2b;` | Memberikan warna maroon pada judul section. |
| `border-left: 5px solid #a83244;` | Menambahkan garis maroon di sebelah kiri judul. |
| `padding-left: 0.7rem;` | Memberikan jarak antara garis kiri dan tulisan judul. |
| `}` | Menutup aturan section h2. |

### Kartu Statistik

| Kode | Penjelasan |
|---|---|
| `/* ===== Kartu Statistik ===== */` | Komentar untuk menandai bagian kartu statistik. |
| `main section:nth-of-type(2) {` | Memilih section kedua yang terdapat di dalam main. |
| `display: grid;` | Menggunakan CSS Grid untuk menyusun kartu statistik. |
| `grid-template-columns: repeat(3, 1fr);` | Membuat tiga kolom dengan ukuran yang sama. |
| `gap: 1rem;` | Memberikan jarak antar kartu statistik. |
| `}` | Menutup aturan section statistik. |
| `main section:nth-of-type(2) article {` | Memilih setiap article yang terdapat pada section statistik. |
| `background: linear-gradient(135deg, #fbecef, #fff7f8);` | Memberikan background gradasi pink muda pada kartu statistik. |
| `border-radius: 12px;` | Membuat sudut kartu menjadi melengkung. |
| `padding: 1.25rem;` | Memberikan jarak antara isi kartu dengan tepi kartu. |
| `text-align: center;` | Membuat teks di dalam kartu berada di tengah. |
| `border: 1px solid #efd0d5;` | Memberikan garis tepi tipis pada kartu. |
| `box-shadow: 0 3px 8px rgba(90, 20, 30, 0.06);` | Memberikan bayangan tipis pada kartu. |
| `transition: 0.2s;` | Membuat perubahan efek kartu menjadi lebih halus. |
| `}` | Menutup aturan article statistik. |
| `main section:nth-of-type(2) article:hover {` | Mengatur tampilan kartu ketika kursor diarahkan ke kartu. |
| `transform: translateY(-3px);` | Menggeser kartu sedikit ke atas saat hover. |
| `box-shadow: 0 6px 12px rgba(90, 20, 30, 0.12);` | Membuat bayangan kartu lebih jelas ketika hover. |
| `}` | Menutup aturan hover kartu. |
| `main section:nth-of-type(2) article h3 {` | Memilih judul h3 pada kartu statistik. |
| `font-size: 0.95rem;` | Mengatur ukuran tulisan judul kartu. |
| `color: #745b60;` | Memberikan warna cokelat keabu-abuan pada judul kartu. |
| `margin-bottom: 0.5rem;` | Memberikan jarak di bawah judul kartu. |
| `}` | Menutup aturan article h3. |
| `main section:nth-of-type(2) article p {` | Memilih paragraf yang berisi angka statistik. |
| `font-size: 1.8rem;` | Membuat angka statistik berukuran lebih besar. |
| `font-weight: 700;` | Membuat angka statistik menjadi tebal. |
| `color: #7b1e2b;` | Memberikan warna maroon pada angka statistik. |
| `}` | Menutup aturan article p. |

### Tabel

| Kode | Penjelasan |
|---|---|
| `/* ===== Tabel ===== */` | Komentar untuk menandai bagian pengaturan tabel. |
| `table {` | Memilih elemen tabel. |
| `width: 100%;` | Membuat tabel menggunakan seluruh lebar area yang tersedia. |
| `border-collapse: collapse;` | Menggabungkan border antar sel tabel agar lebih rapi. |
| `border-radius: 10px;` | Membuat sudut tabel menjadi melengkung. |
| `overflow: hidden;` | Menyembunyikan bagian tabel yang keluar dari area sudut melengkung. |
| `box-shadow: 0 2px 6px rgba(90, 20, 30, 0.06);` | Memberikan bayangan tipis pada tabel. |
| `}` | Menutup aturan CSS untuk tabel. |
| `th,` | Memilih elemen header tabel. |
| `td {` | Memilih sel data pada tabel. |
| `text-align: left;` | Membuat isi sel tabel rata kiri. |
| `padding: 0.65rem 0.75rem;` | Memberikan jarak di dalam setiap sel tabel. |
| `border-bottom: 1px solid #ead4d7;` | Memberikan garis bawah tipis pada setiap sel. |
| `}` | Menutup aturan th dan td. |
| `thead {` | Memilih bagian kepala tabel. |
| `background: linear-gradient(135deg, #7b1e2b, #a83244);` | Memberikan background gradasi maroon pada kepala tabel. |
| `color: #fff;` | Membuat tulisan pada kepala tabel berwarna putih. |
| `}` | Menutup aturan thead. |
| `tbody tr:nth-child(even) {` | Memilih baris tabel dengan nomor genap. |
| `background-color: #fdf6f7;` | Memberikan warna background berbeda pada baris genap. |
| `}` | Menutup aturan baris genap. |
| `tbody tr:hover {` | Mengatur tampilan baris tabel ketika kursor diarahkan ke baris tersebut. |
| `background-color: #fbecef;` | Mengubah warna background baris ketika hover. |
| `}` | Menutup aturan hover tabel. |

### Tombol Tabel

| Kode | Penjelasan |
|---|---|
| `/* ===== Tombol pada Tabel ===== */` | Komentar untuk menandai bagian tombol pada tabel. |
| `td button {` | Memilih tombol yang berada di dalam sel tabel. |
| `padding: 0.35rem 0.7rem;` | Memberikan jarak bagian dalam tombol. |
| `margin-right: 0.35rem;` | Memberikan jarak antara tombol Edit dan Hapus. |
| `border: none;` | Menghilangkan border bawaan tombol. |
| `border-radius: 7px;` | Membuat sudut tombol menjadi melengkung. |
| `cursor: pointer;` | Mengubah kursor menjadi pointer ketika diarahkan ke tombol. |
| `font-size: 0.85rem;` | Mengatur ukuran tulisan tombol. |
| `transition: 0.2s;` | Membuat perubahan tampilan tombol menjadi lebih halus. |
| `}` | Menutup aturan tombol tabel. |
| `td button:first-of-type {` | Memilih tombol pertama pada setiap sel tabel, yaitu tombol Edit. |
| `background-color: #c58b3a;` | Memberikan warna cokelat keemasan pada tombol Edit. |
| `color: #fff;` | Membuat tulisan tombol Edit berwarna putih. |
| `}` | Menutup aturan tombol Edit. |
| `td button:first-of-type:hover {` | Mengatur tampilan tombol Edit saat hover. |
| `background-color: #a8732d;` | Mengubah warna tombol Edit menjadi lebih gelap saat hover. |
| `transform: translateY(-1px);` | Menggeser tombol Edit sedikit ke atas saat hover. |
| `}` | Menutup aturan hover tombol Edit. |
| `td button:last-of-type {` | Memilih tombol terakhir pada setiap sel tabel, yaitu tombol Hapus. |
| `background-color: #a83244;` | Memberikan warna maroon pada tombol Hapus. |
| `color: #fff;` | Membuat tulisan tombol Hapus berwarna putih. |
| `}` | Menutup aturan tombol Hapus. |
| `td button:last-of-type:hover {` | Mengatur tampilan tombol Hapus ketika hover. |
| `background-color: #852637;` | Mengubah warna tombol Hapus menjadi lebih gelap saat hover. |
| `transform: translateY(-1px);` | Menggeser tombol Hapus sedikit ke atas saat hover. |
| `}` | Menutup aturan hover tombol Hapus. |

### Form

| Kode | Penjelasan |
|---|---|
| `/* ===== Form ===== */` | Komentar untuk menandai bagian pengaturan form. |
| `form p {` | Memilih elemen paragraf yang terdapat di dalam form. |
| `margin-bottom: 1rem;` | Memberikan jarak antar bagian input form. |
| `}` | Menutup aturan form p. |
| `form label {` | Memilih label yang terdapat di dalam form. |
| `display: block;` | Membuat label tampil sebagai blok sehingga berada pada baris tersendiri. |
| `margin-bottom: 0.35rem;` | Memberikan jarak antara label dan input. |
| `font-weight: 600;` | Membuat tulisan label menjadi lebih tebal. |
| `color: #56383d;` | Memberikan warna cokelat gelap pada label. |
| `}` | Menutup aturan form label. |
| `form input,` | Memilih semua input yang terdapat di dalam form. |
| `form select {` | Memilih elemen select yang terdapat di dalam form. |
| `width: 100%;` | Membuat input dan select menggunakan lebar penuh area yang tersedia. |
| `max-width: 400px;` | Membatasi lebar maksimal input dan select menjadi 400 piksel. |
| `padding: 0.55rem 0.7rem;` | Memberikan jarak di dalam input dan select. |
| `border: 1px solid #d8b9be;` | Memberikan border tipis pada input dan select. |
| `border-radius: 8px;` | Membuat sudut input dan select menjadi melengkung. |
| `font-size: 1rem;` | Mengatur ukuran tulisan pada input dan select. |
| `background-color: #fffafa;` | Memberikan warna background putih kemerahan yang lembut. |
| `transition: 0.2s;` | Membuat perubahan tampilan input menjadi lebih halus. |
| `}` | Menutup aturan form input dan select. |
| `form input:focus,` | Memilih input ketika sedang aktif atau diklik. |
| `form select:focus {` | Memilih select ketika sedang aktif atau diklik. |
| `outline: none;` | Menghilangkan outline bawaan browser ketika input dipilih. |
| `border-color: #a83244;` | Mengubah warna border menjadi maroon ketika input aktif. |
| `box-shadow: 0 0 0 3px rgba(168, 50, 68, 0.12);` | Memberikan efek bayangan tipis di sekitar input saat aktif. |
| `}` | Menutup aturan focus pada input dan select. |

### Tombol Submit

| Kode | Penjelasan |
|---|---|
| `/* ===== Tombol Submit ===== */` | Komentar untuk menandai bagian tombol submit form. |
| `form button[type="submit"] {` | Memilih tombol submit yang terdapat di dalam form. |
| `background: linear-gradient(135deg, #7b1e2b, #a83244);` | Memberikan background gradasi maroon pada tombol Simpan. |
| `color: #fff;` | Membuat tulisan tombol berwarna putih. |
| `border: none;` | Menghilangkan border bawaan tombol. |
| `padding: 0.6rem 1.5rem;` | Memberikan jarak bagian dalam tombol. |
| `border-radius: 8px;` | Membuat sudut tombol menjadi melengkung. |
| `font-size: 1rem;` | Mengatur ukuran tulisan tombol. |
| `cursor: pointer;` | Mengubah kursor menjadi pointer ketika diarahkan ke tombol. |
| `transition: 0.2s;` | Membuat perubahan tampilan tombol menjadi lebih halus. |
| `}` | Menutup aturan tombol submit. |
| `form button[type="submit"]:hover {` | Mengatur tampilan tombol submit ketika kursor diarahkan ke tombol. |
| `background: linear-gradient(135deg, #641823, #852637);` | Mengubah warna gradasi tombol menjadi lebih gelap ketika hover. |
| `transform: translateY(-1px);` | Menggeser tombol sedikit ke atas ketika hover. |
| `box-shadow: 0 4px 8px rgba(90, 20, 30, 0.2);` | Memberikan bayangan pada tombol ketika hover. |
| `}` | Menutup aturan hover tombol submit. |

### Footer

| Kode | Penjelasan |
|---|---|
| `/* ===== Footer ===== */` | Komentar untuk menandai bagian footer. |
| `footer {` | Memilih elemen semantic footer. |
| `text-align: center;` | Membuat teks footer berada di tengah. |
| `margin-top: 2rem;` | Memberikan jarak antara konten utama dan footer. |
| `padding: 1.25rem;` | Memberikan jarak bagian dalam footer. |
| `color: #fff;` | Membuat teks footer berwarna putih. |
| `font-size: 0.9rem;` | Mengatur ukuran tulisan footer sedikit lebih kecil. |
| `background: linear-gradient(135deg, #7b1e2b, #a83244);` | Memberikan background gradasi maroon pada footer. |
| `border-top-left-radius: 18px;` | Membuat sudut kiri atas footer menjadi melengkung. |
| `border-top-right-radius: 18px;` | Membuat sudut kanan atas footer menjadi melengkung. |
| `box-shadow: 0 -2px 6px rgba(90, 20, 30, 0.1);` | Memberikan bayangan tipis di bagian atas footer. |
| `}` | Menutup aturan CSS untuk footer. |
| `footer p {` | Memilih paragraf yang berada di dalam footer. |
| `margin: 0;` | Menghilangkan margin bawaan pada paragraf footer. |
| `}` | Menutup aturan footer p. |