# Mob’ia / ccomf-unity

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

Mob’ia / ccomf-unity is the product layer around ComfyUI-style workflows.

The agentic angle is not the raw generation pipeline itself. It is the way the LLM helps make profiles, jobs, artifacts, client states and review decisions easier to follow.

---

## LLM role

The LLM can help:

- turn a user request into a profile or job shape;
- summarize workflow state;
- explain artifact status;
- prepare client-facing notes;
- support review and next-action decisions.

---

## Useful workflow

```text
request → profile → job → artifact → client state → review decision
```

This makes generation workflows more understandable to people who did not build the pipeline.

---

## Review signals

| Signal | Meaning |
| --- | --- |
| Profile is readable | The workflow has a clear user or use-case context. |
| Job state is explicit | A reviewer can see what is happening and why. |
| Artifact is not anonymous | The result has a role, status and review state. |
| Client note is useful | The user can understand the output without raw ComfyUI internals. |

---

## Public boundary

This page does not expose private ComfyUI workflows, private models, credentials, internal queues or customer/project data.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Mob’ia / ccomf-unity est la couche produit autour des workflows type ComfyUI.

L’angle agentic n’est pas le pipeline de génération brut. C’est la manière dont le LLM aide à rendre profils, jobs, artefacts, états client et décisions de revue plus faciles à suivre.

---

## Rôle du LLM

Le LLM peut aider à :

- transformer une demande utilisateur en profil ou forme de job ;
- résumer l’état du workflow ;
- expliquer le statut d’un artefact ;
- préparer des notes côté client ;
- soutenir les décisions de revue et prochaine action.

---

## Workflow utile

```text
demande → profil → job → artefact → état client → décision de revue
```

Cela rend les workflows de génération plus compréhensibles pour les personnes qui n’ont pas construit le pipeline.

---

## Signaux de revue

| Signal | Sens |
| --- | --- |
| Le profil est lisible | Le workflow a un contexte utilisateur ou usage clair. |
| L’état du job est explicite | Un reviewer peut voir ce qui se passe et pourquoi. |
| L’artefact n’est pas anonyme | Le résultat a un rôle, un statut et un état de revue. |
| La note client est utile | L’utilisateur comprend la sortie sans les internes ComfyUI bruts. |

---

## Limite publique

Cette page n’expose pas les workflows ComfyUI privés, modèles privés, credentials, queues internes ou données client/projet.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
