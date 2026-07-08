# LLM Roles

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

This page defines the LLM roles used across the agentic project family.

The goal is to keep the repository clear: a project belongs here when the language model is part of the workflow, not just a decoration around it.

---

## Role map

| Role | Meaning |
| --- | --- |
| **Read** | Interpret a scene, request, image, preset, job, manifest or product state. |
| **Plan** | Turn a request into a scoped task with constraints and expected output. |
| **Route** | Choose the right tool, agent, script, surface or workflow path. |
| **Generate** | Produce text, prompts, code, candidates, edits, presets, notes or job instructions. |
| **Inspect** | Look for issues, missing information, inconsistencies or review points. |
| **Edit** | Help modify an artifact through structured instructions or code-assisted operations. |
| **Evaluate** | Compare output against criteria, expected behavior or human review needs. |
| **Summarize** | Leave a readable result, not just a raw output. |
| **Help decide** | Prepare accept, revise, reject, archive, import, regenerate or continue decisions. |

---

## Boundary

The LLM should not be presented as magic autonomy.

In these projects, the useful pattern is:

```text
LLM support + controlled tools + readable output + human review
```

The human stays responsible for the final decision.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Cette page définit les rôles du LLM utilisés dans la famille de projets agentic.

Le but est de garder le dépôt clair : un projet a sa place ici quand le modèle de langage fait partie du workflow, pas seulement de la décoration autour.

---

## Carte des rôles

| Rôle | Sens |
| --- | --- |
| **Lire** | Interpréter une scène, une demande, une image, un preset, un job, un manifest ou un état produit. |
| **Planifier** | Transformer une demande en tâche cadrée avec contraintes et sortie attendue. |
| **Router** | Choisir le bon outil, agent, script, surface ou chemin de workflow. |
| **Générer** | Produire texte, prompts, code, candidats, edits, presets, notes ou instructions de job. |
| **Inspecter** | Chercher problèmes, informations manquantes, incohérences ou points de revue. |
| **Éditer** | Aider à modifier un artefact via des instructions structurées ou opérations assistées par code. |
| **Évaluer** | Comparer une sortie à des critères, un comportement attendu ou un besoin de revue humaine. |
| **Résumer** | Laisser un résultat lisible, pas seulement une sortie brute. |
| **Aider à décider** | Préparer une décision : accepter, corriger, refuser, archiver, importer, régénérer ou continuer. |

---

## Limite

Le LLM ne doit pas être présenté comme une autonomie magique.

Dans ces projets, le modèle utile est :

```text
support LLM + outils contrôlés + sortie lisible + revue humaine
```

L’humain reste responsable de la décision finale.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
