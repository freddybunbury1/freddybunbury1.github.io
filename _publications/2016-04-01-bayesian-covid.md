---
title: "A Bayesian Hierarchical Network for Combining Heterogeneous Data Sources in Medical Diagnoses"
collection: publications
permalink: /publication/2016-04-01-bayesian-covid
excerpt: "Medical practitioners often reach a diagnosis after combining a patient's medical history, their answers to certain questions, and the results of medical tests. We sought to apply this framework in an automated manner using online questionnaires and lateral flow test results. We devised a Stochastic Expectation-Maximization algorithm within a Bayesian formalism to combine heterogeneous data sources, quantify their uncertainty and produce a probabilistic diagnosis. We quantify the potential of this approach on simulated data, and showcase its practicality by deploying it on a real COVID-19 immunity study."
date: 2020-06-01
venue: 'Proceedings of the Machine Learning for Health NeurIPS Workshop'
paperurl: 'http://proceedings.mlr.press/v136/donnat20a/donnat20a.pdf'
image: 'bayes_covid.png'
---

*Joint work with Claire Donnat, Nina Miolane and Jack Kreindler.*

The increasingly widespread use of affordable, yet often less reliable medical data and diagnostic tools poses a new challenge for the field of Computer-Aided Diagnosis: how can we combine multiple sources of information with varying levels of precision and uncertainty to provide an informative diagnosis estimate with confidence bounds? Motivated by a concrete application in lateral flow antibody testing, we devise a Stochastic Expectation-Maximization algorithm that allows the principled integration of heterogeneous and potentially unreliable data types. Our Bayesian formalism is essential in (a) flexibly combining these heterogeneous data sources and their corresponding levels of uncertainty, (b) quantifying the degree of confidence associated with a given diagnostic, and (c) dealing with the missing values that typically plague medical data. We quantify the potential of this approach on simulated data, and showcase its practicality by deploying it on a real COVID19 immunity study.

[Download paper here](http://proceedings.mlr.press/v136/donnat20a/donnat20a.pdf).


Recommended citation: Donnat, Claire, Nina Miolane, __Freddy Bunbury__, and Jack Kreindler. "A bayesian hierarchical network for combining heterogeneous data sources in medical diagnoses."  <i> In Machine Learning for Health (pp. 53-84). PMLR.</i>.
