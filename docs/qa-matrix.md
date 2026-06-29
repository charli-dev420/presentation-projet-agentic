# QA Matrix / Matrice QA

[EN](#english) | [FR](#francais)

## English

### QA Principle

Agentic QA is not only "did the model answer". It asks whether the work was scoped, executed within boundaries, checked, understandable, and accepted by a human.

| Surface | Public validation | Level | Decision signal | Private or excluded artifacts |
| --- | --- | --- | --- | --- |
| Codex Model Orchestrator | Claim levels, quality gates, measurement method, security/privacy framing, run-summary shape. | L1-L2 | Strong evaluation frame for agents, proof, and Apps SDK / MCP productization. | Prompts, raw traces, configs, endpoints, logs, private tools. |
| Apps SDK / MCP surface | Readable status, read/write separation, confirmation model, decision card, redaction note. | L1 | Shows how agentic state becomes usable UI. | Private server source, tool internals, local endpoints, credentials. |
| Orchestrator proof loop | Scope, selected tools/sub-agents, QA result, evidence level, human decision, failure/revision reason. | L1-L2 | Good first private-demo candidate. | Full prompts, provider outputs, local paths, raw run artifacts. |
| CodexToUnity | Public prototype, dry-run/smoke paths, expected manifest, Unity handoff criteria. | L1-L2 | Good scoped demo surface for Unity/ComfyUI bridge work. | Workflows, endpoints, GLB/FBX/OBJ, scenes, builds. |
| Mob'ia / ccomf-unity | Product map: profiles, async jobs, artifacts, Unity/web/mobile clients, review states. | L1 | Useful partnership map for ComfyUI productization. | Routes, infra, tokens, storage details, models, private generated outputs. |
| LocalAssetFactory | Asset-loop diagram, normalization checks, import checklist, scene-review criteria. | L1 | Supports private proof pack design for local asset workflows. | Services, internal screenshots, logs, generated assets, local configs. |

### Gate Checklist

| Gate | Pass signal |
| --- | --- |
| Scope | Goal, allowed actions, data boundary, and expected output are written. |
| Safety | Sensitive actions require human confirmation and private material is redacted. |
| Execution | Tool/sub-agent path is summarized and repeatable enough for review. |
| Verification | The output has checks appropriate to the surface: tests, dry-run, import review, or human scoring. |
| Evidence | Claim level and proof card are attached. |
| Decision | A human outcome is recorded: accept, revise, reject, archive, blocked, or continue. |

## Francais

### Principe QA

La QA agentique ne demande pas seulement "le modele a-t-il repondu". Elle demande si le travail etait cadre, execute dans les frontieres, controle, comprehensible et accepte par un humain.

| Surface | Validation publique | Niveau | Signal pour decision | Artefacts prives ou exclus |
| --- | --- | --- | --- | --- |
| Codex Model Orchestrator | Niveaux de claim, gates qualite, methode de mesure, securite/donnees, forme de run-summary. | L1-L2 | Cadre fort pour evaluer agents, preuves et productisation Apps SDK / MCP. | Prompts, traces brutes, configs, endpoints, logs, outils prives. |
| Surface Apps SDK / MCP | Statut lisible, separation read/write, modele de confirmation, carte decision, note redaction. | L1 | Montre comment l'etat agentique devient UI utilisable. | Source serveur privee, internals outil, endpoints locaux, credentials. |
| Proof loop orchestrateur | Perimetre, outils/sous-agents choisis, resultat QA, niveau de preuve, decision humaine, raison echec/revision. | L1-L2 | Bon candidat de premiere demo privee. | Prompts complets, sorties provider, chemins locaux, artefacts bruts. |
| CodexToUnity | Prototype public, dry-run/smoke paths, manifest attendu, criteres handoff Unity. | L1-L2 | Bonne surface de demo cadree pour pont Unity/ComfyUI. | Workflows, endpoints, GLB/FBX/OBJ, scenes, builds. |
| Mob'ia / ccomf-unity | Carte produit: profils, jobs async, artefacts, clients Unity/web/mobile, etats de revue. | L1 | Carte utile pour partenariat autour productisation ComfyUI. | Routes, infra, tokens, stockage, modeles, sorties generees privees. |
| LocalAssetFactory | Diagramme asset-loop, controles normalisation, checklist import, criteres revue scene. | L1 | Supporte le design d'un proof pack prive pour assets locaux. | Services, captures internes, logs, assets generes, configs locales. |

### Checklist De Gate

| Gate | Signal de passage |
| --- | --- |
| Perimetre | Objectif, actions autorisees, frontiere donnees et sortie attendue sont ecrits. |
| Securite | Actions sensibles confirmee par humain et materiel prive redige. |
| Execution | Chemin outil/sous-agent resume et assez repetable pour revue. |
| Verification | La sortie a les controles adaptes: tests, dry-run, revue import ou score humain. |
| Evidence | Niveau de claim et proof card attaches. |
| Decision | Resultat humain note: accepter, reviser, refuser, archiver, blocked ou continuer. |
