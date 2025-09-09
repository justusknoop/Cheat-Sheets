# <PROJEKTNAME>
<!-- Kurz, präzise: Ein Satz der erklärt, was/wieso. -->
> <Einzeilige Projektbeschreibung/USP>

<!-- Badges (optional) -->
<!--
![Build](https://img.shields.io/github/actions/workflow/status/<org>/<repo>/ci.yml)
![Version](https://img.shields.io/github/v/release/<org>/<repo>)
![License](https://img.shields.io/badge/license-MIT-blue)
-->

## Schnellzugriff
[Demo](#demo) • [Installation](#installation) • [Konfiguration](#konfiguration) • [Nutzung](#nutzung) • [Troubleshooting](#troubleshooting)

## Inhaltsverzeichnis
- [Überblick](#überblick)
- [Systemvoraussetzungen](#systemvoraussetzungen)
- [Installation](#installation)
- [Konfiguration](#konfiguration)
- [Nutzung](#nutzung)
- [Beispiele](#beispiele)
- [Architektur](#architektur)
- [Qualitätssicherung](#qualitätssicherung)
- [CI/CD](#cicd)
- [Sicherheit](#sicherheit)
- [Performance](#performance)
- [Roadmap](#roadmap)
- [Migration/Upgrades](#migrationupgrades)
- [Troubleshooting](#troubleshooting)
- [FAQ](#faq)
- [Beitragen](#beitragen)
- [Lizenz](#lizenz)
- [Maintainer & Dank](#maintainer--dank)
- [Changelog](#changelog)

## Überblick
Kurze, nicht-marketinglastige Beschreibung:
- Problem
- Zielgruppe
- Kernfunktionen (3–5 Bulletpoints)
- Status: `alpha | beta | stable`

## Systemvoraussetzungen
- OS/Arch: Linux/macOS/Windows, x64/arm64
- Laufzeit/Runtime: Node ≥ 20, Python ≥ 3.11, .NET 8, PowerShell 7.4, …
- Abhängigkeiten: Docker, Git, <…>
- Hardware/Ports: <…>

## Installation
```bash
# Klonen
git clone https://github.com/<org>/<repo>.git
cd <repo>

# Variante A: Docker
docker compose up -d

# Variante B: Lokal
<paketmanager-install>   # z. B. npm ci / pip install -r requirements.txt / dotnet restore