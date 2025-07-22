دریچه => اولین و بزرگترین سایت فروش آنلاین همه نوع کالا در افغانستان.
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>دریچه - بازار آنلاین افغانستان</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800;900&display=swap');
        
        * {
            font-family: 'Vazirmatn', sans-serif;
        }
        
        .logo-3d {
            font-family: 'Vazirmatn', sans-serif;
            font-weight: 900;
            font-size: 2.5rem;
            background: linear-gradient(45deg, #1e40af, #3b82f6, #60a5fa);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            letter-spacing: 2px;
            transform: perspective(500px) rotateX(15deg);
        }
        
        .category-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .product-card:hover {
            transform: scale(1.02);
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .search-advanced {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
        }
        
        .search-advanced.active {
            max-height: 300px;
        }
        
        .mobile-menu {
            transform: translateX(100%);
            transition: transform 0.3s ease;
        }
        
        .mobile-menu.active {
            transform: translateX(0);
        }
        
        .dropdown:hover .dropdown-menu {
            display: block;
        }
        
        .flash-sale {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }
        
        .lang-switch {
            position: relative;
        }
        
        .lang-dropdown {
            display: none;
            position: absolute;
            top: 100%;
            right: 0;
            background: white;
            border: 1px solid #e5e7eb;
            border-radius: 8px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            z-index: 50;
        }
        
        .lang-switch:hover .lang-dropdown {
            display: block;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-lg sticky top-0 z-50">
        <!-- Top Bar -->
        <div class="bg-blue-600 text-white py-2">
            <div class="container mx-auto px-4 flex justify-between items-center text-sm">
                <div class="flex items-center space-x-4 space-x-reverse">
                    <span>📞 +93 708 901 903</span>
                    <span>✉️ info@daricha.af</span>
                </div>
                <div class="flex items-center space-x-4 space-x-reverse">
                    <div class="lang-switch">
                        <button class="flex items-center space-x-1 space-x-reverse hover:text-blue-200">
                            <span>🇦🇫 فارسی/دری</span>
                            <i class="fas fa-chevron-down text-xs"></i>
                        </button>
                        <div class="lang-dropdown">
                            <a href="#" class="block px-4 py-2 hover:bg-gray-100 text-gray-800">🇦🇫 فارسی/دری</a>
                            <a href="#" class="block px-4 py-2 hover:bg-gray-100 text-gray-800">🇺🇸 English</a>
                        </div>
                    </div>
                    <span>ارسال رایگان برای خرید بالای 1000 افغانی</span>
                </div>
            </div>
        </div>
        
        <!-- Main Header -->
        <div class="container mx-auto px-4 py-4">
            <div class="flex items-center justify-between">
                <!-- Logo -->
                <div class="flex items-center">
                    <h1 class="logo-3d">دریچه</h1>
                    <span class="text-sm text-gray-500 mr-2">بازار آنلاین افغانستان</span>
                </div>
                
                <!-- Search Bar -->
                <div class="flex-1 max-w-2xl mx-8">
                    <div class="relative">
                        <div class="flex">
                            <input type="text" id="searchInput" placeholder="جستجو در میان هزاران محصول..." 
                                   class="w-full px-4 py-3 border-2 border-gray-300 rounded-r-lg focus:border-blue-500 focus:outline-none">
                            <button class="bg-blue-600 text-white px-6 py-3 rounded-l-lg hover:bg-blue-700 transition-colors">
                                <i class="fas fa-search"></i>
                            </button>
                        </div>
                        <button id="advancedSearchBtn" class="absolute left-12 top-1/3 transform -translate-y-1/3 text-gray-500 hover:text-blue-600">
                            <i class="fas fa-sliders-h"></i>
                        </button>
                    </div>
                    
                    <!-- Advanced Search -->
                    <div id="advancedSearch" class="search-advanced bg-white border border-gray-120 rounded-lg mt-2 p-4">
                        <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                            <select class="border border-gray-200 rounded px-3 py-2">
                                <option>همه دسته‌ها</option>
                                <option>لباس و پوشاک</option>
                                <option>دیجیتال</option>
                                <option>لوازم خانه</option>
                                <option>مبل و فرنیچیر</option>
                                <option>املاک</option>
                                <option>الکترونیک</option>
                                <option>خوراک</option>
                                <option>میوه خشک</option>
                                <option>کتاب</option>
                                <option>تزئینی</option>
                                <option>وسایل نقلیه</option>
                            </select>
                            <select class="border border-gray-200 rounded px-3 py-2">
                                <option>همه ولایات</option>
                                <option>کابل</option>
                                <option>هرات</option>
                                <option>مزار شریف</option>
                                <option>قندهار</option>
                                <option>جلال آباد</option>
                                <option>کندز</option>
                                <option>غزنی</option>
                                <option>بامیان</option>
                                <option>فراه</option>
                                <option>لغمان</option>
                                <option>پکتیا</option>
                                <option>خوست</option>
                                <option>کنر</option>
                                <option>نورستان</option>
                                <option>بدخشان</option>
                                <option>تخار</option>
                                <option>بغلان</option>
                                <option>سمنگان</option>
                                <option>سرپل</option>
                                <option>جوزجان</option>
                                <option>فاریاب</option>
                                <option>بادغیس</option>
                                <option>غور</option>
                                <option>دایکندی</option>
                                <option>اروزگان</option>
                                <option>زابل</option>
                                <option>هلمند</option>
                                <option>نیمروز</option>
                                <option>پکتیکا</option>
                                <option>میدان وردک</option>
                                <option>لوگر</option>
                                <option>کاپیسا</option>
                                <option>پروان</option>
                                <option>پنجشیر</option>
                            </select>
                            <div class="flex space-x-2 space-x-reverse">
                                <input type="number" placeholder="حداقل قیمت" class="border border-gray-200 rounded px-2 py-1/2 w-1/2">
                                <input type="number" placeholder="حداکثر قیمت" class="border border-gray-200 rounded px-2 py-1/2 w-1/2">
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- User Actions -->
                <div class="flex items-center space-x-4 space-x-reverse">
                    <button class="relative text-gray-600 hover:text-blue-600">
                        <i class="fas fa-heart text-xl"></i>
                        <span class="absolute -top-2 -right-2 bg-red-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center">3</span>
                    </button>
                    <button class="relative text-gray-600 hover:text-blue-600">
                        <i class="fas fa-shopping-cart text-xl"></i>
                        <span class="absolute -top-2 -right-2 bg-blue-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center">5</span>
                    </button>
                    <div class="flex space-x-2 space-x-reverse">
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            ورود
                        </button>
                        <button class="border border-blue-600 text-blue-600 px-4 py-2 rounded-lg hover:bg-blue-50 transition-colors">
                            ثبت نام
                        </button>
                    </div>
                </div>
                
                <!-- Mobile Menu Button -->
                <button id="mobileMenuBtn" class="md:hidden text-gray-600">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
        
        <!-- Navigation -->
        <nav class="bg-gray-100 border-t">
            <div class="container mx-auto px-4">
                <div class="flex items-center justify-between py-3">
                    <div class="dropdown relative">
                        <button class="flex items-center space-x-2 space-x-reverse bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700">
                            <i class="fas fa-bars"></i>
                            <span>همه دسته‌ها</span>
                            <i class="fas fa-chevron-down"></i>
                        </button>
                        <div class="dropdown-menu absolute top-full right-0 bg-white border border-gray-200 rounded-lg shadow-lg w-64 z-40" style="display: none;">
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-tshirt text-blue-600"></i>
                                <span>لباس و پوشاک</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-laptop text-blue-600"></i>
                                <span>دیجیتال</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-home text-blue-600"></i>
                                <span>لوازم خانه</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-couch text-blue-600"></i>
                                <span>مبل و فرنیچیر</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-building text-blue-600"></i>
                                <span>املاک</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-tv text-blue-600"></i>
                                <span>الکترونیک</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-utensils text-blue-600"></i>
                                <span>خوراک</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-apple-alt text-blue-600"></i>
                                <span>میوه خشک</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-book text-blue-600"></i>
                                <span>کتاب</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50 border-b">
                                <i class="fas fa-gem text-blue-600"></i>
                                <span>تزئینی</span>
                            </a>
                            <a href="#" class="flex items-center space-x-3 space-x-reverse px-4 py-3 hover:bg-gray-50">
                                <i class="fas fa-car text-blue-600"></i>
                                <span>وسایل نقلیه</span>
                            </a>
                        </div>
                    </div>
                    
                    <div class="hidden md:flex items-center space-x-8 space-x-reverse">
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition-colors">صفحه اصلی</a>
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition-colors">فروشگاه</a>
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition-colors">پیشنهادات ویژه</a>
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition-colors">فروشنده شوید</a>
                        <a href="#" class="text-gray-700 hover:text-blue-600 transition-colors">تماس با ما</a>
                    </div>
                    
                    <div class="flex items-center space-x-4 space-x-reverse">
                        <span class="flash-sale bg-red-500 text-white px-3 py-1 rounded-full text-sm">
                            🔥 فروش ویژه
                        </span>
                        <span class="text-sm text-gray-600">📦 ارسال سریع</span>
                    </div>
                </div>
            </div>
        </nav>
    </header>

    <!-- Mobile Menu -->
    <div id="mobileMenu" class="mobile-menu fixed top-0 right-0 w-80 h-full bg-white shadow-lg z-50 md:hidden">
        <div class="p-4 border-b">
            <div class="flex items-center justify-between">
                <h3 class="text-lg font-bold">منو</h3>
                <button id="closeMobileMenu" class="text-gray-600">
                    <i class="fas fa-times text-xl"></i>
                </button>
            </div>
        </div>
        <div class="p-4">
            <div class="space-y-4">
                <a href="#" class="block py-2 text-gray-700 hover:text-blue-600">صفحه اصلی</a>
                <a href="#" class="block py-2 text-gray-700 hover:text-blue-600">فروشگاه</a>
                <a href="#" class="block py-2 text-gray-700 hover:text-blue-600">پیشنهادات ویژه</a>
                <a href="#" class="block py-2 text-gray-700 hover:text-blue-600">فروشنده شوید</a>
                <a href="#" class="block py-2 text-gray-700 hover:text-blue-600">تماس با ما</a>
            </div>
        </div>
    </div>

    <!-- Hero Section -->
    <section class="hero-gradient py-16">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-center">
                <div class="text-white">
                    <h2 class="text-4xl md:text-5xl font-bold mb-4">
                        بزرگترین بازار آنلاین افغانستان
                    </h2>
                    <p class="text-xl mb-6 opacity-90">
                        هزاران محصول با کیفیت، قیمت مناسب و ارسال سریع در سراسر کشور
                    </p>
                    <div class="flex space-x-4 space-x-reverse">
                        <button class="bg-white text-blue-600 px-8 py-3 rounded-lg font-bold hover:bg-gray-100 transition-colors">
                            شروع خرید
                        </button>
                        <button class="border-2 border-white text-white px-8 py-3 rounded-lg font-bold hover:bg-white hover:text-blue-600 transition-colors">
                            فروشنده شوید
                        </button>
                    </div>
                </div>
                <div class="text-center">
                    <div class="bg-white/10 backdrop-blur-sm rounded-2xl p-8">
                        <div class="grid grid-cols-2 gap-4 text-white text-center">
                            <div>
                                <div class="text-3xl font-bold">50K+</div>
                                <div class="text-sm opacity-80">محصولات</div>
                            </div>
                            <div>
                                <div class="text-3xl font-bold">10K+</div>
                                <div class="text-sm opacity-80">فروشندگان</div>
                            </div>
                            <div>
                                <div class="text-3xl font-bold">100K+</div>
                                <div class="text-sm opacity-80">مشتریان</div>
                            </div>
                            <div>
                                <div class="text-3xl font-bold">34</div>
                                <div class="text-sm opacity-80">ولایات</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Categories Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">دسته‌بندی محصولات</h2>
                <p class="text-gray-600">انتخاب از میان هزاران محصول در دسته‌های مختلف</p>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-6">
                <div class="category-card bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-tshirt text-3xl text-blue-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">لباس و پوشاک</h3>
                    <p class="text-sm text-gray-600 mt-1">2,500+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-purple-50 to-purple-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-laptop text-3xl text-purple-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">دیجیتال</h3>
                    <p class="text-sm text-gray-600 mt-1">1,800+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-green-50 to-green-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-home text-3xl text-green-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">لوازم خانه</h3>
                    <p class="text-sm text-gray-600 mt-1">3,200+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-orange-50 to-orange-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-couch text-3xl text-orange-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">مبل و فرنیچیر</h3>
                    <p class="text-sm text-gray-600 mt-1">900+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-red-50 to-red-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-building text-3xl text-red-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">املاک</h3>
                    <p class="text-sm text-gray-600 mt-1">1,200+ آگهی</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-indigo-50 to-indigo-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-tv text-3xl text-indigo-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">الکترونیک</h3>
                    <p class="text-sm text-gray-600 mt-1">1,500+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-yellow-50 to-yellow-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-utensils text-3xl text-yellow-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">خوراک</h3>
                    <p class="text-sm text-gray-600 mt-1">800+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-pink-50 to-pink-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-apple-alt text-3xl text-pink-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">میوه خشک</h3>
                    <p class="text-sm text-gray-600 mt-1">400+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-teal-50 to-teal-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-book text-3xl text-teal-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">کتاب</h3>
                    <p class="text-sm text-gray-600 mt-1">1,000+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-cyan-50 to-cyan-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-gem text-3xl text-cyan-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">تزئینی</h3>
                    <p class="text-sm text-gray-600 mt-1">600+ محصول</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-gray-50 to-gray-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-car text-3xl text-gray-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">وسایل نقلیه</h3>
                    <p class="text-sm text-gray-600 mt-1">300+ آگهی</p>
                </div>
                
                <div class="category-card bg-gradient-to-br from-rose-50 to-rose-100 p-6 rounded-xl text-center cursor-pointer transition-all duration-300">
                    <i class="fas fa-ellipsis-h text-3xl text-rose-600 mb-3"></i>
                    <h3 class="font-bold text-gray-800">سایر</h3>
                    <p class="text-sm text-gray-600 mt-1">500+ محصول</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Flash Sale Section -->
    <section class="py-16 bg-red-600">
        <div class="container mx-auto px-4">
            <div class="text-center text-white mb-8">
                <h2 class="text-3xl font-bold mb-4">🔥 فروش ویژه امروز</h2>
                <p class="text-xl opacity-90">تخفیف‌های باورنکردنی تا پایان امروز</p>
                <div class="flex justify-center items-center space-x-4 space-x-reverse mt-4">
                    <div class="bg-white/20 px-4 py-2 rounded-lg">
                        <div class="text-2xl font-bold" id="hours">12</div>
                        <div class="text-sm">ساعت</div>
                    </div>
                    <div class="text-2xl">:</div>
                    <div class="bg-white/20 px-4 py-2 rounded-lg">
                        <div class="text-2xl font-bold" id="minutes">34</div>
                        <div class="text-sm">دقیقه</div>
                    </div>
                    <div class="text-2xl">:</div>
                    <div class="bg-white/20 px-4 py-2 rounded-lg">
                        <div class="text-2xl font-bold" id="seconds">56</div>
                        <div class="text-sm">ثانیه</div>
                    </div>
                </div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="bg-white rounded-xl p-4 product-card transition-all duration-300">
                    <div class="relative">
                        <div class="bg-gray-200 h-48 rounded-lg mb-4 flex items-center justify-center">
                            <i class="fas fa-mobile-alt text-4xl text-gray-400"></i>
                        </div>
                        <div class="absolute top-2 right-2 bg-red-500 text-white px-2 py-1 rounded-full text-sm">
                            50% تخفیف
                        </div>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">گوشی هوشمند سامسونگ</h3>
                    <div class="flex items-center justify-between">
                        <div>
                            <span class="text-red-500 font-bold text-lg">15,000 ؋</span>
                            <span class="text-gray-500 line-through text-sm mr-2">30,000 ؋</span>
                        </div>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            خرید
                        </button>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl p-4 product-card transition-all duration-300">
                    <div class="relative">
                        <div class="bg-gray-200 h-48 rounded-lg mb-4 flex items-center justify-center">
                            <i class="fas fa-tshirt text-4xl text-gray-400"></i>
                        </div>
                        <div class="absolute top-2 right-2 bg-red-500 text-white px-2 py-1 rounded-full text-sm">
                            30% تخفیف
                        </div>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">پیراهن مردانه کلاسیک</h3>
                    <div class="flex items-center justify-between">
                        <div>
                            <span class="text-red-500 font-bold text-lg">700 ؋</span>
                            <span class="text-gray-500 line-through text-sm mr-2">1,000 ؋</span>
                        </div>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            خرید
                        </button>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl p-4 product-card transition-all duration-300">
                    <div class="relative">
                        <div class="bg-gray-200 h-48 rounded-lg mb-4 flex items-center justify-center">
                            <i class="fas fa-laptop text-4xl text-gray-400"></i>
                        </div>
                        <div class="absolute top-2 right-2 bg-red-500 text-white px-2 py-1 rounded-full text-sm">
                            25% تخفیف
                        </div>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">لپ تاپ ایسوس</h3>
                    <div class="flex items-center justify-between">
                        <div>
                            <span class="text-red-500 font-bold text-lg">45,000 ؋</span>
                            <span class="text-gray-500 line-through text-sm mr-2">60,000 ؋</span>
                        </div>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            خرید
                        </button>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl p-4 product-card transition-all duration-300">
                    <div class="relative">
                        <div class="bg-gray-200 h-48 rounded-lg mb-4 flex items-center justify-center">
                            <i class="fas fa-headphones text-4xl text-gray-400"></i>
                        </div>
                        <div class="absolute top-2 right-2 bg-red-500 text-white px-2 py-1 rounded-full text-sm">
                            40% تخفیف
                        </div>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">هدفون بلوتوثی</h3>
                    <div class="flex items-center justify-between">
                        <div>
                            <span class="text-red-500 font-bold text-lg">1,200 ؋</span>
                            <span class="text-gray-500 line-through text-sm mr-2">2,000 ؋</span>
                        </div>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            خرید
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Popular Products -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">محصولات پرطرفدار</h2>
                <p class="text-gray-600">پرفروش‌ترین محصولات این ماه</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="bg-white rounded-xl p-4 shadow-sm hover:shadow-lg product-card transition-all duration-300">
                    <div class="relative">
                        <div class="bg-gray-200 h-48 rounded-lg mb-4 flex items-center justify-center">
                            <i class="fas fa-watch text-4xl text-gray-400"></i>
                        </div>
                        <button class="absolute top-2 left-2 text-gray-400 hover:text-red-500">
                            <i class="fas fa-heart"></i>
                        </button>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">ساعت هوشمند</h3>
                    <div class="flex items-center mb-2">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="text-gray-500 text-sm mr-2">(124 نظر)</span>
                    </div>
                    <div class="flex items-center justify-between">
                        <span class="text-blue-600 font-bold text-lg">8,500 ؋</span>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            خرید
                        </button>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl p-4 shadow-sm hover:shadow-lg product-card transition-all duration-300">
                    <div class="relative">
                        <div class="bg-gray-200 h-48 rounded-lg mb-4 flex items-center justify-center">
                            <i class="fas fa-camera text-4xl text-gray-400"></i>
                        </div>
                        <button class="absolute top-2 left-2 text-gray-400 hover:text-red-500">
                            <i class="fas fa-heart"></i>
                        </button>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">دوربین دیجیتال</h3>
                    <div class="flex items-center mb-2">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-gray-500 text-sm mr-2">(89 نظر)</span>
                    </div>
                    <div class="flex items-center justify-between">
                        <span class="text-blue-600 font-bold text-lg">25,000 ؋</span>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            خرید
                        </button>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl p-4 shadow-sm hover:shadow-lg product-card transition-all duration-300">
                    <div class="relative">
                        <div class="bg-gray-200 h-48 rounded-lg mb-4 flex items-center justify-center">
                            <i class="fas fa-gamepad text-4xl text-gray-400"></i>
                        </div>
                        <button class="absolute top-2 left-2 text-gray-400 hover:text-red-500">
                            <i class="fas fa-heart"></i>
                        </button>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">کنسول بازی</h3>
                    <div class="flex items-center mb-2">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="text-gray-500 text-sm mr-2">(256 نظر)</span>
                    </div>
                    <div class="flex items-center justify-between">
                        <span class="text-blue-600 font-bold text-lg">35,000 ؋</span>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            خرید
                        </button>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl p-4 shadow-sm hover:shadow-lg product-card transition-all duration-300">
                    <div class="relative">
                        <div class="bg-gray-200 h-48 rounded-lg mb-4 flex items-center justify-center">
                            <i class="fas fa-book text-4xl text-gray-400"></i>
                        </div>
                        <button class="absolute top-2 left-2 text-gray-400 hover:text-red-500">
                            <i class="fas fa-heart"></i>
                        </button>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">کتاب آموزشی</h3>
                    <div class="flex items-center mb-2">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="far fa-star"></i>
                        </div>
                        <span class="text-gray-500 text-sm mr-2">(67 نظر)</span>
                    </div>
                    <div class="flex items-center justify-between">
                        <span class="text-blue-600 font-bold text-lg">450 ؋</span>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            خرید
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-shipping-fast text-2xl text-blue-600"></i>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">ارسال سریع</h3>
                    <p class="text-gray-600 text-sm">ارسال در کمتر از 24 ساعت در کابل و 48 ساعت در سایر ولایات</p>
                </div>
                
                <div class="text-center">
                    <div class="bg-green-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-shield-alt text-2xl text-green-600"></i>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">خرید امن</h3>
                    <p class="text-gray-600 text-sm">تضمین کیفیت محصولات و امکان بازگشت تا 7 روز</p>
                </div>
                
                <div class="text-center">
                    <div class="bg-purple-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-headset text-2xl text-purple-600"></i>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">پشتیبانی 24/7</h3>
                    <p class="text-gray-600 text-sm">پشتیبانی آنلاین در تمام ساعات شبانه روز</p>
                </div>
                
                <div class="text-center">
                    <div class="bg-orange-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-medal text-2xl text-orange-600"></i>
                    </div>
                    <h3 class="font-bold text-gray-800 mb-2">کیفیت تضمینی</h3>
                    <p class="text-gray-600 text-sm">تمام محصولات دارای گارانتی و کیفیت تایید شده</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter -->
    <section class="py-16 bg-blue-600">
        <div class="container mx-auto px-4 text-center">
            <div class="max-w-2xl mx-auto">
                <h2 class="text-3xl font-bold text-white mb-4">عضویت در خبرنامه</h2>
                <p class="text-blue-100 mb-8">از آخرین تخفیف‌ها و محصولات جدید با خبر شوید</p>
                <div class="flex max-w-md mx-auto">
                    <input type="email" placeholder="ایمیل خود را وارد کنید" 
                           class="flex-1 px-4 py-3 rounded-r-lg border-0 focus:outline-none">
                    <button class="bg-white text-blue-600 px-6 py-3 rounded-l-lg font-bold hover:bg-gray-100 transition-colors">
                        عضویت
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">دریچه</h3>
                    <p class="text-gray-300 mb-4">بزرگترین بازار آنلاین افغانستان با هزاران محصول با کیفیت</p>
                    <div class="flex space-x-4 space-x-reverse">
                        <a href="#" class="text-gray-300 hover:text-white">
                            <i class="fab fa-facebook text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-white">
                            <i class="fab fa-twitter text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-white">
                            <i class="fab fa-instagram text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-300 hover:text-white">
                            <i class="fab fa-telegram text-xl"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">لینک‌های مفید</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-300 hover:text-white">درباره ما</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white">تماس با ما</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white">راهنمای خرید</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white">شرایط استفاده</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">خدمات مشتریان</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-300 hover:text-white">پشتیبانی</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white">سوالات متداول</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white">رویه بازگشت</a></li>
                        <li><a href="#" class="text-gray-300 hover:text-white">ردیابی سفارش</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">اطلاعات تماس</h4>
                    <ul class="space-y-2 text-gray-300">
                        <li><i class="fas fa-map-marker-alt ml-2"></i>کابل، افغانستان</li>
                        <li><i class="fas fa-phone ml-2"></i>+93 700 123 456</li>
                        <li><i class="fas fa-envelope ml-2"></i>info@daricha.af</li>
                        <li><i class="fas fa-clock ml-2"></i>24/7 پشتیبانی</li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center">
                <p class="text-gray-300">© 2024 دریچه. تمام حقوق محفوظ است.</p>
            </div>
        </div>
    </footer>

    <!-- Chat Support -->
    <div class="fixed bottom-6 left-6 z-50">
        <button id="chatBtn" class="bg-blue-600 text-white w-14 h-14 rounded-full shadow-lg hover:bg-blue-700 transition-colors flex items-center justify-center">
            <i class="fas fa-comments text-xl"></i>
        </button>
    </div>

    <!-- Chat Window -->
    <div id="chatWindow" class="fixed bottom-24 left-6 w-80 bg-white rounded-lg shadow-xl border z-50 hidden">
        <div class="bg-blue-600 text-white p-4 rounded-t-lg">
            <div class="flex items-center justify-between">
                <h3 class="font-bold">پشتیبانی آنلاین</h3>
                <button id="closeChatBtn" class="text-white hover:text-gray-200">
                    <i class="fas fa-times"></i>
                </button>
            </div>
        </div>
        <div class="p-4 h-64 overflow-y-auto">
            <div class="mb-4">
                <div class="bg-gray-100 p-3 rounded-lg">
                    <p class="text-sm">سلام! چطور می‌تونم کمکتون کنم؟</p>
                </div>
            </div>
        </div>
        <div class="p-4 border-t">
            <div class="flex">
                <input type="text" placeholder="پیام خود را بنویسید..." 
                       class="flex-1 border border-gray-300 rounded-r-lg px-3 py-2 focus:outline-none focus:border-blue-500">
                <button class="bg-blue-600 text-white px-4 py-2 rounded-l-lg hover:bg-blue-700">
                    <i class="fas fa-paper-plane"></i>
                </button>
            </div>
        </div>
    </div>

    <script>
        // Advanced Search Toggle
        document.getElementById('advancedSearchBtn').addEventListener('click', function() {
            const advancedSearch = document.getElementById('advancedSearch');
            advancedSearch.classList.toggle('active');
        });

        // Mobile Menu
        document.getElementById('mobileMenuBtn').addEventListener('click', function() {
            document.getElementById('mobileMenu').classList.add('active');
        });

        document.getElementById('closeMobileMenu').addEventListener('click', function() {
            document.getElementById('mobileMenu').classList.remove('active');
        });

        // Chat Support
        document.getElementById('chatBtn').addEventListener('click', function() {
            document.getElementById('chatWindow').classList.toggle('hidden');
        });

        document.getElementById('closeChatBtn').addEventListener('click', function() {
            document.getElementById('chatWindow').classList.add('hidden');
        });

        // Flash Sale Countdown
        function updateCountdown() {
            const now = new Date().getTime();
            const endTime = now + (12 * 60 * 60 * 1000) + (34 * 60 * 1000) + (56 * 1000); // 12:34:56
            
            setInterval(function() {
                const currentTime = new Date().getTime();
                const timeLeft = endTime - currentTime;
                
                const hours = Math.floor((timeLeft % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((timeLeft % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((timeLeft % (1000 * 60)) / 1000);
                
                document.getElementById('hours').textContent = hours.toString().padStart(2, '0');
                document.getElementById('minutes').textContent = minutes.toString().padStart(2, '0');
                document.getElementById('seconds').textContent = seconds.toString().padStart(2, '0');
            }, 1000);
        }
        
        updateCountdown();

        // Search functionality
        document.getElementById('searchInput').addEventListener('input', function(e) {
            const searchTerm = e.target.value.toLowerCase();
            // Here you would implement actual search functionality
            console.log('Searching for:', searchTerm);
        });

        // Add to cart functionality
        document.querySelectorAll('.product-card button').forEach(button => {
            if (button.textContent.trim() === 'خرید') {
                button.addEventListener('click', function() {
                    // Add to cart logic
                    this.textContent = 'اضافه شد';
                    this.classList.remove('bg-blue-600', 'hover:bg-blue-700');
                    this.classList.add('bg-green-600');
                    
                    setTimeout(() => {
                        this.textContent = 'خرید';
                        this.classList.remove('bg-green-600');
                        this.classList.add('bg-blue-600', 'hover:bg-blue-700');
                    }, 2000);
                });
            }
        });

        // Heart/Wishlist functionality
        document.querySelectorAll('.fa-heart').forEach(heart => {
            heart.addEventListener('click', function() {
                this.classList.toggle('fas');
                this.classList.toggle('far');
                this.classList.toggle('text-red-500');
                this.classList.toggle('text-gray-400');
            });
        });

        // Newsletter subscription
        document.querySelector('section:nth-last-child(2) button').addEventListener('click', function() {
            const email = this.previousElementSibling.value;
            if (email) {
                alert('با موفقیت در خبرنامه عضو شدید!');
                this.previousElementSibling.value = '';
            }
        });

        // Category cards click
        document.querySelectorAll('.category-card').forEach(card => {
            card.addEventListener('click', function() {
                const categoryName = this.querySelector('h3').textContent;
                console.log('Category selected:', categoryName);
                // Here you would navigate to category page
            });
        });

        // Close mobile menu when clicking outside
        document.addEventListener('click', function(e) {
            const mobileMenu = document.getElementById('mobileMenu');
            const mobileMenuBtn = document.getElementById('mobileMenuBtn');
            
            if (!mobileMenu.contains(e.target) && !mobileMenuBtn.contains(e.target)) {
                mobileMenu.classList.remove('active');
            }
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9630403c873737b1',t:'MTc1MzE1OTEzMi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>


<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>پنل فروشنده - دریچه</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800;900&display=swap');
        
        * {
            font-family: 'Vazirmatn', sans-serif;
        }
        
        .sidebar {
            transition: transform 0.3s ease;
        }
        
        .sidebar.collapsed {
            transform: translateX(100%);
        }
        
        .main-content {
            transition: margin-right 0.3s ease;
        }
        
        .main-content.expanded {
            margin-right: 0;
        }
        
        .stat-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .stat-card.green {
            background: linear-gradient(135deg, #4ade80 0%, #22c55e 100%);
        }
        
        .stat-card.orange {
            background: linear-gradient(135deg, #fb923c 0%, #f97316 100%);
        }
        
        .stat-card.red {
            background: linear-gradient(135deg, #f87171 0%, #ef4444 100%);
        }
        
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
            z-index: 1000;
        }
        
        .modal.active {
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
        }
        
        .notification {
            position: fixed;
            top: 20px;
            right: 20px;
            background: #10b981;
            color: white;
            padding: 12px 24px;
            border-radius: 8px;
            transform: translateX(400px);
            transition: transform 0.3s ease;
            z-index: 1001;
        }
        
        .notification.show {
            transform: translateX(0);
        }
        
        .product-image-preview {
            width: 100px;
            height: 100px;
            object-fit: cover;
            border-radius: 8px;
        }
        
        .drag-drop-area {
            border: 2px dashed #d1d5db;
            border-radius: 8px;
            padding: 40px;
            text-align: center;
            transition: all 0.3s ease;
        }
        
        .drag-drop-area.dragover {
            border-color: #3b82f6;
            background-color: #eff6ff;
        }
        
        @media (max-width: 768px) {
            .sidebar {
                position: fixed;
                top: 0;
                right: 0;
                height: 100vh;
                z-index: 50;
                transform: translateX(100%);
            }
            
            .sidebar.active {
                transform: translateX(0);
            }
            
            .main-content {
                margin-right: 0;
            }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Top Header -->
    <header class="bg-white shadow-sm border-b sticky top-0 z-40">
        <div class="flex items-center justify-between px-6 py-4">
            <div class="flex items-center space-x-4 space-x-reverse">
                <button id="sidebarToggle" class="text-gray-600 hover:text-gray-800 md:hidden">
                    <i class="fas fa-bars text-xl"></i>
                </button>
                <h1 class="text-2xl font-bold text-blue-600">دریچه</h1>
                <span class="text-gray-500">پنل فروشنده</span>
            </div>
            
            <div class="flex items-center space-x-4 space-x-reverse">
                <button class="relative text-gray-600 hover:text-gray-800">
                    <i class="fas fa-bell text-xl"></i>
                    <span class="absolute -top-1 -right-1 bg-red-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center">3</span>
                </button>
                
                <div class="flex items-center space-x-3 space-x-reverse">
                    <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHZpZXdCb3g9IjAgMCA0MCA0MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGNpcmNsZSBjeD0iMjAiIGN5PSIyMCIgcj0iMjAiIGZpbGw9IiMzYjgyZjYiLz4KPHN2ZyB4PSI4IiB5PSI4IiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSI+CjxwYXRoIGQ9Ik0yMCAyMXYtMmE0IDQgMCAwIDAtNC00SDhhNCA0IDAgMCAwLTQgNHYyIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIvPgo8Y2lyY2xlIGN4PSIxMiIgY3k9IjciIHI9IjQiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+Cjwvc3ZnPgo8L3N2Zz4K" 
                         alt="Profile" class="w-10 h-10 rounded-full">
                    <div>
                        <div class="font-medium text-gray-800">احمد محمدی</div>
                        <div class="text-sm text-gray-500">فروشنده طلایی</div>
                    </div>
                    <i class="fas fa-chevron-down text-gray-400"></i>
                </div>
            </div>
        </div>
    </header>

    <div class="flex">
        <!-- Sidebar -->
        <aside id="sidebar" class="sidebar w-64 bg-white shadow-lg h-screen sticky top-16">
            <nav class="p-4">
                <ul class="space-y-2">
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg bg-blue-50 text-blue-600" data-tab="dashboard">
                            <i class="fas fa-tachometer-alt"></i>
                            <span>داشبورد</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="products">
                            <i class="fas fa-box"></i>
                            <span>محصولات</span>
                            <span class="bg-blue-100 text-blue-600 px-2 py-1 rounded-full text-xs mr-auto">24</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="orders">
                            <i class="fas fa-shopping-cart"></i>
                            <span>سفارشات</span>
                            <span class="bg-red-100 text-red-600 px-2 py-1 rounded-full text-xs mr-auto">5</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="inventory">
                            <i class="fas fa-warehouse"></i>
                            <span>موجودی انبار</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="analytics">
                            <i class="fas fa-chart-line"></i>
                            <span>آمار و گزارشات</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="customers">
                            <i class="fas fa-users"></i>
                            <span>مشتریان</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="reviews">
                            <i class="fas fa-star"></i>
                            <span>نظرات و امتیازات</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="finance">
                            <i class="fas fa-dollar-sign"></i>
                            <span>مالی</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="settings">
                            <i class="fas fa-cog"></i>
                            <span>تنظیمات</span>
                        </a>
                    </li>
                </ul>
                
                <div class="mt-8 pt-4 border-t">
                    <a href="#" class="flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-red-600 hover:bg-red-50">
                        <i class="fas fa-sign-out-alt"></i>
                        <span>خروج</span>
                    </a>
                </div>
            </nav>
        </aside>

        <!-- Main Content -->
        <main id="mainContent" class="main-content flex-1 p-6 mr-64">
            <!-- Dashboard Tab -->
            <div id="dashboard" class="tab-content active">
                <div class="mb-6">
                    <h2 class="text-2xl font-bold text-gray-800 mb-2">داشبورد فروشنده</h2>
                    <p class="text-gray-600">خلاصه‌ای از عملکرد فروشگاه شما</p>
                </div>

                <!-- Stats Cards -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-8">
                    <div class="stat-card text-white p-6 rounded-xl">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-white/80 text-sm">فروش امروز</p>
                                <p class="text-2xl font-bold">12,500 ؋</p>
                                <p class="text-white/80 text-sm">+15% از دیروز</p>
                            </div>
                            <i class="fas fa-chart-line text-3xl text-white/60"></i>
                        </div>
                    </div>
                    
                    <div class="stat-card green text-white p-6 rounded-xl">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-white/80 text-sm">سفارشات جدید</p>
                                <p class="text-2xl font-bold">8</p>
                                <p class="text-white/80 text-sm">در انتظار تایید</p>
                            </div>
                            <i class="fas fa-shopping-cart text-3xl text-white/60"></i>
                        </div>
                    </div>
                    
                    <div class="stat-card orange text-white p-6 rounded-xl">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-white/80 text-sm">محصولات</p>
                                <p class="text-2xl font-bold">24</p>
                                <p class="text-white/80 text-sm">3 ناموجود</p>
                            </div>
                            <i class="fas fa-box text-3xl text-white/60"></i>
                        </div>
                    </div>
                    
                    <div class="stat-card red text-white p-6 rounded-xl">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-white/80 text-sm">امتیاز فروشگاه</p>
                                <p class="text-2xl font-bold">4.8</p>
                                <p class="text-white/80 text-sm">از 156 نظر</p>
                            </div>
                            <i class="fas fa-star text-3xl text-white/60"></i>
                        </div>
                    </div>
                </div>

                <!-- Charts and Recent Activity -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">فروش هفتگی</h3>
                        <canvas id="salesChart" width="400" height="200"></canvas>
                    </div>
                    
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">فعالیت‌های اخیر</h3>
                        <div class="space-y-4">
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="w-2 h-2 bg-green-500 rounded-full"></div>
                                <div class="flex-1">
                                    <p class="text-sm text-gray-800">سفارش جدید از علی احمدی</p>
                                    <p class="text-xs text-gray-500">5 دقیقه پیش</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="w-2 h-2 bg-blue-500 rounded-full"></div>
                                <div class="flex-1">
                                    <p class="text-sm text-gray-800">محصول "گوشی سامسونگ" به‌روزرسانی شد</p>
                                    <p class="text-xs text-gray-500">15 دقیقه پیش</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="w-2 h-2 bg-yellow-500 rounded-full"></div>
                                <div class="flex-1">
                                    <p class="text-sm text-gray-800">نظر جدید برای "لپ تاپ ایسوس"</p>
                                    <p class="text-xs text-gray-500">30 دقیقه پیش</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="w-2 h-2 bg-red-500 rounded-full"></div>
                                <div class="flex-1">
                                    <p class="text-sm text-gray-800">موجودی "هدفون بلوتوثی" کم شده</p>
                                    <p class="text-xs text-gray-500">1 ساعت پیش</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Quick Actions -->
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-lg font-bold text-gray-800 mb-4">عملیات سریع</h3>
                    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                        <button class="flex flex-col items-center p-4 border-2 border-dashed border-gray-300 rounded-lg hover:border-blue-500 hover:bg-blue-50 transition-colors" onclick="openModal('addProductModal')">
                            <i class="fas fa-plus text-2xl text-gray-400 mb-2"></i>
                            <span class="text-sm text-gray-600">افزودن محصول</span>
                        </button>
                        <button class="flex flex-col items-center p-4 border-2 border-dashed border-gray-300 rounded-lg hover:border-green-500 hover:bg-green-50 transition-colors">
                            <i class="fas fa-eye text-2xl text-gray-400 mb-2"></i>
                            <span class="text-sm text-gray-600">مشاهده سفارشات</span>
                        </button>
                        <button class="flex flex-col items-center p-4 border-2 border-dashed border-gray-300 rounded-lg hover:border-purple-500 hover:bg-purple-50 transition-colors">
                            <i class="fas fa-chart-bar text-2xl text-gray-400 mb-2"></i>
                            <span class="text-sm text-gray-600">گزارش فروش</span>
                        </button>
                        <button class="flex flex-col items-center p-4 border-2 border-dashed border-gray-300 rounded-lg hover:border-orange-500 hover:bg-orange-50 transition-colors">
                            <i class="fas fa-cog text-2xl text-gray-400 mb-2"></i>
                            <span class="text-sm text-gray-600">تنظیمات</span>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Products Tab -->
            <div id="products" class="tab-content">
                <div class="flex items-center justify-between mb-6">
                    <div>
                        <h2 class="text-2xl font-bold text-gray-800 mb-2">مدیریت محصولات</h2>
                        <p class="text-gray-600">مدیریت و ویرایش محصولات فروشگاه</p>
                    </div>
                    <button class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition-colors" onclick="openModal('addProductModal')">
                        <i class="fas fa-plus ml-2"></i>
                        افزودن محصول جدید
                    </button>
                </div>

                <!-- Filters -->
                <div class="bg-white p-4 rounded-lg shadow-sm mb-6">
                    <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
                        <input type="text" placeholder="جستجو محصول..." class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                        <select class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                            <option>همه دسته‌ها</option>
                            <option>الکترونیک</option>
                            <option>لباس</option>
                            <option>کتاب</option>
                        </select>
                        <select class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                            <option>همه وضعیت‌ها</option>
                            <option>فعال</option>
                            <option>غیرفعال</option>
                            <option>ناموجود</option>
                        </select>
                        <button class="bg-gray-100 text-gray-700 px-4 py-2 rounded-lg hover:bg-gray-200 transition-colors">
                            <i class="fas fa-filter ml-2"></i>
                            فیلتر
                        </button>
                    </div>
                </div>

                <!-- Products Table -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full">
                            <thead class="bg-gray-50">
                                <tr>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">محصول</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">دسته‌بندی</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">قیمت</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">موجودی</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">وضعیت</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">عملیات</th>
                                </tr>
                            </thead>
                            <tbody class="bg-white divide-y divide-gray-200">
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="flex items-center">
                                            <div class="w-12 h-12 bg-gray-200 rounded-lg flex items-center justify-center ml-4">
                                                <i class="fas fa-mobile-alt text-gray-400"></i>
                                            </div>
                                            <div>
                                                <div class="text-sm font-medium text-gray-900">گوشی سامسونگ A54</div>
                                                <div class="text-sm text-gray-500">کد: PRD001</div>
                                            </div>
                                        </div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">الکترونیک</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">15,000 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">12</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-green-100 text-green-800">فعال</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-blue-600 hover:text-blue-900 ml-3">ویرایش</button>
                                        <button class="text-red-600 hover:text-red-900">حذف</button>
                                    </td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="flex items-center">
                                            <div class="w-12 h-12 bg-gray-200 rounded-lg flex items-center justify-center ml-4">
                                                <i class="fas fa-laptop text-gray-400"></i>
                                            </div>
                                            <div>
                                                <div class="text-sm font-medium text-gray-900">لپ تاپ ایسوس</div>
                                                <div class="text-sm text-gray-500">کد: PRD002</div>
                                            </div>
                                        </div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">الکترونیک</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">45,000 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">5</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-green-100 text-green-800">فعال</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-blue-600 hover:text-blue-900 ml-3">ویرایش</button>
                                        <button class="text-red-600 hover:text-red-900">حذف</button>
                                    </td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="flex items-center">
                                            <div class="w-12 h-12 bg-gray-200 rounded-lg flex items-center justify-center ml-4">
                                                <i class="fas fa-headphones text-gray-400"></i>
                                            </div>
                                            <div>
                                                <div class="text-sm font-medium text-gray-900">هدفون بلوتوثی</div>
                                                <div class="text-sm text-gray-500">کد: PRD003</div>
                                            </div>
                                        </div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">الکترونیک</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">1,200 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">0</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-red-100 text-red-800">ناموجود</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-blue-600 hover:text-blue-900 ml-3">ویرایش</button>
                                        <button class="text-red-600 hover:text-red-900">حذف</button>
                                    </td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    
                    <!-- Pagination -->
                    <div class="bg-white px-4 py-3 flex items-center justify-between border-t border-gray-200">
                        <div class="flex-1 flex justify-between sm:hidden">
                            <button class="relative inline-flex items-center px-4 py-2 border border-gray-300 text-sm font-medium rounded-md text-gray-700 bg-white hover:bg-gray-50">قبلی</button>
                            <button class="ml-3 relative inline-flex items-center px-4 py-2 border border-gray-300 text-sm font-medium rounded-md text-gray-700 bg-white hover:bg-gray-50">بعدی</button>
                        </div>
                        <div class="hidden sm:flex-1 sm:flex sm:items-center sm:justify-between">
                            <div>
                                <p class="text-sm text-gray-700">نمایش <span class="font-medium">1</span> تا <span class="font-medium">10</span> از <span class="font-medium">24</span> نتیجه</p>
                            </div>
                            <div>
                                <nav class="relative z-0 inline-flex rounded-md shadow-sm -space-x-px" aria-label="Pagination">
                                    <button class="relative inline-flex items-center px-2 py-2 rounded-r-md border border-gray-300 bg-white text-sm font-medium text-gray-500 hover:bg-gray-50">قبلی</button>
                                    <button class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">1</button>
                                    <button class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-blue-50 text-sm font-medium text-blue-600">2</button>
                                    <button class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">3</button>
                                    <button class="relative inline-flex items-center px-2 py-2 rounded-l-md border border-gray-300 bg-white text-sm font-medium text-gray-500 hover:bg-gray-50">بعدی</button>
                                </nav>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Orders Tab -->
            <div id="orders" class="tab-content">
                <div class="mb-6">
                    <h2 class="text-2xl font-bold text-gray-800 mb-2">مدیریت سفارشات</h2>
                    <p class="text-gray-600">پیگیری و مدیریت سفارشات مشتریان</p>
                </div>

                <!-- Order Stats -->
                <div class="grid grid-cols-1 md:grid-cols-4 gap-4 mb-6">
                    <div class="bg-white p-4 rounded-lg shadow-sm">
                        <div class="flex items-center">
                            <div class="p-2 bg-yellow-100 rounded-lg">
                                <i class="fas fa-clock text-yellow-600"></i>
                            </div>
                            <div class="mr-3">
                                <p class="text-sm text-gray-600">در انتظار تایید</p>
                                <p class="text-xl font-bold text-gray-800">5</p>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white p-4 rounded-lg shadow-sm">
                        <div class="flex items-center">
                            <div class="p-2 bg-blue-100 rounded-lg">
                                <i class="fas fa-truck text-blue-600"></i>
                            </div>
                            <div class="mr-3">
                                <p class="text-sm text-gray-600">در حال ارسال</p>
                                <p class="text-xl font-bold text-gray-800">8</p>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white p-4 rounded-lg shadow-sm">
                        <div class="flex items-center">
                            <div class="p-2 bg-green-100 rounded-lg">
                                <i class="fas fa-check text-green-600"></i>
                            </div>
                            <div class="mr-3">
                                <p class="text-sm text-gray-600">تحویل شده</p>
                                <p class="text-xl font-bold text-gray-800">156</p>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white p-4 rounded-lg shadow-sm">
                        <div class="flex items-center">
                            <div class="p-2 bg-red-100 rounded-lg">
                                <i class="fas fa-times text-red-600"></i>
                            </div>
                            <div class="mr-3">
                                <p class="text-sm text-gray-600">لغو شده</p>
                                <p class="text-xl font-bold text-gray-800">12</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Orders Table -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full">
                            <thead class="bg-gray-50">
                                <tr>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">شماره سفارش</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">مشتری</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">محصولات</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">مبلغ</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">وضعیت</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">تاریخ</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">عملیات</th>
                                </tr>
                            </thead>
                            <tbody class="bg-white divide-y divide-gray-200">
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">#ORD001</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="text-sm text-gray-900">علی احمدی</div>
                                        <div class="text-sm text-gray-500">ali@example.com</div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">گوشی سامسونگ (×1)</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">15,000 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-yellow-100 text-yellow-800">در انتظار تایید</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">1403/08/15</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-green-600 hover:text-green-900 ml-3">تایید</button>
                                        <button class="text-red-600 hover:text-red-900">رد</button>
                                    </td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">#ORD002</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="text-sm text-gray-900">فاطمه کریمی</div>
                                        <div class="text-sm text-gray-500">fateme@example.com</div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">لپ تاپ ایسوس (×1)</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">45,000 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-blue-100 text-blue-800">در حال ارسال</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">1403/08/14</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-blue-600 hover:text-blue-900">جزئیات</button>
                                    </td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>

            <!-- Other tabs content would go here... -->
            <div id="inventory" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">مدیریت موجودی انبار</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>

            <div id="analytics" class="tab-content">
                <div class="mb-6">
                    <h2 class="text-2xl font-bold text-gray-800 mb-2">آمار و گزارشات</h2>
                    <p class="text-gray-600">تحلیل جامع عملکرد فروشگاه و روند فروش</p>
                </div>

                <!-- Time Period Selector -->
                <div class="bg-white p-4 rounded-lg shadow-sm mb-6">
                    <div class="flex flex-wrap items-center justify-between gap-4">
                        <div class="flex items-center space-x-4 space-x-reverse">
                            <label class="text-sm font-medium text-gray-700">بازه زمانی:</label>
                            <select id="timePeriod" class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                                <option value="7">7 روز گذشته</option>
                                <option value="30" selected>30 روز گذشته</option>
                                <option value="90">3 ماه گذشته</option>
                                <option value="365">سال گذشته</option>
                            </select>
                        </div>
                        <div class="flex items-center space-x-2 space-x-reverse">
                            <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                                <i class="fas fa-download ml-2"></i>
                                دانلود گزارش
                            </button>
                            <button class="bg-green-600 text-white px-4 py-2 rounded-lg hover:bg-green-700 transition-colors">
                                <i class="fas fa-file-excel ml-2"></i>
                                خروجی Excel
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Key Metrics -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-8">
                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-blue-500">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-600 text-sm">کل فروش</p>
                                <p class="text-2xl font-bold text-gray-800">485,000 ؋</p>
                                <div class="flex items-center mt-2">
                                    <i class="fas fa-arrow-up text-green-500 text-xs"></i>
                                    <span class="text-green-500 text-sm mr-1">+12.5%</span>
                                    <span class="text-gray-500 text-sm">نسبت به ماه قبل</span>
                                </div>
                            </div>
                            <div class="p-3 bg-blue-100 rounded-full">
                                <i class="fas fa-dollar-sign text-blue-600 text-xl"></i>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-green-500">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-600 text-sm">تعداد سفارشات</p>
                                <p class="text-2xl font-bold text-gray-800">156</p>
                                <div class="flex items-center mt-2">
                                    <i class="fas fa-arrow-up text-green-500 text-xs"></i>
                                    <span class="text-green-500 text-sm mr-1">+8.3%</span>
                                    <span class="text-gray-500 text-sm">نسبت به ماه قبل</span>
                                </div>
                            </div>
                            <div class="p-3 bg-green-100 rounded-full">
                                <i class="fas fa-shopping-cart text-green-600 text-xl"></i>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-orange-500">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-600 text-sm">میانگین سفارش</p>
                                <p class="text-2xl font-bold text-gray-800">3,109 ؋</p>
                                <div class="flex items-center mt-2">
                                    <i class="fas fa-arrow-up text-green-500 text-xs"></i>
                                    <span class="text-green-500 text-sm mr-1">+4.1%</span>
                                    <span class="text-gray-500 text-sm">نسبت به ماه قبل</span>
                                </div>
                            </div>
                            <div class="p-3 bg-orange-100 rounded-full">
                                <i class="fas fa-chart-bar text-orange-600 text-xl"></i>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-purple-500">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-600 text-sm">نرخ تبدیل</p>
                                <p class="text-2xl font-bold text-gray-800">3.2%</p>
                                <div class="flex items-center mt-2">
                                    <i class="fas fa-arrow-down text-red-500 text-xs"></i>
                                    <span class="text-red-500 text-sm mr-1">-0.5%</span>
                                    <span class="text-gray-500 text-sm">نسبت به ماه قبل</span>
                                </div>
                            </div>
                            <div class="p-3 bg-purple-100 rounded-full">
                                <i class="fas fa-percentage text-purple-600 text-xl"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Charts Row -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                    <!-- Sales Trend Chart -->
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <div class="flex items-center justify-between mb-4">
                            <h3 class="text-lg font-bold text-gray-800">روند فروش</h3>
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <button class="text-sm text-blue-600 hover:text-blue-800" onclick="toggleChartType('salesTrendChart')">تغییر نمودار</button>
                            </div>
                        </div>
                        <canvas id="salesTrendChart" height="300"></canvas>
                    </div>

                    <!-- Category Performance -->
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">عملکرد دسته‌بندی‌ها</h3>
                        <canvas id="categoryChart" height="300"></canvas>
                    </div>
                </div>

                <!-- Revenue and Orders Chart -->
                <div class="bg-white p-6 rounded-xl shadow-sm mb-8">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-lg font-bold text-gray-800">درآمد و تعداد سفارشات</h3>
                        <div class="flex items-center space-x-4 space-x-reverse">
                            <label class="flex items-center">
                                <input type="checkbox" id="showRevenue" checked class="rounded border-gray-300 text-blue-600 focus:ring-blue-500">
                                <span class="mr-2 text-sm text-gray-700">درآمد</span>
                            </label>
                            <label class="flex items-center">
                                <input type="checkbox" id="showOrders" checked class="rounded border-gray-300 text-green-600 focus:ring-green-500">
                                <span class="mr-2 text-sm text-gray-700">سفارشات</span>
                            </label>
                        </div>
                    </div>
                    <canvas id="revenueOrdersChart" height="400"></canvas>
                </div>

                <!-- Detailed Analytics Tables -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                    <!-- Top Products -->
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">محصولات پرفروش</h3>
                        <div class="space-y-4">
                            <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 bg-blue-100 rounded-lg flex items-center justify-center ml-3">
                                        <i class="fas fa-mobile-alt text-blue-600"></i>
                                    </div>
                                    <div>
                                        <p class="font-medium text-gray-800">گوشی سامسونگ A54</p>
                                        <p class="text-sm text-gray-500">45 فروش</p>
                                    </div>
                                </div>
                                <div class="text-left">
                                    <p class="font-bold text-gray-800">675,000 ؋</p>
                                    <p class="text-sm text-green-600">+15%</p>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 bg-green-100 rounded-lg flex items-center justify-center ml-3">
                                        <i class="fas fa-laptop text-green-600"></i>
                                    </div>
                                    <div>
                                        <p class="font-medium text-gray-800">لپ تاپ ایسوس</p>
                                        <p class="text-sm text-gray-500">23 فروش</p>
                                    </div>
                                </div>
                                <div class="text-left">
                                    <p class="font-bold text-gray-800">1,035,000 ؋</p>
                                    <p class="text-sm text-green-600">+8%</p>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 bg-purple-100 rounded-lg flex items-center justify-center ml-3">
                                        <i class="fas fa-headphones text-purple-600"></i>
                                    </div>
                                    <div>
                                        <p class="font-medium text-gray-800">هدفون بلوتوثی</p>
                                        <p class="text-sm text-gray-500">67 فروش</p>
                                    </div>
                                </div>
                                <div class="text-left">
                                    <p class="font-bold text-gray-800">80,400 ؋</p>
                                    <p class="text-sm text-red-600">-3%</p>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 bg-orange-100 rounded-lg flex items-center justify-center ml-3">
                                        <i class="fas fa-tablet-alt text-orange-600"></i>
                                    </div>
                                    <div>
                                        <p class="font-medium text-gray-800">تبلت سامسونگ</p>
                                        <p class="text-sm text-gray-500">18 فروش</p>
                                    </div>
                                </div>
                                <div class="text-left">
                                    <p class="font-bold text-gray-800">270,000 ؋</p>
                                    <p class="text-sm text-green-600">+22%</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Customer Insights -->
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">تحلیل مشتریان</h3>
                        <div class="space-y-6">
                            <div>
                                <div class="flex items-center justify-between mb-2">
                                    <span class="text-sm text-gray-600">مشتریان جدید</span>
                                    <span class="text-sm font-medium text-gray-800">34</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-blue-600 h-2 rounded-full" style="width: 68%"></div>
                                </div>
                            </div>

                            <div>
                                <div class="flex items-center justify-between mb-2">
                                    <span class="text-sm text-gray-600">مشتریان بازگشتی</span>
                                    <span class="text-sm font-medium text-gray-800">89</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-green-600 h-2 rounded-full" style="width: 89%"></div>
                                </div>
                            </div>

                            <div>
                                <div class="flex items-center justify-between mb-2">
                                    <span class="text-sm text-gray-600">مشتریان VIP</span>
                                    <span class="text-sm font-medium text-gray-800">12</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-purple-600 h-2 rounded-full" style="width: 24%"></div>
                                </div>
                            </div>

                            <div class="pt-4 border-t">
                                <h4 class="font-medium text-gray-800 mb-3">آمار رضایت مشتریان</h4>
                                <div class="flex items-center justify-between">
                                    <div class="text-center">
                                        <div class="text-2xl font-bold text-green-600">4.8</div>
                                        <div class="text-xs text-gray-500">میانگین امتیاز</div>
                                    </div>
                                    <div class="text-center">
                                        <div class="text-2xl font-bold text-blue-600">94%</div>
                                        <div class="text-xs text-gray-500">رضایت کلی</div>
                                    </div>
                                    <div class="text-center">
                                        <div class="text-2xl font-bold text-orange-600">156</div>
                                        <div class="text-xs text-gray-500">نظرات</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Geographic Sales -->
                <div class="bg-white p-6 rounded-xl shadow-sm mb-8">
                    <h3 class="text-lg font-bold text-gray-800 mb-4">فروش بر اساس منطقه</h3>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                        <div class="space-y-4">
                            <div class="flex items-center justify-between p-3 border rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-3 h-3 bg-blue-500 rounded-full ml-3"></div>
                                    <span class="text-gray-700">کابل</span>
                                </div>
                                <div class="text-left">
                                    <div class="font-bold text-gray-800">185,000 ؋</div>
                                    <div class="text-sm text-gray-500">38% از کل فروش</div>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 border rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-3 h-3 bg-green-500 rounded-full ml-3"></div>
                                    <span class="text-gray-700">هرات</span>
                                </div>
                                <div class="text-left">
                                    <div class="font-bold text-gray-800">125,000 ؋</div>
                                    <div class="text-sm text-gray-500">26% از کل فروش</div>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 border rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-3 h-3 bg-orange-500 rounded-full ml-3"></div>
                                    <span class="text-gray-700">مزار شریف</span>
                                </div>
                                <div class="text-left">
                                    <div class="font-bold text-gray-800">95,000 ؋</div>
                                    <div class="text-sm text-gray-500">20% از کل فروش</div>
                                </div>
                            </div>
                        </div>

                        <div class="md:col-span-2">
                            <canvas id="geoChart" height="200"></canvas>
                        </div>
                    </div>
                </div>

                <!-- Performance Indicators -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">شاخص‌های عملکرد</h3>
                        <div class="space-y-4">
                            <div class="flex items-center justify-between">
                                <span class="text-gray-600">نرخ بازگشت</span>
                                <span class="font-bold text-red-600">2.3%</span>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="text-gray-600">زمان پردازش</span>
                                <span class="font-bold text-green-600">1.2 روز</span>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="text-gray-600">رضایت مشتری</span>
                                <span class="font-bold text-blue-600">94%</span>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="text-gray-600">نرخ تکمیل سفارش</span>
                                <span class="font-bold text-green-600">97.8%</span>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">مقایسه با رقبا</h3>
                        <div class="space-y-4">
                            <div>
                                <div class="flex items-center justify-between mb-1">
                                    <span class="text-sm text-gray-600">قیمت‌گذاری</span>
                                    <span class="text-sm font-medium text-green-600">بهتر از 78%</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-green-600 h-2 rounded-full" style="width: 78%"></div>
                                </div>
                            </div>

                            <div>
                                <div class="flex items-center justify-between mb-1">
                                    <span class="text-sm text-gray-600">کیفیت خدمات</span>
                                    <span class="text-sm font-medium text-blue-600">بهتر از 85%</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-blue-600 h-2 rounded-full" style="width: 85%"></div>
                                </div>
                            </div>

                            <div>
                                <div class="flex items-center justify-between mb-1">
                                    <span class="text-sm text-gray-600">سرعت ارسال</span>
                                    <span class="text-sm font-medium text-orange-600">بهتر از 65%</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-orange-600 h-2 rounded-full" style="width: 65%"></div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">پیش‌بینی فروش</h3>
                        <div class="space-y-4">
                            <div class="text-center p-4 bg-blue-50 rounded-lg">
                                <div class="text-2xl font-bold text-blue-600">520,000 ؋</div>
                                <div class="text-sm text-gray-600">پیش‌بینی ماه آینده</div>
                                <div class="text-xs text-green-600 mt-1">+7.2% رشد</div>
                            </div>

                            <div class="space-y-2">
                                <div class="flex items-center justify-between text-sm">
                                    <span class="text-gray-600">احتمال دستیابی</span>
                                    <span class="font-medium text-green-600">87%</span>
                                </div>
                                <div class="flex items-center justify-between text-sm">
                                    <span class="text-gray-600">بهترین حالت</span>
                                    <span class="font-medium text-gray-800">580,000 ؋</span>
                                </div>
                                <div class="flex items-center justify-between text-sm">
                                    <span class="text-gray-600">بدترین حالت</span>
                                    <span class="font-medium text-gray-800">460,000 ؋</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div id="customers" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">مدیریت مشتریان</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>

            <div id="reviews" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">نظرات و امتیازات</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>

            <div id="finance" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">مدیریت مالی</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>

            <div id="settings" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">تنظیمات فروشگاه</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>
        </main>
    </div>

    <!-- Add Product Modal -->
    <div id="addProductModal" class="modal">
        <div class="bg-white rounded-lg shadow-xl max-w-2xl w-full mx-4 max-h-screen overflow-y-auto">
            <div class="flex items-center justify-between p-6 border-b">
                <h3 class="text-lg font-bold text-gray-800">افزودن محصول جدید</h3>
                <button onclick="closeModal('addProductModal')" class="text-gray-400 hover:text-gray-600">
                    <i class="fas fa-times text-xl"></i>
                </button>
            </div>
            
            <form class="p-6 space-y-6">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">نام محصول</label>
                        <input type="text" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="نام محصول را وارد کنید">
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">دسته‌بندی</label>
                        <select class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                            <option>انتخاب دسته‌بندی</option>
                            <option>الکترونیک</option>
                            <option>لباس و پوشاک</option>
                            <option>لوازم خانه</option>
                            <option>کتاب</option>
                        </select>
                    </div>
                </div>
                
                <div>
                    <label class="block text-sm font-medium text-gray-700 mb-2">توضیحات محصول</label>
                    <textarea rows="4" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="توضیحات کامل محصول را وارد کنید"></textarea>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">قیمت (افغانی)</label>
                        <input type="number" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="0">
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">موجودی</label>
                        <input type="number" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="0">
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">وزن (گرم)</label>
                        <input type="number" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="0">
                    </div>
                </div>
                
                <div>
                    <label class="block text-sm font-medium text-gray-700 mb-2">تصاویر محصول</label>
                    <div class="drag-drop-area" id="imageDropArea">
                        <i class="fas fa-cloud-upload-alt text-4xl text-gray-400 mb-4"></i>
                        <p class="text-gray-600 mb-2">تصاویر را اینجا بکشید یا کلیک کنید</p>
                        <input type="file" id="imageInput" multiple accept="image/*" class="hidden">
                        <button type="button" onclick="document.getElementById('imageInput').click()" class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            انتخاب فایل
                        </button>
                    </div>
                    <div id="imagePreview" class="mt-4 grid grid-cols-4 gap-4"></div>
                </div>
                
                <div class="flex items-center space-x-4 space-x-reverse">
                    <label class="flex items-center">
                        <input type="checkbox" class="rounded border-gray-300 text-blue-600 focus:ring-blue-500">
                        <span class="mr-2 text-sm text-gray-700">محصول فعال باشد</span>
                    </label>
                    <label class="flex items-center">
                        <input type="checkbox" class="rounded border-gray-300 text-blue-600 focus:ring-blue-500">
                        <span class="mr-2 text-sm text-gray-700">محصول ویژه</span>
                    </label>
                </div>
                
                <div class="flex justify-end space-x-4 space-x-reverse pt-6 border-t">
                    <button type="button" onclick="closeModal('addProductModal')" class="px-6 py-2 border border-gray-300 rounded-lg text-gray-700 hover:bg-gray-50 transition-colors">
                        لغو
                    </button>
                    <button type="submit" class="px-6 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition-colors">
                        افزودن محصول
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- Notification -->
    <div id="notification" class="notification">
        <i class="fas fa-check-circle ml-2"></i>
        <span id="notificationText">عملیات با موفقیت انجام شد</span>
    </div>

    <script>
        // Tab Navigation
        document.querySelectorAll('.nav-link').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                
                // Remove active class from all links and tabs
                document.querySelectorAll('.nav-link').forEach(l => {
                    l.classList.remove('bg-blue-50', 'text-blue-600');
                    l.classList.add('text-gray-700');
                });
                document.querySelectorAll('.tab-content').forEach(tab => {
                    tab.classList.remove('active');
                });
                
                // Add active class to clicked link
                this.classList.add('bg-blue-50', 'text-blue-600');
                this.classList.remove('text-gray-700');
                
                // Show corresponding tab
                const tabId = this.getAttribute('data-tab');
                document.getElementById(tabId).classList.add('active');
            });
        });

        // Sidebar Toggle
        document.getElementById('sidebarToggle').addEventListener('click', function() {
            const sidebar = document.getElementById('sidebar');
            const mainContent = document.getElementById('mainContent');
            
            sidebar.classList.toggle('active');
            if (window.innerWidth <= 768) {
                mainContent.classList.toggle('expanded');
            }
        });

        // Modal Functions
        function openModal(modalId) {
            document.getElementById(modalId).classList.add('active');
        }

        function closeModal(modalId) {
            document.getElementById(modalId).classList.remove('active');
        }

        // Close modal when clicking outside
        document.querySelectorAll('.modal').forEach(modal => {
            modal.addEventListener('click', function(e) {
                if (e.target === this) {
                    this.classList.remove('active');
                }
            });
        });

        // Notification Function
        function showNotification(message, type = 'success') {
            const notification = document.getElementById('notification');
            const notificationText = document.getElementById('notificationText');
            
            notificationText.textContent = message;
            
            if (type === 'success') {
                notification.style.background = '#10b981';
            } else if (type === 'error') {
                notification.style.background = '#ef4444';
            }
            
            notification.classList.add('show');
            
            setTimeout(() => {
                notification.classList.remove('show');
            }, 3000);
        }

        // Image Upload Handling
        const imageInput = document.getElementById('imageInput');
        const imagePreview = document.getElementById('imagePreview');
        const dropArea = document.getElementById('imageDropArea');

        imageInput.addEventListener('change', handleImageSelect);

        function handleImageSelect(e) {
            const files = e.target.files;
            displayImages(files);
        }

        function displayImages(files) {
            imagePreview.innerHTML = '';
            
            Array.from(files).forEach(file => {
                if (file.type.startsWith('image/')) {
                    const reader = new FileReader();
                    reader.onload = function(e) {
                        const div = document.createElement('div');
                        div.className = 'relative';
                        div.innerHTML = `
                            <img src="${e.target.result}" class="product-image-preview border rounded-lg">
                            <button type="button" class="absolute -top-2 -right-2 bg-red-500 text-white rounded-full w-6 h-6 flex items-center justify-center text-xs hover:bg-red-600" onclick="this.parentElement.remove()">
                                <i class="fas fa-times"></i>
                            </button>
                        `;
                        imagePreview.appendChild(div);
                    };
                    reader.readAsDataURL(file);
                }
            });
        }

        // Drag and Drop
        dropArea.addEventListener('dragover', function(e) {
            e.preventDefault();
            this.classList.add('dragover');
        });

        dropArea.addEventListener('dragleave', function(e) {
            e.preventDefault();
            this.classList.remove('dragover');
        });

        dropArea.addEventListener('drop', function(e) {
            e.preventDefault();
            this.classList.remove('dragover');
            
            const files = e.dataTransfer.files;
            displayImages(files);
        });

        // Form Submission
        document.querySelector('#addProductModal form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Simulate form submission
            setTimeout(() => {
                closeModal('addProductModal');
                showNotification('محصول با موفقیت اضافه شد!');
                
                // Reset form
                this.reset();
                imagePreview.innerHTML = '';
            }, 1000);
        });

        // Sales Chart
        const ctx = document.getElementById('salesChart').getContext('2d');
        new Chart(ctx, {
            type: 'line',
            data: {
                labels: ['شنبه', 'یکشنبه', 'دوشنبه', 'سه‌شنبه', 'چهارشنبه', 'پنج‌شنبه', 'جمعه'],
                datasets: [{
                    label: 'فروش (افغانی)',
                    data: [12000, 19000, 15000, 25000, 22000, 30000, 28000],
                    borderColor: '#3b82f6',
                    backgroundColor: 'rgba(59, 130, 246, 0.1)',
                    tension: 0.4,
                    fill: true
                }]
            },
            options: {
                responsive: true,
                plugins: {
                    legend: {
                        display: false
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        ticks: {
                            callback: function(value) {
                                return value.toLocaleString() + ' ؋';
                            }
                        }
                    }
                }
            }
        });

        // Analytics Charts
        let salesTrendChart, categoryChart, revenueOrdersChart, geoChart;

        // Sales Trend Chart
        const salesTrendCtx = document.getElementById('salesTrendChart').getContext('2d');
        salesTrendChart = new Chart(salesTrendCtx, {
            type: 'line',
            data: {
                labels: ['هفته 1', 'هفته 2', 'هفته 3', 'هفته 4'],
                datasets: [{
                    label: 'فروش',
                    data: [120000, 135000, 148000, 162000],
                    borderColor: '#3b82f6',
                    backgroundColor: 'rgba(59, 130, 246, 0.1)',
                    tension: 0.4,
                    fill: true
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: false
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        ticks: {
                            callback: function(value) {
                                return value.toLocaleString() + ' ؋';
                            }
                        }
                    }
                }
            }
        });

        // Category Performance Chart
        const categoryCtx = document.getElementById('categoryChart').getContext('2d');
        categoryChart = new Chart(categoryCtx, {
            type: 'doughnut',
            data: {
                labels: ['الکترونیک', 'لباس', 'کتاب', 'لوازم خانه', 'ورزشی'],
                datasets: [{
                    data: [45, 25, 15, 10, 5],
                    backgroundColor: [
                        '#3b82f6',
                        '#10b981',
                        '#f59e0b',
                        '#ef4444',
                        '#8b5cf6'
                    ],
                    borderWidth: 0
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        position: 'bottom',
                        labels: {
                            padding: 20,
                            usePointStyle: true
                        }
                    }
                }
            }
        });

        // Revenue and Orders Chart
        const revenueOrdersCtx = document.getElementById('revenueOrdersChart').getContext('2d');
        revenueOrdersChart = new Chart(revenueOrdersCtx, {
            type: 'bar',
            data: {
                labels: ['فروردین', 'اردیبهشت', 'خرداد', 'تیر', 'مرداد', 'شهریور', 'مهر', 'آبان'],
                datasets: [{
                    label: 'درآمد (هزار افغانی)',
                    data: [320, 380, 420, 390, 450, 480, 520, 485],
                    backgroundColor: 'rgba(59, 130, 246, 0.8)',
                    borderColor: '#3b82f6',
                    borderWidth: 1,
                    yAxisID: 'y'
                }, {
                    label: 'تعداد سفارشات',
                    data: [85, 92, 108, 95, 115, 125, 142, 156],
                    backgroundColor: 'rgba(16, 185, 129, 0.8)',
                    borderColor: '#10b981',
                    borderWidth: 1,
                    yAxisID: 'y1'
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                interaction: {
                    mode: 'index',
                    intersect: false,
                },
                scales: {
                    y: {
                        type: 'linear',
                        display: true,
                        position: 'left',
                        ticks: {
                            callback: function(value) {
                                return value + 'K ؋';
                            }
                        }
                    },
                    y1: {
                        type: 'linear',
                        display: true,
                        position: 'right',
                        grid: {
                            drawOnChartArea: false,
                        },
                        ticks: {
                            callback: function(value) {
                                return value + ' سفارش';
                            }
                        }
                    }
                },
                plugins: {
                    legend: {
                        position: 'top',
                    }
                }
            }
        });

        // Geographic Chart
        const geoCtx = document.getElementById('geoChart').getContext('2d');
        geoChart = new Chart(geoCtx, {
            type: 'bar',
            data: {
                labels: ['کابل', 'هرات', 'مزار شریف', 'قندهار', 'جلال آباد'],
                datasets: [{
                    label: 'فروش (هزار افغانی)',
                    data: [185, 125, 95, 78, 52],
                    backgroundColor: [
                        '#3b82f6',
                        '#10b981',
                        '#f59e0b',
                        '#ef4444',
                        '#8b5cf6'
                    ],
                    borderRadius: 4
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: false
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        ticks: {
                            callback: function(value) {
                                return value + 'K ؋';
                            }
                        }
                    }
                }
            }
        });

        // Chart Toggle Function
        function toggleChartType(chartId) {
            if (chartId === 'salesTrendChart') {
                const currentType = salesTrendChart.config.type;
                const newType = currentType === 'line' ? 'bar' : 'line';
                
                salesTrendChart.destroy();
                salesTrendChart = new Chart(salesTrendCtx, {
                    type: newType,
                    data: {
                        labels: ['هفته 1', 'هفته 2', 'هفته 3', 'هفته 4'],
                        datasets: [{
                            label: 'فروش',
                            data: [120000, 135000, 148000, 162000],
                            borderColor: '#3b82f6',
                            backgroundColor: newType === 'line' ? 'rgba(59, 130, 246, 0.1)' : '#3b82f6',
                            tension: newType === 'line' ? 0.4 : 0,
                            fill: newType === 'line'
                        }]
                    },
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        plugins: {
                            legend: {
                                display: false
                            }
                        },
                        scales: {
                            y: {
                                beginAtZero: true,
                                ticks: {
                                    callback: function(value) {
                                        return value.toLocaleString() + ' ؋';
                                    }
                                }
                            }
                        }
                    }
                });
            }
        }

        // Chart Data Toggle
        document.getElementById('showRevenue').addEventListener('change', function() {
            revenueOrdersChart.data.datasets[0].hidden = !this.checked;
            revenueOrdersChart.update();
        });

        document.getElementById('showOrders').addEventListener('change', function() {
            revenueOrdersChart.data.datasets[1].hidden = !this.checked;
            revenueOrdersChart.update();
        });

        // Time Period Change
        document.getElementById('timePeriod').addEventListener('change', function() {
            const period = this.value;
            // Update all charts based on selected period
            updateChartsData(period);
            showNotification(`داده‌ها برای ${period} روز گذشته به‌روزرسانی شد`);
        });

        function updateChartsData(period) {
            // Simulate data update based on time period
            let newData, newLabels;
            
            switch(period) {
                case '7':
                    newLabels = ['شنبه', 'یکشنبه', 'دوشنبه', 'سه‌شنبه', 'چهارشنبه', 'پنج‌شنبه', 'جمعه'];
                    newData = [12000, 19000, 15000, 25000, 22000, 30000, 28000];
                    break;
                case '30':
                    newLabels = ['هفته 1', 'هفته 2', 'هفته 3', 'هفته 4'];
                    newData = [120000, 135000, 148000, 162000];
                    break;
                case '90':
                    newLabels = ['ماه 1', 'ماه 2', 'ماه 3'];
                    newData = [450000, 520000, 485000];
                    break;
                case '365':
                    newLabels = ['Q1', 'Q2', 'Q3', 'Q4'];
                    newData = [1200000, 1450000, 1380000, 1520000];
                    break;
            }
            
            salesTrendChart.data.labels = newLabels;
            salesTrendChart.data.datasets[0].data = newData;
            salesTrendChart.update();
        }

        // Export Functions
        document.querySelectorAll('button').forEach(button => {
            if (button.textContent.includes('دانلود گزارش')) {
                button.addEventListener('click', function() {
                    // Simulate report download
                    showNotification('گزارش در حال دانلود است...');
                    setTimeout(() => {
                        showNotification('گزارش با موفقیت دانلود شد');
                    }, 2000);
                });
            }
            
            if (button.textContent.includes('خروجی Excel')) {
                button.addEventListener('click', function() {
                    // Simulate Excel export
                    showNotification('فایل Excel در حال آماده‌سازی است...');
                    setTimeout(() => {
                        showNotification('فایل Excel آماده دانلود است');
                    }, 2000);
                });
            }
        });

        // Order Status Updates
        document.querySelectorAll('button').forEach(button => {
            if (button.textContent.trim() === 'تایید') {
                button.addEventListener('click', function() {
                    showNotification('سفارش تایید شد');
                    // Update UI
                    const row = this.closest('tr');
                    const statusCell = row.querySelector('span');
                    statusCell.textContent = 'تایید شده';
                    statusCell.className = 'px-2 py-1 text-xs font-semibold rounded-full bg-green-100 text-green-800';
                });
            }
            
            if (button.textContent.trim() === 'رد') {
                button.addEventListener('click', function() {
                    if (confirm('آیا از رد این سفارش اطمینان دارید؟')) {
                        showNotification('سفارش رد شد', 'error');
                        // Update UI
                        const row = this.closest('tr');
                        const statusCell = row.querySelector('span');
                        statusCell.textContent = 'رد شده';
                        statusCell.className = 'px-2 py-1 text-xs font-semibold rounded-full bg-red-100 text-red-800';
                    }
                });
            }
        });

        // Product Actions
        document.querySelectorAll('button').forEach(button => {
            if (button.textContent.trim() === 'حذف') {
                button.addEventListener('click', function() {
                    if (confirm('آیا از حذف این محصول اطمینان دارید؟')) {
                        this.closest('tr').remove();
                        showNotification('محصول حذف شد');
                    }
                });
            }
        });

        // Responsive Sidebar
        window.addEventListener('resize', function() {
            const sidebar = document.getElementById('sidebar');
            const mainContent = document.getElementById('mainContent');
            
            if (window.innerWidth > 768) {
                sidebar.classList.remove('active');
                mainContent.classList.remove('expanded');
            }
        });

        // Search Functionality
        document.querySelectorAll('input[placeholder*="جستجو"]').forEach(input => {
            input.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                // Implement search logic here
                console.log('Searching for:', searchTerm);
            });
        });

        // Auto-save draft functionality
        let autoSaveTimer;
        document.querySelectorAll('#addProductModal input, #addProductModal textarea, #addProductModal select').forEach(input => {
            input.addEventListener('input', function() {
                clearTimeout(autoSaveTimer);
                autoSaveTimer = setTimeout(() => {
                    // Save draft to localStorage
                    const formData = new FormData(document.querySelector('#addProductModal form'));
                    const draftData = {};
                    for (let [key, value] of formData.entries()) {
                        draftData[key] = value;
                    }
                    localStorage.setItem('productDraft', JSON.stringify(draftData));
                }, 2000);
            });
        });

        // Load draft on page load
        window.addEventListener('load', function() {
            const draft = localStorage.getItem('productDraft');
            if (draft) {
                const draftData = JSON.parse(draft);
                Object.keys(draftData).forEach(key => {
                    const input = document.querySelector(`#addProductModal [name="${key}"]`);
                    if (input) {
                        input.value = draftData[key];
                    }
                });
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'96304f97b6f9c8fc',t:'MTc1MzE1OTc2MS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>


<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>پنل فروشنده - دریچه</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;600;700;800;900&display=swap');
        
        * {
            font-family: 'Vazirmatn', sans-serif;
        }
        
        .sidebar {
            transition: transform 0.3s ease;
        }
        
        .sidebar.collapsed {
            transform: translateX(100%);
        }
        
        .main-content {
            transition: margin-right 0.3s ease;
        }
        
        .main-content.expanded {
            margin-right: 0;
        }
        
        .stat-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .stat-card.green {
            background: linear-gradient(135deg, #4ade80 0%, #22c55e 100%);
        }
        
        .stat-card.orange {
            background: linear-gradient(135deg, #fb923c 0%, #f97316 100%);
        }
        
        .stat-card.red {
            background: linear-gradient(135deg, #f87171 0%, #ef4444 100%);
        }
        
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
            z-index: 1000;
        }
        
        .modal.active {
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
        }
        
        .notification {
            position: fixed;
            top: 20px;
            right: 20px;
            background: #10b981;
            color: white;
            padding: 12px 24px;
            border-radius: 8px;
            transform: translateX(400px);
            transition: transform 0.3s ease;
            z-index: 1001;
        }
        
        .notification.show {
            transform: translateX(0);
        }
        
        .product-image-preview {
            width: 100px;
            height: 100px;
            object-fit: cover;
            border-radius: 8px;
        }
        
        .drag-drop-area {
            border: 2px dashed #d1d5db;
            border-radius: 8px;
            padding: 40px;
            text-align: center;
            transition: all 0.3s ease;
        }
        
        .drag-drop-area.dragover {
            border-color: #3b82f6;
            background-color: #eff6ff;
        }
        
        @media (max-width: 768px) {
            .sidebar {
                position: fixed;
                top: 0;
                right: 0;
                height: 100vh;
                z-index: 50;
                transform: translateX(100%);
            }
            
            .sidebar.active {
                transform: translateX(0);
            }
            
            .main-content {
                margin-right: 0;
            }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Top Header -->
    <header class="bg-white shadow-sm border-b sticky top-0 z-40">
        <div class="flex items-center justify-between px-6 py-4">
            <div class="flex items-center space-x-4 space-x-reverse">
                <button id="sidebarToggle" class="text-gray-600 hover:text-gray-800 md:hidden">
                    <i class="fas fa-bars text-xl"></i>
                </button>
                <h1 class="text-2xl font-bold text-blue-600">دریچه</h1>
                <span class="text-gray-500">پنل فروشنده</span>
            </div>
            
            <div class="flex items-center space-x-4 space-x-reverse">
                <button class="relative text-gray-600 hover:text-gray-800">
                    <i class="fas fa-bell text-xl"></i>
                    <span class="absolute -top-1 -right-1 bg-red-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center">3</span>
                </button>
                
                <div class="flex items-center space-x-3 space-x-reverse">
                    <img src="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHZpZXdCb3g9IjAgMCA0MCA0MCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGNpcmNsZSBjeD0iMjAiIGN5PSIyMCIgcj0iMjAiIGZpbGw9IiMzYjgyZjYiLz4KPHN2ZyB4PSI4IiB5PSI4IiB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSI+CjxwYXRoIGQ9Ik0yMCAyMXYtMmE0IDQgMCAwIDAtNC00SDhhNCA0IDAgMCAwLTQgNHYyIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIvPgo8Y2lyY2xlIGN4PSIxMiIgY3k9IjciIHI9IjQiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+Cjwvc3ZnPgo8L3N2Zz4K" 
                         alt="Profile" class="w-10 h-10 rounded-full">
                    <div>
                        <div class="font-medium text-gray-800">احمد محمدی</div>
                        <div class="text-sm text-gray-500">فروشنده طلایی</div>
                    </div>
                    <i class="fas fa-chevron-down text-gray-400"></i>
                </div>
            </div>
        </div>
    </header>

    <div class="flex">
        <!-- Sidebar -->
        <aside id="sidebar" class="sidebar w-64 bg-white shadow-lg h-screen sticky top-16">
            <nav class="p-4">
                <ul class="space-y-2">
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg bg-blue-50 text-blue-600" data-tab="dashboard">
                            <i class="fas fa-tachometer-alt"></i>
                            <span>داشبورد</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="products">
                            <i class="fas fa-box"></i>
                            <span>محصولات</span>
                            <span class="bg-blue-100 text-blue-600 px-2 py-1 rounded-full text-xs mr-auto">24</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="orders">
                            <i class="fas fa-shopping-cart"></i>
                            <span>سفارشات</span>
                            <span class="bg-red-100 text-red-600 px-2 py-1 rounded-full text-xs mr-auto">5</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="inventory">
                            <i class="fas fa-warehouse"></i>
                            <span>موجودی انبار</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="analytics">
                            <i class="fas fa-chart-line"></i>
                            <span>آمار و گزارشات</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="customers">
                            <i class="fas fa-users"></i>
                            <span>مشتریان</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="reviews">
                            <i class="fas fa-star"></i>
                            <span>نظرات و امتیازات</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="finance">
                            <i class="fas fa-dollar-sign"></i>
                            <span>مالی</span>
                        </a>
                    </li>
                    <li>
                        <a href="#" class="nav-link flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-gray-700 hover:bg-gray-50" data-tab="settings">
                            <i class="fas fa-cog"></i>
                            <span>تنظیمات</span>
                        </a>
                    </li>
                </ul>
                
                <div class="mt-8 pt-4 border-t">
                    <a href="#" class="flex items-center space-x-3 space-x-reverse p-3 rounded-lg text-red-600 hover:bg-red-50">
                        <i class="fas fa-sign-out-alt"></i>
                        <span>خروج</span>
                    </a>
                </div>
            </nav>
        </aside>

        <!-- Main Content -->
        <main id="mainContent" class="main-content flex-1 p-6 mr-64">
            <!-- Dashboard Tab -->
            <div id="dashboard" class="tab-content active">
                <div class="mb-6">
                    <h2 class="text-2xl font-bold text-gray-800 mb-2">داشبورد فروشنده</h2>
                    <p class="text-gray-600">خلاصه‌ای از عملکرد فروشگاه شما</p>
                </div>

                <!-- Stats Cards -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-8">
                    <div class="stat-card text-white p-6 rounded-xl">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-white/80 text-sm">فروش امروز</p>
                                <p class="text-2xl font-bold">12,500 ؋</p>
                                <p class="text-white/80 text-sm">+15% از دیروز</p>
                            </div>
                            <i class="fas fa-chart-line text-3xl text-white/60"></i>
                        </div>
                    </div>
                    
                    <div class="stat-card green text-white p-6 rounded-xl">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-white/80 text-sm">سفارشات جدید</p>
                                <p class="text-2xl font-bold">8</p>
                                <p class="text-white/80 text-sm">در انتظار تایید</p>
                            </div>
                            <i class="fas fa-shopping-cart text-3xl text-white/60"></i>
                        </div>
                    </div>
                    
                    <div class="stat-card orange text-white p-6 rounded-xl">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-white/80 text-sm">محصولات</p>
                                <p class="text-2xl font-bold">24</p>
                                <p class="text-white/80 text-sm">3 ناموجود</p>
                            </div>
                            <i class="fas fa-box text-3xl text-white/60"></i>
                        </div>
                    </div>
                    
                    <div class="stat-card red text-white p-6 rounded-xl">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-white/80 text-sm">امتیاز فروشگاه</p>
                                <p class="text-2xl font-bold">4.8</p>
                                <p class="text-white/80 text-sm">از 156 نظر</p>
                            </div>
                            <i class="fas fa-star text-3xl text-white/60"></i>
                        </div>
                    </div>
                </div>

                <!-- Charts and Recent Activity -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">فروش هفتگی</h3>
                        <canvas id="salesChart" width="400" height="200"></canvas>
                    </div>
                    
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">فعالیت‌های اخیر</h3>
                        <div class="space-y-4">
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="w-2 h-2 bg-green-500 rounded-full"></div>
                                <div class="flex-1">
                                    <p class="text-sm text-gray-800">سفارش جدید از علی احمدی</p>
                                    <p class="text-xs text-gray-500">5 دقیقه پیش</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="w-2 h-2 bg-blue-500 rounded-full"></div>
                                <div class="flex-1">
                                    <p class="text-sm text-gray-800">محصول "گوشی سامسونگ" به‌روزرسانی شد</p>
                                    <p class="text-xs text-gray-500">15 دقیقه پیش</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="w-2 h-2 bg-yellow-500 rounded-full"></div>
                                <div class="flex-1">
                                    <p class="text-sm text-gray-800">نظر جدید برای "لپ تاپ ایسوس"</p>
                                    <p class="text-xs text-gray-500">30 دقیقه پیش</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-3 space-x-reverse">
                                <div class="w-2 h-2 bg-red-500 rounded-full"></div>
                                <div class="flex-1">
                                    <p class="text-sm text-gray-800">موجودی "هدفون بلوتوثی" کم شده</p>
                                    <p class="text-xs text-gray-500">1 ساعت پیش</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Quick Actions -->
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-lg font-bold text-gray-800 mb-4">عملیات سریع</h3>
                    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                        <button class="flex flex-col items-center p-4 border-2 border-dashed border-gray-300 rounded-lg hover:border-blue-500 hover:bg-blue-50 transition-colors" onclick="openModal('addProductModal')">
                            <i class="fas fa-plus text-2xl text-gray-400 mb-2"></i>
                            <span class="text-sm text-gray-600">افزودن محصول</span>
                        </button>
                        <button class="flex flex-col items-center p-4 border-2 border-dashed border-gray-300 rounded-lg hover:border-green-500 hover:bg-green-50 transition-colors">
                            <i class="fas fa-eye text-2xl text-gray-400 mb-2"></i>
                            <span class="text-sm text-gray-600">مشاهده سفارشات</span>
                        </button>
                        <button class="flex flex-col items-center p-4 border-2 border-dashed border-gray-300 rounded-lg hover:border-purple-500 hover:bg-purple-50 transition-colors">
                            <i class="fas fa-chart-bar text-2xl text-gray-400 mb-2"></i>
                            <span class="text-sm text-gray-600">گزارش فروش</span>
                        </button>
                        <button class="flex flex-col items-center p-4 border-2 border-dashed border-gray-300 rounded-lg hover:border-orange-500 hover:bg-orange-50 transition-colors">
                            <i class="fas fa-cog text-2xl text-gray-400 mb-2"></i>
                            <span class="text-sm text-gray-600">تنظیمات</span>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Products Tab -->
            <div id="products" class="tab-content">
                <div class="flex items-center justify-between mb-6">
                    <div>
                        <h2 class="text-2xl font-bold text-gray-800 mb-2">مدیریت محصولات</h2>
                        <p class="text-gray-600">مدیریت و ویرایش محصولات فروشگاه</p>
                    </div>
                    <button class="bg-blue-600 text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition-colors" onclick="openModal('addProductModal')">
                        <i class="fas fa-plus ml-2"></i>
                        افزودن محصول جدید
                    </button>
                </div>

                <!-- Filters -->
                <div class="bg-white p-4 rounded-lg shadow-sm mb-6">
                    <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
                        <input type="text" placeholder="جستجو محصول..." class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                        <select class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                            <option>همه دسته‌ها</option>
                            <option>الکترونیک</option>
                            <option>لباس</option>
                            <option>کتاب</option>
                        </select>
                        <select class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                            <option>همه وضعیت‌ها</option>
                            <option>فعال</option>
                            <option>غیرفعال</option>
                            <option>ناموجود</option>
                        </select>
                        <button class="bg-gray-100 text-gray-700 px-4 py-2 rounded-lg hover:bg-gray-200 transition-colors">
                            <i class="fas fa-filter ml-2"></i>
                            فیلتر
                        </button>
                    </div>
                </div>

                <!-- Products Table -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full">
                            <thead class="bg-gray-50">
                                <tr>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">محصول</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">دسته‌بندی</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">قیمت</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">موجودی</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">وضعیت</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">عملیات</th>
                                </tr>
                            </thead>
                            <tbody class="bg-white divide-y divide-gray-200">
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="flex items-center">
                                            <div class="w-12 h-12 bg-gray-200 rounded-lg flex items-center justify-center ml-4">
                                                <i class="fas fa-mobile-alt text-gray-400"></i>
                                            </div>
                                            <div>
                                                <div class="text-sm font-medium text-gray-900">گوشی سامسونگ A54</div>
                                                <div class="text-sm text-gray-500">کد: PRD001</div>
                                            </div>
                                        </div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">الکترونیک</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">15,000 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">12</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-green-100 text-green-800">فعال</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-blue-600 hover:text-blue-900 ml-3">ویرایش</button>
                                        <button class="text-red-600 hover:text-red-900">حذف</button>
                                    </td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="flex items-center">
                                            <div class="w-12 h-12 bg-gray-200 rounded-lg flex items-center justify-center ml-4">
                                                <i class="fas fa-laptop text-gray-400"></i>
                                            </div>
                                            <div>
                                                <div class="text-sm font-medium text-gray-900">لپ تاپ ایسوس</div>
                                                <div class="text-sm text-gray-500">کد: PRD002</div>
                                            </div>
                                        </div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">الکترونیک</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">45,000 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">5</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-green-100 text-green-800">فعال</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-blue-600 hover:text-blue-900 ml-3">ویرایش</button>
                                        <button class="text-red-600 hover:text-red-900">حذف</button>
                                    </td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="flex items-center">
                                            <div class="w-12 h-12 bg-gray-200 rounded-lg flex items-center justify-center ml-4">
                                                <i class="fas fa-headphones text-gray-400"></i>
                                            </div>
                                            <div>
                                                <div class="text-sm font-medium text-gray-900">هدفون بلوتوثی</div>
                                                <div class="text-sm text-gray-500">کد: PRD003</div>
                                            </div>
                                        </div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">الکترونیک</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">1,200 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">0</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-red-100 text-red-800">ناموجود</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-blue-600 hover:text-blue-900 ml-3">ویرایش</button>
                                        <button class="text-red-600 hover:text-red-900">حذف</button>
                                    </td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    
                    <!-- Pagination -->
                    <div class="bg-white px-4 py-3 flex items-center justify-between border-t border-gray-200">
                        <div class="flex-1 flex justify-between sm:hidden">
                            <button class="relative inline-flex items-center px-4 py-2 border border-gray-300 text-sm font-medium rounded-md text-gray-700 bg-white hover:bg-gray-50">قبلی</button>
                            <button class="ml-3 relative inline-flex items-center px-4 py-2 border border-gray-300 text-sm font-medium rounded-md text-gray-700 bg-white hover:bg-gray-50">بعدی</button>
                        </div>
                        <div class="hidden sm:flex-1 sm:flex sm:items-center sm:justify-between">
                            <div>
                                <p class="text-sm text-gray-700">نمایش <span class="font-medium">1</span> تا <span class="font-medium">10</span> از <span class="font-medium">24</span> نتیجه</p>
                            </div>
                            <div>
                                <nav class="relative z-0 inline-flex rounded-md shadow-sm -space-x-px" aria-label="Pagination">
                                    <button class="relative inline-flex items-center px-2 py-2 rounded-r-md border border-gray-300 bg-white text-sm font-medium text-gray-500 hover:bg-gray-50">قبلی</button>
                                    <button class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">1</button>
                                    <button class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-blue-50 text-sm font-medium text-blue-600">2</button>
                                    <button class="relative inline-flex items-center px-4 py-2 border border-gray-300 bg-white text-sm font-medium text-gray-700 hover:bg-gray-50">3</button>
                                    <button class="relative inline-flex items-center px-2 py-2 rounded-l-md border border-gray-300 bg-white text-sm font-medium text-gray-500 hover:bg-gray-50">بعدی</button>
                                </nav>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Orders Tab -->
            <div id="orders" class="tab-content">
                <div class="mb-6">
                    <h2 class="text-2xl font-bold text-gray-800 mb-2">مدیریت سفارشات</h2>
                    <p class="text-gray-600">پیگیری و مدیریت سفارشات مشتریان</p>
                </div>

                <!-- Order Stats -->
                <div class="grid grid-cols-1 md:grid-cols-4 gap-4 mb-6">
                    <div class="bg-white p-4 rounded-lg shadow-sm">
                        <div class="flex items-center">
                            <div class="p-2 bg-yellow-100 rounded-lg">
                                <i class="fas fa-clock text-yellow-600"></i>
                            </div>
                            <div class="mr-3">
                                <p class="text-sm text-gray-600">در انتظار تایید</p>
                                <p class="text-xl font-bold text-gray-800">5</p>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white p-4 rounded-lg shadow-sm">
                        <div class="flex items-center">
                            <div class="p-2 bg-blue-100 rounded-lg">
                                <i class="fas fa-truck text-blue-600"></i>
                            </div>
                            <div class="mr-3">
                                <p class="text-sm text-gray-600">در حال ارسال</p>
                                <p class="text-xl font-bold text-gray-800">8</p>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white p-4 rounded-lg shadow-sm">
                        <div class="flex items-center">
                            <div class="p-2 bg-green-100 rounded-lg">
                                <i class="fas fa-check text-green-600"></i>
                            </div>
                            <div class="mr-3">
                                <p class="text-sm text-gray-600">تحویل شده</p>
                                <p class="text-xl font-bold text-gray-800">156</p>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white p-4 rounded-lg shadow-sm">
                        <div class="flex items-center">
                            <div class="p-2 bg-red-100 rounded-lg">
                                <i class="fas fa-times text-red-600"></i>
                            </div>
                            <div class="mr-3">
                                <p class="text-sm text-gray-600">لغو شده</p>
                                <p class="text-xl font-bold text-gray-800">12</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Orders Table -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full">
                            <thead class="bg-gray-50">
                                <tr>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">شماره سفارش</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">مشتری</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">محصولات</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">مبلغ</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">وضعیت</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">تاریخ</th>
                                    <th class="px-6 py-3 text-right text-xs font-medium text-gray-500 uppercase tracking-wider">عملیات</th>
                                </tr>
                            </thead>
                            <tbody class="bg-white divide-y divide-gray-200">
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">#ORD001</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="text-sm text-gray-900">علی احمدی</div>
                                        <div class="text-sm text-gray-500">ali@example.com</div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">گوشی سامسونگ (×1)</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">15,000 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-yellow-100 text-yellow-800">در انتظار تایید</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">1403/08/15</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-green-600 hover:text-green-900 ml-3">تایید</button>
                                        <button class="text-red-600 hover:text-red-900">رد</button>
                                    </td>
                                </tr>
                                <tr>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">#ORD002</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <div class="text-sm text-gray-900">فاطمه کریمی</div>
                                        <div class="text-sm text-gray-500">fateme@example.com</div>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">لپ تاپ ایسوس (×1)</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">45,000 ؋</td>
                                    <td class="px-6 py-4 whitespace-nowrap">
                                        <span class="px-2 py-1 text-xs font-semibold rounded-full bg-blue-100 text-blue-800">در حال ارسال</span>
                                    </td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">1403/08/14</td>
                                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium">
                                        <button class="text-blue-600 hover:text-blue-900">جزئیات</button>
                                    </td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>

            <!-- Other tabs content would go here... -->
            <div id="inventory" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">مدیریت موجودی انبار</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>

            <div id="analytics" class="tab-content">
                <div class="mb-6">
                    <h2 class="text-2xl font-bold text-gray-800 mb-2">آمار و گزارشات</h2>
                    <p class="text-gray-600">تحلیل جامع عملکرد فروشگاه و روند فروش</p>
                </div>

                <!-- Time Period Selector -->
                <div class="bg-white p-4 rounded-lg shadow-sm mb-6">
                    <div class="flex flex-wrap items-center justify-between gap-4">
                        <div class="flex items-center space-x-4 space-x-reverse">
                            <label class="text-sm font-medium text-gray-700">بازه زمانی:</label>
                            <select id="timePeriod" class="border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                                <option value="7">7 روز گذشته</option>
                                <option value="30" selected>30 روز گذشته</option>
                                <option value="90">3 ماه گذشته</option>
                                <option value="365">سال گذشته</option>
                            </select>
                        </div>
                        <div class="flex items-center space-x-2 space-x-reverse">
                            <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                                <i class="fas fa-download ml-2"></i>
                                دانلود گزارش
                            </button>
                            <button class="bg-green-600 text-white px-4 py-2 rounded-lg hover:bg-green-700 transition-colors">
                                <i class="fas fa-file-excel ml-2"></i>
                                خروجی Excel
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Key Metrics -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-8">
                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-blue-500">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-600 text-sm">کل فروش</p>
                                <p class="text-2xl font-bold text-gray-800">485,000 ؋</p>
                                <div class="flex items-center mt-2">
                                    <i class="fas fa-arrow-up text-green-500 text-xs"></i>
                                    <span class="text-green-500 text-sm mr-1">+12.5%</span>
                                    <span class="text-gray-500 text-sm">نسبت به ماه قبل</span>
                                </div>
                            </div>
                            <div class="p-3 bg-blue-100 rounded-full">
                                <i class="fas fa-dollar-sign text-blue-600 text-xl"></i>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-green-500">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-600 text-sm">تعداد سفارشات</p>
                                <p class="text-2xl font-bold text-gray-800">156</p>
                                <div class="flex items-center mt-2">
                                    <i class="fas fa-arrow-up text-green-500 text-xs"></i>
                                    <span class="text-green-500 text-sm mr-1">+8.3%</span>
                                    <span class="text-gray-500 text-sm">نسبت به ماه قبل</span>
                                </div>
                            </div>
                            <div class="p-3 bg-green-100 rounded-full">
                                <i class="fas fa-shopping-cart text-green-600 text-xl"></i>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-orange-500">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-600 text-sm">میانگین سفارش</p>
                                <p class="text-2xl font-bold text-gray-800">3,109 ؋</p>
                                <div class="flex items-center mt-2">
                                    <i class="fas fa-arrow-up text-green-500 text-xs"></i>
                                    <span class="text-green-500 text-sm mr-1">+4.1%</span>
                                    <span class="text-gray-500 text-sm">نسبت به ماه قبل</span>
                                </div>
                            </div>
                            <div class="p-3 bg-orange-100 rounded-full">
                                <i class="fas fa-chart-bar text-orange-600 text-xl"></i>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm border-r-4 border-purple-500">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-600 text-sm">نرخ تبدیل</p>
                                <p class="text-2xl font-bold text-gray-800">3.2%</p>
                                <div class="flex items-center mt-2">
                                    <i class="fas fa-arrow-down text-red-500 text-xs"></i>
                                    <span class="text-red-500 text-sm mr-1">-0.5%</span>
                                    <span class="text-gray-500 text-sm">نسبت به ماه قبل</span>
                                </div>
                            </div>
                            <div class="p-3 bg-purple-100 rounded-full">
                                <i class="fas fa-percentage text-purple-600 text-xl"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Charts Row -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                    <!-- Sales Trend Chart -->
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <div class="flex items-center justify-between mb-4">
                            <h3 class="text-lg font-bold text-gray-800">روند فروش</h3>
                            <div class="flex items-center space-x-2 space-x-reverse">
                                <button class="text-sm text-blue-600 hover:text-blue-800" onclick="toggleChartType('salesTrendChart')">تغییر نمودار</button>
                            </div>
                        </div>
                        <canvas id="salesTrendChart" height="300"></canvas>
                    </div>

                    <!-- Category Performance -->
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">عملکرد دسته‌بندی‌ها</h3>
                        <canvas id="categoryChart" height="300"></canvas>
                    </div>
                </div>

                <!-- Revenue and Orders Chart -->
                <div class="bg-white p-6 rounded-xl shadow-sm mb-8">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-lg font-bold text-gray-800">درآمد و تعداد سفارشات</h3>
                        <div class="flex items-center space-x-4 space-x-reverse">
                            <label class="flex items-center">
                                <input type="checkbox" id="showRevenue" checked class="rounded border-gray-300 text-blue-600 focus:ring-blue-500">
                                <span class="mr-2 text-sm text-gray-700">درآمد</span>
                            </label>
                            <label class="flex items-center">
                                <input type="checkbox" id="showOrders" checked class="rounded border-gray-300 text-green-600 focus:ring-green-500">
                                <span class="mr-2 text-sm text-gray-700">سفارشات</span>
                            </label>
                        </div>
                    </div>
                    <canvas id="revenueOrdersChart" height="400"></canvas>
                </div>

                <!-- Detailed Analytics Tables -->
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 mb-8">
                    <!-- Top Products -->
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">محصولات پرفروش</h3>
                        <div class="space-y-4">
                            <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 bg-blue-100 rounded-lg flex items-center justify-center ml-3">
                                        <i class="fas fa-mobile-alt text-blue-600"></i>
                                    </div>
                                    <div>
                                        <p class="font-medium text-gray-800">گوشی سامسونگ A54</p>
                                        <p class="text-sm text-gray-500">45 فروش</p>
                                    </div>
                                </div>
                                <div class="text-left">
                                    <p class="font-bold text-gray-800">675,000 ؋</p>
                                    <p class="text-sm text-green-600">+15%</p>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 bg-green-100 rounded-lg flex items-center justify-center ml-3">
                                        <i class="fas fa-laptop text-green-600"></i>
                                    </div>
                                    <div>
                                        <p class="font-medium text-gray-800">لپ تاپ ایسوس</p>
                                        <p class="text-sm text-gray-500">23 فروش</p>
                                    </div>
                                </div>
                                <div class="text-left">
                                    <p class="font-bold text-gray-800">1,035,000 ؋</p>
                                    <p class="text-sm text-green-600">+8%</p>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 bg-purple-100 rounded-lg flex items-center justify-center ml-3">
                                        <i class="fas fa-headphones text-purple-600"></i>
                                    </div>
                                    <div>
                                        <p class="font-medium text-gray-800">هدفون بلوتوثی</p>
                                        <p class="text-sm text-gray-500">67 فروش</p>
                                    </div>
                                </div>
                                <div class="text-left">
                                    <p class="font-bold text-gray-800">80,400 ؋</p>
                                    <p class="text-sm text-red-600">-3%</p>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-10 h-10 bg-orange-100 rounded-lg flex items-center justify-center ml-3">
                                        <i class="fas fa-tablet-alt text-orange-600"></i>
                                    </div>
                                    <div>
                                        <p class="font-medium text-gray-800">تبلت سامسونگ</p>
                                        <p class="text-sm text-gray-500">18 فروش</p>
                                    </div>
                                </div>
                                <div class="text-left">
                                    <p class="font-bold text-gray-800">270,000 ؋</p>
                                    <p class="text-sm text-green-600">+22%</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Customer Insights -->
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">تحلیل مشتریان</h3>
                        <div class="space-y-6">
                            <div>
                                <div class="flex items-center justify-between mb-2">
                                    <span class="text-sm text-gray-600">مشتریان جدید</span>
                                    <span class="text-sm font-medium text-gray-800">34</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-blue-600 h-2 rounded-full" style="width: 68%"></div>
                                </div>
                            </div>

                            <div>
                                <div class="flex items-center justify-between mb-2">
                                    <span class="text-sm text-gray-600">مشتریان بازگشتی</span>
                                    <span class="text-sm font-medium text-gray-800">89</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-green-600 h-2 rounded-full" style="width: 89%"></div>
                                </div>
                            </div>

                            <div>
                                <div class="flex items-center justify-between mb-2">
                                    <span class="text-sm text-gray-600">مشتریان VIP</span>
                                    <span class="text-sm font-medium text-gray-800">12</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-purple-600 h-2 rounded-full" style="width: 24%"></div>
                                </div>
                            </div>

                            <div class="pt-4 border-t">
                                <h4 class="font-medium text-gray-800 mb-3">آمار رضایت مشتریان</h4>
                                <div class="flex items-center justify-between">
                                    <div class="text-center">
                                        <div class="text-2xl font-bold text-green-600">4.8</div>
                                        <div class="text-xs text-gray-500">میانگین امتیاز</div>
                                    </div>
                                    <div class="text-center">
                                        <div class="text-2xl font-bold text-blue-600">94%</div>
                                        <div class="text-xs text-gray-500">رضایت کلی</div>
                                    </div>
                                    <div class="text-center">
                                        <div class="text-2xl font-bold text-orange-600">156</div>
                                        <div class="text-xs text-gray-500">نظرات</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Geographic Sales -->
                <div class="bg-white p-6 rounded-xl shadow-sm mb-8">
                    <h3 class="text-lg font-bold text-gray-800 mb-4">فروش بر اساس منطقه</h3>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                        <div class="space-y-4">
                            <div class="flex items-center justify-between p-3 border rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-3 h-3 bg-blue-500 rounded-full ml-3"></div>
                                    <span class="text-gray-700">کابل</span>
                                </div>
                                <div class="text-left">
                                    <div class="font-bold text-gray-800">185,000 ؋</div>
                                    <div class="text-sm text-gray-500">38% از کل فروش</div>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 border rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-3 h-3 bg-green-500 rounded-full ml-3"></div>
                                    <span class="text-gray-700">هرات</span>
                                </div>
                                <div class="text-left">
                                    <div class="font-bold text-gray-800">125,000 ؋</div>
                                    <div class="text-sm text-gray-500">26% از کل فروش</div>
                                </div>
                            </div>

                            <div class="flex items-center justify-between p-3 border rounded-lg">
                                <div class="flex items-center">
                                    <div class="w-3 h-3 bg-orange-500 rounded-full ml-3"></div>
                                    <span class="text-gray-700">مزار شریف</span>
                                </div>
                                <div class="text-left">
                                    <div class="font-bold text-gray-800">95,000 ؋</div>
                                    <div class="text-sm text-gray-500">20% از کل فروش</div>
                                </div>
                            </div>
                        </div>

                        <div class="md:col-span-2">
                            <canvas id="geoChart" height="200"></canvas>
                        </div>
                    </div>
                </div>

                <!-- Performance Indicators -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">شاخص‌های عملکرد</h3>
                        <div class="space-y-4">
                            <div class="flex items-center justify-between">
                                <span class="text-gray-600">نرخ بازگشت</span>
                                <span class="font-bold text-red-600">2.3%</span>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="text-gray-600">زمان پردازش</span>
                                <span class="font-bold text-green-600">1.2 روز</span>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="text-gray-600">رضایت مشتری</span>
                                <span class="font-bold text-blue-600">94%</span>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="text-gray-600">نرخ تکمیل سفارش</span>
                                <span class="font-bold text-green-600">97.8%</span>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">مقایسه با رقبا</h3>
                        <div class="space-y-4">
                            <div>
                                <div class="flex items-center justify-between mb-1">
                                    <span class="text-sm text-gray-600">قیمت‌گذاری</span>
                                    <span class="text-sm font-medium text-green-600">بهتر از 78%</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-green-600 h-2 rounded-full" style="width: 78%"></div>
                                </div>
                            </div>

                            <div>
                                <div class="flex items-center justify-between mb-1">
                                    <span class="text-sm text-gray-600">کیفیت خدمات</span>
                                    <span class="text-sm font-medium text-blue-600">بهتر از 85%</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-blue-600 h-2 rounded-full" style="width: 85%"></div>
                                </div>
                            </div>

                            <div>
                                <div class="flex items-center justify-between mb-1">
                                    <span class="text-sm text-gray-600">سرعت ارسال</span>
                                    <span class="text-sm font-medium text-orange-600">بهتر از 65%</span>
                                </div>
                                <div class="w-full bg-gray-200 rounded-full h-2">
                                    <div class="bg-orange-600 h-2 rounded-full" style="width: 65%"></div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-sm">
                        <h3 class="text-lg font-bold text-gray-800 mb-4">پیش‌بینی فروش</h3>
                        <div class="space-y-4">
                            <div class="text-center p-4 bg-blue-50 rounded-lg">
                                <div class="text-2xl font-bold text-blue-600">520,000 ؋</div>
                                <div class="text-sm text-gray-600">پیش‌بینی ماه آینده</div>
                                <div class="text-xs text-green-600 mt-1">+7.2% رشد</div>
                            </div>

                            <div class="space-y-2">
                                <div class="flex items-center justify-between text-sm">
                                    <span class="text-gray-600">احتمال دستیابی</span>
                                    <span class="font-medium text-green-600">87%</span>
                                </div>
                                <div class="flex items-center justify-between text-sm">
                                    <span class="text-gray-600">بهترین حالت</span>
                                    <span class="font-medium text-gray-800">580,000 ؋</span>
                                </div>
                                <div class="flex items-center justify-between text-sm">
                                    <span class="text-gray-600">بدترین حالت</span>
                                    <span class="font-medium text-gray-800">460,000 ؋</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div id="customers" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">مدیریت مشتریان</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>

            <div id="reviews" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">نظرات و امتیازات</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>

            <div id="finance" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">مدیریت مالی</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>

            <div id="settings" class="tab-content">
                <h2 class="text-2xl font-bold text-gray-800 mb-4">تنظیمات فروشگاه</h2>
                <p class="text-gray-600">این بخش در حال توسعه است...</p>
            </div>
        </main>
    </div>

    <!-- Add Product Modal -->
    <div id="addProductModal" class="modal">
        <div class="bg-white rounded-lg shadow-xl max-w-2xl w-full mx-4 max-h-screen overflow-y-auto">
            <div class="flex items-center justify-between p-6 border-b">
                <h3 class="text-lg font-bold text-gray-800">افزودن محصول جدید</h3>
                <button onclick="closeModal('addProductModal')" class="text-gray-400 hover:text-gray-600">
                    <i class="fas fa-times text-xl"></i>
                </button>
            </div>
            
            <form class="p-6 space-y-6">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">نام محصول</label>
                        <input type="text" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="نام محصول را وارد کنید">
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">دسته‌بندی</label>
                        <select class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500">
                            <option>انتخاب دسته‌بندی</option>
                            <option>الکترونیک</option>
                            <option>لباس و پوشاک</option>
                            <option>لوازم خانه</option>
                            <option>کتاب</option>
                        </select>
                    </div>
                </div>
                
                <div>
                    <label class="block text-sm font-medium text-gray-700 mb-2">توضیحات محصول</label>
                    <textarea rows="4" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="توضیحات کامل محصول را وارد کنید"></textarea>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">قیمت (افغانی)</label>
                        <input type="number" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="0">
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">موجودی</label>
                        <input type="number" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="0">
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">وزن (گرم)</label>
                        <input type="number" class="w-full border border-gray-300 rounded-lg px-4 py-2 focus:outline-none focus:border-blue-500" placeholder="0">
                    </div>
                </div>
                
                <div>
                    <label class="block text-sm font-medium text-gray-700 mb-2">تصاویر محصول</label>
                    <div class="drag-drop-area" id="imageDropArea">
                        <i class="fas fa-cloud-upload-alt text-4xl text-gray-400 mb-4"></i>
                        <p class="text-gray-600 mb-2">تصاویر را اینجا بکشید یا کلیک کنید</p>
                        <input type="file" id="imageInput" multiple accept="image/*" class="hidden">
                        <button type="button" onclick="document.getElementById('imageInput').click()" class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition-colors">
                            انتخاب فایل
                        </button>
                    </div>
                    <div id="imagePreview" class="mt-4 grid grid-cols-4 gap-4"></div>
                </div>
                
                <div class="flex items-center space-x-4 space-x-reverse">
                    <label class="flex items-center">
                        <input type="checkbox" class="rounded border-gray-300 text-blue-600 focus:ring-blue-500">
                        <span class="mr-2 text-sm text-gray-700">محصول فعال باشد</span>
                    </label>
                    <label class="flex items-center">
                        <input type="checkbox" class="rounded border-gray-300 text-blue-600 focus:ring-blue-500">
                        <span class="mr-2 text-sm text-gray-700">محصول ویژه</span>
                    </label>
                </div>
                
                <div class="flex justify-end space-x-4 space-x-reverse pt-6 border-t">
                    <button type="button" onclick="closeModal('addProductModal')" class="px-6 py-2 border border-gray-300 rounded-lg text-gray-700 hover:bg-gray-50 transition-colors">
                        لغو
                    </button>
                    <button type="submit" class="px-6 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition-colors">
                        افزودن محصول
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- Notification -->
    <div id="notification" class="notification">
        <i class="fas fa-check-circle ml-2"></i>
        <span id="notificationText">عملیات با موفقیت انجام شد</span>
    </div>

    <script>
        // Tab Navigation
        document.querySelectorAll('.nav-link').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                
                // Remove active class from all links and tabs
                document.querySelectorAll('.nav-link').forEach(l => {
                    l.classList.remove('bg-blue-50', 'text-blue-600');
                    l.classList.add('text-gray-700');
                });
                document.querySelectorAll('.tab-content').forEach(tab => {
                    tab.classList.remove('active');
                });
                
                // Add active class to clicked link
                this.classList.add('bg-blue-50', 'text-blue-600');
                this.classList.remove('text-gray-700');
                
                // Show corresponding tab
                const tabId = this.getAttribute('data-tab');
                document.getElementById(tabId).classList.add('active');
            });
        });

        // Sidebar Toggle
        document.getElementById('sidebarToggle').addEventListener('click', function() {
            const sidebar = document.getElementById('sidebar');
            const mainContent = document.getElementById('mainContent');
            
            sidebar.classList.toggle('active');
            if (window.innerWidth <= 768) {
                mainContent.classList.toggle('expanded');
            }
        });

        // Modal Functions
        function openModal(modalId) {
            document.getElementById(modalId).classList.add('active');
        }

        function closeModal(modalId) {
            document.getElementById(modalId).classList.remove('active');
        }

        // Close modal when clicking outside
        document.querySelectorAll('.modal').forEach(modal => {
            modal.addEventListener('click', function(e) {
                if (e.target === this) {
                    this.classList.remove('active');
                }
            });
        });

        // Notification Function
        function showNotification(message, type = 'success') {
            const notification = document.getElementById('notification');
            const notificationText = document.getElementById('notificationText');
            
            notificationText.textContent = message;
            
            if (type === 'success') {
                notification.style.background = '#10b981';
            } else if (type === 'error') {
                notification.style.background = '#ef4444';
            }
            
            notification.classList.add('show');
            
            setTimeout(() => {
                notification.classList.remove('show');
            }, 3000);
        }

        // Image Upload Handling
        const imageInput = document.getElementById('imageInput');
        const imagePreview = document.getElementById('imagePreview');
        const dropArea = document.getElementById('imageDropArea');

        imageInput.addEventListener('change', handleImageSelect);

        function handleImageSelect(e) {
            const files = e.target.files;
            displayImages(files);
        }

        function displayImages(files) {
            imagePreview.innerHTML = '';
            
            Array.from(files).forEach(file => {
                if (file.type.startsWith('image/')) {
                    const reader = new FileReader();
                    reader.onload = function(e) {
                        const div = document.createElement('div');
                        div.className = 'relative';
                        div.innerHTML = `
                            <img src="${e.target.result}" class="product-image-preview border rounded-lg">
                            <button type="button" class="absolute -top-2 -right-2 bg-red-500 text-white rounded-full w-6 h-6 flex items-center justify-center text-xs hover:bg-red-600" onclick="this.parentElement.remove()">
                                <i class="fas fa-times"></i>
                            </button>
                        `;
                        imagePreview.appendChild(div);
                    };
                    reader.readAsDataURL(file);
                }
            });
        }

        // Drag and Drop
        dropArea.addEventListener('dragover', function(e) {
            e.preventDefault();
            this.classList.add('dragover');
        });

        dropArea.addEventListener('dragleave', function(e) {
            e.preventDefault();
            this.classList.remove('dragover');
        });

        dropArea.addEventListener('drop', function(e) {
            e.preventDefault();
            this.classList.remove('dragover');
            
            const files = e.dataTransfer.files;
            displayImages(files);
        });

        // Form Submission
        document.querySelector('#addProductModal form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Simulate form submission
            setTimeout(() => {
                closeModal('addProductModal');
                showNotification('محصول با موفقیت اضافه شد!');
                
                // Reset form
                this.reset();
                imagePreview.innerHTML = '';
            }, 1000);
        });

        // Sales Chart
        const ctx = document.getElementById('salesChart').getContext('2d');
        new Chart(ctx, {
            type: 'line',
            data: {
                labels: ['شنبه', 'یکشنبه', 'دوشنبه', 'سه‌شنبه', 'چهارشنبه', 'پنج‌شنبه', 'جمعه'],
                datasets: [{
                    label: 'فروش (افغانی)',
                    data: [12000, 19000, 15000, 25000, 22000, 30000, 28000],
                    borderColor: '#3b82f6',
                    backgroundColor: 'rgba(59, 130, 246, 0.1)',
                    tension: 0.4,
                    fill: true
                }]
            },
            options: {
                responsive: true,
                plugins: {
                    legend: {
                        display: false
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        ticks: {
                            callback: function(value) {
                                return value.toLocaleString() + ' ؋';
                            }
                        }
                    }
                }
            }
        });

        // Analytics Charts
        let salesTrendChart, categoryChart, revenueOrdersChart, geoChart;

        // Sales Trend Chart
        const salesTrendCtx = document.getElementById('salesTrendChart').getContext('2d');
        salesTrendChart = new Chart(salesTrendCtx, {
            type: 'line',
            data: {
                labels: ['هفته 1', 'هفته 2', 'هفته 3', 'هفته 4'],
                datasets: [{
                    label: 'فروش',
                    data: [120000, 135000, 148000, 162000],
                    borderColor: '#3b82f6',
                    backgroundColor: 'rgba(59, 130, 246, 0.1)',
                    tension: 0.4,
                    fill: true
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: false
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        ticks: {
                            callback: function(value) {
                                return value.toLocaleString() + ' ؋';
                            }
                        }
                    }
                }
            }
        });

        // Category Performance Chart
        const categoryCtx = document.getElementById('categoryChart').getContext('2d');
        categoryChart = new Chart(categoryCtx, {
            type: 'doughnut',
            data: {
                labels: ['الکترونیک', 'لباس', 'کتاب', 'لوازم خانه', 'ورزشی'],
                datasets: [{
                    data: [45, 25, 15, 10, 5],
                    backgroundColor: [
                        '#3b82f6',
                        '#10b981',
                        '#f59e0b',
                        '#ef4444',
                        '#8b5cf6'
                    ],
                    borderWidth: 0
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        position: 'bottom',
                        labels: {
                            padding: 20,
                            usePointStyle: true
                        }
                    }
                }
            }
        });

        // Revenue and Orders Chart
        const revenueOrdersCtx = document.getElementById('revenueOrdersChart').getContext('2d');
        revenueOrdersChart = new Chart(revenueOrdersCtx, {
            type: 'bar',
            data: {
                labels: ['فروردین', 'اردیبهشت', 'خرداد', 'تیر', 'مرداد', 'شهریور', 'مهر', 'آبان'],
                datasets: [{
                    label: 'درآمد (هزار افغانی)',
                    data: [320, 380, 420, 390, 450, 480, 520, 485],
                    backgroundColor: 'rgba(59, 130, 246, 0.8)',
                    borderColor: '#3b82f6',
                    borderWidth: 1,
                    yAxisID: 'y'
                }, {
                    label: 'تعداد سفارشات',
                    data: [85, 92, 108, 95, 115, 125, 142, 156],
                    backgroundColor: 'rgba(16, 185, 129, 0.8)',
                    borderColor: '#10b981',
                    borderWidth: 1,
                    yAxisID: 'y1'
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                interaction: {
                    mode: 'index',
                    intersect: false,
                },
                scales: {
                    y: {
                        type: 'linear',
                        display: true,
                        position: 'left',
                        ticks: {
                            callback: function(value) {
                                return value + 'K ؋';
                            }
                        }
                    },
                    y1: {
                        type: 'linear',
                        display: true,
                        position: 'right',
                        grid: {
                            drawOnChartArea: false,
                        },
                        ticks: {
                            callback: function(value) {
                                return value + ' سفارش';
                            }
                        }
                    }
                },
                plugins: {
                    legend: {
                        position: 'top',
                    }
                }
            }
        });

        // Geographic Chart
        const geoCtx = document.getElementById('geoChart').getContext('2d');
        geoChart = new Chart(geoCtx, {
            type: 'bar',
            data: {
                labels: ['کابل', 'هرات', 'مزار شریف', 'قندهار', 'جلال آباد'],
                datasets: [{
                    label: 'فروش (هزار افغانی)',
                    data: [185, 125, 95, 78, 52],
                    backgroundColor: [
                        '#3b82f6',
                        '#10b981',
                        '#f59e0b',
                        '#ef4444',
                        '#8b5cf6'
                    ],
                    borderRadius: 4
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        display: false
                    }
                },
                scales: {
                    y: {
                        beginAtZero: true,
                        ticks: {
                            callback: function(value) {
                                return value + 'K ؋';
                            }
                        }
                    }
                }
            }
        });

        // Chart Toggle Function
        function toggleChartType(chartId) {
            if (chartId === 'salesTrendChart') {
                const currentType = salesTrendChart.config.type;
                const newType = currentType === 'line' ? 'bar' : 'line';
                
                salesTrendChart.destroy();
                salesTrendChart = new Chart(salesTrendCtx, {
                    type: newType,
                    data: {
                        labels: ['هفته 1', 'هفته 2', 'هفته 3', 'هفته 4'],
                        datasets: [{
                            label: 'فروش',
                            data: [120000, 135000, 148000, 162000],
                            borderColor: '#3b82f6',
                            backgroundColor: newType === 'line' ? 'rgba(59, 130, 246, 0.1)' : '#3b82f6',
                            tension: newType === 'line' ? 0.4 : 0,
                            fill: newType === 'line'
                        }]
                    },
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        plugins: {
                            legend: {
                                display: false
                            }
                        },
                        scales: {
                            y: {
                                beginAtZero: true,
                                ticks: {
                                    callback: function(value) {
                                        return value.toLocaleString() + ' ؋';
                                    }
                                }
                            }
                        }
                    }
                });
            }
        }

        // Chart Data Toggle
        document.getElementById('showRevenue').addEventListener('change', function() {
            revenueOrdersChart.data.datasets[0].hidden = !this.checked;
            revenueOrdersChart.update();
        });

        document.getElementById('showOrders').addEventListener('change', function() {
            revenueOrdersChart.data.datasets[1].hidden = !this.checked;
            revenueOrdersChart.update();
        });

        // Time Period Change
        document.getElementById('timePeriod').addEventListener('change', function() {
            const period = this.value;
            // Update all charts based on selected period
            updateChartsData(period);
            showNotification(`داده‌ها برای ${period} روز گذشته به‌روزرسانی شد`);
        });

        function updateChartsData(period) {
            // Simulate data update based on time period
            let newData, newLabels;
            
            switch(period) {
                case '7':
                    newLabels = ['شنبه', 'یکشنبه', 'دوشنبه', 'سه‌شنبه', 'چهارشنبه', 'پنج‌شنبه', 'جمعه'];
                    newData = [12000, 19000, 15000, 25000, 22000, 30000, 28000];
                    break;
                case '30':
                    newLabels = ['هفته 1', 'هفته 2', 'هفته 3', 'هفته 4'];
                    newData = [120000, 135000, 148000, 162000];
                    break;
                case '90':
                    newLabels = ['ماه 1', 'ماه 2', 'ماه 3'];
                    newData = [450000, 520000, 485000];
                    break;
                case '365':
                    newLabels = ['Q1', 'Q2', 'Q3', 'Q4'];
                    newData = [1200000, 1450000, 1380000, 1520000];
                    break;
            }
            
            salesTrendChart.data.labels = newLabels;
            salesTrendChart.data.datasets[0].data = newData;
            salesTrendChart.update();
        }

        // Export Functions
        document.querySelectorAll('button').forEach(button => {
            if (button.textContent.includes('دانلود گزارش')) {
                button.addEventListener('click', function() {
                    // Simulate report download
                    showNotification('گزارش در حال دانلود است...');
                    setTimeout(() => {
                        showNotification('گزارش با موفقیت دانلود شد');
                    }, 2000);
                });
            }
            
            if (button.textContent.includes('خروجی Excel')) {
                button.addEventListener('click', function() {
                    // Simulate Excel export
                    showNotification('فایل Excel در حال آماده‌سازی است...');
                    setTimeout(() => {
                        showNotification('فایل Excel آماده دانلود است');
                    }, 2000);
                });
            }
        });

        // Order Status Updates
        document.querySelectorAll('button').forEach(button => {
            if (button.textContent.trim() === 'تایید') {
                button.addEventListener('click', function() {
                    showNotification('سفارش تایید شد');
                    // Update UI
                    const row = this.closest('tr');
                    const statusCell = row.querySelector('span');
                    statusCell.textContent = 'تایید شده';
                    statusCell.className = 'px-2 py-1 text-xs font-semibold rounded-full bg-green-100 text-green-800';
                });
            }
            
            if (button.textContent.trim() === 'رد') {
                button.addEventListener('click', function() {
                    if (confirm('آیا از رد این سفارش اطمینان دارید؟')) {
                        showNotification('سفارش رد شد', 'error');
                        // Update UI
                        const row = this.closest('tr');
                        const statusCell = row.querySelector('span');
                        statusCell.textContent = 'رد شده';
                        statusCell.className = 'px-2 py-1 text-xs font-semibold rounded-full bg-red-100 text-red-800';
                    }
                });
            }
        });

        // Product Actions
        document.querySelectorAll('button').forEach(button => {
            if (button.textContent.trim() === 'حذف') {
                button.addEventListener('click', function() {
                    if (confirm('آیا از حذف این محصول اطمینان دارید؟')) {
                        this.closest('tr').remove();
                        showNotification('محصول حذف شد');
                    }
                });
            }
        });

        // Responsive Sidebar
        window.addEventListener('resize', function() {
            const sidebar = document.getElementById('sidebar');
            const mainContent = document.getElementById('mainContent');
            
            if (window.innerWidth > 768) {
                sidebar.classList.remove('active');
                mainContent.classList.remove('expanded');
            }
        });

        // Search Functionality
        document.querySelectorAll('input[placeholder*="جستجو"]').forEach(input => {
            input.addEventListener('input', function() {
                const searchTerm = this.value.toLowerCase();
                // Implement search logic here
                console.log('Searching for:', searchTerm);
            });
        });

        // Auto-save draft functionality
        let autoSaveTimer;
        document.querySelectorAll('#addProductModal input, #addProductModal textarea, #addProductModal select').forEach(input => {
            input.addEventListener('input', function() {
                clearTimeout(autoSaveTimer);
                autoSaveTimer = setTimeout(() => {
                    // Save draft to localStorage
                    const formData = new FormData(document.querySelector('#addProductModal form'));
                    const draftData = {};
                    for (let [key, value] of formData.entries()) {
                        draftData[key] = value;
                    }
                    localStorage.setItem('productDraft', JSON.stringify(draftData));
                }, 2000);
            });
        });

        // Load draft on page load
        window.addEventListener('load', function() {
            const draft = localStorage.getItem('productDraft');
            if (draft) {
                const draftData = JSON.parse(draft);
                Object.keys(draftData).forEach(key => {
                    const input = document.querySelector(`#addProductModal [name="${key}"]`);
                    if (input) {
                        input.value = draftData[key];
                    }
                });
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'96304f97b6f9c8fc',t:'MTc1MzE1OTc2MS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
