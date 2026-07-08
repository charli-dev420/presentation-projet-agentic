# Agent Unity

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

Agent Unity is the Unity-facing agent line.

It can also appear in a Unity showcase, but here the focus is only on the LLM role: reading scenes, explaining issues, preparing actions and supporting review inside editor workflows.

---

## LLM role

The LLM helps:

- inspect the current scene or selected elements;
- explain visible or structural issues;
- prepare editor tasks;
- turn observations into a clear work queue;
- support visual review before changes are accepted.

---

## Useful workflow

```text
scene context → observation → issue → proposed action → review → human decision
```

The goal is not to let the agent freely change a project. The goal is to make Unity work easier to understand, prepare and verify.

---

## Public boundary

This public page describes the agentic role. Detailed Unity implementation, private scene data and internal automation details belong outside the public showcase.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Agent Unity est la ligne agent orientée Unity.

Il peut aussi apparaître dans une vitrine Unity, mais ici le focus est uniquement sur le rôle du LLM : lire des scènes, expliquer les problèmes, préparer des actions et soutenir la revue dans des workflows éditeur.

---

## Rôle du LLM

Le LLM aide à :

- inspecter la scène courante ou les éléments sélectionnés ;
- expliquer les problèmes visibles ou structurels ;
- préparer des tâches éditeur ;
- transformer les observations en file de travail claire ;
- soutenir la revue visuelle avant acceptation des changements.

---

## Workflow utile

```text
contexte scène → observation → problème → action proposée → revue → décision humaine
```

Le but n’est pas de laisser l’agent modifier librement un projet. Le but est de rendre le travail Unity plus simple à comprendre, préparer et vérifier.

---

## Limite publique

Cette page publique décrit le rôle agentic. L’implémentation Unity détaillée, les données de scène privées et les détails d’automatisation internes restent hors de la vitrine publique.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
