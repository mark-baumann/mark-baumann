
# Mark Baumann

**KI-Entwickler aus München · 26 Jahre · Bachelorand**

- 🌐 Portfolio: https://markb.de
- 💻 GitHub: https://github.com/mark-baumann

---

# Kurzbeschreibung

Ich baue KI-Systeme von den mathematischen Grundlagen bis zum produktiven Deployment: Neuronale Netze (PyTorch), RAG-Pipelines und autonome Agenten.

**Fokus:** nachprüfbare Modelle, zuverlässige Infrastruktur und produktive Endpunkte.

---

# Highlights

- 🧠 **~25 GitHub-Repositories** – zentral verknüpft über **markb.de**
- 🖥️ **14 Live-Dienste** (Raspberry Pi + Cloudflare-Tunnel, via infrastruktur-deployment)
- 🤖 **6 autonome KI-Mitarbeiter** (Monitoring, CI, Code-Verbesserungen, Daten-Feed)
- 🎓 **Bachelorarbeit:** *Architektur und Evaluation autonomer KI-Agenten*
  - Code & Gliederung: https://github.com/mark-baumann/bachelorarbeit

---

# Infrastruktur

Alle 14 Streamlit-Dienste laufen auf einem **Raspberry Pi** und sind über einen **Cloudflare-Tunnel** erreichbar. Das Deployment ist vollständig automatisiert:

```
GitHub Push (main) → GitHub Actions → Docker Build (ARM64) → Pi → Cloudflare → markb.de
```

- **Infrastruktur-Repo:** [infrastruktur-deployment](https://github.com/mark-baumann/infrastruktur-deployment) – deterministische Pipeline für alle Dienste

---

# Projekte & Dienste

Alle Projekte und Live-Dienste sind zentral über **https://markb.de** erreichbar.

## Live-Dienste (via Infrastruktur-Deployment, Raspberry Pi)

| Dienst | GitHub-Repo | URL |
|--------|-------------|-----|
| Vergleich-Agenten | vergleichs-ki | https://vergleichs-ki.markb.de |
| Handels-Agenten | handels-agenten | https://handels-agenten.markb.de |
| Dokumenten-Agent | rag-agent-langgraph | https://dokumenten-agent.markb.de |
| Aktienanalyse | taegliche-aktienanalyse | https://aktienanalyse.markb.de |
| eBay-Agent | ebay-scraping-agent | https://ebay-agent.markb.de |
| Browser-Nutzung | browser-nutzung | https://browser-nutzung.markb.de |
| Open-Manus | open-manus | https://open-manus.markb.de |
| Verstärkungslernen | agenten-verstaerkungslernen | https://verstaerkungslernen.markb.de |
| ART-Agent | ART | https://art-agent.markb.de |
| Email-agent |	Agent für E-Mail-Verarbeitung	Live-Dienst, falls UI vorhanden
| buchungssatz-agent |	KI-Assistent für Buchungssätze	Projekt
| schach-reinforcement-lernen | Reinforcement Learning / Schach	Projekt
| bewerbung-agent	| Agent für Bewerbungsprozesse + Browser-Automatisierung


## Projekte ohne Live-UI

| Projekt | Beschreibung |
|---------|--------------|
| nanoGPT | Training & Sampling |
| Spam-Klassifikation | spam-klassifikation |
| infrastruktur-deployment | Deterministische Deployment-Pipeline |
| ocr_recognition_nn | OCR-Erkennung mit DeepSeek OCR |
| handschrifterkennung-mnist | Handschrifterkennung mit dem MNIST-Datensatz |
| neuronales-netz-von-grund-auf | Neuronales Netz von Grund auf implementiert |
| algorithmen | Allgemeine Algorithmen |
| ki-algorithmen | Algorithmen aus der KI |
| mathe-algorithmen | Algorithmen aus der Mathematik |
| pytorch-lernen | PyTorch-Lernprojekt |



## Forks
|---------|--------------|
hermes-agent | Autonomer KI-Agent / Agentensystem
opencode	| Coding-Agent/Entwicklungsumgebung	
n8n	| Automatisierung von Prozessen mit KI 




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

