<!DOCTYPE html>
<html lang="ja" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HASETOMO. ONE MAN LIVE TOUR 2026 ~ REVOLUTION ~ | チケット・公演情報まとめ</title>
  <meta name="description" content="HASETOMO. ONE MAN LIVE TOUR 2026 ~ REVOLUTION ~ の各種プレイガイド（イープラス・ローチケ・チケットぴあ）および全国公演スケジュールまとめページです。" />

  <!-- Google Fonts: ツアービジュアルに合わせた力強い欧文と視認性の高い和文フォント -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,600;0,800;0,900;1,800&family=Noto+Sans+JP:wght@400;500;700;900&family=Oswald:wght@500;700&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['"Noto Sans JP"', 'sans-serif'],
            display: ['"Montserrat"', 'sans-serif'],
            condensed: ['"Oswald"', 'sans-serif'],
          },
          colors: {
            brand: {
              orange: '#ff7b00',
              amber: '#ff9e00',
              dark: '#09090b',
              card: '#121216',
              border: '#27272a',
            }
          },
          animation: {
            'pulse-slow': 'pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite',
            'shimmer': 'shimmer 2.5s linear infinite',
          },
          keyframes: {
            shimmer: {
              '0%': { transform: 'translateX(-100%)' },
              '100%': { transform: 'translateX(100%)' }
            }
          }
        }
      }
    }
  </script>

  <style>
    /* カスタムスクロールバー & ベーススタイル */
    body {
      background-color: #08080a;
      color: #f4f4f5;
      overflow-x: hidden;
      -webkit-tap-highlight-color: transparent;
    }

    /* 背景の微細なグリッド＆ノイズ質感 */
    .bg-street-grid {
      background-image: 
        radial-gradient(circle at 50% 0%, rgba(255, 123, 0, 0.14) 0%, rgba(8, 8, 10, 0) 60%),
        linear-gradient(to right, rgba(255, 255, 255, 0.025) 1px, transparent 1px),
        linear-gradient(to bottom, rgba(255, 255, 255, 0.025) 1px, transparent 1px);
      background-size: 100% 100%, 32px 32px, 32px 32px;
    }

    /* チケットボタンのホバー・タップエフェクト */
    .ticket-card {
      position: relative;
      overflow: hidden;
      transition: transform 0.22s cubic-bezier(0.22, 1, 0.36, 1), box-shadow 0.22s ease, border-color 0.22s ease;
    }
    .ticket-card:hover {
      transform: translateY(-2px);
    }
    .ticket-card:active {
      transform: scale(0.985);
    }

    /* ライトニングの微光アニメーション */
    @keyframes flashGlow {
      0%, 100% { opacity: 0.35; }
      50% { opacity: 0.75; }
    }
    .lightning-accent {
      animation: flashGlow 3.5s ease-in-out infinite;
    }
  </style>
</head>
<body class="bg-street-grid min-h-screen flex flex-col items-center antialiased selection:bg-brand-orange selection:text-black">

  <!-- 背景の稲妻SVGデコレーション -->
  <div class="fixed inset-0 pointer-events-none overflow-hidden z-0" aria-hidden="true">
    <svg class="absolute -top-12 -right-16 w-96 h-96 text-white/10 lightning-accent" viewBox="0 0 200 200" fill="none">
      <path d="M120 10L65 95H110L85 190L155 85H105L120 10Z" stroke="currentColor" stroke-width="0.75" />
    </svg>
    <svg class="absolute bottom-10 -left-20 w-80 h-80 text-brand-orange/10 lightning-accent" style="animation-delay: 1.5s;" viewBox="0 0 200 200" fill="none">
      <path d="M90 15L40 105H85L65 185L135 85H90L90 15Z" stroke="currentColor" stroke-width="0.75" />
    </svg>
  </div>

  <!-- メインコンテナ（スマホ閲覧に最適化しつつPCでも美しく表示） -->
  <main class="relative z-10 w-full max-w-xl mx-auto px-4 pt-4 pb-16 sm:pt-8">

    <!-- ヒーローセクション：TOP画像 & ツアータイトル -->
    <header class="relative rounded-2xl overflow-hidden bg-zinc-900 border border-zinc-800/90 shadow-2xl shadow-black/80">
      <!-- キービジュアル画像エリア -->
      <div class="relative w-full aspect-[16/10] sm:aspect-[16/9.6] bg-zinc-900 overflow-hidden group">
        <img
          id="hero-poster-img"
          src="はせとも2026ツアー横.webp"
          alt="HASETOMO. ONE MAN LIVE TOUR 2026 ~ REVOLUTION ~ メインビジュアル"
          class="w-full h-full object-cover object-center transition-transform duration-700 group-hover:scale-[1.02]"
          onerror="handleImageError(this)"
        />

        <!-- 画像ローカル未配置時のフォールバック表示（通常時は非表示） -->
        <div id="image-fallback-banner" class="hidden absolute inset-0 flex flex-col items-center justify-center bg-gradient-to-br from-zinc-900 via-zinc-800 to-black p-6 text-center">
          <div class="w-12 h-12 rounded-full bg-brand-orange/20 border border-brand-orange/40 flex items-center justify-center text-brand-orange mb-3">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z" />
            </svg>
          </div>
          <p class="font-display font-extrabold tracking-wider text-sm text-zinc-200 uppercase">HASETOMO. ONE MAN LIVE TOUR 2026</p>
          <p class="text-xs text-zinc-400 mt-1">同一フォルダに <code class="text-brand-orange bg-black/50 px-1.5 py-0.5 rounded">はせとも2026ツアー横.webp</code> を配置すると表示されます</p>
          <label class="mt-3 cursor-pointer inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-zinc-800 hover:bg-zinc-700 border border-zinc-600 text-xs font-medium text-zinc-200 transition">
            <span>プレビュー用に画像を選択</span>
            <input type="file" accept="image/*" class="hidden" onchange="previewLocalFile(event)" />
          </label>
        </div>

        <!-- 下部グラデーションブレンド -->
        <div class="absolute inset-x-0 bottom-0 h-20 bg-gradient-to-t from-[#111114] via-[#111114]/60 to-transparent pointer-events-none"></div>
      </div>

      <!-- イベントタイトル＆概要ヘッダー -->
      <div class="relative px-5 pb-6 pt-2 sm:px-7 sm:pb-7 bg-[#111114]">
        <div class="inline-flex items-center gap-2 px-2.5 py-1 rounded-full bg-brand-orange/15 border border-brand-orange/35 text-brand-orange text-[11px] font-display font-bold tracking-widest uppercase mb-3">
          <span class="w-1.5 h-1.5 rounded-full bg-brand-orange animate-ping"></span>
          OFFICIAL TICKET HUB
        </div>

        <h1 class="font-display font-black text-2xl sm:text-3xl tracking-tight text-white leading-tight">
          HASETOMO.
          <span class="block text-lg sm:text-xl font-extrabold text-zinc-200 mt-0.5">
            ONE MAN LIVE TOUR 2026
          </span>
          <span class="inline-block text-xl sm:text-2xl italic font-black text-transparent bg-clip-text bg-gradient-to-r from-[#ff7b00] via-[#ff9e00] to-[#ff6a00] mt-0.5 tracking-wide">
            ~ REVOLUTION ~
          </span>
        </h1>
      </div>
    </header>

    <!-- チケットプレイガイド リンクセクション -->
    <section aria-labelledby="tickets-heading" class="mt-7">
      <div class="flex items-center justify-between px-1 mb-3.5">
        <div class="flex items-center gap-2.5">
          <span class="w-1 h-5 rounded-full bg-brand-orange"></span>
          <h2 id="tickets-heading" class="font-display font-extrabold text-base sm:text-lg tracking-wider text-white uppercase">
            TICKETS <span class="text-xs font-sans font-bold text-zinc-400 ml-1.5">チケット購入</span>
          </h2>
        </div>
        <span class="text-[11px] text-zinc-500 font-medium">外部サイトへ移動します</span>
      </div>

      <div class="space-y-3.5">
        <!-- 1. イープラス (e+) -->
        <a
          href="https://eplus.jp/sf/detail/4369350001"
          target="_blank"
          rel="noopener noreferrer"
          class="ticket-card group block rounded-2xl bg-gradient-to-r from-[#16161b] to-[#1b1519] border border-zinc-800 hover:border-[#eb0065]/70 p-4 sm:p-5 shadow-lg hover:shadow-[0_8px_30px_rgba(235,0,101,0.18)]"
        >
          <!-- ホバー時のシマー光沢 -->
          <div class="absolute inset-0 -translate-x-full group-hover:animate-[shimmer_1.5s_ease-in-out] bg-gradient-to-r from-transparent via-white/[0.04] to-transparent pointer-events-none"></div>

          <div class="flex items-center justify-between gap-4">
            <div class="flex items-center gap-3.5 sm:gap-4">
              <!-- e+ バッジアイコン -->
              <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-[#eb0065]/15 border border-[#eb0065]/40 flex flex-col items-center justify-center shrink-0 group-hover:bg-[#eb0065] group-hover:border-[#eb0065] transition-colors duration-200">
                <span class="font-display font-black text-xl sm:text-2xl tracking-tighter text-[#ff2e88] group-hover:text-white leading-none">e+</span>
              </div>
              <div>
                <div class="flex items-center gap-2">
                  <span class="font-sans font-black text-base sm:text-lg text-white group-hover:text-[#ff4d9a] transition-colors">イープラス</span>
                  <span class="text-[10px] font-display font-bold uppercase tracking-wider px-2 py-0.5 rounded bg-zinc-800/90 text-zinc-300 border border-zinc-700/70">eplus</span>
                </div>
                <p class="text-xs text-zinc-400 mt-0.5">チケット申し込み・詳細はこちら</p>
              </div>
            </div>

            <!-- 外部リンク矢印ボタン -->
            <div class="w-9 h-9 rounded-full bg-zinc-800/80 group-hover:bg-[#eb0065] flex items-center justify-center text-zinc-300 group-hover:text-white transition-all duration-200 shrink-0">
              <svg class="w-4 h-4 transform group-hover:translate-x-0.5 group-hover:-translate-y-0.5 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M7 17L17 7M17 7H8M17 7V16" />
              </svg>
            </div>
          </div>
        </a>

        <!-- 2. ローチケ (Lawson Ticket) -->
        <a
          href="https://l-tike.com/concert/mevent/?mid=797133"
          target="_blank"
          rel="noopener noreferrer"
          class="ticket-card group block rounded-2xl bg-gradient-to-r from-[#16161b] to-[#131822] border border-zinc-800 hover:border-[#0068b7]/80 p-4 sm:p-5 shadow-lg hover:shadow-[0_8px_30px_rgba(0,104,183,0.22)]"
        >
          <div class="absolute inset-0 -translate-x-full group-hover:animate-[shimmer_1.5s_ease-in-out] bg-gradient-to-r from-transparent via-white/[0.04] to-transparent pointer-events-none"></div>

          <div class="flex items-center justify-between gap-4">
            <div class="flex items-center gap-3.5 sm:gap-4">
              <!-- ローチケ バッジアイコン -->
              <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-[#0068b7]/20 border border-[#0068b7]/50 flex flex-col items-center justify-center shrink-0 group-hover:bg-[#0068b7] group-hover:border-[#0068b7] transition-colors duration-200">
                <span class="font-display font-black text-base sm:text-lg tracking-tight text-[#38a1f3] group-hover:text-white leading-none">L-tike</span>
              </div>
              <div>
                <div class="flex items-center gap-2">
                  <span class="font-sans font-black text-base sm:text-lg text-white group-hover:text-[#5ab4ff] transition-colors">ローチケ</span>
                  <span class="text-[10px] font-display font-bold uppercase tracking-wider px-2 py-0.5 rounded bg-zinc-800/90 text-zinc-300 border border-zinc-700/70">LAWSON TICKET</span>
                </div>
                <p class="text-xs text-zinc-400 mt-0.5">ローソンチケット 公演ページへ</p>
              </div>
            </div>

            <div class="w-9 h-9 rounded-full bg-zinc-800/80 group-hover:bg-[#0068b7] flex items-center justify-center text-zinc-300 group-hover:text-white transition-all duration-200 shrink-0">
              <svg class="w-4 h-4 transform group-hover:translate-x-0.5 group-hover:-translate-y-0.5 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M7 17L17 7M17 7H8M17 7V16" />
              </svg>
            </div>
          </div>
        </a>

        <!-- 3. チケットぴあ (Ticket Pia) -->
        <a
          href="https://t.pia.jp/pia/event/event.do?eventBundleCd=b2671909"
          target="_blank"
          rel="noopener noreferrer"
          class="ticket-card group block rounded-2xl bg-gradient-to-r from-[#16161b] to-[#121c21] border border-zinc-800 hover:border-[#0099d9]/80 p-4 sm:p-5 shadow-lg hover:shadow-[0_8px_30px_rgba(0,153,217,0.2)]"
        >
          <div class="absolute inset-0 -translate-x-full group-hover:animate-[shimmer_1.5s_ease-in-out] bg-gradient-to-r from-transparent via-white/[0.04] to-transparent pointer-events-none"></div>

          <div class="flex items-center justify-between gap-4">
            <div class="flex items-center gap-3.5 sm:gap-4">
              <!-- チケットぴあ バッジアイコン -->
              <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-[#0099d9]/15 border border-[#0099d9]/45 flex flex-col items-center justify-center shrink-0 group-hover:bg-[#0099d9] group-hover:border-[#0099d9] transition-colors duration-200">
                <span class="font-display font-black text-base sm:text-lg tracking-tight text-[#2ec2ff] group-hover:text-white leading-none">PIA</span>
              </div>
              <div>
                <div class="flex items-center gap-2">
                  <span class="font-sans font-black text-base sm:text-lg text-white group-hover:text-[#5cd1ff] transition-colors">チケットぴあ</span>
                  <span class="text-[10px] font-display font-bold uppercase tracking-wider px-2 py-0.5 rounded bg-zinc-800/90 text-zinc-300 border border-zinc-700/70">TICKET PIA</span>
                </div>
                <p class="text-xs text-zinc-400 mt-0.5">チケットぴあ 公演ページへ</p>
              </div>
            </div>

            <div class="w-9 h-9 rounded-full bg-zinc-800/80 group-hover:bg-[#0099d9] flex items-center justify-center text-zinc-300 group-hover:text-white transition-all duration-200 shrink-0">
              <svg class="w-4 h-4 transform group-hover:translate-x-0.5 group-hover:-translate-y-0.5 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M7 17L17 7M17 7H8M17 7V16" />
              </svg>
            </div>
          </div>
        </a>
      </div>
    </section>

    <!-- ツアースケジュール一覧セクション（画像記載の全9公演） -->
    <section aria-labelledby="schedule-heading" class="mt-9">
      <div class="flex items-center justify-between px-1 mb-3.5">
        <div class="flex items-center gap-2.5">
          <span class="w-1 h-5 rounded-full bg-brand-orange"></span>
          <h2 id="schedule-heading" class="font-display font-extrabold text-base sm:text-lg tracking-wider text-white uppercase">
            TOUR SCHEDULE <span class="text-xs font-sans font-bold text-zinc-400 ml-1.5">公演日程</span>
          </h2>
        </div>
        <span class="text-[11px] font-display font-semibold text-brand-orange tracking-wider">ALL 9 SHOWS</span>
      </div>

      <div class="rounded-2xl bg-[#111114] border border-zinc-800/90 divide-y divide-zinc-800/70 overflow-hidden shadow-xl">
        <!-- 1. CHIBA (公演終了) -->
        <div class="flex items-center justify-between px-4 py-3.5 sm:px-5 bg-zinc-950/50 opacity-60">
          <div class="flex flex-wrap items-center gap-2 sm:gap-3">
            <div class="flex items-baseline gap-2">
              <span class="font-condensed font-bold text-base sm:text-lg tracking-wide text-zinc-400 line-through decoration-zinc-600">2026.9.12</span>
              <span class="text-[11px] font-display font-bold text-zinc-600">(Sat)</span>
            </div>
            <span class="inline-flex items-center px-2 py-0.5 rounded text-[10px] font-sans font-bold bg-zinc-800 text-zinc-400 border border-zinc-700/80">
              公演終了
            </span>
          </div>
          <div class="text-right">
            <span class="font-display font-extrabold text-sm sm:text-base tracking-wider text-zinc-400">CHIBA</span>
            <span class="block sm:inline sm:ml-2 text-xs text-zinc-500">KASHIWA PALOOZA</span>
          </div>
        </div>

        <!-- 2. SENDAI (公演終了) -->
        <div class="flex items-center justify-between px-4 py-3.5 sm:px-5 bg-zinc-950/50 opacity-60">
          <div class="flex flex-wrap items-center gap-2 sm:gap-3">
            <div class="flex items-baseline gap-2">
              <span class="font-condensed font-bold text-base sm:text-lg tracking-wide text-zinc-400 line-through decoration-zinc-600">2026.9.19</span>
              <span class="text-[11px] font-display font-bold text-zinc-600">(Sat)</span>
            </div>
            <span class="inline-flex items-center px-2 py-0.5 rounded text-[10px] font-sans font-bold bg-zinc-800 text-zinc-400 border border-zinc-700/80">
              公演終了
            </span>
          </div>
          <div class="text-right">
            <span class="font-display font-extrabold text-sm sm:text-base tracking-wider text-zinc-400">SENDAI</span>
            <span class="block sm:inline sm:ml-2 text-xs text-zinc-500">enn2nd</span>
          </div>
        </div>

        <!-- 3. NAGOYA (公演終了) -->
        <div class="flex items-center justify-between px-4 py-3.5 sm:px-5 bg-zinc-950/50 opacity-60">
          <div class="flex flex-wrap items-center gap-2 sm:gap-3">
            <div class="flex items-baseline gap-2">
              <span class="font-condensed font-bold text-base sm:text-lg tracking-wide text-zinc-400 line-through decoration-zinc-600">2026.9.26</span>
              <span class="text-[11px] font-display font-bold text-zinc-600">(Sat)</span>
            </div>
            <span class="inline-flex items-center px-2 py-0.5 rounded text-[10px] font-sans font-bold bg-zinc-800 text-zinc-400 border border-zinc-700/80">
              公演終了
            </span>
          </div>
          <div class="text-right">
            <span class="font-display font-extrabold text-sm sm:text-base tracking-wider text-zinc-400">NAGOYA</span>
            <span class="block sm:inline sm:ml-2 text-xs text-zinc-500">X-HALL -ZEN-</span>
          </div>
        </div>

        <!-- 4. OSAKA (公演終了) -->
        <div class="flex items-center justify-between px-4 py-3.5 sm:px-5 bg-zinc-950/50 opacity-60">
          <div class="flex flex-wrap items-center gap-2 sm:gap-3">
            <div class="flex items-baseline gap-2">
              <span class="font-condensed font-bold text-base sm:text-lg tracking-wide text-zinc-400 line-through decoration-zinc-600">2026.10.10</span>
              <span class="text-[11px] font-display font-bold text-zinc-600">(Sat)</span>
            </div>
            <span class="inline-flex items-center px-2 py-0.5 rounded text-[10px] font-sans font-bold bg-zinc-800 text-zinc-400 border border-zinc-700/80">
              公演終了
            </span>
          </div>
          <div class="text-right">
            <span class="font-display font-extrabold text-sm sm:text-base tracking-wider text-zinc-400">OSAKA</span>
            <span class="block sm:inline sm:ml-2 text-xs text-zinc-500">ROCKTOWN</span>
          </div>
        </div>

        <!-- 5. HIROSHIMA (公演終了) -->
        <div class="flex items-center justify-between px-4 py-3.5 sm:px-5 bg-zinc-950/50 opacity-60">
          <div class="flex flex-wrap items-center gap-2 sm:gap-3">
            <div class="flex items-baseline gap-2">
              <span class="font-condensed font-bold text-base sm:text-lg tracking-wide text-zinc-400 line-through decoration-zinc-600">2026.10.12</span>
              <span class="text-[11px] font-display font-bold text-zinc-600">(Mon)</span>
            </div>
            <span class="inline-flex items-center px-2 py-0.5 rounded text-[10px] font-sans font-bold bg-zinc-800 text-zinc-400 border border-zinc-700/80">
              公演終了
            </span>
          </div>
          <div class="text-right">
            <span class="font-display font-extrabold text-sm sm:text-base tracking-wider text-zinc-400">HIROSHIMA</span>
            <span class="block sm:inline sm:ml-2 text-xs text-zinc-500">Yise</span>
          </div>
        </div>

        <!-- 6. SHIZUOKA (公演終了) -->
        <div class="flex items-center justify-between px-4 py-3.5 sm:px-5 bg-zinc-950/50 opacity-60">
          <div class="flex flex-wrap items-center gap-2 sm:gap-3">
            <div class="flex items-baseline gap-2">
              <span class="font-condensed font-bold text-base sm:text-lg tracking-wide text-zinc-400 line-through decoration-zinc-600">2026.10.24</span>
              <span class="text-[11px] font-display font-bold text-zinc-600">(Sat)</span>
            </div>
            <span class="inline-flex items-center px-2 py-0.5 rounded text-[10px] font-sans font-bold bg-zinc-800 text-zinc-400 border border-zinc-700/80">
              公演終了
            </span>
          </div>
          <div class="text-right">
            <span class="font-display font-extrabold text-sm sm:text-base tracking-wider text-zinc-400">SHIZUOKA</span>
            <span class="block sm:inline sm:ml-2 text-xs text-zinc-500">LIVE ROXY SHIZUOKA</span>
          </div>
        </div>

        <!-- 7. FUKUOKA (公演終了) -->
        <div class="flex items-center justify-between px-4 py-3.5 sm:px-5 bg-zinc-950/50 opacity-60">
          <div class="flex flex-wrap items-center gap-2 sm:gap-3">
            <div class="flex items-baseline gap-2">
              <span class="font-condensed font-bold text-base sm:text-lg tracking-wide text-zinc-400 line-through decoration-zinc-600">2026.11.7</span>
              <span class="text-[11px] font-display font-bold text-zinc-600">(Sat)</span>
            </div>
            <span class="inline-flex items-center px-2 py-0.5 rounded text-[10px] font-sans font-bold bg-zinc-800 text-zinc-400 border border-zinc-700/80">
              公演終了
            </span>
          </div>
          <div class="text-right">
            <span class="font-display font-extrabold text-sm sm:text-base tracking-wider text-zinc-400">FUKUOKA</span>
            <span class="block sm:inline sm:ml-2 text-xs text-zinc-500">LIVE HOUSE evoL</span>
          </div>
        </div>

        <!-- 8. HOKKAIDO (公演終了) -->
        <div class="flex items-center justify-between px-4 py-3.5 sm:px-5 bg-zinc-950/50 opacity-60">
          <div class="flex flex-wrap items-center gap-2 sm:gap-3">
            <div class="flex items-baseline gap-2">
              <span class="font-condensed font-bold text-base sm:text-lg tracking-wide text-zinc-400 line-through decoration-zinc-600">2026.11.14</span>
              <span class="text-[11px] font-display font-bold text-zinc-600">(Sat)</span>
            </div>
            <span class="inline-flex items-center px-2 py-0.5 rounded text-[10px] font-sans font-bold bg-zinc-800 text-zinc-400 border border-zinc-700/80">
              公演終了
            </span>
          </div>
          <div class="text-right">
            <span class="font-display font-extrabold text-sm sm:text-base tracking-wider text-zinc-400">HOKKAIDO</span>
            <span class="block sm:inline sm:ml-2 text-xs text-zinc-500">Pigsty</span>
          </div>
        </div>

        <!-- 9. TOKYO (Band Set / TOUR FINAL) -->
        <div class="relative flex items-center justify-between px-4 py-4 sm:px-5 bg-gradient-to-r from-brand-orange/15 via-brand-orange/5 to-transparent">
          <div>
            <span class="inline-block text-[10px] font-display font-black uppercase tracking-widest px-2 py-0.5 rounded bg-brand-orange text-black mb-1">
              BAND SET
            </span>
            <div class="flex items-baseline gap-2.5 sm:gap-3.5">
              <span class="font-condensed font-bold text-lg sm:text-xl tracking-wide text-white">2027.1.29</span>
              <span class="text-xs font-display font-bold text-brand-orange">(Fri)</span>
            </div>
          </div>
          <div class="text-right">
            <span class="font-display font-black text-base sm:text-lg tracking-wider text-brand-orange">TOKYO</span>
            <span class="block text-xs font-medium text-zinc-200 mt-0.5">HULIC HALL TOKYO</span>
          </div>
        </div>
      </div>
    </section>

    <!-- シェア / URLコピー アクション -->
    <div class="mt-8 flex justify-center">
      <button
        type="button"
        onclick="copyPageUrl()"
        class="inline-flex items-center gap-2 px-5 py-2.5 rounded-full bg-zinc-900 hover:bg-zinc-800 active:scale-95 border border-zinc-700/80 text-xs font-medium text-zinc-300 hover:text-white transition-all shadow-md"
      >
        <svg class="w-4 h-4 text-brand-orange" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z" />
        </svg>
        <span>このページのURLをコピーしてシェア</span>
      </button>
    </div>

    <!-- フッター -->
    <footer class="mt-10 pt-6 border-t border-zinc-800/70 text-center">
      <p class="font-display font-bold text-xs tracking-widest text-zinc-500 uppercase">
        HASETOMO. ONE MAN LIVE TOUR 2026 ~ REVOLUTION ~
      </p>
      <p class="text-[11px] text-zinc-600 mt-1.5">
        &copy; 2026 HASETOMO. All Rights Reserved.
      </p>
    </footer>
  </main>

  <!-- トースト通知（URLコピー完了時） -->
  <div
    id="copy-toast"
    role="status"
    aria-live="polite"
    class="fixed bottom-6 left-1/2 -translate-x-1/2 z-50 pointer-events-none opacity-0 translate-y-3 transition-all duration-300"
  >
    <div class="flex items-center gap-2 px-4 py-2.5 rounded-full bg-zinc-900/95 border border-brand-orange/60 text-white text-xs font-medium shadow-2xl backdrop-blur-md">
      <svg class="w-4 h-4 text-brand-orange shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7" />
      </svg>
      <span>URLをクリップボードにコピーしました</span>
    </div>
  </div>

  <script>
    /**
     * 画像が同階層に見つからない場合のフォールバック制御
     */
    function handleImageError(imgElement) {
      imgElement.classList.add('hidden');
      const fallback = document.getElementById('image-fallback-banner');
      if (fallback) {
        fallback.classList.remove('hidden');
      }
    }

    /**
     * プレビュー環境でローカル画像を選択して確認できるようにするヘルパー
     */
    function previewLocalFile(event) {
      const file = event.target.files && event.target.files[0];
      if (!file) return;

      const reader = new FileReader();
      reader.onload = function(e) {
        const imgElement = document.getElementById('hero-poster-img');
        const fallback = document.getElementById('image-fallback-banner');
        if (imgElement && e.target && e.target.result) {
          imgElement.src = e.target.result;
          imgElement.classList.remove('hidden');
          if (fallback) fallback.classList.add('hidden');
        }
      };
      reader.readAsDataURL(file);
    }

    /**
     * 現在のページURLをクリップボードへコピーし、トースト通知を表示
     */
    let toastTimer = null;
    function copyPageUrl() {
      const urlToCopy = window.location.href;
      const tempInput = document.createElement('textarea');
      tempInput.value = urlToCopy;
      tempInput.setAttribute('readonly', '');
      tempInput.style.position = 'absolute';
      tempInput.style.left = '-9999px';
      document.body.appendChild(tempInput);
      tempInput.select();

      try {
        document.execCommand('copy');
        showToast();
      } catch (err) {
        console.error('URLのコピーに失敗しました:', err);
      } finally {
        document.body.removeChild(tempInput);
      }
    }

    function showToast() {
      const toast = document.getElementById('copy-toast');
      if (!toast) return;

      toast.classList.remove('opacity-0', 'translate-y-3');
      toast.classList.add('opacity-100', 'translate-y-0');

      if (toastTimer) clearTimeout(toastTimer);
      toastTimer = setTimeout(() => {
        toast.classList.remove('opacity-100', 'translate-y-0');
        toast.classList.add('opacity-0', 'translate-y-3');
      }, 2600);
    }
  </script>
</body>
</html>
