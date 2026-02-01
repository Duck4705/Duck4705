<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=0F52BA&background=00000000&center=true&vCenter=true&width=435&lines=System+Monitor+Active...;Subject:+Duck4705;Role:+Blue+Team+%2F+SOC+Analyst;Target:+Defend+The+Network" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/OS-Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Net-Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Log-Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white" />
  <img src="https://img.shields.io/badge/Code-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/School-UIT-005BBB?style=for-the-badge&logo=google-scholar&logoColor=white" />
</div>

---

### <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30"> Network Defense Architecture

```mermaid
graph LR
    Attacker[👾 Internet / Threat] -- Malicious Traffic --> FW[🔥 Firewall]
    FW -- Filtered Traffic --> Router[🌐 Edge Router]
    Router --> IPS[🛡️ IPS / IDS]
    
    subgraph "Internal Network"
        IPS --> Switch[🔌 Core Switch]
        Switch --> Server[🖥️ Protected Servers]
        Switch --> PC[💻 User Workstations]
    end
    
    subgraph "SOC Monitoring"
        IPS -. Alerts .-> SIEM[📊 SIEM / Dashboard]
        Switch -. Mirror Port .-> Sniffer[🕵️ Packet Capture]
    end

    style FW fill:#ff6b6b,stroke:#333,stroke-width:2px,color:black
    style SIEM fill:#4ecdc4,stroke:#333,stroke-width:2px,color:black
    style IPS fill:#ffe66d,stroke:#333,stroke-width:2px,color:black
