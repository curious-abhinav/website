+++
abstract="Spectral algorithms based on matrix representations of networks are often used to detect communities, but classic spectral methods based on the adjacency matrix and its variants fail in sparse networks. New spectral methods based on non-backtracking random walks have recently been introduced that successfully detect communities in many sparse networks. However, the spectrum of non-backtracking random walks ignores hanging trees in networks that can contain information about their community structure. We introduce the reluctant backtracking operators that explicitly account for hanging trees as they admit a small probability of returning to the immediately previous node, unlike the non-backtracking operators that forbid an immediate return. We show that the reluctant backtracking operators can detect communities in certain sparse networks where the non-backtracking operators cannot, while performing comparably on benchmark stochastic block model networks and real world networks. We also show that the spectrum of the reluctant backtracking operator approximately optimises the standard modularity function. Interestingly, for this family of non- and reluctant-backtracking operators the main determinant of performance on real-world networks is whether or not they are normalised to conserve probability at each node."
authors=["Abhinav Singh", "Mark Humphries"]
date="2015-03-06"
publication="Scientific Reports"
title=" Finding communities in sparse networks"
url_pdf="http://www.nature.com/articles/srep08828.pdf"
selected = true
+++