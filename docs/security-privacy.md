# Security And Privacy / Securite et donnees

[FR](#francais) | [EN](#english)

## Francais

### Principes publics

- Moindre privilege.
- BYOK par defaut quand applicable.
- Pas de prompts bruts dans les traces publiques.
- Pas de cles API dans les traces.
- Pas de telemetrie cachee.
- Consentement explicite avant collecte.
- Confirmation humaine pour actions irreversibles.
- Validation serveur des entrees outils.
- Tests prompt-injection avant soumission.

### Categories de donnees

| Donnee | Public? | Regle |
| --- | --- | --- |
| Token counts | Oui apres redaction | Utile aux benchmarks. |
| Model/provider names | Oui | Necessaire a la reproductibilite. |
| Raw prompts | Non | Hash ou resume redige. |
| Code snippets | Non par defaut | Fingerprints plutot que contenu. |
| API keys | Jamais | Env/local uniquement. |
| User identifiers | Non | IDs aleatoires si necessaire. |
| Cost ledger | Oui apres redaction | Avec contexte et limites. |

## English

Security is built on least privilege, BYOK where applicable, no raw public prompts, no API keys in traces, no hidden telemetry, explicit consent, human confirmation for irreversible actions, server-side validation, and prompt-injection testing.
