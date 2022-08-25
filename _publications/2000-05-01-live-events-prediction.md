---
title: "Predicting COVID-19 Transmission to Inform the Management of Mass Events: Model-Based Approach"
collection: publications
permalink: /publication/2000-05-01-live-events-prediction
excerpt: 'Predicting infectious disease transmission at future public events is a highly uncertain process. In the context of the COVID-19 pandemic, we aimed to systematize the process by 1) reliably model the infectious proportion of participants at a future event, 2) evaluate the efficiency of pre-event screening protocols, and 3) model an event’s transmission dynamics and uncertainty using Monte Carlo simulations. Illustrating the process on a hypothetical concert at the Royal Albert Hall, we tested the effect of factors such as mask wearing, participant reduction, antigen test screening, and delaying the event. Our model is available as a user-friendly RShiny interface and can give event organizers and participants alike an rough understanding of the infection risks associated with attending public events.'
date: 2021-12-01
venue: 'JMIR public health and surveillance'
paperurl: 'https://publichealth.jmir.org/2021/12/e30648'
image: 'events.png'
---
*Joint work with  Claire Donnat, David Liu, Jack Kreindler, Filippos T. Filippidis, Austen El-Osta, Tõnu Esko, and Matthew Harris.*

Background:
Modelling COVID-19 transmission at live events and public gatherings is essential to controlling the probability of subsequent outbreaks and communicating to participants their personalized risk. Yet, despite the fast-growing body of literature on COVID-19 transmission dynamics, current risk models either neglect contextual information including vaccination rates or disease prevalence or do not attempt to quantitatively model transmission.

Objective:
This paper attempted to bridge this gap by providing informative risk metrics for live public events, along with a measure of their uncertainty.

Methods:
Building upon existing models, our approach ties together 3 main components: (1) reliable modelling of the number of infectious cases at the time of the event, (2) evaluation of the efficiency of pre-event screening, and (3) modelling of the event’s transmission dynamics and their uncertainty using Monte Carlo simulations.

Results:
We illustrated the application of our pipeline for a concert at the Royal Albert Hall and highlighted the risk’s dependency on factors such as prevalence, mask wearing, and event duration. We demonstrate how this event held on 3 different dates (August 20, 2020; January 20, 2021; and March 20, 2021) would likely lead to transmission events that are similar to community transmission rates (0.06 vs 0.07, 2.38 vs 2.39, and 0.67 vs 0.60, respectively). However, differences between event and background transmissions substantially widened in the upper tails of the distribution of the number of infections (as denoted by their respective 99th quantiles: 1 vs 1, 19 vs 8, and 6 vs 3, respectively, for our 3 dates), further demonstrating that sole reliance on vaccination and antigen testing to gain entry would likely significantly underestimate the tail risk of the event.

Conclusions:
Despite the unknowns surrounding COVID-19 transmission, our estimation pipeline opens the discussion on contextualized risk assessment by combining the best tools at hand to assess the order of magnitude of the risk. Our model can be applied to any future event and is presented in a user-friendly RShiny interface. Finally, we discussed our model’s limitations as well as avenues for model evaluation and improvement.'

[Download paper here](https://publichealth.jmir.org/2021/12/e30648).



Recommended citation: Donnat, Claire, __Freddy Bunbury,__ Jack Kreindler, David Liu, Filippos T. Filippidis, Tonu Esko, Austen El-Osta, and Matthew Harris. "Predicting COVID-19 Transmission to Inform the Management of Mass Events: Model-Based Approach." <i> JMIR public health and surveillance 7, no. 12 (2021): e30648</i>.
