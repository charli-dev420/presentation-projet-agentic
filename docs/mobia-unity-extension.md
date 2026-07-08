# Mob’ia Unity Extension

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

Mob’ia Unity Extension is the Unity-side surface connected to Mob’ia workflows.

In this repository, it is presented from the LLM angle: how jobs, artifacts and review states can connect to scene context and Unity-side decisions.

---

## LLM role

The LLM can help:

- connect a Mob’ia job to Unity context;
- explain artifact state in scene terms;
- prepare import or review notes;
- surface missing information;
- summarize the next useful editor action.

---

## Useful workflow

```text
Mob’ia job → artifact → Unity context → review note → editor decision
```

The goal is to avoid treating generated output as finished before it has been understood in the target scene or project.

---

## Review signals

| Signal | Meaning |
| --- | --- |
| Job context is linked | The Unity side knows what the artifact is for. |
| Scene meaning is visible | The output is reviewed against its intended role. |
| Missing data is named | The workflow can stop cleanly instead of guessing. |
| Editor action is reviewable | The next step can be approved or revised by a person. |

---

## Public boundary

This page does not expose private Unity extension source code, project files, internal connectors or private Mob’ia job data.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Mob’ia Unity Extension est la surface côté Unity connectée aux workflows Mob’ia.

Dans ce dépôt, elle est présentée sous l’angle LLM : comment jobs, artefacts et états de revue peuvent se connecter au contexte scène et aux décisions côté Unity.

---

## Rôle du LLM

Le LLM peut aider à :

- connecter un job Mob’ia à un contexte Unity ;
- expliquer l’état d’un artefact en termes de scène ;
- préparer des notes d’import ou de revue ;
- faire remonter les informations manquantes ;
- résumer la prochaine action éditeur utile.

---

## Workflow utile

```text
job Mob’ia → artefact → contexte Unity → note de revue → décision éditeur
```

Le but est d’éviter de traiter une sortie générée comme terminée avant qu’elle ait été comprise dans la scène ou le projet cible.

---

## Signaux de revue

| Signal | Sens |
| --- | --- |
| Le contexte job est lié | Le côté Unity sait à quoi sert l’artefact. |
| Le sens scène est visible | La sortie est revue selon son rôle attendu. |
| Les données manquantes sont nommées | Le workflow peut s’arrêter proprement au lieu d’inventer. |
| L’action éditeur est reviewable | La prochaine étape peut être validée ou corrigée par une personne. |

---

## Limite publique

Cette page n’expose pas les sources privées de l’extension Unity, fichiers projet, connecteurs internes ou données privées de jobs Mob’ia.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
