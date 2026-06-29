# Resources / Ressources

[EN](#english) | [FR](#francais)

## English

### Glossary

| Term | Working definition in this showcase |
| --- | --- |
| Agentic | A system where an agent plans, calls tools, delegates, tracks state, and produces evidence for human decision. |
| Orchestrator | The control layer that scopes work, routes sub-tasks, gathers results, runs gates, and summarizes proof. |
| Sub-agent | A specialized worker used for a bounded part of the task. Its output is reviewed rather than blindly accepted. |
| MCP | Tool contract layer between an agent and external capabilities. It should define read/write boundaries and confirmation needs. |
| Apps SDK | Presentation layer for agentic products, used to show state, actions, dashboards, and decision surfaces inside a chat-driven experience. |
| Proof kit | A set of evidence levels, proof cards, QA gates, redaction rules, and decision summaries. |
| Evidence level | A label from L0 to L5 that says how strong a claim is, from instrumentation to independent reproduction or opt-in telemetry. |
| QA gate | A check that turns a run into a decision: pass, revise, fail, blocked, or needs private review. |
| BYOK | Bring your own key. Useful for community benchmarks or partner demos where credentials should stay with the participant. |
| ComfyUI | Node-based generation environment. In this showcase it is treated as a workflow engine that needs product framing and review surfaces. |
| GLB | 3D asset format used in asset pipelines. Public docs can discuss validation without publishing private generated assets. |

### Main Reading Paths

| Need | Read |
| --- | --- |
| First overview | [One-pager](one-pager.md), [ecosystem map](ecosystem-map.md), [visual gallery](visual-gallery.md) |
| Proof and QA | [Evidence](evidence.md), [evidence ledger](evidence-ledger.md), [proof pack](proof-pack.md), [QA matrix](qa-matrix.md), [QA validation](qa-validation.md) |
| Buyer or partner decision | [Buyer evaluation](buyer-evaluation.md), [partnership brief](partnership.md), [decision pack](decision-pack.md), [roadmap](roadmap.md) |
| Project surfaces | [Codex Model Orchestrator](projects/codex-model-orchestrator.md), [CodexToUnity](projects/codextounity.md), [Mob'ia / ccomf-unity](projects/mobia-ccomf-unity.md), [LocalAssetFactory](projects/local-asset-factory.md) |
| Boundaries | [Public scope](public-scope.md), [security and privacy](security-privacy.md), [redaction policy](redaction-policy.md) |

### Evaluation Shortcut

For any claim in the repository, ask:

1. What scenario does it belong to?
2. Which evidence level supports it?
3. Which QA gate would catch a bad output?
4. Where does a human decide?
5. What public artifact can be shared safely?

## Francais

### Glossaire

| Terme | Definition dans cette vitrine |
| --- | --- |
| Agentic | Systeme ou un agent planifie, appelle des outils, delegue, suit l'etat et produit des preuves pour decision humaine. |
| Orchestrateur | Couche de controle qui cadre le travail, route les sous-taches, collecte les resultats, lance les gates et resume la preuve. |
| Sous-agent | Travailleur specialise utilise pour une partie bornee de la tache. Sa sortie est revue, pas acceptee aveuglement. |
| MCP | Couche de contrat outil entre un agent et des capacites externes. Elle doit definir frontieres read/write et confirmations. |
| Apps SDK | Couche de presentation pour produits agentiques, utilisee pour afficher etat, actions, dashboards et decisions dans une experience chat. |
| Proof kit | Ensemble de niveaux de preuve, proof cards, gates QA, regles de redaction et resumes de decision. |
| Niveau de preuve | Label L0 a L5 indiquant la force d'un claim, de l'instrumentation a la reproduction independante ou telemetrie opt-in. |
| Gate QA | Controle qui transforme un run en decision: pass, revision, fail, blocked ou revue privee necessaire. |
| BYOK | Bring your own key. Utile pour benchmarks communautaires ou demos partenaires ou les credentials restent chez le participant. |
| ComfyUI | Environnement de generation node-based. Ici, il est traite comme moteur workflow demandant cadrage produit et surfaces de revue. |
| GLB | Format asset 3D utilise dans les pipelines. Les docs publiques peuvent discuter validation sans publier d'assets prives generes. |

### Parcours De Lecture

| Besoin | Lire |
| --- | --- |
| Vue d'ensemble | [One-pager](one-pager.md), [ecosystem map](ecosystem-map.md), [visual gallery](visual-gallery.md) |
| Preuve et QA | [Evidence](evidence.md), [evidence ledger](evidence-ledger.md), [proof pack](proof-pack.md), [QA matrix](qa-matrix.md), [QA validation](qa-validation.md) |
| Decision acheteur ou partenaire | [Buyer evaluation](buyer-evaluation.md), [partnership brief](partnership.md), [decision pack](decision-pack.md), [roadmap](roadmap.md) |
| Surfaces projet | [Codex Model Orchestrator](projects/codex-model-orchestrator.md), [CodexToUnity](projects/codextounity.md), [Mob'ia / ccomf-unity](projects/mobia-ccomf-unity.md), [LocalAssetFactory](projects/local-asset-factory.md) |
| Frontieres | [Public scope](public-scope.md), [security and privacy](security-privacy.md), [redaction policy](redaction-policy.md) |

### Raccourci D'Evaluation

Pour tout claim du repo, demander:

1. A quel scenario appartient-il?
2. Quel niveau de preuve le soutient?
3. Quel gate QA attraperait une mauvaise sortie?
4. Ou l'humain decide-t-il?
5. Quel artefact public peut etre partage sans risque?
