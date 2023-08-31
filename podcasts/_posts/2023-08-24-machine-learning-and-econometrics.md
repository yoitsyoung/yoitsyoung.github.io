---
title: Opportunities in Machine Learning & Econometrics

tags: Economics

---

## Econometrics vs Machine Learning
Econometrics is the study of causality. The core of econometrics is the OLS (Ordinary Least Squares Regression). It begins with an equation and fits Beta values (gradients) to minimize the sum of errors. In all the regressors (x variables), one would be the causal regressor of interest, and the rest are controls; or in economist-speak, covariates.

Economic applications revolve around the condition of ceteris paribus; or "all other things being equal". What happens to y for a 1 unit/1 percent change in x? Machine learning revolves around the condition of mutatis mutandis; or "allowing other things to change accordingly". This targets the problem of prediction through a multiple-correlation approach.  For the former, causality is explicit and interpretable. for the latter, causality is a wicked, complex problem, and causal channels are often a black box.

Econometricians care about efficiency (reducing variance in the beta estimate), and how strong the inductive argument for causality is. They care about dealing with data specific to societal and market behaviour, which will have its quirks. They also care about using creative ways to argue for causality, identifying so called "natural experiments" in their studies.

Machine Learning scientists care about the bias-variance trade off, and the balance between the overfitting and accuracy of a prediction model. Besides prediction, machine learning scientists also work on extracting information from high volumes of data. The former is commonly known as "supervised learning", and the latter, "unsupervised".

It does not seem one approach is necessarily better than another, but from this lens it's clear why machine learning is currently in vogue, since the performance of ML models as a whole scale, at least logarithmically, to the amount of data available.

## Does Econometrics still Matter?
You're not alone if you think that ceteris paribus conditions never hold in a emergent systems like the economy, and probably ML techniques might better uncover patterns that continue into the future. But econometrics still matters. It is underpinned by human agency, and the assumption that we can figure out how to produce effects on the system itself.

There is a huge design space in bringing ML techniques into econometric studies. For example, in our age of big data, the number of covariates and interaction terms can outnumber the observations. Do we as econometricians leave such heterogeneity out of our regression models, or brusquely relegate them to so-called fixed effects? Machine learning can help us cope with this far more precisely.
