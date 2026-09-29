<!-- HEADER BANNER -->
<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Asenso Owusu Ansah Banner"/>
</p>

<!-- TYPING HEADLINE & SOCIAL BADGES -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&multiline=false&width=620&height=40&lines=CS+%40+KNUST+%E2%80%94+Kumasi%2C+Ghana+%F0%9F%87%AC%F0%9F%87%AD;Full-Stack+Architect+%E2%80%94+React+19+%2B+Node.js+%2B+Prisma;Embedded+Systems+%E2%80%94+ESP32+Firmware+%26+RC522+IoT;Distributed+Systems+%E2%80%94+Escrow+State+Machines;Network+Security+%E2%80%94+Deep+Packet+Inspection+%26+IDS)](https://git.io/typing-svg)

<p align="center">
  <a href="https://linkedin.com/in/asenso-owusu-ansah">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:aowusuansah156@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/holmes1560">
    <img src="https://img.shields.io/badge/GitHub-holmes1560-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=holmes1560&label=PROFILE+VIEWS&color=0284c7&style=for-the-badge" alt="Profile Views" />
</p>

</div>

---

<!-- TERMINAL / ABOUT CARD -->
### 💻 System Terminal

```jsonc
// templar@knust:~$ cat /etc/identity.json
{
  "engineer": "Asenso Owusu Ansah",
  "callsign": "holmes1560",
  "location": "Kumasi, Ghana 🇬🇭",
  "academia": "B.Sc. Computer Science @ KNUST",
  "philosophy": "Systems where the failure mode matters more than the happy path.",
  "layers": [
    "TypeScript / React 19 / Expo mobile clients",
    "Typed Express & Prisma transactional backends",
    "ESP32 C/C++ firmware & SPI/I2C sensor integration",
    "Packet-level network traffic forensics & intrusion detection"
  ],
  "mission": "Refusing to pick just one layer — building the seam where software meets hardware."
}
```

---

<!-- TECH STACK -->
### 🛠️ Tech Arsenal

<div align="center">

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,python,cpp,c,react,nextjs,tailwind,nodejs,express&perline=10" alt="Tech Stack Line 1"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,prisma,redis,arduino,docker,linux,git,github,postman,vscode&perline=10" alt="Tech Stack Line 2"/>
</p>

</div>

---

<!-- FLAGSHIP PROJECTS -->
### 🚀 Flagship Engineered Systems

<table>
  <tr>
    <td width="50%" valign="top">
      <div align="center">
        <h3>🛡️ VeriTrust</h3>
        <p><b>Trust-as-a-Service P2P Escrow & Dispute Engine</b></p>
      </div>
      <p>
        Zero-balance-drift peer-to-peer commerce and dispute arbitration ecosystem removing the standoff between buyers and sellers.
      </p>
      <ul>
        <li><b>Guarded State Machine:</b> Atomic transitions with event audit trail</li>
        <li><b>Cross-Platform:</b> React 19 web portal + Expo SDK React Native mobile app</li>
        <li><b>Ledger Partitioning:</b> Integer pesewas (available, pending, escrow-locked)</li>
        <li><b>Security:</b> HMAC-SHA512 raw-body webhook signature verification</li>
      </ul>
      <p align="center">
        <a href="https://github.com/Veritrust-p2p/p2p">
          <img src="https://img.shields.io/badge/Repository-VeriTrust-0284c7?style=flat-square&logo=github" alt="VeriTrust Repo" />
        </a>
        <a href="https://veritrust-p2p.vercel.app">
          <img src="https://img.shields.io/badge/Live_Demo-Active-10b981?style=flat-square&logo=vercel" alt="VeriTrust Demo" />
        </a>
      </p>
      <details>
        <summary><b>🔍 Technical Architecture Deep-Dive</b></summary>
        <br/>
        <p>• <i>Backend:</i> Node.js & Express 5 REST + Socket.IO API backed by Prisma 7 and Neon PostgreSQL.</p>
        <p>• <i>Concurrence Guard:</i> Row-level debit locks prevent negative wallet balances during simultaneous checkout and withdrawal requests.</p>
        <p>• <i>Resilient Delivery:</i> Custom multi-driver HTTPS mail pipeline bypassing cloud container SMTP port blocks.</p>
      </details>
    </td>
    <td width="50%" valign="top">
      <div align="center">
        <h3>📟 Smart RFID Access System</h3>
        <p><b>Embedded ESP32 IoT Attendance & Lock Platform</b></p>
      </div>
      <p>
        Hardware-to-cloud security platform combining embedded microcontrollers with a live administrative audit log.
      </p>
      <ul>
        <li><b>Hardware Core:</b> ESP32 SoC interfacing RC522 RFID reader over SPI</li>
        <li><b>Firmware:</b> Non-blocking C/C++ FreeRTOS tasks with hardware watchdog</li>
        <li><b>Physical Prototyping:</b> Custom designed & 3D-printed enclosure</li>
        <li><b>Sync Engine:</b> Low-latency Wi-Fi token authentication with backend database</li>
      </ul>
      <p align="center">
        <a href="https://github.com/holmes1560/smart-rfid-attendance-system">
          <img src="https://img.shields.io/badge/Repository-Smart_RFID-0284c7?style=flat-square&logo=github" alt="RFID Repo" />
        </a>
        <a href="https://github.com/holmes1560/RFID_Door_lock">
          <img src="https://img.shields.io/badge/Hardware-Door_Lock-f59e0b?style=flat-square&logo=arduino" alt="Hardware Lock" />
        </a>
      </p>
      <details>
        <summary><b>🔍 Hardware & Protocol Deep-Dive</b></summary>
        <br/>
        <p>• <i>Bus Topology:</i> SPI bus running at high clock speed for instant UID read cycles under 50ms.</p>
        <p>• <i>Fault Tolerance:</i> Local queue cache in SPIFFS memory ensuring zero scan loss during Wi-Fi reconnect drops.</p>
        <p>• <i>Actuation:</i> Optocoupler-isolated relay circuit safely firing 12V electromagnetic strike locks.</p>
      </details>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <div align="center">
        <h3>🔍 P-DeepIDS</h3>
        <p><b>Network Forensics & Deep Packet Inspection</b></p>
      </div>
      <p>
        High-throughput packet dissection and network anomaly detector extracting transport & application layer heuristics.
      </p>
      <ul>
        <li>Live layer 3–7 frame parsing and flow reconstruction</li>
        <li>Statistical anomaly and protocol misuse flagging</li>
        <li>Exportable pcap analysis and event notification pipeline</li>
      </ul>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" alt="Wireshark" />
        <img src="https://img.shields.io/badge/Scapy-Packet_Engine-red?style=flat-square" alt="Scapy" />
      </p>
    </td>
    <td width="50%" valign="top">
      <div align="center">
        <h3>🎙️ Voxsynq</h3>
        <p><b>Low-Latency WebRTC & Socket Engine</b></p>
      </div>
      <p>
        Scalable real-time video, audio, and peer-to-peer data platform with resilient signaling and state reconciliation.
      </p>
      <ul>
        <li>ICE/STUN/TURN connection management & stream negotiation</li>
        <li>Low-overhead signaling protocol over WebSockets</li>
        <li>Optimized client media rendering and bandwidth management</li>
      </ul>
      <p align="center">
        <a href="https://github.com/holmes1560/Voxsynq_Temp">
          <img src="https://img.shields.io/badge/Repository-Voxsynq-0284c7?style=flat-square&logo=github" alt="Voxsynq Repo" />
        </a>
        <img src="https://img.shields.io/badge/WebRTC-Realtime-green?style=flat-square&logo=webrtc" alt="WebRTC" />
      </p>
    </td>
  </tr>
</table>

---

<!-- LIVE ACTIVITY & GRAPHS -->
### 📊 GitHub Activity & Analytics

<div align="center">

<!-- SNAKE CONTRIBUTION ANIMATION -->
<p align="center">
  <img src="assets/github-snake-dark.svg" alt="GitHub Contribution Snake" width="100%" />
</p>

<table border="0" width="100%">
  <tr>
    <td align="center" width="50%">
      <img src="assets/stats.svg" alt="GitHub Engineer Stats" width="100%" />
    </td>
    <td align="center" width="50%">
      <img src="assets/languages.svg" alt="Core Language Distribution" width="100%" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=holmes1560&theme=tokyonight&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub Streak" width="100%" />
    </td>
  </tr>
</table>

</div>

---

<!-- INSPIRING QUOTE / OUTRO -->
<div align="center">
  <p><i>"The seam between software and hardware is where abstractions stop helping — that's where the real engineering begins."</i></p>
  <b>Let's build something extraordinary.</b>
</div>
