# Project Overview

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

This page gives the public overview of the agentic project family.

The repository is not limited to one app or one technical stack. It presents projects where a language model has a central role in the workflow: reading context, preparing work, calling tools, generating material, inspecting output, summarizing state or helping a person decide what comes next.

Some projects can also appear in other showcases. A Unity project can appear here when the LLM is central. A music project can appear here when the LLM helps evaluate presets. An image tool can appear here when Codex or another LLM drives the editing loop.

---

## Core idea

The common idea is not full autonomy.

The useful pattern is:

```text
LLM support → controlled tools → visible output → human review
```

The LLM should make the workflow easier to understand, not harder to audit.

A project is stronger when a reader can quickly answer:

- what the user asked for;
- what the LLM did;
- what tool or surface was involved;
- what artifact, state or note came out;
- what still needs review;
- what decision comes next.

---

## Project families

| Family | Projects | Agentic angle |
| --- | --- | --- |
| **Orchestration** | Codex Model Orchestrator, MCP / Apps SDK surfaces | Task routing, tool calls, readable runs, confirmations and decision surfaces. |
| **Unity and editor assistance** | Agent Unity, CodexToUnity, Mob’ia Unity Extension | Scene reading, editor preparation, handoff notes and review in project context. |
| **Assets and 3D candidates** | LocalAssetFactory, Splat to Assets | Manifest logic, conversion planning, import checks and candidate review. |
| **Product surfaces** | Mob’ia Android, Mob’ia / ccomf-unity | Job states, artifact states, client-readable summaries and next actions. |
| **Creative assistants** | uwdevst_hub, Codex Image Génial | Preset evaluation, image-edit planning, comparison and iterative review. |

---

## What this repository should not become

This repository should not become a dump of every Unity, 3D, music or image detail.

Those topics can have their own showcases. Here, the question stays focused:

```text
What role does the LLM play in the workflow?
```

---

## Public boundary

The public repository can show positioning, pages, diagrams, screenshots, examples, review logic and clear limits.

It should not expose private source code, credentials, private prompts, sensitive automation details, unreleased binaries or internal proof archives.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Cette page donne la vue publique de la famille de projets agentic.

Le dépôt ne se limite pas à une app ou à une stack technique. Il présente les projets où un modèle de langage occupe un rôle central dans le workflow : lire le contexte, préparer le travail, appeler des outils, générer de la matière, inspecter une sortie, résumer un état ou aider une personne à décider la suite.

Certains projets peuvent aussi apparaître dans d’autres vitrines. Un projet Unity peut apparaître ici lorsque le LLM est central. Un projet musique peut apparaître ici lorsque le LLM aide à évaluer des presets. Un outil image peut apparaître ici lorsque Codex ou un autre LLM pilote la boucle d’édition.

---

## Idée centrale

L’idée commune n’est pas l’autonomie totale.

Le modèle utile est :

```text
support LLM → outils contrôlés → sortie visible → revue humaine
```

Le LLM doit rendre le workflow plus simple à comprendre, pas plus difficile à auditer.

Un projet est plus solide lorsqu’un lecteur peut répondre rapidement :

- ce que l’utilisateur a demandé ;
- ce que le LLM a fait ;
- quel outil ou quelle surface a été impliqué ;
- quel artefact, état ou note est sorti ;
- ce qui doit encore être revu ;
- quelle décision vient ensuite.

---

## Familles de projets

| Famille | Projets | Angle agentic |
| --- | --- | --- |
| **Orchestration** | Codex Model Orchestrator, surfaces MCP / Apps SDK | Routage de tâches, appels d’outils, runs lisibles, confirmations et surfaces de décision. |
| **Unity et assistance éditeur** | Agent Unity, CodexToUnity, Mob’ia Unity Extension | Lecture de scène, préparation éditeur, notes de handoff et revue en contexte projet. |
| **Assets et candidats 3D** | LocalAssetFactory, Splat to Assets | Logique manifest, plan de conversion, contrôles d’import et revue des candidats. |
| **Surfaces produit** | Mob’ia Android, Mob’ia / ccomf-unity | États de jobs, états d’artefacts, résumés lisibles côté client et prochaines actions. |
| **Assistants créatifs** | uwdevst_hub, Codex Image Génial | Évaluation de presets, planification d’édition image, comparaison et revue itérative. |

---

## Ce que ce dépôt ne doit pas devenir

Ce dépôt ne doit pas devenir un dump de tous les détails Unity, 3D, musique ou image.

Ces sujets peuvent avoir leurs propres vitrines. Ici, la question reste centrée :

```text
Quel rôle le LLM joue-t-il dans le workflow ?
```

---

## Limite publique

Le dépôt public peut montrer le positionnement, les pages, schémas, captures, exemples, logique de revue et limites claires.

Il ne doit pas exposer les sources privées, credentials, prompts privés, détails d’automatisation sensibles, binaires non publiés ou archives de preuve internes.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
