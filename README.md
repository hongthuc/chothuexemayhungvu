<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Cho Thuê Xe Máy Hùng Vũ Đà Nẵng - Giao Xe Tận Nơi | chothuexemayhungvu.com</title>
  <meta name="description" content="Dịch vụ cho thuê xe máy Hùng Vũ Đà Nẵng uy tín, xe đời mới, giá chỉ từ 80.000đ/ngày. Giao xe miễn phí tận nơi Sân bay, Nhà ga, Khách sạn. Địa chỉ: 28 An Cư 5, An Hải, Đà Nẵng. Hotline: 0787 546 220.">
  
  <!-- Open Graph Thumbnail là Logo trang web khi chia sẻ link -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://chothuexemayhungvu.com/">
  <meta property="og:title" content="Cho Thuê Xe Máy Hùng Vũ Đà Nẵng - Giao Xe Tận Nơi Giá Rẻ">
  <meta property="og:description" content="Cho thuê xe máy Đà Nẵng Hùng Vũ - Xe đời mới, thủ tục nhanh gọn, giao xe tận nơi 10 phút. Địa chỉ: 28 An Cư 5, An Hải, Đà Nẵng. SĐT: 0787 546 220.">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1RQIaJYVpiut3nWHEyTFqi0v3InKOvirI=w800">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1RQIaJYVpiut3nWHEyTFqi0v3InKOvirI=w800">
  <link rel="icon" href="https://lh3.googleusercontent.com/d/1RQIaJYVpiut3nWHEyTFqi0v3InKOvirI=w200">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <!-- Google Fonts: Inter / Roboto chuẩn Flatsome -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <style>
    /* Reset chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Màu chủ đạo theo tông màu Logo Hùng Vũ & chuẩn Flatsome */
    :root {
      --primary-color: #0b4f8a;
      --primary-dark: #073863;
      --accent-color: #e53935;
      --flatsome-sale: #d26e4b;
    }

    /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng chữ bên trong từng danh mục */
    .nav-category-item {
      white-space: nowrap;
      display: inline-flex;
      align-items: center;
      line-height: 1.2;
      transition: all 0.2s ease;
    }

    /* Tiêu đề Section kiểu Flatsome (Section Title) */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 1.25rem;
      width: 100%;
    }
    .flatsome-section-title b {
      display: block;
      flex: 1;
      height: 2px;
      background-color: #cbd5e1;
    }
    .flatsome-section-title span {
      margin: 0 14px;
      text-align: center;
      text-transform: uppercase;
      font-weight: 800;
      color: var(--primary-color);
      letter-spacing: 0.02em;
    }

    /* Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài và không bị cắt thiếu chữ */
    .product-title-full {
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.35;
    }

    /* Huy hiệu % giảm giá chuẩn Flatsome góc trên bên trái */
    .flatsome-onsale {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #e53935;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      width: 38px;
      height: 38px;
      border-radius: 9999px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.22);
      pointer-events: none;
    }
    @media (min-width: 768px) {
      .flatsome-onsale {
        width: 42px;
        height: 42px;
        font-size: 12px;
        top: 10px;
        left: 10px;
      }
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
    @keyframes pulse-ring {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(229, 57, 53, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(229, 57, 53, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(229, 57, 53, 0); }
    }
    .pulse-btn {
      animation: pulse-ring 2s infinite;
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

  <!-- ================= TOP BAR FLATSOME (Đơn giản, không có thanh UX Builder) ================= -->
  <div class="bg-[#073863] text-white text-xs py-1.5 border-b border-white/10">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-amber-400"></i>
          <span>Đ/c: 28 An Cư 5, An Hải, Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-globe text-sky-300"></i>
          <span>chothuexemayhungvu.com</span>
        </span>
      </div>
      <div class="flex items-center gap-3 ml-auto">
        <span class="inline-flex items-center gap-1 text-emerald-300 font-medium">
          <i class="fa-solid fa-clock"></i> Mở cửa 24/7 - Giao xe tận nơi 10 phút
        </span>
        <a href="https://www.facebook.com/ChoThueXeMayHungVu/" target="_blank" rel="noopener" class="hover:text-amber-300 transition" title="Fanpage Cho thuê xe máy Hùng Vũ">
          <i class="fa-brands fa-facebook-f"></i>
        </a>
        <a href="https://share.google/vHa7VIUGFPAlj68Yb" target="_blank" rel="noopener" class="hover:text-amber-300 transition" title="Google Maps">
          <i class="fa-solid fa-map-location-dot"></i>
        </a>
      </div>
    </div>
  </div>

  <!-- ================= HEADER FLATSOME (Logo gọn nhỏ, KHÔNG để nút gọi ngay tránh tràn viền) ================= -->
  <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
    <div class="flatsome-container py-2">
      <div class="flex items-center justify-between gap-2">
        
        <!-- Logo chỉnh gọn nhỏ lại + Tên thương hiệu -->
        <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0 shrink-0">
          <img 
            src="https://lh3.googleusercontent.com/d/1RQIaJYVpiut3nWHEyTFqi0v3InKOvirI=w300" 
            onerror="if(this.src.indexOf('drive.google.com/thumbnail')===-1){this.src='https://drive.google.com/thumbnail?id=1RQIaJYVpiut3nWHEyTFqi0v3InKOvirI&sz=w300';}else{this.src='https://placehold.co/120x120/0b4f8a/ffffff?text=HUNG+VU';}"
            alt="Logo Cho Thuê Xe Máy Hùng Vũ" 
            class="w-9 h-9 sm:w-11 sm:h-11 object-contain rounded-md border border-slate-200 bg-white p-0.5 shrink-0"
          >
          <div class="leading-tight">
            <span class="block font-extrabold text-sm sm:text-base md:text-lg text-[#0b4f8a] tracking-tight">
              THUÊ XE MÁY HÙNG VŨ
            </span>
            <span class="block text-[11px] text-slate-500 font-medium">
              chothuexemayhungvu.com • 0787 546 220
            </span>
          </div>
        </a>

        <!-- Thanh tìm kiếm nhanh trên máy tính (Chuẩn Flatsome Header) -->
        <div class="hidden xl:flex items-center flex-1 max-w-xs mx-3">
          <div class="relative w-full">
            <input 
              id="searchBikeInput" 
              type="text" 
              placeholder="Tìm xe: Air Blade, Vision, Sirius..." 
              class="w-full text-xs border border-slate-300 rounded-full pl-3.5 pr-8 py-1.5 focus:outline-none focus:border-[#0b4f8a]"
            >
            <button type="button" onclick="filterBySearch()" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-slate-400 hover:text-[#0b4f8a]">
              <i class="fa-solid fa-magnifying-glass text-xs"></i>
            </button>
          </div>
        </div>

        <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
        <button 
          type="button" 
          onclick="toggleMobileMenu()" 
          class="lg:hidden inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded-md bg-slate-100 hover:bg-slate-200 text-[#0b4f8a] text-xs font-bold border border-slate-200 shrink-0"
          aria-label="Mở danh mục"
        >
          <i class="fa-solid fa-bars text-sm"></i>
          <span>DANH MỤC</span>
        </button>
      </div>

      <!-- THANH DANH MỤC TRÊN MÁY TÍNH: Chữ nhỏ gọn, nằm trên 1 hàng hoặc xuống hàng 2, tuyệt đối không xuống dòng chữ bên trong tên danh mục -->
      <nav class="hidden lg:flex flex-wrap items-center justify-center gap-x-1.5 gap-y-1 pt-2 mt-2 border-t border-slate-100">
        <a href="#trang-chu" class="nav-category-item text-[12px] font-bold px-2.5 py-1 rounded bg-[#0b4f8a] text-white">
          <i class="fa-solid fa-house mr-1 text-[10px]"></i>Trang Chủ
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('all')" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Thuê Xe Máy Đà Nẵng
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('tay-ga')" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Thuê Xe Tay Ga
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('xe-so')" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Thuê Xe Số
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('con-tay')" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Xe Côn Tay &amp; Cao Cấp
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('xe-50cc')" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Xe Máy 50cc
        </a>
        <a href="#giao-xe-tan-noi" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Giao Xe Sân Bay &amp; Nhà Ga
        </a>
        <a href="#bang-gia" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Bảng Giá Thuê Xe
        </a>
        <a href="#bao-gia-form" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Yêu Cầu Báo Giá
        </a>
        <a href="#bai-viet" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Kinh Nghiệm Thuê Xe
        </a>
        <a href="#doi-tac" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Đối Tác
        </a>
        <a href="#ban-do-fanpage" class="nav-category-item text-[12px] font-semibold px-2.5 py-1 rounded text-slate-700 hover:bg-[#0b4f8a] hover:text-white">
          Bản Đồ &amp; Liên Hệ
        </a>
      </nav>
    </div>

    <!-- MENU DANH MỤC TRÊN ĐIỆN THOẠI (Thiết kế gọn đẹp, chia lưới dễ bấm) -->
    <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 px-3 py-3 shadow-inner">
      <div class="mb-2.5">
        <div class="relative w-full">
          <input 
            id="mobileSearchInput" 
            type="text" 
            placeholder="Tìm tên xe: Vision, Air Blade, Sirius..." 
            class="w-full text-xs border border-slate-300 rounded-lg pl-3 pr-8 py-2 focus:outline-none focus:border-[#0b4f8a]"
          >
          <button type="button" onclick="filterByMobileSearch()" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-[#0b4f8a]">
            <i class="fa-solid fa-magnifying-glass text-xs"></i>
          </button>
        </div>
      </div>
      <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
        <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-[#0b4f8a] flex items-center gap-1.5">
          <i class="fa-solid fa-house text-[11px]"></i> Trang Chủ
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('all'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-motorcycle text-[11px] text-[#0b4f8a]"></i> Tất Cả Dòng Xe
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('tay-ga'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-bolt text-[11px] text-amber-500"></i> Thuê Xe Tay Ga
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('xe-so'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-gears text-[11px] text-emerald-600"></i> Thuê Xe Số
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('con-tay'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-gauge-high text-[11px] text-red-500"></i> Xe Côn Tay &amp; PKL
        </a>
        <a href="#danh-muc-xe" onclick="selectCategory('xe-50cc'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-id-card-clip text-[11px] text-sky-600"></i> Xe Máy 50cc
        </a>
        <a href="#giao-xe-tan-noi" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-plane-arrival text-[11px] text-[#0b4f8a]"></i> Giao Xe Sân Bay
        </a>
        <a href="#bang-gia" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-table-list text-[11px] text-[#0b4f8a]"></i> Bảng Giá Thuê
        </a>
        <a href="#bao-gia-form" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-file-signature text-[11px] text-[#0b4f8a]"></i> Nhận Báo Giá
        </a>
        <a href="#bai-viet" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-newspaper text-[11px] text-[#0b4f8a]"></i> Kinh Nghiệm
        </a>
        <a href="#doi-tac" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-handshake text-[11px] text-[#0b4f8a]"></i> Đối Tác
        </a>
        <a href="#ban-do-fanpage" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
          <i class="fa-solid fa-map-pin text-[11px] text-red-600"></i> Bản Đồ &amp; Liên Hệ
        </a>
      </div>
    </div>
  </header>

  <!-- ================= 2 BANNERS TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ================= -->
  <!-- Thiết kế riêng ảnh Banner Máy Tính (1200x400) và ảnh Banner Điện Thoại (640x340) để tối ưu chữ nhỏ gọn nằm hết bên trong ảnh, không tràn viền -->
  <section id="trang-chu" class="py-3">
    <div class="flatsome-container">
      <div class="relative w-full overflow-hidden rounded-xl shadow-md bg-[#073863]">
        
        <!-- Vùng chứa 2 Slide có kích thước bằng nhau tuyệt đối -->
        <div id="bannerTrack" class="flex transition-transform duration-700 ease-in-out w-full">
          
          <!-- ================= SLIDE 1 ================= -->
          <div class="w-full shrink-0 relative">
            <!-- Ảnh Banner 1 phiên bản MÁY TÍNH (Tối ưu tỷ lệ ngang 1200x400) -->
            <svg class="hidden md:block w-full h-auto aspect-[3/1]" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg">
              <defs>
                <linearGradient id="pcGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#062c4d"/>
                  <stop offset="55%" stop-color="#0b4f8a"/>
                  <stop offset="100%" stop-color="#1268b3"/>
                </linearGradient>
              </defs>
              <rect width="1200" height="400" fill="url(#pcGrad1)"/>
              <!-- Họa tiết trang trí mềm mại bên trong -->
              <circle cx="1050" cy="200" r="240" fill="#ffffff" fill-opacity="0.06"/>
              <circle cx="960" cy="200" r="170" fill="#fbbf24" fill-opacity="0.12"/>
              <rect x="40" y="32" width="1120" height="336" rx="18" fill="none" stroke="#ffffff" stroke-opacity="0.2" stroke-width="2"/>
              
              <!-- Nội dung chữ bên trái: Chữ chỉnh nhỏ gọn nằm trọn trong khung an toàn -->
              <rect x="75" y="62" width="350" height="34" rx="17" fill="#f59e0b"/>
              <text x="250" y="84" text-anchor="middle" fill="#062c4d" font-family="Inter, sans-serif" font-size="14" font-weight="800">
                CHOTHUEXEMAYHUNGVU.COM • ĐÀ NẴNG
              </text>
              
              <text x="75" y="142" fill="#ffffff" font-family="Inter, sans-serif" font-size="34" font-weight="800">
                CHO THUÊ XE MÁY HÙNG VŨ ĐÀ NẴNG
              </text>
              <text x="75" y="182" fill="#fde047" font-family="Inter, sans-serif" font-size="22" font-weight="700">
                XE ĐỜI MỚI 2024 - 2026 • GIÁ CHỈ TỪ 80.000Đ / NGÀY
              </text>
              
              <text x="75" y="226" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="16" font-weight="500">
                ✓ Giao xe miễn phí tận nơi: Sân bay, Nhà ga, Khách sạn, Bãi biển Mỹ Khê trong 10 phút
              </text>
              <text x="75" y="256" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="16" font-weight="500">
                ✓ Trang bị sẵn 2 mũ bảo hiểm chuẩn, 2 áo mưa, hỗ trợ kỹ thuật 24/7 toàn thành phố
              </text>

              <!-- Khung thông tin địa chỉ & SĐT gọn trong banner -->
              <rect x="75" y="286" width="690" height="52" rx="10" fill="#041e36" fill-opacity="0.75" stroke="#38bdf8" stroke-width="1.5"/>
              <text x="95" y="318" fill="#ffffff" font-family="Inter, sans-serif" font-size="16" font-weight="700">
                📍 Đ/c: 28 An Cư 5, An Hải, Đà Nẵng   |   📞 Hotline/Zalo: 0787 546 220
              </text>

              <!-- Huy hiệu bên phải -->
              <circle cx="980" cy="200" r="115" fill="#041e36" fill-opacity="0.55" stroke="#fbbf24" stroke-width="3"/>
              <text x="980" y="168" text-anchor="middle" fill="#fde047" font-family="Inter, sans-serif" font-size="16" font-weight="700">ƯU ĐÃI ĐẶT TRƯỚC</text>
              <text x="980" y="212" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="38" font-weight="800">GIẢM 25%</text>
              <text x="980" y="244" text-anchor="middle" fill="#cbd5e1" font-family="Inter, sans-serif" font-size="14" font-weight="600">Xe Tay Ga &amp; Xe Số</text>
            </svg>

            <!-- Ảnh Banner 1 phiên bản ĐIỆN THOẠI (Thiết kế khác máy tính, tỷ lệ 640x320, chữ nhỏ gọn nằm hết trong ảnh) -->
            <svg class="block md:hidden w-full h-auto aspect-[2/1]" viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg">
              <defs>
                <linearGradient id="mbGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#062c4d"/>
                  <stop offset="100%" stop-color="#0b4f8a"/>
                </linearGradient>
              </defs>
              <rect width="640" height="320" fill="url(#mbGrad1)"/>
              <rect x="18" y="16" width="604" height="288" rx="14" fill="none" stroke="#ffffff" stroke-opacity="0.22" stroke-width="1.5"/>
              
              <rect x="150" y="32" width="340" height="28" rx="14" fill="#f59e0b"/>
              <text x="320" y="51" text-anchor="middle" fill="#062c4d" font-family="Inter, sans-serif" font-size="12" font-weight="800">
                CHOTHUEXEMAYHUNGVU.COM
              </text>

              <text x="320" y="96" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="22" font-weight="800">
                CHO THUÊ XE MÁY HÙNG VŨ
              </text>
              <text x="320" y="128" text-anchor="middle" fill="#fde047" font-family="Inter, sans-serif" font-size="16" font-weight="700">
                XE ĐỜI MỚI • GIÁ TỪ 80.000Đ/NGÀY
              </text>

              <text x="320" y="164" text-anchor="middle" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="13" font-weight="500">
                Giao xe tận nơi miễn phí Sân bay, Nhà ga, Khách sạn
              </text>
              <text x="320" y="190" text-anchor="middle" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="13" font-weight="500">
                Kèm 2 mũ bảo hiểm + áo mưa • Hỗ trợ 24/7
              </text>

              <rect x="44" y="214" width="552" height="68" rx="10" fill="#041e36" fill-opacity="0.8" stroke="#38bdf8" stroke-width="1.2"/>
              <text x="320" y="242" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="13.5" font-weight="700">
                📍 28 An Cư 5, An Hải, Đà Nẵng
              </text>
              <text x="320" y="268" text-anchor="middle" fill="#fde047" font-family="Inter, sans-serif" font-size="14.5" font-weight="800">
                📞 Hotline / Zalo: 0787 546 220
              </text>
            </svg>
          </div>

          <!-- ================= SLIDE 2 ================= -->
          <div class="w-full shrink-0 relative">
            <!-- Ảnh Banner 2 phiên bản MÁY TÍNH (Kích thước 1200x400 bằng tuyệt đối Slide 1) -->
            <svg class="hidden md:block w-full h-auto aspect-[3/1]" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg">
              <defs>
                <linearGradient id="pcGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#083358"/>
                  <stop offset="50%" stop-color="#0f5ca8"/>
                  <stop offset="100%" stop-color="#062c4d"/>
                </linearGradient>
              </defs>
              <rect width="1200" height="400" fill="url(#pcGrad2)"/>
              <circle cx="1020" cy="200" r="220" fill="#38bdf8" fill-opacity="0.08"/>
              <rect x="40" y="32" width="1120" height="336" rx="18" fill="none" stroke="#ffffff" stroke-opacity="0.2" stroke-width="2"/>

              <rect x="75" y="62" width="380" height="34" rx="17" fill="#ef4444"/>
              <text x="265" y="84" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="14" font-weight="800">
                GIAO XE TẬN NƠI MIỄN PHÍ CHỈ 10 PHÚT
              </text>

              <text x="75" y="142" fill="#ffffff" font-family="Inter, sans-serif" font-size="33" font-weight="800">
                ĐỘI XE TAY GA &amp; XE SỐ ĐA DẠNG ĐỜI MỚI
              </text>
              <text x="75" y="182" fill="#fde047" font-family="Inter, sans-serif" font-size="21" font-weight="700">
                AIR BLADE • VISION • LEAD • VARIO • SIRIUS • WAVE • 50CC
              </text>

              <text x="75" y="226" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="16" font-weight="500">
                ✓ Thủ tục đơn giản chỉ 5 phút • Bảo dưỡng định kỳ an toàn tuyệt đối khi đi Sơn Trà, Hải Vân
              </text>
              <text x="75" y="256" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="16" font-weight="500">
                ✓ Thuê theo ngày, theo tuần, theo tháng giá ưu đãi cho khách du lịch &amp; công tác
              </text>

              <rect x="75" y="286" width="690" height="52" rx="10" fill="#041e36" fill-opacity="0.75" stroke="#fbbf24" stroke-width="1.5"/>
              <text x="95" y="318" fill="#ffffff" font-family="Inter, sans-serif" font-size="16" font-weight="700">
                🌐 Web: chothuexemayhungvu.com   |   📞 Đặt xe nhanh: 0787 546 220
              </text>

              <circle cx="980" cy="200" r="115" fill="#041e36" fill-opacity="0.55" stroke="#38bdf8" stroke-width="3"/>
              <text x="980" y="168" text-anchor="middle" fill="#38bdf8" font-family="Inter, sans-serif" font-size="15" font-weight="700">CAM KẾT UY TÍN</text>
              <text x="980" y="210" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="34" font-weight="800">5.0 ★</text>
              <text x="980" y="242" text-anchor="middle" fill="#fde047" font-family="Inter, sans-serif" font-size="14" font-weight="600">Hỗ Trợ 24/24</text>
            </svg>

            <!-- Ảnh Banner 2 phiên bản ĐIỆN THOẠI (Kích thước 640x320 bằng tuyệt đối Slide 1 Điện thoại) -->
            <svg class="block md:hidden w-full h-auto aspect-[2/1]" viewBox="0 0 640 320" xmlns="http://www.w3.org/2000/svg">
              <defs>
                <linearGradient id="mbGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" stop-color="#083358"/>
                  <stop offset="100%" stop-color="#0f5ca8"/>
                </linearGradient>
              </defs>
              <rect width="640" height="320" fill="url(#mbGrad2)"/>
              <rect x="18" y="16" width="604" height="288" rx="14" fill="none" stroke="#ffffff" stroke-opacity="0.22" stroke-width="1.5"/>

              <rect x="145" y="32" width="350" height="28" rx="14" fill="#ef4444"/>
              <text x="320" y="51" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="12" font-weight="800">
                GIAO XE TẬN NƠI TRONG 10 PHÚT
              </text>

              <text x="320" y="96" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="21" font-weight="800">
                ĐỘI XE ĐỜI MỚI CHẤT LƯỢNG CAO
              </text>
              <text x="320" y="128" text-anchor="middle" fill="#fde047" font-family="Inter, sans-serif" font-size="14.5" font-weight="700">
                AIR BLADE • VISION • LEAD • SIRIUS • WAVE
              </text>

              <text x="320" y="164" text-anchor="middle" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="13" font-weight="500">
                Thủ tục thuê xe chỉ 5 phút • Bảo dưỡng định kỳ
              </text>
              <text x="320" y="190" text-anchor="middle" fill="#e2e8f0" font-family="Inter, sans-serif" font-size="13" font-weight="500">
                Ưu đãi giảm giá khi thuê từ 2 ngày hoặc theo tháng
              </text>

              <rect x="44" y="214" width="552" height="68" rx="10" fill="#041e36" fill-opacity="0.8" stroke="#fbbf24" stroke-width="1.2"/>
              <text x="320" y="242" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-size="13.5" font-weight="700">
                🌐 chothuexemayhungvu.com
              </text>
              <text x="320" y="268" text-anchor="middle" fill="#fde047" font-family="Inter, sans-serif" font-size="14.5" font-weight="800">
                📞 Đặt xe nhanh: 0787 546 220
              </text>
            </svg>
          </div>

        </div>

        <!-- Nút điều hướng Banner Trái / Phải -->
        <button 
          type="button" 
          onclick="prevBannerSlide()" 
          class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition"
          aria-label="Slide trước"
        >
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button 
          type="button" 
          onclick="nextBannerSlide()" 
          class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition"
          aria-label="Slide tiếp"
        >
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm tròn chỉ báo Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2">
          <button type="button" id="bannerDot0" onclick="goToBannerSlide(0)" class="w-6 h-2 rounded-full bg-amber-400 transition-all" aria-label="Slide 1"></button>
          <button type="button" id="bannerDot1" onclick="goToBannerSlide(1)" class="w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Slide 2"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- ================= 4 ƯU ĐIỂM NỔI BẬT (Chuẩn cấu trúc web mẫu dichvuthuexedanang.com) ================= -->
  <section class="py-3">
    <div class="flatsome-container">
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
        <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 shadow-sm flex items-start gap-3">
          <div class="w-10 h-10 rounded-lg bg-[#0b4f8a]/10 text-[#0b4f8a] flex items-center justify-center shrink-0">
            <i class="fa-solid fa-motorcycle text-lg"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-[#0b4f8a]">XE MÁY ĐỜI MỚI</h3>
            <p class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Bảo dưỡng định kỳ, máy êm, phanh lốp an toàn tuyệt đối.</p>
          </div>
        </div>
        <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 shadow-sm flex items-start gap-3">
          <div class="w-10 h-10 rounded-lg bg-red-50 text-red-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-bolt text-lg"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-[#0b4f8a]">GIAO XE CHỈ 10 PHÚT</h3>
            <p class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Hỗ trợ giao nhận tận nơi Sân bay, Nhà ga, Khách sạn.</p>
          </div>
        </div>
        <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 shadow-sm flex items-start gap-3">
          <div class="w-10 h-10 rounded-lg bg-emerald-50 text-emerald-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-tags text-lg"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-[#0b4f8a]">GIÁ TỪ 80.000Đ/NGÀY</h3>
            <p class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Niêm yết rõ ràng, thuê nhiều ngày giảm giá sâu.</p>
          </div>
        </div>
        <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 shadow-sm flex items-start gap-3">
          <div class="w-10 h-10 rounded-lg bg-amber-50 text-amber-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-helmet-safety text-lg"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-[#0b4f8a]">ĐẦY ĐỦ TIỆN ÍCH</h3>
            <p class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Kèm 2 mũ bảo hiểm sạch đẹp, 2 áo mưa, hỗ trợ 24/7.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC SẢN PHẨM & 14 ẢNH THỰC TẾ TỪ GOOGLE DRIVE ================= -->
  <section id="danh-muc-xe" class="py-6">
    <div class="flatsome-container">
      
      <!-- Tiêu đề Flatsome -->
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl md:text-2xl">DANH MỤC CHO THUÊ XE MÁY HÙNG VŨ ĐÀ NẴNG</span>
        <b></b>
      </div>
      <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto mb-4">
        Hình ảnh thực tế đội xe tại cửa hàng <strong>Cho Thuê Xe Máy Hùng Vũ</strong> (28 An Cư 5, An Hải, Đà Nẵng). Đầy đủ các dòng xe tay ga, xe số, xe côn tay và xe 50cc phục vụ du lịch, công tác.
      </p>

      <!-- Thanh Danh Mục Sản Phẩm Trang Chủ (Chữ nhỏ gọn, không xuống dòng chữ bên trong từng nút) -->
      <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-5">
        <button type="button" onclick="selectCategory('all')" data-cat="all" class="cat-filter-btn nav-category-item text-xs font-bold px-3 py-1.5 rounded-full bg-[#0b4f8a] text-white shadow-sm">
          Tất Cả Xe (14)
        </button>
        <button type="button" onclick="selectCategory('tay-ga')" data-cat="tay-ga" class="cat-filter-btn nav-category-item text-xs font-semibold px-3 py-1.5 rounded-full bg-white text-slate-700 border border-slate-300 hover:border-[#0b4f8a] hover:text-[#0b4f8a]">
          Thuê Xe Tay Ga (8)
        </button>
        <button type="button" onclick="selectCategory('xe-so')" data-cat="xe-so" class="cat-filter-btn nav-category-item text-xs font-semibold px-3 py-1.5 rounded-full bg-white text-slate-700 border border-slate-300 hover:border-[#0b4f8a] hover:text-[#0b4f8a]">
          Thuê Xe Số (4)
        </button>
        <button type="button" onclick="selectCategory('con-tay')" data-cat="con-tay" class="cat-filter-btn nav-category-item text-xs font-semibold px-3 py-1.5 rounded-full bg-white text-slate-700 border border-slate-300 hover:border-[#0b4f8a] hover:text-[#0b4f8a]">
          Thuê Xe Côn Tay (1)
        </button>
        <button type="button" onclick="selectCategory('xe-50cc')" data-cat="xe-50cc" class="cat-filter-btn nav-category-item text-xs font-semibold px-3 py-1.5 rounded-full bg-white text-slate-700 border border-slate-300 hover:border-[#0b4f8a] hover:text-[#0b4f8a]">
          Xe Máy 50cc Không Cần Bằng (1)
        </button>
      </div>

      <!-- LƯỚI SẢN PHẨM: Chia 2 cột trên Điện Thoại (grid-cols-2), 3 cột trên Tablet, 4 cột trên Máy Tính -->
      <!-- Có huy hiệu % giảm giá chuẩn Flatsome góc trên bên trái, KHÔNG để các nhãn dán khác ở trang chủ -->
      <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
        <!-- Được render tự động từ danh sách 14 ảnh sản phẩm thực tế Google Drive -->
      </div>

    </div>
  </section>

  <!-- ================= BẢNG GIÁ CHI TIẾT & ĐỊA ĐIỂM GIAO XE PHỔ BIẾN (Theo mẫu dichvuthuexedanang.com) ================= -->
  <section id="bang-gia" class="py-6 bg-white border-y border-slate-200">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl md:text-2xl">BẢNG GIÁ THUÊ XE MÁY ĐÀ NẴNG TẠI HÙNG VŨ</span>
        <b></b>
      </div>
      <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto mb-5">
        Hùng Vũ cung cấp dịch vụ cho thuê xe máy theo ngày, theo tuần và theo tháng. Thời gian thuê càng lâu mức giá càng ưu đãi:
      </p>

      <!-- Bảng giá chuẩn Flatsome -->
      <div class="overflow-x-auto rounded-xl border border-slate-200 shadow-sm mb-8">
        <table class="w-full text-left border-collapse text-xs sm:text-sm">
          <thead>
            <tr class="bg-[#0b4f8a] text-white">
              <th class="py-3 px-3 sm:px-4 font-bold">Các Dòng Xe Cho Thuê</th>
              <th class="py-3 px-3 sm:px-4 font-bold text-center">Thuê 1 Ngày</th>
              <th class="py-3 px-3 sm:px-4 font-bold text-center">Thuê Từ 2+ Ngày</th>
              <th class="py-3 px-3 sm:px-4 font-bold text-center">Thuê Theo Tháng</th>
            </tr>
          </thead>
          <tbody class="divide-y divide-slate-200 bg-white">
            <tr class="hover:bg-slate-50">
              <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">
                Xe số phổ thông (Honda Wave Alpha, Wave RSX, Yamaha Sirius)
              </td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-red-600">100.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-emerald-700">80.000đ - 90.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-700">1.400.000đ</td>
            </tr>
            <tr class="hover:bg-slate-50">
              <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">
                Xe máy 50cc (Không cần bằng lái, phù hợp học sinh - sinh viên - du khách)
              </td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-red-600">110.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-emerald-700">90.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-700">1.500.000đ</td>
            </tr>
            <tr class="hover:bg-slate-50">
              <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">
                Xe số cao cấp (Honda Future 125 FI - Chuyên trị đèo Hải Vân, bán đảo Sơn Trà)
              </td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-red-600">120.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-emerald-700">110.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-700">1.800.000đ</td>
            </tr>
            <tr class="hover:bg-slate-50">
              <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">
                Xe tay ga đời mới (Honda Air Blade 125, Honda Vision, Honda Lead, Yamaha Janus)
              </td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-red-600">140.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-emerald-700">110.000đ - 120.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-700">2.200.000đ</td>
            </tr>
            <tr class="hover:bg-slate-50">
              <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">
                Xe tay ga &amp; Côn tay phân khối lớn (Air Blade 150, Vario 160, PCX 150, SH Mode, Exciter 150)
              </td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-red-600">180.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-bold text-emerald-700">150.000đ - 160.000đ</td>
              <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-700">3.200.000đ</td>
            </tr>
          </tbody>
        </table>
      </div>

      <!-- Những địa điểm giao xe phổ biến tại Đà Nẵng (Giống web mẫu) -->
      <div id="giao-xe-tan-noi" class="pt-2">
        <div class="flatsome-section-title">
          <b></b>
          <span class="text-base sm:text-xl">ĐỊA ĐIỂM GIAO XE MÁY TẬN NƠI MIỄN PHÍ TẠI ĐÀ NẴNG</span>
          <b></b>
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
          <div class="rounded-xl border border-slate-200 p-4 bg-slate-50">
            <div class="text-[#0b4f8a] font-extrabold text-sm mb-1.5 flex items-center gap-2">
              <i class="fa-solid fa-plane-arrival"></i> SÂN BAY ĐÀ NẴNG
            </div>
            <p class="text-xs text-slate-600 leading-relaxed">
              Nhận xe ngay khi vừa xuống sân bay Đà Nẵng chỉ trong 10 phút. Tiết kiệm chi phí taxi và chủ động hành trình du lịch.
            </p>
          </div>
          <div class="rounded-xl border border-slate-200 p-4 bg-slate-50">
            <div class="text-[#0b4f8a] font-extrabold text-sm mb-1.5 flex items-center gap-2">
              <i class="fa-solid fa-train-subway"></i> NHÀ GA ĐÀ NẴNG
            </div>
            <p class="text-xs text-slate-600 leading-relaxed">
              Đội ngũ giao nhận xe trực tiếp tại cổng Ga Đà Nẵng đúng giờ tàu đến, thủ tục nhanh gọn trong 5 phút.
            </p>
          </div>
          <div class="rounded-xl border border-slate-200 p-4 bg-slate-50">
            <div class="text-[#0b4f8a] font-extrabold text-sm mb-1.5 flex items-center gap-2">
              <i class="fa-solid fa-hotel"></i> KHÁCH SẠN &amp; BIỂN MỸ KHÊ
            </div>
            <p class="text-xs text-slate-600 leading-relaxed">
              Vị trí cửa hàng tại 28 An Cư 5 (An Hải, Sơn Trà) sát biển Mỹ Khê, giao xe tận sảnh khách sạn/resort siêu tốc.
            </p>
          </div>
          <div class="rounded-xl border border-slate-200 p-4 bg-slate-50">
            <div class="text-[#0b4f8a] font-extrabold text-sm mb-1.5 flex items-center gap-2">
              <i class="fa-solid fa-bus"></i> BẾN XE TRUNG TÂM
            </div>
            <p class="text-xs text-slate-600 leading-relaxed">
              Hỗ trợ giao và nhận trả xe linh hoạt tại Bến xe Trung tâm Đà Nẵng và các quận Sơn Trà, Hải Châu, Ngũ Hành Sơn.
            </p>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- ================= FORM YÊU CẦU ĐẶT XE VÀ BÁO GIÁ TRANG CHỦ ================= -->
  <section id="bao-gia-form" class="py-7 bg-slate-100">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl md:text-2xl">FORM YÊU CẦU ĐẶT XE &amp; NHẬN BÁO GIÁ NHANH</span>
        <b></b>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
        <!-- Cột trái: Thủ tục cần thiết khi thuê xe (Từ web mẫu) -->
        <div class="lg:col-span-5 bg-[#0b4f8a] text-white rounded-xl p-5 shadow-md flex flex-col justify-between">
          <div>
            <h3 class="text-base sm:text-lg font-extrabold text-amber-300 mb-3 uppercase">
              Thủ Tục Thuê Xe Máy Tại Hùng Vũ
            </h3>
            <p class="text-xs sm:text-sm text-slate-100 mb-4 leading-relaxed">
              Thủ tục thuê xe tại <strong>Cho thuê xe máy Hùng Vũ</strong> cực kỳ đơn giản, nhanh gọn chỉ 5 phút:
            </p>
            <ul class="space-y-2.5 text-xs sm:text-sm">
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                <span><strong>Giấy tờ tùy thân:</strong> Căn cước công dân (CCCD) hoặc Hộ chiếu (Passport).</span>
              </li>
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                <span><strong>Bằng lái xe:</strong> GPLX hạng A1 trở lên (Nếu chưa có bằng lái, quý khách có thể chọn dòng xe 50cc).</span>
              </li>
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                <span><strong>Lưu ý bán đảo Sơn Trà:</strong> Quy định TP. Đà Nẵng cấm xe tay ga lên đỉnh Bàn Cờ - Sơn Trà, quý khách đi Sơn Trà nên chọn thuê <strong>Xe Số</strong> (Sirius, Wave, Future).</span>
              </li>
              <li class="flex items-start gap-2.5">
                <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                <span><strong>Trang bị kèm theo miễn phí:</strong> 02 mũ bảo hiểm đạt chuẩn + 02 áo mưa + Hợp đồng thuê xe đầy đủ.</span>
              </li>
            </ul>
          </div>

          <div class="mt-5 pt-4 border-t border-white/20 text-xs sm:text-sm space-y-1">
            <div class="font-bold text-amber-300">LIÊN HỆ TRỰC TIẾP HÙNG VŨ:</div>
            <div>📍 Địa chỉ: 28 An Cư 5, An Hải, Đà Nẵng</div>
            <div>📞 Hotline / Zalo: <a href="tel:0787546220" class="underline font-bold">0787 546 220</a></div>
            <div>🌐 Website: chothuexemayhungvu.com</div>
          </div>
        </div>

        <!-- Cột phải: Form yêu cầu và tự động tính báo giá -->
        <div class="lg:col-span-7 bg-white rounded-xl p-5 border border-slate-200 shadow-sm">
          <form id="quoteRequestForm" onsubmit="handleQuoteSubmit(event)" class="space-y-3.5">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full text-xs sm:text-sm border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b4f8a]">
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905xxxxxx" class="w-full text-xs sm:text-sm border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b4f8a]">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Chọn dòng xe cần thuê *</label>
                <select id="qBike" onchange="calculateEstimatedQuote()" class="w-full text-xs sm:text-sm border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b4f8a]">
                  <option value="120000" data-name="Honda Air Blade 125cc Đời Mới">Honda Air Blade 125cc (120.000đ/ngày)</option>
                  <option value="120000" data-name="Honda Vision 110cc Đời Mới">Honda Vision 110cc (120.000đ/ngày)</option>
                  <option value="120000" data-name="Honda Lead 125cc Cốp Rộng">Honda Lead 125cc Cốp Rộng (120.000đ/ngày)</option>
                  <option value="90000" data-name="Yamaha Sirius FI Đi Sơn Trà">Yamaha Sirius FI (90.000đ/ngày)</option>
                  <option value="80000" data-name="Honda Wave Alpha 110cc">Honda Wave Alpha 110cc (80.000đ/ngày)</option>
                  <option value="90000" data-name="Honda Wave RSX FI 110cc">Honda Wave RSX FI 110cc (90.000đ/ngày)</option>
                  <option value="150000" data-name="Honda Air Blade 150cc ABS">Honda Air Blade 150cc ABS (150.000đ/ngày)</option>
                  <option value="150000" data-name="Honda Vario 160cc Thể Thao">Honda Vario 160cc (150.000đ/ngày)</option>
                  <option value="160000" data-name="Honda PCX 150cc">Honda PCX 150cc (160.000đ/ngày)</option>
                  <option value="110000" data-name="Honda Future 125cc FI">Honda Future 125cc FI (110.000đ/ngày)</option>
                  <option value="180000" data-name="Honda SH Mode 125cc">Honda SH Mode 125cc (180.000đ/ngày)</option>
                  <option value="110000" data-name="Yamaha Janus 125cc">Yamaha Janus 125cc (110.000đ/ngày)</option>
                  <option value="160000" data-name="Yamaha Exciter 150cc">Yamaha Exciter 150cc (160.000đ/ngày)</option>
                  <option value="90000" data-name="Xe Máy 50cc Không Cần Bằng">Xe Máy 50cc Không Cần Bằng (90.000đ/ngày)</option>
                </select>
              </div>
              <div class="grid grid-cols-2 gap-2">
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Số lượng xe</label>
                  <input id="qQty" type="number" min="1" max="30" value="1" onchange="calculateEstimatedQuote()" onkeyup="calculateEstimatedQuote()" class="w-full text-xs sm:text-sm border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b4f8a]">
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Số ngày thuê</label>
                  <input id="qDays" type="number" min="1" max="90" value="2" onchange="calculateEstimatedQuote()" onkeyup="calculateEstimatedQuote()" class="w-full text-xs sm:text-sm border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b4f8a]">
                </div>
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Địa điểm nhận xe</label>
                <select id="qLocation" class="w-full text-xs sm:text-sm border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b4f8a]">
                  <option value="Nhận tại cửa hàng: 28 An Cư 5, An Hải, Đà Nẵng">Tại cửa hàng (28 An Cư 5, An Hải)</option>
                  <option value="Giao tận nơi Sân bay Quốc tế Đà Nẵng">Giao tận nơi Sân bay Đà Nẵng</option>
                  <option value="Giao tận nơi Nhà ga Đà Nẵng">Giao tận nơi Nhà ga Đà Nẵng</option>
                  <option value="Giao tận nơi Khách sạn / Biển Mỹ Khê">Giao tận nơi Khách sạn / Biển Mỹ Khê</option>
                  <option value="Giao tận nơi Bến xe Trung tâm Đà Nẵng">Giao tận nơi Bến xe Đà Nẵng</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Ghi chú thêm (Giờ nhận xe / Địa chỉ KS)</label>
                <input id="qNote" type="text" placeholder="VD: Giao lúc 9h sáng tại KS..." class="w-full text-xs sm:text-sm border border-slate-300 rounded-lg px-3 py-2 focus:outline-none focus:border-[#0b4f8a]">
              </div>
            </div>

            <!-- Hộp hiển thị Báo giá tạm tính trực quan -->
            <div class="bg-sky-50 border border-sky-200 rounded-lg p-3 flex flex-wrap items-center justify-between gap-2">
              <div class="text-xs text-slate-700">
                <span class="font-bold text-[#0b4f8a]">Báo giá tạm tính:</span>
                <span id="quoteSummaryText" class="ml-1">1 xe × 2 ngày (Miễn phí 2 mũ BH + 2 áo mưa)</span>
              </div>
              <div id="quoteTotalPrice" class="text-base sm:text-lg font-extrabold text-red-600">
                240.000₫
              </div>
            </div>

            <div class="flex flex-wrap items-center gap-2.5 pt-1">
              <button type="submit" class="flex-1 min-w-[180px] bg-[#0b4f8a] hover:bg-[#073863] text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg shadow transition flex items-center justify-center gap-2">
                <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU &amp; NHẬN BÁO GIÁ
              </button>
              <a href="https://zalo.me/0787546220" target="_blank" rel="noopener" class="bg-sky-600 hover:bg-sky-700 text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg shadow transition flex items-center justify-center gap-1.5">
                <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo Ngay
              </a>
            </div>
          </form>

          <!-- Hộp thông báo xác nhận sau khi gửi form (Không dùng alert) -->
          <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs sm:text-sm"></div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (KINH NGHIỆM THUÊ XE & DU LỊCH ĐÀ NẴNG) ================= -->
  <section id="bai-viet" class="py-7 bg-white border-b border-slate-200">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl md:text-2xl">KINH NGHIỆM THUÊ XE MÁY &amp; CẨM NANG DU LỊCH ĐÀ NẴNG</span>
        <b></b>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        <!-- Bài viết 1 -->
        <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
          <div>
            <div class="relative aspect-[16/10] bg-[#0b4f8a] overflow-hidden">
              <img 
                src="https://lh3.googleusercontent.com/d/1cTjhnOqrvlMTxGVDEIghZuAH8teRgn4Y=w600" 
                onerror="this.src='https://placehold.co/600x375/0b4f8a/ffffff?text=Ban+Dao+Son+Tra'"
                alt="Kinh nghiệm đi xe máy lên bán đảo Sơn Trà" 
                class="w-full h-full object-cover"
              >
              <span class="absolute bottom-2 left-2 bg-[#0b4f8a]/90 text-white text-[10px] font-bold px-2 py-0.5 rounded">
                Cẩm Nang Sơn Trà
              </span>
            </div>
            <div class="p-3.5">
              <h3 class="font-bold text-sm text-slate-800 mb-1.5 product-title-full">
                Kinh nghiệm đi xe máy lên bán đảo Sơn Trà &amp; Quy định cấm xe tay ga
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Thành phố Đà Nẵng quy định cấm xe tay ga lên bán đảo Sơn Trà để đảm bảo an toàn. Xem ngay lịch trình đi đỉnh Bàn Cờ, Cây Đa Ngàn Năm bằng xe số...
              </p>
            </div>
          </div>
          <div class="px-3.5 pb-3.5">
            <button type="button" onclick="openArticleModal(0)" class="text-xs font-bold text-[#0b4f8a] hover:text-red-600 inline-flex items-center gap-1">
              Xem chi tiết bài viết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
          <div>
            <div class="relative aspect-[16/10] bg-[#0b4f8a] overflow-hidden">
              <img 
                src="https://lh3.googleusercontent.com/d/1fYGANBwkjd5pCS2MSZWEJsk-UaZ1jUh-=w600" 
                onerror="this.src='https://placehold.co/600x375/0b4f8a/ffffff?text=Phuot+Deo+Hai+Van'"
                alt="Kinh nghiệm đi xe máy lên đèo Hải Vân" 
                class="w-full h-full object-cover"
              >
              <span class="absolute bottom-2 left-2 bg-[#0b4f8a]/90 text-white text-[10px] font-bold px-2 py-0.5 rounded">
                Phượt Đèo Hải Vân
              </span>
            </div>
            <div class="p-3.5">
              <h3 class="font-bold text-sm text-slate-800 mb-1.5 product-title-full">
                Kinh nghiệm phượt xe máy đèo Hải Vân và 7 lưu ý quan trọng cần nắm
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Đèo Hải Vân là cung đường ven biển đẹp bậc nhất Việt Nam. Hướng dẫn chọn dòng xe khỏe, kiểm tra phanh, lốp và các điểm check-in Hải Vân Quan...
              </p>
            </div>
          </div>
          <div class="px-3.5 pb-3.5">
            <button type="button" onclick="openArticleModal(1)" class="text-xs font-bold text-[#0b4f8a] hover:text-red-600 inline-flex items-center gap-1">
              Xem chi tiết bài viết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
          <div>
            <div class="relative aspect-[16/10] bg-[#0b4f8a] overflow-hidden">
              <img 
                src="https://lh3.googleusercontent.com/d/1rlLCYqyp9_rhctNk4XcmMyvu7YZZtrCa=w600" 
                onerror="this.src='https://placehold.co/600x375/0b4f8a/ffffff?text=Kiem+Tra+Xe+May'"
                alt="5 bước kiểm tra xe máy trước khi nhận thuê" 
                class="w-full h-full object-cover"
              >
              <span class="absolute bottom-2 left-2 bg-[#0b4f8a]/90 text-white text-[10px] font-bold px-2 py-0.5 rounded">
                Kinh Nghiệm Thuê Xe
              </span>
            </div>
            <div class="p-3.5">
              <h3 class="font-bold text-sm text-slate-800 mb-1.5 product-title-full">
                5 bước kiểm tra xe máy trước khi thuê để đảm bảo chuyến đi an toàn
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Tại Hùng Vũ, xe luôn được kiểm tra mỗi ngày. Tuy nhiên bạn nên nắm rõ cách kiểm tra thắng trước/sau, đèn, còi, xi-nhan và hợp đồng thuê xe...
              </p>
            </div>
          </div>
          <div class="px-3.5 pb-3.5">
            <button type="button" onclick="openArticleModal(2)" class="text-xs font-bold text-[#0b4f8a] hover:text-red-600 inline-flex items-center gap-1">
              Xem chi tiết bài viết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
          <div>
            <div class="relative aspect-[16/10] bg-[#0b4f8a] overflow-hidden">
              <img 
                src="https://lh3.googleusercontent.com/d/1_7EZYgKw4_BOYIsgv6v_riEP8Pn-PLrI=w600" 
                onerror="this.src='https://placehold.co/600x375/0b4f8a/ffffff?text=Thue+Xe+50cc'"
                alt="Khi nào thuê xe máy Đà Nẵng không cần bằng lái" 
                class="w-full h-full object-cover"
              >
              <span class="absolute bottom-2 left-2 bg-[#0b4f8a]/90 text-white text-[10px] font-bold px-2 py-0.5 rounded">
                Thủ Tục &amp; Pháp Lý
              </span>
            </div>
            <div class="p-3.5">
              <h3 class="font-bold text-sm text-slate-800 mb-1.5 product-title-full">
                Khi nào thuê xe máy không cần bằng lái? Giải pháp xe 50cc tiết kiệm
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Nếu bạn quên mang bằng lái hoặc chưa có GPLX A1, dòng xe máy dưới 50cc tại Hùng Vũ giúp bạn vi vu biển Mỹ Khê, phố cổ Hội An đúng luật...
              </p>
            </div>
          </div>
          <div class="px-3.5 pb-3.5">
            <button type="button" onclick="openArticleModal(3)" class="text-xs font-bold text-[#0b4f8a] hover:text-red-600 inline-flex items-center gap-1">
              Xem chi tiết bài viết <i class="fa-solid fa-arrow-right text-[10px]"></i>
            </button>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ================= ĐƯA FANPAGE & ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ ================= -->
  <section id="ban-do-fanpage" class="py-7 bg-slate-50 border-b border-slate-200">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl md:text-2xl">BẢN ĐỒ GOOGLE MAPS &amp; FANPAGE CHO THUÊ XE MÁY HÙNG VŨ</span>
        <b></b>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
        
        <!-- Cột Google Maps (Ảnh trực quan + Bản đồ tương tác + Nút mở link https://share.google/vHa7VIUGFPAlj68Yb) -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between">
          <div class="p-4 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
            <div>
              <h3 class="font-extrabold text-sm sm:text-base text-[#0b4f8a] flex items-center gap-2">
                <i class="fa-solid fa-map-location-dot text-red-600"></i>
                VỊ TRÍ CỬA HÀNG: 28 AN CƯ 5, AN HẢI, ĐÀ NẴNG
              </h3>
              <p class="text-xs text-slate-500 mt-0.5">
                Đánh giá 5.0★ trên Google Maps • Gần bãi biển Mỹ Khê &amp; Cầu Rồng
              </p>
            </div>
            <a 
              href="https://share.google/vHa7VIUGFPAlj68Yb" 
              target="_blank" 
              rel="noopener" 
              class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-red-600 hover:bg-red-700 text-white text-xs font-bold shadow-sm transition"
            >
              <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps Chỉ Đường
            </a>
          </div>

          <!-- Khung Google Map trực quan ngoài trang chủ -->
          <div class="relative w-full h-64 sm:h-72 bg-slate-200">
            <iframe 
              title="Bản đồ Cho Thuê Xe Máy Hùng Vũ 28 An Cư 5 Đà Nẵng"
              src="https://maps.google.com/maps?q=28%20An%20C%C6%B0%205,%20An%20H%E1%BA%A3i,%20S%C6%A1n%20Tr%C3%A0,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
              class="w-full h-full border-0" 
              loading="lazy" 
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>

          <!-- Thẻ Ảnh Sơ Đồ Vị Trí Google Map Tóm Tắt Ngoài Trang Chủ -->
          <a 
            href="https://share.google/vHa7VIUGFPAlj68Yb" 
            target="_blank" 
            rel="noopener"
            class="block bg-slate-50 hover:bg-sky-50 transition p-3 border-t border-slate-200"
          >
            <div class="flex items-center justify-between gap-3">
              <div class="flex items-center gap-3">
                <div class="w-11 h-11 rounded-lg bg-[#0b4f8a] text-white flex items-center justify-center shrink-0">
                  <i class="fa-solid fa-location-dot text-lg text-amber-300"></i>
                </div>
                <div class="text-xs">
                  <div class="font-bold text-slate-800">Cho Thuê Xe Máy Đà Nẵng HÙNG VŨ (Google Maps Chính Thức)</div>
                  <div class="text-slate-600">Địa chỉ: 28 An Cư 5, Phường An Hải, Quận Sơn Trà, TP. Đà Nẵng • ĐT: 0787 546 220</div>
                </div>
              </div>
              <span class="text-xs font-bold text-[#0b4f8a] whitespace-nowrap hidden sm:inline">
                Xem bản đồ <i class="fa-solid fa-up-right-from-square ml-0.5"></i>
              </span>
            </div>
          </a>
        </div>

        <!-- Cột Fanpage Facebook chính thức ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between p-4">
          <div>
            <div class="flex items-center justify-between gap-2 pb-3 mb-3 border-b border-slate-100">
              <div class="flex items-center gap-2">
                <i class="fa-brands fa-facebook text-xl text-[#1877F2]"></i>
                <div>
                  <h3 class="font-extrabold text-sm sm:text-base text-slate-800">FANPAGE FACEBOOK CHÍNH THỨC</h3>
                  <p class="text-[11px] text-slate-500">facebook.com/ChoThueXeMayHungVu</p>
                </div>
              </div>
              <a 
                href="https://www.facebook.com/ChoThueXeMayHungVu/" 
                target="_blank" 
                rel="noopener"
                class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold transition"
              >
                Theo Dõi Trang
              </a>
            </div>

            <!-- Thẻ Fanpage trực quan kèm Plugin nhúng -->
            <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 mb-3">
              <div class="bg-gradient-to-r from-[#073863] to-[#0b4f8a] p-3.5 text-white flex items-center gap-3">
                <img 
                  src="https://lh3.googleusercontent.com/d/1RQIaJYVpiut3nWHEyTFqi0v3InKOvirI=w200" 
                  onerror="this.src='https://placehold.co/80x80/ffffff/0b4f8a?text=HV'"
                  alt="Logo Fanpage Hùng Vũ" 
                  class="w-12 h-12 rounded-full object-contain bg-white p-0.5 border-2 border-amber-400 shrink-0"
                >
                <div class="min-w-0">
                  <a href="https://www.facebook.com/ChoThueXeMayHungVu/" target="_blank" rel="noopener" class="font-extrabold text-sm sm:text-base text-white hover:underline block truncate">
                    Cho Thuê Xe Máy Hùng Vũ Đà Nẵng
                  </a>
                  <div class="text-xs text-sky-200">Dịch vụ cho thuê xe máy • Mở cửa 24/7 • 5.0 ★</div>
                </div>
              </div>
              <div class="p-3 text-xs text-slate-700 space-y-1.5">
                <p>✅ Chuyên cho thuê các dòng xe tay ga &amp; xe số đời mới tại Đà Nẵng.</p>
                <p>✅ Giao nhận xe tận nơi miễn phí: Sân bay, Nhà ga, Khách sạn biển Mỹ Khê.</p>
                <p>📍 <strong>Địa chỉ:</strong> 28 An Cư 5, An Hải, Đà Nẵng</p>
                <p>📞 <strong>Hotline / Zalo:</strong> 0787 546 220</p>
              </div>
            </div>

            <!-- Facebook Page Plugin Iframe -->
            <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-white flex justify-center">
              <iframe 
                title="Facebook Fanpage Cho Thuê Xe Máy Hùng Vũ"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FChoThueXeMayHungVu%2F&tabs=&width=340&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                width="340" 
                height="130" 
                style="border:none;overflow:hidden;max-width:100%;" 
                scrolling="no" 
                frameborder="0" 
                allowfullscreen="true" 
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>
          </div>

          <div class="mt-3 pt-3 border-t border-slate-100 flex items-center justify-between gap-2">
            <a 
              href="https://www.facebook.com/ChoThueXeMayHungVu/" 
              target="_blank" 
              rel="noopener" 
              class="w-full py-2 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-[#0b4f8a] font-bold text-xs text-center transition"
            >
              <i class="fa-brands fa-facebook-messenger mr-1 text-[#1877F2]"></i> Nhắn Tin Qua Fanpage Facebook
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ================= DANH MỤC CÁC ĐỐI TÁC TRANG CHỦ ================= -->
  <section id="doi-tac" class="py-7 bg-white">
    <div class="flatsome-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl md:text-2xl">ĐỐI TÁC ĐỒNG HÀNH CÙNG THUÊ XE MÁY HÙNG VŨ</span>
        <b></b>
      </div>
      <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
        Hợp tác giao nhận xe nhanh chóng cùng hệ thống Khách sạn, Resort ven biển Mỹ Khê, các nền tảng đặt vé du lịch &amp; lữ hành uy tín tại Đà Nẵng:
      </p>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
        <div class="border border-slate-200 rounded-xl p-3.5 text-center bg-slate-50 hover:border-[#0b4f8a] transition">
          <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-[#0b4f8a]/10 text-[#0b4f8a] flex items-center justify-center">
            <i class="fa-solid fa-hotel"></i>
          </div>
          <div class="font-extrabold text-xs text-[#0b4f8a]">KHÁCH SẠN MỸ KHÊ</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Hệ thống KS &amp; Homestay Sơn Trà</div>
        </div>

        <div class="border border-slate-200 rounded-xl p-3.5 text-center bg-slate-50 hover:border-[#0b4f8a] transition">
          <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-amber-500/10 text-amber-600 flex items-center justify-center">
            <i class="fa-solid fa-bus-simple"></i>
          </div>
          <div class="font-extrabold text-xs text-[#0b4f8a]">VEXERE BLOG</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Đối tác giới thiệu điểm thuê xe</div>
        </div>

        <div class="border border-slate-200 rounded-xl p-3.5 text-center bg-slate-50 hover:border-[#0b4f8a] transition">
          <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-emerald-500/10 text-emerald-600 flex items-center justify-center">
            <i class="fa-solid fa-compass"></i>
          </div>
          <div class="font-extrabold text-xs text-[#0b4f8a]">GOLOOK TRAVEL</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Top địa điểm thuê xe uy tín</div>
        </div>

        <div class="border border-slate-200 rounded-xl p-3.5 text-center bg-slate-50 hover:border-[#0b4f8a] transition">
          <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-sky-500/10 text-sky-600 flex items-center justify-center">
            <i class="fa-solid fa-plane-departure"></i>
          </div>
          <div class="font-extrabold text-xs text-[#0b4f8a]">SÂN BAY ĐÀ NẴNG</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Điểm giao nhận xe 10 phút</div>
        </div>

        <div class="border border-slate-200 rounded-xl p-3.5 text-center bg-slate-50 hover:border-[#0b4f8a] transition">
          <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-red-500/10 text-red-600 flex items-center justify-center">
            <i class="fa-solid fa-mountain-sun"></i>
          </div>
          <div class="font-extrabold text-xs text-[#0b4f8a]">TOUR ĐÀ NẴNG - HỘI AN</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Cộng đồng du lịch tự túc</div>
        </div>

        <div class="border border-slate-200 rounded-xl p-3.5 text-center bg-slate-50 hover:border-[#0b4f8a] transition">
          <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-indigo-500/10 text-indigo-600 flex items-center justify-center">
            <i class="fa-solid fa-screwdriver-wrench"></i>
          </div>
          <div class="font-extrabold text-xs text-[#0b4f8a]">HONDA &amp; YAMAHA</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Bảo dưỡng chính hãng định kỳ</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================= FOOTER CHUẨN FLATSOME ================= -->
  <footer class="bg-[#062c4d] text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-amber-400">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/10">
        
        <!-- Cột 1: Về chúng tôi -->
        <div>
          <div class="flex items-center gap-2.5 mb-3">
            <img 
              src="https://lh3.googleusercontent.com/d/1RQIaJYVpiut3nWHEyTFqi0v3InKOvirI=w200" 
              onerror="this.src='https://placehold.co/80x80/ffffff/0b4f8a?text=HV'"
              alt="Logo Hùng Vũ" 
              class="w-10 h-10 rounded bg-white p-0.5 object-contain shrink-0"
            >
            <div>
              <div class="font-extrabold text-sm text-white">CHO THUÊ XE MÁY HÙNG VŨ</div>
              <div class="text-xs text-amber-300">chothuexemayhungvu.com</div>
            </div>
          </div>
          <p class="text-xs text-slate-300 leading-relaxed mb-3">
            Cửa hàng Cho Thuê Xe Máy Đà Nẵng Hùng Vũ chuyên cung cấp các dòng xe tay ga, xe số đời mới chất lượng cao, thủ tục đơn giản, giao xe miễn phí tận nơi nhanh chóng chỉ 10 phút.
          </p>
        </div>

        <!-- Cột 2: Thông tin liên hệ -->
        <div>
          <h4 class="font-extrabold text-sm text-amber-300 uppercase mb-3">Thông Tin Liên Hệ</h4>
          <ul class="space-y-2 text-xs text-slate-200">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-amber-400 mt-0.5"></i>
              <span><strong>Địa chỉ:</strong> 28 An Cư 5, Phường An Hải, Quận Sơn Trà, TP. Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone-volume text-amber-400"></i>
              <span><strong>Hotline / Zalo:</strong> <a href="tel:0787546220" class="text-white font-bold hover:underline">0787 546 220</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-amber-400"></i>
              <span><strong>Website:</strong> chothuexemayhungvu.com</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-brands fa-facebook text-amber-400"></i>
              <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/ChoThueXeMayHungVu/" target="_blank" rel="noopener" class="hover:underline">fb.com/ChoThueXeMayHungVu</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-map-pin text-amber-400"></i>
              <span><strong>Google Map:</strong> <a href="https://share.google/vHa7VIUGFPAlj68Yb" target="_blank" rel="noopener" class="hover:underline">Xem chỉ đường</a></span>
            </li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục dòng xe -->
        <div>
          <h4 class="font-extrabold text-sm text-amber-300 uppercase mb-3">Danh Mục Cho Thuê Xe</h4>
          <ul class="space-y-1.5 text-xs text-slate-300">
            <li><a href="#danh-muc-xe" onclick="selectCategory('tay-ga')" class="hover:text-white">› Thuê xe tay ga Honda Air Blade</a></li>
            <li><a href="#danh-muc-xe" onclick="selectCategory('tay-ga')" class="hover:text-white">› Thuê xe tay ga Honda Vision đời mới</a></li>
            <li><a href="#danh-muc-xe" onclick="selectCategory('tay-ga')" class="hover:text-white">› Thuê xe tay ga Honda Lead cốp rộng</a></li>
            <li><a href="#danh-muc-xe" onclick="selectCategory('xe-so')" class="hover:text-white">› Thuê xe số Yamaha Sirius đi Sơn Trà</a></li>
            <li><a href="#danh-muc-xe" onclick="selectCategory('xe-so')" class="hover:text-white">› Thuê xe số Honda Wave Alpha / RSX</a></li>
            <li><a href="#danh-muc-xe" onclick="selectCategory('xe-50cc')" class="hover:text-white">› Thuê xe máy 50cc không cần bằng lái</a></li>
          </ul>
        </div>

        <!-- Cột 4: Cam kết dịch vụ -->
        <div>
          <h4 class="font-extrabold text-sm text-amber-300 uppercase mb-3">Hỗ Trợ Khách Hàng 24/7</h4>
          <ul class="space-y-1.5 text-xs text-slate-300">
            <li>✓ Giao xe tận Sân bay, Nhà ga, Khách sạn</li>
            <li>✓ Kèm 2 mũ bảo hiểm chuẩn + 2 áo mưa</li>
            <li>✓ Xe bảo dưỡng định kỳ, hỗ trợ sự cố 24/7</li>
            <li>✓ Giá thuê minh bạch, không phí ẩn</li>
          </ul>
        </div>

      </div>

      <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-400">
        <div>Copyright 2026 © <strong>chothuexemayhungvu.com</strong> - Thiết kế theo chuẩn Flatsome Theme</div>
        <div>Địa chỉ: 28 An Cư 5, An Hải, Đà Nẵng • SĐT: 0787 546 220</div>
      </div>
    </div>
  </footer>

  <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
  <div class="fixed bottom-3 right-3 z-50 flex flex-col items-end gap-2">
    <!-- Nút Facebook Fanpage -->
    <a 
      href="https://www.facebook.com/ChoThueXeMayHungVu/" 
      target="_blank" 
      rel="noopener"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
      title="Chat Facebook Cho thuê xe máy Hùng Vũ"
    >
      <i class="fa-brands fa-facebook-messenger text-base sm:text-lg"></i>
      <span class="text-xs font-bold">Facebook</span>
    </a>

    <!-- Nút Zalo 0787 546 220 -->
    <a 
      href="https://zalo.me/0787546220" 
      target="_blank" 
      rel="noopener"
      class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
      title="Nhắn Zalo 0787 546 220"
    >
      <span class="w-5 h-5 rounded-full bg-white text-[#0068ff] font-extrabold text-[10px] flex items-center justify-center">Zalo</span>
      <span class="text-xs font-bold">Zalo 0787.546.220</span>
    </a>

    <!-- Nút Gọi Hotline 0787 546 220 -->
    <a 
      href="tel:0787546220" 
      class="pulse-btn flex items-center gap-2 bg-[#e53935] hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition"
      title="Gọi ngay 0787 546 220"
    >
      <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
      <span class="text-xs sm:text-sm font-extrabold">0787 546 220</span>
    </a>
  </div>

  <!-- ================= MODAL XEM CHI TIẾT BÀI VIẾT CẨM NANG ================= -->
  <div id="articleModal" class="fixed inset-0 z-50 hidden bg-black/60 flex items-center justify-center p-3">
    <div class="bg-white rounded-xl max-w-xl w-full max-h-[85vh] overflow-y-auto p-5 shadow-2xl border border-slate-200">
      <div class="flex items-start justify-between gap-3 pb-3 border-b border-slate-200">
        <h3 id="modalArticleTitle" class="font-extrabold text-base sm:text-lg text-[#0b4f8a]"></h3>
        <button type="button" onclick="closeArticleModal()" class="text-slate-400 hover:text-red-600 text-lg leading-none">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div id="modalArticleBody" class="py-4 text-xs sm:text-sm text-slate-700 space-y-2.5 leading-relaxed"></div>
      <div class="pt-3 border-t border-slate-200 flex items-center justify-between">
        <a href="tel:0787546220" class="bg-[#0b4f8a] text-white text-xs font-bold px-3.5 py-2 rounded-lg">
          📞 Đặt xe ngay: 0787 546 220
        </a>
        <button type="button" onclick="closeArticleModal()" class="text-xs font-bold text-slate-600 hover:text-slate-900 px-3 py-1.5 rounded bg-slate-100">
          Đóng
        </button>
      </div>
    </div>
  </div>

  <!-- ================= JAVASCRIPT XỬ LÝ DỮ LIỆU 14 ẢNH SẢN PHẨM DRIVE, SLIDER & BÁO GIÁ ================= -->
  <script>
    // Danh sách 14 sản phẩm sử dụng chính xác 14 file ảnh thực tế từ Google Drive của khách hàng
    const productsData = [
      {
        id: 1,
        driveId: "1rlLCYqyp9_rhctNk4XcmMyvu7YZZtrCa",
        name: "Thuê Xe Tay Ga Honda Air Blade 125cc Đời Mới",
        category: "tay-ga",
        categoryName: "Thuê Xe Tay Ga",
        oldPrice: 150000,
        newPrice: 120000,
        discountPercent: 20,
        desc: "Xe tay ga Air Blade đời mới, máy êm, cốp rộng, tiết kiệm nhiên liệu."
      },
      {
        id: 2,
        driveId: "1eehbI5bxOROw0X3wwsjKoR0CEN4uBxar",
        name: "Thuê Xe Tay Ga Honda Vision 110cc Đời Mới",
        category: "tay-ga",
        categoryName: "Thuê Xe Tay Ga",
        oldPrice: 150000,
        newPrice: 120000,
        discountPercent: 20,
        desc: "Dòng xe tay ga quốc dân nhỏ gọn, cực kỳ dễ lái, phù hợp di chuyển phố biển."
      },
      {
        id: 3,
        driveId: "1bycuz-gObqZWlCe4N6KVku8_T5P6MEVz",
        name: "Thuê Xe Tay Ga Honda Lead 125cc Cốp Siêu Rộng",
        category: "tay-ga",
        categoryName: "Thuê Xe Tay Ga",
        oldPrice: 150000,
        newPrice: 120000,
        discountPercent: 20,
        desc: "Cốp xe 37 lít để vừa 2 mũ bảo hiểm và balo du lịch, vận hành êm ái."
      },
      {
        id: 4,
        driveId: "1cTjhnOqrvlMTxGVDEIghZuAH8teRgn4Y",
        name: "Thuê Xe Số Yamaha Sirius FI Đi Đỉnh Bàn Cờ",
        category: "xe-so",
        categoryName: "Thuê Xe Số",
        oldPrice: 120000,
        newPrice: 90000,
        discountPercent: 25,
        desc: "Xe số máy khỏe, lựa chọn số 1 để đi bán đảo Sơn Trà, đỉnh Bàn Cờ."
      },
      {
        id: 5,
        driveId: "1PiX1MqPUDkLDTqsILw-GDCrg84I2Yqas",
        name: "Thuê Xe Số Honda Wave Alpha 110cc Tiết Kiệm Xăng",
        category: "xe-so",
        categoryName: "Thuê Xe Số",
        oldPrice: 110000,
        newPrice: 80000,
        discountPercent: 27,
        desc: "Bền bỉ, gọn nhẹ, siêu tiết kiệm xăng, đi được mọi địa hình dốc tại Đà Nẵng."
      },
      {
        id: 6,
        driveId: "1RvZ9SgfNniG_MCBIAw6M4q4I0f_W7TDM",
        name: "Thuê Xe Số Honda Wave RSX FI 110cc Thể Thao",
        category: "xe-so",
        categoryName: "Thuê Xe Số",
        oldPrice: 120000,
        newPrice: 90000,
        discountPercent: 25,
        desc: "Phun xăng điện tử FI tiết kiệm, thắng đĩa an toàn khi đổ đèo Sơn Trà, Hải Vân."
      },
      {
        id: 7,
        driveId: "1bY3-9OGP_kJRwbq0efJf1uttABTQJWlT",
        name: "Thuê Xe Tay Ga Honda Air Blade 150cc Khóa Smartkey",
        category: "tay-ga",
        categoryName: "Thuê Xe Tay Ga",
        oldPrice: 180000,
        newPrice: 150000,
        discountPercent: 17,
        desc: "Động cơ 150cc mạnh mẽ, khóa thông minh Smartkey, phanh ABS an toàn."
      },
      {
        id: 8,
        driveId: "1qbba_uAajTqcncfgskp_4AiD-30tv_ak",
        name: "Thuê Xe Tay Ga Honda Vario 160cc Thể Thao",
        category: "tay-ga",
        categoryName: "Thuê Xe Tay Ga",
        oldPrice: 190000,
        newPrice: 150000,
        discountPercent: 21,
        desc: "Kiểu dáng thể thao năng động, động cơ 160cc bốc và đầm chắc."
      },
      {
        id: 9,
        driveId: "1zDTSY_-KBcPjTfJ0UmenuSJe-riMvaoZ",
        name: "Thuê Xe Tay Ga Honda PCX 150cc Đi Đường Trường",
        category: "tay-ga",
        categoryName: "Thuê Xe Tay Ga",
        oldPrice: 200000,
        newPrice: 160000,
        discountPercent: 20,
        desc: "Tư thế ngồi thoải mái, êm ái khi đi Hội An, Bà Nà Hills, Lăng Cô."
      },
      {
        id: 10,
        driveId: "1fYGANBwkjd5pCS2MSZWEJsk-UaZ1jUh-",
        name: "Thuê Xe Số Honda Future 125cc FI Leo Đèo Khỏe",
        category: "xe-so",
        categoryName: "Thuê Xe Số",
        oldPrice: 140000,
        newPrice: 110000,
        discountPercent: 21,
        desc: "Xe số cao cấp 125cc cốp rộng, leo dốc bán đảo Sơn Trà cực khỏe."
      },
      {
        id: 11,
        driveId: "17Jye5Nm83GlWbXnHWSTnZf1HW4rLTTeH",
        name: "Thuê Xe Tay Ga Honda SH Mode 125cc Thời Trang",
        category: "tay-ga",
        categoryName: "Thuê Xe Tay Ga",
        oldPrice: 220000,
        newPrice: 180000,
        discountPercent: 18,
        desc: "Thiết kế sang trọng, lịch lãm, phù hợp chụp ảnh check-in & công tác."
      },
      {
        id: 12,
        driveId: "1Uj7qtHu2-SnQv798LSXLNFKPlMt90YA8",
        name: "Thuê Xe Tay Ga Yamaha Janus 125cc Nhỏ Gọn",
        category: "tay-ga",
        categoryName: "Thuê Xe Tay Ga",
        oldPrice: 140000,
        newPrice: 110000,
        discountPercent: 21,
        desc: "Trọng lượng nhẹ, động cơ Blue Core êm ái, rất được các bạn nữ ưa chuộng."
      },
      {
        id: 13,
        driveId: "1Y6fCKklSJM51mUISEDUW11RdB5pSn0Ak",
        name: "Thuê Xe Côn Tay Yamaha Exciter 150cc Phượt Đèo",
        category: "con-tay",
        categoryName: "Thuê Xe Côn Tay",
        oldPrice: 200000,
        newPrice: 160000,
        discountPercent: 20,
        desc: "Xe côn tay thể thao mạnh mẽ dành cho tín đồ đam mê phượt đèo Hải Vân."
      },
      {
        id: 14,
        driveId: "1_7EZYgKw4_BOYIsgv6v_riEP8Pn-PLrI",
        name: "Thuê Xe Máy 50cc Không Cần Bằng Lái",
        category: "xe-50cc",
        categoryName: "Xe Máy 50cc",
        oldPrice: 120000,
        newPrice: 90000,
        discountPercent: 25,
        desc: "Không yêu cầu bằng lái A1, nhẹ nhàng, an toàn, tiết kiệm nhiên liệu."
      }
    ];

    // Định dạng tiền tệ VNĐ
    function formatVND(amount) {
      return amount.toLocaleString("vi-VN") + "₫";
    }

    // Render danh sách sản phẩm chuẩn Flatsome (2 cột trên điện thoại, huy hiệu giảm giá góc trên bên trái, không nhãn dán thừa)
    function renderProducts(list) {
      const grid = document.getElementById("productGrid");
      if (!grid) return;

      if (list.length === 0) {
        grid.innerHTML = `
          <div class="col-span-full bg-white rounded-xl p-6 text-center border border-slate-200 text-xs sm:text-sm text-slate-600">
            Không tìm thấy dòng xe phù hợp. Vui lòng gọi <strong>0787 546 220</strong> để được tư vấn trực tiếp!
          </div>
        `;
        return;
      }

      grid.innerHTML = list.map(item => {
        const primaryImg = `https://lh3.googleusercontent.com/d/${item.driveId}=w700`;
        const backupImg = `https://drive.google.com/thumbnail?id=${item.driveId}&sz=w700`;
        const fallbackImg = `https://placehold.co/600x450/0b4f8a/ffffff?text=${encodeURIComponent(item.name)}`;

        return `
          <div class="bg-white rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition overflow-hidden flex flex-col justify-between">
            <div>
              <!-- Khung ảnh sản phẩm + Huy hiệu giảm giá % góc trên bên trái chuẩn Flatsome -->
              <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                <div class="flatsome-onsale">-${item.discountPercent}%</div>
                <img 
                  src="${primaryImg}" 
                  onerror="if(this.src.indexOf('drive.google.com/thumbnail')===-1){this.src='${backupImg}';}else{this.src='${fallbackImg}';}"
                  alt="${item.name}" 
                  loading="lazy"
                  class="w-full h-full object-cover hover:scale-105 transition duration-300"
                >
              </div>

              <!-- Thông tin sản phẩm: Tên sản phẩm đầy đủ không bị cắt chữ, không tràn viền -->
              <div class="p-2.5 sm:p-3.5">
                <div class="text-[10px] sm:text-[11px] font-semibold text-slate-400 uppercase mb-0.5">
                  ${item.categoryName}
                </div>
                <h3 class="product-title-full font-bold text-xs sm:text-sm md:text-[15px] text-slate-800 mb-1.5">
                  ${item.name}
                </h3>
                <p class="text-[11px] sm:text-xs text-slate-500 leading-snug mb-2">
                  ${item.desc}
                </p>
              </div>
            </div>

            <!-- Giá gốc + Giá giảm + Nút đặt thuê chuẩn Flatsome -->
            <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100">
              <div class="flex flex-wrap items-baseline gap-x-1.5 gap-y-0.5 mb-2">
                <del class="text-[11px] sm:text-xs text-slate-400">${formatVND(item.oldPrice)}</del>
                <ins class="text-xs sm:text-sm md:text-base font-extrabold text-red-600 no-underline">
                  ${formatVND(item.newPrice)}<span class="text-[10px] sm:text-xs font-semibold text-slate-500">/ngày</span>
                </ins>
              </div>
              <div class="grid grid-cols-2 gap-1.5">
                <button 
                  type="button" 
                  onclick="chooseBikeForQuote('${item.name}', ${item.newPrice})"
                  class="bg-[#0b4f8a] hover:bg-[#073863] text-white font-bold text-[11px] sm:text-xs py-1.5 px-2 rounded-lg text-center transition"
                >
                  Đặt Xe
                </button>
                <a 
                  href="tel:0787546220" 
                  class="bg-red-50 hover:bg-red-100 text-red-600 border border-red-200 font-bold text-[11px] sm:text-xs py-1.5 px-2 rounded-lg text-center transition"
                >
                  Liên Hệ
                </a>
              </div>
            </div>
          </div>
        `;
      }).join("");
    }

    // Lọc theo danh mục
    function selectCategory(cat) {
      document.querySelectorAll(".cat-filter-btn").forEach(btn => {
        if (btn.getAttribute("data-cat") === cat) {
          btn.className = "cat-filter-btn nav-category-item text-xs font-bold px-3 py-1.5 rounded-full bg-[#0b4f8a] text-white shadow-sm";
        } else {
          btn.className = "cat-filter-btn nav-category-item text-xs font-semibold px-3 py-1.5 rounded-full bg-white text-slate-700 border border-slate-300 hover:border-[#0b4f8a] hover:text-[#0b4f8a]";
        }
      });

      if (cat === "all") {
        renderProducts(productsData);
      } else {
        renderProducts(productsData.filter(p => p.category === cat));
      }
    }

    // Tìm kiếm xe trên máy tính & điện thoại
    function filterBySearch() {
      const q = (document.getElementById("searchBikeInput")?.value || "").trim().toLowerCase();
      if (!q) {
        renderProducts(productsData);
        return;
      }
      const filtered = productsData.filter(p =>
        p.name.toLowerCase().includes(q) || p.desc.toLowerCase().includes(q) || p.categoryName.toLowerCase().includes(q)
      );
      renderProducts(filtered);
      document.getElementById("danh-muc-xe")?.scrollIntoView({ behavior: "smooth" });
    }

    function filterByMobileSearch() {
      const q = (document.getElementById("mobileSearchInput")?.value || "").trim().toLowerCase();
      toggleMobileMenu();
      if (!q) {
        renderProducts(productsData);
        return;
      }
      const filtered = productsData.filter(p =>
        p.name.toLowerCase().includes(q) || p.desc.toLowerCase().includes(q) || p.categoryName.toLowerCase().includes(q)
      );
      renderProducts(filtered);
      document.getElementById("danh-muc-xe")?.scrollIntoView({ behavior: "smooth" });
    }

    // Đóng/mở menu danh mục trên điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById("mobileMenuDrawer");
      if (drawer) {
        drawer.classList.toggle("hidden");
      }
    }

    // ================= SLIDER 2 BANNER TỰ TRƯỢT =================
    let currentBannerIndex = 0;
    let bannerTimer = null;

    function updateBannerPosition() {
      const track = document.getElementById("bannerTrack");
      const dot0 = document.getElementById("bannerDot0");
      const dot1 = document.getElementById("bannerDot1");
      if (!track) return;

      track.style.transform = `translateX(-${currentBannerIndex * 100}%)`;
      if (dot0 && dot1) {
        if (currentBannerIndex === 0) {
          dot0.className = "w-6 h-2 rounded-full bg-amber-400 transition-all";
          dot1.className = "w-2.5 h-2 rounded-full bg-white/60 transition-all";
        } else {
          dot0.className = "w-2.5 h-2 rounded-full bg-white/60 transition-all";
          dot1.className = "w-6 h-2 rounded-full bg-amber-400 transition-all";
        }
      }
    }

    function nextBannerSlide() {
      currentBannerIndex = (currentBannerIndex + 1) % 2;
      updateBannerPosition();
      resetBannerAutoSlide();
    }

    function prevBannerSlide() {
      currentBannerIndex = (currentBannerIndex - 1 + 2) % 2;
      updateBannerPosition();
      resetBannerAutoSlide();
    }

    function goToBannerSlide(index) {
      currentBannerIndex = index;
      updateBannerPosition();
      resetBannerAutoSlide();
    }

    function resetBannerAutoSlide() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(() => {
        currentBannerIndex = (currentBannerIndex + 1) % 2;
        updateBannerPosition();
      }, 4500);
    }

    // ================= TÍNH BÁO GIÁ TỰ ĐỘNG & XỬ LÝ FORM =================
    function calculateEstimatedQuote() {
      const selectEl = document.getElementById("qBike");
      const qtyEl = document.getElementById("qQty");
      const daysEl = document.getElementById("qDays");
      const summaryEl = document.getElementById("quoteSummaryText");
      const totalEl = document.getElementById("quoteTotalPrice");

      if (!selectEl || !qtyEl || !daysEl || !summaryEl || !totalEl) return;

      const pricePerDay = parseInt(selectEl.value, 10) || 120000;
      const qty = Math.max(1, parseInt(qtyEl.value, 10) || 1);
      const days = Math.max(1, parseInt(daysEl.value, 10) || 1);

      // Giảm thêm 10% nếu thuê từ 5 ngày trở lên
      let total = pricePerDay * qty * days;
      let discountNote = "Miễn phí giao xe + 2 mũ BH + 2 áo mưa";
      if (days >= 5) {
        total = Math.round(total * 0.9);
        discountNote = "Đã giảm thêm 10% ưu đãi thuê dài ngày";
      }

      summaryEl.textContent = `${qty} xe × ${days} ngày (${discountNote})`;
      totalEl.textContent = formatVND(total);
    }

    function chooseBikeForQuote(bikeName, price) {
      const selectEl = document.getElementById("qBike");
      if (selectEl) {
        for (let i = 0; i < selectEl.options.length; i++) {
          if ( bikeName.includes(selectEl.options[i].getAttribute("data-name").split(" ")[1]) ) {
            selectEl.selectedIndex = i;
            break;
          }
        }
      }
      calculateEstimatedQuote();
      document.getElementById("bao-gia-form")?.scrollIntoView({ behavior: "smooth" });
    }

    function handleQuoteSubmit(e) {
      e.preventDefault();
      const name = document.getElementById("qName").value.trim();
      const phone = document.getElementById("qPhone").value.trim();
      const selectEl = document.getElementById("qBike");
      const bikeName = selectEl.options[selectEl.selectedIndex].text;
      const qty = document.getElementById("qQty").value;
      const days = document.getElementById("qDays").value;
      const location = document.getElementById("qLocation").value;
      const total = document.getElementById("quoteTotalPrice").textContent;

      const box = document.getElementById("quoteSuccessBox");
      box.classList.remove("hidden");
      box.innerHTML = `
        <div class="font-bold text-emerald-900 mb-1">
          <i class="fa-solid fa-circle-check mr-1"></i> Đã ghi nhận yêu cầu báo giá của ${name} (${phone})!
        </div>
        <div>• <strong>Xe đăng ký:</strong> ${bikeName} | Số lượng: ${qty} xe × ${days} ngày</div>
        <div>• <strong>Điểm nhận xe:</strong> ${location} | <strong>Tổng tạm tính:</strong> <span class="font-bold text-red-600">${total}</span></div>
        <div class="mt-1.5">Cửa hàng <strong>Hùng Vũ (0787 546 220)</strong> sẽ liên hệ xác nhận giao xe ngay cho quý khách!</div>
      `;
    }

    // ================= MODAL BÀI VIẾT CẨM NANG =================
    const articlesContent = [
      {
        title: "Kinh nghiệm đi xe máy lên bán đảo Sơn Trà & Quy định cấm xe tay ga",
        body: `
          <p><strong>1. Quy định cấm xe tay ga lên bán đảo Sơn Trà:</strong> Để đảm bảo an toàn giao thông trên các cung đường dốc đứng như đỉnh Bàn Cờ, Cây Đa Ngàn Năm, TP. Đà Nẵng quy định cấm xe tay ga lưu thông lên bán đảo Sơn Trà (trừ đoạn đường Hoàng Sa đi chùa LinhỨng).</p>
          <p><strong>2. Nên thuê dòng xe nào?</strong> Quý khách nên chọn thuê các dòng <strong>Xe Số</strong> khỏe tại Hùng Vũ như <em>Yamaha Sirius FI, Honda Wave RSX hoặc Honda Future 125 FI</em> để chủ động挂 số thấp khi lên và xuống dốc an toàn.</p>
          <p><strong>3. Thời gian lý tưởng:</strong> Nên xuất phát từ 7h00 - 16h30 hàng ngày để ngắm trọn vẹn cảnh biển Đà Nẵng từ trên cao.</p>
        `
      },
      {
        title: "Kinh nghiệm phượt xe máy đèo Hải Vân và 7 lưu ý quan trọng",
        body: `
          <p><strong>1. Chọn xe phanh tốt, lốp bám đường:</strong> Đèo Hải Vân dài khoảng 20km với nhiều khúc cua tay áo. Đội xe tại Cho thuê xe máy Hùng Vũ luôn được kiểm tra kỹ hệ thống phanh trước/sau và lốp trước khi bàn giao.</p>
          <p><strong>2. Các điểm dừng chân đẹp:</strong> Cây thông cô đơn, Hải Vân Quan, khúc cua chữ U, cà phê Hòn Đá Cụ Rùa và vịnh Lăng Cô.</p>
          <p><strong>3. Lưu ý an toàn:</strong> Đi đúng làn đường, bật đèn chiếu gần nếu có sương mù và luôn mang đầy đủ giấy tờ xe, hợp đồng thuê xe do Hùng Vũ cung cấp.</p>
        `
      },
      {
        title: "5 bước kiểm tra xe máy trước khi thuê để đảm bảo chuyến đi an toàn",
        body: `
          <p>Khi nhận xe tại <strong>Cho thuê xe máy Hùng Vũ (28 An Cư 5, An Hải, Đà Nẵng)</strong>, toàn bộ xe đã được kỹ thuật viên bảo dưỡng. Tuy nhiên quý khách nên kiểm tra nhanh 5 điểm sau:</p>
          <p>• Kiểm tra bóp thắng trước và đạp thắng sau.</p>
          <p>• Kiểm tra hệ thống đèn pha, đèn xi-nhan trái/phải và còi xe.</p>
          <p>• Kiểm tra độ căng của 2 lốp xe và gương chiếu hậu.</p>
          <p>• Nhận đầy đủ 02 mũ bảo hiểm, 02 áo mưa và hợp đồng thuê xe có số Hotline cứu hộ 24/7: <strong>0787 546 220</strong>.</p>
        `
      },
      {
        title: "Khi nào thuê xe máy không cần bằng lái? Giải pháp xe 50cc tiết kiệm",
        body: `
          <p>Không phải du khách nào khi đi du lịch Đà Nẵng cũng mang sẵn bằng lái xe hạng A1 hoặc đã đủ tuổi thi GPLX. Trong trường hợp này, lựa chọn thuê <strong>Xe máy dưới 50cc</strong> tại Hùng Vũ là giải pháp hoàn toàn hợp pháp và an toàn.</p>
          <p>• Không yêu cầu bằng lái xe khi tham gia giao thông.</p>
          <p>• Kiểu dáng nhỏ gọn, dễ điều khiển, rất phù hợp dạo biển Mỹ Khê, Cầu Rồng, chợ Hàn, chợ Cồn và phố cổ Hội An.</p>
        `
      }
    ];

    function openArticleModal(index) {
      const item = articlesContent[index];
      if (!item) return;
      document.getElementById("modalArticleTitle").textContent = item.title;
      document.getElementById("modalArticleBody").innerHTML = item.body;
      document.getElementById("articleModal").classList.remove("hidden");
    }

    function closeArticleModal() {
      document.getElementById("articleModal").classList.add("hidden");
    }

    // Khởi chạy khi tải trang
    window.onload = function () {
      renderProducts(productsData);
      calculateEstimatedQuote();
      resetBannerAutoSlide();
    };
  </script>
</body>
</html>
