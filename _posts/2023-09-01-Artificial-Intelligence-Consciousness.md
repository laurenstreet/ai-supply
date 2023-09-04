---
title: "Artificial Intelligence Consciousness"
permalink: /ai-conscious/
date: 2023-09-01
classes: wide
last_modified_at: 2023-09-03
---

Recently I've been reading an interesting report on consciousness in artificial intelligence (AI) by Patrick Butlin ([Future of Humanity Institute](https://www.fhi.ox.ac.uk/)), Robert Long ([Center for AI Safety](https://www.safe.ai/)), et al. [[1]](https://arxiv.org/abs/2308.08708).  

In this report, the authors attempt to measure the consciousness of current AI systems by testing whether these systems have certain properties that are typically present in systems with consciousness.  These properties, dubbed "indicator" properties, were extracted from leading neuroscientific theories of and ideas about consciousness.

These indicator properties are present in systems with human or animal consciousness, but don't necessarily indicate consciousness.  For example, while these properties may be present in humans, any one property isn't necessarily enough for consciousness, while some properties are much more telling of a conscious system than others.  The authors, therefore, are careful to note that in order to test consciousness with these properties, one has to analyze not only the number of properties present in a given system, but also which properties are present in combination.  

Ultimately, the authors concluded that no current AI system has enough indicator properties (and in the right combination) to deem it conscious.  However, they claim that many of the indicator properties should be programmable into AI systems with our current technology.  This conclusion brings about a sense of urgency for the further analysis of consciousness in AI systems and the evolution of theories and means used to test consciousness.  

There are also the moral considerations that arise.  We are at a stage in our technological development where potentially conscious systems can be made artificially, or at least unconscious systems that seem conscious.  It can be asked, then, what can happen when people under- or over-attribute consciousness to AI systems?

The study is based on three main postulates:
1. computational functionalism
  - mental states arise from the performance of the correct computations in the correct order (these performances are necessary and sufficient for consciousness) 
  - if computational functionalism is not true, consciousness in AI systems may not be possible
2. there is empirical evidence for current neuroscientific theories of and ideas about consciousness
3. the functions used to describe consciousness in neuroscientific theories can be used to test consciousness in AI systems (the authors use a "theory-heavy" approach rather than rely on behavioural tests which can give false positives for unconscious AI systems that can mimic conscious behavior [[2]](https://aeon.co/essays/to-understand-ai-sentience-first-understand-it-in-animals))

Relying on these postulates, the authors then claim that consciousness in AI systems can be tested through the consideration of how many indicator properties (and in what combinations) are present in the system, how confident one is in the theory or idea of consciousness from which the indicator properties are extracted, and how confident one is in the tenet of computational functionalism.

# Indicator properties summary

There are many interesting indicator properties discussed and analyzed in the study, but here I'll only discuss a few.  See Table 1 of [[1]](https://arxiv.org/abs/2308.08708) for a full summary of all indicator properties studies.

- Recurrent Processing Theory (RPT; [[3]](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(06)00237-3?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS1364661306002373%3Fshowall%3Dtrue) [[4]](https://www.frontiersin.org/articles/10.3389/fpsyg.2020.00083/full)) 
  - RPT-1: Input modules using at least algorithmic recurrence
  - RPT-2: Input modules generating unified perceptual representations
- Global Workspace Theory (GWT; [[5]](https://www.sscnet.ucla.edu/comm/steen/cogweb/Abstracts/Baars_88.html) [[6]](https://www.pnas.org/doi/full/10.1073/pnas.95.24.14529) [[7]](https://www.cell.com/neuron/fulltext/S0896-6273(11)00258-3?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0896627311002583%3Fshowall%3Dtrue) [[8]](https://www.cell.com/neuron/fulltext/S0896-6273(20)30052-0?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0896627320300520%3Fshowall%3Dtrue))
  - GWT-1: Multiple modules that can operate in parallel
  - GWT-2: Limited capacity global workspace resulting in information bottleneck and selective attention
  - GWT-3: Module access of workspace information
  - GWT-4: Global workspace with state-dependent attention in order to query modules to perform tasks
- Agency and Embodiment (AE)
  - AE-1: Agency: Ability to pursue goals from feedback and selection of outputs
  - AE-2: Embodiment:  Modeling output-input contingencies for perception or control

# Theories and ideas about consciousness

Now that we have a summary of the indicator properties that were extracted from these theories and ideas, let's try to understand a bit more where these properties come from.

## RPT

RPT is a theory of the perceptual areas of the brain (e.g. visual) and seeks to explain what makes a state conscious and what makes a state unconscious.  Through analysis and testing of this theory it's claimed that in order for a stimulus to be visually conscious, for example, a particular visual process needs to happen.  A stimulus can cause activity in the visual areas, however it doesn't necessarily become visually conscious.  Rather, the stimulus needs to be strong enough in order to trigger the necessary means for consciousness: recurrent processing resulting in unified representations of information.

The authors make the distinction between two different types of recurrent processing, namely implementational and algorithmic.  Implementational recurrent processing is the type of processing utilized by our brains.  Signals that are sent to individual neurons are affected by earlier neuronal outputs due to feedback loops.  In this case, one individual neuron can have a input signal that depends on its earlier output signal.

This type of processing can be mimicked with a suitable feedforward network in which multiple layers in different regions of the network share weights.  In this case, the signal output of one layer of the network can affect multiple layers after it due to the sharing of weights (or, in a sense, signal information).  These layers will then have a signal input which, in a way, depends on its earlier output signal (since it shared information with the earlier layer sharing its weights).  The authors take the position that algorithmic recurrence (rather than the stronger condition of implementation recurrence) is enough for consciousnes, bringing us to the first indicator property for RPT: 

### RPT-1: Input modules using at least algorithmic recurrence

Or in other words, an indicator of consciousness in a given system is that the system have individual processing units, called modules, that are capable of exhibiting algorithmic recurrence (like the different layers of a neural network or neurons in a brain which can exhibit true implementational recurrence).

Another indicator of consciousness comes from the unified representation of input information that arises as a result of algorithmic recurrence giving us the second indicator property for RPT:

### RPT-2: Input modules generating unified perceptual representations

The authors discuss various forms of evidence for RPT.  For example, neuroscientific experiments have suggested that not all visual stimuli become conscious [[3]](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(06)00237-3?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS1364661306002373%3Fshowall%3Dtrue) and that the unified representation of information that arises from recurrent processing is what causes visual stimuli to be conscious [[4]](https://www.frontiersin.org/articles/10.3389/fpsyg.2020.00083/full).

As stated earlier, RPT is a theory of the perceptual areas of our brain (typically visual) and so it's not clear whether the processes necessary for visual consciousness are similar to the processes necessary for other types of consciousness.

### RPT examples

Recurrent neural networks, long short-term memory networks, and gated recurrent unit networks are all existing systems with indicator property RPT-1.  Deep convolutional neural networks (DCNNs) have been used for successful object recognition [[9]](https://www.pnas.org/doi/full/10.1073/pnas.1905544116), however it's not clear whether these systems are good models for human vision [[10]](https://www.cambridge.org/core/journals/behavioral-and-brain-sciences/article/abs/deep-problems-with-neural-network-models-of-human-vision/ABCE483EE95E80315058BB262DCA26A9) or whether the ability for these systems to recognize objects is due to their ability to generate unified representations of information or some other process.

## GWT

GWT is a theory of consciousness which, in part, posits that individual modules can work together in order to perform cognitive tasks and that all modules are integrated together through connections to a warehouse of information called the global workspace (GW).  Information sent to the GW can potentially be represented as information in the GW, and it's this representation that is conscious. In neural versions of GWT, conscious states can arise from sufficient signaling to the GW of the brain resulting in recurrent processing and a unified representation of the signals being sent [[6]](https://www.pnas.org/doi/full/10.1073/pnas.95.24.14529).  

Using GWT, the consciousness of a system can be tested by four categories of increasing access to the full potential of the GW, where systems which exhibit higher level indicator properties are more likely to be conscious. The first indicator concerns the simplest level of access to the GW.


### GWT-1: Multiple modules that can operate in parallel

In other words, the system must have multiple modules that can work together to perform tasks.  

The next level of access is for modules to be able to send information to the GW, which must have a smaller capacity than the sum capacity of all connected modules.  This results in a bottleneck in information, allowing for more efficient sharing of information [[11]](https://arxiv.org/abs/2103.01197) and forcing the GW to represent information in a low-dimensional way that can then be translated into higher-level cognitive tasks [[12]](https://arxiv.org/abs/1709.08568).  

Because of this limited capacity for information, it's necessary for the GW to be selective in the information that is chosen to be represented.  These points make up the second indicator property for GWT:

### GWT-2: Limited capacity global workspace resulting in information bottleneck and selective attention

The next level of access to the GW is that all modules have access to the information represented in the GW.  This enables individual modules to share information with all other modules.  This gives the third indicator property for GWT:

### GWT-3: Module access to workspace information

The next level of access to the GW has access to its full potential, which unlocks the ability for individual modules to not only share information with all other modules, but also to influence the activity and even control other modules.  

In order to do this, the GW must be sensitive to the states of the modules as it selects which information to represent (which allows modules to influence each other), and it must be able to query modules to perform tasks (which allows modules to control each other).  The fourth, and final, indicator property of GWT is then:

### GWT-4: Global workspace with state-dependent attention in order to query modules to perform tasks

Some cited evidence for GWT pertains to studies which seek to compare conscious and unconscious conditions with the use of controlled stimuli.  For example, some studies seem to suggest that consciousness is associated with widespread activity in the brain, including the prefrontal cortex (which may or may not be the GW), and that processing of conscious states seem to be delayed relative to the initial onset of activity (pointing to the necessity for sustained activity to the GW in order to generate GW representations) [[8]](https://www.cell.com/neuron/fulltext/S0896-6273(20)30052-0?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0896627320300520%3Fshowall%3Dtrue). 

### GWT examples

A working implementation of all GWT indicators doesn't seem to exist, though some proposals have been made [[11]](https://arxiv.org/abs/2103.01197) [[13]](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(21)00077-1?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0166223621000771%3Fshowall%3Dtrue).  It can be argued that large language models called Transformers [[14]](https://arxiv.org/abs/1706.03762) exhibit many of the GWT indicator properties, however these models aren't recurrent and lack distinction between modules and the GW. 

## AE

Agency is something that seems to arise in conscious systems.  The authors seem to define it more or less as the ability of a system to learn to pursue goals by sensing and acting upon its environment based on state dependent information.  This gives the first indicator property of AE:
### AE-1 Agency: Ability to pursue goals from feedback and selection of outputs

An agent learns to how pursue goals through feedback mechanisms that give preference to actions that help the pursuit.  An embodied agent can further sense or use motor control to affect their environment and has some model of how their outputs affect their inputs which includes some systematic effects.  This gives us the final indicator for AE:

### AE-2 Embodiment:  Modeling output-input contingencies and some systematic effects for perception or control

This output-input model for embodied agents is particularly important for understanding differences between changes that happen inside and those that happen outside the system. 

### Agency and embodiment examples

Agency is typically an explicit goal of reinforcement learning (RL) systems in which a agent learns how to pursue goals through use of sequences of actions and rewards [[1]](https://mitpress.mit.edu/9780262039246/reinforcement-learning/) and it can be argued that many RL systems exhibit much of AE-1 [[15]](https://onlinelibrary.wiley.com/doi/10.1111/mila.12458).  As for embodiment, DeepMind's AdA [[16]](https://arxiv.org/abs/2301.07608) makes a strong case for embodiment as an RL system used for control of an avatar in a 3D environment.

# Ethical considerations

Of course, with the creation of any new technology comes some ethical considerations, but here we're talking about potentially making machines conscious, arguably bringing a form of life into being.  If, on the other hand, it's not possible to create consciousness in machines, unconscious machines can be made to seem very conscious.

The authors, then, note two main categories of ethical considerations: over-attribution and under-attribution of consciousness to AI.

The risk that we'll attribute consciousness to unconscious AI systems is more likely, especially with large language models [[17]](https://arxiv.org/abs/2305.16367).  While the risk of under-attributed consciousness is also plausible given that conscious AI systems may have completely different modes of being than we [[18]](https://nickbostrom.com/papers/digital-minds.pdf).  

One way to combat both possibilities is to better understand when a system is conscious or not.

# References

[See list of all references here](https://laurenstreet.github.io/ai-supply/refs-ai-conscious/)