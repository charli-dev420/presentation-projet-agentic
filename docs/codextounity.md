# CodexToUnity

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

CodexToUnity is the bridge between an AI-assisted request and a Unity-oriented workflow.

The project can also be discussed in a Unity or 3D context. In this repository, the focus is the LLM layer: how a request becomes a structured task path, with target, constraints, manifest, checks and review notes.

---

## LLM role

The LLM helps:

- read the user request;
- identify the Unity target;
- define expected output and constraints;
- prepare a manifest or handoff note;
- separate generation success from Unity usefulness;
- summarize checks and next actions.

---

## Useful workflow

```text
request → Unity target → task path → manifest → candidate → import checks → review note
```

The goal is to make generated or assisted work easier to inspect before it enters a real Unity project.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

CodexToUnity est le pont entre une demande assistée par IA et un workflow orienté Unity.

Le projet peut aussi être présenté dans un contexte Unity ou 3D. Dans ce dépôt, le focus est la couche LLM : comment une demande devient un chemin de tâche structuré, avec cible, contraintes, manifest, contrôles et notes de revue.

---

## Rôle du LLM

Le LLM aide à :

- lire la demande utilisateur ;
- identifier la cible Unity ;
- définir la sortie attendue et les contraintes ;
- préparer un manifest ou une note de handoff ;
- séparer succès de génération et utilité Unity ;
- résumer les contrôles et prochaines actions.

---

## Workflow utile

```text
requête → cible Unity → chemin de tâche → manifest → candidat → contrôles import → note de revue
```

Le but est de rendre le travail généré ou assisté plus simple à inspecter avant son entrée dans un vrai projet Unity.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
