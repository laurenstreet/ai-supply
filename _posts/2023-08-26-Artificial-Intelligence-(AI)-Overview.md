---
title: "Artificial Intelligence (AI) Overview"
permalink: /ai-overview/
date: 2023-08-26
tags:
  - overview
---

Some common stories are that the idea of AI began in the 1950s [[1]](https://academic.oup.com/mind/article/LIX/236/433/986238?login=false) [[2]](https://aisb.org.uk/what-is-ai/), or actually long ago as seen in ancient myths [[3]](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/1848).  

One reason humans strive to create AI is the perception that it will make life easier.  The numerous examples of automatic task performance and complex problem solving performed by AI today is enough evidence to show that this perception is approximately aligned with reality.  As a bonus to having machines perform tasks for us, AI research also shines a light on intelligence.  In wanting our machines to be intelligent, we bring ourselves the task of understanding what intelligence is.

## How intelligent is AI?

Intelligence is a complex idea spanning many areas of life and with numerous evolving components.  That being said, it is difficult to define.  One way to describe it is by breaking it up into definable, testable traits.  Some of these traits have been researched extensively and programmed into AI systems over the years, including knowledge representation, reasoning, planning, learning, and perception [[4]](https://aima.cs.berkeley.edu/) [[5]](https://www.sciencedirect.com/book/9781558604674/artificial-intelligence-a-new-synthesis).

AI seems to be defined, more or less, as a program with any perceived intelligence.  This includes quite a diverse range of machines, like those that perform one specific reasoning task, and those that are indistinguishable from humans, etc.  It is common, then, to categorize AI by its performance related to humans [[6]](https://www.jstor.org/stable/resrep12564):

1. Artificial narrow intelligence (ANI): designed to perform specific tasks, can potentially simulate or exceed human skill level but has narrow range of applicability related to humans
2. Artificial general intelligence (AGI): performs tasks on par with a human with the full range of applicability as humans
3. Artificial super intelligence (ASI): outperforms human level skills with a superior understanding compared to humans

ANI and AGI are also commonly broken down into further categories as [[7]](https://www.govtech.com/computing/understanding-the-four-types-of-artificial-intelligence.html#:~:text=There%20are%20four%20types%20of,of%20mind%20and%20self%2Dawareness.)

1. Reactive machines
    - Subset of ANI
    - No learning from previous actions, only reacts to stimuli
    - Example: IBM's chess playing AI, Deep Blue, made predictions for next possible moves, but didn't learn from past moves
2. Limited memory machines
    - Subset of ANI
    - Limited ability to learn from past eventsway 
    - Example: Self driving cars use a set of rules (e.g. knowledge of traffic signs) combined with observations of events in their enviroment (e.g. other cars around) to make decisions (e.g. steering and speed adjustment)
3. Theory of mind machines
    - Subset of ANI, almost AGI
    - Limited ability to learn from past events as well as to understand the desires of other entities and how they can be affected 
    - Example: Lack of benchmark tests [[8]](https://arxiv.org/abs/2303.11594) but possibly some large language models [[9]](https://arxiv.org/abs/2302.02083)
4. Self-aware machines
    - Truly AGI
    - Ability to learn from past events, to understand the desires of other entities and how they can be affected, and to understand themself
    - Example: None yet

Given that there are numerous ways to describe intelligence and intelligent machines, there have been attempts to standardize the study and testing of these systems.  One such model is an attempt at the standardization of human-like minds and can be broken down into structure and processing, memory and content, learning, and perception and action [[10]](https://onlinelibrary.wiley.com/doi/10.1609/aimag.v38i4.2744).  This standard model of the mind was based on three existing architectures with the idea that the standard model would grow to include more architectures.  These three structures, namely ACT-R, Soar, and Sigma, base behavior on sequences of memory dependent cycles.  

## Approaches to AI

Historically, there have been two main AI disciplines: connectionist AI utilizes the idea that systems of interconnected neuron-like units (neural networks) are capable of complex logical calculations [[11]](https://link.springer.com/article/10.1007/BF02478259); and symbolic AI utilizes symbolic representations (human readable) to perform tasks [[12]](https://www.sciencedirect.com/science/article/pii/S2352154618301943?via%3Dihub).

Connectionist systems are strong in extracting features from data, yet suffer from a lack of explainability since neural networks are largely unreadable to humans.  Symbolic systems are easily explained since they are represented by human-readable symbolic representations yet suffer from the fact that the symbolic representations are human-made rather than intrinsic to the data. Because both of these approaches have their set of strengths and weaknesses which seem to complement each other, a third approach, Neuro-symbolic (NeSy) AI, has arisen based on the principle of combining the two in an attempt to eliminate the disadvantages of both approaches [[12]](https://www.sciencedirect.com/science/article/pii/S2352154618301943?via%3Dihub) [[13]](https://arxiv.org/abs/2105.05330).

## Applications of AI

AI can be broken down hierarchically into the different structures within AI:

![Common representation of AI, DL, and ML](https://github.com/laurenstreet/ai-supply/blob/main/assets/images/AI-ML-DL.png?raw=true "Common representation of AI, DL, and ML")

Many of the models that I will discuss on this site fall into the category of deep learning.  These include reinforcement learning, natural language processing, and generative models.
## AI ethics

With the increase of AI in our everyday lives comes the onset of responsibilities that can either be taken or shunned.  Some recent and commonly cited ethical problems concern AI algorithms that can generate content like text, images, and audio.  This type of AI can be used to spread misinformation [[14]](https://arxiv.org/abs/2305.00944), while the data these algorithms are trained on can lead to privacy concerns and potential theft of intellectual property [[15]](https://www.washingtonpost.com/technology/2022/12/09/chatgpt-lensa-ai-ethics/). Other potential ethical issues include biased algorithms due to poor training data, privacy and cybersecurity concerns for individuals with increasingly personalized online profiles (e.g. social media, digital goods and services), and the decline of human understanding in decision making processes as interactions between humans and the outside world become more automated [[16]](https://www.forbes.com/sites/nishatalagala/2022/05/31/ai-ethics-what-it-is-and-why-it-matters/?sh=4ef0221a3537).

## References

[See list of all references here](https://laurenstreet.github.io/ai-supply/refs-ai-overview/)