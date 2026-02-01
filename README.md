<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=39FF14&background=00000000&center=true&vCenter=true&width=435&lines=System+Monitor+Active...;Subject:+Duck4705;Role:+Cyber+Security+%2F+SOC;Target:+Defend+The+Network" alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/đức-tào-minh-0b9abb316" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Connect" />
  </a>
  <a href="mailto:taominhduc2005@gmail.com">
    <img src="https://img.shields.io/badge/Email-Send_Mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Contact" />
  </a>
   <img src="https://img.shields.io/badge/School-UIT-005BBB?style=for-the-badge&logo=google-scholar&logoColor=white" />
</div>

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
```

### <img src="https://cdn-icons-png.flaticon.com/512/2620/2620735.png" width="30"> Terminal Access

```bash
# Identity check
$ whoami
> Duck4705

# Current Status
$ cat /etc/status
> Student @ UIT (University of Information Technology)
> Focus: Blue Team, SOC Operations, Network Defense
> Motto: "Eyes on the glass, guarding the data."
```
