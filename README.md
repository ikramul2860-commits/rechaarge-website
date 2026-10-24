<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shahrukh Abedin | Fintech Founder & Platform Builder</title>
  <meta name="description" content="Founder of BillHub. White-label recharge platforms, payment & OTP APIs, and mobile apps.">

  <!-- Google Fonts: Inter & Plus Jakarta Sans -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Plus+Jakarta+Sans:wght@500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS via CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            display: ['Plus Jakarta Sans', 'sans-serif'],
          },
          colors: {
            brand: {
              400: '#34d399',
              500: '#10b981',
              600: '#059669',
            },
            dark: {
              950: '#06090e',
              900: '#0b111a',
              850: '#101826',
              800: '#162032',
            }
          },
          animation: {
            'marquee': 'marquee 25s linear infinite',
          },
          keyframes: {
            marquee: {
              '0%': { transform: 'translateX(0%)' },
              '100%': { transform: 'translateX(-50%)' }
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Subtle background grid pattern */
    .bg-grid-pattern {
      background-size: 40px 40px;
      background-image: 
        linear-gradient(to right, rgba(255, 255, 255, 0.03) 1px, transparent 1px),
        linear-gradient(to bottom, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
    }
    
    /* Card Glassmorphism */
    .glass-card {
      background: rgba(16, 24, 38, 0.7);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border: 1px solid rgba(255, 255, 255, 0.08);
    }
    .glass-card:hover {
      border-color: rgba(16, 185, 129, 0.35);
      box-shadow: 0 10px 30px -10px rgba(16, 185, 129, 0.15);
    }

    .glow-emerald {
      background: radial-gradient(circle, rgba(16, 185, 129, 0.15) 0%, rgba(16, 185, 129, 0) 70%);
    }
    .glow-cyan {
      background: radial-gradient(circle, rgba(6, 182, 212, 0.12) 0%, rgba(6, 182, 212, 0) 70%);
    }
  </style>
</head>
<body class="bg-dark-950 text-slate-200 font-sans antialiased selection:bg-brand-500 selection:text-white relative overflow-x-hidden">

  <!-- Ambient Glows -->
  <div class="fixed top-0 left-1/2 -translate-x-1/2 w-[800px] h-[500px] glow-emerald pointer-events-none -z-10"></div>
  <div class="fixed top-[45%] right-[-100px] w-[600px] h-[600px] glow-cyan pointer-events-none -z-10"></div>

  <!-- Header / Navigation -->
  <header class="sticky top-0 z-50 backdrop-blur-md bg-dark-950/80 border-b border-white/5 transition-all">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 h-20 flex items-center justify-between">
      <a href="#top" class="flex items-center gap-3 group">
        <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-600 to-emerald-400 flex items-center justify-center font-display font-bold text-dark-950 text-lg shadow-lg shadow-brand-500/20 group-hover:scale-105 transition-transform">
          SA
        </div>
        <div class="flex flex-col">
          <span class="font-display font-bold text-white tracking-tight leading-none text-lg">Shahrukh Abedin</span>
          <span class="text-xs text-brand-400 font-medium tracking-wider uppercase mt-1">Fintech Builder</span>
        </div>
      </a>

      <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
        <a href="#billhub" class="hover:text-brand-400 transition-colors flex items-center gap-1.5">
          <span class="w-1.5 h-1.5 rounded-full bg-brand-400"></span> BillHub
        </a>
        <a href="#about" class="hover:text-brand-400 transition-colors">About</a>
        <a href="#ventures" class="hover:text-brand-400 transition-colors">Ventures</a>
        <a href="#services" class="hover:text-brand-400 transition-colors">Services</a>
        <a href="#connect" class="hover:text-brand-400 transition-colors">Connect</a>
      </nav>

      <a href="#contact" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-full text-xs sm:text-sm font-semibold bg-white/10 hover:bg-brand-500 hover:text-dark-950 text-white border border-white/10 hover:border-brand-400 transition-all">
        Let's talk →
      </a>
    </div>
  </header>

  <main id="top">
    <!-- Hero Section -->
    <section class="relative pt-16 pb-20 md:pt-28 md:pb-32 bg-grid-pattern">
      <div class="max-w-6xl mx-auto px-4 sm:px-6">
        <div class="max-w-3xl">
          <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full text-xs font-medium bg-emerald-500/10 border border-emerald-500/20 text-emerald-300 mb-6">
            <span class="inline-block w-2 h-2 rounded-full bg-brand-400 animate-pulse"></span>
            Fintech Founder · Silbori, Assam
          </div>

          <h1 class="text-4xl sm:text-6xl md:text-7xl font-extrabold font-display text-white tracking-tight leading-[1.1] mb-6">
            Shahrukh Abedin
          </h1>
          <p class="text-xl sm:text-2xl text-slate-300 font-normal leading-relaxed mb-8">
            Founder of <strong class="text-brand-400 font-semibold">BillHub</strong> — I build white-label recharge platforms, payment & OTP APIs, and the apps that run them. From a small town in Assam to businesses across India.
          </p>

          <div class="flex flex-wrap items-center gap-4 mb-16">
            <a href="#contact" class="px-7 py-3.5 rounded-xl font-semibold text-sm bg-brand-500 hover:bg-brand-400 text-dark-950 shadow-lg shadow-brand-500/25 transition-all">
              Start a project
            </a>
            <a href="#billhub" class="px-7 py-3.5 rounded-xl font-semibold text-sm bg-dark-850 hover:bg-dark-800 text-white border border-white/10 transition-all">
              See BillHub
            </a>
          </div>

          <!-- Stats Grid -->
          <div class="grid grid-cols-2 sm:grid-cols-4 gap-4 sm:gap-6 pt-10 border-t border-white/10">
            <div class="p-4 rounded-xl glass-card">
              <div class="text-3xl sm:text-4xl font-extrabold text-white font-display">4</div>
              <div class="text-xs sm:text-sm text-slate-400 mt-1">Ventures founded</div>
            </div>
            <div class="p-4 rounded-xl glass-card">
              <div class="text-3xl sm:text-4xl font-extrabold text-brand-400 font-display">10M+</div>
              <div class="text-xs sm:text-sm text-slate-400 mt-1">Users reached</div>
            </div>
            <div class="p-4 rounded-xl glass-card">
              <div class="text-3xl sm:text-4xl font-extrabold text-white font-display">6+</div>
              <div class="text-xs sm:text-sm text-slate-400 mt-1">Years building</div>
            </div>
            <div class="p-4 rounded-xl glass-card">
              <div class="text-3xl sm:text-4xl font-extrabold text-brand-400 font-display">500+</div>
              <div class="text-xs sm:text-sm text-slate-400 mt-1">Businesses served</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Flagship: BillHub -->
    <section id="billhub" class="py-20 border-t border-white/5">
      <div class="max-w-6xl mx-auto px-4 sm:px-6">
        <div class="text-xs font-bold uppercase tracking-widest text-brand-400 mb-3">★ Flagship Product</div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
          <div class="lg:col-span-7">
            <h2 class="text-3xl sm:text-5xl font-extrabold text-white font-display tracking-tight leading-tight mb-4">
              BillHub
              <span class="block text-2xl sm:text-3xl text-slate-400 font-normal mt-2">Recharge & bill payments, at scale.</span>
            </h2>
            <p class="text-slate-300 text-base sm:text-lg leading-relaxed mb-6">
              India's recharge & bill-payment platform — mobile, DTH, electricity, FASTag and more — with white-label, reseller and full API infrastructure. Trusted by users and resellers across the country.
            </p>

            <div class="grid grid-cols-3 gap-4 mb-8">
              <div class="p-4 rounded-xl bg-dark-900 border border-white/5">
                <span class="text-2xl font-bold text-white block">10M+</span>
                <span class="text-xs text-slate-400">1 Crore+ users</span>
              </div>
              <div class="p-4 rounded-xl bg-dark-900 border border-white/5">
                <span class="text-2xl font-bold text-emerald-400 block">24×7</span>
                <span class="text-xs text-slate-400">Instant recharge</span>
              </div>
              <div class="p-4 rounded-xl bg-dark-900 border border-white/5">
                <span class="text-2xl font-bold text-white block">Pan‑India</span>
                <span class="text-xs text-slate-400">Reseller network</span>
              </div>
            </div>

            <div class="flex flex-wrap items-center gap-4 mb-6">
              <a href="https://play.google.com/store" target="_blank" class="px-5 py-3 rounded-xl bg-white text-dark-950 font-semibold text-sm hover:bg-slate-200 transition-colors">
                Google Play
              </a>
              <a href="https://www.apple.com/app-store/" target="_blank" class="px-5 py-3 rounded-xl bg-white/10 hover:bg-white/15 text-white font-semibold text-sm border border-white/10 transition-colors">
                App Store
              </a>
              <a href="https://billhub.in/" target="_blank" class="text-sm font-semibold text-brand-400 hover:text-brand-300 ml-2">
                Visit BillHub ↗
              </a>
            </div>

            <p class="text-xs text-slate-500">
              Payments powered by <span class="text-slate-400">Cashfree · Zaakpay · BBPS via MobiKwik · BillAvenue</span>
            </p>
          </div>

          <!-- Smartphone Mockup -->
          <div class="lg:col-span-5 flex justify-center">
            <div class="w-full max-w-[330px] rounded-[36px] p-4 bg-gradient-to-b from-slate-700 via-dark-850 to-dark-950 border-4 border-slate-700/60 shadow-2xl">
              <div class="bg-dark-900 rounded-[26px] p-5 text-white overflow-hidden border border-white/5">
                <div class="flex justify-between items-center text-[10px] text-slate-400 mb-4 px-1">
                  <span>9:41</span>
                  <span>5G 🔋</span>
                </div>

                <div class="flex justify-between items-center mb-5">
                  <div>
                    <span class="text-xs text-slate-400 block">Welcome back</span>
                    <h3 class="text-base font-bold text-white flex items-center gap-1.5 font-display">
                      <span class="w-2.5 h-2.5 rounded-full bg-brand-400 inline-block"></span> BillHub
                    </h3>
                  </div>
                  <div class="w-8 h-8 rounded-full bg-dark-800 border border-white/10 flex items-center justify-center text-xs">🔔</div>
                </div>

                <div class="p-4 rounded-2xl bg-gradient-to-br from-emerald-600 to-brand-600 text-white mb-5 shadow-lg">
                  <div class="text-[11px] opacity-80 mb-0.5">Wallet balance</div>
                  <div class="text-2xl font-bold font-display" id="mockupBalance">₹ 48,250</div>
                  <div class="flex gap-2 mt-3 pt-3 border-t border-white/20 text-xs">
                    <button onclick="addBalance(500)" class="px-2.5 py-1 bg-white/20 hover:bg-white/30 rounded-lg font-medium transition-colors">+ Add money</button>
                    <button class="px-2.5 py-1 bg-black/20 hover:bg-black/30 rounded-lg font-medium transition-colors">History</button>
                  </div>
                </div>

                <div class="text-xs font-semibold text-slate-400 uppercase tracking-wider mb-3">Quick Services</div>
                <div class="grid grid-cols-4 gap-2 text-center text-[11px] mb-5">
                  <div class="p-2 rounded-xl bg-dark-850 border border-white/5">📱<br>Mobile</div>
                  <div class="p-2 rounded-xl bg-dark-850 border border-white/5">📡<br>DTH</div>
                  <div class="p-2 rounded-xl bg-dark-850 border border-white/5">⚡<br>Electric</div>
                  <div class="p-2 rounded-xl bg-dark-850 border border-white/5">🚗<br>FASTag</div>
                  <div class="p-2 rounded-xl bg-dark-850 border border-white/5">📶<br>Wifi</div>
                  <div class="p-2 rounded-xl bg-dark-850 border border-white/5">🔥<br>Gas</div>
                  <div class="p-2 rounded-xl bg-dark-850 border border-white/5">💧<br>Water</div>
                  <div class="p-2 rounded-xl bg-dark-850 border border-white/5">➕<br>More</div>
                </div>

                <a href="#contact" class="block w-full py-2.5 text-center rounded-xl font-semibold text-xs bg-brand-500 text-dark-950 hover:bg-brand-400 transition-colors">
                  Recharge now →
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 01: About -->
    <section id="about" class="py-24 border-t border-white/5">
      <div class="max-w-6xl mx-auto px-4 sm:px-6">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-10">
          <div class="lg:col-span-4">
            <span class="text-xs font-mono font-bold text-brand-400 block mb-2">01 / ABOUT</span>
            <h2 class="text-3xl sm:text-4xl font-extrabold text-white font-display">
              A self-taught builder turning ideas into products people pay for.
            </h2>
          </div>
          <div class="lg:col-span-8 space-y-5 text-slate-300 text-base leading-relaxed">
            <p>
              I'm <strong class="text-white">Shahrukh Abedin</strong>, a fintech entrepreneur from Silbori, Assam. I started with a little PHP and a lot of curiosity — and built it into a stack of live products used by resellers and businesses every day.
            </p>
            <p>
              Today I run BillHub and a family of payment ventures, ship apps to the Play Store, and help other founders launch their own recharge and payment platforms — end to end, from code to go-live.
            </p>
            <div class="p-6 rounded-2xl glass-card flex flex-col md:flex-row md:items-center justify-between gap-6 mt-6">
              <div>
                <h4 class="text-white font-bold font-display text-lg">Shahrukh Abedin</h4>
                <p class="text-xs text-brand-400">Founder · Fintech & Platforms</p>
                <p class="text-xs text-slate-400 mt-1">📍 Silbori, Darrang, Assam — 784114</p>
              </div>
              <div class="flex flex-wrap gap-2 max-w-sm">
                <span class="px-2.5 py-1 rounded-md text-xs bg-dark-900 border border-white/10">PHP · MySQL</span>
                <span class="px-2.5 py-1 rounded-md text-xs bg-dark-900 border border-white/10">API Infrastructure</span>
                <span class="px-2.5 py-1 rounded-md text-xs bg-dark-900 border border-white/10">Play Store Publisher</span>
                <span class="px-2.5 py-1 rounded-md text-xs bg-dark-900 border border-white/10">White-Label Systems</span>
                <span class="px-2.5 py-1 rounded-md text-xs bg-dark-900 border border-white/10">Graphic Design</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 02: More Ventures -->
    <section id="ventures" class="py-24 border-t border-white/5 bg-dark-900/30">
      <div class="max-w-6xl mx-auto px-4 sm:px-6">
        <div class="mb-14">
          <span class="text-xs font-mono font-bold text-brand-400 block mb-2">02 / MORE VENTURES</span>
          <h2 class="text-3xl sm:text-4xl font-extrabold text-white font-display">Beyond BillHub.</h2>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
          <div class="p-8 rounded-2xl glass-card">
            <div class="w-12 h-12 rounded-xl bg-cyan-500/10 text-cyan-400 flex items-center justify-center font-bold text-xl mb-6">O</div>
            <span class="text-xs text-brand-400 uppercase tracking-widest font-semibold block mb-1">Founder</span>
            <h3 class="text-2xl font-bold text-white font-display mb-3">OkPe</h3>
            <p class="text-slate-300 text-sm mb-6">Digital payments venture built to make everyday transactions simpler and faster.</p>
            <span class="text-xs text-emerald-400 font-medium">● Live product</span>
          </div>
          <div class="p-8 rounded-2xl glass-card">
            <div class="w-12 h-12 rounded-xl bg-purple-500/10 text-purple-400 flex items-center justify-center font-bold text-xl mb-6">P</div>
            <span class="text-xs text-brand-400 uppercase tracking-widest font-semibold block mb-1">Founder</span>
            <h3 class="text-2xl font-bold text-white font-display mb-3">PayBen</h3>
            <p class="text-slate-300 text-sm mb-6">Payments product focused on reliable, low-friction money movement and bill payments.</p>
            <span class="text-xs text-emerald-400 font-medium">● Live product</span>
          </div>
          <div class="p-8 rounded-2xl glass-card">
            <div class="w-12 h-12 rounded-xl bg-emerald-500/10 text-emerald-400 flex items-center justify-center font-bold text-xl mb-6">R</div>
            <span class="text-xs text-brand-400 uppercase tracking-widest font-semibold block mb-1">Founder</span>
            <h3 class="text-2xl font-bold text-white font-display mb-3">Recharge Hub</h3>
            <p class="text-slate-300 text-sm mb-6">White-label recharge platform letting partners run their own branded recharge business.</p>
            <span class="text-xs text-emerald-400 font-medium">● Live product</span>
          </div>
        </div>
      </div>
    </section>

    <!-- 03: Services -->
    <section id="services" class="py-24 border-t border-white/5">
      <div class="max-w-6xl mx-auto px-4 sm:px-6">
        <div class="mb-14">
          <span class="text-xs font-mono font-bold text-brand-400 block mb-2">03 / WHAT I OFFER</span>
          <h2 class="text-3xl sm:text-4xl font-extrabold text-white font-display">Services & solutions.</h2>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
          <div class="p-7 rounded-2xl glass-card">
            <div class="text-2xl mb-4">🚀</div>
            <h3 class="text-lg font-bold text-white mb-2">White-Label Recharge App</h3>
            <p class="text-slate-300 text-sm">Your own branded recharge & bill-payment platform — web, admin, reseller and mobile.</p>
          </div>
          <div class="p-7 rounded-2xl glass-card">
            <div class="text-2xl mb-4">⚡</div>
            <h3 class="text-lg font-bold text-white mb-2">Recharge API</h3>
            <p class="text-slate-300 text-sm">Fast, reliable mobile, DTH and bill-payment APIs with clean docs and high uptime.</p>
          </div>
          <div class="p-7 rounded-2xl glass-card">
            <div class="text-2xl mb-4">💬</div>
            <h3 class="text-lg font-bold text-white mb-2">Bulk SMS & OTP API</h3>
            <p class="text-slate-300 text-sm">High-delivery transactional SMS and OTP infrastructure for verification and alerts.</p>
          </div>
          <div class="p-7 rounded-2xl glass-card">
            <div class="text-2xl mb-4">💡</div>
            <h3 class="text-lg font-bold text-white mb-2">Business Consultation</h3>
            <p class="text-slate-300 text-sm">Strategy for fintech & recharge businesses — pricing, tech stack, and go-to-market.</p>
          </div>
          <div class="p-7 rounded-2xl glass-card">
            <div class="text-2xl mb-4">📱</div>
            <h3 class="text-lg font-bold text-white mb-2">Play Store Publishing</h3>
            <p class="text-slate-300 text-sm">End-to-end publishing on Google Play — policies, setup, and approved live listings.</p>
          </div>
          <div class="p-7 rounded-2xl glass-card">
            <div class="text-2xl mb-4">🎨</div>
            <h3 class="text-lg font-bold text-white mb-2">Graphic Design</h3>
            <p class="text-slate-300 text-sm">Brand visuals, logos, app graphics, social creatives, and marketing collateral.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- 04: Partnerships & Marquee -->
    <section class="py-24 border-t border-white/5 bg-dark-900/30">
      <div class="max-w-6xl mx-auto px-4 sm:px-6">
        <div class="mb-14">
          <span class="text-xs font-mono font-bold text-brand-400 block mb-2">04 / PARTNERSHIPS & TRUST</span>
          <h2 class="text-3xl sm:text-4xl font-extrabold text-white font-display">Built with the right people and platforms.</h2>
        </div>

        <div class="p-8 rounded-2xl glass-card mb-12 border-emerald-500/20">
          <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-6">
            <div class="flex items-center gap-5">
              <div class="w-16 h-16 rounded-2xl bg-gradient-to-tr from-rose-500 to-amber-500 flex items-center justify-center font-display font-bold text-white text-2xl">
                DB
              </div>
              <div>
                <span class="text-xs font-mono text-brand-400 font-semibold uppercase">Strategic Partner</span>
                <h3 class="text-2xl font-bold text-white font-display">Dimpu Baruah</h3>
                <p class="text-slate-300 text-sm mt-1">Creator & entrepreneur — partnering to build and scale products.</p>
              </div>
            </div>
            <div class="flex gap-6">
              <div><span class="text-2xl font-bold text-white">3M+</span><span class="text-xs text-slate-400 block">YouTube</span></div>
              <div class="border-l border-white/10 pl-6"><span class="text-2xl font-bold text-white">1M+</span><span class="text-xs text-slate-400 block">Instagram</span></div>
            </div>
          </div>
        </div>

        <!-- Marquee Ticker -->
        <div class="relative overflow-hidden py-4 [mask-image:_linear-gradient(to_right,transparent_0,_black_128px,_black_calc(100%-128px),transparent_100%)]">
          <div class="flex gap-8 items-center animate-marquee whitespace-nowrap text-slate-300 font-semibold text-lg">
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">Cashfree</span>
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">Zaakpay</span>
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">MobiKwik BBPS</span>
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">BillAvenue</span>
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">BillHub</span>
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">OkPe</span>
            <!-- Loop -->
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">Cashfree</span>
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">Zaakpay</span>
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">MobiKwik BBPS</span>
            <span class="px-5 py-2.5 rounded-xl bg-dark-850 border border-white/5">BillAvenue</span>
          </div>
        </div>
      </div>
    </section>

    <!-- 05: Follow Along -->
    <section id="connect" class="py-24 border-t border-white/5">
      <div class="max-w-6xl mx-auto px-4 sm:px-6">
        <div class="mb-14">
          <span class="text-xs font-mono font-bold text-brand-400 block mb-2">05 / FOLLOW ALONG</span>
          <h2 class="text-3xl sm:text-4xl font-extrabold text-white font-display">Find me across the web.</h2>
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
          <a href="https://instagram.com/" target="_blank" class="p-6 rounded-2xl glass-card hover:bg-dark-800 transition-all">
            <span class="text-2xl mb-3 block">📸</span>
            <h4 class="font-bold text-white">Instagram</h4>
            <span class="text-xs text-brand-400 mt-4 block">Follow ↗</span>
          </a>
          <a href="https://youtube.com/" target="_blank" class="p-6 rounded-2xl glass-card hover:bg-dark-800 transition-all">
            <span class="text-2xl mb-3 block">🎥</span>
            <h4 class="font-bold text-white">YouTube</h4>
            <span class="text-xs text-brand-400 mt-4 block">Subscribe ↗</span>
          </a>
          <a href="https://linkedin.com/" target="_blank" class="p-6 rounded-2xl glass-card hover:bg-dark-800 transition-all">
            <span class="text-2xl mb-3 block">💼</span>
            <h4 class="font-bold text-white">LinkedIn</h4>
            <span class="text-xs text-brand-400 mt-4 block">Connect ↗</span>
          </a>
          <a href="https://wa.me/918638434734" target="_blank" class="p-6 rounded-2xl glass-card hover:bg-dark-800 transition-all">
            <span class="text-2xl mb-3 block">💬</span>
            <h4 class="font-bold text-white">WhatsApp</h4>
            <span class="text-xs text-brand-400 mt-4 block">+91 86384 34734 ↗</span>
          </a>
        </div>
      </div>
    </section>

    <!-- 06: Get in Touch (WhatsApp Generator) -->
    <section id="contact" class="py-24 border-t border-white/5 bg-gradient-to-b from-transparent to-dark-900/60">
      <div class="max-w-6xl mx-auto px-4 sm:px-6">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
          <div class="lg:col-span-5">
            <span class="text-xs font-mono font-bold text-brand-400 block mb-2">06 / GET IN TOUCH</span>
            <h2 class="text-3xl sm:text-5xl font-extrabold text-white font-display mb-4">Let's build<br>something.</h2>
            <p class="text-slate-300 text-sm leading-relaxed mb-6">
              Want your own recharge platform, an API integration, or an app on the Play Store? Tell me what you're building — I'll reply on WhatsApp.
            </p>
            <div class="text-sm space-y-3 text-slate-300">
              <p>📞 <a href="https://wa.me/918638434734" class="hover:text-brand-400">+91 86384 34734</a></p>
              <p>📍 Silbori, Darrang, Assam — 784114</p>
              <p>🌐 <a href="https://shahrukhabedin.com/" class="hover:text-brand-400">shahrukhabedin.com</a></p>
            </div>
          </div>

          <div class="lg:col-span-7">
            <form id="whatsappForm" onsubmit="handleSendWhatsApp(event)" class="p-8 rounded-3xl glass-card space-y-5">
              <div>
                <label class="block text-xs font-semibold uppercase text-slate-300 mb-2">Your Name</label>
                <input type="text" id="userName" required placeholder="e.g. Rahul Sharma" class="w-full px-4 py-3 rounded-xl bg-dark-900 border border-white/10 text-white text-sm focus:border-brand-400 outline-none">
              </div>

              <div>
                <label class="block text-xs font-semibold uppercase text-slate-300 mb-2">What you need</label>
                <select id="userNeed" class="w-full px-4 py-3 rounded-xl bg-dark-900 border border-white/10 text-white text-sm focus:border-brand-400 outline-none">
                  <option value="White-Label Recharge App">White-Label Recharge App</option>
                  <option value="Recharge & Bill Payment API">Recharge & Bill Payment API</option>
                  <option value="Bulk SMS & OTP Infrastructure">Bulk SMS & OTP Infrastructure</option>
                  <option value="Play Store Publishing & Compliance">Play Store Publishing & Compliance</option>
                  <option value="Business Consultation / Strategy">Business Consultation / Strategy</option>
                </select>
              </div>

              <div>
                <label class="block text-xs font-semibold uppercase text-slate-300 mb-2">Message</label>
                <textarea id="userMsg" rows="4" required placeholder="Tell me briefly about your business or goals..." class="w-full px-4 py-3 rounded-xl bg-dark-900 border border-white/10 text-white text-sm focus:border-brand-400 outline-none"></textarea>
              </div>

              <button type="submit" class="w-full py-4 rounded-xl font-bold text-sm bg-brand-500 hover:bg-brand-400 text-dark-950 transition-colors">
                Send on WhatsApp
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="border-t border-white/5 py-12 bg-dark-950 text-xs text-slate-500">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 flex flex-col sm:flex-row justify-between items-center gap-4">
      <p>© 2026 Shahrukh Abedin. All rights reserved.</p>
      <p>Silbori · Assam · India</p>
    </div>
  </footer>

  <script>
    // Simulate wallet balance increase
    let balance = 48250;
    function addBalance(amount) {
      balance += amount;
      document.getElementById('mockupBalance').innerText = '₹ ' + balance.toLocaleString('en-IN');
    }

    // Direct WhatsApp redirect
    function handleSendWhatsApp(e) {
      e.preventDefault();
      const name = document.getElementById('userName').value.trim();
      const need = document.getElementById('userNeed').value;
      const message = document.getElementById('userMsg').value.trim();

      const phone = "918638434734";
      const text = `Hi Shahrukh,\n\nName: ${name}\nNeed: ${need}\n\nMessage:\n${message}\n\n(Sent via portfolio website)`;
      window.open(`https://wa.me/${phone}?text=${encodeURIComponent(text)}`, '_blank');
    }
  </script>
</body>
</html>
