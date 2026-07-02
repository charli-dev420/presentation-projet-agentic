# User Flows / Flux utilisateur

[EN](#english) | [FR](#francais)

## English

### Flow 1 - Run A Readable AI Task

The user gives a goal. Codex Model Orchestrator writes the scope, names constraints, uses the right tool path, records what changed, checks the output, and leaves a small result a person can act on.

Useful observations: is the goal clear, are tool actions understandable, is the result inspectable, and does the final note make the next decision obvious?

### Flow 2 - Prepare A Unity Asset Handoff

The user describes a Unity target: asset role, format, scale expectations, import constraints, and review criteria. CodexToUnity frames the job and manifest. LocalAssetFactory checks candidate output against import, bounds, pivot, naming, materials, sockets, and scene usefulness.

Useful output: one candidate status, one import/readiness note, one review decision.

### Flow 3 - Track A ComfyUI Product Job

Mob'ia / ccomf-unity attaches a request to a profile, creates a job, tracks artifact state, exposes status to a client, and records the decision. The point is to make generation behave like a product workflow, not a folder of disconnected outputs.

Useful output: profile, job state, artifact state, client surface, and next action.

### Flow 4 - Review A Local Asset Candidate

LocalAssetFactory treats generated output as a candidate until it has a manifest, normalized expectations, import checks, scene review, and a written decision. Generation success and Unity usefulness are checked separately.

Useful output: accept, revise, reject, archive, or continue review.

### Flow 5 - Evaluate For Collaboration Or Work

The reader chooses one angle: MCP/App SDK, run summaries, Unity handoff, ComfyUI product jobs, local automation, QA, documentation, funding, mission, or role. They read [overview](overview.md), [project evaluation](project-evaluation.md), and the relevant project page, then choose one concrete next task.

### Feedback Format

- Surface: Orchestrator, MCP/App SDK, CodexToUnity, Mob'ia / ccomf-unity, LocalAssetFactory, documentation.
- Scenario: what the user tried.
- Expected result: what should have happened.
- Observed result: what happened.
- Evidence: what was checked.
- Decision: accept, revise, reject, archive, escalate, or keep reviewing.

## Francais

### Flux 1 - Lancer Une Tache IA Lisible

L'utilisateur donne un objectif. Codex Model Orchestrator ecrit le perimetre, nomme les contraintes, utilise le bon chemin outil, note ce qui a change, controle la sortie et laisse un petit resultat actionnable par une personne.

Observations utiles: l'objectif est-il clair, les actions outil sont-elles comprehensibles, le resultat est-il inspectable, et la note finale rend-elle la prochaine decision evidente ?

### Flux 2 - Preparer Un Handoff Asset Unity

L'utilisateur decrit une cible Unity: role asset, format, attentes d'echelle, contraintes d'import et criteres de revue. CodexToUnity cadre le job et le manifest. LocalAssetFactory controle le candidat contre import, bounds, pivot, nommage, materiaux, sockets et utilite scene.

Sortie utile: un statut candidat, une note import/readiness, une decision de revue.

### Flux 3 - Suivre Un Job Produit ComfyUI

Mob'ia / ccomf-unity attache une demande a un profil, cree un job, suit l'etat artefact, expose le statut a un client et enregistre la decision. Le but est de faire fonctionner la generation comme workflow produit, pas comme dossier de sorties deconnectees.

Sortie utile: profil, etat job, etat artefact, surface client et prochaine action.

### Flux 4 - Reviewer Un Candidat Asset Local

LocalAssetFactory traite une sortie generee comme candidate tant qu'elle n'a pas manifest, attentes de normalisation, controles import, revue scene et decision ecrite. Le succes generation et l'utilite Unity sont controles separement.

Sortie utile: accepter, reviser, refuser, archiver ou continuer la revue.

### Flux 5 - Evaluer Pour Collaboration Ou Travail

Le lecteur choisit un angle: MCP/App SDK, resumes de run, handoff Unity, jobs produit ComfyUI, automatisation locale, QA, documentation, financement, mission ou poste. Il lit [overview](overview.md), [project evaluation](project-evaluation.md) et la page projet pertinente, puis choisit une prochaine tache concrete.

### Format De Retour

- Surface: Orchestrator, MCP/App SDK, CodexToUnity, Mob'ia / ccomf-unity, LocalAssetFactory, documentation.
- Scenario: ce que l'utilisateur a essaye.
- Resultat attendu: ce qui devait arriver.
- Resultat observe: ce qui s'est produit.
- Preuve: ce qui a ete controle.
- Decision: accepter, reviser, refuser, archiver, escalader ou continuer la revue.
