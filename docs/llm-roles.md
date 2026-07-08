# LLM Roles

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

This page defines the LLM roles used across the agentic project family.

The goal is to keep the repository clear: a project belongs here when the language model is part of the workflow, not just decoration around it.

---

## Role map

| Role | Meaning | Example surfaces |
| --- | --- | --- |
| **Read** | Interpret a scene, request, image, preset, job, manifest or product state. | Agent Unity, uwdevst_hub, Codex Image Génial. |
| **Plan** | Turn a request into a scoped task with constraints and expected output. | Codex Model Orchestrator, CodexToUnity. |
| **Route** | Choose the right tool, agent, script, surface or workflow path. | Orchestrator, MCP / Apps SDK surfaces. |
| **Generate** | Produce prompts, code, candidates, edits, presets, notes or job instructions. | uwdevst_hub, Codex Image Génial, Splat to Assets. |
| **Inspect** | Look for issues, missing information, inconsistencies or review points. | Agent Unity, LocalAssetFactory. |
| **Edit** | Help modify an artifact through structured instructions or code-assisted operations. | Codex Image Génial, Unity agent workflows. |
| **Evaluate** | Compare output against criteria, expected behavior or human review needs. | uwdevst_hub, asset review workflows. |
| **Summarize** | Leave a readable result, not just a raw output. | Mob’ia Android, Mob’ia / ccomf-unity. |
| **Help decide** | Prepare accept, revise, reject, archive, import, regenerate or continue decisions. | All project lines. |

---

## Good use vs bad use

| Good use | Weak use |
| --- | --- |
| The LLM explains what it used and what changed. | The LLM only says the result is done. |
| The workflow separates generation from review. | Output is treated as finished immediately. |
| Tool actions are visible and bounded. | Tool actions are vague or hidden. |
| The next human decision is clear. | The user is left with a raw result and no review path. |

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

| Rôle | Sens | Surfaces exemples |
| --- | --- | --- |
| **Lire** | Interpréter une scène, une demande, une image, un preset, un job, un manifest ou un état produit. | Agent Unity, uwdevst_hub, Codex Image Génial. |
| **Planifier** | Transformer une demande en tâche cadrée avec contraintes et sortie attendue. | Codex Model Orchestrator, CodexToUnity. |
| **Router** | Choisir le bon outil, agent, script, surface ou chemin de workflow. | Orchestrator, surfaces MCP / Apps SDK. |
| **Générer** | Produire prompts, code, candidats, edits, presets, notes ou instructions de job. | uwdevst_hub, Codex Image Génial, Splat to Assets. |
| **Inspecter** | Chercher problèmes, informations manquantes, incohérences ou points de revue. | Agent Unity, LocalAssetFactory. |
| **Éditer** | Aider à modifier un artefact via des instructions structurées ou opérations assistées par code. | Codex Image Génial, workflows agent Unity. |
| **Évaluer** | Comparer une sortie à des critères, un comportement attendu ou un besoin de revue humaine. | uwdevst_hub, workflows revue asset. |
| **Résumer** | Laisser un résultat lisible, pas seulement une sortie brute. | Mob’ia Android, Mob’ia / ccomf-unity. |
| **Aider à décider** | Préparer une décision : accepter, corriger, refuser, archiver, importer, régénérer ou continuer. | Toutes les lignes projet. |

---

## Bon usage / usage faible

| Bon usage | Usage faible |
| --- | --- |
| Le LLM explique ce qu’il a utilisé et ce qui a changé. | Le LLM dit seulement que le résultat est terminé. |
| Le workflow sépare génération et revue. | La sortie est traitée comme terminée immédiatement. |
| Les actions outil sont visibles et bornées. | Les actions outil sont vagues ou cachées. |
| La prochaine décision humaine est claire. | L’utilisateur reçoit une sortie brute sans chemin de revue. |

---

## Limite

Le LLM ne doit pas être présenté comme une autonomie magique.

Dans ces projets, le modèle utile est :

```text
support LLM + outils contrôlés + sortie lisible + revue humaine
```

L’humain reste responsable de la décision finale.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
