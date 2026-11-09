<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a8d8f0,100:f8bbd0&height=130&section=header&fontSize=0" width="100%" />

# Maxine Palm

### Software Engineer · C# / .NET · Kotlin · React · Azure

Secure full-stack apps, IoT hardware and Android

**BCIS graduate. Available from 1 December 2026 and open to junior software engineer roles.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-7DB9E8?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maxine-palm-4751a530b/)
[![Email](https://img.shields.io/badge/Email-F4A6C6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maxinepalm450@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:a8d8f0,100:f8bbd0&height=3" width="100%" />

## About

I'm a BCIS graduate in Application Development (Top 10 Achiever) from Emeris. I build things that work, then make them secure. My projects sit where application security, IoT hardware and mobile meet.

| | |
|---|---|
| 🎯 **Focus** | Secure full-stack apps, IoT and Android |
| 💻 **Main stack** | C#, .NET, ASP.NET Core, Kotlin, React, TypeScript, Azure |
| 📚 **Learning** | Arduino and embedded systems |
| 💬 **Ask me about** | .NET, IoT, security and offline-first design |
| 🐱 **Fun fact** | My cat is called Flash |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:a8d8f0,100:f8bbd0&height=3" width="100%" />

## Featured Projects

### 💧 SmartHydro: Offline-First Hydroponics Monitoring

An IoT monitoring and control system for growing crops and fodder in remote, water-scarce areas, built for Emeris and its rural outreach work in Namibia. Team project with six developers.

**My part:** [one or two sentences on exactly what you built, e.g. the Kotlin app screens, API endpoints or ESP32 firmware]

- **Control:** live pH, EC, temperature, humidity, light and water level, with remote control of pumps, fans and dosing over SignalR
- **Offline first:** sensor boxes pair over their own Wi-Fi hotspot and the Android app caches data in Room
- **Alerts and edge ML:** a rule engine raises Warning and Critical alerts, and Random Forest classifiers run on the ESP32 boxes with manual override
- **Security:** PBKDF2 hashing, two-step sign-in, role-based access, rate limiting and CI/CD to Azure

<img src="https://skillicons.dev/icons?i=dotnet,kotlin,postgres,azure,arduino,githubactions&theme=dark" />

[![Code](https://img.shields.io/badge/Code-7DB9E8?style=flat-square&logo=github&logoColor=white)](https://github.com/EMECPE/insy7315-2026-wil-kylelotter) [![Live web app](https://img.shields.io/badge/Live_web_app-F4A6C6?style=flat-square&logo=microsoftazure&logoColor=white)](https://smarthydro-hyhxfuhcdne7cxhx.southafricanorth-01.azurewebsites.net)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:a8d8f0,100:f8bbd0&height=3" width="100%" />

### 💓 PulseLink: Remote Patient Monitoring

An IoT tele-cardiology platform that captures ECG and heart-rate data from a wearable sensor and streams it to a clinical Android app in real time. Co-authored with [Cameron van Heerden](https://github.com/EMECPE).

**My part:** [one or two sentences on what you built]

- **Hardware:** AD8232 ECG sensor on an ESP32-C3, sampling at 250 Hz with Pan-Tompkins R-peak detection for live BPM
- **Backend:** ASP.NET Core REST API on Azure with Firebase Auth, Realtime Database and push alerts
- **Mobile:** Kotlin MVVM app with a 60 FPS ECG view, rhythm strips and an offline-first sync engine
- **Security and DevOps:** AES-256 GCM storage through Android Keystore, TLS in transit, and a GitHub Actions pipeline that tests and builds APK and AAB files

<img src="https://skillicons.dev/icons?i=kotlin,androidstudio,dotnet,azure,firebase,arduino,githubactions&theme=dark" />

[![Code](https://img.shields.io/badge/Code-7DB9E8?style=flat-square&logo=github&logoColor=white)](https://github.com/EMECPE/prog7314-2026-poe-pulselink)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:a8d8f0,100:f8bbd0&height=3" width="100%" />

### 🔐 HustleHub+: Secure Freelance Marketplace

A full-stack marketplace where freelancers list gigs and clients book them, built secure-by-design as a four-person team project.

**My part:** frontend dashboards, role-based route guards, input sanitisation, member profiles and frontend testing.

- **Auth and access control:** email-verified sign-up, JWT sessions with token revocation, Client, Freelancer and Admin roles, and per-record ownership checks
- **Hardening:** sanitisation, rate limiting, Helmet security headers and CSP with violation reporting
- **Dashboards:** income charts and tax estimates for freelancers, spending for clients, overview for admins
- **Testing:** 105 Vitest tests, plus 49 Postman requests (82 assertions) run through Newman

<img src="https://skillicons.dev/icons?i=mongodb,express,react,nodejs,ts,vite&theme=dark" />

[![Code](https://img.shields.io/badge/Code-7DB9E8?style=flat-square&logo=github&logoColor=white)](https://github.com/EMECPE/insy7314-2026-poe-kylelotter)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:a8d8f0,100:f8bbd0&height=3" width="100%" />

### 🌐 Smart-X IoT Mesh: Real-Time Telemetry Gateway

A simulated ESP32 telemetry gateway. A React app and a .NET console client talk to an ASP.NET Core API that queues, classifies and stores sensor readings, with a command stream, Undo and a predictive suggestion engine. Solo project.

- **Data structures in C#:** a priority queue for critical readings, a command stack that powers Undo, O(1) device lookup and a hand-built bounded linked list
- **Prediction:** a Markov chain and linear regression warn before a sensor goes critical
- **Docker:** runs with SQL Server in containers, with Swagger docs for every endpoint

<img src="https://skillicons.dev/icons?i=cs,dotnet,react,vite,docker&theme=dark" />

[![Code](https://img.shields.io/badge/Code-7DB9E8?style=flat-square&logo=github&logoColor=white)](https://github.com/EMECPE/prog7312-2026-poe-maxinepalm)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:a8d8f0,100:f8bbd0&height=3" width="100%" />

## Tech Stack

<img src="https://skillicons.dev/icons?i=cs,kotlin,java,py,ts,js&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=dotnet,react,vite,nodejs,express&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=azure,postgres,mongodb,firebase,docker&theme=dark" /><br>
<img src="https://skillicons.dev/icons?i=androidstudio,arduino,git,github,githubactions,postman,visualstudio&theme=dark" />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:a8d8f0,100:f8bbd0&height=3" width="100%" />

## Let's Connect

I'm looking for a junior software engineer role where I can build secure, useful products that help people. If that sounds like your team, I'd love to talk.

[LinkedIn](https://www.linkedin.com/in/maxine-palm-4751a530b/) · [maxinepalm450@gmail.com](mailto:maxinepalm450@gmail.com)

<br>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a8d8f0,100:f8bbd0&height=100&section=footer&fontSize=0" width="100%" />
</div>
