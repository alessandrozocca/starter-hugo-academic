+++
# Pub_type key
# 0 -> 'Uncategorized',
# 1 -> 'Conference Proceedings',
# 2 -> 'Journal article',
# 3 -> 'Preprint',
# 4 -> 'Report',
# 5 -> 'Book'
# 6 -> 'Book section'
# 7 -> 'Thesis'
# 8 -> 'Patent'

title = "Adaptive Network Response to Line Failures in Power Systems"
date = "2022-03-10"
authors = ["L. Guo","L. Chen","admin","S.H. Low","A. Wierman"]
publication_types = ["2"]
publication =  "L. Guo, L. Chen, A. Zocca, S.H. Low, A. Wierman. (2022) Adaptive Network Response to Line Failures in Power Systems. _Submitted to IEEE Transactions on Control of Network Systems_."
publication_short = "_Submitted to IEEE Transactions on Control of Network Systems_"
image_preview = ""
year = 2022
selected = true
projects = ["algorithms for power systems", "learning in power systems"]
math = true
highlight = true
abstract= "Transmission line failures in power systems propagate and cascade non-locally. In this work, we propose an adaptive control strategy that offers strong guarantees in both the mitigation and localization of line failures. Specifically, we leverage the properties of network bridge-block decomposition and a frequency regulation method called the unified control. If the balancing areas over which the unified control operates coincide with the bridge-blocks of the network, the proposed strategy drives the post-contingency system to a steady state where the impact of initial line outages is localized within the areas where they occurred whenever possible, stopping the cascading process. When the initial line outages cannot be localized, the proposed control strategy provides a configurable design that progressively involves and coordinates more balancing areas. We compare the proposed control strategy with the classical Automatic Generation Control (AGC) on the IEEE 118-bus and 2736-bus test networks. Simulation results show that our strategy greatly improves overall reliability in terms of the ${N-k}$ security standard, and localizes the impact of initial failures in the majority of the simulated contingencies. Moreover, the proposed framework incurs significantly less load loss, if any, compared to AGC, in all our case studies."
summary = "How to synergize topology changes and control mechanisms in power grids?"

[image]
  caption = "Refined bridge-block decomposition with 3 areas for the IEEE 118-bus network"
  placement = ["1"]
  focal_point = "smart"
  preview_only = false

[[links]]
  name = "PDF"
  icon_pack = "ai"
  icon = "open-access"
  url = "papers/guo2022.pdf"

[[links]]
  name = "bib"
  icon_pack = "ai"
  icon = "semantic-scholar"
  url = "papers/guo2022.bib"

+++
