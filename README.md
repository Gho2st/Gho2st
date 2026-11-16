# Dominik Jojczyk

**Full-stack developer z Krakowa.** Robię aplikacje webowe w Next.js i TypeScript: od bazy danych, przez API, po wdrożenie. Głównie dla małych firm. Kilka z nich działa na produkcji i sam je utrzymuję.

📍 Kraków / zdalnie · Biorę zlecenia i chętnie dołączę do ciekawego projektu.

---

## Projekty

### 🛒 E-commerce

**[tresetmob](https://github.com/Gho2st/tresetmob)**: sklep z odzieżą w całości w TypeScript.
`Next.js 16` `Server Actions` `Prisma` `Neon` `NextAuth` `HotPay`
- Ceny i sumę zamówienia liczy serwer, nie przeglądarka.
- Webhook płatności działa w transakcji, więc powtórzone powiadomienie nie zdejmie towaru ze stanu dwa razy.
- Najniższa cena z 30 dni (Omnibus) liczona z historii cen.

**[pantofle-karpaty](https://github.com/Gho2st/pantofle-karpaty)**: sklep producenta kapci · [pantofle-karpaty.pl](https://pantofle-karpaty.pl)
`Next.js` `Prisma` `Stripe` `InPost` `AWS S3`
- Stripe Checkout z webhookiem, paczkomaty InPost, zdjęcia na S3.
- 35 endpointów API i panel admina.
- Nocne zadania cron aktualizują ceny i zwalniają towar z nieopłaconych zamówień.

### 🌐 Strony i aplikacje

**[muszynova](https://github.com/Gho2st/muszynova)**: strona parku rekreacyjnego w 5 językach · [muszynova.pl](https://muszynova.pl)
`Next.js` `next-intl` `Zod` `DeepSeek`
- Tłumaczone adresy URL, blog tłumaczony automatycznie przez AI.
- API rezerwacji stolików: walidacja Zod, wykrywanie kolizji terminów, jedna obsługa błędów mapująca wyjątki na kody HTTP.

**[agent-zdrowie](https://github.com/Gho2st/agent-zdrowie)**: moja praca inżynierska · [agent-zdrowie.vercel.app](https://agent-zdrowie.vercel.app)
`Next.js` `GPT-4o` `NextAuth`
- Dziennik pomiarów: cukier, ciśnienie, waga, tętno.
- Czat AI, który zna dane użytkownika i normy dla jego wieku.
- Logowanie Google, raport PDF.

### ⚙️ Backend i narzędzia

**[stock-market-demo](https://github.com/Gho2st/stock-market-demo)**: symulator giełdy w Go.
`Go` `PostgreSQL` `Docker`
- Kilka replik za load balancerem na wspólnym Postgresie; wyłączenie jednej nie zatrzymuje usługi.
- Każda operacja trafia do niezmiennego audit logu.
- Start jednym `docker compose up`.

**[uk-energy-backend](https://github.com/Gho2st/uk-energy-backend) / [uk-energy-frontend](https://github.com/Gho2st/uk-energy-frontend)**: najlepsze godziny ładowania auta elektrycznego.
`Express` `Next.js` `TypeScript` `Vitest` `Docker` `Render`
- Wyznacza okno z największym udziałem czystej energii w brytyjskiej sieci (Carbon Intensity API), algorytmem przesuwanego okna.
- Testy w Vitest i React Testing Library.

**[bot-skarbowy](https://github.com/Gho2st/bot-skarbowy)**: łowca okazji na licytacjach Skarbu Państwa.
`Python` `GitHub Actions`
- Codziennie przegląda pojazdy na rządowym portalu eLicytacje KAS przez jego API.
- Wysyła mailem tylko oferty do 50% wartości szacunkowej (wolna ręka do 40%), z odległością od Krakowa i linkiem do kalendarza.

### 🏢 Strony dla firm

[wesolewygibasy.pl](https://wesolewygibasy.pl) (sieć żłobków, blog z panelem admina) · [wolaktattoo.pl](https://wolaktattoo.pl) · [domzaproszen.pl](https://domzaproszen.pl) · [barbarapiekos.pl](https://barbarapiekos.pl)

---

## Stack

| | |
|---|---|
| **Języki** | TypeScript, JavaScript, Python, Go |
| **Web** | Next.js (App Router, Server Actions), React, Tailwind CSS, Node.js, Express |
| **Dane** | PostgreSQL (Neon), Prisma, SQLite, AWS S3 |
| **Integracje** | Stripe, HotPay, InPost, NextAuth (Google, Facebook), OpenAI, Gemini |
| **Wdrożenia i testy** | Docker, GitHub Actions, Vercel, Render, VPS, Vitest |
