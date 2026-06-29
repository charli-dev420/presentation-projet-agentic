# Codex Model Orchestrator

[EN](#english) | [FR](#francais)

## English

### Role

Codex Model Orchestrator is the control layer for multi-agent work. It turns a user request into a bounded task, selects specialists or tools, records what happened, applies QA gates, and produces a summary a human can act on.

Its value is not simply parallel model calls. Its value is governance: scope, delegation, evidence, cost awareness, failure handling, and a final human decision.

### Public Product Surface

| Surface | What it shows publicly | Why it matters |
| --- | --- | --- |
| Task framing | Goal, constraints, allowed data, budget, and expected artifact. | Prevents vague automation and gives reviewers a stable contract. |
| Sub-agent orchestration | Which role handled which part of the task and how outputs were reviewed. | Makes delegation inspectable instead of magical. |
| MCP contracts | Tool boundaries, read/write separation, confirmation requirements. | Keeps powerful actions understandable and controllable. |
| Apps SDK views | Status, run summary, proof dashboard, and decision surfaces. | Turns hidden agent state into UI that a non-specialist can read. |
| Proof kit | L0-L5 claim levels, QA gates, evidence cards, redaction rules. | Lets buyers compare claims without seeing private traces. |
| Benchmark framing | Accepted-task cost, failure rate, human score, correction time. | Discusses value in concrete metrics, not generic productivity promises. |

### What A Strong Demo Looks Like

1. The user gives a bounded task.
2. The orchestrator creates a plan and identifies tool/sub-agent roles.
3. Read-only views show status before any sensitive action.
4. Mutating actions require explicit human confirmation.
5. Outputs are checked against task criteria and QA gates.
6. The final result includes evidence level, result status, revision notes, and human decision.
7. The public artifact is a redacted proof card.

### Useful For

- teams evaluating agentic workflows before internal adoption;
- buyers who need proof levels instead of broad AI claims;
- partners building MCP tools or Apps SDK surfaces;
- engineering teams that need multi-agent QA and run summaries;
- recruiters or clients evaluating orchestration, developer tooling, and AI governance skills.

### Public Boundary

Public material can discuss the method, product shape, proof model, QA gates, and scenario outputs. Private source, prompts, raw traces, local configs, endpoints, credentials, logs, provider outputs, and sensitive operational schemas remain unpublished.

## Francais

### Role

Codex Model Orchestrator est la couche de controle du travail multi-agent. Il transforme une demande utilisateur en tache bornee, choisit specialistes ou outils, enregistre ce qui s'est passe, applique des gates QA et produit un resume actionnable par un humain.

Sa valeur n'est pas seulement d'appeler plusieurs modeles en parallele. Sa valeur est la gouvernance: perimetre, delegation, preuve, conscience cout, gestion des echecs et decision humaine finale.

### Surface Produit Publique

| Surface | Ce que cela montre publiquement | Pourquoi c'est important |
| --- | --- | --- |
| Cadrage tache | Objectif, contraintes, donnees autorisees, budget et artefact attendu. | Evite l'automatisation vague et donne un contrat stable au reviewer. |
| Orchestration sous-agents | Quel role a traite quelle partie et comment les sorties ont ete revues. | Rend la delegation inspectable. |
| Contrats MCP | Frontieres outil, separation read/write, confirmations requises. | Rend les actions puissantes comprehensibles et controlables. |
| Vues Apps SDK | Statut, run summary, dashboard preuve et surfaces de decision. | Transforme l'etat agentique cache en UI lisible par non-specialiste. |
| Proof kit | Niveaux L0-L5, gates QA, proof cards, regles de redaction. | Permet aux acheteurs de comparer les claims sans voir les traces privees. |
| Cadrage benchmark | Cout par tache acceptee, taux echec, score humain, temps correction. | Discute la valeur en metriques concretes, pas en promesses generales. |

### A Quoi Ressemble Une Bonne Demo

1. L'utilisateur donne une tache bornee.
2. L'orchestrateur cree un plan et identifie roles outil/sous-agent.
3. Les vues read-only affichent le statut avant action sensible.
4. Les actions mutating demandent confirmation humaine explicite.
5. Les sorties sont controlees contre criteres de tache et gates QA.
6. Le resultat final inclut niveau de preuve, statut, notes de revision et decision humaine.
7. L'artefact public est une proof card redigee.

### Utile Pour

- equipes evaluant des workflows agentiques avant adoption interne;
- acheteurs qui veulent des niveaux de preuve plutot que claims IA larges;
- partenaires construisant outils MCP ou surfaces Apps SDK;
- equipes engineering ayant besoin de QA multi-agent et resumes de run;
- recruteurs ou clients evaluant orchestration, tooling developpeur et gouvernance IA.

### Frontiere Publique

Le public peut discuter methode, forme produit, modele de preuve, gates QA et sorties scenario. Source privee, prompts, traces brutes, configs locales, endpoints, credentials, logs, sorties provider et schemas operationnels sensibles restent non publies.
