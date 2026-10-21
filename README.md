Dominik Jojczyk

Full-stack developer z Krakowa. Robię aplikacje webowe w Next.js i TypeScript: od bazy danych, przez API, po wdrożenie. Głównie dla małych firm. Kilka z nich działa na produkcji i sam je utrzymuję.

Projekty

tresetmob: sklep z odzieżą w całości w TypeScript. Next.js 16 (Server Actions), Prisma + Neon, NextAuth, płatności HotPay. Ceny i sumę liczy serwer, nie przeglądarka. Webhook płatności działa w transakcji, więc powtórzone powiadomienie nie zdejmie towaru ze stanu dwa razy. Najniższa cena z 30 dni (Omnibus) liczona z historii cen. Demo

pantofle-karpaty: sklep producenta kapci, pantofle-karpaty.pl. Next.js, Prisma, Stripe Checkout z webhookiem, paczkomaty InPost, zdjęcia na S3, 35 endpointów API, panel admina. Nocne zadania cron aktualizują ceny i zwalniają towar z nieopłaconych zamówień.

muszynova: strona parku rekreacyjnego w 5 językach, muszynova.pl. next-intl z tłumaczonymi adresami, blog tłumaczony automatycznie przez AI (DeepSeek). API rezerwacji stolików w TypeScript: walidacja Zod, wykrywanie kolizji terminów, jedna obsługa błędów mapująca wyjątki na kody HTTP.

uk-energy-backend / uk-energy-frontend: wyznacza godziny ładowania auta elektrycznego z największym udziałem czystej energii w brytyjskiej sieci (Carbon Intensity API). Backend w Express, frontend w Next.js + TypeScript, algorytm przesuwanego okna, testy w Vitest i React Testing Library, Docker, Render.

stock-market-demo: symulator giełdy w Go. Kilka replik za load balancerem na wspólnym Postgresie, więc wyłączenie jednej nie zatrzymuje usługi. Każda operacja trafia do niezmiennego audit logu. Start jednym docker compose up.

bot-skarbowy: bot w Pythonie, który codziennie przegląda licytacje Skarbu Państwa. Wyciąga dane z HTML, PDF i DOCX przez Gemini i wysyła mailem tylko oferty z ceną do 50% wartości rynkowej. Działa na GitHub Actions.

agent-zdrowie: moja praca inżynierska. Dziennik pomiarów (cukier, ciśnienie, waga, tętno) z czatem AI (GPT-4o), który zna dane użytkownika i normy dla jego wieku. Logowanie Google, raport PDF. agent-zdrowie.vercel.app

Strony dla firm: wesolewygibasy.pl (sieć żłobków, blog z panelem admina), wolaktattoo.pl, domzaproszen.pl, barbarapiekos.pl.

Stack
Języki: TypeScript, JavaScript, Python, Go
Web: Next.js (App Router, Server Actions), React, Tailwind CSS, Node.js, Express
Dane: PostgreSQL (Neon), Prisma, SQLite, AWS S3
Integracje: Stripe, HotPay, InPost, NextAuth (Google, Facebook), OpenAI, Gemini
Wdrożenia i testy: Docker, GitHub Actions, Vercel, Render, VPS, Vitest

Kraków / zdalnie. Biorę zlecenia i chętnie dołączę do ciekawego projektu.
