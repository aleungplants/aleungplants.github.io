---
layout: default
---

I'm an ecophysiologist at the <a href='https://eeb.utoronto.ca'>Dept. of Ecology & Evolutionary Biology</a>, U. of Toronto, Canada.

The goal of my PhD research is to gain mechanistic understanding into the evolution of C4 photosynthesis, a key innovation in flowering plants that enabled diversification into warm and semi-arid habitats. C4 photosynthesis involves modifications to primary metabolic pathways which are typically under purifying or neutral selection, yet it has has evolved over 60 times independently. Thus, it is a unique study system that allows the integration of physiology, ecology, and evolution for insights into how the biosphere was assembled in the last ~30 million years.

**Blog**
{% for post in paginator.posts %}
- {{ post.date | date_to_string }} [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

Funding acknowledgements
- Queen Elizabeth II/Charles E. Eckenwalder Scholarship in Science and Technology
- NSERC Undergraduate Student Research Award
- NSERC Canadian Forest Sector supplement

Contact
- Email (art.leung <at> mail.utoronto.ca)
- Twitter ([@aleungplants](https://twitter.com/aleungplants)
