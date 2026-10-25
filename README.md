<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mèo Thần Tài An Nhiên - 238 Diên Hồng, Đà Nẵng | meothantaiannhien.com</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            red: '#D91424',
                            gold: '#D4AF37',
                            darkGold: '#AA7C11',
                            cream: '#FFFBF0',
                            dark: '#1A1A1A'
                        }
                    },
                    fontFamily: {
                        sans: ['Montserrat', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Montserrat', sans-serif; }
        .hero-gradient { background: linear-gradient(135deg, #7f1d1d 0%, #b91c1c 50%, #991b1b 100%); }
    </style>
</head>
<body class="bg-stone-50 text-stone-800 antialiased">

    <!-- Top Announcement Bar -->
    <div class="bg-brand-red text-white text-xs sm:text-sm py-2 px-4 text-center font-medium">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-1">
            <span>✨ meothantaiannhien.com - Địa chỉ Mèo Thần Tài & Phong Thủy uy tín tại Đà Nẵng!</span>
            <div class="flex items-center gap-4">
                <a href="tel:0901956069" class="hover:underline flex items-center gap-1"><i class="fa-solid fa-phone"></i> Hotline: 0901.956.069</a>
                <span class="hidden md:inline">|</span>
                <span class="hidden md:inline">📍 238 Diên Hồng, Hòa Xuân, Đà Nẵng</span>
            </div>
        </div>
    </div>

    <!-- Main Navigation Header -->
    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur-md shadow-sm border-b border-stone-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo -->
                <a href="#trang-chu" class="flex items-center gap-3">
                    <div class="w-12 h-12 rounded-full bg-red-100 flex items-center justify-center border-2 border-brand-gold shadow-inner">
                        <i class="fa-solid fa-cat text-brand-red text-2xl"></i>
                    </div>
                    <div>
                        <span class="text-xl sm:text-2xl font-extrabold tracking-tight text-brand-red block leading-tight">MÈO THẦN TÀI AN NHIÊN</span>
                        <span class="text-xs text-stone-500 font-semibold tracking-widest uppercase">Chiêu Tài - Tấn Lộc - Bình An</span>
                    </div>
                </a>

                <!-- Desktop Navigation Menu -->
                <nav class="hidden lg:flex items-center gap-5 font-semibold text-xs uppercase text-stone-700">
                    <a href="#trang-chu" class="text-brand-red hover:text-brand-red transition">Trang Chủ</a>
                    <a href="#meo-khai-truong" class="hover:text-brand-red transition">Mèo Khai Trương</a>
                    <a href="#meo-tang-khai-truong" class="hover:text-brand-red transition">Mèo Tặng Khai Trương</a>
                    <a href="#meo-phu-quy" class="hover:text-brand-red transition">Mèo Phú Quý Gia Đình</a>
                    <a href="#vat-pham-phong-thuy" class="hover:text-brand-red transition">Vật Phẩm Phong Thủy</a>
                    <a href="#lien-he" class="hover:text-brand-red transition">Liên Hệ</a>
                </nav>

                <!-- Search & Cart Buttons -->
                <div class="flex items-center gap-3">
                    <button onclick="openCartModal()" class="relative p-2.5 rounded-full bg-stone-100 hover:bg-stone-200 text-stone-800 transition">
                        <i class="fa-solid fa-bag-shopping text-lg"></i>
                        <span id="cart-count" class="absolute -top-1 -right-1 bg-brand-red text-white text-[10px] w-5 h-5 rounded-full flex items-center justify-center font-bold">0</span>
                    </button>
                    <button onclick="toggleMobileMenu()" class="lg:hidden p-2.5 rounded-full bg-stone-100 text-stone-800 hover:bg-stone-200">
                        <i class="fa-solid fa-bars text-lg"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Nav Drawer -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-b border-stone-200 px-4 pt-2 pb-6 space-y-3 font-semibold text-sm">
            <a href="#trang-chu" class="block py-2 text-brand-red border-b border-stone-100">Trang Chủ</a>
            <a href="#meo-khai-truong" class="block py-2 text-stone-700 border-b border-stone-100">Mèo Khai Trương</a>
            <a href="#meo-tang-khai-truong" class="block py-2 text-stone-700 border-b border-stone-100">Mèo Tặng Khai Trương</a>
            <a href="#meo-phu-quy" class="block py-2 text-stone-700 border-b border-stone-100">Mèo Phú Quý Gia Đình</a>
            <a href="#vat-pham-phong-thuy" class="block py-2 text-stone-700 border-b border-stone-100">Vật Phẩm Phong Thủy</a>
            <a href="#lien-he" class="block py-2 text-stone-700">Liên Hệ</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="trang-chu" class="hero-gradient text-white py-16 lg:py-24 relative overflow-hidden">
        <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#d4af37_1px,transparent_1px)] [background-size:16px_16px]"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-6 text-center lg:text-left">
                    <span class="inline-block bg-amber-400 text-stone-900 px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-wider shadow-md">
                        ⭐ meothantaiannhien.com - 238 Diên Hồng, Đà Nẵng
                    </span>
                    <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-tight">
                        Thế Giới Mèo Thần Tài & Vật Phẩm Phong Thủy <span class="text-amber-300">An Nhiên</span>
                    </h1>
                    <p class="text-stone-200 text-base sm:text-lg max-w-xl mx-auto lg:mx-0">
                        Chuyên cung cấp các mẫu Mèo Thần Tài gốm sứ cao cấp vẫy tay khai trương, phát tài phát lộc, cùng vật phẩm phong thủy trấn trạch uy tín nhất Đà Nẵng.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start pt-2">
                        <a href="#meo-khai-truong" class="bg-amber-400 hover:bg-amber-300 text-stone-900 font-bold px-8 py-3.5 rounded-xl shadow-lg transition transform hover:-translate-y-0.5 text-center">
                            Xem Mèo Khai Trương
                        </a>
                        <a href="tel:0901956069" class="border-2 border-white/80 hover:bg-white hover:text-stone-900 text-white font-bold px-8 py-3.5 rounded-xl transition text-center">
                            <i class="fa-solid fa-phone-volume mr-2"></i> Hotline: 0901.956.069
                        </a>
                    </div>
                </div>
                <div class="flex justify-center">
                    <div class="relative w-full max-w-md bg-white/10 p-4 rounded-3xl backdrop-blur-sm border border-white/20 shadow-2xl">
                        <!-- Mẫu Mèo Thần Tài Gốm Sứ Tiêu Chuẩn -->
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Gốm Sứ An Nhiên Đà Nẵng" class="rounded-2xl w-full h-80 object-cover shadow-md">
                        <div class="absolute -bottom-4 -right-4 bg-white text-stone-900 p-4 rounded-2xl shadow-xl border border-stone-100 flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-red-100 flex items-center justify-center text-brand-red font-bold">
                                <i class="fa-solid fa-shield-halved"></i>
                            </div>
                            <div>
                                <p class="text-xs text-stone-500 font-medium">Cửa Hàng Uy Tín</p>
                                <p class="text-sm font-bold text-stone-800">Chuẩn Gốm Sứ Cao Cấp</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Feature Highlights -->
    <section class="py-12 bg-white border-b border-stone-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-6 text-center">
                <div class="p-6 rounded-2xl bg-stone-50 hover:bg-stone-100 transition border border-stone-100">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-full bg-red-50 text-brand-red flex items-center justify-center text-2xl shadow-sm">
                        <i class="fa-solid fa-truck-fast"></i>
                    </div>
                    <h3 class="font-bold text-stone-900 mb-1">Giao Hàng Đà Nẵng</h3>
                    <p class="text-xs text-stone-500">Miễn phí ship nội thành, giao nhanh trong ngày</p>
                </div>
                <div class="p-6 rounded-2xl bg-stone-50 hover:bg-stone-100 transition border border-stone-100">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-full bg-amber-50 text-amber-600 flex items-center justify-center text-2xl shadow-sm">
                        <i class="fa-solid fa-award"></i>
                    </div>
                    <h3 class="font-bold text-stone-900 mb-1">Mẫu Mã Đa Dạng</h3>
                    <p class="text-xs text-stone-500">Cập nhật mẫu mới liên tục chuẩn phong thủy</p>
                </div>
                <div class="p-6 rounded-2xl bg-stone-50 hover:bg-stone-100 transition border border-stone-100">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-full bg-emerald-50 text-emerald-600 flex items-center justify-center text-2xl shadow-sm">
                        <i class="fa-solid fa-gift"></i>
                    </div>
                    <h3 class="font-bold text-stone-900 mb-1">Tặng Kèm Hộp Quà</h3>
                    <p class="text-xs text-stone-500">Hỗ trợ viết thiệp mừng, trang trí nơ khai trương</p>
                </div>
                <div class="p-6 rounded-2xl bg-stone-50 hover:bg-stone-100 transition border border-stone-100">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-full bg-blue-50 text-blue-600 flex items-center justify-center text-2xl shadow-sm">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <h3 class="font-bold text-stone-900 mb-1">Tư Vấn Phong Thủy</h3>
                    <p class="text-xs text-stone-500">Hỗ trợ chọn mèo hợp tuổi, hợp mệnh gia chủ</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Products Section -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 space-y-20">

        <!-- Category 1: Mèo Thần Tài Khai Trương -->
        <section id="meo-khai-truong">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-8 border-b border-stone-200 pb-4">
                <div>
                    <span class="text-brand-red font-bold text-xs uppercase tracking-wider block mb-1">DANH MỤC TRỌNG TÂM</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-stone-900">Mèo Thần Tài Khai Trương (Hồng Phát)</h2>
                </div>
                <span class="text-xs text-stone-500 mt-2 md:mt-0 font-medium">Bày trí quầy thu ngân, cửa hàng, công ty</span>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Product 1 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Đại Cát Đại Lợi" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                        <span class="absolute top-3 left-3 bg-brand-red text-white text-xs font-bold px-2.5 py-1 rounded-lg shadow">Bán Chạy</span>
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Mèo Khai Trương</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Đại Cát Đại Lợi Vẫy Tay Vàng Kim</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">750.000 ₫</span>
                                <span class="text-xs text-stone-400 line-through">890.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Đại Cát Đại Lợi', 750000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Thiên Kim Vạn Lượng" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                        <span class="absolute top-3 left-3 bg-amber-500 text-stone-900 text-xs font-bold px-2.5 py-1 rounded-lg shadow">VIP</span>
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Mèo Khai Trương</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Thiên Kim Vạn Lượng Cỡ Lớn (35cm)</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">1.350.000 ₫</span>
                                <span class="text-xs text-stone-400 line-through">1.550.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Thiên Kim Vạn Lượng', 1350000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Kim Ngưu Cát Tường" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Mèo Khai Trương</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Kim Ngưu Cát Tường Mừng Khai Trương</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">890.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Kim Ngưu Cát Tường', 890000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 4 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Phú Quý Viên Mãn" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                        <span class="absolute top-3 left-3 bg-brand-red text-white text-xs font-bold px-2.5 py-1 rounded-lg shadow">Hot</span>
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Mèo Khai Trương</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Phú Quý Viên Mãn Tay Cầm Hồ Lô Vàng</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">620.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Phú Quý Viên Mãn', 620000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Category 2: Mèo Thần Tài Tặng Khai Trương -->
        <section id="meo-tang-khai-truong">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-8 border-b border-stone-200 pb-4">
                <div>
                    <span class="text-brand-red font-bold text-xs uppercase tracking-wider block mb-1">QUÀ TẶNG Ý NGHĨA</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-stone-900">Mèo Thần Tài Tặng Khai Trương Cửa Hàng, Quán Cà Phê</h2>
                </div>
                <span class="text-xs text-stone-500 mt-2 md:mt-0 font-medium">Bao gồm hộp quà, thiệp chúc mừng & nơ đỏ</span>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Gift 1 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Tặng Khai Trương Quán Cà Phê" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Quà Tặng Khai Trương</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Quà Tặng Khai Trương Quán Cà Phê</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">820.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Tặng Khai Trương Quán Cà Phê', 820000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Gift 2 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Tặng Khai Trương Shop Thời Trang" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Quà Tặng Khai Trương</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Hứng Lộc Mừng Khai Trương Shop</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">950.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Hứng Lộc Khai Trương Shop', 950000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Gift 3 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Tặng Khai Trương Spa Salon" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Quà Tặng Khai Trương</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Cát Tường Mừng Khai Trương Spa / Salon</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">780.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Khai Trương Spa', 780000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Gift 4 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Bộ Quà Tặng Mèo Tài Lộc" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Quà Tặng Khai Trương</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Song Long Biểu Trưng Quà Tặng</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">1.150.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Song Long Quà Tặng', 1150000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Category 3: Mèo Phú Quý Gia Đình -->
        <section id="meo-phu-quy">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-8 border-b border-stone-200 pb-4">
                <div>
                    <span class="text-brand-red font-bold text-xs uppercase tracking-wider block mb-1">DANH MỤC GIA ĐÌNH</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-stone-900">Mèo Thần Tài Phú Quý & Bình An Gia Đình</h2>
                </div>
                <span class="text-xs text-stone-500 mt-2 md:mt-0 font-medium">Bày phòng khách, bàn làm việc, nhà cửa</span>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Product 1 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Bình An Hạnh Phúc" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Mèo Phú Quý</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Gia Đình Bình An Hạnh Phúc Gốm Sứ</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">580.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Bình An Hạnh Phúc', 580000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Hứng Lộc Vạn Sự Như Ý" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Mèo Phú Quý</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Hứng Lộc Vạn Sự Như Ý</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">690.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Vạn Sự Như Ý', 690000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Sức Khỏe & Trường Thọ" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Mèo Phú Quý</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Đào Tiên Trường Thọ Sức Khỏe</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">640.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Đào Tiên Trường Thọ', 640000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 4 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Mèo Thần Tài Tài Lộc Gấp Bội" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Mèo Phú Quý</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Mèo Thần Tài Song Long Biểu Trưng Phát Tài</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">920.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Mèo Thần Tài Song Long Phát Tài', 920000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Category 4: Vật Phẩm Phong Thủy (Tỳ Hưu, Thiềm Thừ, Bát Tụ Bảo) -->
        <section id="vat-pham-phong-thuy">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-8 border-b border-stone-200 pb-4">
                <div>
                    <span class="text-brand-red font-bold text-xs uppercase tracking-wider block mb-1">LINH VẬT TRẤN TRẠCH</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-stone-900">Vật Phẩm Phong Thủy (Tỳ Hưu, Thiềm Thừ, Bát Tụ Bảo)</h2>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Linh vật 1 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Cặp Tỳ Hưu Đá Hoàng Long" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Vật Phẩm Phong Thủy</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Cặp Tỳ Hưu Trấn Trạch Chiêu Tài – Vàng Hoàng Long</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">795.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Cặp Tỳ Hưu Trấn Trạch Chiêu Tài', 795000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Linh vật 2 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Thiềm Thừ Ngậm Tiền" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Vật Phẩm Phong Thủy</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Thiềm Thừ (Cóc Ba Chân) Ngậm Tiền Chiêu Tài Lộc</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">680.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Thiềm Thừ Ngậm Tiền', 680000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Linh vật 3 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition border border-stone-200 overflow-hidden flex flex-col">
                    <div class="relative bg-stone-100 overflow-hidden group">
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/04/meo-than-tai-mini-tien-da-da-tt0409.jpeg" alt="Bát Tụ Bảo Chiêu Tài" class="w-full h-64 object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-5 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <span class="text-xs text-stone-400 font-semibold uppercase">Vật Phẩm Phong Thủy</span>
                            <h3 class="font-bold text-stone-900 text-base mt-1 line-clamp-2">Bát Tụ Bảo Tụ Tài Lộc Đặt Bàn Thần Tài Thu Ngân</h3>
                        </div>
                        <div>
                            <div class="flex items-baseline gap-2">
                                <span class="text-brand-red font-extrabold text-lg">890.000 ₫</span>
                            </div>
                            <button onclick="addToCart('Bát Tụ Bảo Chiêu Tài', 890000)" class="mt-3 w-full bg-stone-900 hover:bg-brand-red text-white py-2.5 rounded-xl font-bold text-sm transition shadow-md flex items-center justify-center gap-2">
                                <i class="fa-solid fa-cart-plus"></i> Thêm Vào Giỏ
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Map & Contact Info Section -->
    <section id="lien-he" class="bg-stone-900 text-white py-16 mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <span class="text-brand-gold font-bold text-xs uppercase tracking-wider block">GHÉ THĂM CỬA HÀNG CHÚNG TÔI</span>
                    <h2 class="text-3xl font-extrabold">Mèo Thần Tài An Nhiên - Đà Nẵng</h2>
                    <p class="text-stone-300 text-sm leading-relaxed">
                        Quý khách hàng tại Đà Nẵng có thể ghé trực tiếp cửa hàng tại 238 Diên Hồng để lựa chọn những chú mèo thần tài gốm sứ cao cấp và vật phẩm phong thủy đẹp mắt nhất. Website chính thức: <span class="text-amber-400 font-bold">meothantaiannhien.com</span>
                    </p>
                    <div class="space-y-4 pt-2">
                        <div class="flex items-start gap-4">
                            <div class="w-10 h-10 rounded-full bg-red-900/50 text-brand-gold flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Địa chỉ cửa hàng:</h4>
                                <p class="text-stone-300 text-sm">238 Diên Hồng, Phường Hòa Xuân, Tp. Đà Nẵng</p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="w-10 h-10 rounded-full bg-red-900/50 text-brand-gold flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Số điện thoại / Hotline:</h4>
                                <p class="text-stone-300 text-sm"><a href="tel:0901956069" class="hover:text-amber-400 font-semibold">0901.956.069</a></p>
                            </div>
                        </div>
                        <div class="flex items-start gap-4">
                            <div class="w-10 h-10 rounded-full bg-red-900/50 text-brand-gold flex items-center justify-center flex-shrink-0 mt-1">
                                <i class="fa-solid fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-sm">Giờ mở cửa:</h4>
                                <p class="text-stone-300 text-sm">08:00 – 21:30 (Tất cả các ngày trong tuần)</p>
                            </div>
                        </div>
                    </div>
                    <div class="pt-4 flex flex-wrap gap-4">
                        <a href="https://www.facebook.com/profile.php?id=61564410320617" target="_blank" class="bg-blue-600 hover:bg-blue-700 text-white px-5 py-2.5 rounded-xl font-bold text-sm transition flex items-center gap-2">
                            <i class="fa-brands fa-facebook"></i> Fanpage Facebook
                        </a>
                        <a href="tel:0901956069" class="bg-brand-red hover:bg-red-700 text-white px-5 py-2.5 rounded-xl font-bold text-sm transition flex items-center gap-2">
                            <i class="fa-solid fa-phone"></i> Gọi 0901.956.069
                        </a>
                    </div>
                </div>

                <!-- Google Map Container -->
                <div class="bg-stone-800 rounded-3xl p-4 border border-stone-700 h-96 flex flex-col justify-center items-center text-center relative overflow-hidden shadow-2xl">
                    <div class="absolute inset-0 opacity-40 bg-[radial-gradient(#444_1px,transparent_1px)] [background-size:20px_20px]"></div>
                    <div class="relative z-10 space-y-4 p-6">
                        <div class="w-16 h-16 mx-auto bg-brand-red rounded-full flex items-center justify-center text-white text-2xl shadow-lg animate-bounce">
                            <i class="fa-solid fa-store"></i>
                        </div>
                        <h3 class="font-bold text-xl text-white">Mèo Thần Tài An Nhiên</h3>
                        <p class="text-stone-300 text-sm max-w-sm">238 Diên Hồng, Phường Hòa Xuân, Tp. Đà Nẵng</p>
                        <a href="https://maps.google.com/?q=238+Dien+Hong+Hoa+Xuan+Da+Nang" target="_blank" class="inline-block bg-amber-400 hover:bg-amber-300 text-stone-900 font-bold px-6 py-2.5 rounded-xl text-sm transition shadow">
                            <i class="fa-solid fa-map-location-dot mr-2"></i> Mở Bản Đồ Google Maps
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-stone-950 text-stone-400 py-10 border-t border-stone-800 text-xs sm:text-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center space-y-4">
            <p class="font-bold text-stone-200 text-base">MÈO THẦN TÀI AN NHIÊN - MEOTHANTAIANNHIEN.COM</p>
            <p>Địa chỉ: 238 Diên Hồng, Phường Hòa Xuân, Tp. Đà Nẵng | Điện thoại: 0901.956.069</p>
            <p class="text-stone-500">© 2026 meothantaiannhien.com. All rights reserved.</p>
        </div>
    </footer>

    <!-- Cart Slide Modal -->
    <div id="cart-modal" class="fixed inset-0 z-50 bg-black/60 backdrop-blur-sm hidden flex justify-end">
        <div class="bg-white w-full max-w-md h-full shadow-2xl flex flex-col justify-between p-6">
            <div class="space-y-6">
                <div class="flex items-center justify-between border-b border-stone-200 pb-4">
                    <h3 class="font-bold text-stone-900 text-lg flex items-center gap-2">
                        <i class="fa-solid fa-bag-shopping text-brand-red"></i> Giỏ Hàng Của Bạn
                    </h3>
                    <button onclick="closeCartModal()" class="text-stone-400 hover:text-stone-700 text-xl font-bold p-1">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>
                <div id="cart-items-list" class="space-y-4 max-h-[60vh] overflow-y-auto pr-2">
                    <p class="text-stone-500 text-center py-8">Giỏ hàng đang trống.</p>
                </div>
            </div>
            <div class="border-t border-stone-200 pt-4 space-y-4">
                <div class="flex justify-between items-center font-bold text-stone-900 text-base">
                    <span>Tổng tiền:</span>
                    <span id="cart-total-price" class="text-brand-red text-xl">0 ₫</span>
                </div>
                <button onclick="checkout()" class="w-full bg-brand-red hover:bg-red-700 text-white font-bold py-3.5 rounded-xl transition shadow-lg text-center">
                    Gửi Đơn Hàng / Đặt Mua
                </button>
            </div>
        </div>
    </div>

    <!-- Notification Toast -->
    <div id="toast" class="fixed bottom-6 right-6 z-50 bg-stone-900 text-white px-5 py-3 rounded-xl shadow-2xl transform translate-y-24 opacity-0 transition duration-300 flex items-center gap-3 border border-stone-700">
        <i class="fa-solid fa-circle-check text-emerald-400 text-lg"></i>
        <span id="toast-msg" class="text-sm font-semibold">Đã thêm vào giỏ hàng thành công!</span>
    </div>

    <!-- JavaScript for interactivity & Cart logic -->
    <script>
        function toggleMobileMenu() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        }

        let cart = [];

        function addToCart(name, price) {
            const existingItem = cart.find(item => item.name === name);
            if (existingItem) {
                existingItem.qty += 1;
            } else {
                cart.push({ name, price, qty: 1 });
            }
            updateCartUI();
            showToast(`Đã thêm "${name}" vào giỏ hàng!`);
        }

        function updateCartUI() {
            const countEl = document.getElementById('cart-count');
            const listEl = document.getElementById('cart-items-list');
            const totalEl = document.getElementById('cart-total-price');

            const totalCount = cart.reduce((sum, item) => sum + item.qty, 0);
            countEl.textContent = totalCount;

            if (cart.length === 0) {
                listEl.innerHTML = '<p class="text-stone-500 text-center py-8">Giỏ hàng đang trống.</p>';
                totalEl.textContent = '0 ₫';
                return;
            }

            let html = '';
            let totalPrice = 0;

            cart.forEach((item, index) => {
                totalPrice += item.price * item.qty;
                html += `
                    <div class="flex items-center justify-between gap-4 bg-stone-50 p-3 rounded-xl border border-stone-100">
                        <div class="flex-1">
                            <h4 class="font-bold text-stone-800 text-sm">${item.name}</h4>
                            <p class="text-xs text-brand-red font-semibold mt-0.5">${item.price.toLocaleString('vi-VN')} ₫ x ${item.qty}</p>
                        </div>
                        <div class="flex items-center gap-2">
                            <button onclick="changeQty(${index}, 1)" class="w-7 h-7 rounded-lg bg-white border border-stone-300 font-bold text-stone-700 hover:bg-stone-100">+</button>
                            <button onclick="changeQty(${index}, -1)" class="w-7 h-7 rounded-lg bg-white border border-stone-300 font-bold text-stone-700 hover:bg-stone-100">-</button>
                        </div>
                    </div>
                `;
            });

            listEl.innerHTML = html;
            totalEl.textContent = totalPrice.toLocaleString('vi-VN') + ' ₫';
        }

        function changeQty(index, delta) {
            cart[index].qty += delta;
            if (cart[index].qty <= 0) {
                cart.splice(index, 1);
            }
            updateCartUI();
        }

        function openCartModal() {
            document.getElementById('cart-modal').classList.remove('hidden');
        }

        function closeCartModal() {
            document.getElementById('cart-modal').classList.add('hidden');
        }

        function checkout() {
            if (cart.length === 0) {
                showToast('Giỏ hàng của bạn đang trống!');
                return;
            }
            alert('Cảm ơn bạn đã đặt hàng tại Mèo Thần Tài An Nhiên (meothantaiannhien.com)! Nhân viên cửa hàng tại 238 Diên Hồng, Đà Nẵng sẽ liên hệ qua SĐT 0901.956.069 để xác nhận đơn hàng ngay.');
            cart = [];
            updateCartUI();
            closeCartModal();
        }

        function showToast(msg) {
            const toast = document.getElementById('toast');
            const msgEl = document.getElementById('toast-msg');
            msgEl.textContent = msg;
            toast.classList.remove('translate-y-24', 'opacity-0');
            setTimeout(() => {
                toast.classList.add('translate-y-24', 'opacity-0');
            }, 3000);
        }
    </script>
</body>
</html>
