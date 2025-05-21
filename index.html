<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodie Express - Your Delicious Meals Delivered</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <style>
        /* --- Root Variables (updated for food theme - DARK MODE) --- */
        :root {
            --primary-color: #FF5733; /* Orange-Red - Keep bright for accents */
            --secondary-color: #FFC300; /* Amber - Keep bright for accents */
            --accent-color: #DAF7A6; /* Light Green */
            --success-color: #28a745; /* Green */

            /* Dark Theme Colors */
            --text-dark: #E0E0E0; /* Light grey for main text */
            --text-light: #B0B0B0; /* Slightly darker light grey for secondary text */
            --bg-light: #1A1A1A; /* Very dark grey for general backgrounds */
            --bg-white: #2C2C2C; /* Darker grey for cards and content boxes */
            --border-color: #444444; /* Darker grey for borders */
            --star-color: #ffc107; /* Keep bright */
            --border-radius: 0.75rem;
            --border-radius-sm: 0.5rem;
            --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.4), 0 2px 4px -1px rgba(0, 0, 0, 0.2);
            --shadow-modal: 0 8px 32px 0 rgba(0, 0, 0, 0.6);
        }

        /* --- Food Delivery Base Styles --- */
        body {
            font-family: 'Inter', sans-serif;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            background-color: var(--bg-light); /* Apply dark background */
            color: var(--text-dark); /* Apply light text color */
        }
        .gradient-text {
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        body::before {
            content: ""; position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background-image: radial-gradient(circle, rgba(255, 255, 255, 0.05) 1px, transparent 1px); /* Subtle light pattern */
            background-size: 20px 20px; opacity: 0.3; z-index: -1;
        }
        .app-card {
            background-color: var(--bg-white); /* Darker card background */
            border: 1px solid var(--border-color); /* Darker border */
            box-shadow: var(--shadow-md); /* Adjusted shadow */
            transition: transform 0.3s ease-out, box-shadow 0.3s ease-out;
        }
        .app-card:hover {
            transform: translateY(-6px) scale(1.02);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3), 0 6px 6px rgba(0, 0, 0, 0.2); /* Darker hover shadow */
        }

        /* --- Message Box --- */
        #message-box {
            position: fixed; top: -100px; left: 50%;
            transform: translateX(-50%);
            z-index: 1050;
            transition: top 0.5s ease-out, opacity 0.5s ease-out;
            opacity: 0; min-width: 250px;
            color: white; /* Ensure text is white on colored background */
        }
        #message-box.show { top: 20px; opacity: 1; }
        /* Specific message box colors will be handled by JavaScript adding classes like bg-green-500 */

        /* --- Advanced Button Styles (Product Cards) --- */
        .action-button {
             position: relative; display: inline-flex; align-items: center; justify-content: center;
             gap: 0.5rem; padding: 0.6rem 1.2rem; border-radius: 9999px;
             font-size: 0.875rem; font-weight: 600; color: white;
             background-color: #555555; /* Fallback for dark theme */
             border: none; cursor: pointer; overflow: hidden;
             transition: all 0.3s ease; box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3); /* Darker button shadow */
        }
        .action-button i { transition: transform 0.3s ease; font-size: 0.8rem; }
        .action-button:hover {
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.45); /* Darker hover shadow */
            transform: translateY(-2px);
        }
        .action-button:active { transform: translateY(0px) scale(0.98); box-shadow: 0 1px 3px rgba(0, 0, 0, 0.2); }

        .add-to-cart-button { background: linear-gradient(to right, #4B5563, #374151); } /* Darker gray gradient */
        .add-to-cart-button:hover { background: linear-gradient(to right, #374151, #1F2937); } /* Even darker on hover */
        .order-now-button.bg-red-gradient { background: linear-gradient(to right, #EF4444, #DC2626); } /* Keep bright */
        .order-now-button.bg-red-gradient:hover { background: linear-gradient(to right, #DC2626, #B91C1C); } /* Keep bright */
        .order-now-button.bg-green-gradient { background: linear-gradient(to right, #22C55E, #16A34A); } /* Keep bright */
        .order-now-button.bg-green-gradient:hover { background: linear-gradient(to right, #16A34A, #15803D); } /* Keep bright */
        .order-now-button.bg-yellow-gradient { background: linear-gradient(to right, #FACC15, #EAB308); } /* Keep bright */
        .order-now-button.bg-yellow-gradient:hover { background: linear-gradient(to right, #EAB308, #D99700); } /* Keep bright */
        .order-now-button.bg-orange-gradient { background: linear-gradient(to right, #FB923C, #F97316); } /* Keep bright */
        .order-now-button.bg-orange-gradient:hover { background: linear-gradient(to right, #F97316, #EA580C); } /* Keep bright */


        /* --- Modal & Cart CSS --- */
        .modal {
            display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            z-index: 1001; justify-content: center; align-items: center;
            opacity: 0; transition: opacity 0.3s ease;
            backdrop-filter: blur(5px); -webkit-backdrop-filter: blur(5px);
        }
        .modal.open { display: flex; opacity: 1; }
        .modal-content {
            background-color: rgba(40, 40, 40, 0.95); /* Darker semi-transparent background */
            backdrop-filter: blur(10px); -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.15); /* Lighter, subtle border */
            padding: 1.8rem; border-radius: var(--border-radius);
            width: 90%; max-height: 85vh; overflow-y: auto;
            box-shadow: var(--shadow-modal); /* Darker modal shadow */
            transform: scale(0.95); transition: transform 0.3s ease, opacity 0.3s ease;
            font-family: 'Poppins', sans-serif;
            color: var(--text-dark); /* Ensure modal text is light */
        }
        .modal.open .modal-content { transform: scale(1); }
        .modal-header {
            display: flex; justify-content: space-between; align-items: center;
            margin-bottom: 1.2rem; padding-bottom: 0.8rem;
            border-bottom: 1px solid rgba(255,255,255,0.1); /* Lighter border */
        }
        .modal-header h2 { font-size: 1.6rem; color: var(--text-dark); font-weight: 600; }
        .close-modal-btn {
            background: none; border: none; font-size: 1.8rem;
            cursor: pointer; color: var(--text-light); /* Lighter color for close btn */
            transition: color 0.2s ease;
        }
        .close-modal-btn:hover { color: var(--primary-color); } /* Keep primary color on hover */
        .cart-modal-content { max-width: 600px; }
        .cart-items-list { margin-bottom: 1.5rem; max-height: 45vh; overflow-y: auto; padding-right: 0.5rem; }
        .cart-item { display: flex; align-items: flex-start; padding: 1rem 0; border-bottom: 1px solid var(--border-color); gap: 1rem; }
        .cart-item:last-child { border-bottom: none; }
        .cart-item img { width: 70px; height: 70px; object-fit: cover; border-radius: var(--border-radius-sm); flex-shrink: 0; border: 1px solid var(--border-color); }
        .cart-item-details { flex-grow: 1; display: flex; flex-direction: column; }
        .cart-item-details h4 { font-size: 0.95rem; font-weight: 600; margin-bottom: 0.25rem; color: var(--text-dark); line-height: 1.3; }
        .cart-item-unit-price { font-size: 0.8rem; color: var(--text-light); margin-bottom: 0.4rem; }
        .cart-item-controls { display: flex; align-items: center; justify-content: space-between; margin-top: 0.3rem; }
        .cart-item-quantity-wrapper { display: flex; align-items: center; }
        .cart-item-quantity-wrapper label { font-size: 0.8rem; margin-right: 0.4rem; color: var(--text-light); }
        .cart-item-quantity input {
            width: 45px; text-align: center; padding: 0.3rem;
            border: 1px solid var(--border-color); border-radius: var(--border-radius-sm);
            font-size: 0.9rem; margin: 0 0.2rem;
            background-color: #383838; /* Darker input background */
            color: var(--text-dark); /* Light text in input */
        }
        .cart-item-subtotal { font-weight: 600; font-size: 0.95rem; color: var(--primary-color); text-align: right; }
        .remove-item-btn { background: none; border: none; color: var(--primary-color); cursor: pointer; font-size: 1.1rem; padding: 0.2rem; line-height: 1; margin-left: 0.8rem; transition: color 0.2s ease; }
        .remove-item-btn:hover { color: #d32f2f; }
        .cart-summary { margin-top: 1.5rem; padding-top: 1.5rem; border-top: 1px solid var(--border-color); }
        .cart-summary p { font-size: 1.1rem; font-weight: 600; margin-bottom: 1rem; color: var(--text-dark); display: flex; justify-content: space-between; }
        .cart-summary p span:first-child { color: var(--text-light); font-weight: 500;}
        .cart-summary .btn { display: block; width: 100%; text-align: center; padding: 0.75rem 1.5rem; border-radius: var(--border-radius-sm); font-weight: 600; text-decoration: none; transition: all 0.25s cubic-bezier(0.68, -0.55, 0.265, 1.55); cursor: pointer; border: none; font-size: 0.95rem; }
        .cart-summary .btn-primary { background-image: linear-gradient(to right, var(--primary-color) 0%, var(--secondary-color) 100%); color: var(--bg-white); }
        .cart-summary .btn-primary:hover { background-image: linear-gradient(to right, var(--secondary-color) 0%, var(--primary-color) 100%); }
        .empty-cart-message { text-align: center; padding: 2.5rem 1rem; color: var(--text-light); font-size: 1.05rem; }
        .empty-cart-message svg { width: 45px; height: 45px; margin: 0 auto 0.8rem auto; display: block; color: var(--border-color); }
        .order-modal-content { max-width: 500px; }
        .order-form-container .form-group { margin-bottom: 1rem; }
        .order-form-container label { display: block; font-size: 0.85rem; font-weight: 500; margin-bottom: 0.3rem; color: var(--text-dark); }
        .order-form-container input[type="text"], .order-form-container input[type="tel"], .order-form-container textarea, .order-form-container select {
            width: 100%; padding: 0.6rem 0.7rem;
            border: 1px solid var(--border-color); border-radius: var(--border-radius-sm);
            font-size: 0.9rem; font-family: 'Poppins', sans-serif;
            background-color: #383838; /* Darker input background */
            color: var(--text-dark); /* Light text in input */
        }
        .order-form-container input:focus, .order-form-container textarea:focus, .order-form-container select:focus { outline: none; border-color: var(--primary-color); box-shadow: 0 0 0 2px rgba(255, 87, 51, 0.2); }
        .order-summary-details {
            background-color: rgba(50, 30, 20, 0.5); /* Darker orange hue for summary */
            padding: 1rem; border-radius: var(--border-radius-sm); margin-bottom: 1rem;
            border: 1px dashed var(--primary-color);
            color: var(--text-dark); /* Ensure text is light */
        }
        .order-summary-details p { font-size: 0.9rem; color: var(--text-dark); margin-bottom: 0.4rem; }
        .order-summary-details p strong { font-weight: 600; }
        .delivery-instruction {
            font-size: 0.8rem; color: var(--text-light); margin-top: 1rem; margin-bottom: 1.2rem;
            text-align: center; padding: 0.5rem;
            background-color: rgba(30, 25, 20, 0.4); /* Darker yellow hue */
            border-radius: var(--border-radius-sm);
        }
        #orderSubmissionMessage { font-size: 0.85rem; text-align: center; display: flex; align-items: center; justify-content:center; gap: 0.5rem; font-weight: 500; color: var(--text-dark); } /* Ensure text color */
        .order-form-container .btn { display: block; width: 100%; text-align: center; padding: 0.75rem 1.5rem; border-radius: var(--border-radius-sm); font-weight: 600; text-decoration: none; transition: all 0.25s cubic-bezier(0.68, -0.55, 0.265, 1.55); cursor: pointer; border: none; font-size: 0.95rem; }
        .order-form-container .btn-success { background-color: var(--success-color); color: var(--bg-white); }
        .order-form-container .btn-success:hover { background-color: #218838; }
        .spinner { width: 18px; height: 18px; border: 3px solid rgba(255,255,255,0.1); border-left-color: var(--primary-color); border-radius: 50%; display: inline-block; animation: spin 1s linear infinite; margin-right: 8px; }
        @keyframes spin { to { transform: rotate(360deg); } }
        .cart-count-badge { position: absolute; top: -8px; right: -10px; min-width: 20px; height: 20px; font-size: 12px; line-height: 20px; border-radius: 50%; text-align: center; }

        /* --- Product Slider Styles --- */
        .product-slider-container { position: relative; margin-bottom: 3rem; }
        .product-slider-wrapper { display: flex; overflow-x: auto; scroll-behavior: smooth; -webkit-overflow-scrolling: touch; padding-bottom: 1rem; gap: 1.5rem; }
        .product-slider-wrapper::-webkit-scrollbar { display: none; }
        .product-slider-wrapper { -ms-overflow-style: none; scrollbar-width: none; }
        .slider-product-card { flex: 0 0 auto; width: 280px; }
        .slider-nav-button {
            position: absolute; top: 50%; transform: translateY(-50%);
            background-color: rgba(40, 40, 40, 0.9); /* Darker background for nav buttons */
            backdrop-filter: blur(3px); -webkit-backdrop-filter: blur(3px);
            color: var(--text-dark); /* Lighter text for nav buttons */
            border: 1px solid var(--border-color); /* Darker border */
            border-radius: 50%; width: 44px; height: 44px;
            display: flex; align-items: center; justify-content: center;
            cursor: pointer; z-index: 10; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.4), 0 2px 4px -1px rgba(0, 0, 0, 0.2); /* Darker shadow */
            transition: all 0.2s ease;
        }
        .slider-nav-button i { font-size: 1.1rem; }
        .slider-nav-button:hover {
            background-color: #333333; /* Slightly lighter dark on hover */
            color: var(--primary-color);
            transform: translateY(-50%) scale(1.08);
        }
        .slider-nav-button.prev { left: -20px; }
        .slider-nav-button.next { right: -20px; }
        @media (max-width: 640px) {
            .slider-nav-button.prev { left: 2px; }
            .slider-nav-button.next { right: 2px; }
            .slider-product-card { width: 250px; }
            .slider-nav-button i { font-size: 0.9rem; }
        }

        /* --- WhatsApp Floating Button --- */
        #whatsapp-float-button {
            position: fixed;
            bottom: 25px;
            right: 25px;
            background-color: #25D366; /* WhatsApp Green */
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px; /* Icon size */
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.4); /* Darker shadow */
            z-index: 999; /* Below modals, above most content */
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        #whatsapp-float-button:hover {
            transform: scale(1.1);
            box-shadow: 0 6px 16px rgba(0, 0, 0, 0.5); /* Darker hover shadow */
        }

        /* NEW: Stylish Hero Banner Slider Styles */
        .hero-banner-new {
            position: relative;
            max-width: 1000px; /* Limit banner width */
            height: 400px; /* Adjusted height */
            overflow: hidden;
            border-radius: var(--border-radius);
            box-shadow: var(--shadow-md);
            margin-top: 2rem;
            border: 1px solid var(--border-color);
        }

        .hero-banner-new .new-slider-wrapper {
            display: flex;
            height: 100%;
            transition: transform 0.7s ease-in-out; /* Smooth slide transition */
        }

        .hero-banner-new .new-slide-item {
            flex-shrink: 0;
            width: 100%;
            height: 100%;
            position: relative;
            display: flex;
            align-items: center;
            /* justify-content is handled by JS based on .align class */
            color: white; /* Text color for overlay */
            background-size: cover;
            background-position: center;
        }

        /* Overlay to make text readable */
        .hero-banner-new .new-slide-item::before {
            content: "";
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: rgba(0, 0, 0, 0.4); /* Dark overlay */
            z-index: 1;
        }

        .hero-banner-new .slide-content {
            position: relative;
            z-index: 2;
            padding: 2rem;
            max-width: 70%; /* Limit content width */
            /* text-align is handled by .align-class */
            text-shadow: 0 2px 8px rgba(0, 0, 0, 0.7); /* Text shadow for readability */
        }

        /* Specific alignment classes for slide content */
        .hero-banner-new .slide-content.align-left { text-align: left; /* margin-right: auto; Removed for general centering */ padding-left: 4rem;}
        .hero-banner-new .slide-content.align-right { text-align: right; /* margin-left: auto; Removed for general centering */ padding-right: 4rem;}
        .hero-banner-new .slide-content.align-center { text-align: center; }


        .hero-banner-new .slide-content h1 {
            font-size: 2.5rem;
            font-weight: 700;
            margin-bottom: 0.75rem;
            line-height: 1.2;
            color: #ffffff; /* Explicitly white */
        }
        .hero-banner-new .slide-content p {
            font-size: 1.1rem;
            font-weight: 400;
            margin-bottom: 1.5rem;
            line-height: 1.5;
            color: #e0e0e0; /* Slightly off-white for description */
        }
        .hero-banner-new .slide-content .btn-banner {
            display: inline-block;
            padding: 0.8rem 2rem;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            color: white;
            border-radius: 9999px;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .hero-banner-new .slide-content .btn-banner:hover {
            transform: translateY(-3px) scale(1.02);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4);
            background: linear-gradient(to right, var(--secondary-color), var(--primary-color));
        }

        .new-slider-dots-container {
            position: absolute;
            bottom: 1rem;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 0.75rem;
            z-index: 10;
        }

        .new-slider-dot {
            width: 10px;
            height: 10px;
            background-color: rgba(255, 255, 255, 0.5); /* Light grey semi-transparent for dark theme */
            border-radius: 50%;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
            border: 1px solid rgba(0,0,0,0.1);
        }

        .new-slider-dot.active {
            background-color: var(--primary-color); /* Primary color for active dot */
            transform: scale(1.2);
            border: 1px solid var(--primary-color);
        }

        /* Tailwind overrides for dark theme */
        .bg-gray-50 { background-color: var(--bg-light); }
        .text-gray-800 { color: var(--text-dark); }
        .bg-white\/90 { background-color: rgba(30, 30, 30, 0.9); } /* Darker header bg */
        .border-gray-200 { border-color: var(--border-color); }
        .text-gray-600 { color: var(--text-light); }
        .hover\:text-red-600:hover { color: var(--primary-color); } /* Keep red for hover */
        .text-gray-700 { color: var(--text-dark); }
        .bg-gray-100 { background-color: #1F1F1F; } /* Darker footer bg */
        .text-gray-500 { color: var(--text-light); }
        .border-gray-100 { border-color: var(--border-color); }

        /* Responsive adjustment for smaller screens */
        @media (max-width: 768px) {
            .hero-banner-new {
                height: 300px;
            }
            .hero-banner-new .slide-content h1 {
                font-size: 1.8rem;
            }
            .hero-banner-new .slide-content p {
                font-size: 0.9rem;
            }
            .hero-banner-new .slide-content {
                max-width: 85%;
                padding: 1rem;
            }
            /* Removing specific paddings for align-left/right if all are centered */
            .hero-banner-new .slide-content.align-left { padding-left: 1rem; }
            .hero-banner-new .slide-content.align-right { padding-right: 1rem; }
        }
        @media (max-width: 480px) {
            .hero-banner-new {
                height: 240px;
            }
            .hero-banner-new .slide-content h1 {
                font-size: 1.5rem;
                margin-bottom: 0.5rem;
            }
            .hero-banner-new .slide-content p {
                font-size: 0.8rem;
                margin-bottom: 1rem;
            }
            .hero-banner-new .slide-content .btn-banner {
                padding: 0.6rem 1.5rem;
                font-size: 0.85rem;
            }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <header class="bg-white/90 backdrop-blur-sm shadow-sm sticky top-0 z-50 border-b border-gray-200">
        <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-3 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold gradient-text">Foodie Express</a>
            <div class="flex items-center">
                <div class="hidden sm:flex items-center space-x-3 lg:space-x-4">
                     <a href="#" class="text-gray-600 hover:text-red-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Popular</a>
                     <a href="#" class="text-gray-600 hover:text-red-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Cuisines</a>
                     <a href="#" class="text-gray-600 hover:text-red-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Restaurants</a>
                     <a href="#" class="bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded-full text-sm font-medium transition-colors shadow-sm">My Orders</a>
                </div>
                <button id="cartIconWrapper" class="relative text-gray-600 hover:text-red-600 p-2 rounded-full transition-colors ml-2 sm:ml-4">
                     <i class="fas fa-shopping-cart fa-lg"></i>
                     <span id="cartItemCount" class="cart-count-badge bg-red-500 text-white font-bold">0</span>
                 </button>
                <div class="sm:hidden ml-1">
                    <button class="text-gray-600 hover:text-red-600 p-2 rounded-md">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" /></svg>
                    </button>
                </div>
            </div>
        </nav>
    </header>

    <!-- NEW: Stylish Auto Image Slider Banner Section -->
    <section class="hero-banner-new container mx-auto px-4 sm:px-6 lg:px-8 py-8">
        <div class="new-slider-wrapper">
            <!-- Slides will be dynamically loaded here by JavaScript -->
        </div>
        <div class="new-slider-dots-container">
            <!-- Dots will be dynamically loaded here by JavaScript -->
        </div>
    </section>

    <section class="container mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <h2 class="text-2xl font-semibold text-gray-700 mb-6">Popular Dishes & Restaurants</h2>
        <div class="product-slider-container">
            <div class="product-slider-wrapper" id="productSliderWrapper">
                </div>
            <button class="slider-nav-button prev" id="sliderPrevBtn"><i class="fas fa-chevron-left"></i></button>
            <button class="slider-nav-button next" id="sliderNextBtn"><i class="fas fa-chevron-right"></i></button>
        </div>
    </section>

    <main class="container mx-auto px-4 sm:px-6 lg:px-8 pb-12">
        <h2 class="text-3xl font-semibold text-gray-700 mb-8 text-center">Explore Delicious Meals</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8" id="allAppsGrid">
            </div>
    </main>

    <footer class="bg-gray-100 border-t border-gray-200 mt-16">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 py-8 text-center text-gray-500">
            <p class="text-sm">© <span id="currentYear"></span> Foodie Express. All rights reserved.</p>
             <div class="flex justify-center space-x-4 mt-4">
                <a href="#" class="hover:text-red-600 transition-colors">Privacy Policy</a>
                <a href="#" class="hover:text-red-600 transition-colors">Terms of Service</a>
                <a href="#" class="hover:text-red-600 transition-colors">Contact Us</a>
            </div>
        </div>
    </footer>

    <a href="https://wa.me/9710544920769" id="whatsapp-float-button"
       target="_blank"
       aria-label="Contact us on WhatsApp">
        <i class="fab fa-whatsapp"></i>
    </a>

    <div id="message-box" class="bg-green-500 text-white px-6 py-3 rounded-lg shadow-xl text-center font-medium">
        <span id="message-text">Message goes here</span>
    </div>

    <div class="modal cart-modal" id="cartModal">
        <div class="modal-content cart-modal-content">
            <div class="modal-header"><h2>Your Cart</h2><button class="close-modal-btn" id="closeCartBtn">×</button></div>
            <div class="cart-items-list" id="cartItemsList"></div>
            <div class="cart-summary">
                <p><span>Subtotal:</span> <span id="cartSubtotal">PKR 0</span></p>
                <p><span>Delivery Fee:</span> <span id="deliveryFee">PKR 250</span></p>
                <p class="text-2xl font-bold text-red-600"><span>Total:</span> <span id="cartTotal">PKR 0</span></p>
                <button class="btn btn-primary" id="proceedToCheckoutBtn" style="width:100%;">Proceed to Order</button>
            </div>
        </div>
    </div>

    <div class="modal order-modal" id="orderConfirmationModal">
        <div class="modal-content order-modal-content">
            <div class="modal-header"><h2>Confirm Your Order</h2><button class="close-modal-btn" id="closeOrderModalBtn">×</button></div>
            <div class="order-form-container">
                <div class="order-summary-details">
                    <p><strong>Order Summary:</strong></p>
                    <div id="orderModalSummary"></div>
                    <hr style="margin: 0.5rem 0; border-color: rgba(255,255,255,0.1);">
                    <p><strong>Total Amount:</strong> PKR <span id="orderModalTotalAmount">0</span></p>
                </div>
                <hr style="margin: 1rem 0; border-color: var(--border-color);">
                <p style="font-size: 0.9rem; margin-bottom: 1rem; color: var(--text-dark);">Please provide your delivery details:</p>
                <form id="orderForm" action="https://formspree.io/f/mrbqapyp" method="POST">
                    <div class="form-group"><label for="customerName">Your Full Name:</label><input type="text" id="customerName" name="customerName" required></div>
                    <div class="form-group"><label for="deliveryAddress">Delivery Address:</label><textarea id="deliveryAddress" name="deliveryAddress" rows="3" required placeholder="House No., Street Name, Area, City"></textarea></div>
                    <div class="form-group"><label for="customerPhone">Your Phone Number:</label><input type="tel" id="customerPhone" name="customerPhone" required placeholder="e.g., 03xxxxxxxxx"></div>
                    <div class="form-group">
                        <label for="paymentMethod">Payment Method:</label>
                        <select id="paymentMethod" name="paymentMethod" required>
                            <option value="Cash on Delivery">Cash on Delivery</option>
                            <option value="Online Payment (Coming Soon)" disabled>Online Payment (Coming Soon)</option>
                        </select>
                    </div>
                    <input type="hidden" name="cartDetails" id="formCartDetails">
                    <input type="hidden" name="totalOrderAmount" id="formTotalOrderAmount">
                    <p class="delivery-instruction">By clicking "Place Order", you confirm your order and agree to our terms.</p>
                    <button type="submit" class="btn btn-success" style="width:100%;">Place Order</button>
                </form>
                <div id="orderSubmissionMessage" class="mt-2" style="display:none;"></div>
            </div>
        </div>
    </div>

    <script>
        // Sample food product data
        const storeProducts = [
            { id: "dish_001", name: "Spicy Chicken Burger", restaurant: "Grill & Chill", price: 850.00, priceDisplay: "PKR 850", description: "Juicy grilled chicken patty, spicy sauce, fresh veggies, toasted bun. A fiery delight!", imageUrl: "https://images.unsplash.com/photo-1561043135-08146747b0e1?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D", gradientClass: "bg-red-gradient" },
            { id: "dish_002", name: "Margherita Pizza", restaurant: "Pizza Palace", price: 1400.00, priceDisplay: "PKR 1400", description: "Classic Italian pizza with fresh mozzarella, basil, and San Marzano tomato sauce.", imageUrl: "https://images.unsplash.com/photo-1593560704563-f176a2eb61db?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D", gradientClass: "bg-green-gradient" },
            { id: "dish_003", name: "Beef Biryani (Large)", restaurant: "Desi Dhaba", price: 1200.00, priceDisplay: "PKR 1200", description: "Aromatic basmati rice cooked with tender beef chunks and traditional spices.", imageUrl: "https://images.unsplash.com/photo-1626804646549-219e248b9415?q=80&w=2574&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D", gradientClass: "bg-yellow-gradient" },
            { id: "dish_004", name: "Chocolate Lava Cake", restaurant: "Sweet Spot", price: 650.00, priceDisplay: "PKR 650", description: "Warm chocolate cake with a molten chocolate center, served with vanilla ice cream.", imageUrl: "https://images.unsplash.com/photo-1590740925203-9111c13d9426?q=80&w=2574&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D", gradientClass: "bg-orange-gradient" },
            { id: "dish_005", name: "Creamy Pasta Alfredo", restaurant: "Pasta Perfection", price: 950.00, priceDisplay: "PKR 950", description: "Fettuccine pasta tossed in a rich, creamy Alfredo sauce with parmesan cheese.", imageUrl: "https://images.unsplash.com/photo-1612803896173-9a7442431713?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D", gradientClass: "bg-red-gradient" },
            { id: "dish_006", name: "Veggie Supreme Pizza", restaurant: "Pizza Palace", price: 1550.00, priceDisplay: "PKR 1550", description: "Loaded with fresh bell peppers, onions, olives, mushrooms, and mozzarella.", imageUrl: "https://images.unsplash.com/photo-1613564993883-8a3583ae005c?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D", gradientClass: "bg-green-gradient" }
        ];

        // NEW: Banner images with content for the stylish slider
        const newBannerData = [
            {
                src: 'https://images.unsplash.com/photo-1512621776951-a579eddc69d4?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
                title: 'Fresh & Delicious Meals',
                description: 'Experience gourmet food delivered right to your doorstep, fresh and fast!',
                buttonText: 'Order Now',
                buttonLink: '#allAppsGrid',
                align: 'center'
            },
            {
                src: 'https://images.unsplash.com/photo-1546069901-ba9599a7e63c?q=80&w=2680&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
                title: 'Variety of Cuisines',
                description: 'Explore a world of flavors from Italian to Pakistani and everything in between.',
                buttonText: 'Browse Cuisines',
                buttonLink: '#',
                align: 'center'
            },
            {
                src: 'https://images.unsplash.com/photo-1563227814-fb6a88e999c0?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
                title: 'Fast & Reliable Delivery',
                description: 'Get your favorites in minutes. Our riders are always on the go!',
                buttonText: 'Check Delivery Areas',
                buttonLink: '#',
                align: 'center'
            },
            {
                src: 'https://images.unsplash.com/photo-1563729780521-e0c1f28b4956?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
                title: 'Exclusive Daily Deals!',
                description: 'Don\'t miss out on our limited-time offers and discounts. Order now and save!',
                buttonText: 'See Deals',
                buttonLink: '#',
                align: 'center'
            }
        ];


        document.addEventListener('DOMContentLoaded', () => {
            // DOM Elements (updated names)
            const messageBox = document.getElementById('message-box');
            const messageText = document.getElementById('message-text');
            const cartIconWrapper = document.getElementById('cartIconWrapper');
            const cartModal = document.getElementById('cartModal');
            const closeCartBtn = document.getElementById('closeCartBtn');
            const cartItemsList = document.getElementById('cartItemsList');
            const cartSubtotalEl = document.getElementById('cartSubtotal');
            const deliveryFeeEl = document.getElementById('deliveryFee');
            const cartTotalEl = document.getElementById('cartTotal');
            const cartItemCountEl = document.getElementById('cartItemCount');
            const proceedToCheckoutBtn = document.getElementById('proceedToCheckoutBtn');
            const orderConfirmationModal = document.getElementById('orderConfirmationModal');
            const closeOrderModalBtn = document.getElementById('closeOrderModalBtn');
            const orderForm = document.getElementById('orderForm');
            const orderModalTotalAmountEl = document.getElementById('orderModalTotalAmount');
            const orderModalSummaryEl = document.getElementById('orderModalSummary');
            const formCartDetailsInput = document.getElementById('formCartDetails');
            const formTotalOrderAmountInput = document.getElementById('formTotalOrderAmount');
            const orderSubmissionMessageEl = document.getElementById('orderSubmissionMessage');
            const productSliderWrapper = document.getElementById('productSliderWrapper');
            const allAppsGrid = document.getElementById('allAppsGrid');
            const sliderPrevBtn = document.getElementById('sliderPrevBtn');
            const sliderNextBtn = document.getElementById('sliderNextBtn');

            // NEW: Stylish Banner slider elements and variables
            const heroBannerNew = document.querySelector('.hero-banner-new');
            const newSliderWrapper = document.querySelector('.hero-banner-new .new-slider-wrapper');
            const newSliderDotsContainer = document.querySelector('.hero-banner-new .new-slider-dots-container');
            let currentNewBannerSlide = 0;
            let newBannerSlideInterval;
            const newBannerSlideDuration = 3000; // 3 seconds for auto-slide

            let store2MessageTimeout;
            let cart = JSON.parse(localStorage.getItem('foodieExpressCart')) || [];
            const CURRENCY_SYMBOL = 'PKR ';
            const DELIVERY_FEE = 250;

            const showAppNotification = (message, isError = false, isOrderNow = false) => {
                if (!messageBox || !messageText) return;
                messageText.textContent = message;
                clearTimeout(store2MessageTimeout);
                messageBox.classList.remove('bg-green-500', 'bg-red-500', 'bg-blue-500');
                if (isError) messageBox.classList.add('bg-red-500');
                else if (isOrderNow) messageBox.classList.add('bg-blue-500');
                else messageBox.classList.add('bg-green-500');
                messageBox.classList.add('show');
                store2MessageTimeout = setTimeout(() => messageBox.classList.remove('show'), isOrderNow ? 4000 : 3000);
            };

            const saveCartToLocalStorage = () => localStorage.setItem('foodieExpressCart', JSON.stringify(cart));

            const updateCartDisplay = () => {
                if (!cartItemsList || !cartSubtotalEl || !cartTotalEl || !cartItemCountEl || !proceedToCheckoutBtn || !deliveryFeeEl) return;
                cartItemsList.innerHTML = '';
                if (cart.length === 0) {
                    cartItemsList.innerHTML = `<div class="empty-cart-message"><svg viewBox="0 0 24 24" fill="currentColor"><path d="M11 9h2V6h3V4h-3V1h-2v3H8v2h3v3zm-4 9c-1.1 0-1.99.9-1.99 2S5.9 22 7 22s2-.9 2-2-.9-2-2-2zm10 0c-1.1 0-1.99.9-1.99 2S15.9 22 17 22s2-.9 2-2-.9-2-2-2zm-9.83-3.25l.03-.12.9-1.63h7.45c.75 0 1.41-.41 1.75-1.03l3.86-7.01L19.42 4H5.21l-.94-2H1v2h2l3.6 7.59-1.35 2.44C4.52 15.37 5.48 17 7 17h12v-2H7l1.1-2-1.42-2.56z"></path></svg>Your cart is currently empty. Start adding some delicious food!</div>`;
                    deliveryFeeEl.textContent = 'PKR 0';
                } else {
                    cart.forEach(item => {
                        const itemEl = document.createElement('div');
                        itemEl.className = 'cart-item';
                        itemEl.innerHTML = `
                            <img src="${item.imageUrl || 'https://placehold.co/80x80/CCCCCC/FFFFFF?text=Food&font=Poppins'}" alt="${item.name}" onerror="this.onerror=null;this.src='https://placehold.co/80x80/CCCCCC/FFFFFF?text=Food&font=Poppins';">
                            <div class="cart-item-details">
                                <h4>${item.name} (${item.restaurant})</h4>
                                <p class="cart-item-unit-price">${CURRENCY_SYMBOL}${parseFloat(item.price).toFixed(0)}</p>
                                <div class="cart-item-controls">
                                    <div class="cart-item-quantity-wrapper">
                                        <label for="qty-${item.id}">Qty:</label>
                                        <input type="number" class="cart-item-quantity" id="qty-${item.id}" value="${item.quantity}" min="1" data-id="${item.id}">
                                    </div>
                                    <p class="cart-item-subtotal">${CURRENCY_SYMBOL}${(parseFloat(item.price) * item.quantity).toFixed(0)}</p>
                                </div>
                            </div>
                            <button class="remove-item-btn" data-id="${item.id}" title="Remove item">×</button>`;
                        cartItemsList.appendChild(itemEl);
                    });
                     deliveryFeeEl.textContent = `${CURRENCY_SYMBOL}${DELIVERY_FEE.toFixed(0)}`;
                }
                const subtotal = cart.reduce((sum, item) => sum + (parseFloat(item.price) * item.quantity), 0);
                const total = cart.length > 0 ? subtotal + DELIVERY_FEE : 0;
                cartSubtotalEl.textContent = `${CURRENCY_SYMBOL}${subtotal.toFixed(0)}`;
                cartTotalEl.textContent = `${CURRENCY_SYMBOL}${total.toFixed(0)}`;
                const totalQuantity = cart.reduce((sum, item) => sum + item.quantity, 0);
                cartItemCountEl.textContent = totalQuantity;
                cartItemCountEl.classList.toggle('hidden', totalQuantity === 0);
                cartItemsList.querySelectorAll('.cart-item-quantity').forEach(input => input.addEventListener('change', (e) => updateCartQuantity(e.target.dataset.id, parseInt(e.target.value))));
                cartItemsList.querySelectorAll('.remove-item-btn').forEach(button => button.addEventListener('click', (e) => removeFromCart(e.target.dataset.id)));
                proceedToCheckoutBtn.disabled = cart.length === 0;
            };

            const addToCart = (productData) => {
                const existingCartItem = cart.find(item => item.id === productData.id);
                if (existingCartItem) {
                    existingCartItem.quantity++;
                    showAppNotification(`Quantity of "${productData.name}" updated.`, false);
                } else {
                    cart.push({ ...productData, quantity: 1 });
                    showAppNotification(`"${productData.name}" added to cart!`, false);
                }
                saveCartToLocalStorage();
                updateCartDisplay();
            };

            const updateCartQuantity = (productId, newQuantity) => {
                const cartItem = cart.find(item => item.id === productId);
                if (cartItem) {
                    if (newQuantity <= 0) removeFromCart(productId);
                    else { cartItem.quantity = newQuantity; saveCartToLocalStorage(); updateCartDisplay(); }
                }
            };

            const removeFromCart = (productId) => {
                const removedItem = cart.find(item => item.id === productId);
                cart = cart.filter(item => item.id !== productId);
                saveCartToLocalStorage();
                updateCartDisplay();
                if(removedItem) showAppNotification(`"${removedItem.name}" removed.`, true);
            };

            const openOrderConfirmationModal = () => {
                if(cart.length === 0) { showAppNotification("Your cart is empty.", true); return; }

                const subtotal = cart.reduce((sum, item) => sum + (parseFloat(item.price) * item.quantity), 0);
                const totalAmount = subtotal + DELIVERY_FEE;

                if (orderModalTotalAmountEl) orderModalTotalAmountEl.textContent = totalAmount.toFixed(0);

                let orderSummaryHtml = '';
                let cartSummaryForEmail = '';
                cart.forEach(item => {
                    orderSummaryHtml += `<p>${item.name} (${item.restaurant}) x ${item.quantity} - ${CURRENCY_SYMBOL}${(parseFloat(item.price) * item.quantity).toFixed(0)}</p>`;
                    cartSummaryForEmail += `${item.name} (${item.restaurant}) (Qty: ${item.quantity}) - ${CURRENCY_SYMBOL}${parseFloat(item.price).toFixed(0)}\n`;
                });
                orderSummaryHtml += `<p>Delivery Fee: ${CURRENCY_SYMBOL}${DELIVERY_FEE.toFixed(0)}</p>`;
                cartSummaryForEmail += `Delivery Fee: ${CURRENCY_SYMBOL}${DELIVERY_FEE.toFixed(0)}\n`;

                if (orderModalSummaryEl) orderModalSummaryEl.innerHTML = orderSummaryHtml;
                if (formCartDetailsInput) formCartDetailsInput.value = cartSummaryForEmail;
                if (formTotalOrderAmountInput) formTotalOrderAmountInput.value = `${CURRENCY_SYMBOL}${totalAmount.toFixed(0)}`;

                if(cartModal) cartModal.classList.remove('open');
                if(orderConfirmationModal) orderConfirmationModal.classList.add('open');
            };

            const handleDirectOrderNow = (productData) => {
                const existingCartItem = cart.find(item => item.id === productData.id);
                if (existingCartItem) existingCartItem.quantity = Math.max(1, existingCartItem.quantity);
                else cart.push({ ...productData, quantity: 1 });
                saveCartToLocalStorage();
                updateCartDisplay();
                showAppNotification(`Proceeding to order "${productData.name}"...`, false, true);
                openOrderConfirmationModal();
            };

            const renderProductCards = (productsArray, containerElement) => {
                if (!containerElement) return;
                containerElement.innerHTML = '';
                productsArray.forEach(product => {
                    const card = document.createElement('div');
                    card.className = (containerElement.id === 'productSliderWrapper' ? 'slider-product-card app-card' : 'app-card') + ' bg-white rounded-xl shadow-md overflow-hidden flex flex-col border border-gray-100 group';
                    card.innerHTML = `
                        <div class="relative h-52 w-full bg-gradient-to-br from-red-100 to-orange-100 overflow-hidden">
                             <img src="${product.imageUrl}" alt="${product.name}" class="w-full h-full object-cover transition-transform duration-500 ease-in-out group-hover:scale-105" onerror="this.onerror=null; this.src='https://placehold.co/600x400/cccccc/ffffff?text=Delicious+Food';">
                        </div>
                        <div class="p-5 flex flex-col flex-grow">
                            <h3 class="text-lg font-semibold text-gray-800 mb-1">${product.name}</h3>
                            <p class="text-sm text-gray-500 mb-3">${product.restaurant}</p>
                            <p class="text-gray-600 text-sm mb-4 flex-grow line-clamp-3">${product.description}</p>
                            <div class="mt-auto pt-4 border-t border-gray-100">
                                <div class="flex justify-between items-center mb-3">
                                    <span class="text-xl font-bold text-${product.gradientClass ? product.gradientClass.split('-')[1] : 'red'}-600">${product.priceDisplay}</span>
                                </div>
                                <div class="flex justify-between items-center space-x-2">
                                    <button class="add-to-cart-button action-button flex-1"
                                            data-id="${product.id}" data-name="${product.name}" data-price="${product.price}"
                                            data-price-display="${product.priceDisplay}" data-image-url="${product.imageUrl}" data-restaurant="${product.restaurant}">
                                        <i class="fas fa-cart-plus"></i><span>Add to Cart</span>
                                    </button>
                                    <button class="order-now-button action-button ${product.gradientClass || 'bg-red-gradient'} flex-1"
                                            data-id="${product.id}" data-name="${product.name}" data-price="${product.price}"
                                            data-price-display="${product.priceDisplay}" data-image-url="${product.imageUrl}" data-restaurant="${product.restaurant}">
                                        <i class="fas fa-motorcycle"></i><span>Order Now</span>
                                    </button>
                                </div>
                            </div>
                        </div>`;
                    containerElement.appendChild(card);
                });
                containerElement.querySelectorAll('.add-to-cart-button').forEach(button => button.addEventListener('click', (e) => {
                    e.preventDefault();
                    const productData = { id: e.currentTarget.dataset.id, name: e.currentTarget.dataset.name, price: parseFloat(e.currentTarget.dataset.price), priceDisplay: e.currentTarget.dataset.priceDisplay, imageUrl: e.currentTarget.dataset.imageUrl, restaurant: e.currentTarget.dataset.restaurant };
                    addToCart(productData);
                }));
                containerElement.querySelectorAll('.order-now-button').forEach(button => button.addEventListener('click', (e) => {
                    e.preventDefault();
                    const productData = { id: e.currentTarget.dataset.id, name: e.currentTarget.dataset.name, price: parseFloat(e.currentTarget.dataset.price), priceDisplay: e.currentTarget.dataset.priceDisplay, imageUrl: e.currentTarget.dataset.imageUrl, restaurant: e.currentTarget.dataset.restaurant };
                    handleDirectOrderNow(productData);
                }));
            };

            // Initialize product rendering and slider
            if (productSliderWrapper && sliderPrevBtn && sliderNextBtn) {
                const scrollAmount = 295;
                sliderPrevBtn.addEventListener('click', () => productSliderWrapper.scrollLeft -= scrollAmount);
                sliderNextBtn.addEventListener('click', () => productSliderWrapper.scrollLeft += scrollAmount);
                renderProductCards(storeProducts.slice(0, 6), productSliderWrapper);
            }
            if (allAppsGrid) renderProductCards(storeProducts, allAppsGrid);

            // Cart Modal Event Listeners
            if(cartIconWrapper) cartIconWrapper.addEventListener('click', () => { updateCartDisplay(); if(cartModal) cartModal.classList.add('open'); });
            if(closeCartBtn) closeCartBtn.addEventListener('click', () => { if(cartModal) cartModal.classList.remove('open'); });
            if(cartModal) cartModal.addEventListener('click', (e) => { if (e.target === cartModal) cartModal.classList.remove('open'); });
            if(proceedToCheckoutBtn) proceedToCheckoutBtn.addEventListener('click', () => { if(cart.length === 0) { showAppNotification("Your cart is empty.", true); return; } openOrderConfirmationModal(); });

            // Order Confirmation Modal Event Listeners
            if(closeOrderModalBtn) closeOrderModalBtn.addEventListener('click', () => { if(orderConfirmationModal) orderConfirmationModal.classList.remove('open'); });
            if(orderConfirmationModal) orderConfirmationModal.addEventListener('click', (e) => { if (e.target === orderConfirmationModal) orderConfirmationModal.classList.remove('open'); });

            // Order Form Submission Logic
            if(orderForm) {
                orderForm.addEventListener('submit', async (e) => {
                    e.preventDefault();
                    const formData = new FormData(orderForm);
                    const customerName = formData.get('customerName');

                    if (!orderSubmissionMessageEl) return;
                    orderSubmissionMessageEl.style.display = 'none'; orderSubmissionMessageEl.textContent = '';

                    // Basic validation for required fields
                    if (!formData.get('customerName') || !formData.get('deliveryAddress') || !formData.get('customerPhone')) {
                        orderSubmissionMessageEl.innerHTML = 'Please fill in all required fields (Name, Address, Phone).';
                        orderSubmissionMessageEl.style.color = 'var(--primary-color)'; orderSubmissionMessageEl.style.display = 'flex'; return;
                    }
                    // Validate phone number format
                    if (!/^03\d{9}$/.test(formData.get('customerPhone'))) {
                        orderSubmissionMessageEl.innerHTML = 'Please enter a valid 11-digit phone number starting with 03.';
                        orderSubmissionMessageEl.style.color = 'var(--primary-color)'; orderSubmissionMessageEl.style.display = 'flex'; return;
                    }

                    orderSubmissionMessageEl.innerHTML = '<div class="spinner"></div> Placing your order...';
                    orderSubmissionMessageEl.style.color = 'var(--text-light)'; orderSubmissionMessageEl.style.display = 'flex';

                    try {
                        const response = await fetch(orderForm.action, {
                            method: 'POST',
                            body: formData,
                            headers: { 'Accept': 'application/json' }
                        });

                        if (response.ok) {
                            orderSubmissionMessageEl.innerHTML = `Thank you, ${customerName}! Your order has been placed successfully. Estimated delivery in 30-45 minutes.`;
                            orderSubmissionMessageEl.style.color = 'var(--success-color)';
                            orderForm.reset();
                            cart = []; // Clear the cart after successful order
                            saveCartToLocalStorage();
                            updateCartDisplay();
                            setTimeout(() => { if(orderConfirmationModal) orderConfirmationModal.classList.remove('open'); orderSubmissionMessageEl.style.display = 'none'; }, 6000);
                        } else {
                            const errorData = await response.json();
                            orderSubmissionMessageEl.innerHTML = `Error placing order: ${errorData.error || 'Please try again.'}`;
                            orderSubmissionMessageEl.style.color = 'var(--primary-color)';
                        }
                    } catch (error) {
                        orderSubmissionMessageEl.innerHTML = 'Could not place your order. Please check your internet connection and try again.';
                        orderSubmissionMessageEl.style.color = 'var(--primary-color)';
                    }
                    orderSubmissionMessageEl.style.display = 'flex';
                });
            }

            // NEW: Stylish Banner Slider Functions
            const createNewBannerSlides = () => {
                if (!newSliderWrapper || !newSliderDotsContainer) return;

                newSliderWrapper.innerHTML = '';
                newSliderDotsContainer.innerHTML = '';

                newBannerData.forEach((slide, index) => {
                    const slideItem = document.createElement('div');
                    slideItem.classList.add('new-slide-item');
                    slideItem.style.backgroundImage = `url('${slide.src}')`;

                    // Ensure content alignment for flexbox parent is center
                    slideItem.classList.add('justify-center'); // Always center content horizontally now

                    const slideContentDiv = document.createElement('div');
                    slideContentDiv.classList.add('slide-content', `align-${slide.align}`); // Add text alignment class
                    slideContentDiv.innerHTML = `
                        <h1 class="font-poppins">${slide.title}</h1>
                        <p>${slide.description}</p>
                        <a href="${slide.buttonLink}" class="btn-banner">${slide.buttonText}</a>
                    `;
                    slideItem.appendChild(slideContentDiv);
                    newSliderWrapper.appendChild(slideItem);

                    const dot = document.createElement('div');
                    dot.classList.add('new-slider-dot');
                    if (index === 0) dot.classList.add('active');
                    dot.addEventListener('click', () => goToNewBannerSlide(index));
                    newSliderDotsContainer.appendChild(dot);
                });
            };

            const updateNewBannerSliderPosition = () => {
                if (newSliderWrapper) {
                    newSliderWrapper.style.transform = `translateX(-${currentNewBannerSlide * 100}%)`;
                }
                if (newSliderDotsContainer) {
                    newSliderDotsContainer.querySelectorAll('.new-slider-dot').forEach((dot, index) => {
                        dot.classList.toggle('active', index === currentNewBannerSlide);
                    });
                }
            };

            const goToNewBannerSlide = (index) => {
                currentNewBannerSlide = index;
                updateNewBannerSliderPosition();
                resetNewBannerSlideInterval(); // Reset interval on manual click
            };

            const nextNewBannerSlide = () => {
                currentNewBannerSlide = (currentNewBannerSlide + 1) % newBannerData.length;
                updateNewBannerSliderPosition();
            };

            const startNewBannerSlideInterval = () => {
                newBannerSlideInterval = setInterval(nextNewBannerSlide, newBannerSlideDuration);
            };

            const resetNewBannerSlideInterval = () => {
                clearInterval(newBannerSlideInterval);
                startNewBannerSlideInterval();
            };

            // Pause banner on hover
            if (heroBannerNew) {
                heroBannerNew.addEventListener('mouseenter', () => clearInterval(newBannerSlideInterval));
                heroBannerNew.addEventListener('mouseleave', () => startNewBannerSlideInterval());
            }

            // Initialize new banner on load
            createNewBannerSlides();
            startNewBannerSlideInterval();


            const currentYearEl = document.getElementById('currentYear');
            if(currentYearEl) currentYearEl.textContent = new Date().getFullYear();
            updateCartDisplay(); // Initial cart display on load
        });
    </script>
</body>
</html>
