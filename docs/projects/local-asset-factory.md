# LocalAssetFactory / Asset Factory

[EN](#english) | [FR](#francais)

## English

### Role

LocalAssetFactory is the local asset production and validation loop. It connects intent, generation, manifest, normalization, Unity import, socket mapping, scene review, and written evidence.

It is the practical layer that prevents asset generation from being treated as complete too early. A generated file is not enough; the output must be identifiable, importable, reviewable, and useful inside the target scene.

### Workflow Model

| Step | What happens | Review question |
| --- | --- | --- |
| Intent | The user describes the desired asset or scene role. | Is the target specific enough to judge? |
| Job | The system creates or simulates a generation job. | Are inputs, constraints, and outputs named? |
| Manifest | The expected artifact metadata is recorded. | Can the artifact be traced and reviewed? |
| Normalization | Scale, orientation, naming, format, and material expectations are checked. | Will Unity import be predictable? |
| Socket/import | The asset is mapped toward Unity use. | Does it fit the intended scene role? |
| Human review | A person accepts, revises, rejects, or archives. | Is the decision explicit and documented? |

### Evaluation Criteria

- The workflow remains controllable.
- Outputs are identifiable and tied to a manifest.
- Unity import is judged separately from generation success.
- Scene usefulness is checked by a human.
- Private data, model settings, workflows, and generated assets stay local unless explicitly cleared.
- Public output is a diagram, checklist, or proof card.

### Useful For

Local asset loops, Unity pipeline QA, ComfyUI/Trellis-style generation review, partner demos, and private proof packs where the reviewer needs confidence without public access to raw assets or workflows.

### Private Boundary

Configurations, workflows, models, datasets, generated GLB/FBX/OBJ assets, services, endpoints, local paths, internal screenshots, logs, and builds are not published.

## Francais

### Role

LocalAssetFactory est la boucle locale de production et validation d'assets. Elle connecte intention, generation, manifest, normalisation, import Unity, socket mapping, revue scene et preuve redigee.

C'est la couche pratique qui evite de declarer un asset termine trop tot. Un fichier genere ne suffit pas; la sortie doit etre identifiable, importable, reviewable et utile dans la scene cible.

### Modele De Workflow

| Etape | Ce qui se passe | Question de revue |
| --- | --- | --- |
| Intention | L'utilisateur decrit l'asset ou le role scene vise. | La cible est-elle assez specifique pour juger? |
| Job | Le systeme cree ou simule un job de generation. | Entrees, contraintes et sorties sont-elles nommees? |
| Manifest | Les metadata attendues de l'artefact sont notees. | L'artefact peut-il etre trace et revu? |
| Normalisation | Echelle, orientation, nommage, format et materiaux attendus sont controles. | L'import Unity sera-t-il previsible? |
| Socket/import | L'asset est mappe vers un usage Unity. | Correspond-il au role scene vise? |
| Revue humaine | Une personne accepte, revise, refuse ou archive. | La decision est-elle explicite et documentee? |

### Criteres D'Evaluation

- Le workflow reste controlable.
- Les sorties sont identifiables et liees a un manifest.
- L'import Unity est juge separement du succes de generation.
- L'utilite scene est controlee par un humain.
- Donnees privees, reglages modele, workflows et assets generes restent locaux sauf validation explicite.
- La sortie publique est un diagramme, checklist ou proof card.

### Utile Pour

Boucles asset locales, QA pipeline Unity, revue de generation type ComfyUI/Trellis, demos partenaires et proof packs prives ou le reviewer veut de la confiance sans acces public aux assets ou workflows bruts.

### Frontiere Privee

Configurations, workflows, modeles, datasets, GLB/FBX/OBJ generes, services, endpoints, chemins locaux, captures internes, logs et builds ne sont pas publies.
