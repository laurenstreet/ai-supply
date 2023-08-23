---
title: "Artificial Intelligence (AI) Overview"
permalink: /ai-overview/
date: 2023-08-23
tags:
  - overview
---

Some common stories are that the idea of AI began in the 1950s [[1]](https://academic.oup.com/mind/article/LIX/236/433/986238?login=false) [[2]](https://aisb.org.uk/what-is-ai/), or actually long ago as seen in ancient myths [[3]](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/1848).  

AI seems to be defined, more or less, as a program with any human reasoning skills, which encompasses quite a lot.  A common way to break down AI is through a hiercharical representation including the structures within AI [[4]](https://www.datacamp.com/blog/how-to-learn-ai) [[5]](https://realpython.com/python-ai-neural-network/)

![Common representation of AI, DL, and ML](https://github.com/laurenstreet/ai-supply/blob/main/assets/images/AI-ML-DL.png?raw=true "Common representation of AI, DL, and ML")

Another common way to categorize AI is by its performance related to humans [[4]](https://www.datacamp.com/blog/how-to-learn-ai) [[6]](https://www.coursera.org/articles/what-is-artificial-intelligence):

1. Artificial narrow intelligence (ANI): designed to perform singular tasks, can potentially simulate human behavior based on set of rules but has limited understanding of the world around it 
2. Artificial general intelligence (AGI): performs tasks on par with a human with the ability to understand the world around them as a human does
3. Artificial super intelligence (ASI): outperforms human level skills with a superior understanding of the world around them compared to humans

ANI and AGI are also commonly broken down into further categories defined by Arend Hintze [[7]](https://www.govtech.com/computing/understanding-the-four-types-of-artificial-intelligence.html#:~:text=There%20are%20four%20types%20of,of%20mind%20and%20self%2Dawareness.) [[6]](https://www.coursera.org/articles/what-is-artificial-intelligence) [[8]](https://www.coursera.org/articles/types-of-ai)

1. Reactive machines
    - Subset of ANI
    - No learning from previous actions, only reacts to stimuli
    - Example: IBM's chess playing AI, Deep Blue, made predictions for next possible moves, but didn't learn from past moves

2. Limited memory machines
    - Subset of ANI
    - Limited ability to learn from past events
    - Example: Self driving cars use a set of rules (e.g. knowledge of traffic signs, etc.) combined with observations of events in their enviroment (e.g. other cars around) to make decisions (e.g. steering and speed adjustment)
3. Theory of mind machines
    - Subset of ANI, almost AGI
    - Limited ability to learn from past events as well as to understand the desires of other entities and how they can be affected 
    - Example: Lack of benchmark tests [[9]](https://arxiv.org/abs/2303.11594) but possibly some large language models [[10]](https://arxiv.org/abs/2302.02083)
4. Self-aware machines
    - Truly AGI
    - Ability to learn from past events, to understand the desires of other entities and how they can be affected, and the ability to be understand themself
    - Example: None yet

With the increase of AI in our everyday lives comes the onset of responsibilities that can either be taken or shunned.  For quick dives into common AI ethics problems see [[6]](https://www.coursera.org/articles/what-is-artificial-intelligence) [[11]](https://www.coursera.org/articles/ai-ethics).  Some recent and commonly cited ethical problems concern AI algorithms that can generate content like text, images, and audio.  This type of AI can be used to spread misinformation [[12]](https://arxiv.org/abs/2305.00944), while the data these algorithms are trained on can lead to privacy concerns and potential theft of intellectual property [[13]](https://www.washingtonpost.com/technology/2022/12/09/chatgpt-lensa-ai-ethics/). Other potential ethical issues include biased algorithms due to poor training data, privacy and cybersecurity concerns for individuals with increasingly personalized online profiles (e.g. social media, digital goods and services), and the decline of human understanding in decision making processes as interactions between humans and the outside world become more automated.

## References

[[1]](https://academic.oup.com/mind/article/LIX/236/433/986238?login=false) Computing Machinery and Intelligence, A. M. Turing (1950)

[[2]](https://aisb.org.uk/what-is-ai/) "What is AI?" The Society for the Study of Artificial Intelligence and Simulation of Behavior (2014)

[[3]](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/1848) A (Very) Brief History of Artificial Intelligence, Bruce G. Buchanan (2005)

[[4]](https://www.datacamp.com/blog/how-to-learn-ai)  "How to Learn AI From Scratch in 2023: A Complete Guide From the Experts," DataCamp (2023)

[[5]](https://realpython.com/python-ai-neural-network/) "Python AI: How to Build a Neural Network & Make Predictions," RealPython

[[6]](https://www.coursera.org/articles/what-is-artificial-intelligence) "What is Artificial Intelligence? Definition, Uses, and Types," Coursera (2023)

[[7]](https://www.govtech.com/computing/understanding-the-four-types-of-artificial-intelligence.html#:~:text=There%20are%20four%20types%20of,of%20mind%20and%20self%2Dawareness.) 
"Understanding the Four Types of Artificial Intelligence," Goverment Technology (2016)

[[8]](https://www.coursera.org/articles/types-of-ai) "4 Types of AI: Getting to Know Artificial Intelligence," Coursera (2023)

[[9]](https://arxiv.org/abs/2303.11594) A Review on Machine Theory of Mind, Yuanyuan Mao, Shuang Liu, Pengshuai Zhao, Qin Ni, Xin Lin, and Liang He 

[[10]](https://arxiv.org/abs/2302.02083) Theory of Mind May Have Spontaneously Emerged in Large Language Models, Michal Kosinski

[[11]](https://www.coursera.org/articles/ai-ethics) "AI Ethics: What It Is and Why It Matters," Coursera (2023)

[[12]](https://arxiv.org/abs/2305.00944) Poisoning Language Models During Instruction Tuning, Alexander Wan, Eric Wallace, Sheng Shen, and Dan Klein

[[13]](https://www.washingtonpost.com/technology/2022/12/09/chatgpt-lensa-ai-ethics/) "A guide to the sticky ethics of fun AI tools," Washington Post (2022)