
## Parallel - Foundations 9

### Elisa Omodei - Centrality in Interconnected multilayer networks

centrality ? : epidemics, info prop, transportation nws.

multilayer nws : urban public transport nw.
social nws : [Kleinenberg, Boguna, Sci Rep 2015]

rethink centrality in multilayer ?

math formulation : tensor representation. [De Domenico et al, Phys Rev X 2013]
rank 4 tensors

Monoplex pagerank -> generalized as steady state of eq p_{\beta\delta} = R p_{\alpha \gamma}
multilayer PageRank vector

[De Domenico, Sole-Ribalta, Omodei, .., Nature communications]

projection of tensor as supra-adjacency nw.

≠ from averaging on separate layers.

Applications :
[Omodei et al. network sci 2016] (known)
interdisciplinarity

ex Nobel price Chemistry 2014
grants erc etc

layers = disciplines.
author at the interface is more central.
case studies : aps journals (pacs code)
us patents (nber)
-> us patents topical interdisciplinarity **TODO : apply this centrality on patents ? !!!**
citation interdisciplinarity : entropy measure : H(p) = - \sum f_i log f_i ; f_i proportion of incident edges coming from layer i.



2nd application:
diffusion of microfinance. Banerjee et al. Science 2013. : data and different centrality measures.
trust : medical help and money


(....?/elisaomodei)



### A Carro - Network effects in noisy voter model

(stylized facts)
trading abm -> add nw -> can infer nw structure

indicators : transition ? \sigma^2 ; rho ; ?

analytics :
master eq for first and second order cross-moments.
nw approx : annealed approx for uncorrelated nws : fully connected, with weight proba being connected.
closed formula / approx for sigma^2

test ≠ nws with various degree of heterogeneity in degree distrib.

critical point moves for ≠ nws.

order param rho = num links in ≠ states / number of links

network approx : fails approx.

highly dependant on topology.

temporal autocorr -> correction term due to topology.

cl (...)

[Carro, Toral, San Miguel, Sci Reports 2016]

Q : second order approx ?
-> other approx better for variance (less for corrs)


### - Mathematical Definition of CS

importance of feedback loops
ex climate change : which models ?
seem to be ok models, accurate at short scales. open questions at longer time scales.

dynamical behavior.

Navier-stokes eq.
very high dimensional.

which feedback loop ?

bifurcation theory / cusp catastrophe.

hysteresis ?

locally only, linked to linearization of the system.

connexion betweeen different type of modeling.

ABM : regime shifts etc.
abm are necessary : classical eco : equilibrium etc
easier to integrate feedback loops.

Interaction graph.

Thomas's first conjecture.

Th : if a system has no positive cycles in G_int(x) for any x, it cannot exhibit multi-stationarity.

Def system ; modularity.
dissect the system ? == decompose system; dissection or modularity of nonlinear system ?

Hopf bifurcation.

current graphs of Selkov model.

internal structure in terms of feedback loops is essential.
need for a sci for feedback mechanisms.

**TODO check modularity etc in more details !**


### - comparing distributions

fitting power law : log-log plot : Cosma Shalizi : good idea for 1890's !

generic way to test and fit power laws ?

Clauset-Shalizi-Newman method

: \hat{\lapha} = ...

Kolmogorov-Smirnov distance as criteria -> bootstrapping on (x_min, alpha)
-> p-value.

pb to compare distribs ?

Finite size effect ? NO, truncation error ?

fit : integrate on [x_min,x_max]
-> Beta_adj

How to generate random exponential distribs ?
-> inverse CDF transform
?

cl :
- eye good gauge but not enough.
- Clauset-Shalizi-Newman : GOLD standard for power laws.
- ?

(no Q, waiting !)

-----------------
