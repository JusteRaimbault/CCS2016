
## Parallel - Urban 3

### S Sinha - Complex Dynamics of Urban Traffic Congestion - Kinetic Monte Carlo

physicists coming to field and rediscovering.
fundamental diagram of traffic -> Greenshields, 1935
Lighthill, Whitnam
[Nagel Schreckenberg 1992] ca model traffic
formation and waves in space and time.

what about Urban Traffic ? high density, many intersections

empirical analysis <-> theoretical modeling : robust models.

"macro-patterns" : city wide.

two ways to have traffic data : sensor ; probe vehicles (followed by GPS)

-> time series of waiting time.

similar patterns accross cities.
spatio-temporal visualization.
congestion hot spots.

waiting time distrib : power law.

micro-model : micro traffic simulation.
stochastic distrib of headways

Kinetic Monte Carlo.
reproduces stylized facts.
reproduces power law.

Q : spatial explicit ? : already

Q : why India explicit ?


### Pres

**Q : cross validation ?**

### Charlotte - individual-based stochastic model

rem Zipf law.

cities : alpha=1
applies to cities, counties, states.

birth-death model : dn/dt = (b-d)n + sqrt((b+d)n)dW
no city disparition.

gibrat formulation : dn/dt = (g-1)n + sqrt(sigma^2 n^2)dW

Basic Model : n(t+1)=\sum poisson
decorrelation of birth and death : lamdba_i=lambda => n_t+1 = poisson(n lambda)
=> SDE formulation

simulation : not zipf law.

if correlated : n_{t+1} = poisson(n lambda) + n kappa_t
-> stationary distrib P(n) = 1/(an + b n^2)

better fit.

an : variability of individual
bn^2 : variability due to interactions with others.

transition when n = a/b

Alternative models : lambda_t ; groups of individuals.

Q : poisson structure : check that against data ?

Q : addition of kappa : what meaning ?

Q : change of slopes in time ?

Q : ergodicity ? probably not.


### M Convertino - Information theoretical Global Epidemic Prediction Model

diseasome : connexion of diseases

coupling many modules.

ex River network : coupling of three models
[Convertino and Huang, 2016]

prediction : short term forecast. real-time info ?

Q : link with decision-making ? decision theory


### M Convertino - integrating ecosystem and stakeholder dynamics

?
