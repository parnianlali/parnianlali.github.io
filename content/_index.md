+++

title = "Parnian Lali"
description = "Official personal website of Parnian Lali, AI Researcher and Professional Violinist"

[extra]
profile_picture = "/assets/images/profilee2.jpg"
name = "Parnian La'li"
subtitle = "Student and Professional Violinist "
about_me = """



**Bio**

I’m a student and researcher working at the intersection of artificial intelligence and other interdisciplinary fields. I’m currently pursuing an M.Sc. and have completed a bachelor in physics with a minor in Electrical Engineering. I’m particularly interested in problems where ideas from different fields come together to provide new ways of understanding complex systems.

Outside of academia, I’m a professional violinist and a member of a classical symphony orchestra, where I perform Classical music greats. Music has always been an important part of my life, and I enjoy the combination of individual practice and collaboration that playing in an orchestra brings.

In my free time, I enjoy being in nature, hiking, and climbing mountains.

If you’d like to know more, have any questions, or just want to say hi, feel free to reach out ;)
"""
###########
# SOCIALS #
###########

[[extra.socials]]
name = "github"
icon = "/assets/icons/github.svg"
label = "Github"
link = "https://github.com/parnianlali"
[[extra.socials]]
name = "Linkedin"
icon = "/assets/icons/linkedin (1).svg"
label = "Linkedin"
link = "https://www.linkedin.com/in/parnianlali"
[[extra.socials]]
name = "letterboxd"
icon = "/assets/icons/letterboxd.svg"
label = "Letterboxd"
link = "https://letterboxd.com/parnianlali"
[[extra.socials]]
name = "instagram"
icon = "/assets/icons/instagram.svg"
label = "instagram"
link = "https://www.instagram.com/parnianlali/"
[[extra.socials]]
name = "mail"
icon = "/assets/icons/mail.svg"
label = "mail"
link = "parnian.lalii@gmail.com"
[[extra.socials]]
name = "kaggle"
icon = "/assets/icons/kaa.svg"
label = "kaggle"
link = "https://www.kaggle.com/parnianlali"
[[extra.socials]]
name = "goodreads"
icon = "/assets/icons/goodreads.svg"
label = "goodreads"
link = "https://www.goodreads.com/user/show/195546310-parnian-la-li"


############
# TOP PROJECTS #
############






[[extra.timeline]]
title = "Bachlor's thesis: machine learning in wearable sensors"
description = "Personal website of Parnian Lali"
subtitle = "Supervisor: Dr. Peyman sahebsara"
date = ""
icon = "/assets/icons/python.svg"
background = "#5d1467"
foreground = "#fff"
content = """
In this project, I explored wearable technologies and various types of sensors, with a special focus on fiber optic sensors, which have emerged as a powerful force in the wearable tech field. I then outlined the fundamental concepts and steps for implementing machine learning in wearable sensors, reviewed existing research in this area, and proposed solutions to address the challenges encountered.
[View pdf](/assets/file/lali.pdf)
"""

[[extra.timeline]]
title = "Auditing Credit Assignment in Cooperative Multi-Agent RL (Independent Research)"
subtitle = "With initial guidance from Dr. Farhad Fazileh"
date = ""
icon = "/assets/icons/artificial_neural_network_icon_large.svg"
background = "#5d1467"
foreground = "#fff"
content = """
This project asks whether credit assignment methods in cooperative multi-agent reinforcement learning actually assign correct credit, rather than just achieving high task return. In small cooperative games, ground-truth credit can be computed exactly by enumerating all coalitions and joint actions. I use this to audit value-decomposition methods (VDN, QMIX) and Shapley-based credit against exact Shapley, Banzhaf and leave-one-out values, across a controlled synergy parameter that interpolates between additive and strongly non-additive team rewards. A central question is whether the choice of counterfactual baseline (what agents outside a coalition are assumed to do) changes the resulting credit more than the choice of solution concept. The project is still ongoing.
"""

[[extra.timeline]]
title = "Master's thesis: Deep Reinforcement Learning for Navigation of Active Brownian Microrobots"
subtitle = "Supervisor: Dr. Ehsan Noruzifar"
date = ""
icon = "/assets/icons/researchs.svg"
background = "#5d1467"
foreground = "#fff"
content = """
This project studies navigation under stochastic noise, using classical controllers (PID and Proportional Navigation) as baselines and deep reinforcement learning (RL) as the main approach. The agents are microscale active Brownian particles in a 2D periodic arena, where thermal noise perturbs both position and heading, and the Péclet number sets how strongly noise competes with propulsion. I built a custom Gymnasium environment for this stochastic setting and tuned both controllers across noise regimes. PID holds up as noise grows, while proportional navigation breaks down at high noise because the line-of-sight rate is buried in stochastic fluctuations. I am now training a single noise-conditioned RL policy (PPO and SAC) that adapts to the noise level, aiming to outperform the classical controllers in the high-noise regime.
"""

+++
