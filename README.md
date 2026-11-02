<!DOCTYPE html>
<html lang="id" translate="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kartu Profil Clarice</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f7cbd4; /* Warna latar belakang pink muda */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .profile-card {
            background-color: #ffffff;
            width: 360px;
            border-radius: 24px;
            padding: 30px 24px;
            text-align: center;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.05);
        }

        .avatar-container {
            width: 110px;
            height: 110px;
            margin: 0 auto 16px;
            border-radius: 50%;
            overflow: hidden;
            border: 2px solid #f2e2e6;
        }

        .avatar-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .name {
            font-size: 22px;
            font-weight: 700;
            color: #1a1a1a;
            margin-bottom: 6px;
        }

        .school {
            font-size: 11px;
            color: #a0a0a0;
            letter-spacing: 1px;
            text-transform: uppercase;
            font-weight: 600;
            margin-bottom: 12px;
        }

        .status-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 6px;
            font-size: 13px;
            font-weight: 600;
            margin-bottom: 24px;
        }

        .status-text {
            color: #666666;
        }

        .class-text {
            color: #e91e63;
        }

        .badge {
            background-color: #e91e63;
            color: white;
            font-size: 10px;
            padding: 4px 10px;
            border-radius: 12px;
            text-transform: uppercase;
            font-weight: 700;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }

        .hobby-section {
            text-align: left;
            border-top: 1px solid #f0f0f0;
            padding-top: 16px;
            margin-bottom: 28px;
        }

        .hobby-title {
            font-size: 13px;
            font-weight: 700;
            color: #333333;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            margin-bottom: 12px;
        }

        .hobby-list {
            list-style: none;
        }

        .hobby-item {
            font-size: 14px;
            color: #4a4a4a;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .btn-contact {
            display: block;
            width: 100%;
            background-color: #e91e63;
            color: white;
            text-decoration: none;
            padding: 14px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 600;
            transition: background-color 0.2s;
        }

        .btn-contact:hover {
            background-color: #d81b60;
        }
    </style>
</head>
<body>

    <div class="profile-card">
        <!-- Foto Profil Clarice -->
        <div class="avatar-container">
            <img src="https://i.pinimg.com/236x/b2/5d/99/b25d99d1cf8a23d6d1d82293a2517243.jpg" alt="Clarice">
        </div>

        <!-- Informasi Utama -->
        <div class="name">Clarice</div>
        <div class="school">SMA Santo Paulus Pontianak</div>

        <!-- Status & Badge -->
        <div class="status-container">
            <span class="status-text">Siswi</span>
            <span class="class-text">Kelas XII</span>
            <span class="badge">💕 Taken by Chris</span>
        </div>

        <!-- Bagian Hobi -->
        <div class="hobby-section">
            <div class="hobby-title">Hobi Saya</div>
            <ul class="hobby-list">
                <li class="hobby-item">😴 Tidur</li>
                <li class="hobby-item">🏀 Basket</li>
            </ul>
        </div>

        <!-- Tombol Aksi (Diproteksi dari Auto-Translate dan Spasi Link Diperbaiki) -->
        <a href="DUAREAL.html" class="btn-contact" translate="no">Klik</a>
    </div>

</body>
</html># TUGASHTML
