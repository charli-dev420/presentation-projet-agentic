# QA Matrix / Matrice QA

[EN](#english) | [FR](#francais)

![AI workflow QA matrix](../assets/qa-matrix.svg)

## English

### Matrix

| Surface | What must be checked | Useful output |
| --- | --- | --- |
| Codex Model Orchestrator | Goal, scope, tool path, checks, uncertainty, human decision. | Run result card. |
| MCP / App SDK | Status readability, read/write separation, confirmation point, decision view. | UI review note. |
| CodexToUnity | Target asset, manifest, import criteria, Unity handoff. | Handoff review note. |
| Mob'ia / ccomf-unity | Profile, job, artifact state, client surface, next action. | Job lifecycle note. |
| LocalAssetFactory | Manifest, normalization, import, socket/scene fit, review decision. | Asset candidate note. |

### Rule

Do not treat output as complete just because a tool produced something. The workflow is complete only when the result is checked against the surface it is meant to serve.

## Francais

### Matrice

| Surface | Ce qui doit etre controle | Sortie utile |
| --- | --- | --- |
| Codex Model Orchestrator | Objectif, perimetre, chemin outil, controles, incertitude, decision humaine. | Carte resultat de run. |
| MCP / App SDK | Lisibilite statut, separation read/write, point confirmation, vue decision. | Note revue UI. |
| CodexToUnity | Asset cible, manifest, criteres import, handoff Unity. | Note revue handoff. |
| Mob'ia / ccomf-unity | Profil, job, etat artefact, surface client, prochaine action. | Note cycle de vie job. |
| LocalAssetFactory | Manifest, normalisation, import, fit socket/scene, decision revue. | Note candidat asset. |

### Regle

Ne pas traiter une sortie comme terminee seulement parce qu'un outil a produit quelque chose. Le workflow est termine seulement quand le resultat est controle contre la surface qu'il doit servir.
