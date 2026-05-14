MediaQR Studio
B-MSAP 2026 — Novykov Yurii
Multimediálna webová služba pre generovanie QR kódov a úpravu fotografií s filtrami.

🚀 Ako spustiť
Projekt je čisto statický — žiadny backend nie je potrebný.

Skopíruj priečinok MediaQR_Studio do Projects/ v repozitári portálu
Spusti portál: python app.py
Otvor http://127.0.0.1:5000 — projekt sa zobrazí ako karta

Alebo otvor index.html priamo v prehliadači.

⚡ Funkcie
📱 QR Generátor

Generovanie QR kódu z ľubovoľného textu alebo URL
Nastavenie veľkosti (200–400px) a úrovne opravy chýb (L / M / Q / H)
6 štýlových predvolieb — Klasický, Invertovaný, Neon, Modrý, Ružový, Fialový
Vlastná farba QR kódu a pozadia (color picker)
Logo v strede QR — nahratie vlastného súboru alebo výber z predvolieb (Instagram, YouTube, Facebook, WhatsApp, TikTok, Twitter)
Stiahnutie vygenerovaného QR kódu ako PNG

🖼 Foto + Filter

Galéria ukážkových fotiek — 8 fotografií z Unsplash (Hory, Mesto, Les, Pláž, Pes, Kvety, Portrét, Noc)
Načítanie fotky cez URL alebo nahratie súboru z počítača
8 filtrov — Originál, Čiernobiely, Sépia, Negatív, Neon, Živý, Blur, Fade
Náhľad všetkých filtrov naraz pre rýchly výber
Transformácie — zrkadlenie horizontálne/vertikálne, otočenie ±90°
Nastavenie jasu, kontrastu a sýtosti (slaidery)
Zobrazenie povereného fotky v modálnom okne (plná veľkosť)
Stiahnutie fotky s aplikovaným filtrom ako PNG
QR kód automaticky odkazuje na URL fotky

🌙 Prepínanie tém

Nočná téma (predvolená) a Denná téma
Plynulý prechod medzi témami


🛠 Technológie

HTML5 / CSS3 / JavaScript — čisto statická aplikácia, beží v prehliadači
QRCode.js — generovanie QR kódov (cdnjs)
Unsplash — ukážkové fotografie (voľná licencia)
Web Canvas API — spracovanie obrázkov a export
CSS Filters — aplikovanie vizuálnych filtrov


📁 Štruktúra
MediaQR_Studio/
  index.html       — hlavná aplikácia
  thumbnail.png    — náhľad pre portál (1000×1000px)
  README.md        — tento súbor

⚠️ Poznámky

Stiahnutie fotky s filtrom funguje spoľahlivo pri nahratí súboru z počítača
Pri URL obrázkoch závisí stiahnutie od CORS politiky servera
QR kód odkazuje na URL — po naskenovaní otvorí originálnu fotku v prehliadači