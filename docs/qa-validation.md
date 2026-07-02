# QA Validation / Validation QA

[EN](#english) | [FR](#francais)

![AI workflow QA matrix](../assets/qa-matrix.svg)

## English

### QA Model

QA is written here as product validation. It checks whether a workflow is scoped, visible, testable, and ended with a decision a person can understand.

### Core Checks

- Scope: goal, constraints, allowed actions, and expected output are written.
- Tool path: read-only and write actions are distinguishable.
- Artifact: the output exists as a file, state, manifest, card, diagram, or written result.
- Surface-specific review: Unity import, ComfyUI job state, MCP/App SDK view, or local asset checks are applied where relevant.
- Decision: the result has a clear accept/revise/reject/archive/continue state.

### Unity And Asset Checks

Unity and asset workflows must separate generation from usefulness. A generated candidate should be checked for manifest, scale, pivot, bounds, naming, materials, sockets, import behavior, and scene role.

### Public QA Output

The useful output is short: scenario, artifact, checks, result, uncertainty, decision, and next action.

## Francais

### Modele QA

La QA est ecrite ici comme validation produit. Elle verifie qu'un workflow est cadre, visible, testable et termine par une decision comprehensible par une personne.

### Controles Coeur

- Perimetre: objectif, contraintes, actions autorisees et sortie attendue sont ecrits.
- Chemin outil: actions read-only et write sont distinguables.
- Artefact: la sortie existe comme fichier, etat, manifest, carte, diagramme ou resultat ecrit.
- Revue adaptee a la surface: import Unity, etat job ComfyUI, vue MCP/App SDK ou controles asset locaux sont appliques selon le cas.
- Decision: le resultat a un etat clair accepter/reviser/refuser/archiver/continuer.

### Controles Unity Et Asset

Les workflows Unity et assets doivent separer generation et utilite. Un candidat genere doit etre controle pour manifest, echelle, pivot, bounds, nommage, materiaux, sockets, comportement import et role scene.

### Sortie QA Publique

La sortie utile est courte: scenario, artefact, controles, resultat, incertitude, decision et prochaine action.
