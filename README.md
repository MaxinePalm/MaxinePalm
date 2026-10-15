<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FFB6E1,100:B983FF&height=240&section=header&text=Maxine%20Palm&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Software%20Developer%20%7C%20Secure%20Apps%20%2B%20IoT%20%2B%20Android&descAlignY=60&descSize=20&animation=fadeIn"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&pause=1000&color=B983FF&center=true&vCenter=true&width=650&height=40&repeat=true&lines=Building+secure+full-stack+applications;Wiring+ESP32+sensors+to+the+cloud;C%23+%2F+.NET+%7C+Kotlin+%7C+React+%7C+Node.js;Learning+Arduino+and+embedded+systems;Cat+mom+to+Flash" alt="Typing SVG" />

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maxine-palm-4751a530b/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maxinepalm450@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@SalticidaeM)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/maxine_palm)

</div>

---

## 👋 About Me

I'm a third-year Software Development student who builds things that work, then makes them secure. My projects sit where application security, IoT hardware and mobile meet.

<table>
  <tr>
    <td>🎓 <b>Year</b></td>
    <td>3rd year Software Development student</td>
  </tr>
  <tr>
    <td>🎯 <b>Focus</b></td>
    <td>Application security, IoT and Android</td>
  </tr>
  <tr>
    <td>💻 <b>Languages</b></td>
    <td>C#, Kotlin, TypeScript, Java, Python</td>
  </tr>
  <tr>
    <td>📚 <b>Learning</b></td>
    <td>Arduino and embedded systems</td>
  </tr>
  <tr>
    <td>💬 <b>Ask me about</b></td>
    <td>.NET, IoT and security</td>
  </tr>
  <tr>
    <td>🐱 <b>Fun fact</b></td>
    <td>My cat is called Flash</td>
  </tr>
</table>

---

## 🚀 Featured Projects

### 💓 PulseLink

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FF416C,100:FF4B2B&height=110&section=header&text=PulseLink&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=Remote%20Patient%20Monitoring%20System&descAlignY=65&descSize=16"/>

> An IoT tele-cardiology platform that captures ECG and heart-rate data from a wearable sensor and streams it to a clinical Android app in real time. Co-authored with [Cameron van Heerden](https://github.com/EMECPE).

- 🔌 **Hardware:** AD8232 ECG sensor on an ESP32-C3, sampling at 250 Hz with Pan-Tompkins R-peak detection for live BPM
- ☁️ **Backend:** ASP.NET Core REST API on Azure with Firebase Auth, Realtime Database and push alerts
- 📱 **Mobile:** Kotlin MVVM app with a 60 FPS ECG view, rhythm strips and an offline-first sync engine
- 🔐 **Security:** AES-256 GCM encrypted storage through Android Keystore, plus TLS in transit
- ⚙️ **DevOps:** GitHub Actions pipeline that tests and builds APK and AAB files, in English, Afrikaans and isiZulu

<img src="https://skillicons.dev/icons?i=kotlin,androidstudio,dotnet,azure,firebase,arduino,githubactions&theme=dark" />

🔗 **[View repository](https://github.com/EMECPE/prog7314-2026-poe-pulselink)**

---

### 💧 SmartHydro

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0083B0,100:00B4DB&height=110&section=header&text=SmartHydro&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=Offline-First%20Hydroponics%20and%20Fodder%20Monitoring&descAlignY=65&descSize=16"/>

> An IoT monitoring and control system for crop and fodder growing in remote, water-scarce areas, built for Emeris and its rural outreach work in Namibia. Team project with six developers.

- 🌱 **Control:** live pH, EC, temperature, humidity, light and water level, with remote control of pumps, fans and dosing over SignalR
- 🚨 **Alerts:** a rule engine raises Warning and Critical alerts against each structure's own safe ranges
- 📴 **Offline first:** sensor boxes pair over their own Wi-Fi hotspot and the Android app caches data in Room
- 🤖 **Edge ML:** Random Forest classifiers exported to C++ and run on the ESP32 boxes, with manual override so the farmer stays in control
- 🔐 **Security:** PBKDF2 hashing, two-step sign-in, role-based access, rate limiting and CI/CD to Azure

<img src="https://skillicons.dev/icons?i=dotnet,kotlin,postgres,azure,arduino,githubactions&theme=dark" />

🔗 **[View repository](https://github.com/EMECPE/insy7315-2026-wil-kylelotter)** &nbsp;|&nbsp; 🌐 **[Live web app](https://smarthydro-hyhxfuhcdne7cxhx.southafricanorth-01.azurewebsites.net)**

---

### 🔐 HustleHub+

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,100:00C6FF&height=110&section=header&text=HustleHub%2B&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=Secure%20Freelance%20Marketplace&descAlignY=65&descSize=16"/>

> A full-stack freelance marketplace where freelancers list gigs and clients book them. Built secure-by-design as a four-person team project. My part: frontend dashboards, role-based route guards, input sanitisation, member profiles and frontend testing.

- 🔑 **Auth:** email-verified sign-up and password reset with hashed one-time codes, JWT sessions and token revocation
- 🛡️ **Access control:** Client, Freelancer and Admin roles, plus per-record ownership checks on the API
- 🧼 **Hardening:** sanitisation, rate limiting, Helmet security headers, CSP with violation reporting and local HTTPS
- 📊 **Dashboards:** income charts and tax estimates for freelancers, spending for clients, overview for admins
- 🧪 **Testing:** 49 Postman requests (82 assertions) through Newman, plus 105 Vitest tests

<img src="https://skillicons.dev/icons?i=mongodb,express,react,nodejs,ts,vite&theme=dark" />

🔗 **[View repository](https://github.com/EMECPE/insy7314-2026-poe-kylelotter)**

---

### 🌐 Smart-X IoT Mesh

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:F953C6,100:B91D73&height=110&section=header&text=Smart-X%20IoT%20Mesh&fontSize=40&fontColor=ffffff&fontAlignY=40&desc=Real-Time%20Telemetry%20Gateway&descAlignY=65&descSize=16"/>

> A simulated ESP32 telemetry gateway. A React app and a .NET console client talk to an ASP.NET Core API that queues, classifies and stores sensor readings, with a command stream, Undo and a predictive suggestion engine.

- 📬 **Queues and stacks:** a FIFO queue with a priority lane for critical readings, and a command stack that powers Undo
- 🔑 **Lookups and sets:** O(1) device lookup, time-ordered history logs and hash sets that stop duplicate alerts
- 🧬 **Core C#:** generics, operator overloading, jagged-array batching, a hand-built bounded linked list and recursive validation
- 🔮 **Prediction:** a Markov chain and linear regression suggest actions and warn before a sensor goes critical
- 🐳 **Docker:** runs with SQL Server in containers, with Swagger docs for every endpoint

<img src="https://skillicons.dev/icons?i=cs,dotnet,react,vite,docker&theme=dark" />

🔗 **[View repository](https://github.com/EMECPE/prog7312-2026-poe-maxinepalm)**

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=cs,kotlin,java,py,ts,js,html,css&theme=dark" />

**Frameworks**

<img src="https://skillicons.dev/icons?i=dotnet,react,vite,nodejs,express,bootstrap&theme=dark" />

**Embedded and Mobile**

<img src="https://skillicons.dev/icons?i=arduino,androidstudio,raspberrypi&theme=dark" />

**Databases and Cloud**

<img src="https://skillicons.dev/icons?i=azure,postgres,mysql,mongodb,firebase&theme=dark" />

**Design and 3D**

<img src="https://skillicons.dev/icons?i=figma,blender,unity,unreal&theme=dark" />

**Tools**

<img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,postman,vscode,visualstudio&theme=dark" />

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=MaxinePalm&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF69B4&icon_color=B983FF&text_color=ffffff"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MaxinePalm&theme=radical&hide_border=true&layout=compact&bg_color=0D1117&title_color=FF69B4&text_color=ffffff"/>

<img src="https://nirzak-streak-stats.vercel.app/?user=MaxinePalm&theme=radical&hide_border=true&background=0D1117&ring=FF69B4&fire=B983FF&currStreakLabel=FF69B4"/>

<img src="https://raw.githubusercontent.com/MaxinePalm/MaxinePalm/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" width="100%"/>

</div>

---

## 📫 Let's Connect

<div align="center">

I'm always up for talking secure apps, IoT builds and Android.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maxine-palm-4751a530b/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maxinepalm450@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@SalticidaeM)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:B983FF,100:FFB6E1&height=120&section=footer"/>
