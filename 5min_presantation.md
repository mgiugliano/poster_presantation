%5Min presentation ~ 800 words 
%Amo
%Dec 2018

It is the first draft, when I read it non stop it takes a bit more than 5 min,
could you please review it. 

thank you


# starter

*something that capture attention, remote from the content but absolutely relevant.*

There is a long standing debate on whether or not computers are a good analogy for the brain. It has not settled yet, but researchers agrees that the brain performs some sort of computation.
In computers built by us, we understand their compartments. Not only their hardware, such as the CPU or the storage memory hard disk, but also their software. We know that, for example, the units of information processing in computers are 0 or 1. What is the computational unit in the brain? Is it the precise timing of the spikes or is it the spike rate? How does information get transferred or stored? There are therefore many unanswered questions at this fundamental level. One of them is about the existence of correlations at different spatial and temporal scales, through out the brain. In our project, we will try to answer what biophysical factors play role in the emergence of correlations.


# what is the scientific question?

*clear definition and using figure to explain the example situation (cortical neurons embedded in the same microcircuit)*

## what are correlations?

But what do we mean by "correlations"? In probability theory, it means that two variables are related to each other and co-vary. The Pearson correlation, you are familiar with, is an example of estimating correlation. In neurophysiology, the term "correlation" has been used to describe the *similarity* and *covariance* between different physiological measures, such as the synaptic activation timing, the subthreshold membrane potential fluctuations, or the emitted spikes.

Correlations between neuronal activity has been observed in the brain at different time scale and locations. For instance. in cortical and sub cortical areas, across distinct global states of the brain (such as anaesthesia or wakefulness), between specific pairs of neighboring neurons or at the network- and global scales. 

Here, we focus on a very specific measure or definition for correlated neural activity: the correlations determined by common neuronal inputs (also known as "external"). Consider this situation -using figures- here we have a network of interconnected neurons, these two neurons (depicted by different colours) are *not* synaptically connected to each other. They receive inputs from many different presynaptic neurons, but a fraction of these inputs is shared. You see it in --- colour. And here you see the recorded spike trains of these two neurons. In simpler terms, we are interested in the similarity of the spiking activity of a neuronal pair (their **co**variability) given a certain amount of common input that theses two cells receive. We quantify such a covariability in terms of the similarity in the number of spikes, known as "spike-count correlation".

## what are the exact research questions?

Cortical neurons are known to be hugely heterogeneous in their own spiking patterns. for instance, excitatory pyramidal cells display a progressive accommodation of an otherwise regular spiking pattern. Inhibitory fast spiking interneurons display instead no accommodation and very high rates of spiking -using figures-. We ask (1) whether such a cell electrophysiological diversity could have quantitative effects on the spike-count correlations. And (2) if it is the case, what membrane biophysical properties are contributing to it? Also (3) we ask which is the effect of different firing rates or different background synaptic activity on the spike-count correlations.

# Method

How do we approach these questions? We will use mathematical modelling of the neuron function. The models are obtained from Human Brain Project, which is a large collaboratory project involving experimentalists and theoreticians. These models are of the variety known as "conductance-based" and "morphologically realistic". They both include the precise kinetics of ion channel gating and incorporate cellular morphology (by cable-theory) in the model description. For simulating the models, we will use the Flemish super computers network.

By increasing progressively its realism, we will mimick synaptic inputs in two ways: current-driven and conductance-based. In both cases, depicted here -using figures-, the stimulus reaching every neuron of the pair will be composed of the superposition of two components, one independent and one "common", or shared by the neuronal pair. The common part will be generated identically in trials, while the independent component will vary. The statistical properties of both components will be manipulating to explore distinct neuronal firing regimes. This setting gives us the freedom to change the amount of shared input as well as the output firing frequency, easily. We will then estimate the spike-count correlations by analysing the spike trains emitted by the neuornal pair, as we change the fraction of common inputs.  

I note that the "conductance-driven" stimuli will let us to simulate accurately both excitatory and inhibitory inputs. Indeed, such a conductance stimuli mimic synaptic inputs, mediated by AMPA- and by GABA-A-receptors.

The stimuli will be in the form of one long waveform, lasting 100 seconds. Blocks of experiment will be repeated 1 to 5 times with constant statistics but the different sets of block repetitions will have different statistics.

Common input will be identical across repetition of blocks and cell types. This will be achieved by using an identical seed for a pseudo-random number generator, which will be used for generating the shared component. 

# Shortcomings & Alternative approaches 

There are at least two potential limitations for our approach: (1) the complexity of the models. Multi-compartmental models of neurons have a large number of interdependent parameters. The exploration and interpretation of these parameters are hard. Despite, these models are not like a black box, they have too many degrees of freedom. An alternative would be to use simpler models, such as single-compartmental models, at the expense of greatly reducing their biophysical accuracy.

Another limitation is (2) the confinement of all synaptic stimuli to the soma. Both current- and conductance-driven stimuli will be in fact injected to the soma. This is done to replicate an actual experiments, performed in brain slices. However, such a strategy fails to mimic dendritically-distributed inputs, as conductance injection has by definition a "point" nature. An alternative is to use a simulation methodology for direct activation of synaptic bouton. This will be adopted if time allows it.




