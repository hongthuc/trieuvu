<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI TRIỆU VŨ | trieuvu.com</title>
    <meta name="description" content="Công ty Cổ phần Xây dựng và Thương mại Triệu Vũ (trieuvu.com) - Chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện và xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0912.164.990.">

    <!-- Open Graph / Social Share Thumbnail sử dụng Logo Triệu Vũ khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://trieuvu.com/">
    <meta property="og:site_name" content="trieuvu.com - Xây Dựng & Thương Mại Triệu Vũ">
    <meta property="og:title" content="CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI TRIỆU VŨ">
    <meta property="og:description" content="Thiết kế kiến trúc - Thi công xây dựng trọn gói - Dự án tiêu biểu tại Đà Nẵng. Hotline: 0912.164.990.">
    <meta property="og:image" content="https://trieuvu.com/wp-content/uploads/logo-trieu-vu-share.png">
    <meta property="og:image:alt" content="Logo Công ty Cổ phần Xây dựng và Thương mại Triệu Vũ">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI TRIỆU VŨ">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng uy tín tại Đà Nẵng - Hotline: 0912.164.990">
    <meta name="twitter:image" content="https://trieuvu.com/wp-content/uploads/logo-trieu-vu-share.png">

    <!-- Favicon đồng bộ Logo -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230E2A47'/%3E%3Cpath d='M12 34L32 14L52 34' stroke='%23E59A24' stroke-width='5' stroke-linecap='round' stroke-linejoin='round' fill='none'/%3E%3Cpath d='M20 30V50H28V38H36V50H44V30' stroke='%23FFFFFF' stroke-width='4' stroke-linejoin='round' fill='none'/%3E%3C/svg%3E">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter (hiển thị sắc nét tiếng Việt) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Cấu hình màu chủ đạo đồng bộ theo Logo Triệu Vũ -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        navy: {
                            DEFAULT: '#0E2A47',
                            dark: '#091C30',
                            light: '#173E66',
                        },
                        gold: {
                            DEFAULT: '#D98A1C',
                            light: '#E8A338',
                            soft: '#FDF6EA',
                        },
                        slatebg: '#F5F7FA',
                    }
                }
            }
        }
    </script>

    <style>
        /* Chuẩn hóa Box-Sizing và triệt tiêu hoàn toàn tràn viền / lệch phải */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
        }

        /* Khung Flatsome: Chiều ngang máy tính đúng 95% kích thước màn hình, căn giữa chuẩn */
        .tv-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .tv-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tiêu đề Section phong cách Flatsome tinh giản dễ dựng UX Builder */
        .flatsome-section-title {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .flatsome-section-title::after {
            content: "";
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 64px;
            height: 3px;
            background-color: #D98A1C;
            border-radius: 999px;
        }
        .flatsome-section-title-left::after {
            left: 0;
            transform: none;
        }

        /* Menu Dropdown Flatsome mượt mà trên máy tính */
        .nav-item-dropdown:hover .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .nav-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }

        /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối, chữ cách xa viền không bị cắt */
        .hero-slider-wrapper {
            position: relative;
            width: 100%;
            overflow: hidden;
        }
        .hero-slides-grid {
            display: grid;
            grid-template-columns: 1fr;
            width: 100%;
        }
        .hero-slide-item {
            grid-area: 1 / 1;
            width: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
            position: relative;
            display: flex;
            align-items: center;
        }
        .hero-slide-item.active {
            opacity: 1;
            visibility: visible;
            z-index: 2;
        }

        /* Ẩn thanh cuộn nhưng vẫn cuộn ngang mượt cho danh mục trên mobile nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Hiệu ứng nhịp nhẹ cho nút Hotline nổi bật */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(217, 138, 28, 0.55); }
            70% { box-shadow: 0 0 0 10px rgba(217, 138, 28, 0); }
            100% { box-shadow: 0 0 0 0 rgba(217, 138, 28, 0); }
        }
        .btn-hotline-pulse {
            animation: softPulse 2.2s infinite;
        }
    </style>
</head>
<body class="antialiased bg-white text-slate-800">

    <!-- =========================================================
         1. TOP BAR THÔNG TIN (Gọn gàng kiểu Flatsome)
    ========================================================== -->
    <div class="bg-navy text-white text-xs py-2 border-b border-white/10">
        <div class="tv-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-4 flex-wrap">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-phone text-gold-light"></i>
                    <a href="tel:0912164990" class="hover:text-gold-light transition font-medium">0912.164.990</a>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-gold-light"></i>
                    <span>K39/16 Lê Văn Thứ, Phường Sơn Trà, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-4 text-slate-200">
                <span class="hidden md:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-gold-light"></i>
                    <span>trieuvu.com</span>
                </span>
                <span class="hidden lg:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-building text-gold-light"></i>
                    <span>MST: 0401974553</span>
                </span>
            </div>
        </div>
    </div>

    <!-- =========================================================
         2. HEADER CHÍNH (Logo gọn nhỏ, Menu 1 hàng không xuống dòng,
            KHÔNG để nút Gọi ngay trên Header tránh tràn viền)
    ========================================================== -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="tv-container">
            <div class="flex items-center justify-between h-16 lg:h-[70px] gap-3">

                <!-- Logo Công ty Triệu Vũ thiết kế chuyên nghiệp, chỉnh gọn nhỏ tinh tế -->
                <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Trang chủ Công ty Cổ phần Xây dựng và Thương mại Triệu Vũ">
                    <svg class="w-9 h-9 lg:w-10 lg:h-10 shrink-0 transition-transform duration-200 group-hover:scale-105" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Khối khiên kiến trúc nền xanh Navy -->
                        <rect x="2" y="2" width="60" height="60" rx="12" fill="#0E2A47"/>
                        <rect x="4" y="4" width="56" height="56" rx="10" stroke="#D98A1C" stroke-width="1.5" stroke-opacity="0.45"/>
                        <!-- Đường mái kiến trúc cách điệu chữ V ngược / Mái nhà vàng Gold -->
                        <path d="M12 31L32 13L52 31" stroke="#E8A338" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <!-- Hệ cột kết cấu vững chắc tạo khối chữ T-V -->
                        <path d="M19 32H45" stroke="#FFFFFF" stroke-width="3.2" stroke-linecap="round"/>
                        <path d="M25 32V49" stroke="#FFFFFF" stroke-width="3.5" stroke-linecap="round"/>
                        <path d="M33 32L38.5 48.5L44 32" stroke="#E8A338" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round"/>
                        <!-- Đường nền móng vững bền -->
                        <path d="M16 51H48" stroke="#FFFFFF" stroke-width="2.2" stroke-linecap="round" stroke-opacity="0.85"/>
                    </svg>
                    <div class="leading-tight">
                        <div class="text-[15px] lg:text-[16px] font-extrabold tracking-tight text-navy whitespace-nowrap">
                            TRIỆU VŨ
                        </div>
                        <div class="text-[9.5px] lg:text-[10px] font-semibold tracking-wider text-gold uppercase whitespace-nowrap">
                            Xây Dựng &amp; Thương Mại
                        </div>
                    </div>
                </a>

                <!-- Menu điều hướng trên máy tính: Chữ nhỏ gọn, viết liền 1 hàng, KHÔNG xuống dòng -->
                <nav class="hidden lg:flex items-center justify-end flex-1 gap-x-1 xl:gap-x-3" aria-label="Menu chính">
                    <a href="#trang-chu" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-navy hover:text-gold transition whitespace-nowrap">
                        Trang chủ
                    </a>
                    <a href="#gioi-thieu" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-gold transition whitespace-nowrap">
                        Giới thiệu
                    </a>

                    <!-- Dropdown Công trình thực tế -->
                    <div class="relative nav-item-dropdown">
                        <a href="#cong-trinh-thuc-te" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-gold transition whitespace-nowrap inline-flex items-center gap-1">
                            <span>Công trình thực tế</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                            <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-1.5">
                                <a href="#cong-trinh-thuc-te" onclick="filterWorks('khach-san-can-ho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-gold-soft hover:text-navy font-medium">Khách sạn – Căn hộ</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterWorks('biet-thu')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-gold-soft hover:text-navy font-medium">Biệt thự</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterWorks('nha-pho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-gold-soft hover:text-navy font-medium">Nhà phố</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterWorks('van-phong')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-gold-soft hover:text-navy font-medium">Văn phòng – Thương mại</a>
                            </div>
                        </div>
                    </div>

                    <!-- Dropdown Lĩnh vực hoạt động -->
                    <div class="relative nav-item-dropdown">
                        <a href="#linh-vuc" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-gold transition whitespace-nowrap inline-flex items-center gap-1">
                            <span>Lĩnh vực hoạt động</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                            <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-1.5">
                                <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-gold-soft hover:text-navy font-medium">Thiết kế Kiến trúc – Nội thất</a>
                                <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-gold-soft hover:text-navy font-medium">Thi công phần thô</a>
                                <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-gold-soft hover:text-navy font-medium">Thi công hoàn thiện</a>
                                <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-gold-soft hover:text-navy font-medium">Thi công nội thất trọn gói</a>
                            </div>
                        </div>
                    </div>

                    <a href="#du-an-da-nang" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-gold transition whitespace-nowrap">
                        Dự án Đà Nẵng
                    </a>
                    <a href="#bao-gia" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-gold transition whitespace-nowrap">
                        Báo giá
                    </a>
                    <a href="#doi-tac" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-gold transition whitespace-nowrap">
                        Đối tác
                    </a>
                    <a href="#tin-tuc" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-gold transition whitespace-nowrap">
                        Tin tức
                    </a>
                    <a href="#lien-he" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-gold transition whitespace-nowrap">
                        Liên hệ
                    </a>
                </nav>

                <!-- Nút mở Menu trên điện thoại (không đặt nút Gọi ngay trên Header) -->
                <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-navy hover:bg-slate-50 transition" aria-label="Mở menu điều hướng">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>
            </div>
        </div>

        <!-- Menu Mobile thả xuống gọn gàng -->
        <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="px-4 py-3 grid grid-cols-2 gap-2">
                <a href="#trang-chu" class="mobile-nav-link px-3 py-2.5 rounded-lg bg-slatebg text-[13px] font-semibold text-navy">Trang chủ</a>
                <a href="#gioi-thieu" class="mobile-nav-link px-3 py-2.5 rounded-lg bg-slatebg text-[13px] font-semibold text-slate-700">Giới thiệu</a>
                <a href="#linh-vuc" class="mobile-nav-link px-3 py-2.5 rounded-lg bg-slatebg text-[13px] font-semibold text-slate-700">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" class="mobile-nav-link px-3 py-2.5 rounded-lg bg-slatebg text-[13px] font-semibold text-slate-700">Công trình thực tế</a>
                <a href="#du-an-da-nang" class="mobile-nav-link px-3 py-2.5 rounded-lg bg-slatebg text-[13px] font-semibold text-slate-700">Dự án Đà Nẵng</a>
                <a href="#bao-gia" class="mobile-nav-link px-3 py-2.5 rounded-lg bg-slatebg text-[13px] font-semibold text-slate-700">Yêu cầu báo giá</a>
                <a href="#doi-tac" class="mobile-nav-link px-3 py-2.5 rounded-lg bg-slatebg text-[13px] font-semibold text-slate-700">Đối tác</a>
                <a href="#tin-tuc" class="mobile-nav-link px-3 py-2.5 rounded-lg bg-slatebg text-[13px] font-semibold text-slate-700">Tin tức</a>
                <a href="#lien-he" class="mobile-nav-link col-span-2 px-3 py-2.5 rounded-lg bg-navy text-white text-[13px] font-semibold text-center">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <main id="trang-chu">

        <!-- =========================================================
             3. HERO SLIDER: 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
                - Hình ảnh và chữ nằm trọn bên trong banner
                - Chữ cách xa viền ảnh (padding rộng)
                - Không bị thiếu chữ trên điện thoại và máy tính
        ========================================================== -->
        <section class="bg-slatebg py-3 sm:py-4">
            <div class="tv-container">
                <div id="heroSlider" class="hero-slider-wrapper rounded-xl shadow-md bg-navy">
                    <div class="hero-slides-grid">

                        <!-- Banner 1 -->
                        <div class="hero-slide-item active min-h-[290px] sm:min-h-[380px] lg:min-h-[460px]">
                            <img src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
                                 data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                 onerror="handleDriveImgError(this, 'Thi Cong Xay Dung Trieu Vu')"
                                 alt="Thi công xây dựng chuyên nghiệp Công ty Cổ phần Xây dựng và Thương mại Triệu Vũ"
                                 class="absolute inset-0 w-full h-full object-cover object-center">
                            <!-- Lớp phủ tối cân đối để chữ nổi bật tuyệt đối -->
                            <div class="absolute inset-0 bg-gradient-to-r from-navy/90 via-navy/75 to-navy/45"></div>

                            <!-- Khung chữ cách xa viền ảnh banner trên mọi màn hình -->
                            <div class="relative z-10 w-full px-8 py-9 sm:px-14 sm:py-12 lg:px-20 lg:py-16">
                                <div class="max-w-2xl">
                                    <p class="text-[11px] sm:text-xs font-bold tracking-widest uppercase text-gold-light mb-2 sm:mb-3">
                                        CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI TRIỆU VŨ
                                    </p>
                                    <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3 sm:mb-4">
                                        THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI CHUYÊN NGHIỆP TẠI ĐÀ NẴNG
                                    </h1>
                                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                                        Kiến tạo công trình bền vững chuẩn kỹ thuật — An toàn, đúng tiến độ và minh bạch chi phí cho mọi nhà phố, biệt thự, khách sạn và văn phòng.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-gold hover:bg-gold-light text-white text-xs sm:text-sm font-bold transition shadow">
                                            Nhận Báo Giá Miễn Phí
                                        </a>
                                        <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                                            Xem Công Trình Thực Tế
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Banner 2 (Cấu trúc tương đồng đảm bảo kích thước bằng nhau 100% với Banner 1) -->
                        <div class="hero-slide-item min-h-[290px] sm:min-h-[380px] lg:min-h-[460px]">
                            <img src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
                                 data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                 onerror="handleDriveImgError(this, 'Du An Tieu Bieu Da Nang - Trieu Vu')"
                                 alt="Dự án xây dựng tiêu biểu tại Đà Nẵng - Triệu Vũ"
                                 class="absolute inset-0 w-full h-full object-cover object-center">
                            <div class="absolute inset-0 bg-gradient-to-r from-navy/90 via-navy/75 to-navy/45"></div>

                            <!-- Khung chữ cách xa viền ảnh banner trên mọi màn hình -->
                            <div class="relative z-10 w-full px-8 py-9 sm:px-14 sm:py-12 lg:px-20 lg:py-16">
                                <div class="max-w-2xl">
                                    <p class="text-[11px] sm:text-xs font-bold tracking-widest uppercase text-gold-light mb-2 sm:mb-3">
                                        ĐỒNG HÀNH CÙNG MỌI CÔNG TRÌNH • TRIEUVU.COM
                                    </p>
                                    <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3 sm:mb-4">
                                        GIẢI PHÁP THI CÔNG PHẦN THÔ, HOÀN THIỆN &amp; NỘI THẤT ĐẲNG CẤP
                                    </h2>
                                    <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                                        Đội ngũ kỹ sư giàu kinh nghiệm trực tiếp giám sát từng hạng mục, cam kết vật tư chuẩn chất lượng và bảo hành công trình lâu dài.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-gold hover:bg-gold-light text-white text-xs sm:text-sm font-bold transition shadow">
                                            Khám Phá Dự Án Đà Nẵng
                                        </a>
                                        <a href="tel:0912164990" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                                            Hotline: 0912.164.990
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng trái / phải tinh gọn sát mép an toàn -->
                    <button id="prevSlideBtn" type="button" aria-label="Banner trước"
                            class="hidden sm:flex absolute left-3 top-1/2 -translate-y-1/2 z-20 w-9 h-9 rounded-full bg-black/35 hover:bg-gold text-white items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-sm"></i>
                    </button>
                    <button id="nextSlideBtn" type="button" aria-label="Banner tiếp theo"
                            class="hidden sm:flex absolute right-3 top-1/2 -translate-y-1/2 z-20 w-9 h-9 rounded-full bg-black/35 hover:bg-gold text-white items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-sm"></i>
                    </button>

                    <!-- Dấu chấm chỉ báo 2 banner -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" class="hero-dot w-7 h-2 rounded-full bg-gold transition-all" data-slide="0" aria-label="Chuyển tới banner 1"></button>
                        <button type="button" class="hero-dot w-2.5 h-2 rounded-full bg-white/55 hover:bg-white transition-all" data-slide="1" aria-label="Chuyển tới banner 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================
             4. DỊCH VỤ TIÊU BIỂU / LĨNH VỰC HOẠT ĐỘNG (Theo mẫu Tín Trường Thịnh)
        ========================================================== -->
        <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
            <div class="tv-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-section-title text-xl sm:text-2xl font-extrabold text-navy uppercase tracking-tight">
                        Lĩnh Vực Hoạt Động Tiêu Biểu
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                        Danh mục dịch vụ trọng tâm từ thiết kế, thi công phần thô, hoàn thiện đến nội thất trọn gói của Triệu Vũ.
                    </p>
                </div>

                <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <a href="#bao-gia" class="group rounded-xl border border-slate-200 bg-white p-4 sm:p-6 text-center hover:border-gold hover:shadow-md transition">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-navy/5 text-navy group-hover:bg-navy group-hover:text-gold-light flex items-center justify-center transition">
                            <i class="fa-solid fa-compass-drafting text-xl sm:text-2xl"></i>
                        </div>
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-navy leading-snug mb-1.5">
                            Thiết Kế Kiến Trúc – Nội Thất
                        </h3>
                        <p class="text-[11.5px] sm:text-[13px] text-slate-600 leading-relaxed">
                            Hồ sơ kiến trúc, kết cấu 3D tối ưu công năng và thẩm mỹ hiện đại.
                        </p>
                    </a>

                    <a href="#bao-gia" class="group rounded-xl border border-slate-200 bg-white p-4 sm:p-6 text-center hover:border-gold hover:shadow-md transition">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-navy/5 text-navy group-hover:bg-navy group-hover:text-gold-light flex items-center justify-center transition">
                            <i class="fa-solid fa-trowel-bricks text-xl sm:text-2xl"></i>
                        </div>
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-navy leading-snug mb-1.5">
                            Thi Công Phần Thô
                        </h3>
                        <p class="text-[11.5px] sm:text-[13px] text-slate-600 leading-relaxed">
                            Móng, khung bê tông cốt thép, xây tô chuẩn kỹ thuật bền vững.
                        </p>
                    </a>

                    <a href="#bao-gia" class="group rounded-xl border border-slate-200 bg-white p-4 sm:p-6 text-center hover:border-gold hover:shadow-md transition">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-navy/5 text-navy group-hover:bg-navy group-hover:text-gold-light flex items-center justify-center transition">
                            <i class="fa-solid fa-paint-roller text-xl sm:text-2xl"></i>
                        </div>
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-navy leading-snug mb-1.5">
                            Thi Công Hoàn Thiện
                        </h3>
                        <p class="text-[11.5px] sm:text-[13px] text-slate-600 leading-relaxed">
                            Ốp lát, sơn nước, điện nước M&amp;E sắc nét từng đường nét chi tiết.
                        </p>
                    </a>

                    <a href="#bao-gia" class="group rounded-xl border border-slate-200 bg-white p-4 sm:p-6 text-center hover:border-gold hover:shadow-md transition">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-navy/5 text-navy group-hover:bg-navy group-hover:text-gold-light flex items-center justify-center transition">
                            <i class="fa-solid fa-couch text-xl sm:text-2xl"></i>
                        </div>
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-navy leading-snug mb-1.5">
                            Thi Công Nội Thất Trọn Gói
                        </h3>
                        <p class="text-[11.5px] sm:text-[13px] text-slate-600 leading-relaxed">
                            Sản xuất &amp; lắp đặt nội thất nhà phố, căn hộ, khách sạn, văn phòng.
                        </p>
                    </a>
                </div>
            </div>
        </section>

        <!-- =========================================================
             5. GIỚI THIỆU CÔNG TY & THẾ MẠNH (Cấu trúc Flatsome 2 cột + 6 ô)
        ========================================================== -->
        <section id="gioi-thieu" class="py-10 sm:py-14 bg-slatebg border-y border-slate-200/70">
            <div class="tv-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
                    <div class="lg:col-span-6">
                        <p class="text-xs font-bold uppercase tracking-wider text-gold mb-2">Về Chúng Tôi</p>
                        <h2 class="flatsome-section-title flatsome-section-title-left text-xl sm:text-2xl font-extrabold text-navy uppercase leading-snug mb-5">
                            CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI TRIỆU VŨ
                        </h2>
                        <p class="text-sm text-slate-700 leading-relaxed mb-3">
                            <strong>Triệu Vũ</strong> chuyên hoạt động trong lĩnh vực Thiết kế Kiến trúc – Thi công Xây dựng – Cung ứng Vật tư Thương mại cho các công trình Khách sạn, Căn hộ cho thuê, Biệt thự, Nhà phố và Văn phòng tại khu vực Đà Nẵng và miền Trung.
                        </p>
                        <p class="text-sm text-slate-700 leading-relaxed mb-5">
                            Đặt chữ <strong>“TÂM – TÍN – CHẤT”</strong> lên hàng đầu, mỗi công trình do Triệu Vũ thực hiện đều được kiểm soát nghiêm ngặt từ bản vẽ, vật tư đầu vào cho tới tiến độ bàn giao, mang lại giá trị sử dụng lâu dài và sự an tâm tuyệt đối cho Quý Chủ đầu tư.
                        </p>
                        <div class="grid grid-cols-3 gap-3 text-center">
                            <div class="bg-white rounded-xl p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-navy">10+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 font-medium">Năm kinh nghiệm</div>
                            </div>
                            <div class="bg-white rounded-xl p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-gold">150+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 font-medium">Công trình bàn giao</div>
                            </div>
                            <div class="bg-white rounded-xl p-3 border border-slate-200">
                                <div class="text-lg sm:text-2xl font-extrabold text-navy">100%</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 font-medium">Đúng tiến độ</div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-6">
                        <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
                            <img src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1200"
                                 data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                                 onerror="handleDriveImgError(this, 'Cong Trinh Thuc Te Trieu Vu')"
                                 alt="Hình ảnh thi công thực tế của Công ty Cổ phần Xây dựng và Thương mại Triệu Vũ"
                                 class="w-full h-64 sm:h-80 object-cover">
                        </div>
                    </div>
                </div>

                <!-- 6 Thế mạnh của Triệu Vũ (tương ứng mẫu web Tín Trường Thịnh) -->
                <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200">
                        <div class="flex items-center gap-2.5 mb-2">
                            <i class="fa-solid fa-user-helmet-safety text-gold text-lg shrink-0"></i>
                            <h3 class="text-[13px] sm:text-[14.5px] font-bold text-navy leading-snug">Đội ngũ kỹ sư chuyên nghiệp</h3>
                        </div>
                        <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư, tổ đội thi công dày dặn kinh nghiệm thực chiến.</p>
                    </div>
                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200">
                        <div class="flex items-center gap-2.5 mb-2">
                            <i class="fa-solid fa-layer-group text-gold text-lg shrink-0"></i>
                            <h3 class="text-[13px] sm:text-[14.5px] font-bold text-navy leading-snug">Vật tư &amp; công nghệ hiện đại</h3>
                        </div>
                        <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Cập nhật xu hướng thiết kế mới, vật liệu chính hãng từ các thương hiệu lớn uy tín.</p>
                    </div>
                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200">
                        <div class="flex items-center gap-2.5 mb-2">
                            <i class="fa-solid fa-clock text-gold text-lg shrink-0"></i>
                            <h3 class="text-[13px] sm:text-[14.5px] font-bold text-navy leading-snug">Giám sát tiến độ chuẩn xác</h3>
                        </div>
                        <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Báo cáo tiến độ công trường minh bạch định kỳ, cam kết bàn giao đúng lịch hẹn.</p>
                    </div>
                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200">
                        <div class="flex items-center gap-2.5 mb-2">
                            <i class="fa-solid fa-shield-halved text-gold text-lg shrink-0"></i>
                            <h3 class="text-[13px] sm:text-[14.5px] font-bold text-navy leading-snug">Bảo hành công trình lâu dài</h3>
                        </div>
                        <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Chính sách bảo hành kết cấu và hoàn thiện rõ ràng, hỗ trợ bảo trì nhanh chóng.</p>
                    </div>
                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200">
                        <div class="flex items-center gap-2.5 mb-2">
                            <i class="fa-solid fa-file-invoice-dollar text-gold text-lg shrink-0"></i>
                            <h3 class="text-[13px] sm:text-[14.5px] font-bold text-navy leading-snug">Chi phí hợp lý, không phát sinh</h3>
                        </div>
                        <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục ngay từ đầu, tối ưu ngân sách cho chủ đầu tư.</p>
                    </div>
                    <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200">
                        <div class="flex items-center gap-2.5 mb-2">
                            <i class="fa-solid fa-headset text-gold text-lg shrink-0"></i>
                            <h3 class="text-[13px] sm:text-[14.5px] font-bold text-navy leading-snug">Tư vấn tận tâm 24/7</h3>
                        </div>
                        <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Hỗ trợ khảo sát hiện trạng, lên phương án và báo giá sơ bộ hoàn toàn miễn phí.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================
             6. DANH MỤC CÔNG TRÌNH / SẢN PHẨM THI CÔNG THỰC TẾ (9 ẢNH DRIVE THỰC TẾ)
                - Chữ danh mục nhỏ gọn, viết liền không xuống dòng tên danh mục
                - 2 cột trên giao diện điện thoại, tên sản phẩm hiển thị đầy đủ không tràn/thiếu chữ
                - KHÔNG để các nhãn dán (badges/stickers) trên hình ảnh trang chủ
        ========================================================== -->
        <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
            <div class="tv-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-section-title text-xl sm:text-2xl font-extrabold text-navy uppercase tracking-tight">
                        Công Trình Thi Công Thực Tế
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                        Hình ảnh thi công thực tế tại công trường theo các danh mục hạng mục xây dựng chuẩn của Công ty Cổ phần Xây dựng và Thương mại Triệu Vũ.
                    </p>
                </div>

                <!-- Thanh danh mục tối ưu đẹp trên máy tính & điện thoại (chữ nhỏ gọn, 1 hàng hoặc gọn hàng 2, KHÔNG xuống dòng trong tên danh mục) -->
                <div id="worksFilterBar" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                    <button type="button" data-filter="all" onclick="filterWorks('all')"
                            class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-navy text-white border border-navy">
                        Tất cả
                    </button>
                    <button type="button" data-filter="khach-san-can-ho" onclick="filterWorks('khach-san-can-ho')"
                            class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-slatebg text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Khách sạn – Căn hộ
                    </button>
                    <button type="button" data-filter="biet-thu" onclick="filterWorks('biet-thu')"
                            class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-slatebg text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Biệt thự
                    </button>
                    <button type="button" data-filter="nha-pho" onclick="filterWorks('nha-pho')"
                            class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-slatebg text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Nhà phố
                    </button>
                    <button type="button" data-filter="van-phong" onclick="filterWorks('van-phong')"
                            class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-slatebg text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Văn phòng
                    </button>
                    <button type="button" data-filter="phan-tho" onclick="filterWorks('phan-tho')"
                            class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-slatebg text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Thi công phần thô
                    </button>
                    <button type="button" data-filter="hoan-thien" onclick="filterWorks('hoan-thien')"
                            class="work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-slatebg text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Thi công hoàn thiện
                    </button>
                </div>

                <!-- Lưới sản phẩm/công trình thực tế: 2 cột trên điện thoại, 3 cột tablet, 3-4 cột máy tính -->
                <div id="worksGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Dữ liệu render bằng JS từ đúng 9 link ảnh Google Drive của người dùng -->
                </div>
            </div>
        </section>

        <!-- =========================================================
             7. DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DRIVE THỰC TẾ)
                - 2 cột trên điện thoại, 4-5 cột gọn đẹp trên máy tính
                - Không có nhãn dán đè lên ảnh, tên dự án đầy đủ không bị cắt
        ========================================================== -->
        <section id="du-an-da-nang" class="py-10 sm:py-14 bg-slatebg border-y border-slate-200/70">
            <div class="tv-container">
                <div class="text-center mb-6">
                    <h2 class="flatsome-section-title text-xl sm:text-2xl font-extrabold text-navy uppercase tracking-tight">
                        Các Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                        Tổng hợp hình ảnh thực tế các dự án xây dựng dân dụng, khách sạn, căn hộ và hạ tầng thương mại do Triệu Vũ triển khai trên địa bàn TP Đà Nẵng.
                    </p>
                </div>

                <!-- Bộ lọc khu vực Đà Nẵng gọn đẹp, không xuống dòng tên danh mục -->
                <div id="danangFilterBar" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                    <button type="button" data-area="all" onclick="filterDaNang('all')"
                            class="dn-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-navy text-white border border-navy">
                        Tất cả dự án Đà Nẵng
                    </button>
                    <button type="button" data-area="son-tra" onclick="filterDaNang('son-tra')"
                            class="dn-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-white text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Sơn Trà
                    </button>
                    <button type="button" data-area="hai-chau" onclick="filterDaNang('hai-chau')"
                            class="dn-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-white text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Hải Châu
                    </button>
                    <button type="button" data-area="ngu-hanh-son" onclick="filterDaNang('ngu-hanh-son')"
                            class="dn-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-white text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Ngũ Hành Sơn
                    </button>
                    <button type="button" data-area="cam-le" onclick="filterDaNang('cam-le')"
                            class="dn-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-white text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200">
                        Cẩm Lệ – Hòa Xuân
                    </button>
                </div>

                <!-- Lưới 10 dự án Đà Nẵng: 2 cột mobile, 5 cột desktop lớn (chia đều 2 hàng x 5 ảnh cực đẹp) -->
                <div id="danangGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Dữ liệu render bằng JS từ đúng 10 link ảnh Google Drive của người dùng -->
                </div>
            </div>
        </section>

        <!-- =========================================================
             8. BẢNG BÁO GIÁ THAM KHẢO & FORM YÊU CẦU TƯ VẤN BÁO GIÁ TRANG CHỦ
        ========================================================== -->
        <section id="bao-gia" class="py-10 sm:py-14 bg-white">
            <div class="tv-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-section-title text-xl sm:text-2xl font-extrabold text-navy uppercase tracking-tight">
                        Yêu Cầu Tư Vấn &amp; Báo Giá Miễn Phí
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                        Để lại thông tin công trình dự kiến, đội ngũ kỹ sư Triệu Vũ sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết nhanh nhất.
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-start">
                    <!-- Cột trái: Các gói báo giá tiêu biểu theo mẫu Tín Trường Thịnh -->
                    <div class="lg:col-span-5 space-y-3">
                        <div class="rounded-xl border border-slate-200 bg-slatebg p-4 sm:p-5">
                            <h3 class="text-sm sm:text-base font-bold text-navy mb-3 flex items-center gap-2">
                                <i class="fa-solid fa-clipboard-list text-gold"></i>
                                <span>Hạng Mục Báo Giá Minh Bạch</span>
                            </h3>
                            <div class="divide-y divide-slate-200 text-xs sm:text-sm">
                                <div class="py-2.5 flex items-center justify-between gap-2">
                                    <span class="font-medium text-slate-700">Thiết kế Kiến trúc – Kết cấu</span>
                                    <span class="font-bold text-navy whitespace-nowrap">Từ 120.000đ/m²</span>
                                </div>
                                <div class="py-2.5 flex items-center justify-between gap-2">
                                    <span class="font-medium text-slate-700">Thi công Phần thô &amp; Nhân công</span>
                                    <span class="font-bold text-navy whitespace-nowrap">Từ 3.600.000đ/m²</span>
                                </div>
                                <div class="py-2.5 flex items-center justify-between gap-2">
                                    <span class="font-medium text-slate-700">Thi công Hoàn thiện Chìa khóa trao tay</span>
                                    <span class="font-bold text-navy whitespace-nowrap">Từ 5.800.000đ/m²</span>
                                </div>
                                <div class="py-2.5 flex items-center justify-between gap-2">
                                    <span class="font-medium text-slate-700">Cải tạo, sửa chữa &amp; Nội thất</span>
                                    <span class="font-bold text-gold whitespace-nowrap">Khảo sát thực tế</span>
                                </div>
                            </div>
                        </div>

                        <div class="rounded-xl bg-navy text-white p-5">
                            <div class="text-xs uppercase tracking-wider text-gold-light font-bold mb-1">Hỗ trợ trực tiếp 24/7</div>
                            <div class="text-base sm:text-lg font-bold mb-2">Khảo sát công trình miễn phí tại Đà Nẵng</div>
                            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-4">
                                Tư vấn xin giấy phép xây dựng, tối ưu phương án kết cấu móng và bóc tách khối lượng vật tư rõ ràng trước khi ký hợp đồng.
                            </p>
                            <a href="tel:0912164990" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-lg bg-gold hover:bg-gold-light text-white text-xs sm:text-sm font-bold transition">
                                <i class="fa-solid fa-phone-volume"></i>
                                <span>Hotline: 0912.164.990</span>
                            </a>
                        </div>
                    </div>

                    <!-- Cột phải: Form Yêu cầu & Báo giá Trang chủ -->
                    <div class="lg:col-span-7">
                        <form id="quoteForm" class="rounded-xl border border-slate-200 bg-white p-5 sm:p-7 shadow-sm">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mb-4">
                                <div>
                                    <label for="qName" class="block text-xs sm:text-sm font-semibold text-navy mb-1.5">Họ và tên *</label>
                                    <input id="qName" type="text" required placeholder="Nhập họ tên của bạn"
                                           class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy focus:ring-2 focus:ring-navy/15">
                                </div>
                                <div>
                                    <label for="qPhone" class="block text-xs sm:text-sm font-semibold text-navy mb-1.5">Số điện thoại *</label>
                                    <input id="qPhone" type="tel" required placeholder="VD: 0912.xxx.xxx"
                                           class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy focus:ring-2 focus:ring-navy/15">
                                </div>
                                <div>
                                    <label for="qEmail" class="block text-xs sm:text-sm font-semibold text-navy mb-1.5">Email</label>
                                    <input id="qEmail" type="email" placeholder="example@gmail.com"
                                           class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy focus:ring-2 focus:ring-navy/15">
                                </div>
                                <div>
                                    <label for="qType" class="block text-xs sm:text-sm font-semibold text-navy mb-1.5">Loại công trình</label>
                                    <select id="qType" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-navy focus:ring-2 focus:ring-navy/15">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Khách sạn – Căn hộ cho thuê">Khách sạn – Căn hộ cho thuê</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Văn phòng – Showroom">Văn phòng – Showroom</option>
                                        <option value="Thi công phần thô">Thi công phần thô</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="qBudget" class="block text-xs sm:text-sm font-semibold text-navy mb-1.5">Mức đầu tư dự kiến</label>
                                    <select id="qBudget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-navy focus:ring-2 focus:ring-navy/15">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                        <option value="2 tỷ - 4 tỷ">2 tỷ – 4 tỷ</option>
                                        <option value="Trên 4 tỷ">Trên 4 tỷ</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="qLocation" class="block text-xs sm:text-sm font-semibold text-navy mb-1.5">Khu vực xây dựng</label>
                                    <input id="qLocation" type="text" placeholder="VD: Sơn Trà, Đà Nẵng"
                                           class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy focus:ring-2 focus:ring-navy/15">
                                </div>
                            </div>

                            <div class="mb-4">
                                <label for="qNote" class="block text-xs sm:text-sm font-semibold text-navy mb-1.5">Yêu cầu chi tiết (diện tích, số tầng...)</label>
                                <textarea id="qNote" rows="3" placeholder="VD: Đất 5x20m, xây nhà phố 3 tầng trọn gói..."
                                          class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-navy focus:ring-2 focus:ring-navy/15"></textarea>
                            </div>

                            <!-- Thông báo gửi form thành công (không dùng alert()) -->
                            <div id="quoteFeedback" class="hidden mb-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>

                            <button type="submit" class="w-full sm:w-auto px-7 py-3 rounded-lg bg-navy hover:bg-navy-light text-white text-sm font-bold transition shadow-sm inline-flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane text-gold-light"></i>
                                <span>Gửi Yêu Cầu Báo Giá Ngay</span>
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================
             9. DANH MỤC CÁC ĐỐI TÁC (Thương hiệu vật tư & đối tác chiến lược)
        ========================================================== -->
        <section id="doi-tac" class="py-10 sm:py-12 bg-slatebg border-y border-slate-200/70">
            <div class="tv-container">
                <div class="text-center mb-7">
                    <h2 class="flatsome-section-title text-xl sm:text-2xl font-extrabold text-navy uppercase tracking-tight">
                        Đối Tác &amp; Nhà Cung Cấp Chiến Lược
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                        Hợp tác cùng các thương hiệu vật liệu xây dựng hàng đầu, đảm bảo chất lượng đồng bộ cho mọi công trình.
                    </p>
                </div>

                <!-- 2 cột trên mobile, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-4">
                    <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 sm:py-5 flex flex-col items-center justify-center text-center hover:border-gold transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy">HÒA PHÁT</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng tiêu chuẩn</div>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 sm:py-5 flex flex-col items-center justify-center text-center hover:border-gold transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy">SÔNG GIANH</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Xi măng chất lượng cao</div>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 sm:py-5 flex flex-col items-center justify-center text-center hover:border-gold transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy">DULUX</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất cao cấp</div>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 sm:py-5 flex flex-col items-center justify-center text-center hover:border-gold transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy">CADIVI</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Dây cáp điện an toàn</div>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 sm:py-5 flex flex-col items-center justify-center text-center hover:border-gold transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy">NHỰA BÌNH MINH</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Hệ thống ống cấp thoát nước</div>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 sm:py-5 flex flex-col items-center justify-center text-center hover:border-gold transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy">TOTO</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh hiện đại</div>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 sm:py-5 flex flex-col items-center justify-center text-center hover:border-gold transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy">ĐỒNG TÂM</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát &amp; ngói màu</div>
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 px-3 py-4 sm:py-5 flex flex-col items-center justify-center text-center hover:border-gold transition">
                        <div class="text-sm sm:text-base font-extrabold tracking-tight text-navy">AN CƯỜNG</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Vật liệu gỗ nội thất</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- =========================================================
             10. DANH MỤC BÀI VIẾT / TIN TỨC TRANG CHỦ
        ========================================================== -->
        <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
            <div class="tv-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-section-title text-xl sm:text-2xl font-extrabold text-navy uppercase tracking-tight">
                        Tin Tức &amp; Cẩm Nang Xây Dựng
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                        Chia sẻ kinh nghiệm thiết kế, quy trình giám sát kỹ thuật và mẹo tối ưu chi phí khi xây dựng tại Đà Nẵng.
                    </p>
                </div>

                <!-- 2 cột mobile, 4 cột desktop -->
                <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Render bằng JS để mở đọc bài viết trực tiếp -->
                </div>
            </div>
        </section>

        <!-- =========================================================
             11. GOOGLE MAP & FANPAGE NGAY NGOÀI TRANG CHỦ
        ========================================================== -->
        <section id="lien-he" class="py-10 sm:py-14 bg-slatebg border-t border-slate-200">
            <div class="tv-container">
                <div class="text-center mb-8">
                    <h2 class="flatsome-section-title text-xl sm:text-2xl font-extrabold text-navy uppercase tracking-tight">
                        Bản Đồ Trụ Sở &amp; Kết Nối Fanpage
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                        Mời Quý khách hàng đến trực tiếp văn phòng Triệu Vũ tại Sơn Trà, Đà Nẵng hoặc theo dõi cập nhật công trình mới nhất trên Fanpage.
                    </p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
                    <!-- Bản đồ Google Maps ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
                            <div class="flex items-center gap-2 text-navy font-bold text-xs sm:text-sm">
                                <i class="fa-solid fa-map-location-dot text-gold"></i>
                                <span>K39/16 Lê Văn Thứ, Phường Sơn Trà, TP Đà Nẵng</span>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=K39%2F16+L%C3%AA+V%C4%83n+Th%E1%BB%A9,+S%C6%A1n+Tr%C3%A0,+%C4%90%C3%A0+N%E1%BA%B5ng"
                               target="_blank" rel="noopener noreferrer"
                               class="text-xs font-semibold text-gold hover:text-navy transition whitespace-nowrap">
                                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>
                        <div class="w-full h-[300px] sm:h-[360px] flex-1 bg-slate-100">
                            <iframe
                                title="Bản đồ Công ty Cổ phần Xây dựng và Thương mại Triệu Vũ - K39/16 Lê Văn Thứ, Sơn Trà, Đà Nẵng"
                                src="https://maps.google.com/maps?q=K39%2F16+L%C3%AA+V%C4%83n+Th%E1%BB%A9,+S%C6%A1n+Tr%C3%A0,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"
                                allowfullscreen>
                            </iframe>
                        </div>
                    </div>

                    <!-- Fanpage chính thức ngay ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-slate-100 flex items-center justify-between">
                            <div class="flex items-center gap-2 text-navy font-bold text-xs sm:text-sm">
                                <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                                <span>Fanpage Chính Thức</span>
                            </div>
                            <span class="text-[11px] font-medium text-slate-500">trieuvu.com</span>
                        </div>

                        <!-- Khung giao diện Fanpage Facebook tích hợp sẵn ảnh bìa, logo & nút tương tác -->
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div class="rounded-lg border border-slate-200 overflow-hidden bg-white">
                                <div class="relative h-32 sm:h-36 bg-navy">
                                    <img src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w1000"
                                         data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                         onerror="handleDriveImgError(this, 'Fanpage Xay Dung Trieu Vu')"
                                         alt="Ảnh bìa Fanpage Xây Dựng Triệu Vũ"
                                         class="w-full h-full object-cover opacity-80">
                                    <div class="absolute inset-0 bg-gradient-to-t from-navy/90 via-navy/40 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                        <div class="w-12 h-12 rounded-lg bg-navy border-2 border-white flex items-center justify-center shrink-0 shadow">
                                            <svg class="w-9 h-9" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <path d="M12 31L32 13L52 31" stroke="#E8A338" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                                                <path d="M19 32H45" stroke="#FFFFFF" stroke-width="3.2" stroke-linecap="round"/>
                                                <path d="M25 32V49" stroke="#FFFFFF" stroke-width="3.5" stroke-linecap="round"/>
                                                <path d="M33 32L38.5 48.5L44 32" stroke="#E8A338" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round"/>
                                            </svg>
                                        </div>
                                        <div class="min-w-0">
                                            <div class="text-white font-bold text-xs sm:text-sm leading-tight">
                                                Xây Dựng &amp; Thương Mại Triệu Vũ
                                            </div>
                                            <div class="text-[11px] text-slate-200 mt-0.5">
                                                Công ty Xây dựng • TP Đà Nẵng
                                            </div>
                                        </div>
                                    </div>
                                </div>

                                <div class="p-3.5 bg-slatebg/60">
                                    <p class="text-xs text-slate-700 leading-relaxed mb-3">
                                        Cập nhật liên tục hình ảnh nghiệm thu đổ bê tông, tiến độ công trình nhà phố, căn hộ và báo giá vật tư mới nhất tại Đà Nẵng.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-2">
                                        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer"
                                           class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-[#1877F2] hover:bg-[#1465D1] text-white text-xs font-bold transition">
                                            <i class="fa-brands fa-facebook-f"></i>
                                            <span>Theo Dõi Fanpage</span>
                                        </a>
                                        <a href="https://zalo.me/0912164990" target="_blank" rel="noopener noreferrer"
                                           class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-white hover:bg-slate-50 text-navy border border-slate-300 text-xs font-bold transition">
                                            <i class="fa-solid fa-comment-dots text-[#0068FF]"></i>
                                            <span>Nhắn Tin Tư Vấn</span>
                                        </a>
                                    </div>
                                </div>
                            </div>

                            <div class="mt-4 pt-3 border-t border-slate-100 text-xs text-slate-600 space-y-1.5">
                                <div class="flex items-start gap-2">
                                    <i class="fa-solid fa-clock text-gold mt-0.5"></i>
                                    <span>Giờ làm việc: Thứ 2 – Thứ 7 (07:30 – 17:30)</span>
                                </div>
                                <div class="flex items-start gap-2">
                                    <i class="fa-solid fa-phone text-gold mt-0.5"></i>
                                    <span>Hotline &amp; Zalo: <strong class="text-navy">0912.164.990</strong></span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- =========================================================
         12. FOOTER CHUẨN FLATSOME
    ========================================================== -->
    <footer class="bg-navy-dark text-slate-300 pt-10 pb-20 sm:pb-8">
        <div class="tv-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-2.5 mb-3">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect x="2" y="2" width="60" height="60" rx="12" fill="#0E2A47"/>
                            <rect x="4" y="4" width="56" height="56" rx="10" stroke="#D98A1C" stroke-width="1.5" stroke-opacity="0.5"/>
                            <path d="M12 31L32 13L52 31" stroke="#E8A338" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M19 32H45" stroke="#FFFFFF" stroke-width="3.2" stroke-linecap="round"/>
                            <path d="M25 32V49" stroke="#FFFFFF" stroke-width="3.5" stroke-linecap="round"/>
                            <path d="M33 32L38.5 48.5L44 32" stroke="#E8A338" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <div>
                            <div class="text-white font-extrabold text-sm sm:text-base leading-tight">
                                CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI TRIỆU VŨ
                            </div>
                            <div class="text-[11px] text-gold-light font-semibold">trieuvu.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-gold-light mt-1"></i>
                            <span>Trụ sở: K39/16 Lê Văn Thứ, Phường Sơn Trà, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-gold-light"></i>
                            <span>Hotline / Zalo: <a href="tel:0912164990" class="text-white font-semibold hover:text-gold-light">0912.164.990</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-gold-light"></i>
                            <span>Website: <a href="https://trieuvu.com" class="text-white hover:text-gold-light">trieuvu.com</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-file-contract text-gold-light"></i>
                            <span>Mã số thuế: 0401974553</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wide mb-3">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li><a href="#linh-vuc" class="hover:text-gold-light transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc" class="hover:text-gold-light transition">Thi công phần thô chuẩn kỹ thuật</a></li>
                        <li><a href="#linh-vuc" class="hover:text-gold-light transition">Thi công hoàn thiện trọn gói</a></li>
                        <li><a href="#linh-vuc" class="hover:text-gold-light transition">Thi công nội thất &amp; Cải tạo</a></li>
                        <li><a href="#doi-tac" class="hover:text-gold-light transition">Cung ứng vật tư xây dựng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục nhanh -->
                <div class="lg:col-span-4">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wide mb-3">Danh Mục Trang Chủ</h4>
                    <div class="grid grid-cols-2 gap-2 text-xs sm:text-[13px]">
                        <a href="#gioi-thieu" class="hover:text-gold-light transition">Giới thiệu công ty</a>
                        <a href="#cong-trinh-thuc-te" class="hover:text-gold-light transition">Công trình thực tế</a>
                        <a href="#du-an-da-nang" class="hover:text-gold-light transition">Dự án Đà Nẵng</a>
                        <a href="#bao-gia" class="hover:text-gold-light transition">Yêu cầu báo giá</a>
                        <a href="#doi-tac" class="hover:text-gold-light transition">Đối tác chiến lược</a>
                        <a href="#tin-tuc" class="hover:text-gold-light transition">Tin tức xây dựng</a>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>© 2026 CÔNG TY CỔ PHẦN XÂY DỰNG VÀ THƯƠNG MẠI TRIỆU VŨ (trieuvu.com).</div>
                <div>Thiết kế tối ưu chuẩn Flatsome UX Builder.</div>
            </div>
        </div>
    </footer>

    <!-- =========================================================
         13. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
             - Tương thích hoàn hảo trên cả máy tính và điện thoại
             - Không gây tràn viền ngang
    ========================================================== -->
    <!-- Phiên bản Máy tính & Tablet: Cố định gọn đẹp góc phải dưới -->
    <div class="hidden sm:flex fixed right-4 bottom-5 z-50 flex-col gap-2.5 items-end">
        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D1] text-white px-3.5 py-2.5 rounded-full shadow-lg transition">
            <i class="fa-brands fa-facebook-f w-5 text-center text-sm"></i>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>
        <a href="https://zalo.me/0912164990" target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white px-3.5 py-2.5 rounded-full shadow-lg transition">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] inline-flex items-center justify-center">Z</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>
        <a href="tel:0912164990"
           class="btn-hotline-pulse flex items-center gap-2 bg-gold hover:bg-gold-light text-white px-4 py-2.5 rounded-full shadow-lg transition">
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs font-extrabold whitespace-nowrap">0912.164.990</span>
        </a>
    </div>

    <!-- Phiên bản Điện thoại: Thanh liên hệ nổi cố định đáy màn hình chia 3 nút đều nhau, không tràn viền -->
    <div class="sm:hidden fixed bottom-0 left-0 right-0 z-50 bg-white/95 backdrop-blur border-t border-slate-200 px-2 py-2 shadow-[0_-4px_12px_rgba(0,0,0,0.08)]">
        <div class="grid grid-cols-3 gap-2">
            <a href="https://zalo.me/0912164990" target="_blank" rel="noopener noreferrer"
               class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-[#0068FF] text-white text-xs font-bold">
                <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] font-extrabold text-[9px] inline-flex items-center justify-center">Z</span>
                <span>Zalo</span>
            </a>
            <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer"
               class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-[#1877F2] text-white text-xs font-bold">
                <i class="fa-brands fa-facebook-f text-xs"></i>
                <span>Facebook</span>
            </a>
            <a href="tel:0912164990"
               class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-gold text-white text-xs font-extrabold">
                <i class="fa-solid fa-phone-volume text-xs"></i>
                <span>Hotline</span>
            </a>
        </div>
    </div>

    <!-- =========================================================
         14. MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH / BÀI VIẾT
    ========================================================== -->
    <div id="detailModal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-sm p-3 sm:p-6 flex items-center justify-center">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="sticky top-0 bg-white px-4 sm:px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
                <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-navy leading-snug">Chi tiết</h3>
                <button id="closeModalBtn" type="button" class="w-8 h-8 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0" aria-label="Đóng cửa sổ">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modalBody" class="p-4 sm:p-5"></div>
        </div>
    </div>

    <!-- =========================================================
         15. JAVASCRIPT XỬ LÝ TƯƠNG TÁC, DỮ LIỆU ẢNH GOOGLE DRIVE & SLIDER
    ========================================================== -->
    <script>
        /**
         * Hàm xử lý fallback thông minh cho link ảnh Google Drive:
         * 1. Thử tải ảnh trực tiếp qua lh3.googleusercontent.com/d/{ID}
         * 2. Nếu lỗi, tự động chuyển qua drive.google.com/thumbnail?id={ID}&sz=w1000
         * 3. Nếu file chưa bật quyền công khai, hiển thị ảnh placeholder sạch theo bộ màu Triệu Vũ
         */
        function handleDriveImgError(imgEl, fallbackLabel) {
            const driveId = imgEl.getAttribute('data-drive-id');
            const step = Number(imgEl.getAttribute('data-fallback-step') || 0);
            if (step === 0 && driveId) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
            } else if (step === 1) {
                imgEl.setAttribute('data-fallback-step', '2');
                const safeText = encodeURIComponent(fallbackLabel || 'Xay Dung Trieu Vu');
                imgEl.src = 'https://placehold.co/800x600/0E2A47/E8A338?text=' + safeText;
            }
        }

        function getDriveImgUrl(id) {
            return 'https://lh3.googleusercontent.com/d/' + id + '=w1000';
        }

        /* ----------------------------------------------------------------
           Dữ liệu 9 ảnh thi công thực tế từ đúng 9 link Google Drive của bạn
           Phân loại sát theo danh mục web mẫu tintruongthinh.com
        ----------------------------------------------------------------- */
        const actualWorks = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô & Kết Cấu Khung Bê Tông Nhà Phố',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Triển khai thi công hệ thống cốt thép dầm sàn, ghép cốp pha và nghiệm thu đổ bê tông đúng tiêu chuẩn kỹ thuật xây dựng.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Trọn Gói Nhà Phố Hiện Đại 3 Tầng',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                location: 'Khu đô thị Hòa Xuân, Đà Nẵng',
                desc: 'Công trình nhà phố thiết kế thông thoáng, thi công trọn gói từ phần móng đến hoàn thiện mặt tiền sắc nét.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi Công Hoàn Thiện Khách Sạn – Căn Hộ Cho Thuê',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn – Căn hộ',
                location: 'Khu vực biển Mỹ Khê, Đà Nẵng',
                desc: 'Hoàn thiện tổ hợp căn hộ dịch vụ và khách sạn tiêu chuẩn hiện đại, tối ưu công năng khai thác lưu trú.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Kết Cấu Biệt Thự 2 Mặt Tiền',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Thi công phần thô và tạo hình kiến trúc biệt thự sân vườn, kiểm soát chặt chẽ độ bền kết cấu và chống thấm.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Xây Tô & Hệ Thống Kỹ Thuật Điện Nước',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                location: 'Quận Hải Châu, TP Đà Nẵng',
                desc: 'Xây tường gạch đúng mạch, lắp đặt hệ thống ống điện nước âm tường chuẩn bản vẽ kỹ thuật M&E.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Hoàn Thiện Mặt Tiền & Ốp Lát Công Trình Văn Phòng',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                location: 'Trung tâm TP Đà Nẵng',
                desc: 'Thi công hoàn thiện không gian văn phòng làm việc, ốp lát đá và sơn nước cao cấp đồng bộ thẩm mỹ.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi Công Hoàn Thiện Nội Ngoại Thất Nhà Phố',
                category: 'hoan-thien',
                categoryLabel: 'Thi công hoàn thiện',
                location: 'Phường Mân Thái, Sơn Trà, Đà Nẵng',
                desc: 'Hạng mục hoàn thiện trần thạch cao, chiếu sáng, sơn hoàn thiện và lắp đặt thiết bị vệ sinh chính hãng.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Tòa Nhà Căn Hộ Dịch Vụ Cao Tầng',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn – Căn hộ',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Triển khai hệ giàn giáo an toàn, thi công kết cấu tầng cao đảm bảo tiến độ và chất lượng bề mặt bê tông.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Hoàn Thiện Biệt Thự Phố & Hạng Mục Sân Vườn',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                location: 'Nam Việt Á, Đà Nẵng',
                desc: 'Bàn giao công trình biệt thự hoàn thiện chỉn chu từ kiến trúc ngoại thất đến không gian sinh hoạt bên trong.'
            }
        ];

        /* ----------------------------------------------------------------
           Dữ liệu 10 dự án tại Đà Nẵng từ đúng 10 link Google Drive của bạn
        ----------------------------------------------------------------- */
        const daNangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Dự Án Căn Hộ – Khách Sạn Ven Biển Sơn Trà',
                area: 'son-tra',
                areaLabel: 'Sơn Trà, Đà Nẵng',
                desc: 'Công trình căn hộ lưu trú cao cấp khu vực bán đảo Sơn Trà do Triệu Vũ trực tiếp thi công và giám sát.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Dự Án Nhà Phố Thương Mại Đường Lê Văn Thứ',
                area: 'son-tra',
                areaLabel: 'Sơn Trà, Đà Nẵng',
                desc: 'Thiết kế và thi công trọn gói nhà phố kết hợp kinh doanh với mặt tiền hiện đại, tối ưu ánh sáng tự nhiên.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Dự Án Biệt Thự Nghỉ Dưỡng Ngũ Hành Sơn',
                area: 'ngu-hanh-son',
                areaLabel: 'Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Thi công phần thô và hoàn thiện biệt thự nghỉ dưỡng tiêu chuẩn cao, không gian mở gần gũi thiên nhiên.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Dự Án Tòa Nhà Văn Phòng Quận Hải Châu',
                area: 'hai-chau',
                areaLabel: 'Hải Châu, Đà Nẵng',
                desc: 'Thi công kết cấu và hoàn thiện khối văn phòng làm việc tại trung tâm hành chính quận Hải Châu.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Dự Án Nhà Phố 3 Tầng Khu Đô Thị Hòa Xuân',
                area: 'cam-le',
                areaLabel: 'Cẩm Lệ – Hòa Xuân',
                desc: 'Thi công nhà ở gia đình trọn gói với vật tư chính hãng, hoàn thành đúng tiến độ cam kết với chủ đầu tư.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Dự Án Căn Hộ Cho Thuê Khu Vực An Thượng',
                area: 'ngu-hanh-son',
                areaLabel: 'Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Xây dựng tổ hợp căn hộ dịch vụ đầy đủ tiện nghi phục vụ khách du lịch và chuyên gia tại Đà Nẵng.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Dự Án Nhà Phố Hiện Đại Phường Mân Thái',
                area: 'son-tra',
                areaLabel: 'Sơn Trà, Đà Nẵng',
                desc: 'Hạng mục thi công trọn gói nhà phố khu dân cư ven biển Sơn Trà, chú trọng giải pháp chống thấm và thông gió.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Dự Án Cải Tạo & Hoàn Thiện Showroom Hải Châu',
                area: 'hai-chau',
                areaLabel: 'Hải Châu, Đà Nẵng',
                desc: 'Cải tạo nâng cấp mặt bằng kinh doanh, thi công trần vách và hệ thống chiếu sáng chuyên nghiệp.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Dự Án Biệt Thự Khu Sinh Thái Hòa Xuân',
                area: 'cam-le',
                areaLabel: 'Cẩm Lệ – Hòa Xuân',
                desc: 'Thi công kiến trúc biệt thự hiện đại ven sông, đảm bảo kết cấu móng cọc vững chắc và hoàn thiện tinh tế.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Dự Án Công Trình Dân Dụng & Thương Mại Đà Nẵng',
                area: 'hai-chau',
                areaLabel: 'TP Đà Nẵng',
                desc: 'Thi công đồng bộ hạ tầng kỹ thuật và không gian thương mại đạt chuẩn an toàn lao động, nghiệm thu bàn giao chất lượng cao.'
            }
        ];

        /* ----------------------------------------------------------------
           Dữ liệu bài viết trang chủ (đồng bộ chủ đề xây dựng Đà Nẵng)
        ----------------------------------------------------------------- */
        const articlesData = [
            {
                imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                date: '15/11/2026',
                title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật sau khi đổ',
                excerpt: 'Quy trình tưới ẩm và che phủ bê tông trong 7 ngày đầu giúp hạn chế nứt bề mặt và đạt cường độ chịu lực tối đa.',
                content: 'Bảo dưỡng bê tông là khâu quan trọng quyết định trực tiếp đến tuổi thọ kết cấu ngôi nhà. Sau khi đổ bê tông từ 4 đến 6 giờ, cần tiến hành phủ bao tải ẩm hoặc bạt giữ ẩm, tưới nước phun sương đều đặn 3–4 lần/ngày trong suốt 7 ngày đầu tiên, đặc biệt trong điều kiện thời tiết nắng gió tại miền Trung và Đà Nẵng.'
            },
            {
                imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                date: '08/11/2026',
                title: 'Kinh nghiệm lựa chọn nhà thầu xây nhà trọn gói uy tín tại Đà Nẵng',
                excerpt: 'Những tiêu chí cốt lõi về năng lực thi công, bảng dự toán vật tư và hợp đồng bảo hành chủ đầu tư cần nắm rõ.',
                content: 'Khi lựa chọn đơn vị xây nhà trọn gói tại Đà Nẵng, chủ đầu tư nên kiểm tra kỹ các công trình thực tế nhà thầu đã thi công, yêu cầu bảng chủng loại vật tư rõ thương hiệu (thép, xi măng, dây điện, ống nước), tiến độ thanh toán theo từng giai đoạn nghiệm thu và điều khoản cam kết không phát sinh chi phí.'
            },
            {
                imgId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                date: '29/10/2026',
                title: 'Giải pháp chống thấm hiệu quả cho nhà phố khu vực ven biển Sơn Trà',
                excerpt: 'Xử lý chống thấm sân thượng, tường ngoài và khu vệ sinh giúp công trình bền đẹp trước thời tiết mưa bão.',
                content: 'Khí hậu ven biển Đà Nẵng có độ ẩm và lượng mưa lớn vào cuối năm. Để ngăn ngừa thấm dột, Triệu Vũ luôn áp dụng quy trình chống thấm đa lớp cho sàn mái, ban công, cổ ống xuyên sàn và sử dụng sơn ngoại thất kháng kiềm, chống muối mặn cho toàn bộ mặt tiền.'
            },
            {
                imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                date: '18/10/2026',
                title: '3 lưu ý quan trọng giúp tối ưu chi phí khi thiết kế nhà phố và căn hộ',
                excerpt: 'Lập hồ sơ thiết kế chi tiết trước khi khởi công giúp tránh đập phá sửa đổi và kiểm soát ngân sách hiệu quả.',
                content: 'Một bản vẽ thiết kế kiến trúc – kết cấu – điện nước đầy đủ ngay từ đầu sẽ giúp chủ đầu tư hình dung rõ công năng từng phòng, dự trù chính xác khối lượng vật tư và hạn chế tối đa chi phí phát sinh trong suốt quá trình thi công thực tế.'
            }
        ];

        /* ----------------------------------------------------------------
           Render Công trình thực tế (2 cột mobile, KHÔNG nhãn dán, tên đầy đủ)
        ----------------------------------------------------------------- */
        function renderWorks(filterKey) {
            const grid = document.getElementById('worksGrid');
            const filtered = filterKey === 'all'
                ? actualWorks
                : actualWorks.filter(item => item.category === filterKey);

            grid.innerHTML = filtered.map((item, idx) => `
                <article onclick="openImageModal('${item.id}', '${item.title.replace(/'/g, "\\'")}', '${item.location.replace(/'/g, "\\'")}', '${item.desc.replace(/'/g, "\\'")}')"
                         class="group cursor-pointer rounded-xl border border-slate-200 bg-white overflow-hidden hover:border-gold hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="${getDriveImgUrl(item.id)}"
                             data-drive-id="${item.id}"
                             onerror="handleDriveImgError(this, 'Cong Trinh Trieu Vu ${idx + 1}')"
                             alt="${item.title}"
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300">
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12.5px] sm:text-[14px] font-bold text-navy group-hover:text-gold leading-snug break-words mb-1.5">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 flex items-center gap-1">
                            <i class="fa-solid fa-location-dot text-gold text-[10px] shrink-0"></i>
                            <span class="break-words">${item.location}</span>
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterWorks(filterKey) {
            document.querySelectorAll('.work-tab-btn').forEach(btn => {
                const isActive = btn.getAttribute('data-filter') === filterKey;
                btn.className = isActive
                    ? 'work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-navy text-white border border-navy'
                    : 'work-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-slatebg text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200';
            });
            renderWorks(filterKey);
        }

        /* ----------------------------------------------------------------
           Render 10 Dự án tại Đà Nẵng (2 cột mobile, KHÔNG nhãn dán, tên đầy đủ)
        ----------------------------------------------------------------- */
        function renderDaNang(areaKey) {
            const grid = document.getElementById('danangGrid');
            const filtered = areaKey === 'all'
                ? daNangProjects
                : daNangProjects.filter(item => item.area === areaKey);

            grid.innerHTML = filtered.map((item, idx) => `
                <article onclick="openImageModal('${item.id}', '${item.title.replace(/'/g, "\\'")}', '${item.areaLabel.replace(/'/g, "\\'")}', '${item.desc.replace(/'/g, "\\'")}')"
                         class="group cursor-pointer rounded-xl border border-slate-200 bg-white overflow-hidden hover:border-gold hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="${getDriveImgUrl(item.id)}"
                             data-drive-id="${item.id}"
                             onerror="handleDriveImgError(this, 'Du An Da Nang ${idx + 1}')"
                             alt="${item.title}"
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-navy group-hover:text-gold leading-snug break-words mb-1.5">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] text-slate-500 flex items-center gap-1">
                            <i class="fa-solid fa-location-dot text-gold text-[10px] shrink-0"></i>
                            <span class="break-words">${item.areaLabel}</span>
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterDaNang(areaKey) {
            document.querySelectorAll('.dn-tab-btn').forEach(btn => {
                const isActive = btn.getAttribute('data-area') === areaKey;
                btn.className = isActive
                    ? 'dn-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-navy text-white border border-navy'
                    : 'dn-tab-btn px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-semibold whitespace-nowrap transition bg-white text-slate-700 hover:bg-gold-soft hover:text-navy border border-slate-200';
            });
            renderDaNang(areaKey);
        }

        /* ----------------------------------------------------------------
           Render Danh mục bài viết trang chủ
        ----------------------------------------------------------------- */
        function renderArticles() {
            const grid = document.getElementById('articlesGrid');
            grid.innerHTML = articlesData.map((art, idx) => `
                <article onclick="openArticleModal(${idx})"
                         class="group cursor-pointer rounded-xl border border-slate-200 bg-white overflow-hidden hover:border-gold hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="${getDriveImgUrl(art.imgId)}"
                             data-drive-id="${art.imgId}"
                             onerror="handleDriveImgError(this, 'Tin Tuc Xay Dung')"
                             alt="${art.title}"
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col">
                        <div class="text-[11px] text-slate-400 font-medium mb-1">
                            <i class="fa-regular fa-calendar mr-1 text-gold"></i>${art.date}
                        </div>
                        <h3 class="text-[12.5px] sm:text-[14px] font-bold text-navy group-hover:text-gold leading-snug break-words mb-2">
                            ${art.title}
                        </h3>
                        <p class="hidden sm:block text-xs text-slate-600 leading-relaxed flex-1">
                            ${art.excerpt}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* ----------------------------------------------------------------
           Modal xem ảnh thực tế & bài viết chi tiết
        ----------------------------------------------------------------- */
        const detailModal = document.getElementById('detailModal');
        const modalTitle = document.getElementById('modalTitle');
        const modalBody = document.getElementById('modalBody');

        function openImageModal(driveId, title, location, desc) {
            modalTitle.textContent = title;
            modalBody.innerHTML = `
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4 border border-slate-200">
                    <img src="${getDriveImgUrl(driveId)}"
                         data-drive-id="${driveId}"
                         onerror="handleDriveImgError(this, 'Hinh Anh Thuc Te Trieu Vu')"
                         alt="${title}"
                         class="w-full max-h-[60vh] object-contain mx-auto bg-slate-900">
                </div>
                <div class="flex items-center gap-2 text-xs font-semibold text-gold mb-2">
                    <i class="fa-solid fa-location-dot"></i>
                    <span>${location}</span>
                </div>
                <p class="text-sm text-slate-700 leading-relaxed mb-5">${desc}</p>
                <div class="flex flex-wrap items-center gap-2.5">
                    <a href="#bao-gia" onclick="closeModal()" class="px-4 py-2.5 rounded-lg bg-navy hover:bg-navy-light text-white text-xs sm:text-sm font-bold transition">
                        Nhận Báo Giá Hạng Mục Tương Tự
                    </a>
                    <a href="tel:0912164990" class="px-4 py-2.5 rounded-lg bg-gold hover:bg-gold-light text-white text-xs sm:text-sm font-bold transition">
                        Gọi 0912.164.990
                    </a>
                </div>
            `;
            detailModal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function openArticleModal(index) {
            const art = articlesData[index];
            if (!art) return;
            modalTitle.textContent = art.title;
            modalBody.innerHTML = `
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4 border border-slate-200">
                    <img src="${getDriveImgUrl(art.imgId)}"
                         data-drive-id="${art.imgId}"
                         onerror="handleDriveImgError(this, 'Tin Tuc Trieu Vu')"
                         alt="${art.title}"
                         class="w-full max-h-72 object-cover">
                </div>
                <div class="text-xs text-slate-500 mb-3">
                    <i class="fa-regular fa-calendar text-gold mr-1"></i>Ngày đăng: ${art.date} • CÔNG TY CP XÂY DỰNG &amp; THƯƠNG MẠI TRIỆU VŨ
                </div>
                <p class="text-sm text-slate-700 leading-relaxed mb-3 font-medium">${art.excerpt}</p>
                <p class="text-sm text-slate-700 leading-relaxed mb-5">${art.content}</p>
                <div class="p-3.5 rounded-lg bg-slatebg border border-slate-200 text-xs sm:text-sm text-navy">
                    Cần tư vấn kỹ thuật chi tiết cho công trình của bạn? Liên hệ ngay Hotline/Zalo: <strong>0912.164.990</strong>.
                </div>
            `;
            detailModal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeModal() {
            detailModal.classList.add('hidden');
            document.body.style.overflow = '';
        }

        document.getElementById('closeModalBtn').addEventListener('click', closeModal);
        detailModal.addEventListener('click', function (e) {
            if (e.target === detailModal) closeModal();
        });

        /* ----------------------------------------------------------------
           Hero Slider 2 banner tự trượt chuyên nghiệp + Hỗ trợ vuốt cảm ứng
        ----------------------------------------------------------------- */
        (function initHeroSlider() {
            const slides = document.querySelectorAll('.hero-slide-item');
            const dots = document.querySelectorAll('.hero-dot');
            const sliderEl = document.getElementById('heroSlider');
            let currentSlide = 0;
            let timerId = null;

            function showSlide(index) {
                currentSlide = (index + slides.length) % slides.length;
                slides.forEach((slide, i) => {
                    slide.classList.toggle('active', i === currentSlide);
                });
                dots.forEach((dot, i) => {
                    if (i === currentSlide) {
                        dot.classList.remove('w-2.5', 'bg-white/55');
                        dot.classList.add('w-7', 'bg-gold');
                    } else {
                        dot.classList.remove('w-7', 'bg-gold');
                        dot.classList.add('w-2.5', 'bg-white/55');
                    }
                });
            }

            function startAutoPlay() {
                stopAutoPlay();
                timerId = setInterval(() => showSlide(currentSlide + 1), 5000);
            }

            function stopAutoPlay() {
                if (timerId) clearInterval(timerId);
            }

            document.getElementById('prevSlideBtn').addEventListener('click', () => {
                showSlide(currentSlide - 1);
                startAutoPlay();
            });
            document.getElementById('nextSlideBtn').addEventListener('click', () => {
                showSlide(currentSlide + 1);
                startAutoPlay();
            });
            dots.forEach(dot => {
                dot.addEventListener('click', () => {
                    showSlide(Number(dot.getAttribute('data-slide')));
                    startAutoPlay();
                });
            });

            // Hỗ trợ vuốt cảm ứng trên điện thoại
            let touchStartX = 0;
            sliderEl.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
                stopAutoPlay();
            }, { passive: true });
            sliderEl.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 40) {
                    showSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                }
                startAutoPlay();
            }, { passive: true });

            sliderEl.addEventListener('mouseenter', stopAutoPlay);
            sliderEl.addEventListener('mouseleave', startAutoPlay);

            startAutoPlay();
        })();

        /* ----------------------------------------------------------------
           Menu Mobile Toggle
        ----------------------------------------------------------------- */
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenuPanel = document.getElementById('mobileMenuPanel');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenuPanel.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => mobileMenuPanel.classList.add('hidden'));
        });

        /* ----------------------------------------------------------------
           Xử lý Form Yêu cầu & Báo giá trang chủ (không dùng alert())
        ----------------------------------------------------------------- */
        document.getElementById('quoteForm').addEventListener('submit', function (e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const type = document.getElementById('qType').value;
            const feedback = document.getElementById('quoteFeedback');

            feedback.textContent = 'Cảm ơn ' + name + '! Yêu cầu báo giá hạng mục "' + type + '" của bạn đã được ghi nhận. Kỹ sư Triệu Vũ sẽ liên hệ qua số ' + phone + ' trong thời gian sớm nhất.';
            feedback.classList.remove('hidden');
            this.reset();
        });

        /* Khởi tạo toàn bộ danh mục khi tải trang */
        window.addEventListener('DOMContentLoaded', function () {
            renderWorks('all');
            renderDaNang('all');
            renderArticles();
        });
    </script>
</body>
</html>
