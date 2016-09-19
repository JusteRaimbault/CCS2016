
## Parallel session Urban 2

### L Alessandretti - multiscalar human mobility

*lauraalessandretti.weebly.com*

distribution of waiting times / jumps -> predictive models of human mobility.
epidemics, transportation design.

Data sources :
  * mobile phone. bad spatial resolution.
  * social network locations. pb : people check in themselves.
  * gps in cars or taxis : limited to that mode.

very broad range for \Delta r
Powerlaw [Gonzalez, Hidalgo, barabasi, 2008] : consistent on large distance.
short distances : exponential ; or others. poisson, etc.

cause for heterogeneity ? unenven sampling, heterogeneous dtaasets.

New dataset : COpenhaguen Nw study. very precise sampling, resolutino and transportation modes.

Multimodeling with AIC weights -> log-normal fit.
Large scale : power law better.
 -- Q : what does "fit" mean here ?

 also at individual level.

 distribution of waiting times also lognormal.

 Typical scales appear.

 also for exploration behavior : first time places.

 cl : lognormal form mulitplicative processes

Q : displacement threshold ?

Q : behavioral model ?

Q (Lenormand) : oversampling possible ? result consistent with changing the threshold.


## Femke Bekius - Exemplifying Railway decision-making

Dutch railway system. socio-technical system.

3 actors at ÷ levels : Prorail tracks owners, NS train service company, governement provides budget and contracts.

Game theory to explain decision making ?

Two level games : strategy level / operational level.

outcome as a decision at a given level.

Win-set : outcome of strategic level they say would win.

next steps : check possible winsets / compare with Putnam hypotheses.

cl :
 - applying game : formalization, capture richness of process.
 - reflection : change in the system.

 Q : methodological framework or real cases ?

 Q : more levels ? why not ; here decisino taken together

 Q Gerhenson : improvment measurements ? well implemened or not ? pb of contradictory objective.


## Lenormand - Modeling individual human mobility patterns by travel purposes

try to explain/reproduce trajectories.
back to [Brockman 2006 Nature, scaling laws of human travels] : conitnuous random walk.

Song : limit of predictibility.

Importance of trip destination ? -> credit card data.

Stratification by spending cost ; collapse into same distrib when normalized by median.

ex calibrated parameters : proba stopping search.

cl :
 * importance of trip destination.
 * test against other type of data ?
 * analytical solution ?

Q : centroid/exact posiiton ?

[Q : for large expenses, reasonable to have a random search model ? why not DC choice between known set of alternatives ?]



## Influencing driving beahvior with recurrent neural nw

long short-term memory neural network.
cntk by microsoft, implemented on GPU.

aim : follow driver, prediction of switch proba.


## Backward exploration of delay propagation in flight networks

high cost of delays. // increase in demand.

Q : how is delay propagated ?

simulations : flight-level impact -> delay a single flight and look at propagation : "dangerousness" of a flight.
 -> measures to avoid.

 DATA : flightradar24.

 returning flights / returning delays.

 Q : level of congestion of airport.


## Cycling safety

ABM to discriminate between behaviroal adaptation / separated cyclig infra.

[Jacobsen, 2003] drivers adapt to cyclist quantity.
-> increasing exposure

VS infrastructure : decreasing infrastructure.

ABM based on [Thompson et al. 2015]

beavioral adaptation : classical conditioning.

Results.

consistent with behavioral studies : [Shenjun and Loo, 2016] HongKong

[@simulated_jase]

Q : e-bikes : cycling faster ?

Q (...)
other paper ? (NFT ???)
