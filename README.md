# Shapley Values - June 6, 2019 Lunch & Learn

## Summary
This tutorial introduces Shapley Values and explains how they can be used to understand complex machine learning models.

## Why
Most high performing models, such as neural networks and ensembles, are difficult to interpret. Non-technical end users that rely on results of these complex models may not fully trust the results these models produce if they are not well understood. Furthermore, certain ethical and legal risks can be unintentionally introduced by using a black box model. Practitioners need to consider these risks before implementing high performing models into production at the scale that automation provides.

Shapley values are a way to interpret complex models and which features are effecting a particular prediction.

## What
This tutorial will first discuss the need for interpretable machine learning review existing methods. Then Shapley Values will be explained in both the game theory and machine learning context. After this description, the tutorial will walk though an implementatation in Python using the `shap` package. Finally, the tutorial makes mention of another tool to be added as part of future work: `Aequitas`.

## Sources

Many resources were used in the creation of this tutorial:

- ["Game Theory for model interpretability: Shapley Values"](http://lineardigressions.com/episodes/2018/5/6/game-theory-for-model-interpretability-shapley-values)
- ["SHAP: Shapley Values in Machine Learning"](http://lineardigressions.com/episodes/2018/5/13/shap-shapley-values-in-machine-learning)
- [A Unified Approach to Interpreting Model Predictions](http://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions.pdf)
- [Consistent Individualized Feature Attribution for Tree Ensembles](https://arxiv.org/pdf/1802.03888.pdf)
- [UCI Machine Learning Repository - Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- [shap Python package](https://github.com/slundberg/shap)
- [Aequitas](https://github.com/dssg/aequitas)