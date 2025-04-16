# SolarStorm-LX
A real-world, Linux-based CTF machine inspired by the SolarWinds attack. Includes realistic persistence, privesc, and forensic flags.
# ⚡ SolarStorm-LX  
**SolarWinds-Inspired Real-World Linux CTF**

## 🎯 SolarStorm-LX CTF Machine

**SolarStorm-LX** is a custom-built Capture The Flag (CTF) virtual machine based on real-world tactics seen in the infamous SolarWinds supply chain breach.

You are dropped into a network where your only clue is a domain name. Your objective: infiltrate the system, uncover hidden backdoors, escalate to root, and collect the flags left behind by the attacker.

---

## 📖 Story Background

> In the shadows of a digital storm, an elite threat actor successfully infiltrated a software supply chain — embedding a malicious update in a trusted Linux package server.  
>  
> Months passed before strange outbound signals and backdoor scripts surfaced inside one of the organization's internal nodes: `solarstorm.smart`.  
>  
> You’re brought in as a cybersecurity specialist to run a forensic simulation on a cloned system. Your mission is to analyze its behavior, uncover the attack path, and discover how root-level control was gained and maintained.  
>  
> ⚠️ Trust no artifact. Treat every script as a suspect. You only get one shot.

---

## 📥 Download the Machine

➡️ [Download from Google Drive](https://drive.google.com/file/d/1suYbOAz-FmSGPWc_TGPNdFp85SYhV3w7/view?usp=sharing) *(insert actual link)*  
⚠️ Format: `.ova`  
Import into VirtualBox or VMware to begin your mission.

---

## 🧠 Instructions

- Boot the machine.
- Add `solarstorm.smart` to your `/etc/hosts` file.
- Begin recon and enumeration.
- All flags follow the format: `flag{...}`
- 🏁 **Total Flags to Capture: 6**
- There are no hand-holding hints — your hacker mindset is your best tool.

---

## 📝 Submit Your Flags & Feedback

If you’ve completed the mission, share your flags and feedback here:  
➡️ [Submit Flags & Feedback](https://docs.google.com/forms/d/e/1FAIpQLSerdrh-usK6dpgR2RW4oVyttiMgkTZf6va_Fm_-t5O5Agd3vg/viewform?usp=sharing)

Your input helps improve future CTF experiences 🕵️‍♂️💻

---

## ☕ Buy Me a Coffee?

If you enjoyed this machine and want to support future CTF releases:  
➡️ [Buy Me a Coffee via PayPal](https://www.paypal.me/mohsinquresh313)

Thank you for supporting independent cybersecurity creators 🖤

---

## 📊 Team Role Mapping

| Team         | Skills Practiced                                                  |
|--------------|-------------------------------------------------------------------|
| 🟥 Red Team   | Reconnaissance, Credential Harvesting, Persistence, PrivEsc      |
| 🟦 Blue Team  | Log Analysis, Bash History Review, Cronjob Detection             |
| 🟪 Purple Team| Combined attack simulation with detection tuning                 |
| 🧑‍💻 Learners | End-to-end Linux exploitation: web, local, forensic, root access   |

---

## 📣 Author

Crafted with precision by [@Mohsin Quresh](https://in.linkedin.com/in/mohsin-quresh)

---

> _This machine won’t self-destruct, but your patience might..._
