<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Payment Successful - MapoZi WiFi</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Continuous hue cycle animation for multicolor glow */
    @keyframes rainbowGlow {
      0% { filter: hue-rotate(0deg) drop-shadow(0 0 6px rgba(255, 0, 128, 0.8)); }
      33% { filter: hue-rotate(120deg) drop-shadow(0 0 6px rgba(0, 255, 128, 0.8)); }
      66% { filter: hue-rotate(240deg) drop-shadow(0 0 6px rgba(0, 128, 255, 0.8)); }
      100% { filter: hue-rotate(360deg) drop-shadow(0 0 6px rgba(255, 0, 128, 0.8)); }
    }

    /* Individual sparkle pulse animation */
    @keyframes sparklePulse {
      0%, 100% { opacity: 0.2; transform: scale(0.8); }
      50% { opacity: 1; transform: scale(1.3); }
    }

    .rainbow-star-container {
      animation: rainbowGlow 6s linear infinite;
    }

    .sparkle-1 { animation: sparklePulse 1.2s infinite ease-in-out; }
    .sparkle-2 { animation: sparklePulse 1.8s infinite ease-in-out 0.3s; }
    .sparkle-3 { animation: sparklePulse 1.5s infinite ease-in-out 0.6s; }
    .sparkle-4 { animation: sparklePulse 2.0s infinite ease-in-out 0.9s; }
  </style>
</head>
<body class="bg-[#dbe7f5] flex items-center justify-center min-h-screen p-4 font-sans">

  <div class="bg-white rounded-[32px] shadow-xl border border-slate-100 w-full max-w-[420px] p-6 text-center space-y-5">
    
    <div class="flex flex-col items-center justify-center pt-2">
      <div class="flex items-center justify-center space-x-1">
        <svg class="w-16 h-12 text-[#0052cc]" viewBox="0 0 100 80" fill="currentColor">
          <path d="M50 15 C30 15 15 30 10 45 C15 35 30 25 50 25 C70 25 85 35 90 45 C85 30 70 15 50 15 Z" opacity="0.3" />
          <path d="M20 65 L35 25 L50 55 L65 25 L80 65 H68 L65 55 L50 25 L35 55 L32 65 Z" />
          <circle cx="50" cy="12" r="4" />
          <path d="M40 8 A12 12 0 0 1 60 8" stroke="currentColor" stroke-width="3" fill="none" stroke-linecap="round" />
          <path d="M32 2 A22 22 0 0 1 68 2" stroke="currentColor" stroke-width="3" fill="none" stroke-linecap="round" />
        </svg>
      </div>
      <h1 class="text-3xl font-black text-[#002b66] tracking-wider -mt-1">MAPO<span class="text-[#0066ff]">Z</span><span class="text-[#0066ff] text-2xl">i</span></h1>
      <div class="flex items-center gap-2 w-32 my-1">
        <div class="h-[1.5px] bg-[#0066ff] flex-1"></div>
        <span class="text-xs font-semibold text-[#0066ff] tracking-widest uppercase">WiFi</span>
        <div class="h-[1.5px] bg-[#0066ff] flex-1"></div>
      </div>
    </div>

    <div class="border border-slate-200 rounded-[24px] p-5 bg-white space-y-4 shadow-sm">
      
      <div class="flex justify-center">
        <div class="w-12 h-12 rounded-full border-[3px] border-[#00a859] flex items-center justify-center text-[#00a859]">
          <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="3" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" />
          </svg>
        </div>
      </div>

      <div class="space-y-1">
        <h2 class="text-2xl font-extrabold text-[#00a859]">Payment Successful!</h2>
        <p class="text-slate-700 text-sm font-medium leading-tight">
          Thank you for choosing Mapozi WiFi.<br>
          <span class="text-slate-600 font-normal">Your internet access is now active.</span>
        </p>
      </div>

      <div class="rounded-xl overflow-hidden bg-black aspect-[4/3] flex items-center justify-center relative border border-slate-800">
        <div class="w-full h-full rainbow-star-container">
          <svg class="w-full h-full" viewBox="0 0 300 220" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect width="300" height="220" fill="black"/>
            
            <path class="sparkle-1" d="M150 20 L180 85 L250 90 L195 135 L215 200 L150 160 L85 200 L105 135 L50 90 L120 85 Z" 
                  stroke="url(#rainbow-grad-1)" stroke-width="4" stroke-dasharray="3 6" stroke-linecap="round" />
            <path class="sparkle-3" d="M150 15 L182 82 L255 88 L198 138 L218 205 L150 163 L82 205 L102 138 L45 88 L118 82 Z" 
                  stroke="url(#rainbow-grad-2)" stroke-width="2" stroke-dasharray="2 8" stroke-linecap="round" />

            <circle class="sparkle-1" cx="150" cy="20" r="3" fill="#ff007f" />
            <circle class="sparkle-2" cx="250" cy="90" r="4" fill="#ff00e0" />
            <circle class="sparkle-4" cx="85" cy="200" r="3.5" fill="#ff00aa" />
            
            <circle class="sparkle-3" cx="180" cy="85" r="3.5" fill="#00f0ff" />
            <circle class="sparkle-2" cx="215" cy="200" r="4" fill="#0088ff" />
            <circle class="sparkle-1" cx="50" cy="90" r="3" fill="#00e5ff" />

            <circle class="sparkle-4" cx="195" cy="135" r="3" fill="#ffd700" />
            <circle class="sparkle-2" cx="150" cy="160" r="4" fill="#ffea00" />
            <circle class="sparkle-3" cx="105" cy="135" r="3.5" fill="#ffb700" />

            <circle class="sparkle-1" cx="120" cy="85" r="3.5" fill="#00ff66" />
            <circle class="sparkle-3" cx="165" cy="50" r="2.5" fill="#00ffaa" />

            <text x="150" y="110" text-anchor="middle" fill="url(#gold-text)" font-family="serif" font-size="22" font-weight="bold" letter-spacing="2">THANK</text>
            <text x="150" y="138" text-anchor="middle" fill="url(#gold-text)" font-family="serif" font-size="22" font-weight="bold" letter-spacing="2">YOU!</text>
            
            <defs>
              <linearGradient id="rainbow-grad-1" x1="0%" y1="0%" x2="100%" y2="100%">
                <stop offset="0%" stop-color="#ff007f" />
                <stop offset="33%" stop-color="#00f0ff" />
                <stop offset="66%" stop-color="#00ff66" />
                <stop offset="100%" stop-color="#ffd700" />
              </linearGradient>
              
              <linearGradient id="rainbow-grad-2" x1="100%" y1="0%" x2="0%" y2="100%">
                <stop offset="0%" stop-color="#ffb700" />
                <stop offset="50%" stop-color="#ff00e0" />
                <stop offset="100%" stop-color="#0088ff" />
              </linearGradient>

              <linearGradient id="gold-text" x1="0%" y1="0%" x2="0%" y2="100%">
                <stop offset="0%" stop-color="#ffe680" />
                <stop offset="50%" stop-color="#ffb700" />
                <stop offset="100%" stop-color="#caa02c" />
              </linearGradient>
            </defs>
          </svg>
        </div>
      </div>

      <a href="#" class="w-full bg-[#0055ff] hover:bg-[#0044cc] text-white font-semibold py-3 px-4 rounded-xl flex items-center justify-center gap-2 transition-colors duration-150 text-base">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
          <circle cx="12" cy="12" r="10" />
          <path stroke-linecap="round" d="M2 12h20M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z" />
        </svg>
        <span>Continue to Internet</span>
      </a>

      <div class="bg-[#e8f1fd] border border-[#d0e2fb] rounded-xl p-3.5 flex items-center gap-3 text-left">
        <div class="text-[#0055ff] pl-1">
          <svg class="w-9 h-9" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 18v-6a9 9 0 0118 0v6M3 18a2 2 0 002 2h1a2 2 0 002-2v-3a2 2 0 00-2-2H3v5zm18 0a2 2 0 01-2 2h-1a2 2 0 01-2-2v-3a2 2 0 012-2h3v5z" />
          </svg>
        </div>
        <div class="space-y-0.5">
          <h3 class="text-[#0044cc] font-bold text-sm leading-tight">Need Help?</h3>
          <p class="text-xs text-slate-600">Contact us on WhatsApp or Call</p>
          <div class="text-[#0044cc] font-extrabold text-base flex items-center gap-1.5 pt-0.5">
            <svg class="w-4 h-4 fill-current text-[#25d366]" viewBox="0 0 24 24">
              <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981z"/>
            </svg>
            <span>0111 442 002</span>
          </div>
        </div>
      </div>

    </div>

    <p class="text-[#0055ff] text-xs font-bold tracking-wide pb-1">
      Fast • Affordable • Reliable
    </p>

  </div>

</body>
</html>
