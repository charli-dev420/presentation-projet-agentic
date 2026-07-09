# Project Overview

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

This page gives the public overview of the agentic project family.

The repository is not the showcase for one single product. It is the map of projects where a language model has a central role in the workflow: reading context, planning, routing tools, generating candidates, editing artifacts, inspecting results, evaluating output or preparing a human decision.

Some projects can also appear in Unity, 3D, music or creative-tool showcases. That is normal. Here, they are included only when the LLM layer is important enough to explain separately.

---

## Core idea

A useful LLM workflow should not end with a vague answer.

It should leave a trace that can be reviewed:

```text
request → LLM role → tool or surface → artifact → checks → review → next decision
```

That pattern applies to orchestration, Unity scenes, generated assets, Android job surfaces, synth presets and image editing.

---

## Project families

| Family | Projects | Why it belongs here |
| --- | --- | --- |
| **Orchestration** | Codex Model Orchestrator, MCP / Apps SDK surfaces | The LLM structures work, calls tools and prepares readable decisions. |
| **Unity and editor assistance** | Agent Unity, CodexToUnity, Mob’ia Unity Extension | The LLM helps read scene context, prepare tasks and support review. |
| **Asset and 3D workflows** | LocalAssetFactory, Splat to Assets | The LLM helps organize generated candidates into inspectable assets. |
| **Product surfaces** | Mob’ia Android, Mob’ia / ccomf-unity | The LLM helps make jobs, artifacts and review states understandable. |
| **Creative assistants** | uwdevst_hub, Codex Image Génial | The LLM supports preset evaluation and image editing loops. |

---

## How to read this repository

Start with the README, then read:

1. [`agentic-projects.md`](agentic-projects.md) for the project map.
2. [`llm-roles.md`](llm-roles.md) for the role vocabulary.
3. One project page only, depending on the area being reviewed.
4. [`proof-summary.md`](proof-summary.md) if the question is about public proof boundaries.
5. [`open-needs.md`](open-needs.md) if the goal is feedback, collaboration or review.

The repository should stay simple enough for an external reader. The details of Unity, 3D, music or image implementation can live in their dedicated showcases.

---

## Public boundary

This public repository can show the map, positioning, workflow language, screenshots, diagrams and high-level review criteria.

It should not expose private source code, credentials, private prompts, private tool configuration, sensitive automation details, internal logs, unreleased binaries or raw proof archives.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Cette page donne la vue publique de la famille de projets agentic.

Le dépôt n’est pas la vitrine d’un seul produit. C’est la carte des projets où un modèle de langage occupe un rôle central dans le workflow : lire le contexte, planifier, router les outils, générer des candidats, éditer des artefacts, inspecter les résultats, évaluer une sortie ou préparer une décision humaine.

Certains projets peuvent aussi apparaître dans des vitrines Unity, 3D, musique ou outils créatifs. C’est normal. Ici, ils sont inclus seulement lorsque la couche LLM mérite d’être expliquée séparément.

---

## Idée centrale

Un workflow LLM utile ne doit pas se terminer par une réponse vague.

Il doit laisser une trace reviewable :

```text
requête → rôle LLM → outil ou surface → artefact → contrôles → revue → prochaine décision
```

Ce modèle s’applique à l’orchestration, aux scènes Unity, aux assets générés, aux surfaces Android de jobs, aux presets synthé et à l’édition d’image.

---

## Familles de projets

| Famille | Projets | Pourquoi c’est ici |
| --- | --- | --- |
| **Orchestration** | Codex Model Orchestrator, surfaces MCP / Apps SDK | Le LLM structure le travail, appelle des outils et prépare des décisions lisibles. |
| **Unity et assistance éditeur** | Agent Unity, CodexToUnity, Mob’ia Unity Extension | Le LLM aide à lire le contexte scène, préparer les tâches et soutenir la revue. |
| **Assets et workflows 3D** | LocalAssetFactory, Splat to Assets | Le LLM aide à organiser des candidats générés en assets inspectables. |
| **Surfaces produit** | Mob’ia Android, Mob’ia / ccomf-unity | Le LLM aide à rendre jobs, artefacts et états de revue compréhensibles. |
| **Assistants créatifs** | uwdevst_hub, Codex Image Génial | Le LLM soutient l’évaluation de presets et les boucles d’édition d’image. |

---

## Comment lire ce dépôt

Commencer par le README, puis lire :

1. [`agentic-projects.md`](agentic-projects.md) pour la carte projet.
2. [`llm-roles.md`](llm-roles.md) pour le vocabulaire des rôles.
3. Une seule page projet, selon la zone à revoir.
4. [`proof-summary.md`](proof-summary.md) si la question concerne les limites de preuve publique.
5. [`open-needs.md`](open-needs.md) si l’objectif est un retour, une collaboration ou une revue.

Le dépôt doit rester assez simple pour un lecteur externe. Les détails d’implémentation Unity, 3D, musique ou image peuvent vivre dans leurs vitrines dédiées.

---

## Limite publique

Ce dépôt public peut montrer la carte, le positionnement, le vocabulaire workflow, des captures, schémas et critères de revue haut niveau.

Il ne doit pas exposer les sources privées, credentials, prompts privés, configuration outil privée, détails d’automatisation sensibles, logs internes, binaires non publiés ou archives de preuve brutes.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
