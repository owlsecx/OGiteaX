# 🦉 OGiteaX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OWeb-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OGiteaX** — Gitea / Forgejo Configuration Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

Gitea / Forgejo self-hosted git forge configuration security auditor

---

## ✨ Features

- go-ini app.ini parser + GITEA__/FORGEJO__ env overrides (docker-compose, systemd Environment=, __FILE secrets)
- Installer lock, secret strength (masked), registration, OpenID, 2FA, passwords, cookies, reverse-proxy auth
- Git hooks RCE, webhook / migration SSRF, DB / SMTP, built-in SSH crypto, logging, metrics, Swagger, CORS
- Actions + act_runner, systemd / compose, permissions, gitea dump, NGINX front-end, version lifecycle
- CWE + MITRE ATT&CK, TXT / MD / JSON / CSV / SARIF, --demo self-test, --fail-on / --min-severity CI gates

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OGiteaX
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
