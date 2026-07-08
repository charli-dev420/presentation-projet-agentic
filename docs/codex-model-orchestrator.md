# Codex Model Orchestrator

<p align="center">
  <strong>Language / Langue</strong><br>
  <a href="#english">🇬🇧 English</a> ·
  <a href="#francais">🇫🇷 Français</a>
</p>

---

<h2 id="english">🇬🇧 English</h2>

Codex Model Orchestrator is the orchestration line of the agentic showcase.

Its role is to make AI-assisted work easier to scope, route, check and hand back to a person. The value is not that an agent says “done”; the value is that the run remains understandable afterwards.

---

## LLM role

The LLM helps:

- understand the request;
- define scope, constraints and expected output;
- choose tools, workers or sub-steps;
- keep the run readable while work happens;
- summarize what changed;
- prepare a human decision.

---

## Useful workflow

```text
request → scope → tool path → artifact → checks → uncertainty → decision
```

A run is useful when another person can read it later and understand what happened without needing the full private context.

---

## Public review checklist

| Question | Expected signal |
| --- | --- |
| Is the task scope clear? | Goal, constraints and expected output are written. |
| Are tool actions understandable? | The path is visible enough to review. |
| Is the output named? | The result is an artifact, note, state or decision card. |
| Are weak points visible? | Uncertainty and remaining review are not hidden. |
| Can a human decide next? | Accept, revise, reject, continue or escalate is clear. |

---

## Boundary

This public page presents the product direction and workflow model.

It does not expose private orchestration prompts, credentials, private tool configs, internal agent routing rules or sensitive automation details.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Codex Model Orchestrator est la ligne orchestration de la vitrine agentic.

Son rôle est de rendre le travail assisté par IA plus facile à cadrer, router, vérifier et remettre à une personne. La valeur n’est pas qu’un agent dise “done”; la valeur est que le run reste compréhensible après coup.

---

## Rôle du LLM

Le LLM aide à :

- comprendre la demande ;
- définir le périmètre, les contraintes et la sortie attendue ;
- choisir les outils, workers ou sous-étapes ;
- garder le run lisible pendant le travail ;
- résumer ce qui a changé ;
- préparer une décision humaine.

---

## Workflow utile

```text
requête → périmètre → chemin outil → artefact → contrôles → incertitude → décision
```

Un run est utile lorsqu’une autre personne peut le relire plus tard et comprendre ce qui s’est passé sans avoir besoin de tout le contexte privé.

---

## Checklist de revue publique

| Question | Signal attendu |
| --- | --- |
| Le périmètre est-il clair ? | Objectif, contraintes et sortie attendue sont écrits. |
| Les actions outil sont-elles compréhensibles ? | Le chemin est assez visible pour être revu. |
| La sortie est-elle nommée ? | Le résultat existe comme artefact, note, état ou carte de décision. |
| Les points faibles sont-ils visibles ? | L’incertitude et la revue restante ne sont pas cachées. |
| Un humain peut-il décider la suite ? | Accepter, corriger, refuser, continuer ou escalader est clair. |

---

## Limite

Cette page publique présente la direction produit et le modèle de workflow.

Elle n’expose pas les prompts privés d’orchestration, credentials, configurations outil privées, règles internes de routage agent ou détails d’automatisation sensibles.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
