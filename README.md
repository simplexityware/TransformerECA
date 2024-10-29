# Learning Elementary Cellular Automata with Transformers

Code for _Burtsev, Mikhail. "[Learning Elementary Cellular Automata with Transformers](https://openreview.net/forum?id=rROdzn4DSb)." In [The 4th Workshop on Mathematical Reasoning and AI at NeurIPS'24](https://mathai2024.github.io/)._

_Keywords_: Transformers, Elementary Cellular Automata, Rule Abstraction, Planning

**TL;DR**: Transformers can learn to generalize the local rules of Elementary Cellular Automata.

## Abstract:

Large Language Models demonstrate remarkable mathematical capabilities but at the same time struggle with abstract reasoning and planning. In this study, we explore whether Transformers can learn to abstract and generalize the rules governing Elementary Cellular Automata. By training Transformers on state sequences generated with random initial conditions and local rules, we show that they can generalize across different Boolean functions of fixed arity, effectively abstracting the underlying rules. While the models achieve high accuracy in next-state prediction, their performance declines sharply in multi-step planning tasks without intermediate context. Our analysis reveals that including future states or rule prediction in the training loss enhances the models' ability to form internal representations of the rules, leading to improved performance in longer planning horizons and autoregressive generation. Furthermore, we confirm that increasing the model's depth plays a crucial role in extended sequential computations required for complex reasoning tasks. This highlights the potential to improve LLM with inclusion of longer horizons in loss function, as well as incorporating recurrence and adaptive computation time for dynamic control of model depth.

