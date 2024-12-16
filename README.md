<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous" />

    <!-- Bootstrap Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.4.1/font/bootstrap-icons.css">

    <!-- My CSS -->
    <link rel="stylesheet" href="style.css" />
    <title>Curriculum Vitae | Bulan Sevila Rahma</title>
    <style>
        body {
            background-color: #f8f9fa;
            font-family: Arial, sans-serif;
        }
        header {
            background-color: #fda4ba;
            color: black;
            padding: 50px 0;
        }
        .jumbotron {
            background-color: #e9ecef;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            margin-top: 30px;
            margin-bottom: 20px;
            color: #007bff;
        }
        footer {
            background-color: rgb(2, 92, 114);
            padding: 20px 0;
        }
        .rounded-circle {
            border: 3px solid #007bff;
        }
        .list-unstyled li {
            background: #ffc0cb;
            border-radius: 5px;
            padding: 15px;
            margin-bottom: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header class="text-center">
        <h1>Bulan Sevila Rahma</h1>
        <p>23050881</p>
        <p>Mahasiswa | Ilmu Komputer</p>
        <p>UNIVERSITAS YATSI MADANI</P>
        <P> Jaringan Semantik </p>
        <p>Email: <a href="mailto:bulansevilarahma@gmail.com" class="text-white">bulansevilarahma@gmail.com</a> | Telepon: 0895-2982-8079</p>
    </header>
    <!-- End Header -->

    <!-- Jumbotron -->
    <section class="jumbotron text-center">
      <img src="C:\Users\bulan\Downloads\foto cv.jpg" alt="Bulan Sevila Rahma" width="154" class="rounded-circle img-thumbnail" />
      <h3 class="mt-3">Selamat Datang di CV Saya!</h3>
    </section>
    <!-- End Jumbotron -->

    <!-- About -->
    <section id="about" class="container my-5">
        <h2 class="text-center">Tentang Saya</h2>
        <p>Nama saya Bulan Sevila Rahma, Biasa dipanggil bulan atau lan, lahir di Tangerang pada 27 Mei 2005. Saat ini saya adalah Mahasiswa semester 3 dengan jurusan Ilmu Komputer. Saya memiliki banyak hobi, termasuk berenang, memasak, dan mendengarkan musik. Saya percaya bahwa untuk meraih kesuksesan, kamu harus mempunyai kemauan untuk menjadi sukses, bukan ketakutan akan kegagalan.</p>
    </section>
    <!-- End About -->

    <!-- Experience -->
    <section id="experience" class="container my-5">
        <h2 class="text-center">Pengalaman Kerja</h2>
        <ul class="list-unstyled">
            <li>
                <h5>Packaging</h5>
                <p><strong>PT. CULLETPRIMA</strong> | JUNI 2023 - JULI 2023</p>                 	  </li>
        </ul>
    </section>
    <!-- End Experience -->

    <!-- Education -->
    <section id="education" class="container my-5">
        <h2 class="text-center">Pendidikan</h2>
        <ul class="list-unstyled">
            <li>
                <h5>SMAN 11 KOTA TANGERANG</h5>
                <p>2020 - 2023</p>
            </li>
            <li>
                <h5>MTS ALMAGHFIROH</h5>
                <p>2017 - 2020</p>
            </li>
        </ul>
    </section>
    <!-- End Education -->

    <!-- Skills -->
    <section id="skills" class="container my-5">
        <h2 class="text-center">Keahlian</h2>
        <ul class="list-unstyled">
            <li>Microsoft Office</li>
            <li>Microsoft Excel</li>
            <li>Komunikasi dan Kerja Sama dengan Tim</li>
        </ul>
    </section>
    <!-- End Skills -->

    <!-- Contact -->
    <section id="contact" class="container my-5">
        <h2 class="text-center">Kontak</h2>
        <form>
            <div class="mb-3">
                <label for="name" class="form-label">Nama Lengkap</label>
                <input type="text" class="form-control" id="name" required />
            </div>
            <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class=" form-control" id="email" required />
            </div>
            <div class="mb-3">
                <label for="message" class="form-label">Pesan</label>
                <textarea class="form-control" id="message" rows="3" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Kirim</button>
        </form>
    </section>
    <!-- End Contact -->

    <!-- Footer -->
    <footer class="text-white text-center py-4" style="background-color: rgb(2, 92, 114);">
        <p>Created with <i class="bi bi-heart-fill text-danger"></i> by <a href="https://www.instagram.com/xsvlrhmx/" class="text-white fw-bold">Bulan Sevila Rahma</a></p>
    </footer>
    <!-- End Footer -->

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0" crossorigin="anonymous"></script>
</body>
</html>
