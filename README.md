# Awesome-LLM-paper

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/aJupyter/Awesome-LLM-paper)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/aJupyter/Awesome-LLM-paper)

This repository contains papers related to all kinds of LLMs.

We strongly encourage researchers in the hope of advancing their excellent work.

---

## Contents

- [Awesome-LLM-paper](#awesome-llm-paper)
    - [Contents](#contents)
- [Resources](#resources)
    - [Workshops and Tutorials](#workshops-and-tutorials)
- [Papers](#papers)
    - [Survey](#survey)
    - [Benchmark and Evaluation](#benchmark-and-evaluation)
    - [RAG](#rag)
    - [Embedding](#embedding)
    - [LLM](#llm)
    - [Agent](#agent)
    - [Tool Leanrning](#tool-learning)
    - [MMLM](#mmlm)
- [🌟 Contributors](#-contributors)
- [Star History](#star-history)

---

# Resources

## Workshops and Tutorials

<table>
    <tr>
        <th>Theme</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
    </tr>
    <tr>
        <th>……</th>
        <th>……</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">……</td>
    </tr>
</table>

# Papers

## Survey

<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2311.12320">A Survey on Multimodal Large Language Models for Autonomous Driving</a></th>
        <th>arXiv:2311.12320</th>
        <th><a href="https://www.bilibili.com/video/BV14i4y1q74H/?spm_id_from=333.999.0.0">bilibili</a></th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">……</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2312.10997">Retrieval-Augmented Generation for Large Language Models: A Survey</a></th>
        <th>Arxiv2023'Tongji University</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">This paper provides a comprehensive overview of the integration of retrieval mechanisms with generative processes within large language models to enhance their performance and knowledge capabilities.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2311.12320">A Survey on Multimodal Large Language Models for Autonomous Driving</a></th>
        <th>WACV2023'Purdue University</th>
        <th><a href="https://www.bilibili.com/video/BV14i4y1q74H/">Bilibili: MLM for Autonomous Driving Survey</a></th>
        <th><a href="https://purduedigitaltwin.github.io/">Github: MLM for Autonomous Driving Survey</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">This paper provides a comprehensive overview of the integration of retrieval mechanisms with generative processes within large language models to enhance their performance and knowledge capabilities.</td>
    </tr>

</table>

## Benchmark and Evaluation

<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
    </tr>
    <tr>
        <th>……</th>
        <th>……</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">……</td>
    </tr>
</table>

## RAG

<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2401.00368">Improving Text Embeddings with Large Language Models</a></th>
        <th>Arxiv2024'Microsoft</th>
        <th>……</th>
        <th><a href="https://huggingface.co/intfloat/e5-mistral-7b-instruct">Hugging Face: e5-mistral-7b-instruct</a></th>
    </tr>
        <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">Mistral's primary work is achieved through a two-stage prompt process:

1. The first stage generates a pool of candidate tasks through brainstorming prompts.
2. The second stage synthesizes data from the pool of candidate tasks.

The author categorizes tasks into two major types - asymmetric tasks where the retrieved pair consists of a query and a document, differentiated by length into short-long matches, long-short matches, long-long matches, and short-short matches, with a classic example being the search engine scenario.

The paper indicates that large language models (LLMs) can significantly improve the quality of text embeddings, partly due to the synthetic data and partly due to the autoregressive capabilities of the LLMs. Moreover, it can streamline multi-stage embedding tasks into a single-stage fine-tuning (SFT) task, simplifying the training process.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2311.09476">ARES: An Automated Evaluation Framework for Retrieval-Augmented Generation Systems</a></th>
        <th>NAACL 2024</th>
        <th><a href="https://www.bilibili.com/video/BV18H4y1W7GL/">bilibili</a></th>
        <th><a href="https://github.com/stanford-futuredata/ARES">Code: stanford-futuredata/ARES</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">ARES, an Automated RAG Evaluation System, efficiently evaluates retrieval-augmented generation systems across multiple tasks using synthetic data and minimal human annotations, maintaining accuracy even with domain shifts.</td>
    </tr>
</table>

## Embedding

<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
       </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2309.07597">C-Pack: Packaged Resources To Advance General Chinese Embedding</a></th>
        <th>Arxiv2023'BAAI</th>
        <th><a href="https://www.bilibili.com/video/BV1VN4y1q7Zt/?spm_id_from=333.337.search-card.all.click&vd_source=7830a50943e3cd844c66dc7aca159592">Bilibili: C-Pack</a></th>
        <th><a href="https://github.com/FlagOpen/FlagEmbedding">Github: C-Pack</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">BAAI and Huggingface introduce C-Pack which is an advanced model for Chinese embeddings, significantly outperforming existing models and includes comprehensive benchmarks, a massive dataset, and a range of models.
BAAI 联合Huggingface 推出的 C-Pack，主打中文嵌入，性能明显优于现有模型，包括全面的基准测试、大规模数据集和多种模型。


</td>
    </tr>
</table>

## LLM

<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
       </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2307.09288">Llama 2: Open Foundation and Fine-Tuned Chat Models</a></th>
        <th>Arxiv2023'Meta</th>
        <th><a href="https://www.bilibili.com/video/BV1YK411x7DF/?spm_id_from=333.337.search-card.all.click">bilibili</a></th>
        <th><a href="https://github.com/meta-llama/llama">Github: Llama</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">The technical report of Llama 2 from Meta Which is one of the top leaders of the LLMs open-sourced community. The greatest contribution of Llama 2 is the development of a range of pretrained and fine-tuned large language models (LLMs) that not only outperform existing open-source chat models on various benchmarks but are also optimized for dialogue scenarios. Additionally, these models have shown excellent performance in human evaluations of helpfulness and safety, potentially serving as effective substitutes for closed-source models. The Llama 2 project also provides a detailed description of the fine-tuning process and safety enhancements, aimed at fostering further development by the community and contributing to the responsible development of large language models.

本论文是Llama 2 模型发布的技术报告，来自全球最主要的大模型开源领袖之一 Meta。Llama 2的最大贡献是开发了一系列预训练和微调的大型语言模型（LLM），这些模型不仅在多个基准测试中优于现有的开源聊天模型，而且还经过优化，特别适用于对话场景。此外，这些模型在人类评估的帮助性和安全性方面表现出色，可能成为闭源模型的有效替代品。Llama 2项目还提供了对微调过程和安全性提升的详细描述，旨在促进社区基于此工作进一步发展，贡献于负责任的大型语言模型的开发。 </td>
    </tr> 
    <tr>
        <th><a href="https://arxiv.org/abs/2402.08562">Higher Layers Need More LoRA Experts</a></th>
        <th>Arxiv2024'Northwestern University</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">In deep learning models, higher layers require more LoRA (Low-Rank Adaptation) experts to enhance the model’s expressive power and adaptability.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2310.06839">LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression</a></th>
        <th>Arxiv2023'Microsoft</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">To accelerate and enhance the performance of large language models (LLMs) in handling long texts, compressing prompts can be an effective method.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2401.13275">Can AI Assistants Know What They Don't Know?</a></th>
        <th>Arxiv2024'Fudan University</th>
        <th>……</th>
        <th><a href="https://github.com/OpenMOSS/Say-I-Dont-Know">Code: Say-I-Dont-Know</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">The paper explores if AI assistants can identify when they don't know something, creating a "I don't know" dataset to teach this, resulting in fewer false answers and increased accuracy.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2308.12950">Code Llama: Open Foundation Models for Code</a></th>
        <th>Arxiv2023'Meta AI</th>
        <th><a href="https://www.bilibili.com/video/BV1YK411x7DF/?spm_id_from=333.788&vd_source=399f12e8692030e26d7132fc951d78d3">bilibili</a></th>
        <th><a href="https://github.com/meta-llama/codellama">codellama</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">The article introduces Code Llama, a family of large programming language models developed by Meta AI, based on Llama 2, designed to offer state-of-the-art performance among open models, support large input contexts, and possess zero-shot instruction following capabilities for programming tasks.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2304.15004">Are Emergent Abilities of Large Language Models a Mirage?</a></th>
        <th>NIPS2023'Stanford University</th>
        <th><a href="https://www.bilibili.com/video/BV1qK411e7aY/?spm_id_from=333.788&vd_source=399f12e8692030e26d7132fc951d78d3">bilibili</a></th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">The article challenges the notion that large language models (LLMs) exhibit "emergent abilities," suggesting that these abilities may be an artifact of the metrics chosen by researchers rather than inherent properties of the models themselves. Through mathematical modeling, empirical testing, and meta-analysis, the authors demonstrate that alternative metrics or improved statistical methods can eliminate the perception of emergent abilities, casting doubt on their existence as a fundamental aspect of scaling AI models.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2312.06109">Vary: Scaling up the Vision Vocabulary for Large Vision-Language Models</a></th>
        <th>Arxiv2023'MEGVII Technology</th>
        <th>……</th>
        <th><a href="https://varybase.github.io/">VaryBase</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">The article introduces Vary, a method for expanding the visual vocabulary of Large Vision-Language Models (LVLMs) to enhance dense and fine-grained visual perception capabilities for specific visual tasks, such as document-level OCR or chart understanding.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/1908.10084">Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks</a></th>
        <th>Arxiv2019'UKP Lab</th>
        <th><a href="https://www.bilibili.com/video/BV1Eg4y1U7Nh/?spm_id_from=333.788&vd_source=399f12e8692030e26d7132fc951d78d3">bilibili</a></th>
        <th><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">The paper introduces Sentence-BERT (SBERT), a modification of the BERT network that employs siamese and triplet network structures to produce semantically meaningful sentence embeddings that can be compared using cosine similarity, thereby significantly enhancing the efficiency of sentence similarity search and clustering tasks.</td>
        <tr>
        <th><a href="https://arxiv.org/abs/2401.04088">Mixtral of Experts</a></th>
        <th>Arxiv2019'UKP Lab</th>
        <th>……</th>
        <th><a href="https://github.com/mistralai/mistral-src">Mixtral of Experts</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">Mixtral is a model based on the Transformer architecture with two key differences:

1. Mixtral supports a full dense context length of up to 32,000 tokens;
2. It utilizes a Mixture of Experts (MoE) layer instead of the traditional feedforward network blocks.

The model is similar to the Mistral 7B architecture, but each layer includes eight feedforward units ("experts"). During processing, a routing network at each layer selects two "experts" to handle and merge the output for each token. Although only two experts’ data are processed per token, different experts may be chosen at each timestep. As a result, while each token has access to 47B parameters, only 13B active parameters are used during inference. Mixtral was trained with a context range of 32k tokens and has outperformed or matched the Llama 2 70B and GPT-3.5 in benchmarks, particularly excelling in mathematics, code generation, and multilingual tasks. Additionally, a specially tuned model—Mixtral 8x7B – Instruct—has surpassed human benchmark models including GPT-3.5 Turbo, Claude-2.1, Gemini Pro, and Llama 2 70B chat models.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/pdf/2404.04167">Chinese Tiny LLM: Pretraining a Chinese-Centric Large Language Model</a></th>
        <th></th>
        <th></th>
        <th>https://github.com/Chinese-Tiny-LLM/Chinese-Tiny-LLM</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">本研究介绍了CT-LLM，一个优先考虑中文的大型语言模型（LLM），使用12000亿标记的大型语料库，其中8000亿为中文标记。CT-LLM通过从头开始并主要使用中文数据，展现了在理解和处理中文方面的卓越能力，同时通过对齐技术进一步提升。该模型在CHC-Bench上表现出色，在中文任务中表现优异，并展示了其在英语任务中的熟练程度。本研究挑战了主要使用英语语料库训练LLM的现有方法，开辟了新的训练方法视野。通过开源完整的训练过程和相关资源（如MAP-CC和CHC-Bench），我们希望促进学术界和工业界的进一步探索和创新，推动更包容和多功能的语言模型的发展。</td>
    </tr>
        </tr>
        <tr>
        <th><a href="https://arxiv.org/pdf/2207.07061">Confident Adaptive Language Modeling</a></th>
        <th>Source</th>
        <th></th>
        <th>Other</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">近年来，基于Transformer的大型语言模型（LLM）在许多任务上取得了显著性能提升，但这些进步伴随着模型规模和推理时间成本的增加。实际上，LLM生成的序列包含不同难度级别的任务，一些预测需要模型的全部计算能力，而其他预测则可以用较少的计算资源完成。在本研究中，我们提出了自信自适应语言建模（CALM）框架，该框架根据输入和生成时间步骤动态分配计算资源。我们解决了早期退出解码的挑战，包括置信度衡量标准、将序列级约束连接到每个token的退出决策以及处理由于早期退出导致的隐藏表示缺失。通过理论分析和实验证明，该框架在保持高性能的同时，可将计算量减少至3倍。</td>
    </tr>


</table>

## Fine-tuning

<table>
    <tr>
        <th><a href="https://arxiv.org/abs/2110.04366">Towards a Unified View of Parameter-Efficient Transfer Learning</a></th>
        <th>ICLR2022'Carnegie Mellon University</th>
        <th>……</th>
        <th><a href="https://github.com/jxhe/unify-parameter-efficient-tuning">unify-parameter-efficient-tuning</a></th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">This paper presents a unified framework for understanding and improving various parameter-efficient transfer learning methods by modifying specific hidden states in pre-trained models, defining a set of design dimensions to differentiate between methods, and experimentally demonstrating the framework's ability to identify important design choices in previous methods and instantiate new parameter-efficient tuning methods that are more effective with fewer parameters.</td>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2305.14314">QLoRA: Efficient Finetuning of Quantized LLMs</a></th>
        <th>NeurIPS2023'University of Washington</th>
        <th><a href="https://www.bilibili.com/video/BV1MH4y1Y7wW?p=6&vd_source=7830a50943e3cd844c66dc7aca159592">bilibili</a></th>
        <th><a href="https://github.com/artidoro/qlora">Github: QLoRA</a></th>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">This paper introduces QLoRA, a method for fine-tuning LLMs that significantly reduces memory usage. QLoRA achieves this by:

- Using a new data type called 4-bit NormalFloat (NF4) for weights, which is efficient for storing normally distributed weight values.
- Applying "double quantization" to compress the size of quantization constants. 
- Employing "paged optimizers" to manage memory spikes during training.

这篇论文提出了一种名为 QLoRA 的大型语言模型的方法，可以显著降低内存使用量。QLoRA 通过以下方式实现这一点：

- 使用一种名为 4-bit NormalFloat (NF4) 的新数据类型来存储权重，该数据类型对存储服从正态分布的权重值非常有效。
- 应用“双量化”来压缩量化常数的尺寸。
- 采用“分页优化器”来管理训练过程中的内存峰值。

这些创新使 QLoRA 能够在内存有限的单个 GPU (48GB) 上微调大型模型 (例如，65B 参数)。 训练出的模型在聊天机器人基准测试上实现了最先进的性能，甚至在某些情况下超过了 ChatGPT 等先前模型的性能。</td>
    </tr>
        <tr>
        <th><a href="https://arxiv.org/abs/2101.00190">Prefix-Tuning: Optimizing Continuous Prompts for Generation</a></th>
        <th>ArXive2021'Stanford University</th>
        <th><a href="https://www.bilibili.com/video/BV1MH4y1Y7wW?p=2&vd_source=7830a50943e3cd844c66dc7aca159592">bilibili</a></th>
        <th>...</th>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">This paper introduces prefix-tuning, a lightweight alternative to fine-tuning for natural language generation tasks. Unlike fine-tuning, which modifies all language model parameters, prefix-tuning keeps them frozen and optimizes a small continuous task-specific vector (called the prefix). This allows prefix-tuning to be more efficient than fine-tuning, especially in low-data settings.

这篇论文提出了一种名为“前缀微调”的轻量级替代微调的方法，用于自然语言生成任务。与微调修改所有语言模型参数不同，前缀微调保持参数冻结，并优化一个小的连续任务特定向量 (称为前缀)。这使得前缀微调比微调更有效，尤其是在数据量较小的背景下。</td>
    <tr>
        <th><a href="https://arxiv.org/abs/2110.07602">P-Tuning v2: Prompt Tuning Can Be Comparable to Fine-tuning Universally Across Scales and Tasks</th>
        <th>ACL2022'Tsinghua University</th>
        <th>……</th>
        <th><a href="https://github.com/THUDM/P-tuning-v2">Github: </th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">The author introduces P-tuning v2, which utilizes deep prompt optimization techniques, such as Prefix Tuning, to improve upon Prompt Tuning and P-Tuning as a universal solution across scales and NLU tasks. Compared to P-tuning, this method incorporates prompt tokens at every layer rather than just at the input layer, bringing two main benefits:

1. More learnable parameters (increasing from 0.01% in P-tuning and Prompt Tuning to 0.1%-3%), while still being efficient.
2. Embedding prompts into deeper structural layers has a more direct impact on model predictions. </td>
    </tr>
</table>

## Prompt/Context

<table>
    </tr>
        <tr>
        <th><a href="https://arxiv.org/abs/2305.14160">Label Words are Anchors: An Information Flow Perspective for Understanding In-Context Learning</a></th>
        <th>EMNLP2023'Peking University</th>
        <th><a href="https://www.bilibili.com/video/BV13w411G7HQ/?spm_id_from=333.337.search-card.all.click&vd_source=7830a50943e3cd844c66dc7aca159592">bilibili</a></th>
        <th><a href="https://github.com/lancopku/label-words-are-anchors">Github: ICL</th>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">This paper sheds light on the inner workings of in-context learning (ICL) in LLMs.  While ICL has shown promise in enabling LLMs to perform various tasks through demonstrations, the mechanism behind this learning has been unclear.  The authors investigate this mechanism through the lens of information flow and discover that labels in the demonstrations act as anchors.  These labels serve two key functions: 1) During initial processing, semantic information accumulates within the representations of these label words. 2) This consolidated information acts as a reference point for the LLMs' final predictions.  Based on these findings, the paper introduces three novel contributions: 1) An anchor re-weighting method to enhance ICL performance, 2) A demonstration compression technique to improve efficiency, and 3) An analysis framework to diagnose ICL errors in GPT2-XL.  The effectiveness of these contributions validates the proposed mechanism and paves the way for future research in ICL.

这篇论文通过信息流视角揭示了大型语言模型 (LLM) 中的上下文学习 (ICL) 的内部工作原理。虽然 ICL 在通过演示让大型语言模型执行各种任务方面表现出潜力，但其背后的学习机制一直不清楚。作者通过信息流的视角研究了这种机制，并发现演示中的标签充当锚点作用。这些标签具有两个关键功能：1) 在初始处理过程中，语义信息会累积在这些标签词的表征中。2) 这种整合的信息作为大型语言模型最终预测的参考点。基于这些发现，论文提出了三项原创贡献：1) 提高 ICL 性能的锚点重新加权方法，2) 提高推理效率的演示压缩技术，3) 用于诊断 GPT2-XL 中 ICL 错误的分析框架。这些贡献的有效性验证了所提出的机制，并为 ICL 的未来研究铺平了道路。。</td>
    </tr>

</table>



## Ad click prediction 
</table>
    </tr>
        <tr>
        <th><a href="https://arxiv.org/pdf/1708.05123">Deep & Cross Network for Ad Click Predictions</a></th>
        <th>Source</th>
        <th></th>
        <th>Other</th>
    </tr>
    <tr>
        <th>……</th>
        <th>……</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">特征工程对于预测模型的成功至关重要，但常常需要手动操作或详尽搜索。尽管DNN能够自动学习特征交互，但在所有类型的特征交互中效率不高。本文提出了深度与交叉网络（DCN），该网络在保留DNN优势的同时，引入了高效学习特定特征交互的新型交叉网络。DCN在每层显式进行特征交叉，无需手动特征工程，并且增加的复杂性极小。实验结果显示，DCN在CTR预测和密集分类数据集上的模型准确性和内存使用均优于现有最先进算法。</td>
    </tr>

</table>

## Agent

<table>
    <tr>
        <th><a href="https://arxiv.org/pdf/2307.07924">ChatDev: Communicative Agents for Software Development</a></th>
        <th>Source</th>
        <th>https://github.com/OpenBMB/ChatDev</th>
        <th>Other</th>
    </tr>
    <tr>
        <th>……</th>
        <th>……</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">软件开发是一个需要多种技能协同的复杂任务。传统深度学习方法在瀑布模型的不同阶段（如设计、编码和测试）中存在技术不一致性，导致开发过程低效。本文提出了ChatDev，一个由大型语言模型驱动的聊天式软件开发框架，利用自然语言和编程语言的统一沟通方式，促进多代理系统在设计、编码和测试阶段的协作，提高了开发效率。ChatDev通过多轮对话生成解决方案，展示了语言作为多代理协作的桥梁的潜力</td>

</table>

## Tool Learning

<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
    </tr>
    <tr>
        <th>……</th>
        <th>……</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">……</td>
    </tr>
</table>

## MMLM

<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
    </tr>
    <tr>
        <th>……</th>
        <th>……</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">……</td>
    </tr>
</table>

## Reinforcement Learning

<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/abs/2208.06193">Diffusion Policies as an Expressive Policy Class for Offline Reinforcement Learning</a></th>
        <th>ICLR2023</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">Diffusion strategies, as a highly expressive class of policies, are used in offline reinforcement learning scenarios to improve learning efficiency and decision-making performance.</td>
    </tr>
</table>
<table>
    <tr>
        <th>Paper</th>
        <th>Source</th>
        <th>Link</th>
        <th>Other</th>
    </tr>
    <tr>
        <th><a href="https://arxiv.org/pdf/2301.12050">Do Embodied Agents Dream of Pixelated Sheep?: Embodied Decision Making using Language Guided World Modelling</a></th>
        <th>ICLR2023</th>
        <th>……</th>
        <th>……</th>
    </tr>
    <tr>
        <th colspan="1">Descriptions</th>
        <td colspan="3">强化学习（RL）代理通常没有先验知识，从零开始学习。我们提出使用少量样本的大型语言模型（LLMs）来假设并验证一个抽象世界模型（AWM），以提高RL代理的样本效率。DECKARD代理在Minecraft中进行物品制作，通过两个阶段实现：Dream阶段，代理利用LLM将任务分解为子目标形成AWM；Wake阶段，代理为每个子目标学习策略并验证AWM。这种方法不仅显著提高了样本效率，还能纠正LLM中的错误，成功结合LLMs的噪声信息与环境动态中的知识。</td>
    </tr>
</table>


# 🌟 Contributors

<a href="https://github.com/aJupyter/Awesome-LLM-paper/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=aJupyter/Awesome-LLM-paper" />
</a>

# Star History

[![Star History Chart](https://api.star-history.com/svg?repos=aJupyter/Awesome-LLM-paper&type=Date)](https://star-history.com/#aJupyter/Awesome-LLM-paper&Date)
