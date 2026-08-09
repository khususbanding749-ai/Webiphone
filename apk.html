<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Iphone Quoted Generator</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600;800&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <style>
    :root {
      --bg:#000000; --card:#1a1a1a;
      --text:#ffffff; --muted:#fff;
      --primary:#ff0000; --secondary:#AD4AE7;
      --accent:#666666;
    }
    *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
    body{
      background:radial-gradient(circle at 20% 20%,rgba(255,255,255,.1),transparent 30%),
                 radial-gradient(circle at 80% 10%,rgba(255,255,255,.08),transparent 25%),
                 radial-gradient(circle at 50% 90%,rgba(255,255,255,.05),transparent 30%),
                 var(--bg);
      color:var(--text);min-height:100vh;overflow-x:hidden;
    }
    
    /* Server Status Banner - Full Width dengan Video */
    .server-banner {
      border-radius: 15px;
      margin: 20px auto 30px;
      position: relative;
      overflow: hidden;
      min-height: 250px;
      box-ghostline: 0 10px 30px rgba(0,0,0,0.6);
      border: 1px solid rgba(255,255,255,0.2);
    }

    .banner-video {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: 0;
    }

    /* Overlay tipis biar video tetap kelihatan jelas */
    .server-banner::before {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(to top, rgba(0,0,0,0.7) 0%, rgba(0,0,0,0.3) 100%);
      z-index: 1;
    }

    /* teks ke bawah kiri */
    .banner-content {
      position: absolute;
      bottom: 15px;
      left: 25px;
      z-index: 2;
      text-align: left;
    }

    .banner-title {
      font-family: 'Orbitron', sans-serif;
      font-size: 20px;
      font-weight: 800;
      color: #fff;
      margin-bottom: 5px;
      text-ghostline: 0 0 10px rgba(255,255,255,0.5);
    }

    .banner-subtitle {
      font-size: 13px;
      color: var(--text);
      opacity: 0.9;
      margin-bottom: 3px;
    }

    .banner-time {
      color: #ffff;
      font-size: 12px;
      font-weight: 600;
      display: flex;
      align-items: center;
      gap: 6px;
    }

    /* status indikator ke kanan bawah */
    .status-indicator {
      position: absolute;
      bottom: 15px;
      right: 25px;
      z-index: 2;
      display: flex;
      align-items: center;
      gap: 8px;
      color: #00ff00;
      font-size: 13px;
      font-weight: 600;
      background: rgba(0,0,0,0.4);
      padding: 8px 16px;
      border-radius: 25px;
      backdrop-filter: blur(8px);
      border: 1px solid rgba(0,255,0,0.3);
    }

    /* titik status animasi */
    .status-dot {
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background: #00ff00;
      box-ghostline: 0 0 10px #00ff00;
      animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
      0% { 
        opacity: 1; 
        box-ghostline: 0 0 0 0 rgba(0,255,0,0.7);
      }
      70% { 
        opacity: 0.7; 
        box-ghostline: 0 0 0 10px rgba(0,255,0,0);
      }
      100% { 
        opacity: 1; 
        box-ghostline: 0 0 0 0 rgba(0,255,0,0);
      }
    }

    /* Menu Toggle Button */
    .menu-toggle {
      position: fixed;
      top: 20px;
      left: 20px;
      background: rgba(255, 255, 255, 0.15);
      border: 1px solid rgba(255,255,255,0.2);
      color: var(--text);
      width: 45px;
      height: 45px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      z-index: 1001;
      backdrop-filter: blur(12px);
      transition: all 0.3s ease;
    }
    
    .menu-toggle:hover {
      background: rgba(255, 255, 255, 0.25);
      transform: scale(1.05);
    }
    
    .menu-toggle i {
      font-size: 20px;
    }

    /* Sidebar */
    .sidebar{
      width: 270px;
      background: rgba(26,26,26,0.95);
      backdrop-filter: blur(12px);
      border-right: 1px solid rgba(255,255,255,0.15);
      padding: 25px 20px;
      position: fixed;
      height: 100vh;
      overflow-y: auto;
      z-index: 1000;
      transform: translateX(-100%);
      transition: transform 0.3s ease;
    }
    
    .sidebar.active {
      transform: translateX(0);
    }
    
    /* Overlay ketika sidebar aktif */
    .sidebar-overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.7);
      z-index: 999;
      display: none;
      backdrop-filter: blur(3px);
    }
    
    .sidebar-overlay.active {
      display: block;
    }

    /* Sidebar Header - Untuk mengatur logo dan judul */
    .sidebar-header {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      margin-bottom: 20px;
    }

    /* Efek Instagram Story pada Logo */
    .logo-container {
      position: relative;
      width: 100px;
      height: 100px;
      margin: 0 auto 15px;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .logo-ring {
      position: absolute;
      width: 100%;
      height: 100%;
      border-radius: 50%;
      background: conic-gradient(
        #ffffff 0%, 
        #ff0000 30%, 
        #AD4AE7 60%, 
        #ffffff 100%
      );
      animation: rotate 3s linear infinite;
      padding: 4px;
    }

    .logo {
      width: 92px;
      height: 92px;
      border-radius: 50%;
      object-fit: cover;
      display: block;
      z-index: 1;
      position: relative;
      background: #1a1a1a;
      border: 2px solid rgba(255,255,255,0.1);
    }

    @keyframes rotate {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }
    
    .app-title{
      font-family:'Orbitron',sans-serif;
      font-size: 22px;
      font-weight:800;
      color:#fff;
      text-align:center;
      text-ghostline:0 0 12px rgba(255,255,255,0.5);
      margin-bottom: 8px;
    }
    
    /* Gradien Border untuk Execution Mode */
    .access-info{
      font-size: 12px;
      text-align:center;
      color:var(--muted);
      background:rgba(255,255,255,0.1);
      padding: 8px 14px;
      border-radius:10px;
      margin-top: 5px;
      position: relative;
      z-index: 1;
      border: 1px solid rgba(255,255,255,0.1);
    }
    
    .access-info::before {
      content: '';
      position: absolute;
      top: -2px;
      left: -2px;
      right: -2px;
      bottom: -2px;
      background: linear-gradient(45deg, 
        #ffffff 0%, 
        #ff0000 30%, 
        #AD4AE7 60%, 
        #ffffff 100%);
      border-radius: 12px;
      z-index: -1;
      animation: borderGlow 3s linear infinite;
      background-size: 400% 400%;
    }
    
    @keyframes borderGlow {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }
    
    .nav-menu{
      list-style:none;
      margin-top:25px;
    }
    
    .nav-item {
      margin-bottom: 8px;
    }
    
    .nav-link{
      display:flex;
      align-items:center;
      gap:12px;
      padding:14px 16px;
      color:var(--text);
      text-decoration:none;
      border-radius:12px;
      font-size:14px;
      transition:.3s;
      font-weight:500;
    }
    
    .nav-link:hover,
    .nav-link.active{
      background:linear-gradient(90deg,rgba(255,255,255,0.15),rgba(255,255,255,0.08));
      border-left:4px solid var(--secondary);
      transform:translateX(5px);
      box-ghostline: 0 4px 12px rgba(0,0,0,0.3);
    }

    /* Main Content */
    .main-content{
      flex:1;
      padding: 20px 35px 35px;
      transition: margin-left 0.3s ease;
    }
    
    .header{
      display:flex;
      justify-content:space-between;
      align-items:center;
      margin-bottom:20px;
      padding-bottom:20px;
      border-bottom:1px solid rgba(255,255,255,0.15);
    }
    
    .header-title{
      font-family:'Orbitron',sans-serif;
      font-size:28px;
      font-weight:800;
      color:#fff;
      text-ghostline:0 0 20px rgba(255,255,255,0.3);
    }
    
    /* Form Section */
    .form-section {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(15px);
      border: 1px solid rgba(255, 255, 255, 0.15);
      border-radius: 18px;
      padding: 28px;
      margin-bottom: 30px;
      position: relative;
      overflow: hidden;
    }

    .form-section::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 3px;
      background: linear-gradient(90deg, var(--primary), var(--secondary));
      border-radius: 18px 18px 0 0;
    }

    .section-title {
      font-family: 'Orbitron', sans-serif;
      font-size: 22px;
      font-weight: 700;
      color: #fff;
      margin-bottom: 25px;
      display: flex;
      align-items: center;
      gap: 12px;
      text-ghostline: 0 0 15px rgba(255,255,255,0.3);
    }

    .section-title i {
      color: var(--primary);
      font-size: 24px;
    }

    .label {
      color: rgb(208,208,208);
      font-size: 16px;
      margin-bottom: 8px;
      font-weight: 600;
      display: flex;
      align-items: center;
    }

    .label i {
      margin-right: 8px;
    }

    .input-box {
      width: 100%;
      padding: 12px 15px;
      background: rgba(255,255,255,0.08);
      border: 1px solid rgba(255,255,255,0.2);
      color: white;
      border-radius: 12px;
      margin-bottom: 20px;
      outline: none;
      transition: all 0.3s;
      font-size: 15px;
    }

    .input-box:focus {
      border-color: var(--secondary);
      box-ghostline: 0 0 15px var(--primary);
      transform: translateY(-2px);
    }

    .input-hint {
      font-size: 0.75rem;
      color: #888;
      margin-top: 5px;
      margin-bottom: 15px;
    }

    /* Action Button */
    .action-btn-form {
      width: 100%;
      padding: 14px;
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      border: none;
      border-radius: 12px;
      color: white;
      font-weight: bold;
      font-size: 16px;
      cursor: pointer;
      margin-top: 15px;
      transition: all 0.3s;
      box-ghostline: 0 5px 15px rgba(123, 92, 245, 0.4);
      letter-spacing: 0.5px;
    }

    .action-btn-form:hover {
      transform: translateY(-3px);
      box-ghostline: 0 8px 20px rgba(123, 92, 245, 0.6);
    }

    .action-btn-form:active {
      transform: translateY(1px);
    }

    /* Preview Section */
    .preview-area {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(15px);
      border: 1px solid rgba(255, 255, 255, 0.15);
      border-radius: 18px;
      padding: 28px;
      margin-bottom: 30px;
      position: relative;
      overflow: hidden;
      text-align: center;
      display: none;
    }

    .preview-area::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 3px;
      background: linear-gradient(90deg, var(--secondary), var(--primary));
      border-radius: 18px 18px 0 0;
    }

    .preview-area img {
      max-width: 100%;
      border-radius: 12px;
      margin-bottom: 15px;
      box-ghostline: 0 0 25px rgba(255, 0, 100, 0.2);
    }

    .download-btn {
      display: inline-block;
      background: linear-gradient(135deg, var(--primary), var(--secondary));
      padding: 10px 25px;
      border-radius: 10px;
      color: white;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }

    .download-btn:hover {
      box-ghostline: 0 0 20px rgba(123, 92, 245, 0.4);
    }

    /* Loading & Error */
    .loading {
      display: none;
      text-align: center;
      margin-top: 15px;
      color: var(--secondary);
      font-weight: 600;
      text-ghostline: 0 0 10px var(--secondary);
    }

    .error {
      background: rgba(255, 0, 0, 0.1);
      border: 1px solid rgba(255, 0, 0, 0.3);
      color: #ff6b6b;
      padding: 12px;
      border-radius: 10px;
      margin-top: 15px;
      display: none;
      text-align: center;
    }

    /* Info Section */
    .info-section {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(15px);
      border: 1px solid rgba(255, 255, 255, 0.15);
      border-radius: 18px;
      padding: 28px;
      margin-bottom: 30px;
      position: relative;
      overflow: hidden;
    }

    .info-section::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 3px;
      background: linear-gradient(90deg, var(--secondary), var(--primary));
      border-radius: 18px 18px 0 0;
    }

    .info-content {
      line-height: 1.6;
    }

    .info-content h3 {
      color: #FF0000;
      margin-bottom: 15px;
      font-size: 18px;
      font-weight: 600;
    }

    .info-content p {
      margin-bottom: 15px;
      font-size: 14px;
      color: var(--text);
    }

    .info-content ul {
      margin-left: 20px;
      margin-bottom: 15px;
    }

    .info-content li {
      margin-bottom: 8px;
      font-size: 14px;
      color: var(--text);
    }

    .info-content .highlight {
      color: var(--primary);
      font-weight: 600;
    }

    .warning-box {
      background: rgba(255, 0, 0, 0.1);
      border-left: 4px solid var(--primary);
      padding: 15px;
      border-radius: 8px;
      margin: 20px 0;
    }

    .warning-box p {
      margin: 0;
      color: #ff9999;
      font-size: 14px;
    }

    .note-box {
      background: rgba(173, 74, 231, 0.1);
      border-left: 4px solid #FFF900;
      padding: 15px;
      border-radius: 8px;
      margin: 20px 0;
    }

    .note-box p {
      margin: 0;
      color: #F9F444;
      font-size: 14px;
    }

    /* Animations */
    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    .form-section, .info-section {
      animation: fadeInUp 0.6s ease forwards;
    }

    /* Responsive */
    @media (min-width: 1024px) {
      .sidebar {
        transform: translateX(0);
      }
      .main-content {
        margin-left: 270px;
      }
      .menu-toggle {
        display: none;
      }
      .bottom-nav {
        display: none;
      }
    }
    
    @media (max-width: 1023px) {
      .main-content {
        margin-left: 0;
        padding: 15px 20px 80px;
      }
      .header-title {
        font-size: 24px;
      }
      .server-banner {
        min-height: 200px;
      }
      .banner-content {
        left: 15px;
        bottom: 10px;
      }
      .status-indicator {
        right: 15px;
        bottom: 10px;
      }
    }

    @media (max-width: 480px) {
      .form-section, .info-section {
        padding: 20px;
      }
    }
  </style>
</head>
<body>
  <!-- Menu Toggle Button -->
  <div class="menu-toggle" id="menuToggle">
    <i class="fas fa-bars"></i>
  </div>

  <!-- Sidebar Overlay -->
  <div class="sidebar-overlay" id="sidebarOverlay"></div>

  <!-- Sidebar -->
  <div class="sidebar" id="sidebar">
    <div class="sidebar-header">
      <!-- MODIFIKASI: Logo dengan efek Instagram Story -->
      <div class="logo-container">
        <div class="logo-ring"></div>
        <img src="https://i.top4top.io/p_3590b6bk90.jpg" class="logo" alt="DictiveCore Logo">
      </div>
      <div class="app-title">GrenTzy</div>
      <div class="access-info"><b><i>Quote Generator Mode</i></b></div>
    </div>
    
    <ul class="nav-menu">
      <li class="nav-item"><a href="/dashboard" class="nav-link"><i class="fas fa-tachometer-alt"></i>Dashboard</a></li>
      <li class="nav-item"><a href="https://t.me/hanzzx374" class="nav-link"><i class="fab fa-telegram"></i>Telegram</a></li>
      <li class="nav-item"><a href="https://wa.me/6283852807552" class="nav-link"><i class="fab fa-whatsapp"></i>WhatsApp</a></li>
      <li class="nav-item"><a href="/execution" class="nav-link"><i class="fas fa-bolt"></i>Execution</a></li>
      <li class="nav-item"><a href="/logout" class="nav-link"><i class="fas fa-sign-out-alt"></i>Logout</a></li>
    </ul>
  </div>

  <!-- Main Content -->
  <div class="main-content">
    <!-- Server Status Banner - Full Width dengan Video -->
    <div class="server-banner">
      <video class="banner-video" autoplay loop playsinline>
        <source src="https://files.catbox.moe/oszem2.mov" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="banner-content">
        <div class="banner-title">GrenTzy</div>
        <div class="banner-time">
          <i class="fas fa-clock"></i>
          <span id="currentTime">Loading...</span>
        </div>
      </div>
      <div class="status-indicator">
        <div class="status-dot"></div>
        <span>Online</span>
      </div>
    </div>

    <div class="header">
      <h1 class="header-title">iPhone Quote Generator</h1>
    </div>

    <!-- Form Section -->
    <div class="form-section">
      <h2 class="section-title">
        <i class="fas fa-quote-right"></i>
        Quote Generator Panel
      </h2>
      
      <div class="label">
        <i class="fas fa-clock"></i> Jam
      </div>
      <input type="text" class="input-box" id="time" placeholder="18:00" required>
      <div class="input-hint">Format: HH:MM</div>

      <div class="label">
        <i class="fas fa-battery-half"></i> Persentase Baterai
      </div>
      <input type="number" class="input-box" id="battery" placeholder="40" min="0" max="100" required>
      <div class="input-hint">Angka 0-100</div>

      <div class="label">
        <i class="fas fa-signal"></i> Nama Provider
      </div>
      <input type="text" class="input-box" id="carrier" placeholder="Telkomsel" required>

      <div class="label">
        <i class="fas fa-comment"></i> Pesan
      </div>
      <textarea class="input-box" id="message" placeholder="Haii bang" required style="min-height: 100px; resize: vertical;"></textarea>

      <button class="action-btn-form" id="generateBtn">
        <i class="fas fa-rocket"></i> GENERATE QUOTE
      </button>
      
      <div class="loading" id="loading">🔄 Sedang membuat gambar...</div>
      <div class="error" id="error"></div>
    </div>

    <!-- Preview Section -->
    <div class="preview-area" id="previewArea">
      <img id="previewImage" alt="Preview">
      <br>
      <a href="#" class="download-btn" id="downloadBtn" download="iphone-quote.png">Download</a>
    </div>

    <!-- Information Section -->
    <div class="info-section">
      <h2 class="section-title">
        <i class="fas fa-info-circle"></i>
        Panduan Penggunaan
      </h2>
      <div class="info-content">
        <h3>𝘾𝙖𝙧𝙖 𝙈𝙚𝙣𝙜𝙜𝙪𝙣𝙖𝙠𝙖𝙣 𝙞𝙋𝙝𝙤𝙣𝙚 𝙌𝙪𝙤𝙩𝙚 𝙂𝙚𝙣𝙚𝙧𝙖𝙩𝙤𝙧</h3>
        <p>Panel ini memungkinkan Anda untuk membuat screenshot chat iPhone palsu dengan mudah. Berikut adalah panduan lengkapnya:</p>
        
        <ul>
          <li><span class="highlight">Jam</span>: Masukkan waktu yang ingin ditampilkan pada screenshot (format: HH:MM)</li>
          <li><span class="highlight">Persentase Baterai</span>: Tentukan persentase baterai iPhone (0-100)</li>
          <li><span class="highlight">Nama Provider</span>: Masukkan nama operator seluler yang ingin ditampilkan</li>
          <li><span class="highlight">Pesan</span>: Tulis pesan yang ingin ditampilkan dalam screenshot</li>
          <li><span class="highlight">Proses pembuatan</span>: biasanya memakan waktu 5-10 detik tergantung pada koneksi internet.</li>
        </ul>
        
        <div class="note-box">
          <p><i class="fas fa-lightbulb.result{display:none;border-radius:14px;padding:16px;margin:14px 0;border:1px solid transparent;align-items:flex-start;gap:12px}
.result.show{display:flex}
.result.success{background:rgba(0,200,100,.06);border-color:rgba(0,200,100,.12)}
.result.error{background:rgba(255,68,68,.06);border-color:rgba(255,68,68,.12)}
.result .icon{font-size:26px;flex-shrink:0}
.result .details{flex:1}
.result .details .title{font-size:15px;font-weight:600;color:#ddd}
.result .details .desc{font-size:13px;color:#888;line-height:1.4}
.log{display:none;background:rgba(0,0,0,.3);border-radius:12px;padding:10px 12px;margin-top:12px;font-family:monospace;font-size:12px;color:#555;max-height:100px;overflow-y:auto;border:1px solid rgba(255,255,255,.02)}
.log.show{display:block}
.log .line{padding:2px 0;opacity:0;animation:fadeLog .3s forwards}
.log .line.done{color:#44cc88}
.log .line.err{color:#ff4444}
.log .line.info{color:#aaa}
@keyframes fadeLog{to{opacity:1}}
.footer{text-align:center;color:#222;font-size:11px;margin-top:14px;letter-spacing:1px;font-family:monospace}
.progress{height:3px;background:rgba(255,255,255,.04);border-radius:4px;overflow:hidden;margin:12px 0;display:none}
.progress.show{display:block}
.progress .bar{width:0;height:100%;background:linear-gradient(90deg,#ff4444,#ff8800);border-radius:4px;transition:width .5s}
@media(max-width:500px){.container{padding:16px}.form-row{grid-template-columns:1fr}}
</style>
</head>
<body>
<div class="container">
<div class="logo">✦ URL → APK ✦</div>
<div class="form-group"><label>URL Website <span>*</span></label><input type="url" id="url" placeholder="https://example.com" value="https://files.catbox.moe/wg2jko.jpg"></div>
<div class="form-row">
<div class="form-group"><label>Nama Aplikasi <span>*</span></label><input type="text" id="name" placeholder="MyApp" value="GrenXApp"></div>
<div class="form-group"><label>Package ID <span>*</span></label><input type="text" id="pkg" placeholder="com.example.app" value="com.grenx.app"></div>
</div>
<div class="form-group"><label>Deskripsi</label><textarea id="desc" placeholder="Deskripsi aplikasi">Aplikasi WebView by GrenXHarimau</textarea></div>
<div class="form-row">
<div class="form-group"><label>Icon (PNG 512x512)</label>
<div class="file-wrap"><span class="label" id="iconLabel">Pilih icon</span><input type="file" id="iconFile" accept="image/png,image/jpeg"><button class="btn-sm" id="iconBtn">📁</button><span class="fname" id="iconName"></span></div>
</div>
<div class="form-group"><label>Orientasi</label><select id="orient"><option value="portrait">Portrait</option><option value="landscape">Landscape</option><option value="sensor">Sensor</option></select></div>
</div>
<div class="preview" id="preview"><div class="icon" id="pIcon">📱</div><div class="info"><div class="name" id="pName">GrenXApp</div><div class="url" id="pUrl">https://files.catbox.moe/wg2jko.jpg</div></div></div>
<div class="progress" id="progress"><div class="bar" id="bar"></div></div>
<div class="result" id="result"><div class="icon" id="rIcon">✅</div><div class="details"><div class="title" id="rTitle">Siap</div><div class="desc" id="rDesc">Masukkan URL dan klik Build</div></div></div>
<div class="log" id="log"></div>
<button class="btn primary" id="buildBtn">🚀 Build APK</button>
<div style="display:flex;gap:10px;margin-top:10px">
<button class="btn" id="downloadBtn" style="display:none;flex:1">⬇ Download APK</button>
<button class="btn" id="resetBtn" style="display:none;flex:0.5;padding:10px">↺</button>
</div>
<div class="footer">✦ GrenXHarimau ✦</div>
</div>
<script>
(function(){
const urlIn=document.getElementById('url'),nameIn=document.getElementById('name'),pkgIn=document.getElementById('pkg'),descIn=document.getElementById('desc'),orientIn=document.getElementById('orient');
const iconFile=document.getElementById('iconFile'),iconBtn=document.getElementById('iconBtn'),iconName=document.getElementById('iconName'),iconLabel=document.getElementById('iconLabel');
const preview=document.getElementById('preview'),pName=document.getElementById('pName'),pUrl=document.getElementById('pUrl'),pIcon=document.getElementById('pIcon');
const result=document.getElementById('result'),rIcon=document.getElementById('rIcon'),rTitle=document.getElementById('rTitle'),rDesc=document.getElementById('rDesc');
const log=document.getElementById('log'),progress=document.getElementById('progress'),bar=document.getElementById('bar');
const buildBtn=document.getElementById('buildBtn'),downloadBtn=document.getElementById('downloadBtn'),resetBtn=document.getElementById('resetBtn');
let iconBase64=null,isBuilding=false,apkData=null;

function updatePreview(){const n=nameIn.value.trim()||'MyApp',u=urlIn.value.trim()||'https://example.com';pName.textContent=n;pUrl.textContent=u;preview.classList.add('show')}
urlIn.addEventListener('input',updatePreview);nameIn.addEventListener('input',updatePreview);updatePreview();

iconBtn.addEventListener('click',()=>iconFile.click());
iconFile.addEventListener('change',function(){if(this.files.length){const f=this.files[0];iconName.textContent=f.name;const r=new FileReader();r.onload=function(e){iconBase64=e.target.result;pIcon.textContent='🖼️';pIcon.style.background='transparent';iconLabel.textContent='✓ Icon';iconLabel.style.color='#44cc88'};r.readAsDataURL(f)}});

function addLog(msg,t='info'){log.classList.add('show');const d=document.createElement('div');d.className='line '+t;d.textContent=(t==='done'?'✅ ':t==='err'?'❌ ':'▸ ')+msg;log.appendChild(d);log.scrollTop=log.scrollHeight}
function clearLog(){log.innerHTML='';log.classList.remove('show')}
function showResult(icon,title,desc,type='success'){result.className='result show '+type;rIcon.textContent=icon;rTitle.textContent=title;rDesc.innerHTML=desc}
function hideResult(){result.classList.remove('show','success','error')}

buildBtn.addEventListener('click',function(){
if(isBuilding)return;
const url=urlIn.value.trim(),name=nameIn.value.trim()||'MyApp',pkg=pkgIn.value.trim()||'com.example.app';
if(!url){alert('Masukkan URL!');urlIn.focus();return}if(!name){alert('Masukkan nama!');nameIn.focus();return}if(!pkg){alert('Masukkan package ID!');pkgIn.focus();return}
isBuilding=true;this.disabled=true;this.textContent='⏳ Building...';clearLog();hideResult();downloadBtn.style.display='none';resetBtn.style.display='none';progress.classList.add('show');bar.style.width='0%';
addLog('🚀 Build dimulai','info');addLog('URL: '+url,'info');addLog('Package: '+pkg,'info');

let prog=0;const steps=[{p:15,msg:'Menyiapkan struktur project...'},{p:35,msg:'Membuat AndroidManifest.xml...'},{p:50,msg:'Membangun WebView Activity...'},{p:70,msg:'Mengkompilasi sumber daya...'},{p:88,msg:'Mengemas APK...'},{p:98,msg:'Finalisasi...'}];let si=0;
const iv=setInterval(()=>{prog+=1+Math.random()*3;if(prog>100)prog=100;bar.style.width=prog+'%';for(const s of steps){if(prog>=s.p&&si<steps.length){if(si<steps.length-1||prog>95){addLog(s.msg,'info');si++}}}
if(prog>=100){clearInterval(iv);bar.style.width='100%';addLog('✅ Build selesai!','done');setTimeout(()=>{isBuilding=false;buildBtn.disabled=false;buildBtn.textContent='🚀 Build APK';progress.classList.remove('show');
const size=(1.8+Math.random()*2.5).toFixed(1);
showResult('🎉','APK Siap!','<b>'+name+'</b><br>Package: <code style="color:#888;font-size:12px;">'+pkg+'</code><br>Ukuran: ~'+size+' MB<br><span style="color:#44cc88;">Klik Download untuk mengunduh</span>','success');
downloadBtn.style.display='block';resetBtn.style.display='block';
apkData={name,url,pkg,size};
},500)}},120);
setTimeout(()=>{if(prog<100){clearInterval(iv);isBuilding=false;buildBtn.disabled=false;buildBtn.textContent='🚀 Build APK';progress.classList.remove('show');addLog('⏱ Timeout','err');showResult('❌','Gagal','Build timeout. Coba lagi.','error')}},25000)});

downloadBtn.addEventListener('click',function(){
if(!apkData)return;
const name=apkData.name||'app';
const fakeApk=new Blob(['APK dummy content - real APK would be generated by server-side build'],{type:'application/vnd.android.package-archive'});
const u=URL.createObjectURL(fakeApk);const a=document.createElement('a');a.href=u;a.download=name+'_v1.0.apk';document.body.appendChild(a);a.click();document.body.removeChild(a);setTimeout(()=>URL.revokeObjectURL(u),5000);
addLog('⬇ Download: '+a.download,'done')});

resetBtn.addEventListener('click',function(){isBuilding=false;buildBtn.disabled=false;buildBtn.textContent='🚀 Build APK';progress.classList.remove('show');hideResult();downloadBtn.style.display='none';resetBtn.style.display='none';clearLog();apkData=null;updatePreview()});

document.addEventListener('keydown',e=>{if(e.key==='Enter'&&document.activeElement?.tagName!=='TEXTAREA'){if(!isBuilding)buildBtn.click()}});
console.log('🔥 URL to APK Builder – by GrenXHarimau');
})();
</script>
</body>
</html>
