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
                        <!-- Ảnh Hero đổi sang hình mèo thực tế từ meothantaikhaitruong.com -->
                        <img src="https://meothantaikhaitruong.com/wp-content/uploads/2024/10/meo-than-tai-vay-tay-bat-phuong-lai-tai-tt11m05.jpg" alt="Mèo Thần Tài Gốm Sứ An Nhiên Đà Nẵng" class="rounded-2xl w-full h-80 object-cover shadow-md">
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
                    <span class="text-brand-red font-bold text-xs uppercase tracking-wider block mb-1">DAN
