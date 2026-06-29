# Evidence / Preuves

[FR](#francais) | [EN](#english)

## Francais

### Niveaux de preuve publics

| Niveau | Sens | Claim autorise |
| --- | --- | --- |
| L0 | Instrumentation | Le projet sait produire des traces et rapports reproductibles. |
| L1 | Replay synthetique | Le pipeline peut rejouer des traces synthetiques et produire des rapports. |
| L2 | Micro-benchmark mainteneur | Un petit echantillon reel peut montrer un resultat sous conditions. |
| L3 | Benchmark community BYOK | Des soumissions externes redigees peuvent comparer les resultats. |
| L4 | Reproduction independante | Un tiers reproduit sur un autre repo ou jeu de taches. |
| L5 | Telemetrie production opt-in | Des donnees anonymisees avec consentement indiquent des tendances. |

### Preuves par scenario

| Scenario | Surface | Niveau | Preuve publique | Usage decision |
| --- | --- | --- | --- | --- |
| Proof loop agentique | Orchestrateur | L1-L2 | Quality gates, claim levels, methode de mesure, security/privacy model. | Evaluer la rigueur avant demo. |
| Benchmark redige | Orchestrateur | L1-L3 selon source | Couts par tache acceptee, echecs publies, score humain, temps de correction. | Discuter les gains sans promesse generale. |
| Unity asset loop | CodexToUnity / LocalAssetFactory | L1-L2 | Prototype public, dry-run/smoke, jobs, manifests, sockets, normalisation GLB. | Cadrer integration Unity. |
| Product layer ComfyUI | Mob'ia / ccomf-unity | L1 | Carte produit: profils, jobs async, artefacts, clients Unity/web/mobile. | Evaluer partenariat produit. |
| Gouvernance publique | Tous | L1 | Redaction policy, public scope, security/privacy, evidence ledger. | Verifier que la vitrine ne publie pas les bruts. |

## English

Evidence is organized by claim level: instrumentation, synthetic replay, maintainer benchmark, community benchmark, independent reproduction, and opt-in production telemetry. This showcase publishes only public-safe summaries and does not expose raw traces, prompts, private code, configs, endpoints, or logs.
