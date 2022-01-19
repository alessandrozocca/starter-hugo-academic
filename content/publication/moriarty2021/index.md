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

title = "A Metropolis-class sampler for targets with non-convex support"
date = "2021-09-15"
authors = ["J. Moriarty","J. Vogrinc ","admin"]
publication_types = ["2"]
publication =  "J. Moriarty, J. Vogrinc, A. Zocca. (2019) A Metropolis-class sampler for targets with non-convex support. _Statistics and Computing_ 31, 72."
publication_short = "_Statistics and Computing_"
year = 2021
image_preview = true
selected = true
projects = ["MCMC","rare events"]
math = true
highlight = true
abstract= "We aim to improve upon the exploration of the general-purpose random walk Metropolis algorithm when the target has non-convex support ${A \\subset \\mathbb{R}^d},$ by reusing proposals in ${A^c}$ which would otherwise be rejected. The algorithm is Metropolis-class and under standard conditions the chain satisfies a strong law of large numbers and central limit theorem. Theoretical and numerical evidence of improved performance relative to random walk Metropolis are provided. Issues of implementation are discussed and numerical examples, including applications to global optimisation and rare event sampling, are presented."
summary = "How to efficiently sample from target densities with non-convex support? Introducing the Skipping Sampler"

[image]
  caption = "Skipping sampler (in blue) vs. Metropolis RW sampler (in red) for the same conditional density with disconnected support"
  placement = ["1"]
  focal_point = "smart"
  preview_only = false

[[links]]
  name = "arXiv preprint"
  icon_pack = "ai"
  icon = "arxiv"
  url = "https://arxiv.org/abs/1905.09964"

[[links]]
  name = "PDF"
  icon_pack = "ai"
  icon = "open-access"
  url = "papers/moriarty2021.pdf"

[[links]]
  name = "DOI"
  icon_pack = "ai"
  icon = "doi"
  url = "https://doi.org/10.1007/s11222-021-10044-4"

[[links]]
  name = "bib"
  icon_pack = "ai"
  icon = "semantic-scholar"
  url = "papers/moriarty2021.bib"

+++
