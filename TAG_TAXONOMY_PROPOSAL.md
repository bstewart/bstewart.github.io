# Publication Tag Taxonomy Proposal

This is a review draft for replacing the current broad publication tags with a smaller set of more meaningful public tags. I have not applied these to the Hugo publication front matter yet.

## Recommended Public Tags

| Tag | Use for | Recommendation behavior |
| --- | --- | --- |
| Text Measurement & Validation | Text-as-data workflow, coding, transparency, measurement, validation, and field-framing pieces. | Connects foundational and validation-oriented text-as-data work without tagging every text paper as "text as data." |
| Topic Models & Discovery | STM, topic-model diagnostics, topic validation, discovery workflows, and topic-model software papers. | Keeps the STM/topic-model cluster coherent. |
| Embeddings & Semantic Representation | Word embeddings, contextual embeddings, semantic spaces, embedding comparison, and representation learning. | Connects conText, ALC, multilingual embeddings, and distance-bias papers. |
| Causal Inference with Text | Papers where text is a treatment, outcome, confounder, proxy, or part of the causal identification problem. | Separates causal-text work from broader causal inference. |
| AI Annotation & Predicted Variables | LLM/supervised labels, predicted variables, surrogate outcomes, annotation error, and downstream inference with generated labels. | Gives the DSL and LLM-annotation papers a specific home. |
| Generative AI & LLMs | LLM behavior, prompting/reasoning, generative model evaluation, LLM-coded expertise, and LLM influence. | Links LLM papers, but should usually be paired with a second tag to avoid noisy recommendations. |
| Research Design & Valid Inference | Estimands, IVs, regression logic, statistical validity, deconfounding, ML validity, and general design/inference pieces. | Replaces the old generic causal-inference bucket for non-text design papers. |
| Prediction & Algorithmic Systems | Predictive modeling, ML evaluation, recommender systems, deployed algorithmic systems, and feedback loops. | Covers ML/prediction/platform papers without making "machine learning" a generic tag. |
| Media & Information Environments | News media, propaganda, political communication, political emails, Fedspeak, state media, and source bias. | Connects substantive information-environment applications across eras. |
| Diffusion, Conflict & Migration | International diffusion, transnational crime, forced migration, conflict, event data, and geopolitical applications. | Keeps the IR/conflict/diffusion work visible as an application thread. |

## Assignment Principles

- Use 1-3 public tags per publication. More than 3 will make filtering and related-publication scoring noisy.
- Tag by the central contribution, not by every technique used in the paper.
- Do not revive `text as data`, `machine learning`, or `causal inference` as public tags; those are too broad.
- Keep `software` as hidden/site metadata if needed, but do not use it for public recommendations. It links otherwise unrelated papers.
- It is acceptable for a few outliers to have no public research tag or only one broad design tag.
- For related-publication scoring, these tags can be combined later with coauthors, year proximity, and abstract similarity. The public tags should stay readable and compact.

## Draft Paper Assignments

| Year | Publication | Draft tags |
| --- | --- | --- |
| 2026 | Using Large Language Model Annotations for the Social Sciences: A General Framework of Using Predicted Variables in Downstream Analyses | AI Annotation & Predicted Variables; Causal Inference with Text; Generative AI & LLMs |
| 2026 | State Media Control Influences Large Language Models | Generative AI & LLMs; Media & Information Environments |
| 2026 | STATe-of-Thoughts: Structured Action Templates for Tree-of-Thoughts | Generative AI & LLMs |
| 2026 | Handle with Care: A Sociologist's Guide to Causal Inference with Instrumental Variables | Research Design & Valid Inference |
| 2026 | Fine-Tuned Large Language Models Can Replicate Expert Coding Better Than Trained Coders | AI Annotation & Predicted Variables; Generative AI & LLMs; Media & Information Environments |
| 2025 | What Good Is a Regression? Inference to the Best Explanation and the Practice of Political Science Research | Research Design & Valid Inference |
| 2025 | The Decade-Long Growth of Government-Authored News Media in China under Xi Jinping | Media & Information Environments |
| 2025 | Short-Term Exposure to "Filter-Bubble" Recommendation Systems Has Limited Polarization Effects | Prediction & Algorithmic Systems; Media & Information Environments; Research Design & Valid Inference |
| 2025 | Multilanguage Word Embeddings for Social Scientists | Embeddings & Semantic Representation |
| 2025 | Measuring Distances in High-Dimensional Spaces | Embeddings & Semantic Representation; Research Design & Valid Inference |
| 2025 | Correcting the Measurement Errors of AI-Assisted Labeling in Image Analysis Using Design-Based Supervised Learning | AI Annotation & Predicted Variables; Research Design & Valid Inference |
| 2024 | REFORMS: Consensus-Based Recommendations for Machine-Learning-Based Science | Prediction & Algorithmic Systems; Research Design & Valid Inference |
| 2024 | More Victories, Less Cooperation: Assessing Cicero's Diplomacy Play | Generative AI & LLMs; Prediction & Algorithmic Systems |
| 2024 | AutoPersuade: A Framework for Evaluating and Explaining Persuasive Arguments | Generative AI & LLMs; Topic Models & Discovery; Media & Information Environments |
| 2023 | Using Imperfect Surrogates for Downstream Inference | AI Annotation & Predicted Variables; Causal Inference with Text |
| 2023 | Naive Regression Requires Weaker Assumptions than Factor Models to Adjust for Multiple Cause Confounding | Research Design & Valid Inference |
| 2023 | Manipulative Tactics Are the Norm in Political Emails | Media & Information Environments |
| 2023 | GPT Deciphering Fedspeak | AI Annotation & Predicted Variables; Generative AI & LLMs; Media & Information Environments |
| 2023 | Embedding Regression: Models for Context-Specific Description and Inference | Embeddings & Semantic Representation; Text Measurement & Validation |
| 2023 | Credible without Credit: Domain Experts Assess Generative Language Models | Generative AI & LLMs |
| 2022 | Topics, Concepts, and Measurement | Topic Models & Discovery; Text Measurement & Validation |
| 2022 | Text as Data: A New Framework for Machine Learning and the Social Sciences | Text Measurement & Validation; Causal Inference with Text; Topic Models & Discovery |
| 2022 | How to Make Causal Inferences Using Texts | Causal Inference with Text |
| 2022 | Causal Inference in Natural Language Processing | Causal Inference with Text |
| 2021 | What Is Your Estimand? | Research Design & Valid Inference |
| 2021 | Machine Learning for Social Science: An Agnostic Approach | Prediction & Algorithmic Systems; Research Design & Valid Inference |
| 2020 | Wrestling with Complexity in Computational Social Science | Prediction & Algorithmic Systems; Research Design & Valid Inference |
| 2020 | Measuring the Predictability of Life Outcomes with a Scientific Mass Collaboration | Prediction & Algorithmic Systems; Research Design & Valid Inference |
| 2020 | Comment: Summarizing Income Mobility with Multiple Smooth Quantiles Instead of Parameterized Means | Research Design & Valid Inference |
| 2020 | Adjusting for Confounding with Text Matching | Causal Inference with Text |
| 2019 | stm: An R Package for Structural Topic Models | Topic Models & Discovery |
| 2019 | What Makes Foreign Policy Teams Tick | Topic Models & Discovery; Prediction & Algorithmic Systems; Diffusion, Conflict & Migration |
| 2018 | The Global Diffusion of Law | Diffusion, Conflict & Migration |
| 2018 | The Civic Mission of MOOCs: Engagement across Political Differences in Online Forums | Prediction & Algorithmic Systems; Media & Information Environments |
| 2018 | How Algorithmic Confounding in Recommendation Systems Increases Homogeneity and Decreases Utility | Prediction & Algorithmic Systems; Research Design & Valid Inference |
| 2018 | A La Carte Embedding | Embeddings & Semantic Representation |
| 2017 | Discourse: MOOC Discussion Forum Analysis at Scale | Text Measurement & Validation; Prediction & Algorithmic Systems |
| 2016 | The Civic Mission of MOOCs: Measuring Engagement across Political Differences in Forums | Prediction & Algorithmic Systems; Media & Information Environments |
| 2016 | Navigating the Local Modes of Big Data | Topic Models & Discovery |
| 2016 | A Model of Text for Experimentation in the Social Sciences | Topic Models & Discovery; Causal Inference with Text |
| 2015 | TopicCheck | Topic Models & Discovery; Text Measurement & Validation |
| 2015 | Plain Text | Text Measurement & Validation |
| 2015 | Computer-Assisted Text Analysis for Comparative Politics | Text Measurement & Validation; Topic Models & Discovery |
| 2015 | Computer-Assisted Reading and Discovery for Student Generated Text in Massive Open Online Courses | Topic Models & Discovery; Prediction & Algorithmic Systems |
| 2014 | lbfgs: Efficient L-BFGS and OWL-QN Optimization in R | No public research tag; keep hidden software metadata only |
| 2014 | Structural Topic Models for Open-Ended Survey Responses | Topic Models & Discovery; Text Measurement & Validation |
| 2014 | Latent Factor Regressions for the Social Sciences | Research Design & Valid Inference |
| 2014 | Computer-Assisted Content Analysis | Topic Models & Discovery; Text Measurement & Validation |
| 2013 | The Structural Topic Model and Applied Social Science | Topic Models & Discovery |
| 2013 | Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts | Text Measurement & Validation |
| 2013 | Psychological and Physiological Responses Following Repeated Peer Death | No public research tag, or Research Design & Valid Inference if every publication must have one |
| 2013 | Learning to Extract International Relations from Political Context | Text Measurement & Validation; Diffusion, Conflict & Migration |
| 2013 | Choosing Your Neighbors: Networks of Diffusion in International Relations | Diffusion, Conflict & Migration; Research Design & Valid Inference |
| 2012 | Combating Transnational Crime | Diffusion, Conflict & Migration |
| 2009 | Use of Force and Civil-Military Relations in Russia | Media & Information Environments; Diffusion, Conflict & Migration; Text Measurement & Validation |
| 2007 | Predicting Risk Factors Associated With Forced Migration | Diffusion, Conflict & Migration; Prediction & Algorithmic Systems |
| 2007 | Political Persecution or Economic Deprivation? | Diffusion, Conflict & Migration |
| 2006 | Fair & Balanced or Fit to Print? | Media & Information Environments; Text Measurement & Validation; Diffusion, Conflict & Migration |

## Critique-Agent Checks

Three independent passes broadly supported the 10-tag structure, with cautions:

- Avoid using any one tag as a replacement for the old generic `text as data` tag.
- `Generative AI & LLMs` should not be the only tag on LLM annotation or LLM media-influence papers, or related publications will be too loose.
- The older corpus needs labels broad enough to include computer-assisted coding and validation, not only modern LLM annotation.
- A few outliers, especially `lbfgs` and the peer-death appendix, should not be forced into a public research tag if the fit is weak.
- Related-publication scoring would improve if hidden `software` stopped contributing to the score, while coauthor/year/abstract similarity could remain as secondary signals.
