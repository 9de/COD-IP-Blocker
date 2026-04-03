# 🎮 Call of Duty — Middle East Server IP Ranges

A community-maintained reference of **IP ranges used by Activision** to host Middle East game servers for the Call of Duty series — covering titles from **Modern Warfare (2019)** through the **Black Ops 7 era**.

> ⚠️ **Disclaimer**
> IP ranges are derived from public ASN data and network observations. They may change at any time as Activision updates its infrastructure.

---

## 📋 Overview

These ranges are collected for users who want to manage or filter connections to Middle East servers. Infrastructure spans multiple cloud providers across Saudi Arabia and Bahrain.

---

## 🌐 IP Ranges

| IP Range | Provider | ASN | Location |
|---|---|---|---|
| `94.97.0.0/16` | Saudi Telecom Company (STC) | AS25019 | 🇸🇦 Saudi Arabia |
| `15.185.0.0/16` | AWS — Amazon Data Services | AS16509 | 🇧🇭 Bahrain |
| `15.184.0.0/16` | AWS — Amazon Data Services | AS16509 | 🇧🇭 Bahrain |
| `16.24.0.0/16` | AWS — Amazon Data Services | AS16509 | 🇧🇭 Bahrain |
| `34.166.0.0/16` | Google Cloud LLC *(new)* | AS396982 | 🇸🇦 Saudi Arabia — Dammam |

---

## 📅 Changelog

| Date | Change |
|---|---|
| Latest | Added `34.166.13.0/24` — Google Cloud, Dammam, Saudi Arabia |
| Initial | AWS Bahrain ranges + STC Saudi Arabia documented |

---

## 📝 Notes

- The `/16` ranges cover large AWS and STC blocks commonly associated with CoD matchmaking in the region.
- The newly added `/24` Google Cloud range (`34.166.13.0/24`) is a narrower, more targeted block hosted out of **Dammam, Saudi Arabia**.
- ASN data sourced from public registries (RIPE, ARIN, etc.) and may not reflect real-time routing changes.

---

*Contributions and corrections welcome — open an issue or PR if you spot outdated ranges.*
