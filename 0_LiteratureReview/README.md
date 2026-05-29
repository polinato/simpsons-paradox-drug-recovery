# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: An Introduction to Causal Inference - Judea Pearl

  - https://ftp.cs.ucla.edu/pub/stat_ser/r354-corrected-reprint.pdf
  - **Objective**:
    The paper summarizes modern advances in causal inference and emphasizes the need to shift from traditional statistical analysis toward causal analysis of multivariate data. Pearl argues that valid causal claims require explicit assumptions formalized through causal graphs and do-operators.
  - **Methods**:
    The article is based on the theory of Structural Causal Models (SCM) and graphical causal analysis. Pearl introduces causal diagrams (DAGs), intervention analysis using the do-operator, and counterfactual reasoning. The paper also reviews formal languages used to represent causal assumptions and causal effects.
  - **Outcomes**:
    The work presents a unified framework for causal inference that combines graphical models with potential outcome approaches. It describes mathematical tools for estimating intervention effects, counterfactual probabilities, and direct and indirect causal effects. The paper also provides important theoretical foundations for mediation analysis and causal effect estimation.
  - **Relation to the Project**:
    This paper provides the theoretical foundation for causal reasoning. In particular, it explains how to estimate intervention effects such as do(drug) instead of relying on simple correlations. This is essential for distinguishing the true causal effect of the drug from misleading observational patterns in the dataset.

- **Source 2**: Simpson’s Paradox Beyond Confounding - Zili Dong, Weixin Cai & Shimin Zhao 

  - https://link.springer.com/article/10.1007/s13194-024-00610-8
  - **Objective**:
    The paper investigates whether Simpson’s paradox can occur without classical confounding variables. The authors argue that some forms of the paradox may emerge purely from statistical aggregation rather than genuine causal relationships.
  - **Methods**:
    The study uses analytical examples, probabilistic reasoning, and causal interpretations of different paradoxical scenarios. Several illustrative cases are examined to demonstrate how reversal effects may occur even without traditional hidden confounders.
  - **Outcomes**:
    The authors show that Simpson’s paradox can sometimes arise from purely statistical or arithmetic properties of aggregated data. However, they also conclude that such cases are relatively rare in practice and that most real-world examples are driven by meaningful causal structures and confounding effects.
  - **Relation to the Project**:
    This source supports the theoretical discussion of the project by highlighting that Simpson’s paradox is strongly connected to causal interpretation. It reinforces the importance of examining confounders such as SES and hospital quality when evaluating drug effectiveness in observational healthcare data.

- **Source 3**: The ubiquity of the Simpson’s Paradox - Alessandro Selvitella

  - https://link.springer.com/article/10.1186/s40488-017-0056-5
  - **Objective**:
    The purpose of this paper is to examine how Simpson’s paradox emerges across different scientific disciplines and to explain why aggregated statistical trends can reverse after conditioning on subgroup variables. The author aims to demonstrate that the paradox is not a rare statistical curiosity, but rather a common phenomenon in observational data analysis.
  - **Methods**:
    The study relies on probability theory, contingency table analysis, and mathematical demonstrations of trend reversals between aggregated and stratified datasets. The paper analyzes multiple examples from social sciences, medicine, and statistics to illustrate how hidden subgroup structures can distort overall associations. The author also discusses the role of confounding variables and conditional probabilities in generating paradoxical conclusions.
  - **Outcomes**:
    The paper concludes that Simpson’s paradox is widespread in real-world datasets and often occurs when important subgroup information is ignored during statistical analysis. The study emphasizes that aggregated observational data may produce misleading or even opposite conclusions compared to subgroup-level analysis. It also highlights the importance of stratification and causal reasoning when interpreting statistical relationships.
  - **Relation to the Project**:
    This source is highly relevant to the project because it provides both theoretical and practical insight into why the relationship between drug treatment and recovery may appear differently before and after controlling for SES. The paper directly supports the project’s central argument that observational healthcare data can lead to misleading conclusions if subgroup structures and confounding variables are ignored. Additionally, it reinforces the importance of causal interpretation rather than relying solely on aggregated statistical correlations.
