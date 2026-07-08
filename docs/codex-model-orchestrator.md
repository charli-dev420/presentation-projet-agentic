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
- define scope and constraints;
- choose tools or workers;
- keep the run readable;
- summarize what changed;
- prepare a human decision.

---

## Useful output

A useful run should leave a compact record:

```text
request → scope → tool path → artifact → checks → uncertainty → decision
```

This makes the result easier to revise, reuse, reject or continue.

---

## Public boundary

This page presents the product direction and public workflow model. It does not expose private orchestration prompts, credentials, private tool configs or internal automation details.

<p align="right"><a href="../README.md">← Back to README</a> · <a href="#francais">Français</a></p>

---

<h2 id="francais">🇫🇷 Français</h2>

Codex Model Orchestrator est la ligne orchestration de la vitrine agentic.

Son rôle est de rendre le travail assisté par IA plus facile à cadrer, router, vérifier et remettre à une personne. La valeur n’est pas qu’un agent dise “done”; la valeur est que le run reste compréhensible après coup.

---

## Rôle du LLM

Le LLM aide à :

- comprendre la demande ;
- définir le périmètre et les contraintes ;
- choisir les outils ou workers ;
- garder le run lisible ;
- résumer ce qui a changé ;
- préparer une décision humaine.

---

## Sortie utile

Un run utile doit laisser une trace compacte :

```text
requête → périmètre → chemin outil → artefact → contrôles → incertitude → décision
```

Cela rend le résultat plus simple à corriger, réutiliser, refuser ou poursuivre.

---

## Limite publique

Cette page présente la direction produit et le modèle de workflow public. Elle n’expose pas les prompts privés d’orchestration, credentials, configurations outil privées ou détails d’automatisation internes.

<p align="right"><a href="../README.md">← Retour au README</a> · <a href="#english">English</a></p>
