---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Active projects

[**Mathematical & Economic Modelling for Vaccination and Immunisation Evaluation (MEMVIE):**]({{ site.baseurl }}{% link _activeresearch/MEMVIE.md %}){:target="_blank"} Epidemiological modelling and health economic modelling to underpin vaccination policy for the Department of Health.

[**Quantifying the impact of HPAI in wild bird and domestic poultry populations:**]({{ site.baseurl }}{% link _activeresearch/wildbird_HPAI.md %}){:target="_blank"} Using mathematical modelling to understand the spread and inform the control of Highly Pathogenic Avian Influenza (HPAI) in wild birds and domestic poultry in the UK.

[**Epidemiological-behavioural modelling applied to public, veterinary and plant health:**]({{ site.baseurl }}{% link _activeresearch/epi_behaviour_modelling.md %}){:target="_blank"} Employing interdisciplinary approaches to improve our understanding of disease management behaviour and its incorporation into epidemiological models.

[**Investigating the impact of symptom propagation on epidemiological and health economic outcomes:**]({{ site.baseurl }}{% link _activeresearch/symptom_propagation.md %}){:target="_blank"} Using mathematical models as a tool to explore the extent to which symptom propagation exists and its subsequent impact on epidemiological and health economic assessments.

## Previous projects

[**Response to the COVID-19 pandemic:**]({{ site.baseurl }}{% link _priorresearch/covid-19.md %}){:target="_blank"} Using real time data on the UK COVID-19 outbreak to provide robust predictions, gauging the ability of a model to predict future epidemic behaviour.

[**Social contagion:**]({{ site.baseurl }}{% link _priorresearch/social_contagion.md %}){:target="_blank"} Spread of behaviour-linked health problems are amenable to being represented with methodological approaches typically used to model infectious diseases. We explore this with regards to depression, developing novel models that exploit the dynamical behaviour of mood over time to ascertain which mood states spread on social networks, via a contagion-like mechanism, and which do not.

[**Influenza A at the human-animal interface:**]({{ site.baseurl }}{% link _priorresearch/zoonotic_flu.md %}){:target="_blank"} Influenza inhabits many hosts and has many strains, but there is a worrying gap in the modelling of spillover transmission from animals to humans. Looking at addressing the lack of established modelling tools that represent this interface, with the applied aim of aiding the design and performance assessment of control strategies for influenza among livestock and across the animal-human interface.

[**Visceral leishmaniasis in Brazil:**]({{ site.baseurl }}{% link _priorresearch/leishmaniasis.md %}){:target="_blank"} Developing a mathematical model of visceral leishmaniasis in Brazil; a vector borne disease with canines being an animal reservoir.

{% include base_path %}

{% assign ordered_pages = site.activeresearch | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

{% include base_path %}

{% assign ordered_pages = site.priorresearch | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}