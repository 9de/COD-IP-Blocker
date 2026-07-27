# 🎮 Call of Duty — Middle East Server IP Ranges

A community-maintained collection of **Middle East server IP ranges** used by **Activision** for the Call of Duty franchise, covering titles from **Modern Warfare (2019)** through the **Black Ops 7 era**.

This repository documents publicly observed server infrastructure to help players, network enthusiasts, and developers identify Call of Duty's Middle East hosting locations.

> [!IMPORTANT]
> This project is **not affiliated with Activision**.
>
> All information is collected through network analysis, packet captures, public ASN databases, and community observations. Server infrastructure may change at any time without notice.

---

# 🌍 Overview

Call of Duty currently utilizes infrastructure from multiple cloud providers across the Middle East.

Known providers include:

- 🇸🇦 Saudi Telecom Company (STC)
- 🇧🇭 Amazon Web Services (AWS Bahrain) [*(currently no longer in use due to the regional conflict)*](https://www.aboutamazon.com/news/aws-bahrain-region-middle-east-conflict?sc_channel=sm&sc_publisher=TWITTER&sc_country=global&sc_geo=GLOBAL&sc_outcome=awareness&linkId=922749702)
- 🇸🇦 Google Cloud Platform (Saudi Arabia)
- 🇸🇦 Alibaba Cloud (Saudi Arabia)

As Activision expands regional capacity, additional providers and IP ranges may appear.

---

# 📦 Known IP Ranges

| IP Range | Provider | ASN | Location | Status |
|----------|----------|------|----------|--------|
| `94.97.0.0/16` | Saudi Telecom Company (STC) | AS25019 | 🇸🇦 Saudi Arabia | ✅ Confirmed |
| `15.184.0.0/16` | Amazon Web Services | AS16509 | 🇧🇭 Bahrain | ✅ Confirmed |
| `15.185.0.0/16` | Amazon Web Services | AS16509 | 🇧🇭 Bahrain | ✅ Confirmed |
| `16.24.0.0/16` | Amazon Web Services | AS16509 | 🇧🇭 Bahrain | ✅ Confirmed |
| `34.166.0.0/16` | Google Cloud Platform | AS396982 | 🇸🇦 Saudi Arabia | ✅ Confirmed |
| `34.180.0.0/16` | Google Cloud Platform | AS396982 | 🇸🇦 Saudi Arabia | 🔍 Observed |
| `35.252.0.0/16` | Google Cloud Platform | AS396982 | 🇸🇦 Saudi Arabia | 🔍 Observed |
| `8.228.0.0/16` | Alibaba Cloud | AS45102 | 🇸🇦 Saudi Arabia | 🔍 Observed |
| `8.228.217.0/24` | Alibaba Cloud | AS45102 | 🇸🇦 Saudi Arabia | ✅ Confirmed |



---

# 🔍 Identification Methodology

Every IP range included in this repository has been identified through one or more of the following:

- 🎮 Live gameplay packet captures
- 📈 Repeated matchmaking observations

Only IP ranges that consistently appear during active gameplay are documented.

---

# ⚠️ Important Notes

## These networks are **NOT exclusive** to Call of Duty

Most of the listed IP ranges belong to large public cloud providers such as:

- Amazon Web Services (AWS)
- Google Cloud Platform (GCP)
- Alibaba Cloud
- Saudi Telecom Company (STC)

These providers host **thousands of unrelated services**, including:

- Websites
- APIs
- Mobile applications
- Video streaming
- CDN infrastructure
- Enterprise services
- Other online games

Blocking an entire provider subnet may unintentionally affect these services.

---

## Use application-specific firewall rules

If your goal is to:

- Force matchmaking to another region
- Prevent connecting to Middle East servers
- Test server selection
- Analyze networking behavior

**Do not block these ranges globally.**

Instead, create firewall rules that apply **only to the Call of Duty executable** using tools such as:

- Windows Firewall
- Windows Filtering Platform (WFP)
- SimpleWall
- NetLimiter
- Your router/firewall (application-aware policies)

This avoids breaking unrelated applications that use the same cloud infrastructure.

---

## Infrastructure changes frequently

Activision may:

- Add new cloud providers
- Remove existing servers
- Expand into new regions
- Announce more specific prefixes
- Change routing without notice

This repository should be considered a **living reference** rather than a complete list.

Always verify new IP ranges before relying on them.

---

# 📅 Changelog

| Version | Changes |
|----------|---------|
| Latest | Added `34.180.0.0/16`, `35.252.0.0/16`, `8.228.0.0/16`, and `8.228.217.0/24` |
| Previous | Added `34.166.13.0/24` (Google Cloud, Saudi Arabia) |
| Initial | Documented AWS Bahrain and STC Saudi Arabia infrastructure |

---

# 🤝 Contributing

Contributions are always welcome.

If you've identified a new Middle East Call of Duty server:

1. Capture gameplay traffic.
2. Verify ownership using WHOIS and ASN lookups.
3. Confirm repeated usage across multiple matches.
4. Open an Issue or Pull Request including:
   - IP address or CIDR
   - ASN
   - Provider
   - Game Name
   - Evidence (packet capture, traceroute, screenshots, etc.)

---

# 📚 Data Sources

This repository references publicly available networking information from:

- [IPinfo](https://ipinfo.io/


---

# ⭐ Support

If this repository helped you:

- ⭐ Star the repository
- 🐛 Report new IP ranges
- 📢 Submit corrections
- 🤝 Contribute additional packet captures

Keeping this list accurate helps the entire Call of Duty networking community.
