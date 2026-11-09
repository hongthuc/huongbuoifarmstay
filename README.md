<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Hương Bưởi Farmstay - Khu Du Lịch Sinh Thái & Nghỉ Dưỡng Xanh Đà Nẵng</title>
    <meta name="description" content="Hương Bưởi Farmstay tại TDP Nam Yên, P. Hải Vân, Đà Nẵng. Điểm đến du lịch sinh thái vườn bưởi, lưu trú nhà sàn, lều Glamping, hồ bơi, ẩm thực bản địa và cắm trại lửa trại.">
    
    <!-- Open Graph / Thumbnail là Logo trang web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://huongbuoifarmstay.com/">
    <meta property="og:title" content="Hương Bưởi Farmstay - Du Lịch Sinh Thái & Nghỉ Dưỡng Xanh Đà Nẵng">
    <meta property="og:description" content="Trải nghiệm không gian vườn bưởi xanh mát, lưu trú nhà sàn, lều Glamping, hồ bơi ngoài trời và ẩm thực bản địa tại TDP Nam Yên, P. Hải Vân, Đà Nẵng. Hotline: 0704.447.876">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq" type="image/png">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        farm: {
                            50: '#f3f9f1',
                            100: '#e2f1dd',
                            200: '#c5e4bc',
                            500: '#3b8c32',
                            600: '#2d7226',
                            700: '#235a1e',
                            800: '#1b4618',
                            900: '#143512',
                        },
                        pomelo: {
                            400: '#facc15',
                            500: '#eab308',
                            600: '#ca8a04',
                        }
                    },
                    maxWidth: {
                        'flatsome': '1500px',
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f9fbf8;
            color: #1f2937;
            scroll-behavior: smooth;
        }

        /* Chuẩn khung Flatsome 1500px trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tối ưu tên danh mục trên máy tính: luôn viết liền trên 1 dòng, không gãy dòng */
        .nav-cat-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
        }

        /* Chữ tên sản phẩm hiển thị đầy đủ, không bị cắt chữ, không tràn khung */
        .product-title-full {
            word-break: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            line-height: 1.38;
        }

        /* Hiệu ứng mượt cho slider banner */
        .banner-slide {
            transition: opacity 0.7s ease-in-out;
        }

        /* Nút liên hệ nổi bật */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(45, 114, 38, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(45, 114, 38, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(45, 114, 38, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class=" flex flex-col min-h-screen">

    <!-- ==========================================
         TOP BAR (THÔNG TIN ĐỊA CHỈ & LIÊN HỆ NHANH)
         ========================================== -->
    <div class="bg-farm-800 text-white text-xs py-2 border-b border-farm-700">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-4 flex-wrap">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-pomelo-400"></i>
                    <span>Địa chỉ: TDP Nam Yên, P. Hải Vân, Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-pomelo-400"></i>
                    <span>huongbuoifarmstay.com</span>
                </span>
            </div>
            <div class="flex items-center gap-4">
                <a href="tel:0704447876" class="hover:text-pomelo-400 transition inline-flex items-center gap-1">
                    <i class="fa-solid fa-phone-volume text-pomelo-400"></i>
                    <span class="font-semibold">0704.447.876</span>
                </a>
                <a href="https://www.facebook.com/Huongbuoifarmstay" target="_blank" rel="noopener noreferrer" class="hover:text-pomelo-400 transition inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i>
                    <span>Fanpage</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header class="sticky top-0 z-40 bg-white shadow-sm border-b border-gray-100">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo chỉnh gọn nhỏ lại -->
            <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                <img 
                    src="https://lh3.googleusercontent.com/d/1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq" 
                    data-drive-id="1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq"
                    onerror="handleDriveImgError(this, 'Logo')"
                    alt="Logo Hương Bưởi Farmstay" 
                    class="h-10 md:h-11 w-10 md:w-11 object-contain rounded-full border border-farm-200 p-0.5 bg-white shrink-0"
                >
                <div class="leading-tight">
                    <span class="block text-sm md:text-base font-extrabold text-farm-700 tracking-tight">HƯƠNG BƯỞI FARMSTAY</span>
                    <span class="block text-[10px] md:text-[11px] text-gray-500 font-medium">huongbuoifarmstay.com</span>
                </div>
            </a>

            <!-- Menu Danh Mục trên Máy Tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng tên danh mục -->
            <nav class="hidden lg:flex items-center justify-end flex-wrap gap-x-3 xl:gap-x-5 gap-y-1">
                <a href="#trang-chu" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-farm-700 hover:text-pomelo-600 transition py-1">TRANG CHỦ</a>
                <a href="#gioi-thieu" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">GIỚI THIỆU</a>
                <a href="#dich-vu" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">DỊCH VỤ & VÉ CỔNG</a>
                <a href="#luu-tru" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">LƯU TRÚ & NHÀ SÀN</a>
                <a href="#am-thuc" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">ẨM THỰC BẢN ĐỊA</a>
                <a href="#tour-du-lich" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">TOUR DU LỊCH</a>
                <a href="#thu-vien-anh" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">HÌNH ẢNH THỰC TẾ</a>
                <a href="#tin-tuc" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">BÀI VIẾT</a>
                <a href="#doi-tac" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">ĐỐI TÁC</a>
                <a href="#bao-gia-lien-he" class="nav-cat-item text-[12.5px] xl:text-[13px] font-semibold text-gray-700 hover:text-farm-600 transition py-1">BÁO GIÁ & LIÊN HỆ</a>
            </nav>

            <!-- Nút mở Menu trên Điện Thoại -->
            <button id="mobileMenuBtn" type="button" aria-label="Mở menu" class="lg:hidden p-2 rounded-lg text-farm-700 hover:bg-farm-50 border border-farm-100">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu Điện Thoại xổ xuống -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-gray-100 shadow-md">
            <div class="flatsome-container py-3 grid grid-cols-2 gap-2 text-xs font-semibold">
                <a href="#trang-chu" class="mobile-nav-link px-3 py-2 rounded-lg bg-farm-50 text-farm-800 whitespace-nowrap"><i class="fa-solid fa-house mr-1.5 text-farm-600"></i>Trang chủ</a>
                <a href="#gioi-thieu" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-seedling mr-1.5 text-farm-600"></i>Giới thiệu</a>
                <a href="#dich-vu" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-ticket mr-1.5 text-farm-600"></i>Dịch vụ & Vé cổng</a>
                <a href="#luu-tru" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-campground mr-1.5 text-farm-600"></i>Lưu trú & Nhà sàn</a>
                <a href="#am-thuc" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-utensils mr-1.5 text-farm-600"></i>Ẩm thực bản địa</a>
                <a href="#tour-du-lich" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-route mr-1.5 text-farm-600"></i>Tour du lịch</a>
                <a href="#thu-vien-anh" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-images mr-1.5 text-farm-600"></i>Hình ảnh thực tế</a>
                <a href="#tin-tuc" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-newspaper mr-1.5 text-farm-600"></i>Bài viết</a>
                <a href="#doi-tac" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-handshake mr-1.5 text-farm-600"></i>Đối tác</a>
                <a href="#bao-gia-lien-he" class="mobile-nav-link px-3 py-2 rounded-lg bg-gray-50 text-gray-700 whitespace-nowrap"><i class="fa-solid fa-envelope-open-text mr-1.5 text-farm-600"></i>Báo giá & Liên hệ</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         BANNER SLIDER 2 ẢNH TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         (Thiết kế riêng bản Máy Tính & bản Điện Thoại để tối ưu chữ nằm gọn trong ảnh)
         ========================================== -->
    <section id="trang-chu" class="relative w-full overflow-hidden bg-farm-900">
        <!-- ================= BANNER MÁY TÍNH (Desktop >= 768px) ================= -->
        <div class="hidden md:block relative w-full h-[440px] lg:h-[480px]">
            <!-- Slide 1 Máy Tính -->
            <div class="desktop-slide banner-slide absolute inset-0 opacity-100 z-10">
                <img 
                    src="https://lh3.googleusercontent.com/d/18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA" 
                    data-drive-id="18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA"
                    onerror="handleDriveImgError(this, 'Banner+1')"
                    alt="Hương Bưởi Farmstay Không Gian Xanh" 
                    class="w-full h-full object-cover"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-black/75 via-black/50 to-black/30 flex items-center">
                    <div class="flatsome-container">
                        <div class="max-w-2xl bg-black/35 backdrop-blur-sm p-6 lg:p-8 rounded-2xl border border-white/20 text-white">
                            <p class="text-pomelo-400 text-xs lg:text-sm font-bold uppercase tracking-widest mb-2">
                                KHU DU LỊCH SINH THÁI & NGHỈ DƯỠNG XANH ĐÀ NẴNG
                            </p>
                            <h1 class="text-2xl lg:text-3xl font-extrabold leading-snug mb-3">
                                HƯƠNG BƯỞI FARMSTAY – VƯỜN THIÊN NHIÊN THANH BÌNH
                            </h1>
                            <p class="text-xs lg:text-sm text-gray-200 leading-relaxed mb-5">
                                Tọa lạc tại TDP Nam Yên, P. Hải Vân, Đà Nẵng. Tận hưởng không gian vườn cây ăn trái hữu cơ, tắm hồ bơi mát lành, nghỉ dưỡng nhà sàn gỗ, lều Glamping và thưởng thức ẩm thực bản địa.
                            </p>
                            <div class="flex flex-wrap items-center gap-3">
                                <a href="#bao-gia-lien-he" class="px-5 py-2.5 rounded-lg bg-pomelo-500 hover:bg-pomelo-600 text-gray-900 font-bold text-xs lg:text-sm transition">
                                    Nhận Báo Giá Ngay
                                </a>
                                <a href="#dich-vu" class="px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs lg:text-sm border border-white/30 transition">
                                    Khám Phá Dịch Vụ
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 2 Máy Tính (Kích thước bằng hệt Slide 1) -->
            <div class="desktop-slide banner-slide absolute inset-0 opacity-0 z-0">
                <img 
                    src="https://lh3.googleusercontent.com/d/1oCktkmYQHKsn8vNSljUI35-9szGcL8JJ" 
                    data-drive-id="1oCktkmYQHKsn8vNSljUI35-9szGcL8JJ"
                    onerror="handleDriveImgError(this, 'Banner+2')"
                    alt="Lưu Trú Nhà Sàn Và Glamping Hương Bưởi Farmstay" 
                    class="w-full h-full object-cover"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-farm-900/80 via-black/50 to-black/30 flex items-center">
                    <div class="flatsome-container">
                        <div class="max-w-2xl bg-black/35 backdrop-blur-sm p-6 lg:p-8 rounded-2xl border border-white/20 text-white">
                            <p class="text-pomelo-400 text-xs lg:text-sm font-bold uppercase tracking-widest mb-2">
                                LƯU TRÚ NHÀ SÀN • GLAMPING • HỒ BƠI • LỬA TRẠI
                            </p>
                            <h2 class="text-2xl lg:text-3xl font-extrabold leading-snug mb-3">
                                TRẢI NGHIỆM CAMPING & ẨM THỰC ĐẶC SẢN BẢN ĐỊA
                            </h2>
                            <p class="text-xs lg:text-sm text-gray-200 leading-relaxed mb-5">
                                Điểm hẹn lý tưởng cho gia đình, hội nhóm và công ty tổ chức Team Building, tiệc nướng BBQ ngoài trời, đốt lửa trại đêm và thưởng thức gà nướng, cá suối, trái cây sạch tại vườn.
                            </p>
                            <div class="flex flex-wrap items-center gap-3">
                                <a href="#luu-tru" class="px-5 py-2.5 rounded-lg bg-farm-500 hover:bg-farm-600 text-white font-bold text-xs lg:text-sm transition">
                                    Xem Phòng & Lều Trại
                                </a>
                                <a href="tel:0704447876" class="px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs lg:text-sm border border-white/30 transition">
                                    Hotline: 0704.447.876
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- ================= BANNER ĐIỆN THOẠI (Mobile < 768px - Thiết kế riêng tối ưu chữ nhỏ gọn nằm hết trong ảnh) ================= -->
        <div class="block md:hidden relative w-full h-[270px] sm:h-[300px]">
            <!-- Slide 1 Điện Thoại -->
            <div class="mobile-slide banner-slide absolute inset-0 opacity-100 z-10">
                <img 
                    src="https://lh3.googleusercontent.com/d/10lyuHOyvcVp_cX2Z6oDBJShz0jCdkPpm" 
                    data-drive-id="10lyuHOyvcVp_cX2Z6oDBJShz0jCdkPpm"
                    onerror="handleDriveImgError(this, 'Mobile+Banner+1')"
                    alt="Hương Bưởi Farmstay Mobile 1" 
                    class="w-full h-full object-cover"
                >
                <div class="absolute inset-0 bg-black/55 flex items-center justify-center p-4">
                    <div class="w-full max-w-[92%] bg-black/45 backdrop-blur-xs px-3.5 py-3 rounded-xl border border-white/20 text-center text-white">
                        <span class="block text-[10px] font-bold text-pomelo-400 uppercase tracking-wider mb-1">
                            TDP NAM YÊN - P. HẢI VÂN - ĐÀ NẴNG
                        </span>
                        <h2 class="text-sm sm:text-base font-extrabold leading-snug mb-1.5">
                            HƯƠNG BƯỞI FARMSTAY ĐÀ NẴNG
                        </h2>
                        <p class="text-[11px] text-gray-200 leading-normal mb-2.5">
                            Vườn cây sinh thái, hồ bơi, lưu trú nhà sàn, lều Glamping & ẩm thực dân dã.
                        </p>
                        <div class="flex items-center justify-center gap-2">
                            <a href="#bao-gia-lien-he" class="px-3 py-1.5 rounded-md bg-pomelo-500 text-gray-900 font-bold text-[11px]">
                                Đặt Dịch Vụ
                            </a>
                            <a href="tel:0704447876" class="px-3 py-1.5 rounded-md bg-farm-600 text-white font-semibold text-[11px]">
                                0704.447.876
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 2 Điện Thoại (Kích thước bằng hệt Slide 1) -->
            <div class="mobile-slide banner-slide absolute inset-0 opacity-0 z-0">
                <img 
                    src="https://lh3.googleusercontent.com/d/1jnFEJt8IN54L-96ATTrOlzZTSuBUe09z" 
                    data-drive-id="1jnFEJt8IN54L-96ATTrOlzZTSuBUe09z"
                    onerror="handleDriveImgError(this, 'Mobile+Banner+2')"
                    alt="Hương Bưởi Farmstay Mobile 2" 
                    class="w-full h-full object-cover"
                >
                <div class="absolute inset-0 bg-black/55 flex items-center justify-center p-4">
                    <div class="w-full max-w-[92%] bg-black/45 backdrop-blur-xs px-3.5 py-3 rounded-xl border border-white/20 text-center text-white">
                        <span class="block text-[10px] font-bold text-pomelo-400 uppercase tracking-wider mb-1">
                            NGHỈ DƯỠNG XANH & TEAM BUILDING
                        </span>
                        <h2 class="text-sm sm:text-base font-extrabold leading-snug mb-1.5">
                            CAMPING • BBQ LỬA TRẠI • HỒ BƠI
                        </h2>
                        <p class="text-[11px] text-gray-200 leading-normal mb-2.5">
                            Trọn gói lưu trú qua đêm, thưởng thức gà nướng, cá suối & trái cây tại vườn.
                        </p>
                        <div class="flex items-center justify-center gap-2">
                            <a href="#luu-tru" class="px-3 py-1.5 rounded-md bg-pomelo-500 text-gray-900 font-bold text-[11px]">
                                Xem Lưu Trú
                            </a>
                            <a href="#am-thuc" class="px-3 py-1.5 rounded-md bg-white/20 text-white font-semibold text-[11px] border border-white/30">
                                Xem Ẩm Thực
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Nút điều hướng Banner -->
        <button onclick="prevBanner()" aria-label="Slide trước" class="absolute left-2 md:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 md:w-10 md:h-10 rounded-full bg-black/40 hover:bg-farm-600 text-white flex items-center justify-center transition">
            <i class="fa-solid fa-chevron-left text-xs md:text-sm"></i>
        </button>
        <button onclick="nextBanner()" aria-label="Slide tiếp" class="absolute right-2 md:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 md:w-10 md:h-10 rounded-full bg-black/40 hover:bg-farm-600 text-white flex items-center justify-center transition">
            <i class="fa-solid fa-chevron-right text-xs md:text-sm"></i>
        </button>

        <!-- Chấm tròn chỉ báo Slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button onclick="goToBanner(0)" id="dot-0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-pomelo-400 transition-all"></button>
            <button onclick="goToBanner(1)" id="dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
        </div>
    </section>

    <!-- ==========================================
         THANH DANH MỤC TRANG CHỦ (TỐI ƯU CHO MÁY TÍNH & ĐIỆN THOẠI)
         Chữ danh mục nhỏ gọn, tên danh mục viết liền trên 1 hàng không gãy dòng
         ========================================== -->
    <section class="py-5 bg-white border-b border-gray-100">
        <div class="flatsome-container">
            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2 md:gap-2.5">
                <a href="#dich-vu" class="flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-xl bg-farm-50 hover:bg-farm-600 text-farm-800 hover:text-white border border-farm-100 transition group">
                    <i class="fa-solid fa-ticket text-farm-600 group-hover:text-pomelo-400 text-xs shrink-0"></i>
                    <span class="text-[11.5px] xl:text-xs font-semibold whitespace-nowrap">Vé Tham Quan</span>
                </a>
                <a href="#dich-vu" class="flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-xl bg-farm-50 hover:bg-farm-600 text-farm-800 hover:text-white border border-farm-100 transition group">
                    <i class="fa-solid fa-water-ladder text-farm-600 group-hover:text-pomelo-400 text-xs shrink-0"></i>
                    <span class="text-[11.5px] xl:text-xs font-semibold whitespace-nowrap">Hồ Bơi & Chòi Nghỉ</span>
                </a>
                <a href="#luu-tru" class="flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-xl bg-farm-50 hover:bg-farm-600 text-farm-800 hover:text-white border border-farm-100 transition group">
                    <i class="fa-solid fa-house-chimney-window text-farm-600 group-hover:text-pomelo-400 text-xs shrink-0"></i>
                    <span class="text-[11.5px] xl:text-xs font-semibold whitespace-nowrap">Lưu Trú Nhà Sàn</span>
                </a>
                <a href="#luu-tru" class="flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-xl bg-farm-50 hover:bg-farm-600 text-farm-800 hover:text-white border border-farm-100 transition group">
                    <i class="fa-solid fa-tents text-farm-600 group-hover:text-pomelo-400 text-xs shrink-0"></i>
                    <span class="text-[11.5px] xl:text-xs font-semibold whitespace-nowrap">Lều Glamping</span>
                </a>
                <a href="#dich-vu" class="flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-xl bg-farm-50 hover:bg-farm-600 text-farm-800 hover:text-white border border-farm-100 transition group">
                    <i class="fa-solid fa-fire-burner text-farm-600 group-hover:text-pomelo-400 text-xs shrink-0"></i>
                    <span class="text-[11.5px] xl:text-xs font-semibold whitespace-nowrap">Camping Lửa Trại</span>
                </a>
                <a href="#am-thuc" class="flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-xl bg-farm-50 hover:bg-farm-600 text-farm-800 hover:text-white border border-farm-100 transition group">
                    <i class="fa-solid fa-drumstick-bite text-farm-600 group-hover:text-pomelo-400 text-xs shrink-0"></i>
                    <span class="text-[11.5px] xl:text-xs font-semibold whitespace-nowrap">Ẩm Thực Bản Địa</span>
                </a>
                <a href="#tour-du-lich" class="flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-xl bg-farm-50 hover:bg-farm-600 text-farm-800 hover:text-white border border-farm-100 transition group">
                    <i class="fa-solid fa-map-location-dot text-farm-600 group-hover:text-pomelo-400 text-xs shrink-0"></i>
                    <span class="text-[11.5px] xl:text-xs font-semibold whitespace-nowrap">Tour Sinh Thái</span>
                </a>
                <a href="#bao-gia-lien-he" class="flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-xl bg-pomelo-400 hover:bg-pomelo-500 text-gray-900 border border-pomelo-500 transition group">
                    <i class="fa-solid fa-file-signature text-gray-900 text-xs shrink-0"></i>
                    <span class="text-[11.5px] xl:text-xs font-bold whitespace-nowrap">Báo Giá Nhanh</span>
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION GIỚI THIỆU HƯƠNG BƯỞI FARMSTAY (BỐ CỤC UX BUILDER)
         ========================================== -->
    <section id="gioi-thieu" class="py-10 md:py-14">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Cột văn bản (6 cột) -->
                <div class="lg:col-span-6 space-y-4">
                    <div class="inline-flex items-center gap-2 text-farm-600 font-bold text-xs uppercase tracking-wider">
                        <i class="fa-solid fa-leaf"></i>
                        <span>GIỚI THIỆU VỀ HƯƠNG BƯỞI FARMSTAY</span>
                    </div>
                    <h2 class="text-xl md:text-2xl lg:text-3xl font-extrabold text-gray-900 leading-snug">
                        Điểm Đến Du Lịch Sinh Thái, Nghỉ Dưỡng Xanh Giữa Thung Lũng Nam Yên – Hải Vân
                    </h2>
                    <p class="text-sm text-gray-600 leading-relaxed">
                        Tọa lạc tại <strong>TDP Nam Yên, Phường Hải Vân, TP. Đà Nẵng</strong> (khu vực Hòa Bắc sinh thái), <strong>Hương Bưởi Farmstay</strong> là không gian nghỉ dưỡng xanh mát chỉ cách trung tâm thành phố khoảng 30 phút di chuyển. Nơi đây sở hữu khu vườn cây ăn quả trù phú với bưởi, ổi, mít, chanh hữu cơ cùng không khí trong lành của núi rừng.
                    </p>
                    <p class="text-sm text-gray-600 leading-relaxed">
                        Đến với Hương Bưởi Farmstay, du khách được trải nghiệm lưu trú tại nhà sàn gỗ truyền thống hoặc khu lều Glamping phong cách Địa Trung Hải, thỏa thích bơi lội tại hồ bơi ngoài trời, quây quần bên ánh lửa trại ấm áp và thưởng thức các món đặc sản bản địa tươi ngon do chính nông trại chuẩn bị.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 pt-2">
                        <div class="p-3 rounded-xl bg-white border border-gray-200">
                            <p class="text-base font-extrabold text-farm-700">Vườn Cây Sạch</p>
                            <p class="text-xs text-gray-500 mt-0.5">Bưởi, ổi, mít hữu cơ xanh mát</p>
                        </div>
                        <div class="p-3 rounded-xl bg-white border border-gray-200">
                            <p class="text-base font-extrabold text-farm-700">Hồ Bơi & Lửa Trại</p>
                            <p class="text-xs text-gray-500 mt-0.5">Khuôn viên rộng cho đoàn, nhóm</p>
                        </div>
                        <div class="p-3 rounded-xl bg-white border border-gray-200 col-span-2 sm:col-span-1">
                            <p class="text-base font-extrabold text-farm-700">Ẩm Thực Dân Dã</p>
                            <p class="text-xs text-gray-500 mt-0.5">Gà đồi nướng, cá suối, rau rừng</p>
                        </div>
                    </div>
                </div>

                <!-- Cột hình ảnh thực tế (6 cột) -->
                <div class="lg:col-span-6 grid grid-cols-2 gap-3">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1jFspxcE3l-1U5PeG9g0OeMiAa9UA72wa" 
                        data-drive-id="1jFspxcE3l-1U5PeG9g0OeMiAa9UA72wa"
                        onerror="handleDriveImgError(this, 'Khong+Gian+1')"
                        alt="Không gian Hương Bưởi Farmstay 1" 
                        class="w-full h-44 md:h-56 object-cover rounded-xl shadow-sm border border-gray-100"
                    >
                    <img 
                        src="https://lh3.googleusercontent.com/d/1pahDckLB2bC3gBHhRQeTSEvXZXfYIX5l" 
                        data-drive-id="1pahDckLB2bC3gBHhRQeTSEvXZXfYIX5l"
                        onerror="handleDriveImgError(this, 'Khong+Gian+2')"
                        alt="Không gian Hương Bưởi Farmstay 2" 
                        class="w-full h-44 md:h-56 object-cover rounded-xl shadow-sm border border-gray-100"
                    >
                    <img 
                        src="https://lh3.googleusercontent.com/d/1Nu4x0ZcBQ3uIQt_prn7tNTXac1Fd0N1D" 
                        data-drive-id="1Nu4x0ZcBQ3uIQt_prn7tNTXac1Fd0N1D"
                        onerror="handleDriveImgError(this, 'Khong+Gian+3')"
                        alt="Không gian Hương Bưởi Farmstay 3" 
                        class="w-full h-44 md:h-56 object-cover rounded-xl shadow-sm border border-gray-100 col-span-2"
                    >
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 1: DỊCH VỤ & VUI CHƠI GIẢI TRÍ (Theo mẫu Suối Lương Hải Vân Park)
         - Điện thoại: 2 cột (grid-cols-2)
         - Máy tính: 4 cột (lg:grid-cols-4)
         - Không nhãn dán trên ảnh, tên sản phẩm hiển thị đầy đủ không cắt chữ
         ========================================== -->
    <section id="dich-vu" class="py-10 bg-white border-t border-gray-100">
        <div class="flatsome-container">
            <div class="text-center max-w-2xl mx-auto mb-7">
                <h2 class="text-lg md:text-2xl font-extrabold text-farm-800 uppercase tracking-tight">
                    DỊCH VỤ & TRẢI NGHIỆM SINH THÁI
                </h2>
                <div class="w-16 h-1 bg-pomelo-500 mx-auto my-2 rounded-full"></div>
                <p class="text-xs md:text-sm text-gray-600">
                    Đa dạng loại hình dịch vụ tham quan vườn bưởi, tắm hồ bơi, cắm trại, đốt lửa trại và tổ chức sự kiện ngoài trời tại Hương Bưởi Farmstay.
                </p>
            </div>

            <!-- Grid 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <!-- Sản phẩm 1 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA" 
                                data-drive-id="18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA"
                                onerror="handleDriveImgError(this, 'Ve+Tham+Quan')"
                                alt="Vé Vào Cổng & Tham Quan Vườn Bưởi Sinh Thái" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Vé Vào Cổng & Tham Quan Vườn Bưởi Sinh Thái
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Dạo bước dưới tán vườn bưởi, ổi, mít xanh mát và chụp hình check-in không gian nông trại thanh bình.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Từ 100.000đ/khách</span>
                        <button onclick="selectServiceForQuote('Vé Vào Cổng & Tham Quan Vườn Bưởi Sinh Thái')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt dịch vụ
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 2 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1D8iLupXqG5l8z7yDr2VLSZGEFRjHeQhY" 
                                data-drive-id="1D8iLupXqG5l8z7yDr2VLSZGEFRjHeQhY"
                                onerror="handleDriveImgError(this, 'Ho+Boi+Choi+Nghi')"
                                alt="Đặt Chòi Nghỉ Mát & Sử Dụng Hồ Bơi Ngoài Trời" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Đặt Chòi Nghỉ Mát & Sử Dụng Hồ Bơi Ngoài Trời
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Không gian chòi nghỉ thoáng đãng bên vườn cây kết hợp tắm hồ bơi nước sạch mát lạnh cho gia đình và trẻ nhỏ.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Miễn phí khi lưu trú</span>
                        <button onclick="selectServiceForQuote('Đặt Chòi Nghỉ Mát & Sử Dụng Hồ Bơi Ngoài Trời')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt dịch vụ
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 3 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1us5JbbU9WoEN1MDcdBtjm_voFVliBPW_" 
                                data-drive-id="1us5JbbU9WoEN1MDcdBtjm_voFVliBPW_"
                                onerror="handleDriveImgError(this, 'Camping+Lua+Trai')"
                                alt="Dịch Vụ Bãi Cắm Trại Camping & Đốt Lửa Trại Đêm" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Dịch Vụ Bãi Cắm Trại Camping & Đốt Lửa Trại Đêm
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Khu vực đốt lửa trại ngoài trời rộng rãi, giao lưu acoustic nhẹ nhàng dưới bầu trời đầy sao tại Nam Yên.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Báo giá theo đoàn</span>
                        <button onclick="selectServiceForQuote('Dịch Vụ Bãi Cắm Trại Camping & Đốt Lửa Trại Đêm')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt dịch vụ
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 4 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/17gkybGke6lemTuV8wKShzcw59-6FXbWY" 
                                data-drive-id="17gkybGke6lemTuV8wKShzcw59-6FXbWY"
                                onerror="handleDriveImgError(this, 'Team+Building')"
                                alt="Tổ Chức Sự Kiện, Sinh Nhật & Team Building" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Tổ Chức Sự Kiện, Sinh Nhật & Team Building
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Thiết kế không gian sinh hoạt tập thể, họp lớp, kỷ niệm gia đình và trò chơi gắn kết đội nhóm giữa thiên nhiên.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Ưu đãi đoàn đông</span>
                        <button onclick="selectServiceForQuote('Tổ Chức Sự Kiện, Sinh Nhật & Team Building')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt dịch vụ
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 2: LƯU TRÚ & NGHỈ DƯỠNG FARMSTAY (Theo mẫu Khách sạn/Lưu trú Suối Lương)
         - Điện thoại: 2 cột (grid-cols-2)
         - Máy tính: 4 cột (lg:grid-cols-4)
         ========================================== -->
    <section id="luu-tru" class="py-10 bg-farm-50/70 border-t border-gray-100">
        <div class="flatsome-container">
            <div class="text-center max-w-2xl mx-auto mb-7">
                <h2 class="text-lg md:text-2xl font-extrabold text-farm-800 uppercase tracking-tight">
                    LƯU TRÚ NHÀ SÀN & LỀU GLAMPING
                </h2>
                <div class="w-16 h-1 bg-pomelo-500 mx-auto my-2 rounded-full"></div>
                <p class="text-xs md:text-sm text-gray-600">
                    Lựa chọn nghỉ đêm tại nhà sàn gỗ ấm cúng hoặc lều trại phong cách Địa Trung Hải đầy đủ chăn ga, đệm nằm, quạt mát và 2 bữa ăn.
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <!-- Lưu trú 1 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1oCktkmYQHKsn8vNSljUI35-9szGcL8JJ" 
                                data-drive-id="1oCktkmYQHKsn8vNSljUI35-9szGcL8JJ"
                                onerror="handleDriveImgError(this, 'Nha+San+Go')"
                                alt="Nhà Sàn Gỗ Truyền Thống 2 Tầng Sức Chứa 20 Khách" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Nhà Sàn Gỗ Truyền Thống 2 Tầng Sức Chứa 20 Khách
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Tầng 1 sinh hoạt chung thoáng mát, tầng 2 phòng nghỉ tập thể trang bị đầy đủ nệm êm, chăn gối và quạt máy.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">600.000đ/người</span>
                        <button onclick="selectServiceForQuote('Nhà Sàn Gỗ Truyền Thống 2 Tầng Sức Chứa 20 Khách')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt phòng
                        </button>
                    </div>
                </div>

                <!-- Lưu trú 2 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/10lyuHOyvcVp_cX2Z6oDBJShz0jCdkPpm" 
                                data-drive-id="10lyuHOyvcVp_cX2Z6oDBJShz0jCdkPpm"
                                onerror="handleDriveImgError(this, 'Leu+Glamping')"
                                alt="Khu Nhà Lều Glamping Phong Cách Địa Trung Hải" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Khu Nhà Lều Glamping Phong Cách Địa Trung Hải
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Không gian lều nghỉ bài trí tinh tế giữa vườn cây, trang bị sẵn đệm nằm, chăn gối, quạt điện và ổ cắm tiện lợi.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">600.000đ/người</span>
                        <button onclick="selectServiceForQuote('Khu Nhà Lều Glamping Phong Cách Địa Trung Hải')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt lều
                        </button>
                    </div>
                </div>

                <!-- Lưu trú 3 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1jnFEJt8IN54L-96ATTrOlzZTSuBUe09z" 
                                data-drive-id="1jnFEJt8IN54L-96ATTrOlzZTSuBUe09z"
                                onerror="handleDriveImgError(this, 'Combo+Qua+Dem')"
                                alt="Combo Lưu Trú Qua Đêm Trọn Gói Ăn Tối & Ăn Sáng" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Combo Lưu Trú Qua Đêm Trọn Gói Ăn Tối & Ăn Sáng
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Bao gồm nghỉ đêm nhà sàn hoặc lều trại, miễn phí hồ bơi ngoài trời cùng bữa tối đặc sản và bữa sáng tại farm.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">550.000đ - 650.000đ</span>
                        <button onclick="selectServiceForQuote('Combo Lưu Trú Qua Đêm Trọn Gói Ăn Tối & Ăn Sáng')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt combo
                        </button>
                    </div>
                </div>

                <!-- Lưu trú 4 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1KIxhw7CYiF2qViu6AfzI_V9XyRfdEr8H" 
                                data-drive-id="1KIxhw7CYiF2qViu6AfzI_V9XyRfdEr8H"
                                onerror="handleDriveImgError(this, 'Thue+Nguyen+Khu')"
                                alt="Thuê Nguyên Khu Farmstay Cho Đoàn Gia Đình & Công Ty" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Thuê Nguyên Khu Farmstay Cho Đoàn Gia Đình & Công Ty
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Tận hưởng không gian riêng tư toàn bộ nhà sàn, khu lều, bãi cỏ lửa trại và hồ bơi dành riêng cho đoàn từ 15 - 30 khách.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Liên hệ báo giá</span>
                        <button onclick="selectServiceForQuote('Thuê Nguyên Khu Farmstay Cho Đoàn Gia Đình & Công Ty')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt phòng
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 3: ẨM THỰC NHÀ HÀNG & NÔNG SẢN SẠCH (Theo mẫu Ẩm thực Suối Lương)
         - Điện thoại: 2 cột (grid-cols-2)
         - Máy tính: 4 cột (lg:grid-cols-4)
         ========================================== -->
    <section id="am-thuc" class="py-10 bg-white border-t border-gray-100">
        <div class="flatsome-container">
            <div class="text-center max-w-2xl mx-auto mb-7">
                <h2 class="text-lg md:text-2xl font-extrabold text-farm-800 uppercase tracking-tight">
                    ẨM THỰC BẢN ĐỊA & TRÁI CÂY TẠI VƯỜN
                </h2>
                <div class="w-16 h-1 bg-pomelo-500 mx-auto my-2 rounded-full"></div>
                <p class="text-xs md:text-sm text-gray-600">
                    Thưởng thức hương vị ẩm thực dân dã đặc trưng vùng núi Hòa Bắc – Hải Vân do chính chủ nhà Hương Bưởi Farmstay tận tay chế biến.
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <!-- Ẩm thực 1 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1bIAcH7KwypdN5T7c-B_OE1pHyKlBeIXk" 
                                data-drive-id="1bIAcH7KwypdN5T7c-B_OE1pHyKlBeIXk"
                                onerror="handleDriveImgError(this, 'Ga+Nuong+Ca+Suoi')"
                                alt="Đặc Sản Gà Đồi Nướng & Cá Suối Nướng Hòa Bắc" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Đặc Sản Gà Đồi Nướng & Cá Suối Nướng Hòa Bắc
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Gà thả vườn nướng than hồng thơm lừng và cá suối tươi ngon ăn kèm muối ớt xanh, rau rừng bản địa.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Đặt trước theo mâm</span>
                        <button onclick="selectServiceForQuote('Đặc Sản Gà Đồi Nướng & Cá Suối Nướng Hòa Bắc')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt món
                        </button>
                    </div>
                </div>

                <!-- Ẩm thực 2 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1iFy2dHzGNZz0RUPiMvVQnDf4RQOa4tvZ" 
                                data-drive-id="1iFy2dHzGNZz0RUPiMvVQnDf4RQOa4tvZ"
                                onerror="handleDriveImgError(this, 'Set+BBQ+San+Vuon')"
                                alt="Tiệc Nướng BBQ Sân Vườn Ngoài Trời Buổi Tối" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Tiệc Nướng BBQ Sân Vườn Ngoài Trời Buổi Tối
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Thực đơn nướng BBQ phong phú với thịt nướng, hải sản, rau củ sạch thu hoạch trực tiếp từ nông trại.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Từ 250.000đ/suất</span>
                        <button onclick="selectServiceForQuote('Tiệc Nướng BBQ Sân Vườn Ngoài Trời Buổi Tối')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt tiệc
                        </button>
                    </div>
                </div>

                <!-- Ẩm thực 3 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1hbdObGRDRbLpwvmNnQ5CGpaoC4pGnYfH" 
                                data-drive-id="1hbdObGRDRbLpwvmNnQ5CGpaoC4pGnYfH"
                                onerror="handleDriveImgError(this, 'Com+Que+Dan+Da')"
                                alt="Mâm Cơm Quê Dân Dã & Rau Rừng Thung Lũng Nam Yên" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Mâm Cơm Quê Dân Dã & Rau Rừng Thung Lũng Nam Yên
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Bữa cơm gia đình ấm áp với canh chua, cá kho tộ, rau rừng luộc chấm mắm nêm chuẩn vị miền Trung.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Từ 150.000đ/suất</span>
                        <button onclick="selectServiceForQuote('Mâm Cơm Quê Dân Dã & Rau Rừng Thung Lũng Nam Yên')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt món
                        </button>
                    </div>
                </div>

                <!-- Ẩm thực 4 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/10w8TtqbWvE7eaWxOUsqL9SeBH8qqwoWB" 
                                data-drive-id="10w8TtqbWvE7eaWxOUsqL9SeBH8qqwoWB"
                                onerror="handleDriveImgError(this, 'Buoi+Sach+Huu+Co')"
                                alt="Thưởng Thức Bưởi Sạch, Ổi, Mít, Chanh Hữu Cơ Tại Vườn" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Thưởng Thức Bưởi Sạch, Ổi, Mít, Chanh Hữu Cơ Tại Vườn
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Trái cây canh tác theo hướng hữu cơ tự nhiên tại Hương Bưởi Farmstay, ngọt lành và an toàn cho sức khỏe.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Quà quê theo mùa</span>
                        <button onclick="selectServiceForQuote('Thưởng Thức Bưởi Sạch, Ổi, Mít, Chanh Hữu Cơ Tại Vườn')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt mua
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 4: TOUR DU LỊCH & TRẢI NGHIỆM (Theo mẫu Tour du lịch Suối Lương)
         - Điện thoại: 2 cột (grid-cols-2)
         - Máy tính: 4 cột (lg:grid-cols-4)
         ========================================== -->
    <section id="tour-du-lich" class="py-10 bg-farm-50/70 border-t border-gray-100">
        <div class="flatsome-container">
            <div class="text-center max-w-2xl mx-auto mb-7">
                <h2 class="text-lg md:text-2xl font-extrabold text-farm-800 uppercase tracking-tight">
                    TOUR DU LỊCH SINH THÁI TRỌN GÓI
                </h2>
                <div class="w-16 h-1 bg-pomelo-500 mx-auto my-2 rounded-full"></div>
                <p class="text-xs md:text-sm text-gray-600">
                    Khám phá vẻ đẹp nguyên sơ của vùng sinh thái Nam Yên – Hòa Bắc – Hải Vân với các lịch trình trải nghiệm hấp dẫn.
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <!-- Tour 1 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1tRhc3u13KCUlLyfbUXTjS7RnfXiuuGHF" 
                                data-drive-id="1tRhc3u13KCUlLyfbUXTjS7RnfXiuuGHF"
                                onerror="handleDriveImgError(this, 'Tour+Nong+Trai')"
                                alt="Chương Trình Du Lịch Sinh Thái Hương Bưởi Trong Ngày" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Chương Trình Du Lịch Sinh Thái Hương Bưởi Trong Ngày
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Khởi hành 7h30 - 17h00: Tham quan vườn bưởi, tắm hồ bơi, thưởng thức bữa trưa bản địa và nghỉ ngơi nhà sàn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">400.000đ/khách</span>
                        <button onclick="selectServiceForQuote('Chương Trình Du Lịch Sinh Thái Hương Bưởi Trong Ngày')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt tour
                        </button>
                    </div>
                </div>

                <!-- Tour 2 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1jFspxcE3l-1U5PeG9g0OeMiAa9UA72wa" 
                                data-drive-id="1jFspxcE3l-1U5PeG9g0OeMiAa9UA72wa"
                                onerror="handleDriveImgError(this, 'Tour+Nam+Yen')"
                                alt="Tour Khám Phá Thung Lũng Nam Yên & Sông Cu Đê 2N1Đ" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Tour Khám Phá Thung Lũng Nam Yên & Sông Cu Đê 2N1Đ
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Trọn gói nghỉ đêm tại Hương Bưởi Farmstay, ngắm hoàng hôn ven sông Cu Đê, tiệc BBQ và đốt lửa trại.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">600.000đ/khách</span>
                        <button onclick="selectServiceForQuote('Tour Khám Phá Thung Lũng Nam Yên & Sông Cu Đê 2N1Đ')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt tour
                        </button>
                    </div>
                </div>

                <!-- Tour 3 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1pahDckLB2bC3gBHhRQeTSEvXZXfYIX5l" 
                                data-drive-id="1pahDckLB2bC3gBHhRQeTSEvXZXfYIX5l"
                                onerror="handleDriveImgError(this, 'Tour+Hoc+Duong')"
                                alt="Tour Trải Nghiệm Nông Nghiệp Xanh Cho Học Sinh & Gia Đình" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Tour Trải Nghiệm Nông Nghiệp Xanh Cho Học Sinh & Gia Đình
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Tìm hiểu quy trình trồng bưởi sạch hữu cơ, hoạt động ngoại khóa thiên nhiên và vui chơi an toàn cho bé.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">350.000đ/khách</span>
                        <button onclick="selectServiceForQuote('Tour Trải Nghiệm Nông Nghiệp Xanh Cho Học Sinh & Gia Đình')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt tour
                        </button>
                    </div>
                </div>

                <!-- Tour 4 -->
                <div class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-gray-100">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1Nu4x0ZcBQ3uIQt_prn7tNTXac1Fd0N1D" 
                                data-drive-id="1Nu4x0ZcBQ3uIQt_prn7tNTXac1Fd0N1D"
                                onerror="handleDriveImgError(this, 'Xe+Dua+Don')"
                                alt="Dịch Vụ Thuê Xe Du Lịch Đưa Đón Đà Nẵng - Hương Bưởi Farmstay" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Dịch Vụ Thuê Xe Du Lịch Đưa Đón Đà Nẵng - Hương Bưởi Farmstay
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed mb-2">
                                Hỗ trợ đặt xe du lịch 7 chỗ, 16 chỗ, 29 chỗ đưa đón tận nơi từ trung tâm Đà Nẵng lên thẳng Farmstay.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1 border-t border-gray-100 flex items-center justify-between gap-2 flex-wrap">
                        <span class="text-xs md:text-sm font-extrabold text-farm-700">Theo lộ trình</span>
                        <button onclick="selectServiceForQuote('Dịch Vụ Thuê Xe Du Lịch Đưa Đón Đà Nẵng - Hương Bưởi Farmstay')" class="text-[11px] md:text-xs font-semibold px-2.5 py-1.5 rounded-lg bg-farm-600 hover:bg-farm-700 text-white transition">
                            Đặt xe
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         THƯ VIỆN 16 ẢNH THỰC TẾ HƯƠNG BƯỞI FARMSTAY
         (Hiển thị đầy đủ 16 file ảnh Google Drive khách cung cấp)
         ========================================== -->
    <section id="thu-vien-anh" class="py-10 bg-white border-t border-gray-100">
        <div class="flatsome-container">
            <div class="text-center max-w-2xl mx-auto mb-7">
                <h2 class="text-lg md:text-2xl font-extrabold text-farm-800 uppercase tracking-tight">
                    HÌNH ẢNH THỰC TẾ TẠI HƯƠNG BƯỞI FARMSTAY
                </h2>
                <div class="w-16 h-1 bg-pomelo-500 mx-auto my-2 rounded-full"></div>
                <p class="text-xs md:text-sm text-gray-600">
                    Toàn cảnh không gian vườn bưởi, nhà sàn gỗ, khu lều Glamping, hồ bơi, lửa trại và ẩm thực tại TDP Nam Yên, P. Hải Vân, Đà Nẵng.
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-4">
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA" data-drive-id="18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+1')" alt="Ảnh thực tế Hương Bưởi Farmstay 1" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1oCktkmYQHKsn8vNSljUI35-9szGcL8JJ" data-drive-id="1oCktkmYQHKsn8vNSljUI35-9szGcL8JJ" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+2')" alt="Ảnh thực tế Hương Bưởi Farmstay 2" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/10lyuHOyvcVp_cX2Z6oDBJShz0jCdkPpm" data-drive-id="10lyuHOyvcVp_cX2Z6oDBJShz0jCdkPpm" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+3')" alt="Ảnh thực tế Hương Bưởi Farmstay 3" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1jnFEJt8IN54L-96ATTrOlzZTSuBUe09z" data-drive-id="1jnFEJt8IN54L-96ATTrOlzZTSuBUe09z" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+4')" alt="Ảnh thực tế Hương Bưởi Farmstay 4" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1jFspxcE3l-1U5PeG9g0OeMiAa9UA72wa" data-drive-id="1jFspxcE3l-1U5PeG9g0OeMiAa9UA72wa" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+5')" alt="Ảnh thực tế Hương Bưởi Farmstay 5" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1pahDckLB2bC3gBHhRQeTSEvXZXfYIX5l" data-drive-id="1pahDckLB2bC3gBHhRQeTSEvXZXfYIX5l" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+6')" alt="Ảnh thực tế Hương Bưởi Farmstay 6" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1Nu4x0ZcBQ3uIQt_prn7tNTXac1Fd0N1D" data-drive-id="1Nu4x0ZcBQ3uIQt_prn7tNTXac1Fd0N1D" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+7')" alt="Ảnh thực tế Hương Bưởi Farmstay 7" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1D8iLupXqG5l8z7yDr2VLSZGEFRjHeQhY" data-drive-id="1D8iLupXqG5l8z7yDr2VLSZGEFRjHeQhY" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+8')" alt="Ảnh thực tế Hương Bưởi Farmstay 8" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1us5JbbU9WoEN1MDcdBtjm_voFVliBPW_" data-drive-id="1us5JbbU9WoEN1MDcdBtjm_voFVliBPW_" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+9')" alt="Ảnh thực tế Hương Bưởi Farmstay 9" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/17gkybGke6lemTuV8wKShzcw59-6FXbWY" data-drive-id="17gkybGke6lemTuV8wKShzcw59-6FXbWY" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+10')" alt="Ảnh thực tế Hương Bưởi Farmstay 10" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1KIxhw7CYiF2qViu6AfzI_V9XyRfdEr8H" data-drive-id="1KIxhw7CYiF2qViu6AfzI_V9XyRfdEr8H" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+11')" alt="Ảnh thực tế Hương Bưởi Farmstay 11" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1bIAcH7KwypdN5T7c-B_OE1pHyKlBeIXk" data-drive-id="1bIAcH7KwypdN5T7c-B_OE1pHyKlBeIXk" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+12')" alt="Ảnh thực tế Hương Bưởi Farmstay 12" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1iFy2dHzGNZz0RUPiMvVQnDf4RQOa4tvZ" data-drive-id="1iFy2dHzGNZz0RUPiMvVQnDf4RQOa4tvZ" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+13')" alt="Ảnh thực tế Hương Bưởi Farmstay 13" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1hbdObGRDRbLpwvmNnQ5CGpaoC4pGnYfH" data-drive-id="1hbdObGRDRbLpwvmNnQ5CGpaoC4pGnYfH" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+14')" alt="Ảnh thực tế Hương Bưởi Farmstay 14" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/10w8TtqbWvE7eaWxOUsqL9SeBH8qqwoWB" data-drive-id="10w8TtqbWvE7eaWxOUsqL9SeBH8qqwoWB" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+15')" alt="Ảnh thực tế Hương Bưởi Farmstay 15" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
                <div class="aspect-[4/3] rounded-xl overflow-hidden border border-gray-200 bg-gray-100">
                    <img src="https://lh3.googleusercontent.com/d/1tRhc3u13KCUlLyfbUXTjS7RnfXiuuGHF" data-drive-id="1tRhc3u13KCUlLyfbUXTjS7RnfXiuuGHF" onerror="handleDriveImgError(this, 'Anh+Thuc+Te+16')" alt="Ảnh thực tế Hương Bưởi Farmstay 16" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         ĐÁNH GIÁ KHÁCH HÀNG (Theo mẫu Suối Lương Hải Vân Park)
         ========================================== -->
    <section class="py-10 bg-farm-800 text-white">
        <div class="flatsome-container">
            <div class="text-center max-w-2xl mx-auto mb-7">
                <h2 class="text-lg md:text-2xl font-extrabold uppercase tracking-tight">
                    CẢM NHẬN DU KHÁCH VỀ HƯƠNG BƯỞI FARMSTAY
                </h2>
                <div class="w-16 h-1 bg-pomelo-400 mx-auto my-2 rounded-full"></div>
                <p class="text-xs md:text-sm text-farm-100">
                    Hơn 150+ lượt đánh giá 4.5/5 sao từ các gia đình, nhóm bạn trẻ và đoàn công ty khi ghé thăm nông trại.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-6">
                <div class="bg-farm-900/70 p-5 rounded-xl border border-farm-700">
                    <div class="text-pomelo-400 text-xs mb-2">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-xs md:text-sm text-gray-200 leading-relaxed mb-4">
                        "Không gian vườn bưởi rất mát mẻ, yên bình. Gia đình mình lên đây dịp cuối tuần, các bé thích mê hồ bơi ngoài trời, tối lại được đốt lửa trại và thưởng thức gà nướng, cá suối do anh chị chủ nhà chuẩn bị rất chu đáo."
                    </p>
                    <div class="font-bold text-xs text-pomelo-400">Chị Ngọc Thủy – Nhân viên văn phòng Đà Nẵng</div>
                </div>

                <div class="bg-farm-900/70 p-5 rounded-xl border border-farm-700">
                    <div class="text-pomelo-400 text-xs mb-2">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-xs md:text-sm text-gray-200 leading-relaxed mb-4">
                        "Nhóm mình 18 người thuê nhà sàn gỗ và lều Glamping qua đêm. Chăn đệm sạch sẽ, thoáng mát, góc nào lên hình cũng đẹp. Giá trọn gói cả ăn tối BBQ và ăn sáng cực kỳ hợp lý cho chuyến đi đổi gió gần trung tâm."
                    </p>
                    <div class="font-bold text-xs text-pomelo-400">Anh Hoàng Quân – Trưởng nhóm IT</div>
                </div>

                <div class="bg-farm-900/70 p-5 rounded-xl border border-farm-700">
                    <div class="text-pomelo-400 text-xs mb-2">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-xs md:text-sm text-gray-200 leading-relaxed mb-4">
                        "Đúng chất 'bỏ phố về vườn'. Vườn nhiều cây ăn trái như bưởi, ổi, mít xanh mướt. Buổi tối ngồi đàn guitar, nghe nhạc nhẹ bên bếp lửa trại ở Nam Yên thực sự thư giãn. Chắc chắn sẽ quay lại!"
                    </p>
                    <div class="font-bold text-xs text-pomelo-400">Bạn Minh Tâm – Du khách TP. Hồ Chí Minh</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & CẨM NANG)
         ========================================== -->
    <section id="tin-tuc" class="py-10 bg-white border-t border-gray-100">
        <div class="flatsome-container">
            <div class="text-center max-w-2xl mx-auto mb-7">
                <h2 class="text-lg md:text-2xl font-extrabold text-farm-800 uppercase tracking-tight">
                    BÀI VIẾT & CẨM NANG DU LỊCH
                </h2>
                <div class="w-16 h-1 bg-pomelo-500 mx-auto my-2 rounded-full"></div>
                <p class="text-xs md:text-sm text-gray-600">
                    Cập nhật kinh nghiệm đi du lịch sinh thái Nam Yên – Hải Vân, hoạt động mùa vụ vườn bưởi và ưu đãi mới nhất tại nông trại.
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-5">
                <article class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-gray-100">
                            <img src="https://lh3.googleusercontent.com/d/18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA" data-drive-id="18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA" onerror="handleDriveImgError(this, 'Bai+Viet+1')" alt="Kinh nghiệm nghỉ dưỡng Hương Bưởi Farmstay" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Kinh Nghiệm Nghỉ Dưỡng Cuối Tuần Tại Hương Bưởi Farmstay Đà Nẵng Từ A - Z
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed">
                                Hướng dẫn cung đường di chuyển đến TDP Nam Yên, P. Hải Vân và lịch trình vui chơi 2 ngày 1 đêm tiết kiệm nhất.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-farm-600 hover:text-farm-800 inline-flex items-center gap-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <article class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-gray-100">
                            <img src="https://lh3.googleusercontent.com/d/10w8TtqbWvE7eaWxOUsqL9SeBH8qqwoWB" data-drive-id="10w8TtqbWvE7eaWxOUsqL9SeBH8qqwoWB" onerror="handleDriveImgError(this, 'Bai+Viet+2')" alt="Mùa bưởi hữu cơ tại nông trại" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Khám Phá Khu Vườn Cây Ăn Trái Hữu Cơ Bưởi, Ổi, Mít Xanh Mướt Tại Nam Yên
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed">
                                Tận hưởng không gian thiên nhiên trong lành và tìm hiểu mô hình nông nghiệp xanh kết hợp du lịch sinh thái bền vững.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-farm-600 hover:text-farm-800 inline-flex items-center gap-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <article class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-gray-100">
                            <img src="https://lh3.googleusercontent.com/d/1bIAcH7KwypdN5T7c-B_OE1pHyKlBeIXk" data-drive-id="1bIAcH7KwypdN5T7c-B_OE1pHyKlBeIXk" onerror="handleDriveImgError(this, 'Bai+Viet+3')" alt="Ẩm thực bản địa Hòa Bắc" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Top Các Món Đặc Sản Bản Địa Nhất Định Phải Thử Khi Đến Hương Bưởi Farmstay
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed">
                                Thưởng thức gà đồi nướng than, cá suối tươi, rau rừng và tiệc nướng BBQ ấm cúng giữa tiết trời se lạnh.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-farm-600 hover:text-farm-800 inline-flex items-center gap-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <article class="bg-white rounded-xl border border-gray-200 overflow-hidden flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <div class="aspect-[16/10] w-full overflow-hidden bg-gray-100">
                            <img src="https://lh3.googleusercontent.com/d/1us5JbbU9WoEN1MDcdBtjm_voFVliBPW_" data-drive-id="1us5JbbU9WoEN1MDcdBtjm_voFVliBPW_" onerror="handleDriveImgError(this, 'Bai+Viet+4')" alt="Đốt lửa trại và lưu trú nhà sàn" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3 md:p-4">
                            <h3 class="product-title-full text-[13px] md:text-[15px] font-bold text-gray-900 mb-1.5">
                                Lưu Ý Quan Trọng Khi Đặt Lưu Trú Nhà Sàn Và Lều Cắm Trại Qua Đêm Cho Đoàn Đông
                            </h3>
                            <p class="text-[11.5px] md:text-xs text-gray-600 leading-relaxed">
                                Những quy định giữ gìn không gian yên tĩnh, bảo vệ vườn cây ăn quả và chuẩn bị cho đêm lửa trại trọn vẹn.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 md:px-4 md:pb-4 pt-1">
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-farm-600 hover:text-farm-800 inline-flex items-center gap-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FANPAGE + GOOGLE MAP TRANG CHỦ
         ========================================== -->
    <section id="bao-gia-lien-he" class="py-10 md:py-14 bg-farm-50 border-t border-gray-200">
        <div class="flatsome-container">
            <div class="text-center max-w-2xl mx-auto mb-8">
                <h2 class="text-lg md:text-2xl font-extrabold text-farm-800 uppercase tracking-tight">
                    ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ
                </h2>
                <div class="w-16 h-1 bg-pomelo-500 mx-auto my-2 rounded-full"></div>
                <p class="text-xs md:text-sm text-gray-600">
                    Quý du khách vui lòng để lại thông tin hoặc liên hệ trực tiếp Hotline <strong>0704.447.876</strong> để đặt phòng nhà sàn, lều trại và dịch vụ ăn uống chu đáo nhất.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
                <!-- Cột 1: Form Yêu Cầu & Báo Giá (5 cột) -->
                <div class="lg:col-span-5 bg-white p-5 md:p-6 rounded-2xl shadow-sm border border-gray-200">
                    <h3 class="text-base md:text-lg font-extrabold text-farm-800 mb-4 flex items-center gap-2">
                        <i class="fa-solid fa-paper-plane text-pomelo-500"></i>
                        <span>Form Yêu Cầu & Báo Giá Nhanh</span>
                    </h3>
                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                        <div>
                            <label class="block text-xs font-bold text-gray-700 mb-1">Họ và tên quý khách *</label>
                            <input type="text" id="qName" required placeholder="Nhập họ và tên của bạn" class="w-full px-3.5 py-2.5 text-xs md:text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-farm-600">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="qPhone" required placeholder="Ví dụ: 0905xxxxxx" class="w-full px-3.5 py-2.5 text-xs md:text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-farm-600">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Số lượng khách dự kiến</label>
                                <input type="number" id="qGuests" min="1" value="4" placeholder="Số người" class="w-full px-3.5 py-2.5 text-xs md:text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-farm-600">
                            </div>
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Ngày dự kiến đến</label>
                                <input type="date" id="qDate" class="w-full px-3.5 py-2.5 text-xs md:text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-farm-600">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Dịch vụ cần báo giá</label>
                                <select id="qService" class="w-full px-3.5 py-2.5 text-xs md:text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-farm-600 bg-white">
                                    <option value="Combo Lưu Trú Qua Đêm Trọn Gói">Combo Lưu Trú Qua Đêm Trọn Gói</option>
                                    <option value="Lưu Trú Nhà Sàn Gỗ Truyền Thống">Lưu Trú Nhà Sàn Gỗ Truyền Thống</option>
                                    <option value="Khu Nhà Lều Glamping Địa Trung Hải">Khu Nhà Lều Glamping Địa Trung Hải</option>
                                    <option value="Vé Tham Quan & Tắm Hồ Bơi Trong Ngày">Vé Tham Quan & Tắm Hồ Bơi Trong Ngày</option>
                                    <option value="Đặt Tiệc Nướng BBQ & Ẩm Thực Bản Địa">Đặt Tiệc Nướng BBQ & Ẩm Thực Bản Địa</option>
                                    <option value="Tổ Chức Sự Kiện, Lửa Trại & Team Building">Tổ Chức Sự Kiện, Lửa Trại & Team Building</option>
                                    <option value="Thuê Nguyên Khu Farmstay Cho Đoàn">Thuê Nguyên Khu Farmstay Cho Đoàn</option>
                                </select>
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-gray-700 mb-1">Yêu cầu chi tiết (Ăn uống, lửa trại, xe đưa đón...)</label>
                            <textarea id="qNote" rows="3" placeholder="Nhập ghi chú thêm nếu có..." class="w-full px-3.5 py-2 text-xs md:text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-farm-600"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3 rounded-xl bg-farm-600 hover:bg-farm-700 text-white font-bold text-xs md:text-sm shadow transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-check-circle"></i>
                            <span>GỬI YÊU CẦU NHẬN BÁO GIÁ</span>
                        </button>
                    </form>
                </div>

                <!-- Cột 2: Đưa Fanpage Ra Ngoài Trang Chủ (3.5 cột) -->
                <div class="lg:col-span-3 bg-white p-5 rounded-2xl shadow-sm border border-gray-200 flex flex-col justify-between">
                    <div>
                        <h3 class="text-base font-extrabold text-farm-800 mb-3 flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-blue-600"></i>
                            <span>Fanpage Chính Thức</span>
                        </h3>

                        <!-- Khung hiển thị trực quan Fanpage Hương Bưởi Farmstay -->
                        <div class="rounded-xl overflow-hidden border border-gray-200 mb-3 bg-gray-50">
                            <div class="relative h-28 w-full">
                                <img src="https://lh3.googleusercontent.com/d/18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA" data-drive-id="18rXHBciqNraxXia4s-7M-Y-FDm6jbqqA" onerror="handleDriveImgError(this, 'Fanpage+Cover')" alt="Bìa Fanpage Hương Bưởi Farmstay" class="w-full h-full object-cover">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-2.5">
                                    <img src="https://lh3.googleusercontent.com/d/1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq" data-drive-id="1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq" onerror="handleDriveImgError(this, 'Logo')" alt="Avatar Fanpage" class="w-11 h-11 rounded-full border-2 border-white bg-white object-contain shrink-0">
                                    <div class="text-white overflow-hidden">
                                        <a href="https://www.facebook.com/Huongbuoifarmstay" target="_blank" rel="noopener noreferrer" class="font-bold text-sm hover:underline block truncate">Hương Bưởi Farmstay</a>
                                        <span class="text-[11px] text-gray-200 block">@Huongbuoifarmstay • Du lịch sinh thái</span>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 space-y-2 text-xs text-gray-600">
                                <p class="leading-relaxed">
                                    Khu lưu trú sinh thái vườn bưởi, nhà sàn, lều trại, hồ bơi và ẩm thực dân dã tại TDP Nam Yên, P. Hải Vân, Đà Nẵng.
                                </p>
                                <div class="pt-1 flex items-center gap-2">
                                    <a href="https://www.facebook.com/Huongbuoifarmstay" target="_blank" rel="noopener noreferrer" class="w-full py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-semibold text-center text-xs transition inline-flex items-center justify-center gap-1.5">
                                        <i class="fa-brands fa-facebook-f"></i>
                                        <span>Theo Dõi & Nhắn Tin Fanpage</span>
                                    </a>
                                </div>
                            </div>
                        </div>

                        <!-- Nhúng Plugin Facebook Iframe chuẩn -->
                        <div class="w-full overflow-hidden rounded-lg border border-gray-100 flex justify-center bg-gray-50">
                            <iframe 
                                title="Facebook Fanpage Hương Bưởi Farmstay"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FHuongbuoifarmstay&tabs=timeline&width=300&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                width="300" 
                                height="180" 
                                style="border:none;overflow:hidden;max-width:100%;" 
                                scrolling="no" 
                                frameborder="0" 
                                allowfullscreen="true" 
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>
                    </div>
                </div>

                <!-- Cột 3: Đưa Ảnh & Bản Đồ Google Map Ra Ngoài Trang Chủ (4 cột) -->
                <div class="lg:col-span-4 bg-white p-5 rounded-2xl shadow-sm border border-gray-200">
                    <h3 class="text-base font-extrabold text-farm-800 mb-3 flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot text-red-600"></i>
                        <span>Bản Đồ Đường Đi Google Map</span>
                    </h3>
                    <p class="text-xs text-gray-600 mb-3">
                        <i class="fa-solid fa-location-dot text-farm-600 mr-1"></i>
                        <strong>Địa chỉ:</strong> TDP Nam Yên, P. Hải Vân, TP. Đà Nẵng
                    </p>

                    <!-- Bản đồ Google Maps trực tiếp ngoài trang chủ -->
                    <div class="w-full h-56 rounded-xl overflow-hidden border border-gray-200 mb-3 bg-gray-100">
                        <iframe 
                            title="Bản đồ Hương Bưởi Farmstay"
                            src="https://www.google.com/maps?q=H%C6%B0%C6%A1ng+B%C6%B0%E1%BB%9Fi+Farmstay+Nam+Y%C3%AAn+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed" 
                            width="100%" 
                            height="100%" 
                            style="border:0;" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>

                    <div class="flex flex-col sm:flex-row items-center justify-between gap-2 bg-farm-50 p-3 rounded-xl border border-farm-100">
                        <div class="text-xs text-gray-700">
                            <span class="font-bold block text-farm-800">Hương Bưởi Farmstay</span>
                            <span>Cách trung tâm Đà Nẵng ~30 phút</span>
                        </div>
                        <a href="https://share.google/jYVARnqoWvLHSfxOq" target="_blank" rel="noopener noreferrer" class="w-full sm:w-auto px-3.5 py-2 rounded-lg bg-farm-600 hover:bg-farm-700 text-white font-bold text-xs text-center whitespace-nowrap transition inline-flex items-center justify-center gap-1.5">
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span>Mở Google Maps</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC ĐỒNG HÀNH
         ========================================== -->
    <section id="doi-tac" class="py-9 bg-white border-t border-gray-200">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="text-base md:text-xl font-extrabold text-farm-800 uppercase tracking-tight">
                    ĐỐI TÁC ĐỒNG HÀNH & LIÊN KẾT DU LỊCH
                </h2>
                <div class="w-12 h-1 bg-pomelo-500 mx-auto my-1.5 rounded-full"></div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="p-3.5 rounded-xl bg-gray-50 border border-gray-200 flex flex-col items-center justify-center text-center hover:border-farm-500 transition">
                    <i class="fa-solid fa-building-columns text-xl text-farm-700 mb-1.5"></i>
                    <span class="text-xs font-bold text-gray-800">Du Lịch Đà Nẵng</span>
                    <span class="text-[10px] text-gray-500">Xúc tiến điểm đến xanh</span>
                </div>
                <div class="p-3.5 rounded-xl bg-gray-50 border border-gray-200 flex flex-col items-center justify-center text-center hover:border-farm-500 transition">
                    <i class="fa-solid fa-seedling text-xl text-farm-700 mb-1.5"></i>
                    <span class="text-xs font-bold text-gray-800">OCOP Hải Vân</span>
                    <span class="text-[10px] text-gray-500">Nông sản sạch địa phương</span>
                </div>
                <div class="p-3.5 rounded-xl bg-gray-50 border border-gray-200 flex flex-col items-center justify-center text-center hover:border-farm-500 transition">
                    <i class="fa-solid fa-earth-asia text-xl text-farm-700 mb-1.5"></i>
                    <span class="text-xs font-bold text-gray-800">Vietravel</span>
                    <span class="text-[10px] text-gray-500">Đối tác lữ hành</span>
                </div>
                <div class="p-3.5 rounded-xl bg-gray-50 border border-gray-200 flex flex-col items-center justify-center text-center hover:border-farm-500 transition">
                    <i class="fa-solid fa-compass text-xl text-farm-700 mb-1.5"></i>
                    <span class="text-xs font-bold text-gray-800">Saigontourist</span>
                    <span class="text-[10px] text-gray-500">Tour sinh thái miền Trung</span>
                </div>
                <div class="p-3.5 rounded-xl bg-gray-50 border border-gray-200 flex flex-col items-center justify-center text-center hover:border-farm-500 transition">
                    <i class="fa-solid fa-plane-departure text-xl text-farm-700 mb-1.5"></i>
                    <span class="text-xs font-bold text-gray-800">Traveloka & Klook</span>
                    <span class="text-[10px] text-gray-500">Nền tảng đặt dịch vụ</span>
                </div>
                <div class="p-3.5 rounded-xl bg-gray-50 border border-gray-200 flex flex-col items-center justify-center text-center hover:border-farm-500 transition">
                    <i class="fa-solid fa-people-group text-xl text-farm-700 mb-1.5"></i>
                    <span class="text-xs font-bold text-gray-800">CLB Farmstay Việt Nam</span>
                    <span class="text-[10px] text-gray-500">Cộng đồng du lịch xanh</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER (CHÂN TRANG CHUẨN MẪU SUỐI LƯƠNG HẢI VÂN PARK)
         ========================================== -->
    <footer class="bg-farm-900 text-gray-200 pt-10 pb-6 border-t border-farm-800 mt-auto">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-farm-800">
                <!-- Cột 1: Thông tin thương hiệu -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq" 
                            data-drive-id="1WSW7lXnC4deMFyDHMeWLbab8Ojwvtitq"
                            onerror="handleDriveImgError(this, 'Logo')"
                            alt="Logo Hương Bưởi Farmstay" 
                            class="w-10 h-10 rounded-full bg-white p-0.5 object-contain shrink-0"
                        >
                        <div>
                            <h3 class="text-sm font-extrabold text-white">HƯƠNG BƯỞI FARMSTAY</h3>
                            <p class="text-[11px] text-pomelo-400">huongbuoifarmstay.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-gray-300 leading-relaxed">
                        Khu du lịch sinh thái vườn cây ăn quả, nghỉ dưỡng nhà sàn, lều Glamping, hồ bơi ngoài trời và ẩm thực bản địa đặc sắc tại Đà Nẵng.
                    </p>
                </div>

                <!-- Cột 2: Thông tin liên hệ -->
                <div class="space-y-2.5 text-xs">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wider mb-2">THÔNG TIN LIÊN HỆ</h4>
                    <p class="flex items-start gap-2">
                        <i class="fa-solid fa-location-dot text-pomelo-400 mt-0.5 shrink-0"></i>
                        <span>Địa chỉ: TDP Nam Yên, P. Hải Vân, TP. Đà Nẵng</span>
                    </p>
                    <p class="flex items-center gap-2">
                        <i class="fa-solid fa-phone text-pomelo-400 shrink-0"></i>
                        <span>Hotline / Zalo: <a href="tel:0704447876" class="font-bold text-white hover:text-pomelo-400">0704.447.876</a></span>
                    </p>
                    <p class="flex items-center gap-2">
                        <i class="fa-solid fa-globe text-pomelo-400 shrink-0"></i>
                        <span>Website: <a href="https://huongbuoifarmstay.com" class="hover:text-pomelo-400">huongbuoifarmstay.com</a></span>
                    </p>
                    <p class="flex items-center gap-2">
                        <i class="fa-brands fa-facebook text-pomelo-400 shrink-0"></i>
                        <span>Fanpage: <a href="https://www.facebook.com/Huongbuoifarmstay" target="_blank" rel="noopener noreferrer" class="hover:text-pomelo-400">Hương Bưởi Farmstay</a></span>
                    </p>
                    <p class="flex items-center gap-2">
                        <i class="fa-solid fa-map-pin text-pomelo-400 shrink-0"></i>
                        <span>Bản đồ: <a href="https://share.google/jYVARnqoWvLHSfxOq" target="_blank" rel="noopener noreferrer" class="hover:text-pomelo-400 underline">Xem vị trí Google Maps</a></span>
                    </p>
                </div>

                <!-- Cột 3: Danh mục dịch vụ -->
                <div class="space-y-2 text-xs">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wider mb-2">DANH MỤC DỊCH VỤ</h4>
                    <ul class="space-y-1.5 text-gray-300">
                        <li><a href="#dich-vu" class="hover:text-pomelo-400 transition">• Vé vào cổng & Tham quan vườn bưởi</a></li>
                        <li><a href="#dich-vu" class="hover:text-pomelo-400 transition">• Đặt chòi nghỉ & Hồ bơi ngoài trời</a></li>
                        <li><a href="#luu-tru" class="hover:text-pomelo-400 transition">• Lưu trú nhà sàn gỗ & Lều Glamping</a></li>
                        <li><a href="#am-thuc" class="hover:text-pomelo-400 transition">• Ẩm thực gà nướng, cá suối & BBQ</a></li>
                        <li><a href="#tour-du-lich" class="hover:text-pomelo-400 transition">• Tour du lịch sinh thái Nam Yên</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Hỗ trợ & Quy định lưu trú -->
                <div class="space-y-2 text-xs">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wider mb-2">HỖ TRỢ & LƯU Ý</h4>
                    <ul class="space-y-1.5 text-gray-300">
                        <li>• Mở cửa đón khách tất cả các ngày trong tuần</li>
                        <li>• Vui lòng đặt trước 24h để phục vụ chu đáo nhất</li>
                        <li>• Không sử dụng loa kéo công suất lớn gây ồn</li>
                        <li>• Giữ gìn vệ sinh chung & bảo vệ cây ăn trái</li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-gray-400">
                <p>© 2026 HUONGBUOIFARMSTAY.COM. All rights reserved.</p>
                <p>TDP Nam Yên, Phường Hải Vân, Thành phố Đà Nẵng | SĐT: 0704.447.876</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên Máy tính & Điện thoại, không tràn viền
         ========================================== -->
    <div class="fixed bottom-4 right-3 md:bottom-6 md:right-5 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0704447876" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo" class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 md:px-3.5 md:py-2.5 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
            <span class="w-6 h-6 rounded-full bg-white text-blue-600 font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold hidden sm:inline">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/Huongbuoifarmstay" target="_blank" rel="noopener noreferrer" aria-label="Facebook Fanpage" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 md:px-3.5 md:py-2.5 rounded-full shadow-lg transition transform hover:-translate-y-0.5">
            <i class="fa-brands fa-facebook-f w-6 h-6 rounded-full bg-white/20 flex items-center justify-center text-xs shrink-0"></i>
            <span class="text-xs font-bold hidden sm:inline">Facebook</span>
        </a>

        <!-- Nút Gọi Hotline nổi bật -->
        <a href="tel:0704447876" aria-label="Gọi Hotline 0704.447.876" class="pulse-btn flex items-center gap-2 bg-farm-600 hover:bg-farm-700 text-white px-3.5 py-2.5 md:px-4 md:py-3 rounded-full shadow-xl border border-pomelo-400 transition">
            <i class="fa-solid fa-phone-volume text-pomelo-400 text-sm shrink-0"></i>
            <span class="text-xs md:text-sm font-extrabold whitespace-nowrap">0704.447.876</span>
        </a>
    </div>

    <!-- ==========================================
         HỘP THOẠI THÔNG BÁO (THAY THẾ ALERT)
         ========================================== -->
    <div id="customModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/60 p-4">
        <div class="bg-white rounded-2xl max-w-md w-full p-6 text-center shadow-2xl border border-farm-100">
            <div class="w-12 h-12 rounded-full bg-farm-100 text-farm-600 flex items-center justify-center mx-auto mb-3 text-xl">
                <i class="fa-solid fa-check"></i>
            </div>
            <h4 class="text-base md:text-lg font-extrabold text-gray-900 mb-2">Gửi Yêu Cầu Báo Giá Thành Công!</h4>
            <p id="modalMessage" class="text-xs md:text-sm text-gray-600 leading-relaxed mb-5">
                Cảm ơn quý khách đã liên hệ Hương Bưởi Farmstay. Chúng tôi sẽ gọi lại tư vấn và gửi báo giá chi tiết trong thời gian sớm nhất!
            </p>
            <div class="flex items-center justify-center gap-3">
                <a href="https://zalo.me/0704447876" target="_blank" rel="noopener noreferrer" class="px-4 py-2 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs transition">
                    Nhắn Zalo Ngay
                </a>
                <button onclick="closeCustomModal()" class="px-5 py-2 rounded-lg bg-farm-600 hover:bg-farm-700 text-white font-bold text-xs transition">
                    Đóng
                </button>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SLIDER, FALLBACK ẢNH DRIVE & FORM BÁO GIÁ
         ========================================== -->
    <script>
        // Xử lý dự phòng tự động cho ảnh Google Drive nếu link chính bị giới hạn băng thông
        function handleDriveImgError(imgEl, label) {
            const driveId = imgEl.getAttribute('data-drive-id');
            const triedThumb = imgEl.getAttribute('data-tried-thumb');
            if (driveId && !triedThumb) {
                imgEl.setAttribute('data-tried-thumb', 'true');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1200';
            } else {
                imgEl.onerror = null;
                imgEl.src = 'https://placehold.co/800x600/2d7226/ffffff?text=' + (label || 'Huong+Buoi+Farmstay');
            }
        }

        // Menu trên điện thoại
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        if (mobileMenuBtn && mobileMenu) {
            mobileMenuBtn.addEventListener('click', function () {
                mobileMenu.classList.toggle('hidden');
            });
            document.querySelectorAll('.mobile-nav-link').forEach(function (link) {
                link.addEventListener('click', function () {
                    mobileMenu.classList.add('hidden');
                });
            });
        }

        // Điều khiển 2 ảnh Banner tự trượt chuyên nghiệp (Đồng bộ cả Máy tính & Điện thoại)
        let currentSlide = 0;
        const totalSlides = 2;
        const desktopSlides = document.querySelectorAll('.desktop-slide');
        const mobileSlides = document.querySelectorAll('.mobile-slide');
        const dot0 = document.getElementById('dot-0');
        const dot1 = document.getElementById('dot-1');

        function renderBannerSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            desktopSlides.forEach((slide, idx) => {
                if (idx === currentSlide) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });
            mobileSlides.forEach((slide, idx) => {
                if (idx === currentSlide) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });
            if (dot0 && dot1) {
                if (currentSlide === 0) {
                    dot0.className = 'w-6 h-2 rounded-full bg-pomelo-400 transition-all';
                    dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                } else {
                    dot1.className = 'w-6 h-2 rounded-full bg-pomelo-400 transition-all';
                    dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function nextBanner() {
            renderBannerSlide(currentSlide + 1);
        }

        function prevBanner() {
            renderBannerSlide(currentSlide - 1);
        }

        function goToBanner(index) {
            renderBannerSlide(index);
        }

        // Tự động trượt mỗi 5 giây
        setInterval(nextBanner, 5000);

        // Chọn nhanh dịch vụ đưa xuống Form báo giá
        function selectServiceForQuote(serviceName) {
            const selectEl = document.getElementById('qService');
            const noteEl = document.getElementById('qNote');
            if (selectEl) {
                let matched = false;
                for (let i = 0; i < selectEl.options.length; i++) {
                    if (selectEl.options[i].value === serviceName) {
                        selectEl.selectedIndex = i;
                        matched = true;
                        break;
                    }
                }
                if (!matched && noteEl) {
                    noteEl.value = 'Tôi muốn nhận tư vấn & báo giá dịch vụ: ' + serviceName;
                }
            }
            const formSection = document.getElementById('bao-gia-lien-he');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // Xử lý gửi Form Yêu Cầu & Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const guests = document.getElementById('qGuests').value;
            const service = document.getElementById('qService').value;

            const modal = document.getElementById('customModal');
            const msg = document.getElementById('modalMessage');
            if (msg) {
                msg.innerHTML = 'Cảm ơn <strong>' + name + '</strong> (SĐT: <strong>' + phone + '</strong>) đã đăng ký <strong>' + service + '</strong> cho đoàn <strong>' + guests + ' khách</strong>.<br>Bộ phận đặt dịch vụ Hương Bưởi Farmstay (<strong>0704.447.876</strong>) sẽ liên hệ xác nhận ngay!';
            }
            if (modal) {
                modal.classList.remove('hidden');
                modal.classList.add('flex');
            }
            document.getElementById('quoteForm').reset();
        }

        function closeCustomModal() {
            const modal = document.getElementById('customModal');
            if (modal) {
                modal.classList.add('hidden');
                modal.classList.remove('flex');
            }
        }
    </script>
</body>
</html>
