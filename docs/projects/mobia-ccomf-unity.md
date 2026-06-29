# Mob'ia / ccomf-unity

[EN](#english) | [FR](#francais)

## English

### Role

Mob'ia / ccomf-unity is the product layer around ComfyUI work: backend, profiles, async jobs, artifacts, user tracking, and Unity/web/mobile clients. It is the part of the ecosystem that makes generation feel like a product workflow rather than a private technical workflow.

### Product Value

| Product need | How this surface helps |
| --- | --- |
| Non-technical review | Users see job status, artifact state, and next decision instead of raw workflow internals. |
| Multi-client access | Unity, web, and mobile surfaces can share the same job language. |
| Repeatable generation | Profiles and job metadata make requests easier to compare and revise. |
| Partner evaluation | Buyers can discuss users, artifacts, permissions, and review states without seeing backend internals. |
| Evidence | A job can become a public-safe proof summary after redaction. |

### Public Journey

1. A product-level request is attached to a profile.
2. A job is created and tracked.
3. The artifact reaches a review state.
4. Unity, web, or mobile clients expose the result status.
5. A user accepts, revises, archives, or escalates.
6. A redacted proof card records the decision.

### Good Partner Questions

- Which user profile should be proven first?
- What artifact type matters most?
- Which client surface should lead the review?
- What makes a generated output acceptable?
- Which data must remain private during evaluation?

### Private Boundary

Exact routes, tokens, infrastructure configuration, pods, Docker/run configs, backend source, storage details, secrets, models, workflows, generated outputs, and unredacted screenshots are not published.

## Francais

### Role

Mob'ia / ccomf-unity est la couche produit autour du travail ComfyUI: backend, profils, jobs async, artefacts, suivi utilisateur et clients Unity/web/mobile. C'est la partie de l'ecosysteme qui transforme une generation technique privee en workflow produit.

### Valeur Produit

| Besoin produit | Apport de cette surface |
| --- | --- |
| Revue non technique | Les utilisateurs voient statut job, etat artefact et prochaine decision au lieu d'internals workflow. |
| Acces multi-client | Unity, web et mobile partagent le meme langage de job. |
| Generation repetable | Profils et metadata job rendent les demandes comparables et revisables. |
| Evaluation partenaire | Les acheteurs discutent utilisateurs, artefacts, permissions et etats de revue sans voir le backend. |
| Preuve | Un job peut devenir resume public-safe apres redaction. |

### Parcours Public

1. Une demande produit est attachee a un profil.
2. Un job est cree et suivi.
3. L'artefact atteint un etat de revue.
4. Les clients Unity, web ou mobile exposent le statut.
5. Un utilisateur accepte, revise, archive ou escalade.
6. Une proof card redigee note la decision.

### Bonnes Questions Partenaire

- Quel profil utilisateur prouver en premier?
- Quel type d'artefact compte le plus?
- Quelle surface client doit mener la revue?
- Qu'est-ce qui rend une sortie generee acceptable?
- Quelles donnees doivent rester privees pendant l'evaluation?

### Frontiere Privee

Routes exactes, tokens, configuration infra, pods, Docker/run configs, source backend, details stockage, secrets, modeles, workflows, sorties generees et captures non redigees ne sont pas publies.
