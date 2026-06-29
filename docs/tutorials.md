# Tutorials / Tutoriels

[EN](#english) | [FR](#francais)

## English

### Tutorial 1 - Read MCP As A Tool Contract

MCP is useful because it makes the agent/tool boundary explicit. A good tool contract answers:

- what the tool can read;
- what the tool can change;
- which actions are read-only and which are mutating;
- which inputs must be validated;
- which actions require human confirmation;
- which evidence will be produced after the tool runs.

How to evaluate it: if a tool can change files, call services, trigger generation, or alter a project, the public documentation should show how that action is bounded and confirmed.

### Tutorial 2 - Read An Apps SDK Surface

An Apps SDK surface should make agentic state visible to a human. The reader should not need raw logs to know what happened.

Look for:

- task status;
- selected scenario;
- allowed actions;
- tool or sub-agent results;
- evidence level;
- QA gate result;
- cost or runtime signal when relevant;
- accept/revise/reject decision.

Good interface language turns "the agent did something" into "this task reached this state, with this evidence, and now a person must decide".

### Tutorial 3 - Read Agentic Evidence

A useful proof card includes:

| Field | Why it matters |
| --- | --- |
| Goal | Prevents vague claims. |
| Scope | Shows what was allowed and excluded. |
| Tool/sub-agent path | Explains how work moved through the system. |
| Result | States what changed or what was produced. |
| QA gate | Shows whether the output met the expected checks. |
| Human decision | Makes acceptance, revision, or rejection explicit. |
| Evidence level | Prevents overclaiming. |
| Redaction note | Explains what stayed private and why. |

Raw prompts, traces, local paths, endpoints, and private screenshots are not public evidence. They may support a private audit, but public material should be rewritten and bounded.

### Tutorial 4 - Evaluate A Unity Asset Job

Use this checklist before treating an asset workflow as useful:

1. The target asset and scene role are clear.
2. The expected format and import path are named.
3. The job has a manifest or equivalent structured summary.
4. Scale, pivot, materials, bounds, sockets, and naming are checked.
5. Unity review is recorded separately from generation success.
6. The human decision is explicit.
7. The public proof does not leak GLB/FBX/OBJ files, private workflows, local paths, or generated private assets.

### Tutorial 5 - Prepare A Collaboration

Before a collaboration, define:

- the scenario to prove;
- allowed data and tools;
- proof level target;
- confirmation rules;
- public/private split;
- expected proof artifact;
- decision criteria for continuing.

This prevents a private demo from becoming an uncontrolled support session and gives every stakeholder the same evaluation frame.

## Francais

### Tutoriel 1 - Lire MCP Comme Contrat Outil

MCP est utile parce qu'il rend explicite la frontiere agent/outil. Un bon contrat outil repond:

- ce que l'outil peut lire;
- ce que l'outil peut modifier;
- quelles actions sont read-only et lesquelles sont mutating;
- quelles entrees doivent etre validees;
- quelles actions demandent confirmation humaine;
- quelle preuve est produite apres execution.

Comment evaluer: si un outil peut modifier des fichiers, appeler des services, declencher une generation ou alterer un projet, la documentation publique doit montrer comment cette action est bornee et confirmee.

### Tutoriel 2 - Lire Une Surface Apps SDK

Une surface Apps SDK doit rendre l'etat agentique visible pour un humain. Le lecteur ne devrait pas avoir besoin de logs bruts pour comprendre.

Chercher:

- statut de tache;
- scenario choisi;
- actions autorisees;
- resultats outil ou sous-agent;
- niveau de preuve;
- resultat gate QA;
- signal de cout ou runtime si pertinent;
- decision accepter/reviser/refuser.

Un bon langage d'interface transforme "l'agent a fait quelque chose" en "cette tache est dans cet etat, avec cette preuve, et une personne doit decider".

### Tutoriel 3 - Lire Une Preuve Agentique

Une proof card utile inclut:

| Champ | Pourquoi c'est important |
| --- | --- |
| Objectif | Evite les claims vagues. |
| Perimetre | Montre ce qui etait autorise et exclu. |
| Chemin outil/sous-agent | Explique comment le travail a circule. |
| Resultat | Dit ce qui a change ou ete produit. |
| Gate QA | Montre si la sortie a passe les controles attendus. |
| Decision humaine | Rend acceptation, revision ou rejet explicite. |
| Niveau de preuve | Evite le surclaim. |
| Note de redaction | Explique ce qui reste prive et pourquoi. |

Prompts bruts, traces, chemins locaux, endpoints et captures privees ne sont pas des preuves publiques. Ils peuvent soutenir un audit prive, mais le public doit recevoir une version redigee et bornee.

### Tutoriel 4 - Evaluer Un Job Asset Unity

Utiliser cette checklist avant de juger un workflow asset utile:

1. L'asset cible et son role scene sont clairs.
2. Le format attendu et le chemin d'import sont nommes.
3. Le job a un manifest ou resume structure equivalent.
4. Echelle, pivot, materiaux, bounds, sockets et nommage sont verifies.
5. La revue Unity est distincte du succes de generation.
6. La decision humaine est explicite.
7. La preuve publique ne fuit pas de GLB/FBX/OBJ, workflows prives, chemins locaux ou assets prives generes.

### Tutoriel 5 - Preparer Une Collaboration

Avant une collaboration, definir:

- le scenario a prouver;
- donnees et outils autorises;
- niveau de preuve cible;
- regles de confirmation;
- partage public/prive;
- artefact de preuve attendu;
- criteres de decision pour continuer.

Cela evite qu'une demo privee devienne une session support non cadree et donne a chaque partie le meme cadre d'evaluation.
