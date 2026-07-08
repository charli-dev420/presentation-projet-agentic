# Mob’ia Android

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

Mob’ia Android is the mobile product surface for following LLM-assisted generation and review workflows.

In this repository, the Android part is not presented as a generic app topic. It is presented as an interface where jobs, profiles, artifacts and review states become understandable to a user.

---

## LLM role

The LLM can help:

- describe a request;
- structure a job;
- summarize generation status;
- explain artifact state;
- prepare review wording;
- help the user choose the next action.

---

## Useful workflow

```text
profile → request → job → artifact → status → review → next action
```

The goal is to make complex generation work readable from a mobile product surface.

---

## Review signals

| Signal | Meaning |
| --- | --- |
| Job state is clear | The user can see whether work is pending, running, ready or blocked. |
| Artifact state is readable | The output is not just a file; it has status and context. |
| Review wording is useful | The app helps the user understand what to do next. |
| LLM role is bounded | The model explains and supports decisions without hiding control. |

---

## Public boundary

This page describes the product and LLM angle. It does not expose private mobile code, backend credentials, internal queues or unreleased packages.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Mob’ia Android est la surface produit mobile pour suivre des workflows de génération et de revue assistés par LLM.

Dans ce dépôt, la partie Android n’est pas présentée comme un sujet app générique. Elle est présentée comme une interface où jobs, profils, artefacts et états de revue deviennent compréhensibles pour l’utilisateur.

---

## Rôle du LLM

Le LLM peut aider à :

- décrire une demande ;
- structurer un job ;
- résumer un statut de génération ;
- expliquer l’état d’un artefact ;
- préparer le wording de revue ;
- aider l’utilisateur à choisir la prochaine action.

---

## Workflow utile

```text
profil → demande → job → artefact → statut → revue → prochaine action
```

Le but est de rendre un travail de génération complexe lisible depuis une surface produit mobile.

---

## Signaux de revue

| Signal | Sens |
| --- | --- |
| L’état du job est clair | L’utilisateur voit si le travail est en attente, en cours, prêt ou bloqué. |
| L’état de l’artefact est lisible | La sortie n’est pas seulement un fichier ; elle a un statut et un contexte. |
| Le wording de revue est utile | L’app aide l’utilisateur à comprendre quoi faire ensuite. |
| Le rôle LLM est borné | Le modèle explique et soutient la décision sans cacher le contrôle. |

---

## Limite publique

Cette page décrit l’angle produit et LLM. Elle n’expose pas le code mobile privé, les credentials backend, les queues internes ou packages non publiés.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
