# **[CNS 2018 workshop](http://www.cnsorg.org/cns-2018)**
Large neural networks, biological or artificial, can learn complex input-output relations. During learning, the network dynamics are often constrained to a low-dimensional manifold despite available high-dimensional space. The mechanism behind this space dimensionality confinement is yet unclear. 

Current technological advances in chronic population recordings and optogenetics provide the tools to measure and manipulate the reorganization of this state-space structure in neural circuits in awake, behaving animals during learning. 

We will bring together theoreticians and experimentalists to address a most fundamental question in neuroscience, that is, how learning reshapes collective network activity. 

More specifically, we will explore the following questions: 
* How does the neural dimensionality of a learned task relate to the task complexity? 
* Which mathematical tools are suitable to identify low-dimensional neural manifolds and track their emergence during learning?
* How does the dimensionality constrain the learning capabilities?

### [Registration](https://ocns.memberclicks.net/cns-2018 "CNS 2018 registration")
Note that the early registration deadline for the Seattle meeting (including workshops) is now very close: May 7 for non-members of OCNS, and May 16 for members.

### Schedule Wednesday, July 18:
08:50-09:00 Opening remarks  


09:00-09:30 [Zack Kilpatrick](https://www.colorado.edu/amath/zpkilpat) (University of Colorado Boulder):  
*Learning continuous attractors in recurrent neural networks*  
09:30-10:00 [SueYeon Chung](https://sites.google.com/site/sueyeonchung/) (Harvard University):  
*Classification and geometry of neural manifolds, and the application to deep networks*  
10:00-10:30 [Kameron Decker Harris](http://faculty.washington.edu/kamdh/) (University of Washington):  
*Connections between dimensionality and network sparsity*  


10:30-11:00 _Break_  


11:00-11:30 [Luca Mazzucato](https://lucamazzucato.weebly.com/) (Columbia University, University of Oregon):  
*Changes in effective network coupling mediate learning in a trace fear conditioning task*  
11:30-12:00 [Guillaume Lajoie](https://dms.umontreal.ca/~lajoie/) (Université de Montréal):  
*External perturbations modulate coding manifolds and dimensionality of motor cortex activity*  
12:00-12:30 [Alex Williams](http://alexhwilliams.info/) (Stanford University):  
*Dimensionality reduction with single trial resolution* 


12:30-14:00 _Lunch break_  


14:00-14:30 [Merav Stern](https://faculty.washington.edu/ms4325/) (University of Washington):  
*Increased correlations and decreased activity dimensions during task performance*  
14:30-15:00 [Stefano Recanatesi](https://faculty.washington.edu/etsb/) (University of Washington):  
*Explaining the dimensionality of the activity in RNNs through connectivity motifs*  


15:00-15:30 _Break_  


15:30-16:00 [Evelyn Tang](https://scholar.google.com/citations?user=CQbaZpMAAAAJ&hl=en) (University of Pennsylvania):  
*Effective learning is accompanied by high dimensional and efficient representations of neural activity*  
16:30-17:00 [Rainer Engelken](https://ctn.zuckermaninstitute.columbia.edu/people/rainer-engelken) (Columbia University):  
*Dimensionality and entropy rate of spontaneous and evoked neural rate dynamics*  


17:00-17:30 Discussion  

### Organizers

* Rainer Engelken, Center for Theoretical Neuroscience, Columbia University
* Guillaume Lajoie, Dept. de Mathématiques et Statistiques, Université de Montréal
* Merav Stern, Department of Applied Mathematics, University of Washington


### Abstracts


[Zack Kilpatrick](https://www.colorado.edu/amath/zpkilpat) (University of Colorado Boulder):  
*Training vs. designing continuous attractors in recurrent neuronal networks*  
Continuous attractors are a convenient conceptual model of the neural computations underlying spatial navigation, head direction, and other forms of parametric working memory. They are manifolds of marginally stable equilibria whose linearization is associated with one or more zero eigenvalues. We compare two approaches of generating continuous attractors in recurrent neuronal networks. The classic approach is to construct them explicitly by specifying the synaptic connectivity matrix be symmetric; e.g., bump attractors emerge in lateral inhibitory networks. When perturbed by noise fluctuations, bumps stochastically wander the attractor according to Brownian motion, degrading memory of their initial condition. A newer approach introduced by Sussillo and Barak (2013) is to generate continuous attractors using supervised training algorithms. We show this is an effective strategy for a network to learn a parametric working memory task. Furthermore, we can quantify how well a continuous attractor has been learned by computing an approximate potential function of the network along the trained attractor. Noise fluctuations still cause the stored variable to wander the trained attractor, as in the case of bumps. Linearization allows us to quantify how attractive equilibria along the attractor are. We then discuss numerical observations we have made based on different training conditions. Counterintuitively, the task is learned more robustly if the network is not required to represent the cue while it is being presented, but only after it is presented. We also demonstrate that adding noise fluctuations during learning can improve the generalization of the training.



[SueYeon Chung](https://sites.google.com/site/sueyeonchung/) (Harvard University):  
*Classification and geometry of neural manifolds, and the application to deep networks*  
Object manifolds arise when a neural population responds to an ensemble of sensory signals associated with different physical features (e.g., orientation, pose, scale, location, and intensity) of the same perceptual object. Object recognition and discrimination require classifying the manifolds in a manner that is insensitive to variability within a manifold. How neuronal systems give rise to invariant object classification and recognition is a fundamental problem in brain theory as well as in machine learning. 

We studied the ability of a readout network to classify objects from their perceptual manifold representations. We developed a statistical mechanical theory for the linear classification of manifolds with arbitrary geometries. We show how special anchor points on the manifolds can be used to define novel geometrical measures of radius and dimension which can explain the linear separability of manifolds of various geometries. Theoretical predictions are corroborated by numerical simulations using recently developed algorithms to compute maximum margin solutions for manifold dichotomies.

Our theory and its extensions provide a powerful and rich framework for applying statistical mechanics of linear classification to data arising from perceptual neuronal responses as well as to artificial deep networks trained for object recognition tasks. We demonstrate results from applying our method to both neuronal networks and deep networks for visual object recognition tasks. 

Exciting future work lies ahead as manifold representations of the sensory world are ubiquitous in both biological and artificial neural systems. Questions for future work include: How do neural manifold representations reformat in biological sensory hierarchies? Could we characterize dynamical neural manifolds for complex sequential stimuli and behaviors? How do neural manifold representations evolve during learning? Can neural manifold separability used as a design principle for artificial deep networks? 


[Kameron Decker Harris](http://faculty.washington.edu/kamdh/) (University of Washington):  
*Connections between dimensionality and network sparsity*  
Synaptic connectivity varies widely across neuronal types: cerebellar granule cells receive five orders of magnitude fewer inputs than the Purkinje cells they innervate. Similar circuits, including the insect mushroom body, also exhibit large divergences in connectivity. In contrast, the number of inputs per neuron in cerebral cortex is more uniform and large. We investigated how the "dimension" of a representation in a population of neurons depends on how many inputs each neuron receives and how this affects associative learning. Our theory predicts that the dimensions these representations are maximized at synaptic connectivities which match those observed anatomically, showing that sparse connectivity is sometimes superior to dense connectivity. When input synapses are subject to supervised plasticity, however, dense wiring becomes advantageous. This is a possible explanation for the differences between "cerebellar" and cortical structures.


[Luca Mazzucato](https://lucamazzucato.weebly.com/) (Columbia University, University of Oregon):  
*Changes in effective network coupling mediate learning in a trace fear conditioning task*  
Episodic memory requires linking events in time, a function dependent on the hippocampus. In `trace' fear conditioning, animals learn to associate a neutral cue with an aversive stimulus despite their separation in time by a delay period on the order of tens of seconds, but how this temporal association forms remains unclear. Here we track neural population dynamics over the complete time-course of learning and show that, in contrast to previous theories, the hippocampus does not generate persistent activity to bridge this gap. Instead learning is concomitant with the reorganization of neuronal covariance, where clusters of co-active neurons propagate stimulus information without temporal regularity. We characterize learning as the emergence of a consistent alignment of low-rank structures in covariance space across trials. Using latent space models, we demonstrate that such alignment is due to the stochastic reactivation of stimulus-specific neural assemblies occurring after learning. These data suggest that the network may maintain information across time delays by modifying the effective coupling between neurons.

[Guillaume Lajoie](https://dms.umontreal.ca/~lajoie/) (Université de Montréal):  
*External perturbations modulate coding manifolds and dimensionality of motor cortex activity*  
Stimulation of neurons in the brain can shape neural activity, synaptic connectivity, and function, with promising clinical uses as treatments for neural pathologies as well as novel information-transfer paradigms to interact with our brains. Brain stimulation comes in different temporal and spatial resolutions, from chronically implanted electrode arrays to electrical current delivery over broad areas, all with circuit-wide impact and poorly understood functional effects. As these technologies develop, and to better target their use, it is important to understand their influence on the organization of neural population dynamics, beyond the physiological implications on single neurons. What does stimulation do to sensory encoding, or motor control? How does it change the way populations of neurons coordinate and give rise to a given function?

In this talk, I will discuss recent findings that uncover the neural effects of a hotly debated form of non-invasive transcranial electric stimulation called tDCS (transcranial direct current stimulation) and its influence on population coding in cortex. Based on experimental data from macaque motor cortex (MC) during a reach task, I will describe dimension-based metrics to track how stimulation affects population coding in MC circuits. I will discuss how such metrics can track population-wide changes in task-relevant dynamics, and how they may be used for targeted stimulation design. 

[Alex Williams](http://alexhwilliams.info/) (Stanford University):  
*Dimensionality reduction with single trial resolution*  
Neural dimensionality is typically defined based on trial-averaged population activity, however it is of substantial interest to understand how neural dynamics change and evolve on a trial-by-trial basis due to changes in attention, motivation, or learning. Defining and measuring dimensionality with single-trial resolution is complicated by the fact that neural activity and animal behaviors can be highly stochastic, even under nominally identical trials. In this talk, I will explore two sources of single-trial variability and propose simple statistical methods to account for them. First, to account for trial-to-trial variation in amplitude (e.g., gain modulation), I propose the use of classic tensor decomposition methods. Second, to account for trial-to-trial variation in the latency or speed of neural dynamics (e.g. changes in reaction time), I propose a family of simple time warping models. In both cases, we find that these non-trial-averaged analyses provide much richer visualizations and nuanced understandings of experimental data derived from mice, rats, and primate models on diverse behavioral tasks. This work demonstrates the ability of unsupervised learning methods to uncover hidden features in neural data, which may be overlooked by classic dimensionality reduction methods.

[Merav Stern](https://faculty.washington.edu/ms4325/) (University of Washington):  
*Increased correlations and decreased activity dimensions during task performance*  
TBA

[Stefano Recanatesi](https://faculty.washington.edu/etsb/) (University of Washington):  
*Explaining the dimensionality of the activity in RNNs through connectivity motifs*  
TBA

[Evelyn Tang](https://scholar.google.com/citations?user=CQbaZpMAAAAJ&hl=en) (University of Pennsylvania):  
*Effective learning is accompanied by high dimensional and efficient representations of neural activity*  
A fundamental cognitive process is the ability to map value and identity onto objects as we learn about them. Exactly how such mental constructs emerge and what kind of space best embeds this mapping remains incompletely understood. Here we develop tools to quantify the space and organization of such a mapping, thereby providing a framework for studying the geometric representations of neural responses as reflected in functional MRI. Considering how human subjects learn the values of novel objects, we show that quick learners have a higher dimensional geometric representation than slow learners, and hence more easily distinguishable whole-brain responses to objects of different value. Furthermore, we find that quick learners display a more compact embedding of the task-based information and hence have a higher ratio of task-based dimension to embedding dimension, consistent with a greater efficiency of cognitive coding. Lastly, we investigate the neurophysiological drivers of high dimensional patterns at both regional and voxel levels, and complete our study with a complementary test of the distinguishability of associated whole-brain responses. Our results demonstrate a spatial organization of neural responses characteristic of learning, and offer a suite of geometric measures applicable to the study of efficient coding in higher-order cognitive processes more broadly.

16:30-17:00 [Rainer Engelken](https://ctn.zuckermaninstitute.columbia.edu/people/rainer-engelken) (Columbia University):  
*Dimensionality and entropy rate of spontaneous and evoked neural rate dynamics*  
Cortical circuits exhibit complex activity patterns both spontaneously and evoked by external stimuli. Finding low-dimensional structure in this high-dimensional population activity is a challenge for both experiment and theory. What is the diversity of the collective neural activity and how is it affected by an external stimulus?  
We present a new approach to answer these long-standing questions using firing-rate networks. Using concepts from dynamical systems theory, we calculate the attractor dimensionality and dynamical entropy rate of these networks. The dimensionality measures the diversity of collective activity states. Dynamical entropy quantifies the uncertainty amplification due to sensitivity to initial conditions. We obtain these two canonical measures of the collective network dynamics from the full set of Lyapunov exponents. Lyapunov exponents measure the exponential sensitivity to small perturbations in the tangent space along a trajectory. Our approach is applicable to arbitrary network topology and firing-rate dynamics.  
For concreteness, we consider a randomly-wired firing-rate network that exhibits chaotic rate fluctuations for sufficiently strong synaptic weights. We show that dynamical entropy scales logarithmically with synaptic coupling strength, while the attractor dimensionality exponentially saturates. Thus, despite the increasing dynamic uncertainty, the diversity of collective activity saturates for strong coupling. We find that a varying external stimulus drastically reduces both entropy and dimensionality.
Our study opens a novel avenue for characterizing the complex dynamics of rate networks and the geometric structure of the corresponding high-dimensional chaotic attractor. This not only gives a deeper understanding of the dynamics but also will help harness its computational capacities, e.g. for plasticity and learning of stable trajectories.


![visualization of low-dimensional attractor of chaotic firing-rate network by Rainer Engelken](http://www.columbia.edu/~re2365/attractor.png)
