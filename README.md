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

OPuppetX is an offline, read-only configuration-hardening auditor for Puppet. It parses puppet.conf, autosign and auth.conf, Hiera/eyaml, manifests and Puppetfiles, and flags weaknesses in certificate authority, autosigning, TLS and secret handling. Secrets are masked and findings map to CWE and MITRE references.

---

## ✨ Features

- Stdlib parsers for INI, HOCON, YAML, Puppet DSL and Puppetfile
- puppet.conf CA/CRL/autosign and agent/report settings analysis
- autosign.conf glob and policy-executable review correlated with CA SANs
- auth.conf, puppetserver/webserver TLS and PuppetDB checks
- Hiera/eyaml secret and key-permission checks plus manifest (.pp) exec/file/password review
- r10k/Puppetfile pin checks with TXT/MD/JSON/CSV/SARIF export and CI gates

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OPuppetX -p /etc/puppetlabs/puppet/puppet.conf
./OPuppetX --scan --root /mnt/collected --sarif -o report.sarif
./OPuppetX -p ./puppet --fail-on high
./OPuppetX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
