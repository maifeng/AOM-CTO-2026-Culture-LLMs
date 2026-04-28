 # **Dissecting Corporate Culture with Large Language Models**

## Feng Mai (University of Iowa) 

### AOM CTO 2026 · Computational Methods Workshop


feng-mai@uiowa.edu

April 28,  2026

Part of the Academy of Management Communication, Digital Technology, and Organization (CTO) Division online workshop series

---

## Part 1: Slides

[**Dissecting Corporate Culture with Large Language Models** (PDF, 7 MB)](Dissecting-Corporate-Culture-with-LLMs-Mai-2026.pdf)

The conceptual half (Part 1) walks through three generations of text-as-data for measuring corporate culture: word2vec, SPAR (sentence embeddings + semantic projection), and generative-AI extraction. Part 2 is live coding in Colab using the three packages below.

---

## Part 2: Live Colab notebooks

If you have not used Google Colab before, see [this link for a short tutorial](https://www.marqo.ai/blog/getting-started-with-google-colab-a-beginners-guide).

| Package | What it does | Paper | Open in Colab |
|---|---|---|---|
| [`lmsy_w2v_rfs`](https://github.com/maifeng/lmsy_w2v_rfs) | Trains word2vec on your own corpus, then expands a handful of seed words (*integrity*, *teamwork*, ...) into a domain-specific dictionary, and scores documents by weighted term frequency. | Li, Mai, Shen, Yan (2021), *RFS* | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maifeng/lmsy_w2v_rfs/blob/main/notebooks/01_quickstart_colab.ipynb) |
| [`spar_measure`](https://github.com/maifeng/SPAR_measure) | Embeds documents with a pretrained transformer, then projects them onto theoretical concept axes defined by a few seed sentences. Active retrieval surfaces in-corpus exemplars so each scale is grounded in the domain. | Yan, Mai, Wu, Chen, Li (2024), *ISR* | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maifeng/SPAR_measure/blob/master/resources/example_colab.ipynb) |
| [`lmsyz_genai_ie_rfs`](https://github.com/maifeng/lmsyz_genai_ie_rfs) | Efficient LLM-based information extraction over a DataFrame: pass a prompt, get back a structured DataFrame. | Li, Mai, Shen, Yang, Zhang (2026), *RFS* | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maifeng/lmsyz_genai_ie_rfs/blob/main/notebooks/01_quickstart.ipynb) |

---

## Three focal papers

The workshop walks through these papers in order:

1. **Li, Kai, Feng Mai, Rui Shen, and Xinyan Yan (2021).** *Measuring Corporate Culture Using Machine Learning.* Review of Financial Studies 34(7): 3265-3315. [https://doi.org/10.1093/rfs/hhaa079](https://doi.org/10.1093/rfs/hhaa079)

2. **Yan, Bei, Feng Mai, Chaojiang Wu, Rui Chen, and Xiaolin Li (2024).** *A Computational Framework for Understanding Firm Communication During Disasters.* Information Systems Research 35(2): 590-608. [https://doi.org/10.1287/isre.2022.0128](https://doi.org/10.1287/isre.2022.0128)

3. **Li, Kai, Feng Mai, Rui Shen, Chelsea Yang, and Tengfei Zhang (2026).** *Dissecting Corporate Culture Using Generative AI.* Review of Financial Studies 39(1): 253-296. [https://doi.org/10.1093/rfs/hhaf081](https://doi.org/10.1093/rfs/hhaf081)

**Download all three (PDF):** [Dropbox folder](https://www.dropbox.com/scl/fo/whlma39wm29uagajqmh30/AIYvtdya8Ie3jfeT-V1LhMk?rlkey=ki7cpwt66es282amu35w043de&dl=0)
