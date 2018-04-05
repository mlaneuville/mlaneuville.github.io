---
layout: post
title: AGU &middot Exploring the exoplanet catalogue with neural nets
type: talk
---

Over the last months we developped several ways to explore the exoplanet 
catalogue using neural networks. In the 'Rise of Machine Learning' session, I 
presented part of our work: how low dimensional embedding helped us see 
structure in planetary distribution, and a new method to predict planetary mass 
with higher accuracy. This is another output from the Planetary Diversity 
workshop held at ELSI a year before. Abstract below.



Laneuville, Tasker and Guttenberg.

The launch of Kepler in 2009 brought the number of known exoplanets into the
thousands, in a growth explosion that shows no sign of abating. While the data
available for individual planets is presently typically restricted to orbital
and bulk properties, the quantity of data points allows the potential for
meaningful statistical analysis.

It is not clear how planet mass, radius, orbital path, stellar properties and
neighbouring planets influence one another, therefore it seems inevitable that
patterns will be missed simply due to the difficulty of including so many
dimensions. Even simple trends may be overlooked if they fall outside our
expectation of planet formation; a strong risk in a field where new discoveries
have destroyed theories from the first observations of hot Jupiters.

A possible way forward is to take advantage of the capabilities of neural
network autoencoders. The idea of such algorithms is to learn a representation
(encoding) of the data in a lower dimension space, without a priori knowledge
about links between the elements. This encoding space can then be used to
discover the strongest correlations in the original dataset.

The key point is that trends identified by a neural network are independent of
any previous analysis and pre-conceived ideas about physical processes. Results
can reveal new relationships between planet properties and verify existing
trends.

We applied this concept to study data from the NASA Exoplanet Archive and while
we have begun to explore the potential use of neural networks for exoplanet
data, there are many possible extensions. For example, the network can produce a
large number of 'alternative planets' whose statistics should match the current
distribution. This larger dataset could highlight gaps in the parameter space or
indicate observations are missing particular regimes. This could guide
instrument proposals towards objects liable to yield the most information.
