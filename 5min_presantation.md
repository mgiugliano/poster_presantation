%5Min presentation ~ 800 words 
%Amo
%Dec 2018

It is the first draft, when I read it non stop it takes a bit more than 5 min,
could you please review it. 

thank you


# starter

*something that capture attention, remote from the content but relevant.*

There is a long lasting debate over whether the computers are good analogy for the brain or not, it is not settled yet, but everyone agrees that brains do some sort of computation.
In computers that we built for ourselves, we know its components, not only the hardware, like CPU or hard disk, but also software, we know that for example the units of information in computers are 0 and 1. But what is the computational unit in the brain? is it the timing of the spikes or is it the number of the spikes? how information get transferred? there are many unanswered questions at this fundamental level, one of them is about the emergence of correlations. It is present at different spatial and temporal scales through out the brain. In our project we will try to answer what biophysical factors may play role in its emergence.


# what is the question

*clear definition and using figure to explain the example situation (cortical neurons embedded in the same microcircuit)*

## what is correlation

But what do we mean when we say correlations? In probability theory, it means how two different sets of variables are related to each other. The Pearson correlation that you are familiar with. In neurophysiology this term has been used to describe the association between different physiological measures, be it synaptic activation timing, membrane potential fluctuations or the emitted spikes.

Different forms of correlations at different time scale and locations in the brain has been observed, in cortical and sub cortical areas, in different global states of the brain, anaesthesia or wakefulness, between pairs of neurons or at the network and global scale. Even between sub threshold membrane potential of the neurons. No matter what techniques have been used for stimulation of neurons or recording them.

Here we are interested in a very specific form of correlation emergence: consider this situation -using figures- here we have a network of interconnected neurons, these two neurons that are depicted with different colours, they are *not* connected to each other. They receive many inputs from many different neurons, but a minority of these inputs are shared. You see it in --- colour. And here you see the recorded spike trains of these two neurons. In simple terms, what we are interested in, is the correlation between the amount of common input that theses two cells receive, and the amount of **co**variability that they show in their spiking patterns. It is called spike count correlation. 

This situation is not occasional, indeed if you randomly pick to unconnected neurons, in close proximity, they may exhibit this quality, many independent inputs and some common inputs that they receive.

We have some hypothesis with regard to what could be the functional role of this form of correlations in the brain but we have no understanding of its biophysical substrates, like what sort of membrane properties or cell morphology can be responsible for shaping it.

## what are the exact questions

So what is our question in this project? we know that cortical neurons are hugely heterogeneous in their spiking patterns, for instance, pyramidal cells with their progressive accommodation of a regular spiking pattern or fast spiking interneurons with no accommodation -using figures-. We question whether this cell e-type diversity can have quantitative effect on the correlations? And if it is the case then what biophysical properties of the membrane are contributing? Also we will manipulate the statistics of the inputs to evaluate the effects of different firing rates and different background synaptic activities on correlations.

# method

How we approach this questions? we will use mathematical modelling of the neuron function. The models are obtained from blue brain project. They are in the domain of conductance based models and morphologically realistic. And for simulations we will use Flemish super computer.

We will use two forms of stimulations, current driven and conductance based. In both cases as shown here -using figures-, the stimulation composed of superposition of two waveforms, one independent input and one common input. The common part will be generated identically in trials but the independent component will vary by manipulating the statistics of the input. This setting will give us the freedom to change the amount of shared input or firing frequency of the output easily. Just one cell needs to be stimulated and recorded at the time, because the shared common input is identical in trials.  

conductance driven stimulation will let us to have both excitatory and inhibitory stimulation. The conductance stimulations mimic synaptic conductances mediated by AMPA- and by GABA-A-receptors.

stimulations will be in the form of one long waveform that will last 100 seconds. Blocks of experiment will be repeated 1 to 5 times with constant statistics but different sets of blocks repetitions will have different statistics.

# shortcomings & alternatives 

There are at least two potential limitations for this approach, one, is the complexity of the models, we use multi compartmental models with interdependent parameters, so manipulation of these parameters would be hard also tracing back the findings of experiments. It is more or less like a black box. The alternative would be using a single compartmental model but in that case it will greatly reduce the biophysical relevance of the model.

Another limitation is the confinement of all activation to the soma. Both current and conductance driven stimulations will be injected to the soma. It means that although we will use conductance based stimulation to mimic dendritically distributed inputs, still the point nature of the conductance injection has an effect. A possible alternative is to use a methodology for direct activation of synaptic bouton.




