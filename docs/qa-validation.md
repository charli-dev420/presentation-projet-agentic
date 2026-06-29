# QA Validation / Validation QA

[EN](#english) | [FR](#francais)

![Agentic QA matrix](../assets/qa-matrix.svg)

## English

### What QA Means Here

Agentic QA is a decision system. It checks whether a workflow is scoped, visible, bounded, verifiable, and reviewed by a human.

| QA layer | Validation question | Good evidence |
| --- | --- | --- |
| Scope | Was the goal, allowed data, and expected output written first? | Task card or scenario statement. |
| Tool boundary | Were read-only and mutating actions separated? | MCP/App SDK description and confirmation point. |
| Execution | Can the tool/sub-agent path be summarized? | Redacted run summary or proof card. |
| Verification | Was the output checked with surface-appropriate criteria? | Test result, dry-run, import checklist, human score, or review note. |
| Evidence | Is the claim tied to L0-L5? | Evidence ledger row and proof card. |
| Decision | Did a human accept, revise, reject, archive, or escalate? | Decision field in the proof card. |

### Unity / Asset-Specific Validation

Unity and asset workflows must separate generation from usefulness. A generated file is only a candidate until it passes review for scale, pivot, bounds, materials, naming, socket intent, import behavior, and scene role.

### Public QA Output

The public output should be a short QA summary, not a raw log: task class, scope, checks performed, result, evidence level, human decision, and redaction note.

## Francais

### Ce Que Signifie QA Ici

La QA agentique est un systeme de decision. Elle verifie qu'un workflow est cadre, visible, borne, verifiable et revu par un humain.

| Couche QA | Question de validation | Bonne preuve |
| --- | --- | --- |
| Perimetre | Objectif, donnees autorisees et sortie attendue etaient-ils ecrits d'abord? | Carte tache ou statement scenario. |
| Frontiere outil | Les actions read-only et mutating etaient-elles separees? | Description MCP/App SDK et point de confirmation. |
| Execution | Le chemin outil/sous-agent peut-il etre resume? | Run summary redige ou proof card. |
| Verification | La sortie a-t-elle ete controlee avec des criteres adaptes a la surface? | Test, dry-run, checklist import, score humain ou note revue. |
| Evidence | Le claim est-il lie a L0-L5? | Ligne evidence ledger et proof card. |
| Decision | Un humain a-t-il accepte, revise, refuse, archive ou escalade? | Champ decision dans la proof card. |

### Validation Specifique Unity / Asset

Les workflows Unity et assets doivent separer generation et utilite. Un fichier genere est seulement un candidat tant qu'il n'est pas revu pour echelle, pivot, bounds, materiaux, nommage, intention socket, comportement import et role scene.

### Sortie QA Publique

La sortie publique doit etre un resume QA court, pas un log brut: classe de tache, perimetre, controles effectues, resultat, niveau de preuve, decision humaine et note de redaction.
