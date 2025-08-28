# ⚡🌀✋ EnigMano Windows 11 Deployment — Your Tactical Fortress Commander

![GitHub Workflow](https://img.shields.io/badge/GitHub-Workflow-blue?style=for-the-badge\&logo=github\&logoColor=white)
![Windows](https://img.shields.io/badge/Runner-Windows-lime?style=for-the-badge\&logo=windows\&logoColor=white)
![PowerShell](https://img.shields.io/badge/Script-PowerShell-178600?style=for-the-badge\&logo=powershell\&logoColor=white)

---

**EnigMano 🌀✋** is forged from two powerful concepts:

* **Enigma 🌀** — a puzzle wrapped in shadows, precision, and quiet strength.
* **Mano ✋** — the “hand” that commands, controls, and executes with unwavering resolve.

Together, **EnigMano** embodies *“The Hand of Mystery”* — a silent guardian orchestrating the life and legacy of every fortress instance with masterful precision and hidden grace. 🛡️

> **Project Focus:** This repository is part of the EnigMano ecosystem, dedicated to creating **RDP-enabled, fully automated Windows 11 instances**. Each instance is pre-configured, secure, and ready for remote deployment and operations.

---

## 🔥 What Is This? 🕵️‍♂️

This GitHub Actions workflow automates the deployment of **EnigMano Windows 11 instances**, preparing a **digital fortress environment** that includes:

* Visual personalization (wallpapers, themes)
* Multi-browser deployment (Chrome & Brave) with isolated profiles
* Essential extensions for privacy, productivity, and automation
* Secure remote access via RDP & encrypted ngrok tunnels
* Optional tools like **Internet Download Manager (IDM)** and **Cloudflare WARP**

Everything runs automatically, creating **self-sufficient, ready-to-use workstations**.

---

## ⚡ Fortress Overview 🏰

| Parameter               | Value / Action                                                                                                                                                                                                                                 |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Workflow Trigger        | Manual, enter **INSTANCE** number ✋                                                                                                                                                                                                            |
| Runner                  | Windows (`windows-2025`) 💻                                                                                                                                                                                                                  |
| Secrets Required        | `SECRET_SHAHZAIB`, `NGROK_SHAHZAIB` 🔐                                                                                                                                                                                                         |
| Chrome & Brave Profiles | 3 isolated profiles per browser 🖥️                                                                                                                                                                                                            |
| Extensions Installed    | WebRTC Protect 🛡️, Video Quality Settings 🎥, Random YouTube Video 🎲, Proton VPN 🔒, Stop Autoplay Next ⏹️, YouTube Nonstop 🔁, uBlock Origin 🚫, Ghostery 👻, Tab Auto Refresh 🔄, Adguard, IDM Integration Module, YouTube Ad Auto Skipper |
| Personalization         | Wallpaper & theme applied via PowerShell 🎨                                                                                                                                                                                                    |
| Secure Access           | RDP enabled, firewall configured, ngrok tunnel 🌐                                                                                                                                                                                              |
| Mission Duration        | 340 minutes ⏱️                                                                                                                                                                                                                                 |
| Logs & Reporting        | Step-by-step deployment + final status 📝                                                                                                                                                                                                      |

---

## 🔐 Prerequisites 🛡️

* Runner: **windows-2025** (Windows 11 environment) 🖥️
* GitHub secrets configured:

  * `SECRET_SHAHZAIB` 🔑
  * `NGROK_SHAHZAIB` 🌐

---

## ⚠️ Notes & Tips ⚠️

* Keep your secrets **secure and confidential** 🔒
* Use only in **private and secure environments** 🕵️‍♂️
* Ensure network allows RDP and outbound connections for ngrok 🌐
* Monitor logs for step-by-step deployment confirmation 📝

---

## 🙌 Credits 🛡️

Built & maintained by **SHAHZAIB-YT** — orchestrating Windows 11 fortresses with tactical precision. 🔋

---

Ready to deploy your **EnigMano Windows 11 fortress**? Command the silent hand now! 🌀✋🛡️

---

## 🖼️ Visual Architecture Diagram 🌀✋

```mermaid
flowchart TD
    subgraph ENVIRONMENT
        WP[Wallpaper & Theme Personalization 🎨]
        DV[Data Vault Creation 📂]
    end

    subgraph BROWSERS
        Chrome[Google Chrome 🖥️]
        Brave[Brave Browser 🖥️]
        Extensions[Extensions Deployment 🛡️]
        Profiles[Profile Isolation 🗂️]
    end

    subgraph SECURE_ACCESS
        RDP[RDP Enabled 🌐]
        Firewall[Firewall Rules 🛡️]
        Ngrok[Ngrok Tunnel 🔐]
    end

    subgraph UTILITIES
        IDM[Internet Download Manager ⚡]
        WARP[Cloudflare WARP 🌐]
    end

    subgraph CONTROLLER
        Workflow[GitHub Actions Workflow ⚡]
        Secrets[Secrets Injection 🔑]
        Logger[Deployment Logs 📝]
        Handoff[Instance Relay ✋]
    end

    Workflow --> Secrets
    Workflow --> Logger
    Workflow --> ENVIRONMENT
    ENVIRONMENT --> BROWSERS
    BROWSERS --> SECURE_ACCESS
    SECURE_ACCESS --> UTILITIES
    UTILITIES --> Handoff
    Handoff --> Workflow
```

> **Diagram Explanation:**
> This architecture shows how the **EnigMano Windows 11 instance** is orchestrated: environment personalization → browser & extension deployment → secure access → utility tools → instance handoff → repeat for multi-instance operations.
