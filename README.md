<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>Nhôm Kính Xuân Định | Công Ty TNHH MTV TM - DV - SX - XD Xuân Trường Đà Nẵng</title>
  <meta name="description" content="Nhôm Kính Xuân Định (nhomkinhxuandinh.com) - Công Ty TNHH MTV Thương Mại - Dịch Vụ - Sản Xuất - Xây Dựng Xuân Trường chuyên thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Kính ốp bếp, Phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0934.123.693." />

  <!-- Meta Open Graph & Favicon sử dụng Logo chính thức của Nhôm Kính Xuân Định khi chia sẻ link -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="Nhôm Kính Xuân Định - nhomkinhxuandinh.com" />
  <meta property="og:title" content="Nhôm Kính Xuân Định | Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng" />
  <meta property="og:description" content="Công Ty TNHH MTV Thương Mại - Dịch Vụ - Sản Xuất - Xây Dựng Xuân Trường. Địa chỉ: 17 Bàu Mạc 16, P. Liên Chiểu, TP Đà Nẵng. Hotline/Zalo: 0934.123.693." />
  <meta property="og:url" content="https://nhomkinhxuandinh.com" />
  <meta property="og:image" content="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 600 315'%3E%3Crect width='600' height='315' fill='%230B3B70'/%3E%3Crect x='24' y='24' width='552' height='267' rx='16' fill='none' stroke='%23E67E22' stroke-width='3'/%3E%3Cg transform='translate(75,92)'%3E%3Crect x='0' y='0' width='120' height='120' rx='18' fill='%2311559C' stroke='%23E67E22' stroke-width='4'/%3E%3Cpath d='M24 24H54V96H24V24ZM66 24H96V56H66V24ZM66 66H96V96H66V66Z' fill='%23FFFFFF'/%3E%3Cpath d='M24 24L96 96' stroke='%23E67E22' stroke-width='5' stroke-linecap='round'/%3E%3C/g%3E%3Ctext x='220' y='142' fill='%23FFFFFF' font-family='Arial,sans-serif' font-weight='800' font-size='34'%3ENH%C3%94M K%C3%8DNH%3C/text%3E%3Ctext x='220' y='184' fill='%23F59E0B' font-family='Arial,sans-serif' font-weight='800' font-size='38'%3EXU%C3%82N %C4%90%E1%BB%8ANH%3C/text%3E%3Ctext x='220' y='216' fill='%23CBD5E1' font-family='Arial,sans-serif' font-size='15'%3EC%C3%94NG TY TNHH MTV XD XU%C3%82N TR%C6%AF%E1%BB%9CNG%3C/text%3E%3C/svg%3E" />
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%230B3B70'/%3E%3Crect x='12' y='12' width='17' height='40' rx='2' fill='%23FFFFFF'/%3E%3Crect x='35' y='12' width='17' height='18' rx='2' fill='%23FFFFFF'/%3E%3Crect x='35' y='34' width='17' height='18' rx='2' fill='%23E67E22'/%3E%3C/svg%3E" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              dark: '#07274D',
              primary: '#0B3B70',   /* Xanh dương kiến trúc chủ đạo theo Logo */
              medium: '#11559C',    /* Xanh nhôm kính */
              light: '#EAF2FB',     /* Nền xanh nhạt tinh tế */
              accent: '#E67E22',    /* Cam vàng kim loại từ Logo */
              accentHover: '#D35400',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* ==========================================================================
       CẤU HÌNH CHUNG & CHỐNG TRÀN VIỀN (FLATSOME UX BUILDER READY)
       ========================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      max-width: 100%;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #F8FAFC;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .container-95 {
      width: 100%;
      padding-left: 12px;
      padding-right: 12px;
      margin-left: auto;
      margin-right: auto;
    }

    @media (min-width: 1024px) {
      .container-95 {
        width: 95%;
        max-width: 1840px;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu Dropdown chuẩn Flatsome */
    .flatsome-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.22s ease;
    }
    .group:hover .flatsome-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Banner tự trượt - 2 slide kích thước bằng nhau tuyệt đối */
    .hero-slider-track {
      display: flex;
      width: 200%;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
    }
    .hero-slide-item {
      width: 50%;
      flex-shrink: 0;
    }

    /* Hiệu ứng rung nhẹ cho nút liên hệ nổi bật */
    @keyframes pulseRing {
      0% { transform: scale(0.95); opacity: 0.75; }
      70% { transform: scale(1.32); opacity: 0; }
      100% { transform: scale(1.32); opacity: 0; }
    }
    .pulse-ring::before {
      content: '';
      position: absolute;
      inset: 0;
      border-radius: 9999px;
      background-color: inherit;
      z-index: -1;
      animation: pulseRing 2s infinite;
    }

    /* Tùy chỉnh thanh cuộn danh mục ngang trên mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>
<body class="antialiased selection:bg-brand-primary selection:text-white">

  <!-- ========================================================================
       [UX SECTION 1] TOP BAR THÔNG TIN CÔNG TY
       ======================================================================== -->
  <div class="bg-brand-dark text-slate-200 text-[11px] sm:text-xs border-b border-white/10">
    <div class="container-95 py-1.5 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 sm:gap-5 truncate">
        <span class="inline-flex items-center gap-1.5 truncate">
          <svg class="w-3.5 h-3.5 text-brand-accent shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span class="truncate">17 Bàu Mạc 16, Phường Liên Chiểu, TP Đà Nẵng</span>
        </span>
        <span class="hidden md:inline-flex items-center gap-1.5 whitespace-nowrap">
          <svg class="w-3.5 h-3.5 text-brand-accent shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          <span>Làm việc 24/7 • Khảo sát &amp; Báo giá tận nơi</span>
        </span>
      </div>
      <div class="hidden sm:flex items-center gap-4 whitespace-nowrap text-slate-300">
        <span>Website: <strong class="text-white">nhomkinhxuandinh.com</strong></span>
        <span class="text-white/30">|</span>
        <a href="https://www.facebook.com/nhomkinhxuandinh" target="_blank" rel="noopener noreferrer" class="hover:text-brand-accent transition">Fanpage: Nhôm Kính Xuân Định</a>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       [UX SECTION 2] HEADER CHÍNH (LOGO GỌN ĐẸP, TÌM KIẾM, KHÔNG NÚT GỌI NGAY TRÀN VIỀN)
       ======================================================================== -->
  <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200/80">
    <div class="container-95 py-2.5 lg:py-3 flex items-center justify-between gap-3">
      
      <!-- Nút mở menu trên Mobile -->
      <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg border border-slate-200 text-brand-primary hover:bg-brand-light transition shrink-0">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M4 6h16M4 12h16M4 18h16"/></svg>
      </button>

      <!-- LOGO CÔNG TY CHUYÊN NGHIỆP - CHỈNH GỌN NHỎ LẠI -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
        <!-- Biểu tượng kiến trúc khung nhôm Xingfa & Kính -->
        <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-gradient-to-br from-brand-primary to-brand-medium p-1.5 flex items-center justify-center shadow-sm border border-brand-accent/60 group-hover:scale-105 transition-transform">
          <svg viewBox="0 0 48 48" class="w-full h-full" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="4" y="4" width="40" height="40" rx="5" stroke="#FFFFFF" stroke-width="3"/>
            <line x1="22" y1="4" x2="22" y2="44" stroke="#FFFFFF" stroke-width="2.5"/>
            <line x1="22" y1="24" x2="44" y2="24" stroke="#FFFFFF" stroke-width="2.5"/>
            <path d="M10 12L17 19M10 19L17 12" stroke="#E67E22" stroke-width="2.5" stroke-linecap="round"/>
            <rect x="27" y="9" width="12" height="10" rx="1.5" fill="#E67E22"/>
            <path d="M28 38L38 29" stroke="#93C5FD" stroke-width="2.2" stroke-linecap="round"/>
          </svg>
        </div>
        <!-- Tên thương hiệu gọn gàng -->
        <div class="leading-tight">
          <div class="flex items-center gap-1">
            <span class="text-sm sm:text-base lg:text-[17px] font-extrabold tracking-tight text-brand-primary">NHÔM KÍNH</span>
            <span class="text-sm sm:text-base lg:text-[17px] font-extrabold tracking-tight text-brand-accent">XUÂN ĐỊNH</span>
          </div>
          <p class="text-[9.5px] sm:text-[10px] font-semibold text-slate-500 uppercase tracking-wider truncate max-w-[185px] sm:max-w-[240px]">
            CÔNG TY TNHH MTV XD XUÂN TRƯỜNG
          </p>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm (Gọn gàng ở giữa trên Desktop) -->
      <div class="hidden md:flex flex-1 max-w-md lg:max-w-lg mx-3">
        <form onsubmit="handleSearchSubmit(event)" class="w-full flex items-center bg-slate-100 border border-slate-200 rounded-full overflow-hidden focus-within:border-brand-primary focus-within:bg-white transition">
          <input id="desktopSearchInput" type="text" placeholder="Tìm cửa nhôm Xingfa, cửa kính cường lực, kính ốp bếp..." class="w-full bg-transparent px-4 py-1.5 text-xs lg:text-sm text-slate-700 placeholder-slate-400 focus:outline-none" />
          <button type="submit" aria-label="Tìm kiếm" class="bg-brand-primary hover:bg-brand-medium text-white px-4 py-2 transition flex items-center justify-center shrink-0">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
          </button>
        </form>
      </div>

      <!-- Khu vực thông tin ngắn gọn bên phải Header (Không đặt nút Gọi Ngay gây tràn viền) -->
      <div class="flex items-center gap-2 sm:gap-3 shrink-0">
        <a href="#form-bao-gia" class="hidden sm:inline-flex items-center gap-1.5 text-xs font-semibold text-brand-primary bg-brand-light hover:bg-brand-primary hover:text-white px-3 py-2 rounded-lg transition whitespace-nowrap">
          <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/></svg>
          <span>Nhận báo giá</span>
        </a>
        <button type="button" onclick="openQuoteDrawer()" class="relative inline-flex items-center gap-1.5 text-xs font-semibold text-slate-700 hover:text-brand-primary bg-slate-100 hover:bg-slate-200/70 px-2.5 sm:px-3 py-2 rounded-lg transition whitespace-nowrap">
          <svg class="w-4 h-4 text-brand-primary shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"/></svg>
          <span class="hidden sm:inline">Dự toán</span>
          <span id="quoteCountBadge" class="bg-brand-accent text-white text-[10px] font-bold px-1.5 py-0.5 rounded-full leading-none">0</span>
        </button>
      </div>
    </div>

    <!-- ======================================================================
         THANH DANH MỤC CHÍNH TRÊN MÁY TÍNH
         (Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng trong tên danh mục)
         ====================================================================== -->
    <nav aria-label="Danh mục chính" class="hidden lg:block bg-brand-primary text-white border-t border-white/10">
      <div class="container-95">
        <ul class="flex flex-wrap items-center justify-between xl:justify-center gap-x-0.5 xl:gap-x-1">
          <li>
            <a href="#trang-chu" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              Trang chủ
            </a>
          </li>
          <li>
            <a href="#gioi-thieu" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              Giới thiệu
            </a>
          </li>

          <!-- Danh mục có menu con: Cửa nhôm xingfa -->
          <li class="relative group">
            <a href="#san-pham" onclick="filterProductsByCategory('Cửa nhôm Xingfa')" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              <span>Cửa nhôm xingfa</span>
              <svg class="w-3.5 h-3.5 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <ul class="flatsome-dropdown absolute left-0 top-full w-60 bg-white text-slate-800 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50">
              <li><a href="#san-pham" onclick="filterProductsBySub('1 cánh')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham" onclick="filterProductsBySub('2 cánh')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham" onclick="filterProductsBySub('3 cánh')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham" onclick="filterProductsBySub('4 cánh')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham" onclick="filterProductsBySub('5 cánh')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </li>

          <li>
            <a href="#san-pham" onclick="filterProductsByCategory('Cửa kính cường lực')" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              Cửa kính cường lực
            </a>
          </li>

          <!-- Danh mục có menu con: Sản phẩm -->
          <li class="relative group">
            <a href="#danh-muc-noi-bat" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              <span>Sản phẩm</span>
              <svg class="w-3.5 h-3.5 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <ul class="flatsome-dropdown absolute left-0 top-full w-56 bg-white text-slate-800 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50">
              <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa nhôm Xingfa')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Cửa nhôm xingfa</a></li>
              <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa nhựa lõi thép')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Cửa nhựa lõi thép</a></li>
              <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa kính tự động')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Cửa kính tự động</a></li>
              <li><a href="#san-pham" onclick="filterProductsByCategory('Cầu thang kính')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Cầu thang kính</a></li>
              <li><a href="#san-pham" onclick="filterProductsByCategory('Kính ốp bếp')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap border-b border-slate-100">Kính ốp bếp</a></li>
              <li><a href="#san-pham" onclick="filterProductsByCategory('Phòng tắm kính')" class="block px-4 py-2 text-[13px] font-medium hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Phòng tắm kính</a></li>
            </ul>
          </li>

          <li>
            <a href="#cong-trinh" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              Công trình
            </a>
          </li>
          <li>
            <a href="#bang-bao-gia" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              Báo giá
            </a>
          </li>
          <li>
            <a href="#tin-tuc" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              Tin tức
            </a>
          </li>
          <li>
            <a href="#lien-he" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-bold uppercase tracking-tight whitespace-nowrap hover:bg-brand-accent transition">
              Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- ========================================================================
       DRAWER DANH MỤC MOBILE (TỐI ƯU GIAO DIỆN ĐIỆN THOẠI)
       ======================================================================== -->
  <div id="mobileDrawer" class="fixed inset-0 z-50 hidden">
    <div onclick="closeMobileMenu()" class="absolute inset-0 bg-slate-900/60 backdrop-blur-xs"></div>
    <aside class="relative w-[82%] max-w-xs h-full bg-white shadow-2xl flex flex-col overflow-y-auto">
      <div class="p-4 bg-brand-primary text-white flex items-center justify-between">
        <div>
          <p class="font-extrabold text-sm">NHÔM KÍNH XUÂN ĐỊNH</p>
          <p class="text-[11px] text-slate-200">Danh mục sản phẩm &amp; dịch vụ</p>
        </div>
        <button onclick="closeMobileMenu()" aria-label="Đóng menu" class="p-1.5 rounded-lg bg-white/10 hover:bg-white/20">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>

      <!-- Tìm kiếm trên Mobile -->
      <div class="p-3 border-b border-slate-100">
        <form onsubmit="handleMobileSearch(event)" class="flex items-center bg-slate-100 rounded-lg overflow-hidden border border-slate-200">
          <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm..." class="w-full px-3 py-2 text-xs bg-transparent focus:outline-none" />
          <button type="submit" class="px-3 py-2 bg-brand-primary text-white text-xs font-semibold">Tìm</button>
        </form>
      </div>

      <ul class="divide-y divide-slate-100 text-sm font-semibold text-slate-700">
        <li><a href="#trang-chu" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Trang chủ</a></li>
        <li><a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Giới thiệu</a></li>
        
        <!-- Accordion Cửa nhôm xingfa -->
        <li>
          <button type="button" onclick="toggleSubMenu('mobSubXingfa')" class="w-full px-4 py-3 flex items-center justify-between hover:bg-brand-light hover:text-brand-primary">
            <span>Cửa nhôm xingfa</span>
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
          </button>
          <ul id="mobSubXingfa" class="hidden bg-slate-50 pl-6 pr-3 py-1 space-y-1 text-xs font-medium text-slate-600">
            <li><a href="#san-pham" onclick="filterProductsBySub('1 cánh'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsBySub('2 cánh'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsBySub('3 cánh'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsBySub('4 cánh'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsBySub('5 cánh'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </li>

        <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa kính cường lực'); closeMobileMenu();" class="block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Cửa kính cường lực</a></li>

        <!-- Accordion Sản phẩm -->
        <li>
          <button type="button" onclick="toggleSubMenu('mobSubProducts')" class="w-full px-4 py-3 flex items-center justify-between hover:bg-brand-light hover:text-brand-primary">
            <span>Sản phẩm</span>
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
          </button>
          <ul id="mobSubProducts" class="hidden bg-slate-50 pl-6 pr-3 py-1 space-y-1 text-xs font-medium text-slate-600">
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa nhôm Xingfa'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cửa nhôm xingfa</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa nhựa lõi thép'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cửa nhựa lõi thép</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa kính tự động'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cửa kính tự động</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cầu thang kính'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Cầu thang kính</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Kính ốp bếp'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Kính ốp bếp</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Phòng tắm kính'); closeMobileMenu();" class="block py-2 hover:text-brand-primary">+ Phòng tắm kính</a></li>
          </ul>
        </li>

        <li><a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Công trình</a></li>
        <li><a href="#bang-bao-gia" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Báo giá</a></li>
        <li><a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Tin tức</a></li>
        <li><a href="#lien-he" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-light hover:text-brand-primary">Liên hệ</a></li>
      </ul>

      <div class="mt-auto p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
        <p class="font-bold text-brand-primary">CÔNG TY TNHH MTV XD XUÂN TRƯỜNG</p>
        <p>Đ/c: 17 Bàu Mạc 16, P. Liên Chiểu, Đà Nẵng</p>
        <p>Hotline: <a href="tel:0934123693" class="font-bold text-brand-accent">0934.123.693</a></p>
      </div>
    </aside>
  </div>

  <!-- ========================================================================
       [UX SECTION 3] 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       (Hình ảnh và chữ nằm gọn trong banner, chữ cách xa viền, không mất chữ trên ĐT & MT)
       ======================================================================== -->
  <section id="trang-chu" class="pt-3 lg:pt-4">
    <div class="container-95">
      <div class="relative overflow-hidden rounded-2xl shadow-md bg-brand-dark border border-slate-200/80">
        
        <!-- Khung trượt 2 slide bằng nhau tuyệt đối -->
        <div id="heroSliderTrack" class="hero-slider-track">
          
          <!-- SLIDE 1 -->
          <div class="hero-slide-item relative h-[270px] sm:h-[360px] md:h-[420px] lg:h-[470px] flex items-center">
            <!-- Ảnh nền công trình thực tế + lớp phủ gradient bảo vệ độ tương phản chữ -->
            <img
              src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w1600"
              data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
              onerror="handleDriveImgError(this)"
              alt="Thi công cửa nhôm Xingfa và kính cường lực Đà Nẵng - Nhôm Kính Xuân Định"
              class="absolute inset-0 w-full h-full object-cover object-center opacity-40"
            />
            <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-primary/85 to-brand-primary/50"></div>

            <!-- Vùng an toàn chữ cách xa 4 viền ảnh banner trên cả Mobile & Desktop -->
            <div class="relative z-10 w-full px-10 py-6 sm:px-16 sm:py-10 md:px-24 md:py-12 lg:px-28">
              <div class="max-w-2xl space-y-2 sm:space-y-3.5">
                <p class="inline-block text-[10px] sm:text-xs font-bold uppercase tracking-widest text-amber-300 bg-white/10 border border-amber-300/30 px-2.5 py-1 rounded-md">
                  NHÔM KÍNH XUÂN ĐỊNH • ĐÀ NẴNG
                </p>
                <h1 class="text-[16px] sm:text-2xl md:text-3xl lg:text-[38px] font-extrabold text-white leading-snug">
                  THI CÔNG CỬA NHÔM XINGFA &amp; KÍNH CƯỜNG LỰC CHÍNH HÃNG
                </h1>
                <p class="text-[11px] sm:text-sm md:text-base text-slate-100/95 leading-relaxed max-w-xl">
                  Giải pháp cửa bền đẹp cho nhà phố, biệt thự, khách sạn &amp; resort tại Đà Nẵng. Phụ kiện Kinlong đồng bộ, bảo hành dài hạn.
                </p>
                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 sm:gap-3">
                  <a href="#form-bao-gia" class="inline-flex items-center justify-center bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-[11px] sm:text-sm px-3.5 py-2 sm:px-5 sm:py-2.5 rounded-lg shadow transition">
                    Nhận báo giá miễn phí
                  </a>
                  <a href="#san-pham" class="inline-flex items-center justify-center bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-[11px] sm:text-sm px-3.5 py-2 sm:px-5 sm:py-2.5 rounded-lg transition">
                    Xem mẫu cửa mới
                  </a>
                </div>
              </div>
            </div>
          </div>

          <!-- SLIDE 2 (Kích thước chiều ngang & chiều cao bằng 100% Slide 1) -->
          <div class="hero-slide-item relative h-[270px] sm:h-[360px] md:h-[420px] lg:h-[470px] flex items-center">
            <img
              src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ=w1600"
              data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
              onerror="handleDriveImgError(this)"
              alt="Xưởng sản xuất Nhôm Kính Xuân Định - Công Ty TNHH MTV XD Xuân Trường"
              class="absolute inset-0 w-full h-full object-cover object-center opacity-40"
            />
            <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-medium/85 to-brand-dark/55"></div>

            <!-- Vùng an toàn chữ cách xa 4 viền ảnh banner trên cả Mobile & Desktop -->
            <div class="relative z-10 w-full px-10 py-6 sm:px-16 sm:py-10 md:px-24 md:py-12 lg:px-28">
              <div class="max-w-2xl space-y-2 sm:space-y-3.5">
                <p class="inline-block text-[10px] sm:text-xs font-bold uppercase tracking-widest text-amber-300 bg-white/10 border border-amber-300/30 px-2.5 py-1 rounded-md">
                  CÔNG TY TNHH MTV XD XUÂN TRƯỜNG
                </p>
                <h2 class="text-[16px] sm:text-2xl md:text-3xl lg:text-[38px] font-extrabold text-white leading-snug">
                  GIÁ GỐC TẠI XƯỞNG • LẮP ĐẶT TẬN NƠI TẠI LIÊN CHIỂU, ĐÀ NẴNG
                </h2>
                <p class="text-[11px] sm:text-sm md:text-base text-slate-100/95 leading-relaxed max-w-xl">
                  Chuyên cửa nhôm Xingfa 1–5 cánh, cầu thang kính, kính ốp bếp, phòng tắm kính, cửa tự động. Tư vấn tận tâm – Thi công đúng tiến độ.
                </p>
                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 sm:gap-3">
                  <a href="#cong-trinh" class="inline-flex items-center justify-center bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-[11px] sm:text-sm px-3.5 py-2 sm:px-5 sm:py-2.5 rounded-lg shadow transition">
                    Công trình tiêu biểu
                  </a>
                  <a href="#bang-bao-gia" class="inline-flex items-center justify-center bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-[11px] sm:text-sm px-3.5 py-2 sm:px-5 sm:py-2.5 rounded-lg transition">
                    Bảng giá 2026
                  </a>
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng trái / phải nhỏ gọn sát mép không đè chữ -->
        <button type="button" onclick="prevBannerSlide()" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition">
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button type="button" onclick="nextBannerSlide()" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition">
          <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Chấm chuyển slide -->
        <div class="absolute bottom-2.5 sm:bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToBannerSlide(0)" id="bannerDot0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-brand-accent transition-all"></button>
          <button type="button" onclick="goToBannerSlide(1)" id="bannerDot1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 4] 4 CAM KẾT DỊCH VỤ & THỐNG KÊ NĂNG LỰC (MẪU NGOCHANWINDOW)
       ======================================================================== -->
  <section class="py-5 lg:py-6">
    <div class="container-95">
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
        <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200/80 shadow-2xs flex items-center gap-3">
          <div class="w-10 h-10 rounded-lg bg-brand-light text-brand-primary flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
          </div>
          <div class="min-w-0">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 truncate">Vật tư chính hãng</h3>
            <p class="text-[11px] sm:text-xs text-slate-500 truncate">Nhôm Xingfa &amp; Kinlong chuẩn</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200/80 shadow-2xs flex items-center gap-3">
          <div class="w-10 h-10 rounded-lg bg-amber-50 text-brand-accent flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          </div>
          <div class="min-w-0">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 truncate">Ưu đãi đến 20%</h3>
            <p class="text-[11px] sm:text-xs text-slate-500 truncate">Giá trực tiếp tại xưởng SX</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200/80 shadow-2xs flex items-center gap-3">
          <div class="w-10 h-10 rounded-lg bg-brand-light text-brand-primary flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>
          </div>
          <div class="min-w-0">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 truncate">Lắp đặt miễn phí</h3>
            <p class="text-[11px] sm:text-xs text-slate-500 truncate">Đo đạc tận nhà tại Đà Nẵng</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200/80 shadow-2xs flex items-center gap-3">
          <div class="w-10 h-10 rounded-lg bg-amber-50 text-brand-accent flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>
          </div>
          <div class="min-w-0">
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 truncate">Bảo hành 5–10 năm</h3>
            <p class="text-[11px] sm:text-xs text-slate-500 truncate">Hỗ trợ kỹ thuật 24/7</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 5] DANH MỤC SẢN PHẨM NỔI BẬT (CHỮ DANH MỤC TRANG CHỦ NHỎ GỌN)
       ======================================================================== -->
  <section id="danh-muc-noi-bat" class="py-4 lg:py-6">
    <div class="container-95">
      <div class="flex items-center justify-between mb-4 border-b border-slate-200 pb-2.5">
        <div class="flex items-center gap-2">
          <span class="w-1.5 h-5 bg-brand-accent rounded-full"></span>
          <h2 class="text-sm sm:text-base lg:text-lg font-extrabold uppercase text-brand-primary tracking-tight">
            Danh mục sản phẩm nổi bật
          </h2>
        </div>
        <a href="#san-pham" onclick="filterProductsByCategory('Tất cả')" class="text-xs font-semibold text-brand-medium hover:text-brand-accent transition whitespace-nowrap">
          Xem tất cả →
        </a>
      </div>

      <!-- 6 Danh mục sản phẩm sử dụng đúng 6 ảnh Google Drive của bạn -->
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-4">
        
        <a href="#san-pham" onclick="filterProductsByCategory('Cửa nhôm Xingfa')" class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md hover:border-brand-primary transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w800" data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX" onerror="handleDriveImgError(this)" alt="Cửa nhôm Xingfa" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-2.5 text-center bg-white">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase tracking-tight truncate">
              Cửa nhôm Xingfa
            </h3>
          </div>
        </a>

        <a href="#san-pham" onclick="filterProductsByCategory('Cửa nhựa lõi thép')" class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md hover:border-brand-primary transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w800" data-drive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA" onerror="handleDriveImgError(this)" alt="Cửa nhựa lõi thép" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-2.5 text-center bg-white">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase tracking-tight truncate">
              Cửa nhựa lõi thép
            </h3>
          </div>
        </a>

        <a href="#san-pham" onclick="filterProductsByCategory('Cửa kính tự động')" class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md hover:border-brand-primary transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ=w800" data-drive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ" onerror="handleDriveImgError(this)" alt="Cửa kính tự động" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-2.5 text-center bg-white">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase tracking-tight truncate">
              Cửa tự động
            </h3>
          </div>
        </a>

        <a href="#san-pham" onclick="filterProductsByCategory('Cầu thang kính')" class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md hover:border-brand-primary transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w800" data-drive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul" onerror="handleDriveImgError(this)" alt="Cầu thang kính" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-2.5 text-center bg-white">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase tracking-tight truncate">
              Cầu thang kính
            </h3>
          </div>
        </a>

        <a href="#san-pham" onclick="filterProductsByCategory('Kính ốp bếp')" class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md hover:border-brand-primary transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb=w800" data-drive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb" onerror="handleDriveImgError(this)" alt="Kính ốp bếp" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-2.5 text-center bg-white">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase tracking-tight truncate">
              Kính ốp bếp
            </h3>
          </div>
        </a>

        <a href="#san-pham" onclick="filterProductsByCategory('Phòng tắm kính')" class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md hover:border-brand-primary transition flex flex-col">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w800" data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH" onerror="handleDriveImgError(this)" alt="Phòng tắm kính" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-2.5 text-center bg-white">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 group-hover:text-brand-primary uppercase tracking-tight truncate">
              Phòng tắm kính
            </h3>
          </div>
        </a>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 6] SẢN PHẨM NỔI BẬT (2 CỘT TRÊN ĐIỆN THOẠI, GIÁ & GIẢM GIÁ % GÓC TRÊN TRÁI)
       ======================================================================== -->
  <section id="san-pham" class="py-6 lg:py-8">
    <div class="container-95">
      <div class="flex flex-col md:flex-row md:items-center justify-between gap-3 mb-5 border-b border-slate-200 pb-3">
        <div class="flex items-center gap-2">
          <span class="w-1.5 h-5 bg-brand-accent rounded-full"></span>
          <h2 class="text-sm sm:text-base lg:text-lg font-extrabold uppercase text-brand-primary tracking-tight">
            Sản phẩm nổi bật &amp; Báo giá lắp đặt
          </h2>
        </div>

        <!-- Thanh lọc danh mục gọn gàng -->
        <div id="productFilterTabs" class="flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-1 md:pb-0">
          <!-- Render bằng JS -->
        </div>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
      <div id="productsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4 lg:gap-5">
        <!-- Render động bằng JavaScript -->
      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 7] GIỚI THIỆU CÔNG TY TNHH MTV TM - DV - SX - XD XUÂN TRƯỜNG
       ======================================================================== -->
  <section id="gioi-thieu" class="py-6 lg:py-10 bg-white border-y border-slate-200/80">
    <div class="container-95">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
        <!-- Cột nội dung giới thiệu -->
        <div class="lg:col-span-7 space-y-3.5">
          <div class="inline-flex items-center gap-2 bg-brand-light text-brand-primary text-xs font-bold px-3 py-1 rounded-full">
            <span>VỀ CHÚNG TÔI • NHÔM KÍNH XUÂN ĐỊNH</span>
          </div>
          <h2 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-primary leading-snug">
            CÔNG TY TNHH MTV THƯƠNG MẠI - DỊCH VỤ - SẢN XUẤT - XÂY DỰNG XUÂN TRƯỜNG
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
            <strong>Nhôm Kính Xuân Định</strong> (trực thuộc <em>Công Ty TNHH MTV Thương Mại - Dịch Vụ - Sản Xuất - Xây Dựng Xuân Trường</em>) là đơn vị trực tiếp tư vấn, gia công sản xuất và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại <strong>Đà Nẵng</strong> và khu vực Miền Trung.
          </p>
          <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
            Với xưởng sản xuất hiện đại tọa lạc tại <strong>17 Bàu Mạc 16, Phường Liên Chiểu, TP Đà Nẵng</strong> cùng đội ngũ kỹ thuật viên lành nghề, chúng tôi cam kết mang đến những bộ cửa nhôm Xingfa nhập khẩu tem đỏ, cửa kính cường lực, cửa nhựa lõi thép uPVC, cầu thang kính, kính màu ốp bếp và cabin phòng tắm kính đạt độ kín khít tuyệt đối, cách âm – cách nhiệt vượt trội và thẩm mỹ bền vững theo thời gian.
          </p>

          <!-- 4 Con số ấn tượng -->
          <div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5 pt-2">
            <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-3 text-center">
              <div class="text-lg sm:text-xl font-extrabold text-brand-accent">150+</div>
              <div class="text-[11px] sm:text-xs font-semibold text-slate-600">Dự án hoàn thành</div>
            </div>
            <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-3 text-center">
              <div class="text-lg sm:text-xl font-extrabold text-brand-primary">50+</div>
              <div class="text-[11px] sm:text-xs font-semibold text-slate-600">Thợ kỹ thuật giỏi</div>
            </div>
            <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-3 text-center">
              <div class="text-lg sm:text-xl font-extrabold text-brand-accent">100+</div>
              <div class="text-[11px] sm:text-xs font-semibold text-slate-600">Mẫu cửa đa dạng</div>
            </div>
            <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-3 text-center">
              <div class="text-lg sm:text-xl font-extrabold text-brand-primary">100%</div>
              <div class="text-[11px] sm:text-xs font-semibold text-slate-600">Khách hàng hài lòng</div>
            </div>
          </div>
        </div>

        <!-- Cột hình ảnh công trình thực tế -->
        <div class="lg:col-span-5">
          <div class="relative rounded-2xl overflow-hidden shadow-md border border-slate-200 bg-slate-100 aspect-[16/11]">
            <img
              src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc=w1000"
              data-drive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc"
              onerror="handleDriveImgError(this)"
              alt="Thi công nhôm kính dự án tại Đà Nẵng - Nhôm Kính Xuân Định"
              class="w-full h-full object-cover"
            />
            <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-brand-dark/90 via-brand-dark/60 to-transparent p-4 text-white">
              <p class="text-xs sm:text-sm font-bold">Xưởng sản xuất &amp; Văn phòng giao dịch</p>
              <p class="text-[11px] text-slate-200">17 Bàu Mạc 16, Phường Liên Chiểu, TP Đà Nẵng</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 8] CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 ẢNH DỰ ÁN TỪ GOOGLE DRIVE)
       ======================================================================== -->
  <section id="cong-trinh" class="py-6 lg:py-8">
    <div class="container-95">
      <div class="flex items-center justify-between mb-4 border-b border-slate-200 pb-2.5">
        <div class="flex items-center gap-2">
          <span class="w-1.5 h-5 bg-brand-accent rounded-full"></span>
          <h2 class="text-sm sm:text-base lg:text-lg font-extrabold uppercase text-brand-primary tracking-tight">
            Các công trình &amp; dự án tiêu biểu tại Đà Nẵng
          </h2>
        </div>
        <span class="hidden sm:inline text-xs font-medium text-slate-500">Thi công thực tế bởi Nhôm Kính Xuân Định</span>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-3.5 sm:gap-5">
        
        <!-- Dự án 1 -->
        <article class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md transition">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ=w900" data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ" onerror="handleDriveImgError(this)" alt="DỰ ÁN KHÁCH SẠN RUBY LIGHT" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-3.5">
            <span class="text-[11px] font-semibold text-brand-accent uppercase">Khách sạn • Đà Nẵng</span>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary mt-1 line-clamp-2">
              DỰ ÁN KHÁCH SẠN RUBY LIGHT
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Thi công toàn bộ hệ thống cửa đi, cửa sổ nhôm Xingfa hệ 55 và vách kính cường lực mặt tiền.</p>
          </div>
        </article>

        <!-- Dự án 2 -->
        <article class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md transition">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w900" data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ" onerror="handleDriveImgError(this)" alt="DỰ ÁN RESORT MỸ SƠN 4 SAO MY SON HERITAGE RESORT & SPA" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-3.5">
            <span class="text-[11px] font-semibold text-brand-accent uppercase">Khu nghỉ dưỡng 4 sao</span>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary mt-1 line-clamp-2">
              DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Cung cấp &amp; lắp đặt cửa nhôm kính cách âm cao cấp, cabin phòng tắm kính cho khu lưu trú.</p>
          </div>
        </article>

        <!-- Dự án 3 -->
        <article class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md transition">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy=w900" data-drive-id="1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy" onerror="handleDriveImgError(this)" alt="THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-3.5">
            <span class="text-[11px] font-semibold text-brand-accent uppercase">Khách sạn • Đà Nẵng</span>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary mt-1 line-clamp-2">
              THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Thi công cửa kính tự động sảnh chính, lan can kính ban công và hệ cửa nhôm Xingfa đồng bộ.</p>
          </div>
        </article>

        <!-- Dự án 4 -->
        <article class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md transition">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64=w900" data-drive-id="1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64" onerror="handleDriveImgError(this)" alt="THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-3.5">
            <span class="text-[11px] font-semibold text-brand-accent uppercase">Khách sạn &amp; Căn hộ</span>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary mt-1 line-clamp-2">
              THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Hạng mục cửa sổ mở hất chống gió bão ven biển, vách kính cường lực 10mm – 12mm an toàn.</p>
          </div>
        </article>

        <!-- Dự án 5 -->
        <article class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md transition">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt=w900" data-drive-id="1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt" onerror="handleDriveImgError(this)" alt="THI CÔNG DỰ ÁN KHÁCH SẠN SOHO" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-3.5">
            <span class="text-[11px] font-semibold text-brand-accent uppercase">Khách sạn Boutique</span>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary mt-1 line-clamp-2">
              THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Lắp đặt cửa đi mở quay nhôm Xingfa, phòng tắm kính cường lực phụ kiện inox 304 cao cấp.</p>
          </div>
        </article>

        <!-- Dự án 6 -->
        <article class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md transition">
          <div class="aspect-[16/10] overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc=w900" data-drive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc" onerror="handleDriveImgError(this)" alt="THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-3.5">
            <span class="text-[11px] font-semibold text-brand-accent uppercase">Khách sạn biển Đà Nẵng</span>
            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary mt-1 line-clamp-2">
              THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
            </h3>
            <p class="text-[11px] sm:text-xs text-slate-500 mt-1">Thi công mặt dựng kính cường lực chịu áp lực gió biển, cửa đi xếp trượt nhôm Xingfa.</p>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 9] BẢNG BÁO GIÁ THAM KHẢO NHANH TẠI ĐÀ NẴNG
       ======================================================================== -->
  <section id="bang-bao-gia" class="py-6 lg:py-8 bg-white border-y border-slate-200/80">
    <div class="container-95">
      <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-4 border-b border-slate-200 pb-2.5">
        <div class="flex items-center gap-2">
          <span class="w-1.5 h-5 bg-brand-accent rounded-full"></span>
          <h2 class="text-sm sm:text-base lg:text-lg font-extrabold uppercase text-brand-primary tracking-tight">
            Bảng báo giá thi công nhôm kính tham khảo 2026
          </h2>
        </div>
        <span class="text-xs text-slate-500">Đơn giá đã bao gồm vận chuyển &amp; lắp đặt tại Đà Nẵng</span>
      </div>

      <div class="overflow-x-auto rounded-xl border border-slate-200">
        <table class="w-full text-left border-collapse text-xs sm:text-sm">
          <thead>
            <tr class="bg-brand-primary text-white">
              <th class="py-2.5 px-3 sm:px-4 font-bold">STT</th>
              <th class="py-2.5 px-3 sm:px-4 font-bold">Hạng mục sản phẩm</th>
              <th class="py-2.5 px-3 sm:px-4 font-bold">Quy cách kỹ thuật</th>
              <th class="py-2.5 px-3 sm:px-4 font-bold text-right">Đơn giá ưu đãi</th>
            </tr>
          </thead>
          <tbody class="divide-y divide-slate-200 bg-white">
            <tr class="hover:bg-brand-light/40">
              <td class="py-2.5 px-3 sm:px-4 font-semibold">01</td>
              <td class="py-2.5 px-3 sm:px-4 font-bold text-slate-800">Cửa sổ mở quay / mở hất nhôm Xingfa</td>
              <td class="py-2.5 px-3 sm:px-4 text-slate-600">Nhôm Xingfa hệ 55 dày 1.4mm, kính cường lực 8mm</td>
              <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-red-600 whitespace-nowrap">1.650.000 ₫/m²</td>
            </tr>
            <tr class="hover:bg-brand-light/40">
              <td class="py-2.5 px-3 sm:px-4 font-semibold">02</td>
              <td class="py-2.5 px-3 sm:px-4 font-bold text-slate-800">Cửa đi mở quay 1, 2, 4 cánh nhôm Xingfa</td>
              <td class="py-2.5 px-3 sm:px-4 text-slate-600">Nhôm Xingfa hệ 55 dày 2.0mm, kính cường lực 8mm</td>
              <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-red-600 whitespace-nowrap">1.785.000 ₫/m²</td>
            </tr>
            <tr class="hover:bg-brand-light/40">
              <td class="py-2.5 px-3 sm:px-4 font-semibold">03</td>
              <td class="py-2.5 px-3 sm:px-4 font-bold text-slate-800">Cửa đi xếp trượt nhôm Xingfa hệ 63</td>
              <td class="py-2.5 px-3 sm:px-4 text-slate-600">Nhôm Xingfa dày 1.8–2.5mm, kính cường lực 8mm–10mm</td>
              <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-red-600 whitespace-nowrap">1.950.000 ₫/m²</td>
            </tr>
            <tr class="hover:bg-brand-light/40">
              <td class="py-2.5 px-3 sm:px-4 font-semibold">04</td>
              <td class="py-2.5 px-3 sm:px-4 font-bold text-slate-800">Cửa kính cường lực bản lề sàn 10mm</td>
              <td class="py-2.5 px-3 sm:px-4 text-slate-600">Kính cường lực Việt Nhật 10ly tôi chuẩn, phụ kiện VVP</td>
              <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-red-600 whitespace-nowrap">750.000 ₫/m²</td>
            </tr>
            <tr class="hover:bg-brand-light/40">
              <td class="py-2.5 px-3 sm:px-4 font-semibold">05</td>
              <td class="py-2.5 px-3 sm:px-4 font-bold text-slate-800">Cửa nhựa lõi thép uPVC cao cấp</td>
              <td class="py-2.5 px-3 sm:px-4 text-slate-600">Thanh nhựa Sparlee lõi thép mạ kẽm, kính 8mm</td>
              <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-red-600 whitespace-nowrap">1.250.000 ₫/m²</td>
            </tr>
            <tr class="hover:bg-brand-light/40">
              <td class="py-2.5 px-3 sm:px-4 font-semibold">06</td>
              <td class="py-2.5 px-3 sm:px-4 font-bold text-slate-800">Kính màu ốp bếp cường lực 8mm</td>
              <td class="py-2.5 px-3 sm:px-4 text-slate-600">Kính tôi cường lực 8ly sơn chịu nhiệt đa sắc màu</td>
              <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-red-600 whitespace-nowrap">720.000 ₫/md</td>
            </tr>
            <tr class="hover:bg-brand-light/40">
              <td class="py-2.5 px-3 sm:px-4 font-semibold">07</td>
              <td class="py-2.5 px-3 sm:px-4 font-bold text-slate-800">Cầu thang kính &amp; Phòng tắm kính 10mm–12mm</td>
              <td class="py-2.5 px-3 sm:px-4 text-slate-600">Kính cường lực 10–12mm, phụ kiện Inox 304 chống gỉ</td>
              <td class="py-2.5 px-3 sm:px-4 text-right font-bold text-red-600 whitespace-nowrap">1.150.000 ₫/md</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 10] FORM YÊU CẦU & BÁO GIÁ + BẢN ĐỒ GOOGLE MAP + FANPAGE FACEBOOK
       (Hiển thị trực tiếp ngay ngoài trang chủ theo yêu cầu)
       ======================================================================== -->
  <section id="form-bao-gia" class="py-6 lg:py-8">
    <div class="container-95">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
        
        <!-- Cột 1 (5/12): FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ -->
        <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 shadow-sm p-5 sm:p-6 flex flex-col justify-between">
          <div>
            <div class="flex items-center gap-2 mb-1">
              <span class="w-1.5 h-5 bg-brand-accent rounded-full"></span>
              <h2 class="text-sm sm:text-base lg:text-lg font-extrabold uppercase text-brand-primary">
                Đăng ký nhận báo giá nhanh
              </h2>
            </div>
            <p class="text-xs text-slate-500 mb-4">
              Để lại thông tin, kỹ thuật viên <strong>Nhôm Kính Xuân Định</strong> sẽ khảo sát &amp; gửi bảng dự toán chi tiết sau 15 phút.
            </p>

            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
              <div>
                <label for="cusName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                <input id="cusName" type="text" required placeholder="Nhập họ tên của bạn..." class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:border-brand-primary focus:outline-none" />
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label for="cusPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="cusPhone" type="tel" required placeholder="VD: 0934.123.693" class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:border-brand-primary focus:outline-none" />
                </div>
                <div>
                  <label for="cusCategory" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                  <select id="cusCategory" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-primary focus:outline-none">
                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                    <option value="Cầu thang kính">Cầu thang kính</option>
                    <option value="Kính ốp bếp">Kính ốp bếp</option>
                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                  </select>
                </div>
              </div>

              <div>
                <label for="cusAddress" class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình &amp; Ghi chú kích thước</label>
                <textarea id="cusAddress" rows="3" placeholder="VD: Nhà phố 3 tầng tại Quận Liên Chiểu, Đà Nẵng..." class="w-full px-3.5 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:border-brand-primary focus:outline-none"></textarea>
              </div>

              <button type="submit" class="w-full bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg shadow transition">
                GỬI YÊU CẦU BÁO GIÁ NGAY
              </button>
            </form>
          </div>

          <!-- Thông báo phản hồi Form (Không dùng alert) -->
          <div id="quoteFormFeedback" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs leading-relaxed"></div>
        </div>

        <!-- Cột 2 (4/12): BẢN ĐỒ GOOGLE MAP TRỰC TIẾP NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-4 bg-white rounded-2xl border border-slate-200 shadow-sm p-4 sm:p-5 flex flex-col">
          <div class="flex items-center justify-between mb-2.5">
            <div class="flex items-center gap-2">
              <span class="w-1.5 h-5 bg-brand-accent rounded-full"></span>
              <h2 class="text-sm sm:text-base font-extrabold uppercase text-brand-primary">
                Bản đồ Google Map
              </h2>
            </div>
            <a href="https://maps.google.com/?q=17+Bàu+Mạc+16,+Phường+Liên+Chiểu,+TP+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold text-brand-medium hover:underline">
              Chỉ đường ↗
            </a>
          </div>
          <p class="text-xs text-slate-600 mb-3">
            <strong>Địa chỉ:</strong> 17 Bàu Mạc 16, Phường Liên Chiểu, TP Đà Nẵng
          </p>
          <div class="flex-1 min-h-[250px] rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
            <iframe
              title="Bản đồ Nhôm Kính Xuân Định - 17 Bàu Mạc 16, Liên Chiểu, Đà Nẵng"
              src="https://maps.google.com/maps?q=17%20B%C3%A0u%20M%E1%BA%A1c%2016,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full min-h-[250px] border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>

        <!-- Cột 3 (3/12): FANPAGE FACEBOOK CHÍNH THỨC NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-3 bg-white rounded-2xl border border-slate-200 shadow-sm p-4 sm:p-5 flex flex-col">
          <div class="flex items-center justify-between mb-2.5">
            <div class="flex items-center gap-2">
              <span class="w-1.5 h-5 bg-[#1877F2] rounded-full"></span>
              <h2 class="text-sm sm:text-base font-extrabold uppercase text-brand-primary">
                Fanpage Facebook
              </h2>
            </div>
            <a href="https://www.facebook.com/nhomkinhxuandinh" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold text-[#1877F2] hover:underline">
              Theo dõi ↗
            </a>
          </div>

          <!-- Card giao diện Fanpage đồng bộ + iframe nhúng chính thức -->
          <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex-1 flex flex-col justify-between">
            <div>
              <div class="relative h-24 bg-brand-primary overflow-hidden">
                <img src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w600" data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX" onerror="handleDriveImgError(this)" alt="Cover Fanpage Nhôm Kính Xuân Định" class="w-full h-full object-cover opacity-55" />
                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent"></div>
                <div class="absolute bottom-2 left-3 right-3 flex items-center gap-2.5">
                  <div class="w-10 h-10 rounded-lg bg-brand-primary border-2 border-white flex items-center justify-center text-white font-extrabold text-xs shrink-0 shadow">
                    XĐ
                  </div>
                  <div class="min-w-0 text-white">
                    <a href="https://www.facebook.com/nhomkinhxuandinh" target="_blank" rel="noopener noreferrer" class="block text-xs font-bold truncate hover:underline">
                      Nhôm Kính Xuân Định
                    </a>
                    <p class="text-[10px] text-slate-200 truncate">facebook.com/nhomkinhxuandinh</p>
                  </div>
                </div>
              </div>

              <div class="p-3 space-y-2 text-xs text-slate-600">
                <p class="font-semibold text-slate-800">CÔNG TY TNHH MTV XD XUÂN TRƯỜNG</p>
                <p class="text-[11px] leading-relaxed">
                  Chuyên sản xuất &amp; thi công cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính, kính ốp bếp tại Đà Nẵng.
                </p>
                <div class="flex items-center gap-2 pt-1">
                  <a href="https://www.facebook.com/nhomkinhxuandinh" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 bg-[#1877F2] hover:bg-[#166FE5] text-white font-bold text-[11px] py-2 px-3 rounded-lg transition">
                    <svg class="w-3.5 h-3.5 fill-current" viewBox="0 0 24 24"><path d="M22 12c0-5.52-4.48-10-10-10S2 6.48 2 12c0 4.84 3.44 8.87 8 9.8V15H8v-3h2V9.5C10 7.57 11.57 6 13.5 6H16v3h-2c-.55 0-1 .45-1 1v2h3v3h-3v6.95c5.05-.5 9-4.76 9-9.95z"/></svg>
                    <span>Thích Trang</span>
                  </a>
                  <a href="https://zalo.me/0934123693" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center bg-white hover:bg-slate-100 text-slate-700 border border-slate-300 font-semibold text-[11px] py-2 px-2.5 rounded-lg transition">
                    Nhắn tin
                  </a>
                </div>
              </div>
            </div>

            <!-- Nhúng plugin Facebook Page chính thức -->
            <div class="border-t border-slate-200 bg-white overflow-hidden">
              <iframe
                title="Facebook Fanpage Nhôm Kính Xuân Định"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fnhomkinhxuandinh&tabs=&width=340&height=130&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=false"
                width="100%"
                height="130"
                style="border:none;overflow:hidden"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                loading="lazy">
              </iframe>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 11] DANH MỤC CÁC BÀI VIẾT & TIN TỨC NỔI BẬT TRANG CHỦ
       ======================================================================== -->
  <section id="tin-tuc" class="py-6 lg:py-8 bg-white border-t border-slate-200/80">
    <div class="container-95">
      <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3 mb-4 border-b border-slate-200 pb-2.5">
        <div class="flex items-center gap-2">
          <span class="w-1.5 h-5 bg-brand-accent rounded-full"></span>
          <h2 class="text-sm sm:text-base lg:text-lg font-extrabold uppercase text-brand-primary tracking-tight">
            Danh mục bài viết &amp; Cẩm nang nhôm kính
          </h2>
        </div>

        <!-- Danh mục bài viết trang chủ nhỏ gọn -->
        <div id="newsCategoryTabs" class="flex items-center gap-1.5 overflow-x-auto no-scrollbar">
          <button type="button" onclick="filterArticles('Tất cả')" data-news-cat="Tất cả" class="news-tab-btn px-3 py-1 rounded-full text-xs font-bold bg-brand-primary text-white whitespace-nowrap transition">Tất cả bài viết</button>
          <button type="button" onclick="filterArticles('Kinh nghiệm chọn cửa')" data-news-cat="Kinh nghiệm chọn cửa" class="news-tab-btn px-3 py-1 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light whitespace-nowrap transition">Kinh nghiệm chọn cửa</button>
          <button type="button" onclick="filterArticles('Báo giá & Kỹ thuật')" data-news-cat="Báo giá & Kỹ thuật" class="news-tab-btn px-3 py-1 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light whitespace-nowrap transition">Báo giá &amp; Kỹ thuật</button>
          <button type="button" onclick="filterArticles('Phong thủy & Thẩm mỹ')" data-news-cat="Phong thủy & Thẩm mỹ" class="news-tab-btn px-3 py-1 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light whitespace-nowrap transition">Phong thủy &amp; Thẩm mỹ</button>
        </div>
      </div>

      <div id="articlesGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5 sm:gap-5">
        <!-- Render động bằng JavaScript -->
      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 12] ĐỐI TÁC CHIẾN LƯỢC (6 ẢNH LOGO ĐỐI TÁC TỪ GOOGLE DRIVE)
       ======================================================================== -->
  <section class="py-6 lg:py-8">
    <div class="container-95">
      <div class="flex items-center gap-2 mb-4 border-b border-slate-200 pb-2.5">
        <span class="w-1.5 h-5 bg-brand-accent rounded-full"></span>
        <h2 class="text-sm sm:text-base lg:text-lg font-extrabold uppercase text-brand-primary tracking-tight">
          Đối tác cung cấp vật tư chính hãng
        </h2>
      </div>

      <div class="grid grid-cols-3 sm:grid-cols-6 gap-2.5 sm:gap-4">
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-2xs hover:border-brand-primary transition">
          <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk=w400" data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" onerror="handleDriveImgError(this)" alt="Đối tác Xingfa" class="max-h-14 w-auto object-contain" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-2xs hover:border-brand-primary transition">
          <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq=w400" data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" onerror="handleDriveImgError(this)" alt="Đối tác Kinlong" class="max-h-14 w-auto object-contain" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-2xs hover:border-brand-primary transition">
          <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn=w400" data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" onerror="handleDriveImgError(this)" alt="Đối tác phụ kiện VVP" class="max-h-14 w-auto object-contain" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-2xs hover:border-brand-primary transition">
          <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT=w400" data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" onerror="handleDriveImgError(this)" alt="Đối tác kính cường lực" class="max-h-14 w-auto object-contain" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-2xs hover:border-brand-primary transition">
          <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-=w400" data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" onerror="handleDriveImgError(this)" alt="Đối tác cửa cuốn cửa nhôm" class="max-h-14 w-auto object-contain" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-2xs hover:border-brand-primary transition">
          <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg=w400" data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" onerror="handleDriveImgError(this)" alt="Đối tác vật tư xây dựng" class="max-h-14 w-auto object-contain" />
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       [UX SECTION 13] FOOTER CHUYÊN NGHIỆP (THÔNG TIN ĐẦY ĐỦ THEO MẪU FLATSOME)
       ======================================================================== -->
  <footer id="lien-he" class="bg-brand-dark text-slate-300 pt-10 pb-20 lg:pb-10 border-t-4 border-brand-accent">
    <div class="container-95">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">
        
        <!-- Cột 1: Thông tin pháp lý công ty -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-2.5">
            <div class="w-9 h-9 rounded-lg bg-brand-primary border border-brand-accent flex items-center justify-center text-white font-extrabold text-sm">
              XĐ
            </div>
            <div>
              <p class="text-white font-extrabold text-base tracking-tight">NHÔM KÍNH XUÂN ĐỊNH</p>
              <p class="text-[11px] text-amber-400 font-semibold">nhomkinhxuandinh.com</p>
            </div>
          </div>
          <p class="text-xs sm:text-sm font-bold text-white leading-snug">
            CÔNG TY TNHH MTV THƯƠNG MẠI - DỊCH VỤ - SẢN XUẤT - XÂY DỰNG XUÂN TRƯỜNG
          </p>
          <ul class="space-y-2 text-xs text-slate-300">
            <li class="flex items-start gap-2">
              <span class="text-brand-accent font-bold">Địa chỉ:</span>
              <span>17 Bàu Mạc 16, Phường Liên Chiểu, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <span class="text-brand-accent font-bold">Hotline / Zalo:</span>
              <a href="tel:0934123693" class="text-white font-bold hover:text-amber-400">0934.123.693</a>
            </li>
            <li class="flex items-center gap-2">
              <span class="text-brand-accent font-bold">Website:</span>
              <span>www.nhomkinhxuandinh.com</span>
            </li>
            <li class="flex items-center gap-2">
              <span class="text-brand-accent font-bold">Fanpage:</span>
              <a href="https://www.facebook.com/nhomkinhxuandinh" target="_blank" rel="noopener noreferrer" class="hover:text-amber-400 underline">facebook.com/nhomkinhxuandinh</a>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục dịch vụ -->
        <div class="lg:col-span-4 space-y-2.5">
          <h3 class="text-xs sm:text-sm font-extrabold uppercase text-white tracking-wider border-b border-white/15 pb-2">
            Danh mục sản phẩm &amp; dịch vụ
          </h3>
          <ul class="grid grid-cols-2 gap-x-3 gap-y-2 text-xs">
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa nhôm Xingfa')" class="hover:text-amber-400 transition">• Cửa nhôm Xingfa 1–5 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa kính cường lực')" class="hover:text-amber-400 transition">• Cửa kính cường lực</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa nhựa lõi thép')" class="hover:text-amber-400 transition">• Cửa nhựa lõi thép uPVC</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cửa kính tự động')" class="hover:text-amber-400 transition">• Cửa kính tự động</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Cầu thang kính')" class="hover:text-amber-400 transition">• Cầu thang kính cường lực</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Kính ốp bếp')" class="hover:text-amber-400 transition">• Kính màu ốp bếp 8mm</a></li>
            <li><a href="#san-pham" onclick="filterProductsByCategory('Phòng tắm kính')" class="hover:text-amber-400 transition">• Phòng tắm kính cường lực</a></li>
            <li><a href="#cong-trinh" class="hover:text-amber-400 transition">• Thi công dự án khách sạn</a></li>
          </ul>
        </div>

        <!-- Cột 3: Hỗ trợ khách hàng -->
        <div class="lg:col-span-3 space-y-2.5">
          <h3 class="text-xs sm:text-sm font-extrabold uppercase text-white tracking-wider border-b border-white/15 pb-2">
            Chính sách &amp; Hỗ trợ
          </h3>
          <ul class="space-y-2 text-xs">
            <li><a href="#bang-bao-gia" class="hover:text-amber-400 transition">• Bảng báo giá nhôm kính 2026</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-400 transition">• Quy trình khảo sát &amp; lắp đặt</a></li>
            <li><a href="#gioi-thieu" class="hover:text-amber-400 transition">• Chính sách bảo hành 5–10 năm</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-400 transition">• Tư vấn kỹ thuật &amp; phong thủy cửa</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400">
        <p>© 2026 Bản quyền thuộc về <strong class="text-white">Nhôm Kính Xuân Định</strong> – Công Ty TNHH MTV TM - DV - SX - XD Xuân Trường.</p>
        <p>Thiết kế tối ưu Flatsome UX Builder • Đà Nẵng</p>
      </div>
    </div>
  </footer>

  <!-- ========================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MT & ĐT)
       ======================================================================== -->
  <div class="fixed bottom-4 right-3 sm:right-5 z-40 flex flex-col items-end gap-2.5">
    
    <!-- Nút Facebook Fanpage -->
    <a href="https://www.facebook.com/nhomkinhxuandinh" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook Nhôm Kính Xuân Định" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1464D0] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2 transition-transform hover:scale-105">
      <svg class="w-5 h-5 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22 12c0-5.52-4.48-10-10-10S2 6.48 2 12c0 4.84 3.44 8.87 8 9.8V15H8v-3h2V9.5C10 7.57 11.57 6 13.5 6H16v3h-2c-.55 0-1 .45-1 1v2h3v3h-3v6.95c5.05-.5 9-4.76 9-9.95z"/></svg>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Fanpage</span>
    </a>

    <!-- Nút Chat Zalo -->
    <a href="https://zalo.me/0934123693" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0934.123.693" class="relative pulse-ring flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2 transition-transform hover:scale-105">
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Hotline Gọi Ngay -->
    <a href="tel:0934123693" aria-label="Gọi Hotline 0934.123.693" class="relative pulse-ring flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition-transform hover:scale-105">
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span class="text-xs font-extrabold whitespace-nowrap">0934.123.693</span>
    </a>

  </div>

  <!-- ========================================================================
       MODAL XEM NHANH SẢN PHẨM & BÀI VIẾT + DRAWER DỰ TOÁN
       ======================================================================== -->
  <div id="quickViewModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-4">
    <div onclick="closeQuickView()" class="absolute inset-0 bg-slate-900/65 backdrop-blur-xs"></div>
    <div id="quickViewContent" class="relative bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200 p-4 sm:p-6 z-10">
      <!-- Render bằng JS -->
    </div>
  </div>

  <div id="quoteDrawer" class="fixed inset-0 z-50 hidden">
    <div onclick="closeQuoteDrawer()" class="absolute inset-0 bg-slate-900/60"></div>
    <div class="relative ml-auto w-[90%] max-w-md h-full bg-white shadow-2xl flex flex-col">
      <div class="p-4 bg-brand-primary text-white flex items-center justify-between">
        <h3 class="font-bold text-sm uppercase">Danh sách hạng mục dự toán</h3>
        <button onclick="closeQuoteDrawer()" class="p-1 rounded bg-white/10 hover:bg-white/20">✕</button>
      </div>
      <div id="quoteDrawerItems" class="flex-1 p-4 overflow-y-auto space-y-3 text-xs"></div>
      <div class="p-4 border-t border-slate-200 bg-slate-50 space-y-2">
        <a href="#form-bao-gia" onclick="closeQuoteDrawer()" class="block w-full text-center bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs py-2.5 rounded-lg">
          GỬI YÊU CẦU BÁO GIÁ CHI TIẾT
        </a>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       JAVASCRIPT ĐIỀU KHIỂN SLIDER, DỮ LIỆU SẢN PHẨM, BÀI VIẾT & TƯƠNG TÁC
       ======================================================================== -->
  <script>
    // 1. Hàm xử lý dự phòng ảnh Google Drive nếu link chính bị giới hạn băng thông
    function handleDriveImgError(imgEl) {
      const driveId = imgEl.getAttribute('data-drive-id');
      const retryCount = parseInt(imgEl.getAttribute('data-retry') || '0', 10);
      if (driveId && retryCount === 0) {
        imgEl.setAttribute('data-retry', '1');
        imgEl.src = `https://drive.google.com/thumbnail?id=${driveId}&sz=w1000`;
      } else {
        const altText = encodeURIComponent(imgEl.alt || 'Nhom Kinh Xuan Dinh');
        imgEl.src = `https://placehold.co/800x600/0B3B70/FFFFFF?text=${altText}`;
      }
    }

    // 2. Dữ liệu sản phẩm đầy đủ theo danh mục web mẫu & ảnh Google Drive thực tế
    const PRODUCTS_DATA = [
      {
        id: 'xf-1c',
        name: 'Cửa đi quay mở 1 cánh nhôm Xingfa',
        category: 'Cửa nhôm Xingfa',
        subTag: '1 cánh',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: 2100000,
        price: 1785000,
        discount: 15,
        unit: '₫/m²',
        specs: 'Nhôm Xingfa nhập khẩu hệ 55 dày 2.0mm, kính cường lực 8mm, phụ kiện Kinlong đồng bộ chính hãng.'
      },
      {
        id: 'xf-2c',
        name: 'Cửa đi quay mở 2 cánh nhôm Xingfa',
        category: 'Cửa nhôm Xingfa',
        subTag: '2 cánh',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: 2150000,
        price: 1820000,
        discount: 15,
        unit: '₫/m²',
        specs: 'Nhôm Xingfa tem đỏ Quảng Đông hệ 55 dày 2.0mm, gioăng kép EPDM kín khít tuyệt đối, chống ồn & chống thấm nước.'
      },
      {
        id: 'xf-3c',
        name: 'Cửa đi quay mở 3 cánh nhôm Xingfa',
        category: 'Cửa nhôm Xingfa',
        subTag: '3 cánh',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: 2200000,
        price: 1850000,
        discount: 16,
        unit: '₫/m²',
        specs: 'Thiết kế 3 cánh linh hoạt tối ưu diện tích mở cho mặt tiền nhà phố, ban công rộng, phụ kiện Kinlong cao cấp.'
      },
      {
        id: 'xf-4c',
        name: 'Cửa đi quay mở 4 cánh nhôm Xingfa',
        category: 'Cửa nhôm Xingfa',
        subTag: '4 cánh',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: 2250000,
        price: 1890000,
        discount: 16,
        unit: '₫/m²',
        specs: 'Cửa đi mặt tiền 4 cánh nhôm Xingfa dày 2.0mm sang trọng, chịu lực gió bão cấp 12 tại Đà Nẵng.'
      },
      {
        id: 'xf-xt-5c',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt (5 cánh)',
        category: 'Cửa nhôm Xingfa',
        subTag: '5 cánh',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: 2450000,
        price: 1990000,
        discount: 19,
        unit: '₫/m²',
        specs: 'Hệ nhôm Xingfa 63 xếp trượt gấp gọn toàn bộ cánh sang 1 hoặc 2 bên, mở rộng 100% không gian.'
      },
      {
        id: 'xf-mh-2c',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: 'Cửa nhôm Xingfa',
        subTag: '2 cánh',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: 1950000,
        price: 1650000,
        discount: 15,
        unit: '₫/m²',
        specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh định vị góc mở 45 độ chống gió va đập, lấy thoáng ngay cả khi trời mưa.'
      },
      {
        id: 'ck-cl-1',
        name: 'Cửa kính cường lực bản lề sàn 2 cánh 10mm',
        category: 'Cửa kính cường lực',
        subTag: 'Kính cường lực',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        oldPrice: 920000,
        price: 750000,
        discount: 18,
        unit: '₫/m²',
        specs: 'Kính cường lực Việt Nhật 10mm tôi nhiệt chuẩn, bản lề thủy lực VVP Thái Lan vận hành êm ái.'
      },
      {
        id: 'cn-lt-1',
        name: 'Cửa nhựa lõi thép uPVC mở quay 2 cánh',
        category: 'Cửa nhựa lõi thép',
        subTag: 'uPVC',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        oldPrice: 1480000,
        price: 1250000,
        discount: 16,
        unit: '₫/m²',
        specs: 'Thanh nhựa uPVC Sparlee có lõi thép gia cường chống ăn mòn, cách âm cách nhiệt vượt trội.'
      },
      {
        id: 'ct-td-1',
        name: 'Cửa kính trượt tự động 2 cánh cảm biến',
        category: 'Cửa kính tự động',
        subTag: 'Tự động',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        oldPrice: 28500000,
        price: 23900000,
        discount: 16,
        unit: '₫/bộ',
        specs: 'Motor tự động nhập khẩu Hàn Quốc/Nhật Bản, mắt thần radar nhận diện chuyển động siêu nhạy.'
      },
      {
        id: 'ct-k-1',
        name: 'Cầu thang kính cường lực 12mm tay vịn gỗ',
        category: 'Cầu thang kính',
        subTag: 'Cầu thang',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        oldPrice: 1450000,
        price: 1220000,
        discount: 16,
        unit: '₫/md',
        specs: 'Kính cường lực 12ly kết hợp trụ inox 304 và tay vịn gỗ căm xe/sồi tự nhiên sang trọng.'
      },
      {
        id: 'kob-1',
        name: 'Kính màu ốp bếp cường lực 8mm cao cấp',
        category: 'Kính ốp bếp',
        subTag: 'Ốp bếp',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        oldPrice: 880000,
        price: 720000,
        discount: 18,
        unit: '₫/md',
        specs: 'Kính cường lực 8mm phun sơn chịu nhiệt bóng đẹp, chống bám dầu mỡ, dễ dàng lau chùi.'
      },
      {
        id: 'ptk-1',
        name: 'Phòng tắm kính cường lực 10mm góc 90 độ',
        category: 'Phòng tắm kính',
        subTag: 'Phòng tắm',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        oldPrice: 1380000,
        price: 1150000,
        discount: 17,
        unit: '₫/m²',
        specs: 'Vách tắm kính cường lực 10mm, bộ phụ kiện bản lề & thanh giằng Inox 304 chống gỉ sét.'
      }
    ];

    // 3. Dữ liệu bài viết tin tức trang chủ
    const ARTICLES_DATA = [
      {
        id: 'art-1',
        category: 'Kinh nghiệm chọn cửa',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?',
        date: '18/11/2026',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        excerpt: 'Khí hậu miền Trung nắng gắt, mưa bão nhiều và hơi muối biển cao đòi hỏi hệ cửa có độ bền oxy hóa vượt trội...',
        content: 'Tại Đà Nẵng, đặc biệt là khu vực Liên Chiểu, Sơn Trà, Ngũ Hành Sơn gần biển, hơi muối và gió bão dễ làm xuống cấp các loại cửa sắt hoặc nhôm mỏng thông thường. Cửa nhôm Xingfa nhập khẩu tem đỏ dày 1.4mm–2.0mm được sơn tĩnh điện ngoài trời cao cấp kết hợp hệ gioăng EPDM và kính cường lực giúp chống ăn mòn muối biển, cách âm cách nhiệt và chịu áp lực gió bão cực tốt.'
      },
      {
        id: 'art-2',
        category: 'Báo giá & Kỹ thuật',
        title: 'Cách phân biệt nhôm Xingfa nhập khẩu tem đỏ chính hãng và nhôm nhái',
        date: '12/11/2026',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        excerpt: 'Hướng dẫn kiểm tra mã QR tem đỏ Quảng Đông, độ dày thanh profile và ánh kim mặt cắt bên trong thanh nhôm...',
        content: 'Để nhận biết nhôm Xingfa chính hãng tại xưởng Nhôm Kính Xuân Định: 1) Kiểm tra tem đỏ sắc nét có mã QR truy xuất nguồn gốc; 2) Bề mặt bên trong thanh nhôm có ánh đồng đặc trưng do mạ Crom chống oxy hóa; 3) Độ dày tiêu chuẩn 1.4mm cho cửa sổ và 2.0mm cho cửa đi, kết hợp phụ kiện Kinlong đồng bộ.'
      },
      {
        id: 'art-3',
        category: 'Kinh nghiệm chọn cửa',
        title: 'So sánh cửa nhôm Xingfa và cửa nhựa lõi thép uPVC: Nên chọn loại nào?',
        date: '05/11/2026',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        excerpt: 'Phân tích chi tiết ưu nhược điểm về độ bền kết cấu, khả năng cách âm và chi phí đầu tư giữa hai dòng cửa phổ biến...',
        content: 'Cửa nhựa lõi thép uPVC có ưu điểm giá thành tiết kiệm, cách âm phòng ngủ rất tốt. Trong khi đó, cửa nhôm Xingfa có độ cứng vững vượt trội, chịu nắng mưa trực tiếp ở mặt tiền và ban công không bị ngả màu hay cong vênh, tuổi thọ lên đến trên 25 năm.'
      },
      {
        id: 'art-4',
        category: 'Phong thủy & Thẩm mỹ',
        title: 'Bí quyết chọn màu kính ốp bếp cường lực giúp gian bếp sáng rộng & hợp phong thủy',
        date: '28/10/2026',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        excerpt: 'Gợi ý các tông màu kính ốp bếp 8mm như xanh ngọc, vàng chanh, trắng sữa giúp không gian bếp luôn sạch sẽ...',
        content: 'Kính màu ốp bếp cường lực 8mm không có mạch vữa như gạch men nên tuyệt đối không bám bẩn hay ẩm mốc. Gia chủ mệnh Mộc/Hỏa có thể chọn màu xanh non, xanh ngọc; mệnh Kim/Thủy hợp màu trắng sữa, xanh dương nhạt hoặc vàng kem sang trọng.'
      }
    ];

    // 4. Điều khiển 2 Banner tự trượt kích thước bằng nhau
    let currentSlide = 0;
    const totalSlides = 2;
    let bannerInterval = null;

    function updateBannerUI() {
      const track = document.getElementById('heroSliderTrack');
      const dot0 = document.getElementById('bannerDot0');
      const dot1 = document.getElementById('bannerDot1');
      if (!track) return;
      track.style.transform = `translateX(-${currentSlide * 50}%)`;
      if (currentSlide === 0) {
        dot0.className = 'w-6 h-2 rounded-full bg-brand-accent transition-all';
        dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all';
      } else {
        dot1.className = 'w-6 h-2 rounded-full bg-brand-accent transition-all';
        dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all';
      }
    }

    function nextBannerSlide() {
      currentSlide = (currentSlide + 1) % totalSlides;
      updateBannerUI();
      resetBannerAutoplay();
    }

    function prevBannerSlide() {
      currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
      updateBannerUI();
      resetBannerAutoplay();
    }

    function goToBannerSlide(idx) {
      currentSlide = idx;
      updateBannerUI();
      resetBannerAutoplay();
    }

    function resetBannerAutoplay() {
      if (bannerInterval) clearInterval(bannerInterval);
      bannerInterval = setInterval(() => {
        currentSlide = (currentSlide + 1) % totalSlides;
        updateBannerUI();
      }, 5000);
    }

    // 5. Render danh sách nút lọc sản phẩm & Lưới sản phẩm 2 cột trên mobile
    let activeProductCategory = 'Tất cả';
    let quoteBasket = [];

    function formatVND(num) {
      return num.toLocaleString('vi-VN');
    }

    function renderProductFilterTabs() {
      const categories = [
        'Tất cả',
        'Cửa nhôm Xingfa',
        'Cửa kính cường lực',
        'Cửa nhựa lõi thép',
        'Cửa kính tự động',
        'Cầu thang kính',
        'Kính ốp bếp',
        'Phòng tắm kính'
      ];
      const container = document.getElementById('productFilterTabs');
      container.innerHTML = categories.map(cat => {
        const isActive = cat === activeProductCategory;
        return `
          <button
            type="button"
            onclick="filterProductsByCategory('${cat}')"
            class="px-3 py-1.5 rounded-full text-xs whitespace-nowrap transition ${
              isActive
                ? 'bg-brand-primary text-white font-bold shadow-2xs'
                : 'bg-white border border-slate-200 text-slate-700 font-semibold hover:border-brand-primary hover:text-brand-primary'
            }"
          >
            ${cat}
          </button>
        `;
      }).join('');
    }

    function renderProducts(list) {
      const grid = document.getElementById('productsGrid');
      if (!list.length) {
        grid.innerHTML = `
          <div class="col-span-full bg-white rounded-xl p-8 text-center border border-slate-200">
            <p class="text-sm font-semibold text-slate-600">Không tìm thấy sản phẩm phù hợp. Vui lòng thử từ khóa khác hoặc chọn "Tất cả".</p>
            <button onclick="filterProductsByCategory('Tất cả')" class="mt-3 px-4 py-2 bg-brand-primary text-white text-xs font-bold rounded-lg">Xem tất cả sản phẩm</button>
          </div>
        `;
        return;
      }

      grid.innerHTML = list.map(item => `
        <article class="group bg-white rounded-xl border border-slate-200/90 overflow-hidden shadow-2xs hover:shadow-md hover:border-brand-primary/60 transition flex flex-col">
          <!-- Khung ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
          <div class="relative aspect-square overflow-hidden bg-slate-100">
            <span class="absolute top-2 left-2 z-10 bg-red-600 text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded-md shadow-xs">
              -${item.discount}%
            </span>
            <img
              src="https://lh3.googleusercontent.com/d/${item.driveId}=w800"
              data-drive-id="${item.driveId}"
              onerror="handleDriveImgError(this)"
              alt="${item.name}"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
            />
            <button
              type="button"
              onclick="openProductQuickView('${item.id}')"
              class="absolute inset-x-2 bottom-2 bg-brand-primary/90 hover:bg-brand-accent text-white text-[11px] font-bold py-1.5 rounded-lg opacity-0 group-hover:opacity-100 transition text-center hidden sm:block"
            >
              Xem nhanh chi tiết
            </button>
          </div>

          <!-- Nội dung tên sản phẩm & Giá (không tràn chữ trên điện thoại) -->
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <p class="text-[10px] sm:text-[11px] font-semibold text-slate-400 uppercase truncate">${item.category}</p>
              <h3
                onclick="openProductQuickView('${item.id}')"
                class="cursor-pointer text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug line-clamp-2 min-h-[2.6em] mt-0.5 break-words"
              >
                ${item.name}
              </h3>
            </div>

            <div class="mt-2 pt-2 border-t border-slate-100">
              <div class="flex flex-wrap items-baseline gap-x-1.5 gap-y-0.5">
                <span class="text-xs sm:text-[15px] font-extrabold text-red-600">
                  ${formatVND(item.price)} <span class="text-[10px] sm:text-xs font-semibold">${item.unit}</span>
                </span>
                <span class="text-[10px] sm:text-xs text-slate-400 line-through">
                  ${formatVND(item.oldPrice)}₫
                </span>
              </div>

              <div class="mt-2 flex items-center gap-1.5">
                <button
                  type="button"
                  onclick="addToQuoteBasket('${item.id}')"
                  class="flex-1 bg-brand-light hover:bg-brand-primary text-brand-primary hover:text-white font-bold text-[11px] sm:text-xs py-1.5 px-2 rounded-lg transition text-center truncate"
                >
                  + Dự toán
                </button>
                <button
                  type="button"
                  onclick="openProductQuickView('${item.id}')"
                  class="bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold text-[11px] sm:text-xs py-1.5 px-2.5 rounded-lg transition shrink-0"
                >
                  Chi tiết
                </button>
              </div>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterProductsByCategory(cat) {
      activeProductCategory = cat;
      renderProductFilterTabs();
      if (cat === 'Tất cả') {
        renderProducts(PRODUCTS_DATA);
      } else {
        renderProducts(PRODUCTS_DATA.filter(p => p.category === cat));
      }
    }

    function filterProductsBySub(subKeyword) {
      activeProductCategory = 'Cửa nhôm Xingfa';
      renderProductFilterTabs();
      const filtered = PRODUCTS_DATA.filter(
        p => p.category === 'Cửa nhôm Xingfa' && (p.name.toLowerCase().includes(subKeyword.toLowerCase()) || p.subTag.toLowerCase().includes(subKeyword.toLowerCase()))
      );
      renderProducts(filtered.length ? filtered : PRODUCTS_DATA.filter(p => p.category === 'Cửa nhôm Xingfa'));
    }

    function handleSearchSubmit(e) {
      e.preventDefault();
      const kw = document.getElementById('desktopSearchInput').value.trim().toLowerCase();
      performSearch(kw);
    }

    function handleMobileSearch(e) {
      e.preventDefault();
      const kw = document.getElementById('mobileSearchInput').value.trim().toLowerCase();
      closeMobileMenu();
      performSearch(kw);
    }

    function performSearch(kw) {
      const targetSec = document.getElementById('san-pham');
      if (targetSec) targetSec.scrollIntoView({ behavior: 'smooth' });
      if (!kw) {
        filterProductsByCategory('Tất cả');
        return;
      }
      activeProductCategory = 'Tất cả';
      renderProductFilterTabs();
      const results = PRODUCTS_DATA.filter(
        p => p.name.toLowerCase().includes(kw) || p.category.toLowerCase().includes(kw) || p.specs.toLowerCase().includes(kw)
      );
      renderProducts(results);
    }

    // 6. Xem nhanh sản phẩm Modal
    function openProductQuickView(id) {
      const item = PRODUCTS_DATA.find(p => p.id === id);
      if (!item) return;
      const modal = document.getElementById('quickViewModal');
      const content = document.getElementById('quickViewContent');
      content.innerHTML = `
        <div class="flex items-start justify-between gap-3 border-b border-slate-100 pb-3 mb-4">
          <div>
            <span class="text-[11px] font-bold uppercase text-brand-accent">${item.category}</span>
            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary">${item.name}</h3>
          </div>
          <button onclick="closeQuickView()" class="p-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-600 font-bold">✕</button>
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 items-center">
          <div class="relative rounded-xl overflow-hidden border border-slate-200 aspect-square bg-slate-100">
            <span class="absolute top-2 left-2 bg-red-600 text-white text-xs font-extrabold px-2 py-0.5 rounded-md">-${item.discount}%</span>
            <img src="https://lh3.googleusercontent.com/d/${item.driveId}=w800" data-drive-id="${item.driveId}" onerror="handleDriveImgError(this)" alt="${item.name}" class="w-full h-full object-cover" />
          </div>
          <div class="space-y-3">
            <div class="bg-slate-50 p-3 rounded-xl border border-slate-200/80">
              <p class="text-xs text-slate-500">Đơn giá ưu đãi tại xưởng:</p>
              <div class="flex items-baseline gap-2 mt-0.5">
                <span class="text-xl font-extrabold text-red-600">${formatVND(item.price)} ${item.unit}</span>
                <span class="text-xs text-slate-400 line-through">${formatVND(item.oldPrice)}₫</span>
              </div>
            </div>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${item.specs}</p>
            <ul class="text-xs text-slate-600 space-y-1">
              <li>✓ Khảo sát, đo đạc miễn phí tại Đà Nẵng</li>
              <li>✓ Bảo hành phụ kiện &amp; kết cấu 5–10 năm</li>
              <li>✓ Thi công bởi Công Ty TNHH MTV XD Xuân Trường</li>
            </ul>
            <div class="pt-2 flex flex-col sm:flex-row gap-2">
              <button onclick="addToQuoteBasket('${item.id}'); closeQuickView();" class="flex-1 bg-brand-primary hover:bg-brand-medium text-white font-bold text-xs py-2.5 px-3 rounded-lg transition">
                Thêm vào bảng dự toán
              </button>
              <a href="https://zalo.me/0934123693" target="_blank" rel="noopener noreferrer" class="flex-1 bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs py-2.5 px-3 rounded-lg transition text-center">
                Tư vấn qua Zalo
              </a>
            </div>
          </div>
        </div>
      `;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeQuickView() {
      const modal = document.getElementById('quickViewModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    // 7. Giỏ dự toán báo giá
    function addToQuoteBasket(id) {
      const item = PRODUCTS_DATA.find(p => p.id === id);
      if (!item) return;
      if (!quoteBasket.some(x => x.id === id)) {
        quoteBasket.push(item);
      }
      document.getElementById('quoteCountBadge').textContent = quoteBasket.length;
      openQuoteDrawer();
    }

    function removeFromQuoteBasket(id) {
      quoteBasket = quoteBasket.filter(x => x.id !== id);
      document.getElementById('quoteCountBadge').textContent = quoteBasket.length;
      renderQuoteDrawer();
    }

    function renderQuoteDrawer() {
      const box = document.getElementById('quoteDrawerItems');
      if (!quoteBasket.length) {
        box.innerHTML = `<p class="text-slate-500 text-center py-8">Chưa có hạng mục nào trong bảng dự toán. Hãy chọn "+ Dự toán" trên sản phẩm bạn quan tâm.</p>`;
        return;
      }
      box.innerHTML = quoteBasket.map(item => `
        <div class="flex items-center justify-between gap-2 p-2.5 rounded-xl border border-slate-200 bg-slate-50">
          <div class="min-w-0">
            <p class="font-bold text-slate-800 truncate">${item.name}</p>
            <p class="text-red-600 font-bold mt-0.5">${formatVND(item.price)} ${item.unit}</p>
          </div>
          <button onclick="removeFromQuoteBasket('${item.id}')" class="text-slate-400 hover:text-red-600 font-bold px-2">✕</button>
        </div>
      `).join('');
    }

    function openQuoteDrawer() {
      renderQuoteDrawer();
      document.getElementById('quoteDrawer').classList.remove('hidden');
    }

    function closeQuoteDrawer() {
      document.getElementById('quoteDrawer').classList.add('hidden');
    }

    // 8. Render danh mục bài viết & Modal đọc bài viết
    function renderArticles(cat = 'Tất cả') {
      document.querySelectorAll('.news-tab-btn').forEach(btn => {
        const isCurrent = btn.getAttribute('data-news-cat') === cat;
        btn.className = isCurrent
          ? 'news-tab-btn px-3 py-1 rounded-full text-xs font-bold bg-brand-primary text-white whitespace-nowrap transition'
          : 'news-tab-btn px-3 py-1 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light whitespace-nowrap transition';
      });

      const list = cat === 'Tất cả' ? ARTICLES_DATA : ARTICLES_DATA.filter(a => a.category === cat);
      const grid = document.getElementById('articlesGrid');
      grid.innerHTML = list.map(art => `
        <article class="group bg-slate-50 rounded-xl border border-slate-200/90 overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="aspect-[16/10] overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/${art.driveId}=w700" data-drive-id="${art.driveId}" onerror="handleDriveImgError(this)" alt="${art.title}" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" />
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="flex items-center justify-between text-[10px] font-semibold text-slate-500 mb-1">
                <span class="text-brand-accent uppercase">${art.category}</span>
                <span>${art.date}</span>
              </div>
              <h3 onclick="openArticleModal('${art.id}')" class="cursor-pointer text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary line-clamp-2 leading-snug">
                ${art.title}
              </h3>
              <p class="text-[11px] sm:text-xs text-slate-600 line-clamp-2 mt-1.5">${art.excerpt}</p>
            </div>
            <button type="button" onclick="openArticleModal('${art.id}')" class="mt-3 inline-flex items-center text-xs font-bold text-brand-primary hover:text-brand-accent transition">
              Xem chi tiết →
            </button>
          </div>
        </article>
      `).join('');
    }

    function filterArticles(cat) {
      renderArticles(cat);
    }

    function openArticleModal(id) {
      const art = ARTICLES_DATA.find(a => a.id === id);
      if (!art) return;
      const modal = document.getElementById('quickViewModal');
      const content = document.getElementById('quickViewContent');
      content.innerHTML = `
        <div class="flex items-start justify-between gap-3 border-b border-slate-100 pb-3 mb-4">
          <div>
            <span class="text-[11px] font-bold uppercase text-brand-accent">${art.category} • ${art.date}</span>
            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary mt-0.5">${art.title}</h3>
          </div>
          <button onclick="closeQuickView()" class="p-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-600 font-bold">✕</button>
        </div>
        <div class="space-y-3">
          <div class="aspect-[16/9] rounded-xl overflow-hidden bg-slate-100">
            <img src="https://lh3.googleusercontent.com/d/${art.driveId}=w900" data-drive-id="${art.driveId}" onerror="handleDriveImgError(this)" alt="${art.title}" class="w-full h-full object-cover" />
          </div>
          <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">${art.content}</p>
          <div class="p-3 rounded-xl bg-brand-light text-xs text-brand-primary font-medium">
            Liên hệ tư vấn &amp; báo giá trực tiếp: <strong>Nhôm Kính Xuân Định</strong> – 17 Bàu Mạc 16, P. Liên Chiểu, Đà Nẵng • Hotline/Zalo: <strong>0934.123.693</strong>.
          </div>
        </div>
      `;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    // 9. Xử lý gửi Form báo giá trang chủ
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('cusName').value.trim();
      const phone = document.getElementById('cusPhone').value.trim();
      const cat = document.getElementById('cusCategory').value;
      const feedback = document.getElementById('quoteFormFeedback');
      feedback.innerHTML = `
        Cảm ơn Quý khách <strong>${name}</strong>! Yêu cầu báo giá hạng mục <strong>${cat}</strong> (SĐT: <strong>${phone}</strong>) đã được gửi đến bộ phận kỹ thuật <strong>Nhôm Kính Xuân Định</strong>. Chúng tôi sẽ liên hệ lại ngay!
      `;
      feedback.classList.remove('hidden');
      e.target.reset();
    }

    // 10. Điều khiển Mobile Drawer
    document.getElementById('mobileMenuBtn').addEventListener('click', () => {
      document.getElementById('mobileDrawer').classList.remove('hidden');
    });

    function closeMobileMenu() {
      document.getElementById('mobileDrawer').classList.add('hidden');
    }

    function toggleSubMenu(id) {
      const el = document.getElementById(id);
      if (el) el.classList.toggle('hidden');
    }

    // Khởi tạo khi trang tải xong
    window.addEventListener('DOMContentLoaded', () => {
      renderProductFilterTabs();
      renderProducts(PRODUCTS_DATA);
      renderArticles('Tất cả');
      resetBannerAutoplay();
    });
  </script>
</body>
</html>
