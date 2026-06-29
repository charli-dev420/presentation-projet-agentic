# Scenario: Unity Asset Loop

[EN](#english) | [FR](#francais)

## English

### Scenario

A creator wants an AI-assisted asset or scene element that is usable inside Unity, not just a generated file.

### Flow

1. The user describes the Unity target, scene role, asset constraints, format, and acceptance criteria.
2. CodexToUnity frames a job and expected manifest.
3. LocalAssetFactory runs generation or dry-run, normalization, and socket/import preparation.
4. Unity or the review client receives a manifest and import checklist.
5. The result is checked for scale, pivot, bounds, naming, materials, sockets, and scene usability.
6. A human accepts, revises, rejects, archives, or requests another job.

### Public Output

A written summary, diagram, and proof card. The public artifact can describe the workflow and review criteria without publishing GLB/FBX/OBJ files, private ComfyUI workflows, endpoints, local paths, model configs, generated private assets, Unity scenes, raw logs, or builds.

### Buyer Signal

This scenario is useful for Unity/creative partners because it separates generation success from production usefulness. The asset is only valuable after import and human review.

## Francais

### Scenario

Un createur veut un asset ou element de scene assiste IA utilisable dans Unity, pas seulement un fichier genere.

### Flux

1. L'utilisateur decrit la cible Unity, le role scene, les contraintes asset, le format et les criteres d'acceptation.
2. CodexToUnity cadre un job et le manifest attendu.
3. LocalAssetFactory execute generation ou dry-run, normalisation et preparation socket/import.
4. Unity ou le client de revue recoit un manifest et une checklist import.
5. Le resultat est controle: echelle, pivot, bounds, nommage, materiaux, sockets et utilisabilite scene.
6. Un humain accepte, revise, refuse, archive ou demande un autre job.

### Sortie Publique

Un resume redige, un diagramme et une proof card. L'artefact public peut decrire workflow et criteres de revue sans publier GLB/FBX/OBJ, workflows ComfyUI prives, endpoints, chemins locaux, configs modele, assets prives generes, scenes Unity, logs bruts ou builds.

### Signal Acheteur

Ce scenario est utile pour partenaires Unity/creatifs parce qu'il separe succes de generation et utilite production. L'asset n'a de valeur qu'apres import et revue humaine.
