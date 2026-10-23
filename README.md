<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:1a1b27,50:2d1b4e,100:7aa2f7&height=220&section=header&text=Hey,%20I'm%20Mo&fontColor=e0af68&fontSize=60&animation=twinkling&desc=Full-Stack%20%C2%B7%20Security%20%C2%B7%20Home%20Lab%20%C2%B7%20Hardware&descAlignY=74&descSize=18&descColor=c0caf5" width="100%" alt="header"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2400&pause=600&color=BB9AF7&center=true&vCenter=true&width=700&height=55&lines=Full-Stack+Engineer+%F0%9F%9B%A0%EF%B8%8F;Software+Engineer+%F0%9F%92%BB;Security-Minded+Builder+%F0%9F%9B%A1%EF%B8%8F;Home-Lab+Operator+%E2%80%94+Proxmox+%C2%B7+Linux+%F0%9F%96%A5%EF%B8%8F;Systems+Engineer+%E2%9A%99%EF%B8%8F;I+build+drones+and+robots+%F0%9F%9A%81;Basically...+an+Everything+Engineer+%F0%9F%9A%80" alt="typing"/>

<br/>

<img src="https://img.shields.io/badge/Full--Stack-7aa2f7?style=for-the-badge&logo=react&logoColor=1a1b27"/>
<img src="https://img.shields.io/badge/Security-f7768e?style=for-the-badge&logo=letsencrypt&logoColor=1a1b27"/>
<img src="https://img.shields.io/badge/Home_Lab-9ece6a?style=for-the-badge&logo=proxmox&logoColor=1a1b27"/>
<img src="https://img.shields.io/badge/Hardware-e0af68?style=for-the-badge&logo=arduino&logoColor=1a1b27"/>

</div>

---

### 🧑‍💻 `struct Mo`

```swift
struct Mo: Engineer {
    let based       = "Staten Island, NY 🗽"
    let titles      = ["Full-Stack Engineer", "Software Engineer", "Security nerd", "Home-lab operator"]
    let shipping    = ["ICSI Hub CRM", "ICSI Community app", "ICSI Transit"]
    let servers     = ["Proxmox", "Linux boxes", "a VPS", "a Raspberry Pi"]
    let builtByHand = ["my own drone 🚁", "a JARVIS desk robot 🤖"]

    func motto() -> String { "If it runs, I want to know how. If it breaks, I want to fix it." }
}
```

---

### 🚀 Flagship projects

<table>
<tr>
<td width="50%" valign="top">

**🏢 ICSI Hub** · [`icsihub.org`](https://icsihub.org)<br/>
The CRM that runs the Islamic Center of Staten Island: members, programs, payments and alerts. Split into an API and background workers, deployed on my own Linux server with uptime monitoring.<br/>
<sub>TypeScript · Express · React · PostgreSQL · Linux</sub>

</td>
<td width="50%" valign="top">

**📱 ICSI Community**<br/>
Native iPhone app for the whole community: prayer times, café ordering, a wallet, donations, programs and a parent portal.<br/>
<sub>Swift · SwiftUI</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🚌 ICSI Transit**<br/>
Live school-bus tracking for parents and drivers, plus attendance and fleet management.<br/>
<sub>Swift · TypeScript API · Supabase</sub>

</td>
<td width="50%" valign="top">

**🥽 Agent Cockpit**<br/>
A Quest 3 mixed-reality cockpit where I watch and approve AI coding agents with hand gestures, floating in my room.<br/>
<sub>WebXR · Three.js · Node · WebSockets</sub>

</td>
</tr>
</table>

---

### 🛡️ Security

> I don't treat security as an afterthought. Every project I ship gets threat-modeled and checked against a checklist before launch.

- **✅ DevChecklists Security:** my own security & design checklist system, which tracks every project from first commit to launch: auth, secrets, input validation and dependencies.
- **🎮 CyberQuest:** a gamified cybersecurity learning app I built to level up hacking & defense skills.
- **🔐 Zero-trust home network:** every server sits behind a private **Tailscale** mesh, nothing is exposed to the open internet, and secrets are locked down.
- **🕵️ Security reviews:** I run security audits on my own code before it ever hits production.

---

### 🖥️ The Home Lab

```text
                    ┌──────────────────────────────┐
                    │     Tailscale mesh (VPN)     │
                    └──────────────┬───────────────┘
         ┌─────────────────┬───────┴─────────┬─────────────────┐
  ┌──────┴──────┐   ┌──────┴──────┐   ┌──────┴──────┐   ┌──────┴──────┐
  │   Proxmox   │   │   "nova"    │   │     VPS     │   │ Raspberry Pi│
  │  hypervisor │   │ Linux+Docker│   │  prod CRM   │   │  "friday"   │
  │  VMs / LXC  │   │  AI server  │   │ API+workers │   │  edge node  │
  └─────────────┘   └──────┬──────┘   └─────────────┘   └─────────────┘
                           │
      ollama (local LLMs) · LLM router · n8n automations · AI "second brain"
      video -> knowledge pipeline · custom Next.js dashboard for every service
```

I self-host my own stack: local AI models, automation, a personal knowledge base that turns videos into searchable notes, and a dashboard that watches all of it.

---

### 🔧 Hardware: things I built with my hands

<table>
<tr>
<td width="50%" valign="top">

**🚁 Custom Drone**<br/>
Designed, assembled and flew my own drone from parts.

</td>
<td width="50%" valign="top">

**🤖 JARVIS Desk Robot**<br/>
A desktop companion with a 3-axis animated head (yaw, pitch and roll), glowing display eyes, 3D-printed faceted armor and a voice stack (speech-to-text → LLM → voice).<br/>
<sub>CAD · 3D printing · Python · servos</sub>

</td>
</tr>
</table>

---

### 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=swift,ts,js,py,react,nextjs,nodejs,express,postgres,sqlite,supabase,tailwind&perline=12&theme=dark" alt="dev stack"/><br/>
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,docker,bash,git,github,vercel,raspberrypi,arduino,blender,apple&perline=12&theme=dark" alt="infra and hardware"/><br/>
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white"/>
</p>

---

### 📈 Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Smoky-killer&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=tokyonight" alt="stats"/>
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=Smoky-killer&hide_border=true&theme=tokyonight" alt="streak"/>

</div>

### 👾 Pac-Man is eating my contributions

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Smoky-killer/Smoky-killer/output/pacman-contribution-graph-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Smoky-killer/Smoky-killer/output/pacman-contribution-graph.svg"/>
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/Smoky-killer/Smoky-killer/output/pacman-contribution-graph.svg" width="100%"/>
</picture>

</div>

---

<div align="center">

<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="22"/> <sub>As-salamu alaykum, thanks for stopping by ✌️</sub><br/>
<img src="https://komarev.com/ghpvc/?username=Smoky-killer&style=flat-square&color=bb9af7&label=profile+views" alt="views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:2d1b4e,100:1a1b27&height=120&section=footer&animation=twinkling" width="100%" alt="footer"/>
