---
title: "Guided RRT Connect"
excerpt: "<img src='/images/guided_rrt_connect/visualiser.png' height = '200' width='200'>"
collection: projects
---

<img src="/images/guided_rrt_connect/visualiser.png">

* RRT Connect is a sampling based planning algorithm used for planning of multi-arm manipulators.
* Instead of naively choosing a tree to extend(switching between the trees), we propose a multi-armed bandit setting where the action space is selecting the tree to extend.
* The agent choosing the tree is given a higher reward if we don’t make significant progress(we want to expand it more) and given a lower reward if it makes significant progress.
* Tested two multi armed algorithms : Upper Confidence Bound and Dynamic Thompson Sampling.
* We were able to decrease the planning time of a simulated multi-arm manipulator by 30 percent by augmenting out tree switching mechanism.

[Technical Report](https://drive.google.com/file/d/1dL9yRUegyA_MQ0bju2H_RrLtYSXdYZES/view?usp=sharing "Technical Report")
[Presentation](https://drive.google.com/file/d/1vOuCVcyK-tOiROwCqBsHiSI9hkF7wXcc/view?usp=sharing "Presentation")
[Video](https://www.youtube.com/watch?v=PbfxSmOMLOU&feature=youtu.be "Video")

