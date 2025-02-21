---
title: Learning, Modeling, and Robotics
description: Bridging the gap between robotics and artificial intelligence
subtype: learning and modeling
permalink: subteam/learning-modeling-robotics.html
image:
    feature: research/npm/poking.jpg
    size: 60%
excerpt_separator: <!-- More -->
---

Our goal is to catalyze tangible and substantial improvements in robot capabilities, especially in human–robot scenarios, with research at the confluence of learning, modeling, and robotics.
We accomplish this from two perspectives:

 * In the first, we leverage recent advances in learning and modeling to develop sophisticated, accessible, and generalizable robot technologies.
 Our focus here is primarily directed toward robots that operate in human environments. The ability of robots to interact or even cooperate with humans are considerations that are often neglected in the learning and modeling communities.
 * Complementarily, we draw upon our expertise in robotics and human–robot interaction to inform foundational research in artificial intelligence---particularly in natural language processing and reinforcement learning.
 Our experience with real-world robotic systems allows us to underpin our research with strong empirical motivations, an approach that is conspicuously scant in much of the existing literature.

<!-- More -->

# Contents
{:.no_toc}

* This line will be replaced by the ToC, excluding the "Contents" header
{:toc}

# 1. Projects

## 1.1. Non-Prehensile Manipulation

**Students:** [Anuj Pasricha]({% post_url people/2019-10-13-anuj %}), Yi-Shiuan Tung

**_Publications:_**
 - A. Pasricha, Y. Tung, B. Hayes, and A. Roncone, _"PokeRRT: Poking as a skill and failure recovery tactic for planar non-prehensile manipulation"_, 2021. Under review.

Non-prehensile manipulation (i.e., manipulation that does not involve grasping) can significantly expand the operational space of a robot.
We posit that robots need to leverage non-prehensile manipulation as part of their skill set if they are to achieve human-level dexterity.
Our past work introduced a novel planner that uses poking as a skill _and_ failure recovery tactic synergistically with grasping.
Moving forward, we are building hybrid models for manipulation in which physics-based and learning-based approaches complement each other, toward generating a repository of skills that robots can then use to engage in more complex, affordance-informed task planning and manipulation.

<!-- {% include image.html url="research/npm/poking.jpg" max-width="40%" description="Expanding operational space by leveraging non-prehensile manipulation." %} -->

<div class="row">
    {% include post-sorter.html subtype="non-prehensile manipulation" %}
</div>

## 1.2. Natural Language Grounding and Skill Transfer

**Students:** Stéphane Aroca-Ouellette  
  
**_Publications:_**  
 - S. Aroca-Ouellette, C. Paik, A. Roncone, and K. Kann, _"PROST: Physical Reasoning of Objects through Space and Time"_, 2021. In Findings of the Association for Computational Linguistics: ACL-IJCNLP2021, [[PDF]]({{ site.url }}/papers/2021_Aroca-Ouellette_ACL_findings.pdf) [[BIB]]({{ site.url }}/papers/2021_Aroca-Ouellette_ACL_findings.bib)

Natural language is the easiest and most generalizable way for humans to specify a task, provide new information, and convey intentions. Being able to leverage language for task specification and skill transfer would greatly increase the abilities of current robots.
Concurrently, current language models fail to understand language as humans do, which we hypothesize is caused a lack of real-world experience.
To this end, we aim at bridging the gap between the field of robotics and NLP to produce robots that can act and learn through language, and who in turn will generate experiences for it develop a richer understanding of language.

<div class="row">
    {% include post-sorter.html subtype="grounding_language_through_experience" %}
</div>


## 1.3. Multi-Agent Reinforcement Learning

**Students:** Guohui Ding, [Joewie J. Koh](https://joewiekoh.com)

**_Publications:_**
 - J. J. Koh*, G. Ding*, C. Heckman, L. Chen, A. Roncone, "Cooperative control of mobile robots with Stackelberg learning," in _2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)_, 2020. [[PDF]]({{ site.url }}/papers/2020_Koh_IROS_SLiCC.pdf) [[BIB]]({{ site.url }}/papers/2020_Koh_IROS_SLiCC.bib)
 - G. Ding*, J. J. Koh*, K. Merckaert, B. Vanderborght, M. M. Nicotra, C. Heckman, A. Roncone, L. Chen, "Distributed reinforcement learning for cooperative multi-robot object manipulation," in _19th International Conference on Autonomous Agents and Multiagent Systems (AAMAS)_, 2020. [[PDF]]({{ site.url }}/papers/2020_Ding_AAMAS_cooperative_object_manipulation.pdf) [[BIB]]({{ site.url }}/papers/2020_Ding_AAMAS_cooperative_object_manipulation.bib)

Reinforcement learning (RL), which allows an agent to learn from interactions with its environment, presents an increasingly promising alternative to traditional model-based control.
However, much of the work applying RL to robotics has been in the single-agent paradigm—despite the pervasiveness of multi-agent robotic systems in the real world.
We are most interested in developing algorithms for controlling heterogeneous teams that cooperate to accomplish common goals, with the aim of enabling multi-robot systems to be imbued with capabilities that are more than the sum of their parts.
Moreover, we envision multi-agent systems serving as the setting for the next wave of progress in RL research, and are further driven by the belief that multi-agent RL can provide a theoretical basis for understanding the application of RL in human–robot contexts.

{% include image.html url="research/marl/SLiCC.png" max-width="40%" description="Learning to cooperate with asymmetric perceptual capabilities." %}

## 1.4. Learning Discourse Policies for Dialog Management

**Students:** [Joewie J. Koh](https://joewiekoh.com), [Kaleb Bishop](https://kalebishop.github.io/)

The [NSF National AI Institute for Student-AI Teaming (iSAT)](https://www.colorado.edu/research/ai-institute/) is a multi-site interdisciplinary institute with the vision of developing artificial intelligence as a social, collaborative partner that helps both students and teachers make learning more effective, engaging, and equitable.
As a part of this institute, we conduct foundational research on dialog management for AI-based conversation participation and facilitation.
Specifically, we are studying how reinforcement learning might be applied to autonomously generate and fine-tune discourse policies.

{% include image.html url="research/isat.jpg" description="iSAT's vision for student-AI teaming and classroom orchestration." %}
