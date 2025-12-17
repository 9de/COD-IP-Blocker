# COD IP Blocker — Windows Firewall Script

This repository contains a **Windows CMD script** that allows you to block specific IP ranges for a given game executable (e.g., *Call of Duty HQ*).  
It uses **Windows Defender Firewall** to block outbound connections from the game binary to selected IP ranges.

---

## 🌐 IP Ranges to Block

| IP Range        | Description / Owner                    | ASN        | Country         |
|-----------------|----------------------------------------|------------|-----------------|
| `94.97.0.0/16`  | Saudi Telecom Company JSC              | AS25019    | Saudi Arabia 🇸🇦 | :contentReference[oaicite:0]{index=0}
| `15.185.0.0/16` | AWS (Amazon Data Services Bahrain)     | AS16509    | Bahrain 🇧🇭     | :contentReference[oaicite:1]{index=1}
| `15.184.0.0/16` | AWS (Amazon Data Services Bahrain)     | AS16509    | Bahrain 🇧🇭     | :contentReference[oaicite:2]{index=2}

> **Note:** These IP ranges may host services or servers used by the game or its backend services. Blocking them may affect connectivity in unexpected ways.

---

## 🛠️ Windows CMD Script

This script will ask for the **path to the COD game executable** and create firewall rules to block the above IP ranges.
