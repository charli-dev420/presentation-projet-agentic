# Security And Privacy / Securite et donnees

[EN](#english) | [FR](#francais)

## English

### Public Security Principles

- Least privilege for tools and data access.
- BYOK where partner or community evaluation requires participant-owned credentials.
- No raw public prompts or raw private traces.
- No API keys, tokens, local endpoints, or private configs in public artifacts.
- No hidden telemetry.
- Explicit consent before collecting or retaining evaluation data.
- Human confirmation for irreversible or mutating actions.
- Server-side validation for tool inputs.
- Prompt-injection and tool-boundary review before a private demo.
- Redacted proof cards instead of raw operational dumps.

### Data Categories

| Data | Public? | Rule |
| --- | --- | --- |
| Evidence level | Yes | Required for every meaningful claim. |
| Token or cost counts | Yes after redaction | Useful when tied to task class and context. |
| Model/provider names | Yes when safe | Helps reproducibility and buyer evaluation. |
| Raw prompts | No | Use hash, summary, or proof-card language. |
| Raw traces/logs | No | Summarize status, tool path, and decision. |
| Code snippets | No by default | Use architecture summaries or fingerprints unless cleared. |
| API keys/tokens | Never | Local/env only. |
| User identifiers | No | Use synthetic or randomized identifiers when needed. |
| Generated private assets | No by default | Use diagrams, screenshots only if cleared and redacted. |
| Cost ledger | Yes after redaction | Include context, task class, and limits. |

### Security Review Question

For every artifact, ask: could this reveal a credential, endpoint, private workflow, user identity, generated private asset, local path, or operational capability? If yes, redraw or summarize it.

## Francais

### Principes Publics De Securite

- Moindre privilege pour outils et acces donnees.
- BYOK quand evaluation partenaire ou communautaire demande des credentials propres au participant.
- Pas de prompts bruts publics ni traces privees brutes.
- Pas de cles API, tokens, endpoints locaux ou configs privees dans les artefacts publics.
- Pas de telemetrie cachee.
- Consentement explicite avant collecte ou retention de donnees d'evaluation.
- Confirmation humaine pour actions irreversibles ou mutating.
- Validation serveur des entrees outils.
- Revue prompt-injection et frontieres outil avant demo privee.
- Proof cards redigees au lieu de dumps operationnels bruts.

### Categories De Donnees

| Donnee | Public? | Regle |
| --- | --- | --- |
| Niveau de preuve | Oui | Requis pour chaque claim significatif. |
| Token ou cout | Oui apres redaction | Utile si lie a classe de tache et contexte. |
| Noms modele/provider | Oui si sans risque | Aide reproductibilite et evaluation acheteur. |
| Prompts bruts | Non | Utiliser hash, resume ou langage proof-card. |
| Traces/logs bruts | Non | Resumer statut, chemin outil et decision. |
| Extraits code | Non par defaut | Utiliser resumes architecture ou fingerprints sauf validation. |
| Cles API/tokens | Jamais | Local/env uniquement. |
| Identifiants utilisateur | Non | Utiliser identifiants synthetiques ou randomises si besoin. |
| Assets prives generes | Non par defaut | Utiliser diagrammes ou captures seulement si validees et redigees. |
| Cost ledger | Oui apres redaction | Inclure contexte, classe de tache et limites. |

### Question De Revue Securite

Pour chaque artefact, demander: cela peut-il reveler credential, endpoint, workflow prive, identite utilisateur, asset prive genere, chemin local ou capacite operationnelle? Si oui, redessiner ou resumer.
