# Szia, Szczuka Bendegúz vagyok! 👋

## Rólam
Elkötelezett és kommunikatív fejlesztő vagyok, aki törekszik a folyamatos tanulásra. Jelenleg Üzemmérnök-Informatikus szakot végzem az Óbudai Egyetemen, és lelkesen bővítem a tudásom és szakértelmem az IT területén.

🌱 Jelenleg a Damocles Kft-nél dolgozom és fejlesztem skilljeimet az egyetemi tanulmányaim mellett.

## ⭐ Project highlight: CodeLingo (Full‑stack + DevOps)
A **CodeLingo** egy Duolingo‑jellegű tanulóplatform, amelyet full‑stack szemlélettel fejlesztettünk (ASP.NET 8 backend + Angular frontend + Bootstrap UI).  
Live: https://codelingo.hu  
🔗 Repo: https://github.com/bprof-spec-codes/codelingo

**Szerepem:** Architect / Lead Developer – a fejlesztés technikai irányítását vittem, a rendszer felépítését és főbb döntéseit én terveztem meg, és projektmenedzsment jellegű feladatokba (prioritások, feladatok szervezése, egyeztetések) is aktívan bekapcsolódtam.
**DevOps / üzembe helyezés:** a projektet production szintre is elvittem, Debian alapú VPS-en:  
- Apache VirtualHost + Reverse Proxy (frontend + API külön eléréssel). 
- Backend futtatás systemd service-ekkel (tartós futás, újraindítás, környezetek kezelése).
- Security hardening: SSH kulcsalapú belépés, UFW tűzfal.
- HTTPS Let’s Encrypt + Certbot, tanúsítvány-megújítás automatizálása.
- CI/CD GitHub Actions-szel: build + deploy automatizálás, külön production és test környezet (GitFlow master/develop), konfigurációk kezelése GitHub Secrets-szel.

## Tapasztalat

### Bosch Robotépítő Csapatverseny (2023–2026)
- 🥇 **2025**: **1. helyezés** mind a **Sprint**, mind az **Összesített** kategóriákban egy **ESP32**-alapú robottal, amely egyedi **web interface**-t tartalmazott **monitoring** és **paraméter tuning** céljából.  
  🔗 [GitHub Repository](https://github.com/asimoq/Jerry3_ESP32_MazeSolvingRobot)
- 🏆 **2024**: Ismét **3. hely**, valamint **Mechanical Design Special Award** díj egy továbbfejlesztett **Arduino**-alapú robottal.  
  🔗 [GitHub Repository](https://github.com/asimoq/ArduinoMazeSolvingRobot)
- 🏆 **2023**: **3. helyezést** értünk el egy **Arduino**-alapú maze-solving robot segítségével.  
  🔗 [GitHub Repository](https://github.com/asimoq/ArduinoMazeSolvingRobot)
- 👨‍💻 Részt vettem a tervezésben, mechanikai kivitelezésben és programozásban minden évben.
- 🚀 Fejlesztettem a készségeimet az embedded systems, robotics, real-time diagnostics, teamwork és end-to-end project development területeken.
- 🌐 [www.teamjerry.hu](https://teamjerry.hu) – Nézd meg a weboldalt, amit a csapatunknak készítettem!

## Fejlesztői tapasztalat – kiemelt projektek

- **CodeLingo (Full‑stack + DevOps)** – Duolingo‑jellegű tanulóplatform; architect/lead developer szerepben vezettem a technikai tervezést és a fejlesztést, valamint a teljes üzembe helyezést és CI/CD-t is megvalósítottam (Debian VPS, Apache reverse proxy + VirtualHost, systemd, UFW, Let’s Encrypt/Certbot, GitHub Actions; prod + teszt környezet). [projekt](https://github.com/bprof-spec-codes/codelingo) · [live](https://codelingo.hu)

- **booking_webapp_nullpontmuhely (Nullpont Műhely – Event Booking System)** – éles, valós felhasználói flow-t kiszolgáló full‑stack webapp: jegyfoglalás valós idejű kapacitásellenőrzéssel (max. 60 fő/esemény), automatikus email visszaigazolással és admin dashboard-dal a foglalások kezelésére. Tech: Next.js 16 (App Router) + TypeScript + Bootstrap/SCSS, Next.js API Routes, Resend + React Email, JSON fájl alapú perzisztencia. [projekt](https://github.com/szczukabendeguz/booking_webapp_nullpontmuhely) · [live](https://nullpontmuhely.hu)

- **Választás2026 (Election Simulation Engine)** – kliensoldali, részletes választási szimulátor a 2026-os magyar országgyűlési választások modellezésére (106 EVK + 93 listás mandátum), a töredékszavazat‑kompenzációk és a D’Hondt szerinti listás kiosztás implementálásával. Moduláris ES6 felépítés (számítási logika, CSV adatkezelés, state, render) és körzeti “rural bias” modell a földrajzi torzítások szimulálására. [projekt](https://github.com/szczukabendeguz/Valasztas2026) · [live](https://szczukabendeguz.github.io/Valasztas2026/)

- **Jerry3_ESP32_MazeSolvingRobot (Embedded + Web diagnostics)** – ESP32‑alapú autonóm labirintus‑megoldó robot (Óbudai Egyetem “Mobile Robots in the Maze”); WiFi‑n keresztüli valós idejű hangolást és monitorozást biztosító webes felülettel (SoftAP), miközben embedded oldalon PID‑es falkövetés, Kalman‑szűrt IR szenzoradatok, RFID‑alapú navigáció és giroszkóp‑asszisztált fordulók futnak AsyncWebServer-rel. [projekt](https://github.com/szczukabendeguz/Jerry3_ESP32_MazeSolvingRobot)

- **Fullstack_BikeStore** – Angular 19 + .NET 8 Web API + EF Core (SQL Server) alapú full‑stack “bike store” alkalmazás; márkák és modellek CRUD, szűrés, statisztikák (pl. átlagár). Backend oldalon Identity + JWT, AutoMapper és Swagger, rétegezett felépítéssel (Endpoint/Logic/Data) SPA frontendlal. [projekt](https://github.com/szczukabendeguz/Fullstack_BikeStore)

- **ASP.NET_CarRental** – clean/layered architektúrájú car‑rental menedzsment rendszer: REST API + többféle kliens (ASP.NET MVC web, WPF desktop, konzol, JS kliens), SignalR alapú valós idejű kommunikációval és Swagger dokumentált API-val. Entity Framework Core + repository pattern + business logic réteg mentén épül fel. [projekt](https://github.com/szczukabendeguz/ASP.NET_CarRental)

### Damocles Kft. – IT Operations & Automation Specialist (2024 – jelenleg is)
- 🖥️ Egy kis, de dinamikus IT szolgáltató cégnél dolgozom, ahol a rugalmasság, innováció és együttműködés áll a középpontban.
- 🔧 Feladataim közé tartozik az általános IT üzemeltetés: network monitoring, szerver- és workstation-karbantartás, remote support, rendszertelepítések és konfigurációs feladatok.
- 📦 Részt veszek automation workflow fejlesztésben **PHP**, **JavaScript** és **PowerShell** segítségével az ügyféloldali folyamatok egyszerűsítésére.
- 🐳 Használom a **Docker**-t konténerizálásra, valamint segítek autómatizációs és AI eszközök fejlesztésében.
- ☁️ Tapasztalatot szereztem cloud platformokkal, mint például **Azure**.
- 🛠️ Napi szinten használom az **Atlassian stack**-et (Jira, Confluence) és kollaboratív munkafolyamatokat.
- 🤝 Erősítem problémamegoldó készségeimet, kommunikációmat, és tapasztalatot szerezek egy gyors tempójú, ügyfélorientált környezetben.

## Tanulmányok és Nyelvtudás

- 📚 **Computer Science Engineering** – Óbudai Egyetem (2022 – jelenleg is)
- 🌐 **Angol nyelv** – C1 szint
- 🇭🇺 **Magyar nyelv** – Anyanyelvi szint

## Erősségek

- ✨ Problémamegoldás
- 🤝 Csapatmunka
- 🗣️ Kommunikáció
- ⌛ Időgazdálkodás

## Hobbijaim

- 🚵‍♂️ Hegyi kerékpározás
- 🎸 Gitár és zongora játék
- 🎬 Színjátszás és rendezés
- 📷 Fotózás és filmkészítés

## Elérhetőség

- 📧 **Email**: szczukabendeguz@gmail.com  
- 🌐 **LinkedIn**: [linkedin.com/in/szczuka-bende/](https://www.linkedin.com/in/szczuka-bende/)  
- 💻 **GitHub**: [github.com/asimoq/](https://github.com/asimoq/)

Nézd meg a repóimat és projektjeimet bátran – ha érdekel az együttműködés, keress meg! 🚀
