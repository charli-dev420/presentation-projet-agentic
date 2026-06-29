# Codex Model Orchestrator One-Pager

[EN](#english) | [FR](#francais)

![Agentic one-pager](../assets/one-pager.svg)

## English

### The Short Version

I am working on a simple but important question: when an AI tool does work for you, how do you know what really happened?

**Codex Model Orchestrator** is the project where I try to answer that with a product surface, not just with logs. A run should start from a clear request, use allowed tools, produce something inspectable, show what was checked, and end with a decision a person can actually make.

Around it, **CodexToUnity**, **Mob'ia / ccomf-unity**, and **LocalAssetFactory** give the idea concrete pressure. Generated assets have files, manifests, previews, imports, mistakes, weights, formats, and review points. They are a good test for whether the orchestration is useful or just nicely written.

### What A Useful Run Looks Like

A useful run might look like this:

1. A user asks for a Unity asset batch to be prepared.
2. The system writes the scope before touching anything.
3. It calls the right tool, creates or checks the artifact, and records what happened.
4. It reports what passed, what is doubtful, and what still needs a human eye.
5. It leaves a small result card that a partner, buyer, or teammate can read without opening the whole raw session.

That last step matters. If the only person who understands the work is the person who ran the tool, the workflow is not good enough.

### Why It Matters

AI tools are becoming easy to launch and hard to supervise. The risk is not only that they fail. The risk is that they fail in a way nobody can explain later.

I want these projects to make the work legible: what the run tried to do, what it changed, what evidence exists, what needs review, and what the next useful move is.

### What To Read

Start with the [ecosystem map](ecosystem-map.md), then read the [user flows](user-flows.md) and [orchestrator proof loop](scenarios/orchestrator-proof-loop.md). For a more serious look, use the [evidence ledger](evidence-ledger.md), [proof pack](proof-pack.md), [QA matrix](qa-matrix.md), and [buyer evaluation](buyer-evaluation.md).

### Good First Conversations

The best conversations start with one workflow: a tool chain to make readable, an asset pipeline to review, a ComfyUI/Unity handoff to structure, an internal AI demo to make credible, or a role where AI tooling needs to be useful for more than the person who built it.

## Francais

### Version Courte

Je travaille sur une question simple mais importante: quand un outil IA fait du travail pour vous, comment sait-on ce qui s'est vraiment passe ?

**Codex Model Orchestrator** est le projet ou j'essaie de repondre avec une vraie surface produit, pas seulement avec des logs. Un run doit partir d'une demande claire, utiliser des outils autorises, produire quelque chose d'inspectable, montrer ce qui a ete verifie et finir sur une decision qu'une personne peut vraiment prendre.

Autour, **CodexToUnity**, **Mob'ia / ccomf-unity** et **LocalAssetFactory** mettent l'idee sous contrainte concrete. Les assets generes ont des fichiers, manifests, previews, imports, erreurs, poids, formats et points de revue. C'est un bon test pour savoir si l'orchestration est utile ou seulement bien formulee.

### A Quoi Ressemble Un Run Utile

Un run utile peut ressembler a cela:

1. Un utilisateur demande de preparer un lot d'assets Unity.
2. Le systeme ecrit le cadrage avant de toucher quoi que ce soit.
3. Il appelle le bon outil, cree ou controle l'artefact, puis garde une trace de ce qui s'est passe.
4. Il indique ce qui passe, ce qui est douteux et ce qui demande encore un regard humain.
5. Il laisse une petite carte de resultat qu'un partenaire, acheteur ou coequipier peut lire sans ouvrir toute la session brute.

Ce dernier point compte. Si la seule personne qui comprend le travail est celle qui a lance l'outil, le workflow n'est pas assez bon.

### Pourquoi C'est Important

Les outils IA deviennent faciles a lancer et difficiles a superviser. Le risque n'est pas seulement qu'ils echouent. Le risque est qu'ils echouent d'une maniere que personne ne peut expliquer ensuite.

Je veux que ces projets rendent le travail lisible: ce que le run a essaye de faire, ce qu'il a change, quelles preuves existent, ce qui demande revue et quel est le prochain geste utile.

### Quoi Lire

Commencer par l'[ecosystem map](ecosystem-map.md), puis lire les [flux utilisateur](user-flows.md) et le [proof loop orchestrateur](scenarios/orchestrator-proof-loop.md). Pour une lecture plus serieuse, utiliser l'[evidence ledger](evidence-ledger.md), le [proof pack](proof-pack.md), la [QA matrix](qa-matrix.md) et l'[evaluation acheteur](buyer-evaluation.md).

### Bonnes Premieres Discussions

Les meilleures discussions partent d'un workflow: une chaine d'outils a rendre lisible, un pipeline asset a revoir, un handoff ComfyUI/Unity a structurer, une demo IA interne a rendre credible ou un poste ou l'outillage IA doit servir a plus que la personne qui l'a construit.
