# Codex Model Orchestrator / AI Workflow Tools

<p align="center">
  <img src="assets/project-banners/codex-model-orchestrator.jpg" width="900" alt="Codex Model Orchestrator banner">
</p>

<p align="center">
  <strong>I am building tools for AI-assisted work that needs to be checked, reused, explained, and handed back to a real person.</strong>
</p>

<p align="center">
  <a href="#english">English</a> ·
  <a href="#francais">Francais</a> ·
  <a href="docs/one-pager.md">One-pager</a> ·
  <a href="docs/ecosystem-map.md">Ecosystem map</a> ·
  <a href="docs/evidence-ledger.md">Evidence ledger</a> ·
  <a href="docs/buyer-evaluation.md">Buyer evaluation</a>
</p>

## English

### What I Am Trying To Solve

When I use AI tools on real work, the hard part is rarely the first answer. The hard part comes after: keeping track of what was asked, what the tool touched, why it chose that path, what still needs checking, and what a human should decide before the result is accepted.

**Codex Model Orchestrator** is my answer to that problem. I want a run to leave behind something readable: a short brief, the tools involved, the decisions made, the evidence available, the weak points, and the next action. Not a wall of hidden traces, not a vague "done", and not a demo that only works while someone is explaining it live.

The Unity and asset projects keep the idea honest. **CodexToUnity**, **Mob'ia / ccomf-unity**, and **LocalAssetFactory** force the system to deal with concrete work: generated assets, manifests, import checks, review states, ComfyUI handoff, and files that need to survive outside the chat window.

### A Concrete Example

Imagine a small asset workflow.

A user asks for a generated object to be prepared for Unity. The system should not just say "asset created". It should know which source was used, which generation step ran, what file came out, whether the manifest is complete, whether the import looks plausible, what still needs a human review, and what summary can be sent to a collaborator.

That is the kind of loop I care about. If the run cannot be reread, questioned, and improved, it is not ready for a team.

### How To Read This Repo

Start with the [one-pager](docs/one-pager.md) for the short version. Then use the [ecosystem map](docs/ecosystem-map.md) to see how the pieces fit together.

For real usage, read the [user flows](docs/user-flows.md), [tutorials](docs/tutorials.md), and [orchestrator proof loop](docs/scenarios/orchestrator-proof-loop.md). For evaluation, read [evidence](docs/evidence.md), [evidence ledger](docs/evidence-ledger.md), [proof pack](docs/proof-pack.md), [QA matrix](docs/qa-matrix.md), and [QA validation](docs/qa-validation.md).

If you are thinking about a mission, pilot, partnership, funding discussion, or role, the useful pages are [buyer evaluation](docs/buyer-evaluation.md), [partnership brief](docs/partnership.md), [decision pack](docs/decision-pack.md), and [security/privacy](docs/security-privacy.md).

Project pages are available for [Codex Model Orchestrator](docs/projects/codex-model-orchestrator.md), [CodexToUnity](docs/projects/codextounity.md), [Mob'ia / ccomf-unity](docs/projects/mobia-ccomf-unity.md), and [LocalAssetFactory](docs/projects/local-asset-factory.md).

### Project Tracks

<p>
  <img align="left" src="assets/project-banners/agentic-workflows.jpg" width="260" alt="AI workflow banner">
  <strong>Codex Model Orchestrator is about readable runs.</strong><br>
  I use it to explore task routing, sub-agent work, run summaries, proof cards, and MCP/App SDK surfaces. The point is not to make the tool sound autonomous. The point is to let someone understand the run after it happened.
</p>

<br clear="left">

<p>
  <img align="left" src="assets/project-banners/mobia-mobile.jpg" width="260" alt="Mob'ia mobile banner">
  <strong>Unity and asset workflows give the system something real to carry.</strong><br>
  CodexToUnity, Mob'ia / ccomf-unity, and LocalAssetFactory connect orchestration to generated files, manifests, review screens, import checks, and client-facing summaries.
</p>

<br clear="left">

<p>
  <img align="left" src="assets/project-banners/codex-model-orchestrator.jpg" width="260" alt="Codex Model Orchestrator banner">
  <strong>The output must help a person decide.</strong><br>
  A good run should end with a useful choice: accept it, revise it, ask for proof, send it to a collaborator, or stop there. That decision is part of the product.
</p>

<br clear="left">

### Why Contact

Contact makes sense if you have a workflow where AI assistance is useful but trust, review, handoff, or repeatability is still messy.

Good starting points: an MCP/App SDK interface that needs to be easier to read, a Unity or ComfyUI pipeline to structure, an internal tool that needs proof cards, a demo that must be judged by non-developers, a paid pilot, a technical mission, or a role around AI tooling and developer experience.

Public contact route: [GitHub - Unicorn Who Dev](https://github.com/charli-dev420).

## Francais

### Ce Que Je Cherche A Resoudre

Quand j'utilise des outils IA sur du vrai travail, le plus dur n'est pas souvent la premiere reponse. Le dur arrive apres: garder la trace de ce qui a ete demande, ce que l'outil a touche, pourquoi il a choisi ce chemin, ce qui reste a verifier, et ce qu'une personne doit decider avant d'accepter le resultat.

**Codex Model Orchestrator** est ma reponse a ce probleme. Je veux qu'un run laisse quelque chose de lisible: un brief court, les outils impliques, les decisions prises, les preuves disponibles, les points faibles et l'action suivante. Pas un mur de traces, pas un simple "done", pas une demo qui ne tient que pendant qu'on l'explique a l'oral.

Les projets Unity et assets gardent l'idee concrete. **CodexToUnity**, **Mob'ia / ccomf-unity** et **LocalAssetFactory** obligent le systeme a traiter du travail reel: assets generes, manifests, controles d'import, etats de revue, handoff ComfyUI et fichiers qui doivent survivre hors de la fenetre de chat.

### Exemple Concret

Imaginez un petit workflow asset.

Un utilisateur demande de preparer un objet genere pour Unity. Le systeme ne doit pas seulement dire "asset created". Il doit savoir quelle source a ete utilisee, quelle generation a tourne, quel fichier est sorti, si le manifest est complet, si l'import parait plausible, ce qui demande encore une revue humaine et quel resume peut etre envoye a un collaborateur.

C'est ce type de boucle qui m'interesse. Si le run ne peut pas etre relu, questionne et ameliore, il n'est pas pret pour une equipe.

### Lire Ce Repo

Le [one-pager](docs/one-pager.md) donne la version courte. L'[ecosystem map](docs/ecosystem-map.md) montre comment les pieces se relient.

Pour l'usage, lire les [flux utilisateur](docs/user-flows.md), les [tutoriels](docs/tutorials.md) et le [proof loop orchestrateur](docs/scenarios/orchestrator-proof-loop.md). Pour evaluer, lire [evidence](docs/evidence.md), [evidence ledger](docs/evidence-ledger.md), [proof pack](docs/proof-pack.md), [QA matrix](docs/qa-matrix.md) et [QA validation](docs/qa-validation.md).

Pour une mission, un pilote, un partenariat, un financement ou un poste, les pages utiles sont [buyer evaluation](docs/buyer-evaluation.md), [partnership brief](docs/partnership.md), [decision pack](docs/decision-pack.md) et [security/privacy](docs/security-privacy.md).

Les pages projet couvrent [Codex Model Orchestrator](docs/projects/codex-model-orchestrator.md), [CodexToUnity](docs/projects/codextounity.md), [Mob'ia / ccomf-unity](docs/projects/mobia-ccomf-unity.md) et [LocalAssetFactory](docs/projects/local-asset-factory.md).

### Axes Projet

<p>
  <img align="left" src="assets/project-banners/agentic-workflows.jpg" width="260" alt="Banniere workflow IA">
  <strong>Codex Model Orchestrator sert a rendre les runs lisibles.</strong><br>
  Je l'utilise pour explorer routage de taches, travail de sous-agents, resumes de run, cartes de preuve et surfaces MCP/App SDK. Le but n'est pas de donner l'impression que l'outil est autonome. Le but est que quelqu'un puisse comprendre le run apres coup.
</p>

<br clear="left">

<p>
  <img align="left" src="assets/project-banners/mobia-mobile.jpg" width="260" alt="Banniere Mob'ia mobile">
  <strong>Unity et les workflows assets donnent au systeme quelque chose de reel a porter.</strong><br>
  CodexToUnity, Mob'ia / ccomf-unity et LocalAssetFactory relient l'orchestration a des fichiers generes, manifests, ecrans de revue, controles d'import et resumes lisibles cote client.
</p>

<br clear="left">

<p>
  <img align="left" src="assets/project-banners/codex-model-orchestrator.jpg" width="260" alt="Banniere Codex Model Orchestrator">
  <strong>La sortie doit aider une personne a decider.</strong><br>
  Un bon run doit finir sur un vrai choix: accepter, reviser, demander une preuve, envoyer a un collaborateur ou s'arreter la. Cette decision fait partie du produit.
</p>

<br clear="left">

### Pourquoi Contacter

Le contact a du sens si vous avez un workflow ou l'assistance IA est utile mais ou la confiance, la revue, le handoff ou la repetabilite restent difficiles.

Bons points de depart: une interface MCP/App SDK a rendre plus lisible, un pipeline Unity ou ComfyUI a structurer, un outil interne qui a besoin de cartes de preuve, une demo qui doit etre jugee par des non-developpeurs, un pilote payant, une mission technique ou un poste autour de l'outillage IA et de la developer experience.

Contact public recommande: [GitHub - Unicorn Who Dev](https://github.com/charli-dev420).
