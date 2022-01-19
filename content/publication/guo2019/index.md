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

title = "Less is More: Real-time Failure Localization in Power Systems"
date = "2019-12-13"
authors = ["L. Guo","C. Liang","admin","S.H. Low","A. Wierman"]
publication_types = ["1"]
publication =  "L. Guo, C. Liang, A. Zocca, S.H. Low, A. Wierman. (2019) Less is More: Real-time Failure Localization in Power Systems. In _2019 IEEE 58th Conference on Decision and Control (CDC)_,  Nice, France, 2019, pp. 3871-3877."
publication_short = "_2019 Conference on Decision and Control (CDC)_"
year = 2019
image_preview = true
selected = true
projects = ["algorithms for power systems"]
math = true
highlight = true
abstract= "Cascading failures in power systems exhibit nonlocal propagation patterns, which make the analysis and mitigation of failures difficult. In this work, we propose a distributed control framework inspired by the recently proposed concepts of unified controller and network tree-partition that offers strong guarantees in both the mitigation and localization of cascading failures in power systems. In this framework, the transmission network is partitioned into several control areas which are connected in a tree structure, and the unified controller is adopted by generators or controllable loads for fast timescale disturbance response. After an initial failure, the proposed strategy always prevents successive failures from happening, and regulates the system to the desired steady state where the impact of initial failures are localized as much as possible. For extreme failures that cannot be localized, the proposed framework has a configurable design, that progressively involves and coordinates more control areas for failure mitigation and, as a last resort, imposes minimal load shedding. We compare the proposed control framework with Automatic Generation Control (AGC) on the IEEE 118-bus test system. Simulation results show that our novel framework greatly improves the system robustness in terms of the ${N − 1}$ security standard, and localizes the impact of initial failures in majority of the load profiles that are examined. Moreover, the proposed framework incurs significantly less load loss, if any, compared to AGC."
summary = "A distributed control strategy operating on the frequency regulation timescale with provable failure mitigation properties and localization guarantees"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.

[image]
  caption = "Number of vulnerable lines for AGC vs. UC"
  placement = ["1"]
  focal_point = "smart"
  preview_only = false

[[links]]
  name = "arXiv preprint"
  icon_pack = "ai"
  icon = "arxiv"
  url = "https://arxiv.org/abs/1904.05461"
[[links]]
  name = "PDF"
  icon_pack = "ai"
  icon = "open-access"
  url = "papers/guo2019.pdf"
[[links]]
  name = "DOI"
  icon_pack = "ai"
  icon = "doi"
  url = "https://doi.org/10.1109/CDC40024.2019.9029393"
[[links]]
  name = "bib"
  icon_pack = "ai"
  icon = "semantic-scholar"
  url = "papers/guo2019.bib"

+++
