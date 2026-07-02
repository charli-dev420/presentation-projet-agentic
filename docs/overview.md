# AI Workflow Overview / Vue generale outillage IA

[EN](#english) | [FR](#francais)

![AI workflow one-pager](../assets/one-pager.svg)

## English

### The Shape Of The Work

This repo presents a small set of tools around one main question: when AI-assisted work produces an output, can another person understand the run well enough to accept, revise, reuse, or reject it?

**Codex Model Orchestrator** is the main project. It frames a task, routes work, calls tools, records checks, and produces a readable decision surface.

**CodexToUnity**, **Mob'ia / ccomf-unity**, and **LocalAssetFactory** are concrete workflow surfaces. They make the orchestration deal with generated files, manifests, Unity imports, artifact states, ComfyUI jobs, and human review.

### Why This Repository Exists

The work is spread across orchestration, MCP/App SDK ideas, Unity bridges, ComfyUI product surfaces, and local asset loops. This repository gives a clean public reading path: what each project does, who it helps, how the workflow is checked, what visual material exists, and where support would move the work forward.

It is not a feature dump. It is a dossier for people who need to understand the product direction before testing, funding, hiring, collaborating, or reviewing one workflow in depth.

### Reading Path

Start with [Codex Model Orchestrator](projects/codex-model-orchestrator.md). Then read [CodexToUnity](projects/codextounity.md), [Mob'ia / ccomf-unity](projects/mobia-ccomf-unity.md), and [LocalAssetFactory](projects/local-asset-factory.md).

For usage, read [user flows](user-flows.md), [tutorials](tutorials.md), and [resources](resources.md). For validation, read [evidence](evidence.md), [evidence ledger](evidence-ledger.md), [proof pack](proof-pack.md), [QA matrix](qa-matrix.md), and [QA validation](qa-validation.md). For collaboration, read [project evaluation](project-evaluation.md), [open needs](partnership.md), [readiness notes](blockers.md), and [roadmap](roadmap.md).

### What Should Stay Clear

Codex Model Orchestrator is the product center. The Unity, ComfyUI, Mob'ia, and LocalAssetFactory pages are not side quests; they are proof surfaces where the orchestration has to handle real artifacts and real review decisions.

## Francais

### La Forme Du Travail

Ce repo presente un ensemble d'outils autour d'une question principale: quand un travail assiste par IA produit une sortie, est-ce qu'une autre personne peut comprendre le run assez bien pour accepter, reviser, reutiliser ou refuser le resultat ?

**Codex Model Orchestrator** est le projet principal. Il cadre une tache, route le travail, appelle les outils, enregistre les controles et produit une surface de decision lisible.

**CodexToUnity**, **Mob'ia / ccomf-unity** et **LocalAssetFactory** sont des surfaces de workflow concretes. Elles obligent l'orchestration a traiter fichiers generes, manifests, imports Unity, etats artefact, jobs ComfyUI et revue humaine.

### Pourquoi Ce Repo Existe

Le travail est reparti entre orchestration, idees MCP/App SDK, ponts Unity, surfaces produit ComfyUI et boucles asset locales. Ce repo donne un chemin de lecture public propre: ce que fait chaque projet, qui il aide, comment le workflow est controle, quels visuels existent et quel support ferait avancer le travail.

Ce n'est pas un inventaire de features. C'est un dossier pour les personnes qui doivent comprendre la direction produit avant de tester, financer, recruter, collaborer ou reviewer un workflow en detail.

### Chemin De Lecture

Commencer par [Codex Model Orchestrator](projects/codex-model-orchestrator.md). Lire ensuite [CodexToUnity](projects/codextounity.md), [Mob'ia / ccomf-unity](projects/mobia-ccomf-unity.md) et [LocalAssetFactory](projects/local-asset-factory.md).

Pour l'usage, lire [user flows](user-flows.md), [tutorials](tutorials.md) et [resources](resources.md). Pour la validation, lire [evidence](evidence.md), [evidence ledger](evidence-ledger.md), [proof pack](proof-pack.md), [QA matrix](qa-matrix.md) et [QA validation](qa-validation.md). Pour collaboration, lire [project evaluation](project-evaluation.md), [open needs](partnership.md), [readiness notes](blockers.md) et [roadmap](roadmap.md).

### Ce Qui Doit Rester Clair

Codex Model Orchestrator est le centre produit. Les pages Unity, ComfyUI, Mob'ia et LocalAssetFactory ne sont pas des detours; ce sont des surfaces de preuve ou l'orchestration doit gerer de vrais artefacts et de vraies decisions de revue.
