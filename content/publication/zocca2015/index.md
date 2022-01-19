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

title = "Spatio-temporal dynamics of random-access networks: An interacting particle approach (PhD thesis)"
date = "2015-12-17"
authors = ["admin"]
publication_types = ["7"]
publication =  "A. Zocca. (2015) Spatio-temporal dynamics of random-access networks: An interacting particle approach. _PhD thesis_, Technische Universiteit Eindhoven."
publication_short = "_PhD thesis_"
year = 2015
image_preview = true
selected = true
projects = ["wireless networks"]
math = true
highlight = true
abstract= "In this thesis we study mathematical models that capture the collective behavior of devices sharing a wireless medium in a distributed fashion by viewing them as repelling particles. Our research is motivated by fundamental challenges in wireless networks, which typically are very large and lack centralized control. Instead these networks vitally rely on a distributed mechanism for regulating the access of the various devices to the shared medium. Thanks to their low implementation complexity, randomized algorithms provide a popular mechanism for distributed medium-access control. The work in this thesis is particularly concerned with the so-called Carrier-Sense Multiple-Access (CSMA) protocol, various incarnations of which are implemented in IEEE 802.11 networks. Despite its simplicity on a local level, the macroscopic behavior of the CSMA protocol in large networks tends to be exceedingly complex, and critically depends on global spatial characteristics of the network in non-intuitive ways. We consider stylized stochastic models to understand how the spatial deployment of the various transmitter-receiver pairs affects the global performance of the network. Specifically, we model the random-access network as an interacting particle system on a graph, which captures the interplay of conflicting transmissions due to interference. The global evolution of such a particle system is described by a continuous-time Markov process, which exhibits fascinating connections with the hard-core interaction between gas particles studied in chemistry and statistical physics. Specific attention is paid to scenarios in which nodes become more aggressive in trying to activate, which is relevant for networks in high-load regimes, where one cannot afford to leave network resources unutilized. This scenario corresponds to the low-temperature regime for the corresponding interacting particle system. The most likely activity states for the network in this regime are those with a maximum number of active nodes, to which we refer as dominant states. Even in scenarios where all nodes have an equal opportunity to be active in the long run or in symmetric scenarios where spatial fairness is automatically ensured, transient yet significant starvation effects can arise due to the fact that the dominant states become extremely rigid, by which we mean that the transitions between dominant states can be extremely slow, causing starvation for the nodes not in the currently active dominant state."
summary = "How to use interacting particle systems to describe and predict the performance of wireless networks?"

[image]
  caption = "The cover of my PhD thesis, depicting the state space corresponding to a small random-access network"
  placement = ["1"]
  focal_point = "smart"
  preview_only = false

[[links]]
  name = "PDF"
  icon_pack = "ai"
  icon = "open-access"
  url = "papers/zocca2015.pdf"
[[links]]
  name = "TU/e repository"
  icon_pack = "ai"
  icon = "doi"
  url = "http://repository.tue.nl/801489"
[[links]]
  name = "bib"
  icon_pack = "ai"
  icon = "semantic-scholar"
  url = "papers/zocca2015.bib"

+++
