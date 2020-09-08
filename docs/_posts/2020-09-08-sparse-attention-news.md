---
layout: single
title: "Powering 10x longer sequences and 6x faster execution through DeepSpeed Sparse Attention"
excerpt: ""
categories: news
new_post: true
date: 2020-09-09 00:00:00
---

DeepSpeed offers sparse attention kernels, an instrumental technology to support long sequences of model inputs, whether for text, image, or sound. Compared with the classic dense Transformers, it powers an order-of-magnitude longer input sequence and obtains up to 6x faster execution with comparable accuracy. It also outperforms state-of-the-art sparse implementations with 1.5-3x faster execution. Furthermore, our sparse kernels support efficient execution of flexible sparse format and empower users to innovate on their custom sparse structures.

* Brief overview, see our [press release](https://www.microsoft.com/en-us/research/blog/TODO-PR-DeepSpeed-V3/).
* Detailed technology deep dive, see our [blog post](https://www.deepspeed.ai/news/2020/09/08/sparse-attention.html).
* Tutorial on how to reproduce our results, see our [Sparse attention tutorial](https://www.deepspeed.ai/tutorials/sparse-attention/).
* The source code for our transformer kernels can be found in the [DeepSpeed repo](https://github.com/microsoft/deepspeed) and BERT pre-training code can be found in the [DeepSpeedExamples repo](https://github.com/microsoft/deepspeedexamples).