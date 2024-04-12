# Awesome-Continual-Learning-For-LLMs
Following [Wu et al.]([Continual Learning for Large Language Models: A Survey](http://arxiv.org/abs/2402.01364)), this project classifies the work of continual learning for LLMs from the stages of pre-training, instruction tuning and alignment, so as to make it easier for researchers to understand this area.

## Continual Pretrain Learning
- CERT: Continual Pre-Training on Sketches for Library-Oriented Code Generation.(**IJCAI 2022**) [[paper]](https://www.ijcai.org/proceedings/2022/0329.pdf)
- Continual Learning Under Language Shift.(**arXiv 2024**) [[paper]](http://arxiv.org/abs/2311.01200)
- Continual Pre-Training Mitigates Forgetting in Language and Vision.(**SSRN 2023**) [[paper]](https://www.ssrn.com/abstract=4495233)
- Drinking from a firehose: Continual learning with web-scale natural language.(**TPAMI 2022**) [[paper]](https://ieeexplore.ieee.org/abstract/document/9933017/)
- EcomGPT-CT: Continual Pre-training of E-commerce Large Language Models with Semi-structured Data.(**arXiv 2023**) [[paper]](http://arxiv.org/abs/2312.15696)
- Efficient Continual Pre-training for Building Domain Specific Large Language Models.(**arXiv 2023**) [[paper]](http://arxiv.org/abs/2311.08545)
- Ernie 2.0: A continual pre-training framework for language understanding.(**AAAI 2020**) [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6428)
- Exploring Continual Learning for Code Generation Models.(**ACL 2023**) [[paper]](https://aclanthology.org/2023.acl-short.68/)
- Learning to solve NLP tasks in an incremental number of languages.(**ACL 2021**) [[paper]](https://aclanthology.org/2021.acl-short.106/)
- Lifelong Pretraining: Continually Adapting Language Models to Emerging Corpora.(**NAACL 2022**) [[paper]](https://aclanthology.org/2022.naacl-main.351/)
- TemporalWiki: A Lifelong Benchmark for Training and Evaluating Ever-Evolving Language Models. (**EMNLP 2022**) [[paper]](https://aclanthology.org/2022.emnlp-main.418/)
- Towards Continual Knowledge Learning of Language Models. (**ICLR 2022**) [[paper]](https://openreview.net/forum?id=vfsRB5MImo9)
- TRACE: A Comprehensive Benchmark for Continual Learning in Large Language Models. (**arXiv 2023**) [[paper]](http://arxiv.org/abs/2310.06762)

## Continual Instruction Tuning
### Task
- Bayesian Parameter-Efficient Fine-Tuning for Overcoming Catastrophic Forgetting. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2402.12220)
- CITB: A Benchmark for Continual Instruction Tuning. (**EMNLP 2023**) [[paper]](https://aclanthology.org/2023.findings-emnlp.633/)
- ConTinTin: Continual Learning from Task Instructions. (**ACL 2022**) [[paper]](https://aclanthology.org/2022.acl-long.218/)
- Continual Learning for Natural Language Generation in Task-oriented Dialog Systems. (**EMNLP 2020**) [[paper]](https://www.aclweb.org/anthology/2020.findings-emnlp.310)
- Don't Stop Pretraining: Adapt Language Models to Domains and Tasks. (**ACL 2020**) [[paper]](https://aclanthology.org/2020.acl-main.740/)
- Don't Half-listen: Capturing Key-part Information in Continual Instruction Tuning. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2403.10056)
- Exploring the benefits of training expert language models over instruction tuning. (**ICML 2023**) [[paper]](https://proceedings.mlr.press/v202/jang23a.html)
- InsCL: A Data-efficient Continual Learning Paradigm for Fine-tuning Large Language Models with Instructions. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2403.11435)
- Large-scale lifelong learning of in-context instructions and how to tackle it. (**ACL 2023**) [[paper]](https://aclanthology.org/2023.acl-long.703/)
- LFPT5: A Unified Framework for Lifelong Few-Shot Language Learning Based on Prompt Tuning of T5. (**ICLR 2022**) [[paper]](https://openreview.net/pdf?id=HCRVf71PMF)
- LLaMA Pro: Progressive LLaMA with Block Expansion. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2401.02415)
- Orthogonal Subspace Learning for Language Model Continual Learning. (**EMNLP 2023**) [[paper]](https://aclanthology.org/2023.findings-emnlp.715/)
- Rehearsal-free Continual Language Learning via Efficient Parameter Isolation. (**ACL 2023**) [[paper]](https://aclanthology.org/2023.acl-long.612)
- SAPT: A Shared Attention Framework for Parameter-Efficient Continual Learning of Large Language Models. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2401.08295)
- Scalable Language Model with Generalized Continual Learning. (**ICLR 2024**) [[paper]](https://openreview.net/forum?id=mz8owj4DXu)
- Scaling Laws for Forgetting When Fine-Tuning Large Language Models. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2401.05605)
- Understanding Catastrophic Forgetting in Language Models via Implicit Inference. (**ICLR 2024**) [[paper]](https://openreview.net/forum?id=VrHiF2hsrm)

### Domain
- Adapting Large Language Models via Reading Comprehension. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2309.09530)
- ConPET: Continual Parameter-Efficient Tuning for Large Language Models. (**arXiv 2023**) [[paper]](http://arxiv.org/abs/2309.14763)
- How Abilities in Large Language Models are Affected by Supervised Fine-tuning Data Composition. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2310.05492)
- Reformulating Domain Adaptation of Large Language Models as Adapt-Retrieve-Revise. (**arXiv 2023**) [[paper]](http://arxiv.org/abs/2310.03328)
  
### Tool
- Editing Large Language Models: Problems, Methods, and Opportunities. (**EMNLP 2023**) [[paper]](https://aclanthology.org/2023.emnlp-main.632/)
- Genegpt: Augmenting large language models with domain tools for improved access to biomedical information. (**Bioinformatics 2024**) [[paper]](https://doi.org/10.1093/bioinformatics/btae075)
- Llemma: An Open Language Model For Mathematics. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2310.10631)
- TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs. (**arXiv 2023**) [[paper]](http://arxiv.org/abs/2303.16434)
- Toolkengpt: Augmenting frozen language models with massive tools via tool embeddings. (**NIPS 2023**) [[paper]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8fd1a81c882cd45f64958da6284f4a3f-Abstract-Conference.html)
- ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs. (**arXiv 2023**) [[paper]](http://arxiv.org/abs/2307.16789)
  
## Continual Alignment
- COPR: Continual Learning Human Preference through Optimal Policy Regularization. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2310.15694)
- CPPO: Continual Learning for Reinforcement Learning with Human Feedback. (**ICLR 2024**) [[paper]](https://openreview.net/pdf?id=86zAUE80pP)
- Mitigating the Alignment Tax of RLHF. (**arXiv 2024**) [[paper]](https://arxiv.org/abs/2309.06256)

## Early Work about Continual Learning for NLP
- Achieving Forgetting Prevention and Knowledge Transfer in Continual Learning. (**NIPS 2021**) [[paper]](https://openreview.net/pdf?id=RJ7XFI15Q8f)
- Anatomy of Catastrophic Forgetting: Hidden Representations and Task Semantics. (**ICLR 2021**) [[paper]](https://openreview.net/forum?id=LhY8QdUGSuw)
- An Empirical Investigation of the Role of Pre-training in Lifelong Learning. (**JMLR 2021**) [[paper]](http://arxiv.org/abs/2112.09153)
- Catastrophic Forgetting, Rehearsal, and Pseudorehearsal. (**Connection Science 1995**) [[paper]](https://web.archive.org/web/20200222081438id_/http://www.cs.otago.ac.nz/staffpriv/anthony/publications/pdfs/Robins95.pdf)
- Continual learning of a mixed sequence of similar and dissimilar tasks.(**NIPS 2020**) [[paper]](https://proceedings.neurips.cc/paper_files/paper/2020/file/d7488039246a405baf6a7cbc3613a56f-Paper.pdf)
- Continual Learning for Sentence Representations Using Conceptors. (**NAACL 2019**) [[paper]](https://aclanthology.org/N19-1331/)
- Continual Relation Learning via Episodic Memory Activation and Reconsolidation. (**ACL 2020**) [[paper]](https://aclanthology.org/2020.acl-main.573)
- Continual Learning of Knowledge Graph Embeddings. (**RA-L 2021**) [[paper]](https://ieeexplore.ieee.org/abstract/document/9343669/)
- Continual Learning for Named Entity Recognition. (**AAAI 2021**) [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17600)
- Continual Lifelong Learning in Natural Language Processing: A Survey. (**COLING 2020**) [[paper]](https://aclanthology.org/2020.coling-main.574/)
- Continual Learning in Task-Oriented Dialogue Systems. (**ACL 2021**) [[paper]](https://aclanthology.org/2021.emnlp-main.590/)
- Continual Training of Language Models for Few-Shot Learning. (**EMNLP 2022**) [[paper]](https://aclanthology.org/2022.emnlp-main.695/)
- Consistent Representation Learning for Continual Relation Extraction. (**ACL 2022**) [[paper]](http://arxiv.org/abs/2203.02721)
- Class-Incremental Learning with Strong Pre-trained Models. (**CVPR 2022**) [[paper]](https://ieeexplore.ieee.org/document/9878545/)
- Create and Find Flatness: Building Flat Training Spaces in Advance for Continual Learning. (**ECAI 2023**) [[paper]](http://arxiv.org/abs/2309.11305)
- Continual Pre-Training of Large Language Models: How to (re)warm your model?. (**ICML 2023**) [[paper]](https://arxiv.org/abs/2308.04014)
- Continual Pre-Training of Language Models. (**ICLR 2023**) [[paper]](https://openreview.net/pdf?id=m_GDIItaI3o)
- CODA-Prompt: COntinual Decomposed Attention-Based Prompting for Rehearsal-Free Continual Learning. (**CVPR 2023**) [[paper]](https://ieeexplore.ieee.org/document/10204890/)
- Distantly supervised lifelong learning for large-scale social media sentiment analysis.(**CVPR 2023**) [[paper]](https://ieeexplore.ieee.org/document/10204890/)
- Enhancing Lifelong Language Learning by Improving Pseudo-Sample Generation. (**ACL 2022**) [[paper]](https://direct.mit.edu/coli/article/48/4/819/112114/Enhancing-Lifelong-Language-Learning-by-Improving)
- ELLE: Efficient Lifelong Pre-training for Emerging Data. (**ACL 2022**) [[paper]](https://aclanthology.org/2022.findings-acl.220/)
- Episodic Memory in Lifelong Language Learning. (**NIPS 2019**) [[paper]](https://proceedings.neurips.cc/paper_files/paper/2019/file/f8d2e80c1458ea2501f98a2cafadb397-Paper.pdf)
- Fine-tuned Language Models are Continual Learners. (**EMNLP 2022**) [[paper]](https://aclanthology.org/2022.emnlp-main.410)
- How Should Pre-Trained Language Models Be Fine-Tuned Towards Adversarial Robustness? (**NIPS 2021**) [[paper]](https://proceedings.neurips.cc/paper/2021/hash/22b1f2e0983160db6f7bb9f62f4dbb39-Abstract.html)
- Investigating Continual Pretraining in Large Language Models: Insights and Implications. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2402.17400)
- Improving Gender Fairness of Pre-Trained Language Models without Catastrophic Forgetting. (**ACL 2023**) [[paper]](http://arxiv.org/abs/2110.05367)
- LAMOL: Language Modeling for Lifelong Language Learning. (**ICLR 2020**) [[paper]](https://openreview.net/pdf?id=Skgxcn4YDS)
- Lifelong-RL: Lifelong Relaxation Labeling for Separating Entities and Aspects in Opinion Targets. (**EMNLP 2016**) [[paper]](https://aclanthology.org/D16-1022)
- Lifelong Learning for Sentiment Classification. (**ACL 2015**) [[paper]](https://aclanthology.org/D16-1022)
- Lifelong Learning CRF for Supervised Aspect Extraction. (**ACL 2017**) [[paper]](https://aclanthology.org/P17-2023)
- Lifelong Domain Word Embedding via Meta-Learning. (**IJCAI 2018**) [[paper]](https://www.ijcai.org/proceedings/2018/0627.pdf)
- Learning to Prompt for Continual Learning. (**CVPR 2022**) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Learning_To_Prompt_for_Continual_Learning_CVPR_2022_paper.pdf)
- Learn from Yesterday: A Semi-supervised Continual Learning Method for Supervision-Limited Text-to-SQL Task Streams. (**AAAI 2023**) [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26492)
- Meta-Learning Improves Lifelong Relation Extraction. (**RepL4NLP 2019**) [[paper]](https://aclanthology.org/W19-4326)
- Mitigating Catastrophic Forgetting in Large Language Models with Self-Synthesized Rehearsal. (**arXiv 2024**) [[paper]](http://arxiv.org/abs/2403.01244)
- Progressive Prompts: Continual Learning for Language Models. (**NIPS 2023**) [[paper]](http://arxiv.org/abs/2305.10626)
- Prompt Gradient Projection for Continual Learning. (**ICLR 2024**) [[paper]](https://openreview.net/pdf?id=EH2O3h7sBI)
- Recall and Learn: Fine-tuning Deep Pretrained Language Models with Less Forgetting. (**EMNLP 2020**) [[paper]](https://aclanthology.org/2020.emnlp-main.634)
- Rational LAMOL: A Rationale-based Lifelong Learning Framework. (**ACL 2021**) [[paper]](https://aclanthology.org/2021.acl-long.229)
- RecallM: An Adaptable Memory Mechanism with Temporal Understanding for Large Language Models. (**arXiv 2023**) [[paper]](http://arxiv.org/abs/2307.02738)
- Retentive or Forgetful? Diving into the Knowledge Memorizing Mechanism of Language Models. (**arXiv 2023**) [[paper]](http://arxiv.org/abs/2305.09144)
- Sentence Embedding Alignment for Lifelong Relation Extraction. (**NAACL 2019**) [[paper]](https://aclanthology.org/N19-1086/)
- Universal Language Model Fine-tuning for Text Classification. (**ACL 2018**) [[paper]](https://aclanthology.org/P18-1031)
- What Will My Model Forget? Forecasting Forgotten Examples in Language Model Refinement. (**arXiv 2023**) [[paper]](http://arxiv.org/abs/2402.01865)
