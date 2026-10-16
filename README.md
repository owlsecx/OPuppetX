# 🦉 OPuppetX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OPuppetX** — Puppet Configuration-Hardening Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

Puppet Server / CA / PuppetDB / Hiera / manifest security-hardening auditor

---

## ✨ Features

- Stdlib INI / HOCON / YAML / Puppet DSL / Puppetfile parsers
- puppet.conf CA, CRL, autosign, agent & report settings
- autosign.conf globs + policy executables, CA SAN / authz extensions correlated with broad autosigning
- auth.conf rules, puppetserver / webserver TLS, PuppetDB
- Hiera / eyaml secrets & key perms, manifests (.pp) exec / file / password / source checks, r10k & Puppetfile pins
- SSL dir key permissions; secrets masked everywhere
- Export TXT / MD / JSON / CSV / SARIF; --demo, --fail-on

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OPuppetX
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
