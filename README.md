# Recommender Systems with Large Language Models (Paper List)

This is an actively maintaing curated paper list on recommender systems with large language models. The adopted language models and the correspponding model size, the first pulication date, the first affiliation of the authors are also presented.

## Overview
* [Related Survey Paper](#Related-Survey-paper)
* [LMs as Textual Encoders](#LMs-as-Textual-Encoders)
* [LLMs as Recommenders](#LLMs-as-Recommenders)
* [Related Paper Repo](#Related-Paper-Repo)

### Related Survey Paper
* Pre-train, Prompt and Recommendation: A Comprehensive Survey of Language Modelling Paradigm Adaptations in Recommender Systems, _Norwegian University of Science and Technology, ArXiv 2023, 15 Mar 2023._
  * **Paper link:** [https://arxiv.org/pdf/2302.03735.pdf](https://arxiv.org/pdf/2302.03735.pdf)

* A Survey on Large Language Models for Recommendation, _University of Science and Technology of China, ArXiv 2023, 1 Jun 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.19860.pdf](https://arxiv.org/pdf/2305.19860.pdf)
 
* How Can Recommender Systems Benefit from Large Language Models: A Survey, _Shanghai Jiao Tong University, Huawei Noah's Ark Lab, ArXiv 2023, 12 Jun 2023._
  * **Paper link:** [https://arxiv.org/pdf/2306.05817.pdf](https://arxiv.org/pdf/2306.05817.pdf)

### LMs as Textual Encoders
* U-BERT: Pre-training user representations for improved recommendation, _Tencent, AAAI 2021, 18 May 2021._
  * **Paper link:** [https://ojs.aaai.org/index.php/AAAI/article/view/16557](https://ojs.aaai.org/index.php/AAAI/article/view/16557)
  * **Adopted language model:** BERT (340 milllion)


* Zeor-shot Recommender Systems. _Amazon, ArXiv 2021, 12 Oct 2021._
  * **Paper link:** [https://arxiv.org/pdf/2105.08318.pdf](https://arxiv.org/pdf/2105.08318.pdf)
  * **Adopted language model:** BERT (340 million)

* Towards Universal Sequence Representation Learning for Recommender Systems, _Renmin University of China, KDD 2022, 14 Aug 2022._
  * **Paper link:** [https://dl.acm.org/doi/pdf/10.1145/3534678.3539381?casa_token=aJ-Ili7OeaAAAAAA:Kn_qnglaBAxZ8NUCVtcQ7AqM7q5GyQdzvwc8D8mKyFG0mMbvocmw5VQDNuvL3AH9wb9onPzYPTw](https://dl.acm.org/doi/pdf/10.1145/3534678.3539381?casa_token=aJ-Ili7OeaAAAAAA:Kn_qnglaBAxZ8NUCVtcQ7AqM7q5GyQdzvwc8D8mKyFG0mMbvocmw5VQDNuvL3AH9wb9onPzYPTw)
  * **Adopted language model:** BERT (340 million)

* Learning Vector-Qantized Item Representation for Transferable Sequential Recommenders,  _Renmin University of China, WWW 2023, 30 Apr 2023._
  * **Paper link:** [https://dl.acm.org/doi/pdf/10.1145/3543507.3583434?casa_token=yETRRb_bSf4AAAAA:yuyiF-BgL6uyjwbSCdN0Zia7OifGeZ-vHku5zETltYl8vYhp2eiw6Z9IySBFVKPbK170LPrm1ac](https://dl.acm.org/doi/pdf/10.1145/3543507.3583434?casa_token=yETRRb_bSf4AAAAA:yuyiF-BgL6uyjwbSCdN0Zia7OifGeZ-vHku5zETltYl8vYhp2eiw6Z9IySBFVKPbK170LPrm1ac)
  * **Adopted language model:** BERT (340 million)

* TransRec: Learning Transferable Recommendation from Mixture-of-Modality Feedback, _University of Glasgow & Westlake University, Arxiv 2022, 13 Jun 2022._
  * **Paper link:** [https://arxiv.org/pdf/2206.06190.pdf](https://arxiv.org/pdf/2206.06190.pdf)
  * **Adopted language model:** BERT (110M)

* Where to Go Next for Recommender Systems? ID- vs. Modality-based Recommender Models Revisited, _Westlake University, SIGIR 2023, 23 Jul 2023._
  * **Paper link:** [https://dl.acm.org/doi/pdf/10.1145/3539618.3591932](https://dl.acm.org/doi/pdf/10.1145/3539618.3591932)
  * **Adopted language model:** RoBERTa (125 million) & BERT (110M) & OPT (125M)

* Exploring Adapter-based Transfer Learning for Recommender Systems: Empirical Studies and Practical Insights, _Westlake University, WSDM 2024, 4 Mar 2024._
  * **Paper link:** [https://arxiv.org/pdf/2305.15036.pdf](https://arxiv.org/pdf/2305.15036.pdf)
  * **Adopted language model:** RoBERTa (125 million) & BERT (110M)

* Exploring the Upper Limits of Text-Based
Collaborative Filtering Using Large Language
Models: Discoveries and Insights, _Westlake University, Arxiv, 19 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.11700.pdf](https://arxiv.org/pdf/2305.11700.pdf)
  * **Adopted language model:** OPT (125M ~ 175B)

* NineRec: A Benchmark Dataset Suite for Evaluating Transferable
Recommendation, _Westlake University, Arxiv, 20 Sep 2023._
  * **Paper link:** [https://arxiv.org/pdf/2309.07705.pdf](https://arxiv.org/pdf/2309.07705.pdf)
  * **Adopted language model:** RoBERTa (125 million) & BERT (110M) & OPT (125M)


### LLMs as Recommenders

* LLMRec: Large Language Models with Graph Augmentation for Recommendation, _HKU&Baidu, WSDM 2024 Oral, 5 Nov 2023._
  * **Paper link:** [https://arxiv.org/abs/2311.00423](https://arxiv.org/pdf/2311.00423.pdf)
  * **Code link:** [https://github.com/HKUDS/LLMRec](https://github.com/HKUDS/LLMRec)
    
* Language Models as Recommender Systems: Evaluations and Limitations, _Amazon, ICBINB@NeurIPS2021, 19 Oct 2021._
  * **Paper link:** [https://openreview.net/pdf?id=hFx3fY7-m9b](https://openreview.net/pdf?id=hFx3fY7-m9b)
  * **Adopted language model:** BERT (340 milllion) and GPT-2 (1.5 billion)

* M6-Rec: Generative Pretrained Language Models are Open-Ended Recommender Systems, _Alibaba, Arxiv 2022, 19 May 2022._
  * **Paper link:** [https://arxiv.org/pdf/2205.08084.pdf](https://arxiv.org/pdf/2205.08084.pdf)
  * **Adopted language model:** M6 (10-100 billion)
 
* Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5), _Rutgers University, RecSys 2022, 18 Sep 2022._
  * **Paper link:** [https://dl.acm.org/doi/pdf/10.1145/3523227.3546767?casa_token=s3UwOJ1REN0AAAAA:v4II6fdXMjt8sArQcELa79oG0jTIl4BpMyeMCvQvG37K4GiOrPvlG2AcNgWll9mdmZTfL7lcT08](https://dl.acm.org/doi/pdf/10.1145/3523227.3546767?casa_token=s3UwOJ1REN0AAAAA:v4II6fdXMjt8sArQcELa79oG0jTIl4BpMyeMCvQvG37K4GiOrPvlG2AcNgWll9mdmZTfL7lcT08)
  * **Adopted language model:** T5 (11 billion)

* Chat-REC: Towards Interactive and Explainable LLMs-Augmented Recommender System, _Fudan University, ArXiv 2023, 4 Apr 2023._
  * **Paper link:** [https://arxiv.org/pdf/2303.14524.pdf](https://arxiv.org/pdf/2303.14524.pdf)
  * **Adopted language model:** ChatGPT

* Zero-Shot Next-Item Recommendation using Large Pretrained Language Models, _Singapore Management University, ArXiv 2023, 6 Apr 2023._
  * **Paper link:** [https://arxiv.org/pdf/2304.03153.pdf](https://arxiv.org/pdf/2304.03153.pdf)
  * **Adopted language model:** GPT-3 (175 billion)

* Generative Recommendation: Towards Next-generation Recommender Paradigm, _National University of Singapore, ArXiv 2023, 7 Apr 2023._
  * **Paper link:** [https://arxiv.org/pdf/2304.03516.pdf](https://arxiv.org/pdf/2304.03516.pdf)
  * **Adopted language model:** ChatGPT

* TALLRec: An Effective and Efficient Tuning Framework to Align Large Language Model with Recommendation, _University of Science and Technology of China, ArXiv 2023, 30 Apr 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.00447.pdf](https://arxiv.org/pdf/2305.00447.pdf)
  * **Adopted language model:** LLaMa (7 billion)

* Is ChatGPT a Good Recommender? A Preliminary Study, _Alibaba, ArXiv 2023, 20 Apr 2023._
  * **Paper link:** [https://arxiv.org/pdf/2304.10149.pdf](https://arxiv.org/pdf/2304.10149.pdf)
  * **Adopted language model:** ChatGPT 

* Do LLMs Understand User Preferences? Evaluating LLMs On User Rating Prediction, _Google Research, ArXiv 2023, 10 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.06474.pdf](https://arxiv.org/pdf/2305.06474.pdf)
  * **Adopted language model:** ChatGPT and Flan-U-PaLM (540 billion)

* Sparks of Artificial General Recommender (AGR): Early Experiments with ChatGPT, _Rutgers University, ArXiv 2023, 8 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.04518.pdf](https://arxiv.org/pdf/2305.04518.pdf)
  * **Adopted language model:** ChatGPT
  
* Uncovering ChatGPT's Capabilities in Recommender Systems, _Remin University of China, ArXiv 2023, 11 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.02182.pdf](https://arxiv.org/pdf/2305.02182.pdf)
  * **Adopted language model:** ChatGPT and others

* A First Look at LLM-Powered Generative News Recommendation, _The Hong Kong Polytechnic University, ArXiv 2023, 11 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.06566.pdf](https://arxiv.org/pdf/2305.06566.pdf)
  * **Adopted language model:** ChatGPT

* Recommendation as Instruction Following: A Large Language Model Empowered Recommendation Approach, _Remin University of China, ArXiv 2023, 11 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.07001.pdf](https://arxiv.org/pdf/2305.07001.pdf)
  * **Adopted language model:** Flan-T5-XL (3 billion)

* PALR: Personalization Aware LLMs for Recommendation. _Drexel University, ArXiv 2023, 12 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.07622.pdf](https://arxiv.org/pdf/2305.07622.pdf)
  * **Adopted language model:** LLaMa (7 billion)

* Is ChatGPT Fair for Recommendation? Evaluating Fairness in Large Language Model Recommendation, _University of Science and Technology of China, ArXiv 2023, 12 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.07609.pdf](https://arxiv.org/pdf/2305.07609.pdf)
  * **Adopted language model:** ChatGPT

* How to Index Item IDs for Recommendation Foundation Models. _Rutgers University, ArXiv 2023, 12 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.06569.pdf](https://arxiv.org/pdf/2305.06569.pdf)
  * **Adopted language model:** P5 (11 billion)

* Large Language Models are Zero-Shot Rankers for Recommender Systems, _Renmin University of China, ArXiv 2023, 15 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.08845.pdf](https://arxiv.org/pdf/2305.08845.pdf)
  * **Adopted language model:** ChatGPT

* Leveraging Large Language Models in Conversational Recommender Systems, _Google Research, ArXiv 2023, 16 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.07961.pdf](https://arxiv.org/pdf/2305.07961.pdf)
  * **Adopted language model:** LaMDA (137 billlion)

* Rethinking the Evaluation for Conversational Recommendation in the Era of Large Language Models,  _Renmin University of China, ArXiv 2023, 22 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.13112.pdf](https://arxiv.org/pdf/2305.13112.pdf)
  * **Adopted language model:** ChatGPT

* BookGPT: A General Framework for Book Recommendation Based on a Large Language Model, _AI for Science Institute, ArXiv 2023, 25 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.15673.pdf](https://arxiv.org/pdf/2305.15673.pdf)
  * **Adopted language model:** ChatGPT

* UniTRec: A Unified Text-to-Text Transformer and Joint Contrastive Learning Framework for Text-based Recommendation, _The Chinese University of Hong Kong, ACL 2023 (short), May 25 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.15756.pdf](https://arxiv.org/pdf/2305.15756.pdf)
  * **Adopted language model:** BART (140 million)

* Text Is All You Need: Learning Language Representations for Sequential Recommendation, _University of California, San Diego, KDD 2023, 26 May 2023._
  * **Paper link:** [https://arxiv.org/pdf/2305.13731.pdf](https://arxiv.org/pdf/2305.13731.pdf)
  * **Adopted language model:** Longformer (102 million)
 
* Prompt Tuning Large Language Models on Personalized Aspect Extraction for Recommendations, _New York University, Google Research, ArXiv 2023, 2 Jun 2023._
  * **Paper link:** [https://arxiv.org/pdf/2306.01475.pdf](https://arxiv.org/pdf/2306.01475.pdf)
  * **Adopted language model:** GPT-2 (1.5 billion)
 
* Large Language Model Augmented Narrative Driven Recommendations, _University of Massachusetts, ArXiv 2023, 4 Jun 2023._
  * **Paper link:** [https://arxiv.org/pdf/2306.02250.pdf](https://arxiv.org/pdf/2306.02250.pdf)
  * **Adopted language model:** InstructGPT (175 billion)
 
* CTRL: Connect Tabular and Language Model for CTR Prediction, _Huawei Noah's Ark Lab, ArXiv 2023, 8 Jun 2023._
  * **Paper link:** [https://arxiv.org/pdf/2306.02841.pdf](https://arxiv.org/pdf/2306.02841.pdf)
  * **Adopted language model:** RoBERTa (355 million)

* A Preliminary Study of ChatGPT on News Recommendation: Personalization, Provider Fairness, Fake News, _Northwestern University, ArXiv 2023, 19 Jun 2023._
  * **Paper link:** [https://arxiv.org/pdf/2306.10702.pdf](https://arxiv.org/pdf/2306.10702.pdf)
  * **Adopted language model:** ChatGPT

* Generative Sequential Recommendation with GPTRec, _University of Glasgow, ArXiv 2023, 19 Jun 2023._
  * **Paper link:** [https://arxiv.org/pdf/2306.11114.pdf](https://arxiv.org/pdf/2306.11114.pdf)
  * **Adopted language model:** GPT-2 (1.5 billion)
 
* Towards Open-World Recommendation with Knowledge Augmentation from Large Language Models, _Shanghai Jiao Tong University, Huawei Noah's Ark Lab, ArXiv 2023, 19 Jun 2023._
  * **Paper link:** [https://arxiv.org/pdf/2306.10933.pdf](https://arxiv.org/pdf/2306.10933.pdf)
  


### Related Paper Repo
* [Recommender systems and pretrained models](https://github.com/archersama/awesome-recommend-system-pretraining-papers) by archersama
* [Recommender systems](https://github.com/creyesp/Awesome-recsys) by creyesp
* [Generative recommender systems](https://github.com/jihoo-kim/Awesome-Generative-RecSys) by jihoo-kim

