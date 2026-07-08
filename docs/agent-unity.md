# Agent Unity

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

Agent Unity is the Unity-facing agent line.

It can also appear in a Unity showcase, but here the focus is only the LLM role: reading scenes, explaining issues, preparing actions and supporting review inside editor workflows.

---

## LLM role

The LLM helps:

- inspect the current scene or selected elements;
- describe visible, structural or naming issues;
- turn observations into a clear work queue;
- prepare editor actions without hiding risk;
- support visual review before changes are accepted.

---

## Useful workflow

```text
scene context → observation → issue → proposed action → review → human decision
```

The agent should help prepare and explain work. It should not be presented as a free actor that can change a project without review.

---

## Review signals

| Area | What should be visible |
| --- | --- |
| Scene reading | What the agent looked at and what it understood. |
| Issue detection | What seems wrong, missing, inconsistent or risky. |
| Action preparation | What should be changed and why. |
| Human control | What must be approved before changes are applied. |

---

## Public boundary

Detailed Unity implementation, private scene data, editor automation details and internal project files belong outside the public showcase.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Agent Unity est la ligne agent orientée Unity.

Il peut aussi apparaître dans une vitrine Unity, mais ici le focus est uniquement le rôle du LLM : lire des scènes, expliquer les problèmes, préparer des actions et soutenir la revue dans des workflows éditeur.

---

## Rôle du LLM

Le LLM aide à :

- inspecter la scène courante ou les éléments sélectionnés ;
- décrire les problèmes visibles, structurels ou de nommage ;
- transformer les observations en file de travail claire ;
- préparer des actions éditeur sans cacher les risques ;
- soutenir la revue visuelle avant acceptation des changements.

---

## Workflow utile

```text
contexte scène → observation → problème → action proposée → revue → décision humaine
```

L’agent doit aider à préparer et expliquer le travail. Il ne doit pas être présenté comme un acteur libre pouvant modifier un projet sans revue.

---

## Signaux de revue

| Zone | Ce qui doit être visible |
| --- | --- |
| Lecture de scène | Ce que l’agent a regardé et compris. |
| Détection de problème | Ce qui semble faux, manquant, incohérent ou risqué. |
| Préparation d’action | Ce qui devrait être modifié et pourquoi. |
| Contrôle humain | Ce qui doit être approuvé avant application des changements. |

---

## Limite publique

L’implémentation Unity détaillée, les données de scène privées, les détails d’automatisation éditeur et les fichiers projet internes restent hors de la vitrine publique.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
