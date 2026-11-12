<!-- Facts here mirror https://solomon.wayler.tech (the source of truth). See AGENTS.md before editing. -->
# Hey, I'm Solomon Njenga 👋

**IT Systems & Security · Founder of [WaylerTech](https://wayler.tech) · Final-year CS @ Tharaka University (graduating 2027)**

I keep real systems working and trustworthy for the people who depend on them. I fix them, build them and secure them.

I enjoy understanding how systems work beneath the surface: how they communicate, how they fail and how they can be secured. I prefer:

- Reading packet captures over social media feeds
- Solving real problems over memorising theory
- Understanding systems deeply instead of using them blindly

---

## 🔧 What I've been doing

- **ICT Intern at Gertrude's Children's Hospital, Nairobi (May–Aug 2026).** I migrated ~30 clinical workstations to Windows 11, administered Active Directory accounts, terminated ~15 Cat6 runs for VoIP phones, set up the endpoints for the DaktariSmart telemedicine link to Lamu, Samburu, Baringo and other remote areas, and applied Data Protection Act 2019 controls on machines that handle patient data.
- **Founder of [WaylerTech](https://wayler.tech) (since Jul 2024).** I run a small IT business doing repairs, Linux installs, networking and custom bootable drives. I built its platform myself and write the WaylerLab repair guides.
- **ISACA Tharaka University Student Group.** Social media manager since Sep 2025. I facilitated a live Linux command-line CTF for 50+ students at the overnight HackNight, and gave talks, including "Digital Forensics – The Cyber Detective".
- **Hackathons.** 3rd place at the Tharaka University Cybersecurity & AI Hackathon (Feb 2026), with a team project on detecting AI-generated work, deepfakes and email spoofing. I also built and pitched prototypes at BushHack (Mt Kenya Innovation Week) and the AYSC 2026 Climate Hackathon.
- **IEEE student member.** I led registration and guest arrival (16 volunteers) at the launch of the Tharaka University IEEE Student Branch in Oct 2026.

Every one of these has a dated record with photos at [solomon.wayler.tech/records](https://solomon.wayler.tech/records).

---

## 🏗️ Projects

### [WaylerTech platform](https://wayler.tech)
The full business system behind my IT company: quote requests with photo uploads, a customer job tracker, orders, verified reviews and a role-based admin CMS. I built security in from the start:

- owner / admin / editor roles, enforced with Postgres row-level security
- an audit log on every change
- rate limiting with salted IP hashes, so no raw IPs are stored
- private uploads through one-time signed URLs
- an anonymous feedback form that really is anonymous

Self-hosted on a Linux server behind Caddy (systemd, automatic HTTPS).

`Next.js` `TypeScript` `Supabase` `PostgreSQL` `Tailwind` `Linux` `Caddy`

### [Campus E-Voting System](https://evoting-system-nine.vercel.app/)
A prototype voting platform with role-based access and real-time tallying, built to cut paper use and manual counting errors on campus.

`JavaScript` `Node.js` `HTML/CSS`

### [Vee Beauty World](https://vee-beauty-world.vercel.app/)
A responsive website template for salons and other small businesses.

`React` `CSS`

---

## 🛠️ What I work with

**Systems:** Windows 10/11 deployment · Active Directory · Linux administration · hardware diagnostics & repair

**Networking:** Cat6 / T568B cabling · VoIP · TCP/IP troubleshooting · Wireshark

**Security:** endpoint hardening · access control · Data Protection Act 2019 controls · secure web app design (RLS, RBAC, audit logging, rate limiting) · digital forensics basics

**Building:** TypeScript · JavaScript · React · Next.js · Node.js · PostgreSQL · Bash · Python · Git

---

## 🧪 Currently exploring

- Active Directory: how it's attacked, and how those attacks are detected
- Linux hardening
- Detection engineering
- Security automation with Python and Bash

---

## 🌐 Find me

[Website](https://solomon.wayler.tech) · [WaylerTech](https://wayler.tech) · [LinkedIn](https://www.linkedin.com/in/njenga-solomon) · [Email](mailto:njengasolomon10@gmail.com)

> *"Understand the system deeply enough to build it, break it, and defend it."*
