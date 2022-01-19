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

title = "Failure Localization in Power Systems via Tree Partitions"
date = "2018-12-16"
authors = ["L. Guo","C. Liang","admin","S.H. Low","A. Wierman"]
publication_types = ["1"]
publication =  "L. Guo, C. Liang, A. Zocca, S.H. Low, A. Wierman. (2018) Failure Localization in Power Systems via Tree Partitions. In _2018 IEEE 57th Conference on Decision and Control (CDC)_,  Miami Beach, FL, 2018, pp. 6832-6839."
publication_short = "_2018 Conference on Decision and Control (CDC)_"
year = 2018
image_preview = true
selected = true
projects = ["algorithms for power systems"]
math = true
highlight = true
abstract= "Cascading failures in power systems propagate non-locally, making the control and mitigation of outages extremely hard. In this work, we use the emerging concept of the tree partition of transmission networks to provide an analytical characterization of line failure localizability in transmission systems. Our results rigorously establish the well perceived intuition in power community that failures cannot cross bridges, and reveal a finer-grained concept that encodes more precise information on failure propagations within tree-partition regions. Specifically, when a non-bridge line is tripped, the impact of this failure only propagates within well-defined components, which we refer to as cells, of the tree partition defined by the bridges. In contrast, when a bridge line is tripped, the impact of this failure propagates globally across the network, affecting the power flow on all remaining transmission lines. This characterization suggests that it is possible to improve the system robustness by temporarily switching off certain transmission lines, so as to create more, smaller components in the tree partition; thus spatially localizing line failures and making the grid less vulnerable to large-scale outages. We illustrate this approach using the IEEE 118-bus test system and demonstrate that switching off a negligible portion of transmission lines allows the impact of line failures to be significantly more localized without substantial changes in line congestion."
summary = "How do line failure propagate in power systems? Graph theory comes to rescue!"

[image]
  caption = "Influence graph of the IEEE 118-bus network after creating a tree partition with 2 areas"
  placement = ["1"]
  focal_point = "smart"
  preview_only = false

[[links]]
  name = "arXiv preprint"
  icon_pack = "ai"
  icon = "arxiv"
  url = "https://arxiv.org/abs/1803.08551"
[[links]]
  name = "PDF"
  icon_pack = "ai"
  icon = "open-access"
  url = "papers/guo2018.pdf"
[[links]]
  name = "DOI"
  icon_pack = "ai"
  icon = "doi"
  url = "https://doi.org/10.1109/CDC.2018.8619562"
[[links]]
  name = "bib"
  icon_pack = "ai"
  icon = "semantic-scholar"
  url = "papers/guo2018.bib"

+++
