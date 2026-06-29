# Scenario: Orchestrator Proof Loop

[EN](#english) | [FR](#francais)

## English

### Scenario

A user wants a bounded task completed by an agentic system, but also needs evidence that the result is safe to trust, revise, or reject.

### Flow

1. The user submits a task with goal, constraints, allowed data, and expected output.
2. The orchestrator creates a plan and selects tools or sub-agents.
3. Read-only status is shown before any mutating action.
4. Sensitive actions require explicit human confirmation.
5. Outputs are checked against build/test, verifiability, human score, correction time, and failure/revision reason.
6. The result is summarized with an evidence level.
7. A human decides: accept, revise, reject, archive, or escalate.

### Public Output

A proof card with:

- task class;
- allowed scope;
- summarized tool/sub-agent path;
- evidence level;
- result status;
- human decision;
- redacted measurement;
- redaction note.

No prompt, raw trace, token, endpoint, local path, provider output, private tool definition, or internal log is included.

### Buyer Signal

This is the strongest first demo because it proves the control system itself: orchestration, evidence, QA, redaction, and human decision.

## Francais

### Scenario

Un utilisateur veut qu'un systeme agentique realise une tache bornee, mais il a aussi besoin d'une preuve pour savoir si le resultat est fiable, revisable ou a refuser.

### Flux

1. L'utilisateur soumet une tache avec objectif, contraintes, donnees autorisees et sortie attendue.
2. L'orchestrateur cree un plan et choisit outils ou sous-agents.
3. Le statut read-only est affiche avant toute action mutating.
4. Les actions sensibles demandent confirmation humaine explicite.
5. Les sorties sont controlees contre build/test, verifiability, score humain, temps de correction et raison d'echec/revision.
6. Le resultat est resume avec un niveau de preuve.
7. Un humain decide: accepter, reviser, refuser, archiver ou escalader.

### Sortie Publique

Une proof card avec:

- classe de tache;
- perimetre autorise;
- chemin outil/sous-agent resume;
- niveau de preuve;
- statut resultat;
- decision humaine;
- mesure redigee;
- note de redaction.

Aucun prompt, trace brute, token, endpoint, chemin local, sortie provider, definition d'outil prive ou log interne n'est inclus.

### Signal Acheteur

C'est la meilleure premiere demo parce qu'elle prouve le systeme de controle lui-meme: orchestration, preuve, QA, redaction et decision humaine.
