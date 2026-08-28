➕ 4. buku/tambah.html — Tambah Buku

| Kode | Penjelasan |
|---|---|
| `<!DOCTYPE html>` | Mendeklarasikan dokumen menggunakan HTML5. |
| `<html lang="id">` | Membuka dokumen HTML dan menentukan bahasa sebagai Bahasa Indonesia. |
| `<head>` | Membuka bagian head dokumen. |
| `<meta charset="UTF-8">` | Menentukan encoding karakter UTF-8. |
| `<title>SIMPUS-Mini \| Tambah Buku</title>` | Menentukan judul halaman pada tab browser. |
| `</head>` | Menutup bagian head. |
| `<body>` | Membuka bagian body yang berisi konten halaman. |
| `<header>` | Membuka elemen semantic header. |
| `<h1>SIMPUS-Mini</h1>` | Menampilkan judul utama aplikasi. |
| `<nav>` | Membuka elemen navigasi. |
| `<ul>` | Membuat daftar menu navigasi. |
| `<li><a href="../index.html">Beranda</a></li>` | Membuat menu Beranda menuju halaman utama. |
| `<li><a href="list.html">Daftar Buku</a></li>` | Membuat menu Daftar Buku. |
| `<li><a href="tambah.html">Tambah Buku</a></li>` | Membuat menu menuju halaman Tambah Buku. |
| `<li><a href="../anggota/list.html">Daftar Anggota</a></li>` | Membuat menu menuju halaman Daftar Anggota. |
| `</ul>` | Menutup daftar menu. |
| `</nav>` | Menutup elemen navigasi. |
| `</header>` | Menutup header. |
| `<main>` | Membuka konten utama halaman. |
| `<section>` | Membuka section untuk form tambah buku. |
| `<h2>Tambah Buku</h2>` | Menampilkan judul bagian Tambah Buku. |
| `<form>` | Membuka form untuk memasukkan data buku. |
| `<label for="judul">Judul</label><br>` | Membuat label untuk field judul buku. |
| `<input type="text" id="judul" name="judul" required>` | Membuat input teks untuk judul buku dan menjadikannya wajib diisi. |
| `<label for="pengarang">Pengarang</label><br>` | Membuat label untuk field pengarang. |
| `<input type="text" id="pengarang" name="pengarang" required>` | Membuat input teks untuk pengarang dan menjadikannya wajib diisi. |
| `<label for="tahun">Tahun Terbit</label><br>` | Membuat label untuk tahun terbit buku. |
| `<input type="number" id="tahun" name="tahun" min="1900" max="2026" required>` | Membuat input angka untuk tahun terbit dengan batas tahun 1900 sampai 2026 dan wajib diisi. |
| `<label for="isbn">ISBN</label><br>` | Membuat label untuk field ISBN. |
| `<input type="text" id="isbn" name="isbn">` | Membuat input teks untuk ISBN buku. |
| `<label for="stok">Stok</label><br>` | Membuat label untuk jumlah stok buku. |
| `<input type="number" id="stok" name="stok" min="0" required>` | Membuat input angka untuk stok dengan nilai minimum 0 dan wajib diisi. |
| `<label for="kategori">Kategori</label><br>` | Membuat label untuk pilihan kategori buku. |
| `<select id="kategori" name="kategori">` | Membuat menu pilihan kategori buku. |
| `<option value="fiksi">Fiksi</option>` | Menambahkan pilihan kategori Fiksi. |
| `<option value="non-fiksi">Non-Fiksi</option>` | Menambahkan pilihan kategori Non-Fiksi. |
| `<option value="referensi">Referensi</option>` | Menambahkan pilihan kategori Referensi. |
| `</select>` | Menutup menu pilihan kategori. |
| `<button type="submit">Simpan</button>` | Membuat tombol untuk mengirim form. |
| `</form>` | Menutup form tambah buku. |
| `</section>` | Menutup section. |
| `</main>` | Menutup konten utama halaman. |
| `<footer>` | Membuka bagian footer. |
| `<p>&copy; 2026 SIMPUS-Mini &mdash; Jobsheet 1</p>` | Menampilkan informasi hak cipta dan keterangan Jobsheet 1. |
| `</footer>` | Menutup footer. |
| `</body>` | Menutup body. |
| `</html>` | Menutup dokumen HTML. |

