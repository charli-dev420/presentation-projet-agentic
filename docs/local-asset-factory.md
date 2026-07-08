# LocalAssetFactory

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

LocalAssetFactory is the local loop for generated asset candidates.

It may also appear in a Unity or 3D showcase. In this repository, it is presented from the LLM-readable workflow angle: manifests, checks, review notes and decisions around generated candidates.

---

## LLM role

The LLM can help:

- read or prepare a manifest;
- describe expected asset behavior;
- identify missing metadata;
- summarize import and review checks;
- separate generation output from accepted asset status.

---

## Useful workflow

```text
generated candidate → manifest → normalization → import check → review note → decision
```

A candidate is not finished only because generation succeeded. It becomes useful when it can be inspected in the target context.

---

## Review signals

| Signal | Meaning |
| --- | --- |
| Manifest exists | The candidate has enough structure to review. |
| Normalization is clear | Scale, orientation, naming and format expectations are visible. |
| Import check is separate | Generation success and project usefulness are not confused. |
| Decision is explicit | Accept, revise, reject, archive or continue is named. |

---

## Public boundary

This page does not expose private asset packs, local scripts, generation jobs, unreleased datasets or internal Unity project data.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

LocalAssetFactory est la boucle locale autour des candidats assets générés.

Le projet peut aussi apparaître dans une vitrine Unity ou 3D. Dans ce dépôt, il est présenté sous l’angle workflow lisible par LLM : manifests, contrôles, notes de revue et décisions autour des candidats générés.

---

## Rôle du LLM

Le LLM peut aider à :

- lire ou préparer un manifest ;
- décrire le comportement attendu d’un asset ;
- identifier les métadonnées manquantes ;
- résumer les contrôles d’import et de revue ;
- séparer sortie de génération et statut d’asset accepté.

---

## Workflow utile

```text
candidat généré → manifest → normalisation → contrôle import → note de revue → décision
```

Un candidat n’est pas terminé parce que la génération a réussi. Il devient utile lorsqu’il peut être inspecté dans le contexte cible.

---

## Signaux de revue

| Signal | Sens |
| --- | --- |
| Le manifest existe | Le candidat a assez de structure pour être revu. |
| La normalisation est claire | Échelle, orientation, nommage et format attendu sont visibles. |
| Le contrôle d’import est séparé | Succès de génération et utilité projet ne sont pas confondus. |
| La décision est explicite | Accepter, corriger, refuser, archiver ou continuer est nommé. |

---

## Limite publique

Cette page n’expose pas les packs assets privés, scripts locaux, jobs de génération, datasets non publiés ou données internes de projets Unity.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
