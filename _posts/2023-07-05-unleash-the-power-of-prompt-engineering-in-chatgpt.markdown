---
layout: post
title:  "Unleash the Power of Prompt Engineering in ChatGPT - A Simple Guide"
date:   2023-07-05 12:22:06 +0800
categories: ChatGPT
tags: ChatGPT PromptEngineering
img: https://cdn.pixabay.com/photo/2018/05/11/09/02/technology-3389904_1280.jpg
describe: A prompt is the text-based input given to natural language AI models to perform tasks. Prompt engineering is a sophisticated natural language processing (NLP) technique that enables users to elicit desired replies from language models such as ChatGPT.
---

## Background
Recently (28 May - 5 June), I had the opportunity to attend BuildingBloCS' June Conference on AI, a captivating event that delved into the exciting realm of artificial intelligence. I was able to immerse myself in a wealth of knowledge, from the intriccacies of prompt engineering to gaining deeper insights to different python libraries like Numpy, Tensorflow, Sklearn and more. This conference equipped me with a diverse set of AI skills, and inspired it, I would like to share my insights on prompt engineering in this blog post.

## Terms

### Prompt
A prompt is the text-based input given to natural language AI models to perform tasks. Prompt engineering is a sophisticated natural language processing (NLP) technique that enables users to elicit desired replies from language models such as ChatGPT.

### Temperature
The Temperature parameter controls the randomness of the predictions(output). The higher the temperature, the more likely the model is to sample unlikely tokens (more diverse and creative). The lower the temperature, the more likely the model is to produce more focused and predictable outputs.

### Frequency
The frequency parameter controls the number of occurence of certain phrases or information in the prompt. It can be used to encourage the model to prioritise certain information over others. Conversely, it can also be used to discourage the model from using certain information, minimising their impact on the output.

## Prompt Engineering Techniques
With the jargon out of the way, let's dive into the different prompt engineering techniques :D

1. Context Setting
Context setting involves providing a brief introduction to the topic of the prompt. This allows the model to understand the context of the prompt, and generate more relevant responses.

For instance, we can use a prompt like:

``` 
"Pretend that you are an cybersecurity researcher. You are tasked to write a report on a prominent cyber attack. Write a report on the cyber attack."
``` 

2. Answer Format
Answer format involves providing a desired format or sample answer to the prompt. This allows the model to understand the format of the answer, and generate more relevant responses.

For instance, we can use prompts like:

```
"List the top 3 cyber attacks in 2020."
```

```
"In bullet points, explain the typical steps performed by a threat actor in a cyber attack."
```

3. Temperature Control
As mentioned under the terms section, temperature controls the randomness of the model's predictions or output.

For instance, we can use prompts like:

```
"Tell me a joke about computers. Generate a response with a temperature setting of 0.8."
```

```
"Generate a report on computer security with a temperature setting of 0.2."
```

By setting a higher temperature (0.8), the model will produce more diverse and creative jokes about computers, resulting in potentially more imaginative and amusing responses.
Conversely, by setting a lower temperature (0.2), the model will produce more focused and predictable reports on computer security.

4. Frequency Adjustment
Also with reference to the terms section, frequency allows users to control the occurence of phrases in the prompt to encourage or discourage the model from focusing on certain information.

For example, we can use prompts like:

```
"Generate a report on the top 3 cyber attacks in 2020. The report should mention the SolarWinds attack more than 3 times."
```

```
"Provide a summary of discoveries made by cybersecurity researchers in 2010, with a reduced frequency of technical jargon."
```

## Prompt Optimisation
### Experimentation
Prompt engineering often involves an iterative process of experimentation and refinement. Hence, users would have to experiment with different prompts and settings to achieve the desired results. By observing the model's responses, users can then refine their prompts and settings accordingly.

## Conclusion
While prompt engineering can be used to empower users to elicit desired responses from language models, it is not a silver bullet. It is not a replacement for human intelligence, and should be used to complement it. Users should also be aware of the ethical considerations such as bias and misinformation that may arise from the use of prompt engineering. As research in this field advances, we can expect that prompt engineering will continue to evolve and provide us users with more control and customisations. By leveraging on the power of prompt engineering, we can harness the power of language models to generate meaningful and relevant responses to our prompts. However, it is crucial to use this power responsibly and with a critical eye towards ensuring accurate and unbiased information.

## References:

1. Wankhede, C. (2023). What is prompt engineering and how does it work? Android Authority. 2. Sarah P. Grant (May, 2023). What is prompt engineering? Zapier 3. Prompt Engineering Guide - Nextra. (n.d.).