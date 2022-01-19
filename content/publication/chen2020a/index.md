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

title = "An Integrated Approach for Failure Mitigation & Localization in Power Systems"
date = "2021-02-02"
authors = ["L. Chen","L. Guo","admin","S. Yu","S.H. Low","A. Wierman"]
publication_types = ["2"]
publication = "L. Chen, L. Guo, A. Zocca, S. Yu, S.H. Low, A. Wierman. (2020) An Integrated Approach for Failure Mitigation and Localization in Power Systems. In _Electric Power Systems Research_, Vol. 190, 106613."
publication_short = "_Electric Power Systems Research_"
year = "2021"
selected = true
projects = ["algorithms for power systems"]
math = true
highlight = true
abstract= "The transmission grid is often comprised of several control areas that are connected by multiple tie lines in a mesh structure for reliability. It is also well-known that line failures can propagate non-locally and redundancy can exacerbate cascading. In this paper, we propose an integrated approach to grid reliability that (i) judiciously switches off a small number of tie lines so that the control areas are connected in a tree structure; and (ii) leverages a unified frequency control paradigm to provide congestion management in real time. Even though the proposed topology reduces redundancy, the integration of tree structure at regional level and real-time congestion management can provide stronger guarantees on failure localization and mitigation. We illustrate our approach on the IEEE 39-bus network and evaluate its performance on the IEEE 118-bus, 179-bus, 200-bus and 240-bus networks with various network congestion conditions. Simulations show that, compared with the traditional approach, our approach not only prevents load shedding in more failure scenarios, but also incurs smaller amounts of load loss in scenarios where load shedding is inevitable. Moreover, generators under our approach adjust their operations more actively and efficiently in a local manner."
summary = "How to combine fast-scale frequency control with line switching to make power networks more robust?"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.

[image]
  caption = "IEEE 39-bus network with a 2-area tree partition leveraged by the UC control"
  placement = ["1"]
  focal_point = "smart"
  preview_only = false

[[links]]
  name = "arXiv preprint"
  icon_pack = "ai"
  icon = "arxiv"
  url = "https://arxiv.org/abs/2004.10401"

[[links]]
  name = "PDF"
  icon_pack = "ai"
  icon = "open-access"
  url = "papers/chen2020a.pdf"

[[links]]
  name = "DOI"
  icon_pack = "ai"
  icon = "doi"
  url = "https://doi.org/10.1016/j.epsr.2020.106613"

[[links]]
  name = "bib"
  icon_pack = "ai"
  icon = "semantic-scholar"
  url = "papers/chen2020a.bib"
+++
