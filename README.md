# Truth Forest: Toward Multi-Scale Truthfulness in Large Language Models through Intervention without Tuning

This repository contains the source code for the paper titled "Truth Forest: Toward Multi-Scale Truthfulness in Large Language Models through Intervention without Tuning" 

**NEWS**: Our paper has been accepted as AAAI2024! We are currently working on code, thanks for your patience. :)

## Abstract

> Despite the great success of Large Language Models (LLMs) in various tasks, they suffer from generating hallucinations. We introduce Truth Forest, a method that enhances truthfulness in LLMs by uncovering hidden truth representations using multi-dimensional orthogonal probes. Specifically, it creates multiple orthogonal bases for modeling truth by incorporating orthogonal constraints into the probes. Moreover, we introduce Random Peek, a systematic technique that considers an extended range of positions within the sequence, reducing the gap between discerning and generating truth features in LLMs. By employing this approach, we improved the truthfulness of Llama-2-7B from 40.8\% to 74.5\% on TruthfulQA. Likewise, significant improvements are observed in fine-tuned models, such as Alpaca, Vicuna, and Llama 2-Chat. We conducted a thorough analysis of truth features using probes. Our visualization results show that orthogonal probes capture complementary truth-related features, forming well-defined clusters that reveal the inherent structure of the dataset. 

