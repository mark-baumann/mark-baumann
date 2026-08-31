# Mark Baumann

**KI-Entwickler aus München · 26 Jahre · Bachelorand**

- 🌐 Portfolio: https://markb.de
- 💻 GitHub: https://github.com/mark-baumann

---

# Kurzbeschreibung

Ich baue KI-Systeme von den mathematischen Grundlagen bis zum produktiven Deployment: Neuronale Netze (PyTorch), RAG-Pipelines und autonome Agenten.

**Fokus:** nachprüfbare Modelle, zuverlässige Infrastruktur und produktive Endpunkte.

---

# Projekte & Dienste

Alle Projekte und Live-Dienste sind zentral über **https://markb.de** erreichbar.

## Deployment-Status (Aufnahme: 31.08.2026)

Kanonische Liste gemäß `infrastruktur-deployment/config/services.yaml`.
Deployment-Plattform: Cloudflare-Tunnel (`markb-tunnel-v4`) → Host srv1741927 (Userspace, kein Docker). Der Raspberry Pi wird nicht mehr als Deployment-Ziel genutzt.

Legende: 🟢 Live (HTTP 200) · 🔴 Offline (Tunnel erreichbar, Backend läuft nicht) · ⚪ nicht öffentlich (bewusst `expose: false`) · ➖ Repo fehlt auf GitHub

| Dienst | GitHub-Repo | URL | Status |
|--------|-------------|-----|--------|
| Schach | schach-reinforcement-lernen | https://schach.markb.de | 🟢 Live |
| Vergleich-Agenten | vergleichs-ki | https://vergleichs-ki.markb.de | 🔴 Offline (Tunnel ok, Backend fehlt) |
| Handels-Agenten | handels-agenten | https://handels-agenten.markb.de | 🔴 Offline (Tunnel ok, Backend fehlt) |
| Dokumenten-Agent | rag-agent-langgraph | https://dokumenten-agent.markb.de | 🔴 Offline (Tunnel ok, Backend fehlt) |
| Aktienanalyse | taegliche-aktienanalyse | https://aktienanalyse.markb.de | 🔴 Offline (Tunnel ok, Backend fehlt) |
| eBay-Agent | ebay-scraping-agent | https://ebay-agent.markb.de | 🔴 Offline (Tunnel ok, Backend fehlt) |
| Browser-Nutzung | ➖ (Repo fehlt) | https://browser-nutzung.markb.de | 🔴 Offline (Tunnel ok, Repo + Backend fehlen) |
| Open-Manus | open-manus | https://open-manus.markb.de | 🔴 Offline (Tunnel ok, Backend fehlt) |
| ART-Agent | ART | https://art-agent.markb.de | 🔴 Offline (Tunnel ok, Backend fehlt) |
| Spam-Klassifikation | spam-klassifikation | — | ⚪ nicht öffentlich (kein Streamlit-UI) |
| Daten-Feed-Worker | ➖ (Repo fehlt) | — | ⚪ Headless, nicht deployed |
| OCR-Agent | ➖ (Repo fehlt) | — | ⚪ Headless/GPU, nicht deployed |
| Status-Dashboard | ➖ (Repo fehlt) | https://status.markb.de | ⏸ Stillgelegt per Nutzer-Direktive |

> Hinweis: Der Cloudflare-Tunnel und DNS sind für alle Domains korrekt konfiguriert — alle 10 öffentlichen Dienste sind per HTTPS erreichbar. Der Status bezieht sich auf das jeweilige Backend auf dem Host. Live-Bring-up der Dienste erfolgt Schritt für Schritt über `infrastruktur-deployment` (Issue-Tracking: AUG-106).

## Projekte ohne Live-UI

| Projekt | Beschreibung |
|---------|--------------|
| nanoGPT | Training & Sampling |
| Spam-Klassifikation | spam-klassifikation |
| infrastruktur-deployment | Deterministische Deployment-Pipeline |
| ocr-erkennung | OCR-Erkennung mit DeepSeek OCR |
| handschrifterkennung-mnist | Handschrifterkennung mit dem MNIST-Datensatz |
| neuronales-netz-von-grund-auf | Neuronales Netz von Grund auf implementiert |
| algorithmen | Allgemeine Algorithmen |
| ki-algorithmen | Algorithmen aus der KI |
| mathe-algorithmen | Algorithmen aus der Mathematik |
| pytorch-lernen | PyTorch-Lernprojekt |



## Forks
| Projekt | Beschreibung |
|---------|--------------|
| hermes-agent | Autonomer KI-Agent / Agentensystem |
| opencode | Coding-Agent / Entwicklungsumgebung |
| n8n | Automatisierung von Prozessen mit KI |




---

# Tech-Stack

**Programmiersprache**
- Python

**Machine Learning & KI**
- PyTorch
- NumPy
- LangGraph
- Qdrant
- OpenPipe
- Weights & Biases (W&B)

**Web & Anwendungen**
- Streamlit
- WordPress

**Automatisierung & DevOps**
- GitHub Actions
- Docker
- n8n
- Cloudflare
- Linux