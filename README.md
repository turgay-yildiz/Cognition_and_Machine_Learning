# Cognition_and_Machine_Learning
The primary objective of this project is to undertake the implementation of fundamental components pivotal to the realization of AGI through the utilization of machine learning methodologies. These foundational components can be categorized as intuitive physics, intuitive psychology, causality, compositionality, and learning-to-learn.

Project Idea :

The primary objective of this project is to undertake the implementation of fundamental
components pivotal to the realization of Artificial General Intelligence (AGI) through the utilization
of machine learning methodologies. These foundational components can be categorized as intuitive
physics, intuitive psychology, causality, compositionality, and learning-to-learn. While the
application of such theoretical constructs within the domains of Artificial Intelligence (AI) and
Machine Learning (ML) may initially appear unconventional and perhaps distant, historical
perspectives reveal a symbiotic relationship between these fields. Notably, seminal works in AI and
ML often found their genesis within the purview of Cognitive Science, Psychological Review, or
Psychology journals, exemplified by the following:

Rumelhart, D., Hinton, G. & Williams, R. Learning representations by back-propagating errors ,
Institute for Cognitive Science, University of California
Ackley, D. H., Hinton, G. E., & Sejnowski, T. J. (1985). A learning algorithm for Boltzmann
Machines. Cognitive Science, 9(1), 147–169.
Elman, Jeffrey L. (1990). Finding Structure in Time. Cognitive Science 14 (2):179-211.

These aforementioned concepts were researched and implemented in models, particularly within the
realm of Cognitive Science research1,2,3. The overarching aim of such endeavors can be succinctly
summarized as the emulation of human perception, learning, and cognitive processes within
machine systems : building machines that see, learn and think like people4. Hence, my approach
shall transcend mere pattern recognition, emphasizing the imperative of comprehensive model
construction.


Concepts :

1. Intuitive Physics:
   
Intuitive Physics can be conceptualized as an understanding of physical concepts like object
permanence (Lake et al., 2017), enabling infants to comprehend the persistence of objects over
time, even when they are not visually perceptible. This cognitive ability encompasses the
recognition that objects retain their existence despite being temporarily occluded from view.
Furthermore, infants also discount physically impossible trajectories (Lake et al., 2017). They
1exhibit an awareness of how the behaviors or trajectories of objects conform to fundamental
principles of physics, such as gravitational forces and friction. Additionally, they demonstrate a
comprehension of properties like solidity (Lake et al., 2017) and analogous characteristics. Intuitive
physics can be used as a tool to facilitate transfer learning in AI and ML or to create models to have
a more causally proper understanding of the world. To simulate the objects’ behavior and
trajectories under different conditions, Battaglia et al., (2013) used Intuitive Physics Engine (IPE)
which is a probabilistic simulation tool.
Physical Intuition also has a spatial and temporal facet. For example, Omniglot which is the dataset
this project is going to employ was used by Li et al., (2022) to explore the spatio-temporal
characterization capabilities of spiking neural networks (SNNs) by employing few-shot learning.
Therefore, spatial and temporal aspects of data is a very important component of building models,
especially models designed to reach to the human-level intelligence. Hence, one-shot and few-shot
learning seem to be the best way for this challenge.

3. Intuitive Psychology:
   
Intuitive Psychology as mentioned by Lake et al., (2017) pertains to infants' capacity to attribute
mental states, such as beliefs, goals, and desires, to other individuals. This cognitive ability
significantly influences their learning processes and predictive reasoning. For instance, Lake et al.,
(2017) gives a video game example : when observing a person engage in a video game, a child can
infer the intentions behind the player's actions based on their understanding of psychological states.
Consequently, the child may discern certain in-game objects as detrimental, prompting them to
avoid interaction, while others are perceived as advantageous, thereby motivating pursuit. This
comprehension of psychological states facilitates infants' social cognition and informs their
decision-making in various contexts.
Ability to differentiate between what is animate and what is inanimate may ease the process
of learning. We assume that human beings are rational, and we expect them to behave in predicted
ways. We know that inanimate objects are not rational and only subject to the physical rules. These
concepts facilitate our understanding or modeling of the reality. As Lake et al., (2017) put forward,
Model building is the hallmark of human-level learning. That is where Cognitive Science can make
great contributions to the AI, by bridging the gap between machines and people.

5. Causality:
   
As mentioned above, both intuitive physics and intuitive psychology revolve around the construction
of models. As previously noted, these elements are often lacking in conventional AI and ML
techniques. Human cognition inherently involves an ongoing endeavor to construct representations
of the surrounding world. This novel approach lies at the intersection of AI and Cognitive Science.
Notably, as Lake et al., (2017) claimed, both intuitive physics and intuitive psychology can be seen
2as causal models of reality. Lake et al., (2015) used Bayesian Program Learning (BPL) to capture
the causal and compositional properties of the Omniglot dataset.
By giving image caption examples from Deep Neural Networks, Lake et al., (2017) shows that
while Deep Learning models excel in pattern and object recognition within datasets, they fall short
in establishing causal relationships among these entities. This deficiency underscores a significant
disparity between machine intelligence and human-level cognition. Primarily, it stems from the
absence of key concepts such as intuitive understanding of physical phenomena and the causative
links between them. Consequently, bridging this gap necessitates a paradigm shift towards
integrating causal reasoning frameworks into AI and ML methodologies.

7. Compositionality:
   
In this project, compositionality will serve as a pivotal implementation method. Typically utilized in
algorithms such as one-shot learning and few-shot learning. Compositionality stands as a technique
enabling models to learn from sparse data (Lake et al., 2017). This approach is closely intertwined
with learning-to-learn, also known as transfer learning or meta-learning (Lake et al., 2011).
Notably, compositionality and learning-to-learn are intricately interconnected concepts.
The essence of compositionality lies in the notion that learning from individual components of a
system can expedite the learning of a different system with similar components as a whole,
particularly in scenarios where data availability is limited. By initially acquiring knowledge of
constituent elements, subsequent learning endeavors can capitalize on this foundation. Thereby, this
can facilitate more efficient learning processes with minimal data input. Indeed, the ability to learn
from sparse datasets represents a paramount challenge in the pursuit of developing machines with
human-like cognitive capacities. As such, compositionality emerges as a crucial tool in the quest to
bridge this disparity between artificial and human intelligence.
9. Learning-to-learn:
Learning-to-learn, also referred to as transfer learning or meta-learning, encompasses a nuanced
distinction depending on the context in which it is employed. Within the realm of Deep Learning,
transfer learning or meta-learning typically involves the utilization of pre-trained layers to expedite
the learning process for subsequent tasks. However, in the domain of Cognitive Science, learning-
to-learn embodies a more profound connotation aligned with its literal interpretation.
Consider a child's acquisition of knowledge regarding the composition of letters or digits,
recognizing them as distinct arrangements of discrete shapes. Beyond mere task-specific
application, this cognitive process engenders a fundamental understanding that entities can be
comprised of constituent components, thereby facilitating discrimination and comprehension. This
form of learning transcends pattern recognition, engendering the assimilation of novel concepts and
3the construction of cognitive models. Consequently, individuals develop the capacity to learn how
to learn, a trait embodied by their adeptness at deriving insights from sparse data.
The efficacy of learning-to-learn lies in its facilitation of not only task-specific adaptation but also
the acquisition of generalizable cognitive frameworks. By embracing the underlying principles of
compositional learning, individuals become adept at extrapolating knowledge across diverse
domains, thereby enhancing their capacity for rapid and efficient learning. Thus, learning-to-learn
emerges as a cornerstone in the endeavor to equip artificial systems with human-like cognitive
capabilities, enabling them to thrive in dynamic and data-scarce environments.

What's Novel:

First of all, a comprehensive review of prior research endeavors within the field will be conducted
to elucidate the existing landscape of knowledge. This critical examination will encompass an
exploration of how foundational concepts such as causality, compositionality, and learning-to-learn
have been leveraged in the context of one-shot and few-shot learning paradigms. The rationale
behind this inquiry lies in the recognition of these cognitive principles as potential differentiators
between human and machine learning processes, with a particular emphasis on model building in
comparison with pattern recognition. Consequently, the endeavor to learn from sparse data emerges
as a natural consequence of portraying the differences between human and machine learning
modalities. Thereby, it serves as a potential indicator of progress towards achieving human-level
intelligence.

The novel aspect of this project, unlike former studies, lies in its innovative approach to classifying
handwritten characters using machine learning techniques, specifically leveraging the principle of
compositionality. While previous research, such as the work by Lake et al., (2017), has
demonstrated the efficacy of Bayesian Program Learning (BPL) in achieving human-level
performance in one-shot classification tasks, this project deviates from using BPL. Instead, its aim
is to harness the concept of compositionality by both employing different data processing
techniques and using Machine Learning models, instead of BPL. To capture causality, Lake et al.,
(2015) used Bayesian Program Learning (BPL). However, with this project, we can hope to capture
causality by employing chronological order of strokes in two dimensional space in the Omniglot
data.

By refraining from reliance on statistics or conditional probability which are inherent in BPL, the
project intends a quest to conceptualize and exploit compositionality and causality as the
cornerstone of the its algorithmic framework. This departure necessitates a creative reimagining of
how compositionality and causality can be translated into a practical algorithmic implementation.
Unlike BPL, which utilizes a causal and compositional model inherently, the proposed algorithm of
this project seeks to extract the essence of compositionality and causality; and embed them within
the learning process without direct recourse to probabilistic methodologies.
4Lake et al., (2011) created a library of strokes. They clustered 40,000 strokes by using k-means to
form 1000 centroids. The library is composed of these 1000 centroids. Then, they tested three
different models: the stroke model which in fact is a generative model that they introduced, the
Deep Boltzman Machine (DBM), and Nearest Neighbor (NN) for 20 way-classification from one
example. The stroke model (% 54.9) outperformed both (% 39.6 for the DBM and % 15.7 for the
NN).

Li et al., (2022) reconstructed Omniglot data into videos. By employing spatial and temporal
information in txt files, they reconstructed the text record of strokes as a video of writing tracks. I
am going to use a similar technique. They also employed linear interpolation algorithm to complete
the data in milliseconds to reconstruct the character writing as accurate as possible. However, since
I am not going to use the time dimension in my model so as to require any interpolation method. I
am only going to use spatial knowledge in txt files to construct components of images and use time
dimension only to put these newly created images into a chronological order.
Thus, the novelty of this endeavor lies in its ambition to forge new pathways in AI and ML by
leveraging the inherent principles of compositionality and causality to achieve superior performance
in classifying and even predicting handwritten characters from sparse data by employing a novel
data processing and implementation approach. This departure from traditional statistical approaches
represents a paradigm shift towards more conceptually driven algorithmic solutions, potentially
unlocking novel avenues for advancing the capabilities of machine learning systems.

Implementation of the Project:

1. The Dataset :
   
Each process of implementation of the project is going to be clarified as step by step. Specifically, a
Machine Learning model will be trained to discern and learn components (subparts) of a dataset
called Omniglot which composed of 1623 distinct handwritten characters from 50 different
alphabets. The Omniglot dataset aims to cultivate algorithms that mimic human learning processes
more closely. Each character was independently drawn by 20 individuals through Amazon's
Mechanical Turk platform. Each image is paired with stroke data, presenting sequences of [x,y,t]
coordinates where time (t) is measured in milliseconds.
Important Note : The dataset is used mostly in generative models like BPL (Lake et al., 2011, 2015
and 2017), and in those models, it requires parsers. In other models, it is generally used for its
spatial and temporal aspect (Li et al., 2022). I invented a new method which seems easier to
understand and apply to.
