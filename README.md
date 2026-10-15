<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FFB6E1,100:B983FF&height=220&section=header&text=Maxine%20Palm%20%E2%9C%A8&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Software%20Developer%20%7C%20Secure%20Apps%20%2B%20IoT%20%2B%20Android&descAlignY=58&descSize=18&animation=fadeIn"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&pause=1000&color=B983FF&center=true&vCenter=true&width=600&lines=Building+secure+full-stack+applications;C%23+%2F+.NET+%7C+React+%7C+Node.js;Learning+Arduino+%26+Embedded+Systems;Exploring+Android+with+Jetpack+Compose" alt="Typing SVG" />

<br><br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maxine-palm-4751a530b/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maxinepalm450@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@SalticidaeM)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/maxine_palm)

</div>

<br>

## 👋 About

I'm a third-year Software Development student who likes building things that work, and then making them secure. My coursework and personal projects sit across web security, backend APIs, IoT simulation and mobile.

- 🔐 Focused on **application security**: authentication, secure API design, and defensive coding
- 🧱 Comfortable across the stack: **ASP.NET Core**, **React/Vite**, **Node.js**, **SQL and NoSQL** databases
- 🔌 Currently learning **Arduino** and embedded systems
- 📱 Exploring **Android** development with Kotlin and Jetpack Compose
- 🐱 Cat mom to **Flash**

<br>

## 🚀 Featured Projects

### 💓 [PulseLink](https://github.com/EMECPE/prog7314-2026-poe-pulselink) - Remote Patient Monitoring System

> An IoT-driven tele-cardiology platform that captures single-lead ECG and heart-rate data from a wearable sensor and streams it to a clinical Android app in real time. Co-authored with [Cameron van Heerden](https://github.com/EMECPE).

- 🔌 **Hardware:** AD8232 ECG front-end on an ESP32-C3, sampling at 250 Hz with on-chip filtering and Pan-Tompkins R-peak detection for live BPM
- ☁️ **Backend:** ASP.NET Core REST API on Azure with Firebase Auth, Realtime Database and push alerts for tachycardia and bradycardia
- 📱 **Android app:** Kotlin MVVM with a 60 FPS oscilloscope-style ECG view, paper-accurate rhythm strips and an offline-first sync engine
- 🔐 **Security:** AES-256 GCM encrypted storage via Android Keystore and TLS transport
- 🌍 **Localised** in English, Afrikaans and isiZulu, with a GitHub Actions pipeline that tests and builds APK and AAB artefacts

![ESP32](https://img.shields.io/badge/ESP32--C3-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=flat-square&logo=microsoftazure&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2671E5?style=flat-square&logo=githubactions&logoColor=white)

<br>

### 💧 [SmartHydro](https://github.com/EMECPE/insy7315-2026-wil-kylelotter) - Offline-First Hydroponics and Fodder Monitoring

> An IoT monitoring and control system for crop and livestock fodder growing in remote, water-scarce environments, built for Emeris and its rural outreach work in Namibia. Team project with six developers. [Live web app](https://smarthydro-hyhxfuhcdne7cxhx.southafricanorth-01.azurewebsites.net)

- 🌱 **Monitoring and control:** live pH, EC, temperature, humidity, light and water level, with remote control of pumps, fans and dosing over SignalR
- 🚨 **Smart alerts:** a rule engine raises Warning and Critical alerts against each structure's own safe ranges
- 📴 **Offline first:** boxes pair over their own Wi-Fi hotspot and the Android app caches everything in Room for use without internet
- 🤖 **Edge ML:** Random Forest classifiers exported to C++ and running on the ESP32 boxes, with a 15 minute dosing lockout and manual override so the farmer stays in control
- 🔐 **Security:** PBKDF2 hashing, two-step sign-in with emailed codes, role-based access (Admin, Operator, Worker), rate limiting and a full CI/CD pipeline to Azure

![ASP.NET](https://img.shields.io/badge/ASP.NET_Core_10-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Arduino](https://img.shields.io/badge/ESP32_Firmware-00979D?style=flat-square&logo=arduino&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0072C6?style=flat-square&logo=microsoftazure&logoColor=white)

<br>

### 🔐 [HustleHub+](https://github.com/EMECPE/insy7314-2026-poe-kylelotter) - Secure Freelance Marketplace

> A full-stack MERN freelance marketplace where freelancers list gigs, clients book them, and every booking creates a simulated transaction. Built secure-by-design as a four-person team project. My part: frontend dashboards, role-based route guards, input sanitisation, member profiles and frontend testing.

- 🔑 **Auth:** email-verified registration and password reset with hashed one-time codes, JWT sessions, and token revocation on password change
- 🛡️ **Access control:** role-based access (Client, Freelancer, Admin) plus per-record ownership checks on the API
- 🧼 **Hardening:** global sanitisation, rate limiting, Helmet security headers, CSP with violation reporting, and local HTTPS
- 📊 **Dashboards:** income charts and tax estimates for freelancers, spending for clients, platform overview for admins
- 🧪 **Tested:** 49 Postman requests (82 assertions) run through Newman, plus 105 Vitest tests across 13 files

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

<br>

### 🌐 [Smart-X IoT Mesh Gateway](https://github.com/EMECPE/prog7312-2026-poe-maxinepalm) - Real-Time Telemetry Engine

> A simulated ESP32 telemetry gateway: a React SPA and a .NET console client both talk to an ASP.NET Core Minimal API that queues, classifies and stores sensor readings, with a command stream, Undo and a predictive suggestion engine.

- 📬 **Queues and stacks:** a FIFO queue with a priority lane so critical readings jump the line, and a command stack that powers Undo
- 🔑 **Lookups and sets:** O(1) device lookup, time-ordered history logs, and hash sets that stop duplicate error alerts
- 🧬 **Core C#:** generic `TelemetryPacket<T>`, operator overloading, jagged-array batching, a hand-built `BoundedLinkedList<T>` and recursive deployment validation
- 🔮 **Prediction engine:** co-occurrence counting, a Markov chain and linear regression suggest actions and warn before a sensor goes critical
- 🐳 **Dockerised** with SQL Server, Swagger docs for every endpoint, and a live-feed device simulator

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET_Core_10-5C2D91?style=flat-square&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)

<br>

## 🛠️ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=cs,java,py,js,ts,kotlin,html,css&theme=dark" />

**Frameworks and Libraries**

<img src="https://skillicons.dev/icons?i=dotnet,react,vite,nodejs,bootstrap&theme=dark" />

**Embedded and Mobile**

<img src="https://skillicons.dev/icons?i=arduino,androidstudio,raspberrypi&theme=dark" />

**Databases and Cloud**

<img src="https://skillicons.dev/icons?i=azure,postgres,mysql,mongodb,firebase&theme=dark" />

**Design and 3D**

<img src="https://skillicons.dev/icons?i=figma,blender,unity,unreal&theme=dark" />

**Tools**

<img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,postman,vscode,visualstudio&theme=dark" />

</div>

<br>

<br>

## 🌱 Currently

- 🔭 Building secure, production-style apps for my coursework
- 📚 Going deeper on embedded systems and Android
- 💬 Happy to chat about **C#**, **.NET**, **application security** or **IoT simulation**

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7B5CFF,50:D68BFF,100:FFB6E1&height=120&section=footer"/>
