# Scenario: ComfyUI Product Layer

[EN](#english) | [FR](#francais)

## English

### Scenario

A team wants ComfyUI generation to behave like a product workflow: profiles, jobs, review states, client surfaces, and evidence, rather than a private node graph operated by one technical user.

### Flow

1. Mob'ia / ccomf-unity receives a product-level request.
2. A user profile selects or constrains the intended generation path.
3. A job is created with status, expected artifact type, and review criteria.
4. The job is monitored and converted into a reviewable artifact.
5. Unity, Android, or web clients display the result status.
6. A user accepts, revises, archives, or escalates the artifact.
7. A public-safe proof card records the profile, job state, artifact type, and decision.

### Public Output

A product journey card with profile, job status, artifact type, client surface, review decision, and evidence level. It does not publish backend routes, tokens, storage details, Docker/run configs, private workflows, generated private images, provider outputs, logs, or account metadata.

### Buyer Signal

This scenario is useful when the conversation is productization: how to make generation trackable, reviewable, multi-client, and safe enough for a non-technical user to operate.

## Francais

### Scenario

Une equipe veut que la generation ComfyUI fonctionne comme un workflow produit: profils, jobs, etats de revue, surfaces client et preuve, au lieu d'un graph node prive opere par un seul utilisateur technique.

### Flux

1. Mob'ia / ccomf-unity recoit une demande niveau produit.
2. Un profil utilisateur selectionne ou contraint le chemin de generation vise.
3. Un job est cree avec statut, type d'artefact attendu et criteres de revue.
4. Le job est suivi et transforme en artefact reviewable.
5. Les clients Unity, Android ou web affichent le statut.
6. Un utilisateur accepte, revise, archive ou escalade l'artefact.
7. Une proof card public-safe note profil, etat job, type artefact et decision.

### Sortie Publique

Une carte de parcours produit avec profil, statut job, type artefact, surface client, decision de revue et niveau de preuve. Elle ne publie pas routes backend, tokens, details stockage, Docker/run configs, workflows prives, images privees generees, sorties provider, logs ou metadata compte.

### Signal Acheteur

Ce scenario est utile quand la discussion porte sur la productisation: comment rendre la generation suivable, reviewable, multi-client et assez sure pour un utilisateur non technique.
