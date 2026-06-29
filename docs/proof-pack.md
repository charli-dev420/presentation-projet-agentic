# Public Proof Pack / Pack de preuves public

[EN](#english) | [FR](#francais)

## English

### Purpose

The proof pack is the public-safe replacement for raw traces. It lets a reader understand what was attempted, how it was bounded, what happened, how it was checked, and what a human decided.

### Proof Pack Contents

| Proof item | Source surface | Current public level | What it supports |
| --- | --- | --- | --- |
| Claim levels L0-L5 | Orchestrator proof method | L1 | Clear language for what can and cannot be claimed. |
| QA gates | Orchestrator, workflows, scenarios | L1-L2 | Evaluation of agentic outputs before acceptance. |
| Measurement method | Orchestrator benchmark framing | L1-L2 | Discussion of accepted-task cost, failures, human score, and correction time. |
| MCP / Apps SDK interaction model | Orchestrator product surface | L1 | Separation of status, actions, read/write boundaries, and decision UI. |
| Human decision record | User flows and scenarios | L1 | Acceptance, revision, rejection, escalation, or blocked status. |
| CodexToUnity prototype framing | Public bridge documentation | L1-L2 | How a Unity handoff can be scoped and checked. |
| Mob'ia / ccomf-unity product map | Private-source summary | L1 | How ComfyUI work becomes profiles, jobs, artifacts, clients, and review. |
| LocalAssetFactory workflow | Private/local-source summary | L1 | How asset generation can be connected to manifest, normalization, import, and review. |

### Public Proof Card Template

| Field | Example content |
| --- | --- |
| Task class | Orchestrator proof loop, Unity asset loop, ComfyUI product job, or Apps SDK / MCP review. |
| Scope | Allowed tools, data, actions, budget, and private boundaries. |
| Execution path | Tool/sub-agent path summarized without raw prompts or private traces. |
| Evidence level | L0-L5 label with reason. |
| QA result | Passed, revised, failed, blocked, or needs private review. |
| Human decision | Accepted, revise, reject, archive, escalate, or continue to pilot. |
| Measurement | Cost/time/failure/correction signal when available and safe to publish. |
| Redaction | What was removed and why. |

### What A Private Demo Can Add

A private demo may show rawer operational detail under agreement: live run, internal dashboard, logs, source snippets, tool definitions, or generated assets. The public artifact after that demo should still be a redacted proof card, not a dump of private material.

## Francais

### Objectif

Le proof pack remplace publiquement les traces brutes. Il permet de comprendre ce qui etait tente, comment c'etait borne, ce qui s'est passe, comment c'etait controle et ce qu'un humain a decide.

### Contenu Du Proof Pack

| Element de preuve | Surface source | Niveau public actuel | Ce que cela soutient |
| --- | --- | --- | --- |
| Niveaux de claim L0-L5 | Methode preuve orchestrateur | L1 | Langage clair pour ce qui peut ou non etre affirme. |
| Gates QA | Orchestrateur, workflows, scenarios | L1-L2 | Evaluation des sorties agentiques avant acceptation. |
| Methode de mesure | Cadrage benchmark orchestrateur | L1-L2 | Discussion cout par tache acceptee, echecs, score humain et temps de correction. |
| Modele interaction MCP / Apps SDK | Surface produit orchestrateur | L1 | Separation statut, actions, frontieres read/write et UI de decision. |
| Record decision humaine | User flows et scenarios | L1 | Acceptation, revision, rejet, escalation ou statut blocked. |
| Cadrage prototype CodexToUnity | Documentation pont public | L1-L2 | Comment un handoff Unity peut etre cadre et controle. |
| Carte produit Mob'ia / ccomf-unity | Resume de source privee | L1 | Comment ComfyUI devient profils, jobs, artefacts, clients et revue. |
| Workflow LocalAssetFactory | Resume source privee/locale | L1 | Comment la generation asset se relie a manifest, normalisation, import et revue. |

### Template De Proof Card Publique

| Champ | Exemple de contenu |
| --- | --- |
| Classe de tache | Proof loop orchestrateur, boucle asset Unity, job produit ComfyUI ou revue Apps SDK / MCP. |
| Perimetre | Outils, donnees, actions, budget et frontieres privees autorises. |
| Chemin execution | Chemin outil/sous-agent resume sans prompts bruts ni traces privees. |
| Niveau de preuve | Label L0-L5 avec raison. |
| Resultat QA | Passed, revised, failed, blocked ou revue privee necessaire. |
| Decision humaine | Accepter, reviser, refuser, archiver, escalader ou continuer vers pilote. |
| Mesure | Signal cout/temps/echec/correction quand disponible et publiable. |
| Redaction | Ce qui a ete retire et pourquoi. |

### Ce Qu'une Demo Privee Peut Ajouter

Une demo privee peut montrer plus de detail operationnel sous accord: run live, dashboard interne, logs, extraits source, definitions outils ou assets generes. L'artefact public apres demo doit rester une proof card redigee, pas un dump de materiel prive.
