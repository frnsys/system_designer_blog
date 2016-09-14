---
published_at: 07.01.2016 17:04
author: Francis Tseng
---

# Social Simulation Components: Cultural Values

The agents in [`syd`](/projects/sim_architecture) will need to be parameterized in some way that meaningfully affects their behavior. Another way to put this is that the agents need some values that guide their actions. In [Humans of Simulated New York](http://spaceandtim.es/projects/hosny) Fei and I defined individuals along the axes of greed vs altruism, lavishness vs frugality, long-sightedness vs short-sightedness, and introversion vs extroversion. The exact configuration of these values are what made an agent an individual: a lavish agent would spend more of their money, an extroverted agent would have a larger network of friends (which consequently made finding a job easier), greedy agents would pay their employees less, and so on.

![HOSNY value dimensions](/assets/uploads/hosny_dimensions.png)

The dimensions we used aren't totally comprehensive. There are many aspects of human behavior that they don't encapsulate. Fortunately there is quite a bit of past work to build on - there have been many past attempts to inventory a value spectrums that defines and distinguishs cultures. The paper [A Proposal for Clustering the Dimensions of National Culture](https://www.researchgate.net/profile/W_MARTIN_Jong/publication/262413029_A_Proposal_for_Clustering_the_Dimensions_of_National_Culture/links/5552b0fc08ae6fd2d81d5e61.pdf) (Maleki, A., de Jong, M, 2014) neatly catalogues these previous efforts and proposes their own measurements as well.

The authors propose the following cultural dimensions:

- individualism vs collectivism
- power distance: "the extent to which hierarchical relations and position-related roles are accepted"
- uncertainty avoidance: "to what extent people feel uncomfortable with certain, unknown, or unstructured situations"
- mastery vs harmony: "competitiveness, achievement, and self-assertion versus consensus, equity, and harmony"
- traditionalism vs secularism: "religiosity, self-stability, feelings of pride and, consistency between emotion felt and their expression vs secular orientation and flexibility"
- indulgence vs restraint: "the extent to which gratification of desires and feelings is free or restrained"
- assertiveness vs tenderness: "being assertive and aggressive versus kind and tender in social relationships"
- gender egalitarianism
- collaborativeness: "the spirit of 'team-work'"

We can (imprecisely) map the dimensions we used in HOSNY to these:

- greed vs altruism -> individualism vs collectivism and collaborativeness
- lavishness vs frugality -> indulgence vs restraint
- long-sightedness vs short-sightedness -> indulgence vs restraint
- introversion vs extroversion -> assertiveness vs tenderness (?)

It doesn't feel very exact though.

All of the previously defined dimensions are worth a look too:

[![](/assets/uploads/cultural_dimensions_01.png)](/assets/uploads/cultural_dimensions_01.png)
[![](/assets/uploads/cultural_dimensions_02.png)](/assets/uploads/cultural_dimensions_02.png)
[![](/assets/uploads/cultural_dimensions_03.png)](/assets/uploads/cultural_dimensions_03.png)
[![](/assets/uploads/cultural_dimensions_04.png)](/assets/uploads/cultural_dimensions_04.png)
[![](/assets/uploads/cultural_dimensions_05.png)](/assets/uploads/cultural_dimensions_05.png)
[![](/assets/uploads/cultural_dimensions_06.png)](/assets/uploads/cultural_dimensions_06.png)
[![](/assets/uploads/cultural_dimensions_07.png)](/assets/uploads/cultural_dimensions_07.png)

---

_republished from [space & times](http://spaceandtim.es/)_
