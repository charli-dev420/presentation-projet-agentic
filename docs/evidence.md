# Evidence / Preuves

[EN](#english) | [FR](#francais)

## English

### Public Evidence Levels

Evidence levels keep the repository honest. A low level is not a failure; it tells the reader what kind of claim is currently supportable.

| Level | Meaning | Allowed claim |
| --- | --- | --- |
| L0 | Instrumentation | The project can produce traces, counters, summaries, or reports for later review. |
| L1 | Synthetic replay or public method | The pipeline can replay synthetic or redacted examples and explain the method. |
| L2 | Maintainer micro-benchmark | A small real sample can show a result under stated conditions. |
| L3 | Community BYOK benchmark | External submissions can compare results with their own credentials and constraints. |
| L4 | Independent reproduction | A third party reproduces the result on another repository or task set. |
| L5 | Opt-in production telemetry | Consented, anonymized telemetry shows trends over real use. |

### Evidence By Scenario

| Scenario | Surface | Level | Public evidence | Decision use |
| --- | --- | --- | --- | --- |
| Orchestrator proof loop | Codex Model Orchestrator | L1-L2 | Claim levels, QA gates, measurement method, redaction model, human decision flow. | Judge whether the control layer is demo-ready. |
| Apps SDK / MCP surface | Orchestrator product UI | L1 | Readable state, read/write separation, decision cards, confirmation language. | Decide whether the interface shape is suitable for users. |
| Benchmark framing | Orchestrator | L1-L3 depending on source | Accepted-task cost, failures, human score, correction time, redacted summaries. | Discuss value without making unsupported broad productivity claims. |
| Unity asset loop | CodexToUnity / LocalAssetFactory | L1-L2 | Public prototype framing, dry-run/smoke paths, manifest, import checklist, scene review. | Scope a Unity/ComfyUI private demo. |
| ComfyUI product layer | Mob'ia / ccomf-unity | L1 | Product map: profiles, async jobs, artifacts, Unity/web/mobile clients, review states. | Evaluate product partnership around generation workflows. |
| Public governance | All surfaces | L1 | Public scope, security/privacy, redaction policy, evidence ledger, QA matrix. | Confirm the showcase is useful without leaking private material. |

### Claim Discipline

When presenting the project, attach each claim to its level. For example: "the public method is documented" is L1; "this improves production throughput" would need stronger benchmark or telemetry evidence.

## Francais

### Niveaux De Preuve Publics

Les niveaux de preuve gardent le repo honnete. Un niveau bas n'est pas un echec; il indique au lecteur quel type de claim est supportable aujourd'hui.

| Niveau | Sens | Claim autorise |
| --- | --- | --- |
| L0 | Instrumentation | Le projet sait produire traces, compteurs, resumes ou rapports pour revue ulterieure. |
| L1 | Replay synthetique ou methode publique | Le pipeline peut rejouer des exemples synthetiques/rediges et expliquer la methode. |
| L2 | Micro-benchmark mainteneur | Un petit echantillon reel peut montrer un resultat sous conditions explicites. |
| L3 | Benchmark community BYOK | Des soumissions externes peuvent comparer les resultats avec leurs credentials et contraintes. |
| L4 | Reproduction independante | Un tiers reproduit sur un autre repo ou jeu de taches. |
| L5 | Telemetrie production opt-in | Des donnees anonymisees avec consentement montrent des tendances d'usage reel. |

### Preuves Par Scenario

| Scenario | Surface | Niveau | Preuve publique | Usage decision |
| --- | --- | --- | --- | --- |
| Proof loop orchestrateur | Codex Model Orchestrator | L1-L2 | Niveaux de claim, gates QA, methode de mesure, modele redaction, flux decision humaine. | Juger si la couche de controle est prete pour demo. |
| Surface Apps SDK / MCP | UI produit orchestrateur | L1 | Etat lisible, separation read/write, cartes decision, langage confirmation. | Decider si la forme interface convient aux utilisateurs. |
| Cadrage benchmark | Orchestrateur | L1-L3 selon source | Cout par tache acceptee, echecs, score humain, temps correction, resumes rediges. | Discuter la valeur sans claims productivite trop larges. |
| Boucle asset Unity | CodexToUnity / LocalAssetFactory | L1-L2 | Cadrage prototype public, dry-run/smoke paths, manifest, checklist import, revue scene. | Cadrer une demo privee Unity/ComfyUI. |
| Couche produit ComfyUI | Mob'ia / ccomf-unity | L1 | Carte produit: profils, jobs async, artefacts, clients Unity/web/mobile, etats revue. | Evaluer partenariat produit autour workflows generation. |
| Gouvernance publique | Toutes surfaces | L1 | Public scope, securite/donnees, redaction policy, evidence ledger, QA matrix. | Confirmer que la vitrine est utile sans fuite privee. |

### Discipline De Claim

Quand le projet est presente, chaque claim doit etre rattache a son niveau. Par exemple: "la methode publique est documentee" est L1; "cela ameliore le throughput production" demanderait des preuves benchmark ou telemetrie plus fortes.
