## hey, i'm lexie 

10 years in cyber. 8 years USAF plus 3-4 years private industry also cyber. Currently running a hackerspace in Philadelphia and building robots that break things in interesting ways.

I lead **[Ex Machina Parlor (EMP)](https://exmachinaparlor.com/)** — a security research lab and hackerspace supporting DC215. We run workshops, a cyber range, and various projects that live somewhere between "cool research" and "why did we build this."

[![Website](https://img.shields.io/badge/Website-3776AB?style=for-the-badge)](https://lexiethach.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lexie-alex-thach-297190120/)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@alex.thach3)
[![Email](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:lexicon21@proton.me)

---

### what i actually do

- **Red/purple team** — AD attacks, C2 infra, EDR evasion, the usual chaos
- **Hardware & RF security** — if it has an antenna or a microcontroller, it's probably a target
- **Robotics / autonomous systems** — building and (ethically) breaking mobile platforms
- **ICS/SCADA** — OT security research and range simulation
- **AI/ML integration** — currently deep in local inference stacks and robotics AI pipelines
- **Running a hackerspace** — mentoring, workshops, and cyber range ops for the community

---

### current projects

<details>
<summary><b> Tengu Marauder Vanguard / Stryker (TMV/TMS)</b> — autonomous RF attack platform</summary>

<br/>

The evolution of the original Tengu Marauder. A multi-robot platform built for mobile penetration testing, RF operations, and conference demos.

- **[Vanguard](https://github.com/ExMachinaParlor/Tengu-Marauder-Vanguard)** — Raspberry Pi 4 based units for mobile recon and wireless ops. Presented at Black Hat USA 2025 Arsenal.
- **[Stryker](https://github.com/ExMachinaParlor/Tengu-Marauder-Stryker)** — Mark 3 unit on Raspberry Pi 5 + Hailo AI HAT 2 + Fusion HAT+ with onboard AI inference and expanded sensor suite
- **ESP32-C5** — dual-band WiFi scanning via custom Marauder firmware
- **Wi-Fi HaLow (802.11ah)** — long-range sub-GHz command and control
- **Containerized stack** — Flask REST APIs, TUI over HTTP, Sliver C2 integration

**Conference history:**
- Black Hat USA 2026 — Arsenal — **Tengu Marauder Vanguard 2.0** *(accepted)*
- DEF CON 33 (2025) — Demo Labs — Tengu Marauder v2
- Black Hat USA 2025 — Arsenal — Tengu Marauder Vanguard
- DEF CON 32 (2024) — Demo Labs — Tengu Marauder
- DEF CON 31 (2023) — Demo Labs — Strix Interceptor

</details>

<details>
<summary><b> EMP Cyber Range</b></summary>

<br/>

A full simulated enterprise environment on virtualized infra. 56 VMs across 20 VLANs.

- University AD, Mattermost, Jitsi, ERP, WordPress
- OT/ICS segment — Modbus PLCs, HMI with live Flask dashboards, power plant and fuel farm physics loops
- Red team Kali with OT attack toolkit pre-staged
- Security Onion with custom Suricata/Sigma rules for range participant monitoring
- Exercise control docs, scoring rubric, rollback procedures — the whole package

Used for EMP community workshops and ongoing security research.

</details>

<details>
<summary><b> EMP Lab Infrastructure</b></summary>

<br/>

Built and maintain two lab environments for EMP:

- **EMP Colo Emulation Lab** — a persistent emulation environment hosted at the EMP colo, used for security research, range ops, and community training
- **EMP Mobile Range Lab** — a portable fly-away kit I bring to conferences like Black Hat, DEF CON, and other security cons for on-site workshops, demos, and range access for participants

Both connect over site-to-site WireGuard so the mobile lab extends the colo environment wherever we set up.

</details>

<details>
<summary><b> Self-hosted AI stack</b></summary>

<br/>

Running local inference because I like owning my data and my compute:

- Local inference node running LocalAI + Open WebUI + ComfyUI
- MCP tool servers wired into Continue.dev in VS Code

</details>

---

### older stuff that started it all

<details>
<summary> Strix Interceptor — DEF CON 31 (2023) Demo Labs</summary>

<br/>

- **[GitHub](https://github.com/Lexicon121/Strix-Interceptor)** — defensive interceptor drone for tactical RF operations
- Demoed at DEF CON 31 Demo Labs — the project that started the Tengu lineage

</details>

<details>
<summary> Tengu Marauder — DEF CON 32 (2024) Demo Labs</summary>

<br/>

- **[GitHub](https://github.com/Lexicon121/Tengu-Marauder)** — the original: mini wardriving drone with ESP32 Marauder + Flipper Zero
- Demoed at DEF CON 32 Demo Labs
- The direct predecessor to the TMV/TMS platform

</details>

<details>
<summary> Tengu Marauder Vanguard — Black Hat USA 2025 Arsenal</summary>

<br/>

- **[GitHub](https://github.com/ExMachinaParlor/Tengu-Marauder-Vanguard)** — mobile cyber-physical platform: drive control, live camera, ESP32 Marauder integration, passive wireless recon, all in a single Docker container
- Presented at Black Hat USA 2025 Arsenal

</details>

<details>
<summary> Xonar Swarm System</summary>

<br/>

- **[GitHub](https://github.com/Lexicon121/Xonar)** — swarm navigation for Crazyflie 2.0 + ROS2, using HTC Vive 1.0 lighthouse + Xbox Kinect + OpenCV for localization

</details>

<details>
<summary> ICARUS Framework</summary>

<br/>

- **[GitHub](https://github.com/Lexicon121/ICARUS-Framework)** — theoretical security framework for small UAS, based on MITRE ATT&CK and SPARTA
- Published at IAC 2023: [IAC-2023-80363](https://dl.iafastro.directory/event/IAC-2023/paper/80363/) — AI-enabled cybersecurity model for satellite threat protection

</details>

---

### the lab

EMP runs on Proxmox, pfSense/OPNsense, Security Onion, TrueNAS, and a lot of Docker. Forgejo for self-hosted git. Wazuh for endpoint monitoring. Semaphore for Ansible automation. KasmVDI for bastion access.

If you're in the Philly security community and want range access for practice or research, find us through DC215.

---

### support the work

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.me/AThach822)
[![Cash App](https://img.shields.io/badge/CashApp-01D21C?style=for-the-badge&logo=cashapp&logoColor=white)](https://cash.app/$Vexacon121)
[![Buy Me A Coffee](https://img.shields.io/badge/BuyMeACoffee-FFDD00?style=for-the-badge)](https://www.buymeacoffee.com/lexiecon121)

<details>
<summary>crypto</summary>

<br/>

| Currency | Address |
|----------|---------|
| Bitcoin | `3Pgqkda3w8ZTzBGT5DeLDiWdkgNTNjNxvo` |
| Ethereum | `0x31Dcb542BA6dDf0b16EcB36B5Aedf14d5CEcB897` |
| Tether | `0x96AfE6640a310265D3177eFC3bfEAa0dC6F4e31E` |

</details>
