---
title: "Multi Agent Construction"
excerpt: "<br/><img src='/images/multi_agent_construction/expert_planner.gif' height = '200' width='200'>"
collection: portfolio
---

<img src="/images/multi_agent_construction/expert_planner.gif">

* Developed an expert planner with help of multi-agent path planning algorithm, M* and A*
* The planner was constructed with respect to the constraints of the environment. A level wise approach was adopted to address the constraints.
* We then tried to do learn multi-agent policies by trying to imitate the expert planner.
* We performed experiments to train policies of agents by imitating the expert planner.
* Our experiments failed, the agents were not able to learn by imitation. On further analysis, we figured out that there was a problem with with the way in which we were performing imitation learning. The agents were not able to assign proper credit to their actions.
