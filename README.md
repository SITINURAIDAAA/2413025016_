<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Saya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
            border-radius: 8px;
            opacity: 0;
            transform: translateY(20px);
            animation: fadeIn 1s forwards;
        }
        @keyframes fadeIn {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #ff4500;
            animation: popIn 1s ease-out;
        }
        @keyframes popIn {
            0% { transform: scale(0.5); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }
        h1 {
            color: #2c3e50;
            animation: slideIn 1s ease-in-out;
        }
        @keyframes slideIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .bio, .tasks {
            text-align: left;
            margin-top: 20px;
            padding: 10px;
            border-radius: 5px;
            opacity: 0;
            animation: fadeIn 1.5s forwards;
        }
        .bio {
            background: #e6f7ff;
        }
        .tasks {
            background: #ffebcc;
        }
        .tasks ul {
            list-style-type: none;
            padding: 0;
        }
        .tasks li {
            background: #ffd699;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
            transition: transform 0.3s ease-in-out;
        }
        .tasks li:hover {
            transform: scale(1.05);
        }
        button {
            padding: 10px 20px;
            background: #ff4500;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
            transition: background 0.3s;
        }
        button:hover {
            background: #cc3700;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="profil.JPG" alt="Foto Profil" class="profile-img">
        <h1>Nama Saya</h1>
        <div class="bio">
            <p><strong>Nama:</strong> SITI NUR IADA</p>
            <p><strong>Npm:</strong> 2413025016</p>
            <p><strong>Alamat:</strong> LAMPUNG, Indonesia</p>
            <p><strong>Tanggal Lahir:</strong> 19 september 2006</p>
            <p><strong>Hobi:</strong> Menulis, Traveling</p>
        </div>
        <div class="row">
            <div class="service-item padd-15">
              <div class="service-item-inner">
                <!-- <div class="icon">
                  <i class="fas fa-user-tie"></i>
                </div> -->
                <img src="tugas 1.jpg" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
                <h4>TUGAS 1</h4>
                <p><b><i>Meceritakan Tokoh Grafika Komputer.</i></b></p><br>
                <p style="text-align: center;">prof.Danie Thalmann.</p>
                <a href="https://youtu.be/AFfHUzv-tOI?si=2K649TIZS9WSW4EX" target="_blank" 
                 style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
                Kunjungi YouTube
                </a><br>
        <div class="row">
            <div class="service-item padd-15">
              <div class="service-item-inner">
                <!-- <div class="icon">
                  <i class="fas fa-user-tie"></i>
                </div> -->
                <img src="tugas 2.jpg" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
                <h4>TUGAS 2</h4>
                <p><b><i>Membuat Garis DDA dan Bresenham.</i></b></p><br>
                <p style="text-align: center;">DDA menggunakan operasi aritmatika riil (floating-point) seperti perkalian dan pembagian, yang membuatnya lebih lambat. Bresenham menggunakan operasi bilangan bulat (integer) seperti penjumlahan dan pengurangan, sehingga lebih cepat dan efisien.</p>
                <a href="https://youtu.be/CbBCxqJrKck?si=DE4jWS6NhrlJzcYq" target="_blank" 
                 style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
                Kunjungi YouTube
                </a><br>
        <div class="service-item padd-15">
            <div class="service-item-inner">
              <!-- <div class="icon">
                <i class="fas fa-user-tie"></i>
              </div> -->
              <img src="tugas 3.jpg" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
              <h4>TUGAS 3</h4>
              <p><b><i>Membuat Algoritma Lingkaran Bresenham dan Midpoint.</i></b></p><br>
              <p style="text-align: center;">Algoritma lingkaran Bresenham dan Midpoint adalah dua algoritma yang digunakan untuk menggambar lingkaran pada tampilan raster. Keduanya efisien dan akurat, tetapi Bresenham dikenal karena menggunakan operasi bilangan bulat, sementara Midpoint menggunakan prinsip titik tengah untuk perhitungan. .</p>
              <a href="https://youtu.be/Iz8HF4VwNkI?si=ynvvgsoE7v5_TOG8" target="_blank" 
               style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
              Kunjungi YouTube
              </a><br>
      <div class="row">
        <div class="service-item padd-15">
          <div class="service-item-inner">
            <!-- <div class="icon">
              <i class="fas fa-user-tie"></i>
            </div> -->
            <img src="tugas 4.jpg" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
            <h4>TUGAS 4</h4>
            <p><b><i>Membuat Kurva Gambar Kucing.</i></b></p><br>
            <p style="text-align: center;">Kurva adalah garis yang melengkung, bukan garis lurus. Dalam matematika, kurva didefinisikan sebagai objek yang mengikuti lintasan tertentu, yang bisa berupa garis lurus, garis lengkung terbuka, atau lintasan tertutup..</p>
            <a href="https://youtu.be/zP81JCrQ5o0?si=aA66F0x444E6v81B" target="_blank" 
             style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
            Kunjungi YouTube
            </a><br>
    <div class="row">
        <div class="service-item padd-15">
          <div class="service-item-inner">
            <!-- <div class="icon">
              <i class="fas fa-user-tie"></i>
            </div> -->
            <img src="tugas 5.jpeg" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
            <h4>TUGAS 5</h4>
            <p><b><i>MATRIKS TRANSFORMASI.</i></b></p><br>
            <p style="text-align: center;">Matriks transformasi adalah matriks yang digunakan untuk menggambarkan bagaimana sebuah objek atau titik dipindahkan, dirotasi, atau diubah ukurannya dalam ruang geometri.</p>
            <a href="https://youtu.be/h196QFDR9to?si=byRiSMPdMcGKRUBC" target="_blank" 
             style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
            Kunjungi YouTube
            </a><br>
    <div class="row">
        <div class="service-item padd-15">
          <div class="service-item-inner">
            <!-- <div class="icon">
              <i class="fas fa-user-tie"></i>
            </div> -->
            <img src="tugas 6.PNG" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
            <h4>TUGAS 6</h4>
            <p><b><i>CLIPPING.</i></b></p><br>
            <p style="text-align: center;">TUGAS CLIPPING.</p>
            <a href="https://docs.google.com/spreadsheets/d/1FA4vAyJ47IlD2yIox3SJN5h-2ShI3UYBGKq8PBFi08U/edit?usp=sharing" target="_blank" 
             style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
            Kunjungi LINK
            </a><br>
    <div class="row">
        <div class="service-item padd-15">
          <div class="service-item-inner">
            <!-- <div class="icon">
              <i class="fas fa-user-tie"></i>
            </div> -->
            <img src="latihan cohen clip.jpeg" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
            <h4>TUGAS LATIHAN COHEN CLIP</h4>
            <p><b><i>CLIPPING.</i></b></p><br>
            <p style="text-align: center;">Cohen clipping (Algoritma Cohen-Sutherland) adalah algoritma yang digunakan untuk memotong garis atau objek dalam ruang tampilan.</p>
            <a href="https://youtu.be/XJfPCtORoE8?si=FloGEaqP1guCMyOs" target="_blank" 
             style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
            Kunjungi YouTube
            </a><br>
        <div class="row">
        <div class="service-item padd-15">
          <div class="service-item-inner">
            <!-- <div class="icon">
              <i class="fas fa-user-tie"></i>
            </div> -->
            <img src="polygon.jpeg" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
            <h4>CLIPPING POLYGON T7</h4>
            <p><b><i>CLIPPING.</i></b></p><br>
            <p style="text-align: center;">Clipping polygon adalah proses pemotongan sebuah poligon (bangun datar yang dibatasi oleh garis lurus) sehingga hanya bagian yang berada di dalam area yang diinginkan yang ditampilkan, sementara bagian yang berada di luar akan disembunyikan. </p>
            <a href="https://youtu.be/_WjGkiM2ECk?si=hMtyTge8Vnwem97D" target="_blank" 
             style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
            Kunjungi YouTube
            </a><br>
            <div class="row">
        <div class="service-item padd-15">
          <div class="service-item-inner">
            <!-- <div class="icon">
              <i class="fas fa-user-tie"></i>
            </div> -->
            <img src="PERSAMAAN.PNG" alt="Foto Tokoh" style="width: 200px; height: 120px; border-radius: 10px;">
            <h4>PERSAMAAN MISTERI</h4>
            <p><b><i>Persamaan T8</i></b></p><br>
            <p style="text-align: center;"> memvisualisasikan persamaan implisit (𝑥2+𝑦2−1)3=𝑥2𝑦3(x2+y2−1)3=x2y3 menggunakan pemrograman JavaScript dalam konteks grafika komputer, di mana persamaan tersebut dipetakan ke bidang koordinat layar melalui HTML Canvas dengan pendekatan numerik. </p>
            <a href="file:///C:/Users/NUR%20AIDA/Documents/GRAFKOM/CODING%20PERSAMAAN%20MISTERI.html" target="_blank" 
             style="display:inline-block; background-color:#53a4bd; color:#fff; padding:10px 20px; margin:8px 0; text-decoration:none; border-radius:8px; font-weight:bold;">
            Kunjungi 
            </a><br>
    <script>
        function showMessage() {
            alert("Terima kasih telah mengunjungi portofolio saya!");
        }
    </script>
</body>
</html>
