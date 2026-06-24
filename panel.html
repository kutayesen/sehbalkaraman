<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Şehbal Kulüp Bilgi Sistemi | Yönetim Paneli</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #0d4a2d;
            --secondary-color: #0b8793;
            --logo-blue: #29b6f6;
            --sidebar-width: 260px;
            --bg-color: #f4f7f6;
            --text-dark: #333;
        }

        * { 
            margin: 0; 
            padding: 0; 
            box-sizing: border-box; 
            font-family: 'Poppins', sans-serif; 
        }
        
        body { 
            background: var(--bg-color); 
            display: flex; 
            min-height: 100vh;
            color: var(--text-dark);
        }

        /* --- SOL MENÜ (SIDEBAR) --- */
        .sidebar {
            width: var(--sidebar-width);
            background: linear-gradient(180deg, var(--primary-color), #052415);
            color: white;
            position: fixed;
            top: 0; left: 0; bottom: 0;
            padding: 25px 20px;
            display: flex;
            flex-direction: column;
            box-shadow: 4px 0 15px rgba(0,0,0,0.1);
            z-index: 100;
        }

        .sidebar-brand {
            text-align: center;
            font-size: 20px;
            font-weight: 600;
            padding-bottom: 20px;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            margin-bottom: 25px;
            letter-spacing: 1px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .sidebar-menu { list-style: none; }
        .sidebar-menu li { margin-bottom: 8px; }
        .sidebar-menu a {
            display: flex;
            align-items: center;
            gap: 15px;
            color: rgba(255,255,255,0.75);
            text-decoration: none;
            padding: 12px 15px;
            border-radius: 12px;
            font-weight: 500;
            font-size: 14px;
            transition: 0.3s ease;
        }
        
        .sidebar-menu a:hover, .sidebar-menu li.active a {
            background: rgba(255,255,255,0.15);
            color: white;
            padding-left: 20px;
        }

        /* --- ANA İÇERİK ALANI --- */
        .main-content {
            margin-left: var(--sidebar-width);
            width: calc(100% - var(--sidebar-width));
            padding: 40px;
        }

        /* Üst Karşılama Paneli */
        .header-panel {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            background: white;
            padding: 20px 30px;
            border-radius: 20px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.02);
        }
        .header-panel h2 { font-size: 22px; color: var(--primary-color); }
        .header-panel p { color: #777; font-size: 14px; }

        /* --- ÖZET KARTLARI (KONTROL PANELİ) --- */
        .dashboard-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 25px;
            margin-bottom: 35px;
        }

        .data-card {
            background: white;
            padding: 25px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.02);
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-left: 5px solid var(--logo-blue);
            transition: transform 0.3s;
        }
        .data-card:hover { transform: translateY(-3px); }
        .data-card.success { border-left-color: #2ecc71; }
        .data-card.warning { border-left-color: #e67e22; }

        .data-card h3 { font-size: 13px; color: #888; margin-bottom: 5px; text-transform: uppercase; letter-spacing: 0.5px; }
        .data-card p { font-size: 24px; font-weight: 600; color: #222; }
        .data-card i { font-size: 32px; color: #e0e0e0; }

        /* --- E-OKUL BİLGİ TABLOLARI KUTUSU --- */
        .table-container {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.02);
            margin-bottom: 30px;
        }

        .table-container h3 { 
            margin-bottom: 20px; 
            font-size: 18px; 
            color: var(--primary-color); 
            display: flex;
            align-items: center;
            gap: 10px;
        }

        table { width: 100%; border-collapse: collapse; text-align: left; }
        th, td { padding: 14px 20px; border-bottom: 1px solid #eee; font-size: 14px; }
        th { background-color: #f8faf9; color: #555; font-weight: 600; text-transform: uppercase; font-size: 12px; letter-spacing: 0.5px; }
        tr:hover { background-color: #fafdfb; }

        /* Durum Rozetleri */
        .badge {
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
            display: inline-block;
        }
        .badge.success { background: #e8f8f0; color: #2ecc71; }
        .badge.info { background: #e3f2fd; color: var(--logo-blue); }
        .badge.danger { background: #ffebee; color: #e74c3c; }
    </style>
</head>
<body>

    <div class="sidebar">
        <div class="sidebar-brand">
            <i class="fa-solid fa-graduation-cap"></i> ŞEHBAL KYS
        </div>
        <ul class="sidebar-menu">
            <li class="active"><a href="#"><i class="fa-solid fa-house"></i> Panel Ana Sayfa</a></li>
            <li><a href="#"><i class="fa-solid fa-user"></i> Profil Bilgilerim</a></li>
            <li><a href="#"><i class="fa-solid fa-calendar-check"></i> Devamsızlık Sorgulama</a></li>
            <li><a href="#"><i class="fa-solid fa-file-invoice"></i> Gelişim / Not Kartı</a></li>
            <li><a href="#"><i class="fa-solid fa-dumbbell"></i> Haftalık Program</a></li>
            <li><a href="#"><i class="fa-solid fa-bullhorn"></i> Kulüp Duyuruları</a></li>
            <li style="margin-top: 60px;">
                <a href="index.html" style="color: #ff7675; background: rgba(255,118,117,0.1);"><i class="fa-solid fa-arrow-right-from-bracket"></i> Güvenli Çıkış</a>
            </li>
        </ul>
    </div>

    <div class="main-content">
        
        <div class="header-panel">
            <div>
                <h2>Hoş Geldiniz, Ömer Asaf Yılmaz</h2>
                <p>Mercan Şehbal Erkek Birimi • Öğrenci No: #1024</p>
            </div>
            <div style="text-align: right;">
                <span class="badge info" style="font-size: 13px;"><i class="fa-solid fa-circle-check"></i> Sistem Aktif</span>
            </div>
        </div>

        <div class="dashboard-grid">
            <div class="data-card">
                <div>
                    <h3>Toplam Devamsızlık</h3>
                    <p>1.5 Gün</p>
                </div>
                <i class="fa-solid fa-user-clock"></i>
            </div>
            <div class="data-card success">
                <div>
                    <h3>Gelişim Puanı</h3>
                    <p>94.50</p>
                </div>
                <i class="fa-solid fa-chart-line"></i>
            </div>
            <div class="data-card warning">
                <div>
                    <h3>Kayıtlı Faaliyet</h3>
                    <p>3 Kulüp</p>
                </div>
                <i class="fa-solid fa-cubes"></i>
            </div>
        </div>

        <div class="table-container">
            <h3><i class="fa-solid fa-clipboard-list"></i> Aktif Dönem Faaliyet ve Devamsızlık Durumu</h3>
            <table>
                <thead>
                    <tr>
                        <th>Birim / Kulüp Faaliyeti</th>
                        <th>Eğitmen / Antrenör</th>
                        <th>Haftalık Gün & Saat</th>
                        <th>Son Durum</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><b>Eğitim & Akademik Destek</b></td>
                        <td>Ahmet Hoca</td>
                        <td>Cumartesi 10:00</td>
                        <td><span class="badge success">Devamlı</span></td>
                    </tr>
                    <tr>
                        <td><b>Okçuluk / Spor Kulübü</b></td>
                        <td>Mustafa Antrenör</td>
                        <td>Pazar 14:00</td>
                        <td><span class="badge success">Devamlı</span></td>
                    </tr>
                    <tr>
                        <td><b>Karakter Eğitimi & Söyleşi</b></td>
                        <td>Mehmet Bey</td>
                        <td>Cuma 18:00</td>
                        <td><span class="badge danger">1 Gün İzinli</span></td>
                    </tr>
                </tbody>
            </table>
        </div>

    </div>

</body>
</html>
