<div align="center">
 
<img src="https://capsule-render.vercel.app/api?type=waving&color=00e5a0,00c880,0f6e56&height=180&section=header&text=SPARK%20IA&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=L'intelligence%20artificielle%2C%20enfin%20responsable.&descAlignY=60&descSize=16" width="100%"/>
 
<br/>
 
![Status](https://img.shields.io/badge/Status-Prototype%20interactif-00e5a0?style=flat-square&labelColor=0f1a1f)
![Stack](https://img.shields.io/badge/Stack-HTML%20·%20CSS%20·%20JavaScript-00c880?style=flat-square&labelColor=0f1a1f)
![Context](https://img.shields.io/badge/Contexte-Projet%20Green%20AI-0f6e56?style=flat-square&labelColor=0f1a1f)
 
### [Voir la demo live](https://anais-rnct.github.io/spark-ia/spark-ia.html)
 
</div>
 
---
 
## Le problème
 
Les entreprises déploient des modèles d'IA de plus en plus lourds, mais personne ne mesure leur coût environnemental réel.
 
- L'entraînement d'un LLM peut émettre autant de CO2 qu'un vol transatlantique
- L'inférence quotidienne de milliers de requêtes représente une consommation électrique massive et invisible
- Des datacenters sous-optimisés génèrent un gaspillage caché qui fait exploser les coûts
 
SPARK IA rend cet impact visible, mesurable et actionnable.
 
---
 
## La solution
 
Plateforme SaaS conçue pour les grandes entreprises qui veulent piloter l'empreinte carbone de leurs systèmes d'IA.
 
| Module | Description |
|--------|-------------|
| Dashboard | Vue temps réel de la consommation énergétique et des émissions CO2 par projet IA |
| Sources de données | Connexion à AWS, Azure, GCP, OpenAI API, Anthropic API, Datadog, SAP |
| Simulateur | Anticiper l'impact d'un changement de modèle ou de datacenter avant de migrer |
| Infrastructure | Cartographie des datacenters avec PUE, intensité carbone, conformité RGPD |
| Rapport RSE | Génération automatique du rapport d'impact IA — format CSRD / ESG ready |
 
---
 
## Lancer le prototype
 
```bash
git clone https://github.com/anais-rnct/spark-ia.git
cd spark-ia
# Ouvrir spark-ia.html dans Chrome / Firefox / Edge
```
 
Ou directement en ligne : [anais-rnct.github.io/spark-ia/spark-ia.html](https://anais-rnct.github.io/spark-ia/spark-ia.html)
 
---
 
## Fonctionnalités interactives
 
- Navigation entre les 5 modules
- Simulateur dynamique : changez le modèle, le volume de requêtes, le datacenter — les économies CO2 et financières se calculent en temps réel
- Connexion et déconnexion des sources de données simulées
- Recommandations générées automatiquement
- Score "IA Responsable" calculé par projet
 
---
 
## Stack technique
 
```
Frontend   HTML5 · CSS3 · JavaScript vanilla
Fonts      Cabinet Grotesk · Instrument Mono
Data       Simulation de métriques réalistes (CO2, kWh, coûts cloud)
```
 
Aucune dépendance externe — fichier unique.
 
---
 
## Exemple de résultats
 
Pour un projet de détection de fraude avec 22 000 requêtes/jour sur GPT-4 hébergé US-East :
 
| Scénario | CO2/an | Coût API/an | Énergie/an |
|----------|--------|-------------|------------|
| Actuel — GPT-4, US-East | 5.9 t CO2 | 128 k€ | 18.6 GWh |
| Optimisé — Mistral 7B, EU-West | 0.05 t CO2 | 12 k€ | 274 MWh |
| Réduction | -99% | -116 k€/an | -98% |
 
---
 
## Autrice
 
**[Anaïs Renonciat](https://github.com/anais-rnct)** — Etudiante ingénieure, en recherche d'alternance en cybersécurité.
 
Projet développé dans le cadre d'un travail sur la Green AI et la responsabilité environnementale des systèmes d'intelligence artificielle en entreprise.
 
---
 
## Licence
 
MIT — libre d'utilisation avec attribution.
 
<img src="https://capsule-render.vercel.app/api?type=waving&color=00e5a0,00c880,0f6e56&height=100&section=footer" width="100%"/>
