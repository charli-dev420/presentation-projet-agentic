# Security And Privacy / Securite et donnees

[EN](#english) | [FR](#francais)

## English

### Principles

- Use least privilege for tools and data access.
- Keep API keys, tokens, endpoints, local configs, raw prompts, raw traces, and user identifiers out of public material.
- Require human confirmation for irreversible or write actions.
- Validate tool inputs server-side when a workflow becomes product-facing.
- Use written summaries and diagrams instead of raw operational dumps.
- Collect or retain evaluation data only with explicit consent.

### Data Handling

| Data | Publication rule |
| --- | --- |
| Product diagrams | Allowed when they do not expose endpoints, paths, credentials, or live user data. |
| Model or provider names | Allowed when they help reproducibility and do not reveal private operations. |
| Cost or timing signals | Allowed when summarized by task class. |
| Raw prompts, traces, logs | Do not publish; summarize the task and decision instead. |
| Generated assets | Publish only if specifically cleared for presentation. |
| User or account identifiers | Do not publish; use synthetic labels when examples are needed. |

### Review Question

Before publishing an artifact, ask whether it exposes a credential, endpoint, local path, private workflow, user identity, generated asset, or operational capability. If yes, summarize or redraw it.

## Francais

### Principes

- Utiliser le moindre privilege pour outils et acces donnees.
- Garder cles API, tokens, endpoints, configs locales, prompts bruts, traces brutes et identifiants utilisateur hors du materiel public.
- Demander confirmation humaine pour actions irreversibles ou d'ecriture.
- Valider les entrees outils cote serveur quand un workflow devient surface produit.
- Utiliser syntheses ecrites et diagrammes plutot que dumps operationnels bruts.
- Collecter ou conserver des donnees d'evaluation seulement avec consentement explicite.

### Gestion Des Donnees

| Donnee | Regle de publication |
| --- | --- |
| Diagrammes produit | Autorises s'ils n'exposent pas endpoints, chemins, credentials ou donnees utilisateur reelles. |
| Noms modele ou provider | Autorises s'ils aident la reproductibilite sans reveler operations privees. |
| Signaux cout ou timing | Autorises quand resumes par classe de tache. |
| Prompts, traces, logs bruts | Ne pas publier; resumer la tache et la decision. |
| Assets generes | Publier seulement s'ils sont valides pour presentation. |
| Identifiants utilisateur ou compte | Ne pas publier; utiliser des labels synthetiques si besoin d'exemple. |

### Question De Revue

Avant publication d'un artefact, demander s'il expose credential, endpoint, chemin local, workflow prive, identite utilisateur, asset genere ou capacite operationnelle. Si oui, resumer ou redessiner.
