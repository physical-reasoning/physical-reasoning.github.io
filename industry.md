---
layout: page
title: Industry Panel
permalink: /industry/
---

<figure>
	<div style="text-align:center;max-width:700px;width=100%;align:center">
        <a href="https://slideslive.com/38974994/industry-panel"
           alt="industry panel slide" target="_blank">
		<img src="../assets/img/industry.jpg" alt="Industry Panel Summary" />
        </a>
	</div>
</figure>


<h2>A List of Practical Recommendations</h2>

The list below summarizes the insights from our industry panel.
We hope that it can help making academic research applicable to real-world challenges.

### A. Tackle complex environments

#### A.1 Train safely and inclusively

A view from Aleksandra Faust: Construct simulation environments where a robot
can navigate and populate this environment with realistic objects and basic 
models of humans; train in simulation to avoid safety and privacy concerns; 
add active (programmable) models of humans into the environments to 
make this training relevant to realistic scenarios.

#### A.2 Support cross-disciplinary research to handle realistic scenarios

A view from Kenneth Tran: ML benefited from benchmarks initially, but the 
progress can be slowed down by benchmarks as well; if there is not enough 
emphasis on the interdisciplinary research, the focus can move away from 
research directions that can handle realistic data.


### B. Bring in rich data

#### B.1 Wellcome and emphasize industrial datasets and benchmarks 

There is a need for benchmarks that present a holistic picture of the data/task,
as opposed to the narrow  benchmarks that cause over-tuning and myopic focus.
A view from Aleksandra Faust:
It's not an easy problem - there are challenges for sharing the data, 
e.g privacy issues, liability, scale, and even more difficulties for 
experiments with physical systems, still that doesn't mean we should not strive 
to figure out how to resolve the difficulties.
The new NeurIPS Datasets and Benchmarks track could help to address this point.

#### B.2 Seek ways to retain and analyze all data

Seek opportunities to use all/most of the data that is collected, as opposed 
to only getting the data that is customarily used because existing techniques found
it useful. 
An example from Michael Roberts: full blood count tests are done routinely, 
but only 10-15 main parameters are used to make diagnoses, while hundreds of 
other parameters are discarded.

#### B.3 Organize focused joint hackathons

Bring industry and academics together for hackathon-style events, 
where industry brings interesting datasets and academics can try 
out various methods, but also can benefit from industrial participants 
for data intuition and quicker code setup. 
An example from Hiro Ono: NASA JPL has a dataset of all the labeled 
Martian terrain data, and JPL researchers and engineers already know 
what are the main challenges with this data, so a hackathon-style event could be 
a quick way for them to show to the academics what is lacking.


### C. Welcome research on safety, reliability and data anomalies/biases

#### C.1 Avoid viewing reliability as solely "an engineering" problem
A view from Hiro Ono: it is expected and fine that industry needs to focus on 
reliability while academia needs to encourage novelty; however, if these are 
taken to extremes, then industry and academia get into a situation where they 
are using a disjoint set of algorithms, so there is too little overlap, too 
few opportunities for meaningful collaboration and lack of potential for
mutual benefits.

#### C.2 Pay attention to skews and biases in the data

Develop algorithms that can incorporate information about known biases, 
develop methods that can detect and account for unexpected skew in the data.
An example from Michael Roberts: tendency to treat data as homogeneous can be 
harmful: e.g. data with COVID patient outcomes that does not mark whether a
hospital has overstretched its ICU resources.

<hr />


<div id="presentation-embed-38974994"></div>
<script src="https://slideslive.com/embed_presentation.js"></script>
<script>
  embed = new SlidesLiveEmbed("presentation-embed-38974994", {
    presentationId: "38974994",
    autoPlay: false,
    verticalEnabled: true,
  });
</script>
