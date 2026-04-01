<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Jean-Philippe+Belliard&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Automatisation+IA+·+Agents+LLM+·+Workflows+n8n&descAlignY=58&descSize=16" width="100%"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/web-creat/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/webcreatjp-tech)
[![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io)

</div>

---

## Qui je suis

Consultant en automatisation IA basé en Provence, je conçois des **systèmes intelligents qui tournent en production** — pas des démos.

Mon terrain de jeu : connecter des LLMs locaux ou cloud à des processus métier réels, pour des PME qui n'ont ni DSI ni budget enterprise. Je viens du terrain (16 ans chef d'équipe BTP, puis support technique), ce qui change radicalement la façon dont je comprends les besoins.

```python
class JeanPhilippe:
    role        = "Consultant Automatisation & IA"
    stack       = ["n8n", "Ollama", "Mistral AI", "Claude API", "Qdrant", "Docker"]
    llms        = ["qwen2.5:14b", "mistral-large", "claude-sonnet-4"]
    philosophie = "Local-first · Production-ready · Terrain avant tout"
    disponible  = True  # missions freelance + intérim tech
```

---

## Projets en production

<table>
<tr>
<td width="50%">

### 🏭 [Mon Usine](https://github.com/webcreatjp-tech/n8n-mon-usine)
**Problème** : traitement manuel des factures fournisseurs (heures perdues, erreurs)  
**Solution** : pipeline OCR → extraction structurée → base de données → dashboard  
`PDF → Mistral OCR → PostgreSQL → Reporting`  
**Stack** : n8n · Mistral OCR · PostgreSQL

</td>
<td width="50%">

### 🏥 [SeniorAssist](https://github.com/webcreatjp-tech/n8n-senior-assist)
**Problème** : surveillance de personnes âgées à domicile, sans envoyer de vidéo dans le cloud  
**Solution** : détection locale, alertes Telegram famille, rapport LLM nocturne  
`Caméra → Frigate → Analyse LLM → Telegram`  
**Stack** : n8n · Frigate · Ollama · 100% RGPD local

</td>
</tr>
<tr>
<td width="50%">

### 🔍 RAG Documentations Techniques *(en cours)*
**Problème** : technicien poseur qui cherche une info dans 1 300+ pages PDF constructeurs  
**Solution** : chatbot local interrogeable en langage naturel, zéro cloud  
`FAAC · Came · Nice · Somfy · BFT · Cardin → Qdrant → qwen2.5`  
**Stack** : n8n · Qdrant · Ollama · qwen2.5:14b

</td>
<td width="50%">

### 📱 [LinkedIn Factory](https://github.com/webcreatjp-tech/n8n-linkedin-factory)
**Problème** : veille + rédaction + publication LinkedIn prend trop de temps  
**Solution** : pipeline automatisé de veille, rédaction IA, validation humaine, publication  
`Veille → LLM → Validation → Publication`  
**Stack** : n8n · Apify · Mistral

</td>
</tr>
<tr>
<td width="50%">

### 🤖 [Agents IA](https://github.com/webcreatjp-tech/n8n-ai-agents)
Agent personnel multi-outils via Telegram  
`Telegram → Router → Gmail · Agenda · Web · Fichiers`  
**Stack** : n8n · Ollama · Mistral · Claude API

</td>
<td width="50%">

### 🎓 [English Coach](https://github.com/webcreatjp-tech/n8n-english-coach)
Apprentissage de l'anglais assisté par IA : exercices adaptatifs, correction, suivi  
`Exercice → Correction LLM → Score → Progression`  
**Stack** : n8n · Ollama

</td>
</tr>
</table>

---

## Stack technique

<div align="center">

**Orchestration & Infra**  
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_24.04-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Self-hosted](https://img.shields.io/badge/Self--hosted-333333?style=flat-square)

**IA & LLM**  
![Claude](https://img.shields.io/badge/Claude_Sonnet-000000?style=flat-square&logoColor=white)
![Mistral](https://img.shields.io/badge/Mistral_Large-FF7000?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama_Local-333333?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant_RAG-DC244C?style=flat-square)

**Data & Intégrations**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=flat-square&logo=airtable&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white)

</div>

---

## Ce qui me différencie

Beaucoup de gens font des workflows n8n. Ce qui change ici :

**Local-first par conviction** — Ollama + hébergement local par défaut. Pas de données qui partent dans le cloud sans décision explicite. Adapté aux PME qui traitent des données clients sensibles (BTP, santé, immobilier).

**Background terrain** — 16 ans en pose et encadrement BTP avant l'automatisation. Je comprends ce que "ça marche pas" veut dire pour un chef d'équipe à 7h du matin, pas pour un consultant en salle de réunion.

**Production, pas POC** — Les projets listés ici ont tourné ou tournent chez des clients réels. Le code est dans les repos.

---

## Disponibilité

🟢 **Disponible** — missions freelance automatisation/IA et missions intérimaires tech (Provence / distanciel)

📬 Le plus simple : [LinkedIn](https://www.linkedin.com/in/web-creat/) ou une issue GitHub sur le repo qui t'intéresse.

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
