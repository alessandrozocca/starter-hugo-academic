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

title = "A Spectral Representation of Power Systems with Applications to Adaptive Grid Partitioning and Cascading Failure Localization"
date = "2021-05-01"
authors = ["admin","L. Chen","L. Guo","S.H. Low","A. Wierman"]
publication_types = ["3"]
publication = "A. Zocca, L. Chen, L. Guo, S.H. Low, A. Wierman. (2021) A Spectral Representation of Power Systems with Applications to Adaptive Grid Partitioning and Cascading Failure Localization. _Submitted_."
publication_short = "_Submitted_"
year = 2021
selected = true
projects = ["algorithms for power systems", "learning in power systems"]
math = true
highlight = true
abstract= "Transmission line failures in power systems propagate and cascade non-locally. This well-known yet counter-intuitive feature makes it even more challenging to optimally and reliably operate these complex networks. In this work we present a comprehensive framework based on spectral graph theory that fully and rigorously captures how multiple simultaneous line failures propagate, distinguishing between non-cut and cut set outages. Using this spectral representation of power systems, we identify the crucial graph sub-structure that ensures line failure localization – the network bridge-block decomposition. Leveraging this theory, we propose an adaptive network topology reconfiguration paradigm that uses a two-stage algorithm where the first stage aims to identify optimal clusters using the notion of network modularity and the second stage refines the clusters by means of optimal line switching actions. Our proposed methodology is illustrated using extensive numerical examples on standard IEEE networks and we discussed several extensions and variants of the proposed algorithm."
summary = "How to use spectral graph theory to improve power networks robustness against cascading failures?"

[image]
  caption = "The IEEE 118-bus network after the optimal switching actions, with its bridge-block decomposition and relative influence graph"
  placement = ["1"]
  focal_point = "smart"
  preview_only = false

[[links]]
  name = "arXiv preprint"
  icon_pack = "ai"
  icon = "arxiv"
  url = "https://arxiv.org/abs/2105.05234"

[[links]]
  name = "PDF"
  icon_pack = "ai"
  icon = "open-access"
  url = "papers/zocca2021b.pdf"

[[links]]
  name = "bib"
  icon_pack = "ai"
  icon = "semantic-scholar"
  url = "papers/zocca2021b.bib"
+++
