# Cześć! 👋

**Full-stack Developer** — buduję produkcyjne aplikacje webowe, narzędzia AI i backendy o wysokiej dostępności. Od pomysłu i architektury, przez kod, aż po deploy i utrzymanie na własnej infrastrukturze.

---

### 🚀 O mnie

Programuję **end-to-end**: frontend, backend, bazy danych, integracje, automatyzacja i AI — a potem sam to wdrażam i utrzymuję.

Pracuję w wielu językach (**TypeScript / JavaScript, Python, Go, C++**) i dobieram narzędzie do problemu, a nie odwrotnie. Najbardziej lubię projekty, które realnie rozwiązują problem biznesowy albo upraszczają komuś codzienność — i które trafiają na produkcję, a nie do szuflady z dema.

Stawiam na **wydajność, bezpieczeństwo, testy i czytelną architekturę**. Wdrażam zarówno na platformach (Vercel, Render), jak i **samodzielnie na VPS** (Docker, reverse proxy, CI/CD).

---

### 🛠️ Wybrane projekty

**🛒 [pantofle-karpaty](https://github.com/Gho2st/pantofle-karpaty)** — *Next.js 14 · Stripe · InPost · Prisma · NeonDB*
Pełnowymiarowa platforma e-commerce dla realnego producenta obuwia, działająca na żywo ([pantoflekarpaty.pl](https://pantoflekarpaty.pl)). Cały lejek zakupowy: produkty → koszyk (localStorage + sync z serwerem) → wybór paczkomatu → płatność online → panel klienta i zamówień. Mobile-first, optymalizacja Core Web Vitals oraz SEO (SSG + SSR), bezpieczna autoryzacja i zarządzanie danymi klientów.

**📈 [stock-market-demo](https://github.com/Gho2st/stock-market-demo)** — *Go · PostgreSQL · Docker*
Symulator giełdy zaprojektowany pod **wysoką dostępność**: działa jako wiele replik za load balancerem, współdzielących jedną bazę Postgres — ubicie jednej repliki nie przerywa działania usługi. Każda operacja trafia do **niezmiennego audit logu**. Uruchamiany jednym `docker compose up`, lokalnie działa też na wbudowanym SQLite bez zależności zewnętrznych.

**🚗 [bot-skarbowy](https://github.com/Gho2st/bot-skarbowy)** — *Python · Google Gemini · GitHub Actions*
Bot działający **produkcyjnie**, który codziennie skanuje licytacje Skarbu Państwa, a następnie za pomocą Gemini AI wyciąga ustrukturyzowane dane (marka, model, cena, wartość, lokalizacja) z nieuporządkowanych **HTML, PDF i DOCX**. Filtruje tylko realne okazje (cena ≤ 50% wartości rynkowej), liczy odległość do wskazanej lokalizacji i wysyła powiadomienia e-mail. Uruchamiany automatycznie przez GitHub Actions.

**🧠 [agent-zdrowie](https://github.com/Gho2st/agent-zdrowie)** — *Next.js · OpenAI · Neon · Prisma*
Aplikacja do monitorowania zdrowia (cukier, ciśnienie, waga, puls) z chatbotem AI mającym dostęp do danych użytkownika i porównującym je z normami liczonymi na podstawie wieku, wagi i wzrostu. Logowanie Google (OAuth), system codziennych check-inów i streaków. Projekt powstał jako praca inżynierska.

**⚡ uk-energy ([backend](https://github.com/Gho2st/uk-energy-backend) · [frontend](https://github.com/Gho2st/uk-energy-frontend))** — *Node/Express · Next.js · TypeScript · Vitest · Docker*
Aplikacja licząca **optymalne okno ładowania EV** według udziału czystej energii w brytyjskiej sieci (dane z publicznego Carbon Intensity API). Czysto rozdzielony backend i frontend, pokryte testami (Vitest + React Testing Library), z konteneryzacją i deployem na Render.

**🧬 [Kalkulator-Tm-Sekwencji-DNA](https://github.com/Gho2st/Kalkulator-Tm-Sekwencji-DNA)** — *Python · Tkinter*
Bioinformatyczna aplikacja desktopowa: generowanie sekwencji DNA, liczenie temperatury topnienia (metody GC oraz Nearest-Neighbor) i wizualizacja składu nukleotydów. Programowanie GUI + obliczenia naukowe + wizualizacja danych.

> Więcej projektów (strony korporacyjne, podróże, lokalne biznesy) znajdziesz na [moim profilu →](https://github.com/Gho2st?tab=repositories)

---

### 💡 Co mnie wyróżnia

- Buduję **produkcyjne aplikacje**, a nie tylko dema — z deployem i utrzymaniem włącznie
- **Polyglot** — TypeScript, Python, Go, C++; dobieram język do zadania
- Projektuję pod **wysoką dostępność i skalowanie** (replikacja, load balancing, audit log)
- Mocny w **integracjach**: płatności, dostawy, AI, OAuth, geolokalizacja
- **Web scraping + LLM parsing** nieustrukturyzowanych danych (HTML / PDF / DOCX)
- Piszę **testy** i dbam o wydajność, SEO, UX oraz bezpieczeństwo
- **Samodzielny deploy** — VPS, Docker, CI/CD (GitHub Actions), Vercel, Render

---

### 🧰 Tech stack

**Języki:** TypeScript, JavaScript, Python, Go, C++

**Frontend:** Next.js (App Router), React, TypeScript, Tailwind CSS, Headless UI, Recharts

**Backend:** Next.js (API Routes, Server Components & Actions), Node.js / Express, Prisma ORM, PostgreSQL (Neon), SQLite

**AI & Automatyzacja:** Google Gemini, OpenAI, BeautifulSoup, web scraping, GitHub Actions

**DevOps & Infra:** Docker / Docker Compose, VPS, load balancing, CI/CD, Vercel, Render

**Integracje:** Stripe, InPost, NextAuth.js / OAuth, REST API

**Testy:** Vitest, React Testing Library

---

**Aktualnie otwarty na nowe wyzwania** — komercyjne projekty i współpracę przy ciekawych produktach.

📍 Kraków / zdalnie
✉️ Napisz do mnie — chętnie porozmawiam o wspólnych projektach!
