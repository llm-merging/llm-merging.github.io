---
layout: default
---

# Competition Rules
- Submissions must be reproducible from initial model through merging and fine-tuning. Winning models, along with all associated code and data, must be open-sourced and made public after the competition.

- Submissions must NOT use any copyrighted or proprietary data, code, or closed-source content. The use of data or content that breaks service contracts or trade secrets of any entity is not allowed.

- Submissions must take less than 1 hours to merge/fine-tune and evaluate on a single Nvidia A6000 (48 GB) or equivalent resource.

- Each team can make unlimited submissions during the competition, however the submissions will be evaluated once every week. We will further update the instructions for model submissions as the competition progresses.

- This competition will be run under the honor system. Teams that submit very similar results or copy another team's solution will be disqualified. Violating the spirit of the honor system or taking unfair advantage of the community, even when not against an explicit rule, may result in disqualification and ineligibility for prizes.


### Allowed Models
- Participants in the LLM-Merging competition are allowed to use **any** publicly available model weights that can be downloaded and fullfils the conditions. Specifically, the model should satisfy the following criteria:
  - The model is publicly available on Hugging Face 
  - The model is uploaded before May 31st 2024 
  - The model's parameter size is not larger than 8 billion
This flexibility aims to encourage creativity and innovation in model merging techniques. To help participants get started, we have provided a list of recommended models.

#### 1. Base Model suggestions

<details><summary> <strong>Llama 2 Family</strong>
      <details> 
       - [Llama 2-7B](https://huggingface.co/meta-llama/Llama-2-7b-hf)  
    - [Llama 2-7B Chat](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf)  
    - [LlamaGuard 7B](https://huggingface.co/meta-llama/LlamaGuard-7b)  
    - [Tulu 2-7B](https://huggingface.co/allenai/tulu-2-7b)  
    - [Tulu 2 DPO 7B](https://huggingface.co/allenai/tulu-2-dpo-7b)
    </details>

<details><summary> <strong>Llama 3 Family</strong>
      <details> 
      - [Meta Llama 3-8B](https://huggingface.co/meta-llama/Meta-Llama-3-8B)  
    - [Meta Llama 3-8B Instruct](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct)
    </details>

<details><summary> <strong>Mistral Family</strong>
      <details> 
    - [Mistral 7B Instruct v0.2](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2)  
    - [Mistral 7B Instruct v0.1](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)  
    - [Mistral 7B v0.1](https://huggingface.co/mistralai/Mistral-7B-v0.1)
    </details>

<details><summary> <strong>FLAN T5 Family</strong>
      <details> 
    - [FLAN T5 Large](https://huggingface.co/google/flan-t5-large)  
    - [FLAN T5 Base](https://huggingface.co/google/flan-t5-base)  
    - [FLAN T5 Small](https://huggingface.co/google/flan-t5-small)  
    - [FLAN T5 XL](https://huggingface.co/google/flan-t5-xl)
    </details>


<details><summary> <strong>Gemma Family</strong>
      <details> 
    - [gemma-7b-pytorch ](https://huggingface.co/google/gemma-7b-pytorch)  
    - [gemma-7b-it ](https://huggingface.co/google/gemma-7b-it)  
    </details>


#### 2. Finetuned Model example

<details><summary> <strong>All adapters under</strong></summary>
  <details>
    - [predibase](https://huggingface.co/predibase)  
    - [magicoder](https://huggingface.co/predibase/magicoder)  
    - [conllpp](https://huggingface.co/predibase/conllpp)  
    - [dbpedia](https://huggingface.co/predibase/dbpedia)  
    - [cnn](https://huggingface.co/predibase/cnn)  
    - [agnews_explained](https://huggingface.co/predibase/agnews_explained)  
    - [gsm8k](https://huggingface.co/predibase/gsm8k)  
    - [customer_support](https://huggingface.co/predibase/customer_support)  
    - [glue_qnli](https://huggingface.co/predibase/glue_qnli)  
    - [glue_mnli](https://huggingface.co/predibase/glue_mnli)  
    - [glue_sst2](https://huggingface.co/predibase/glue_sst2)  
    - [glue_cola](https://huggingface.co/predibase/glue_cola)  
    - [glue_stsb](https://huggingface.co/predibase/glue_stsb)  
    - [glue_mrpc](https://huggingface.co/predibase/glue_mrpc)  
    - [glue_qqp](https://huggingface.co/predibase/glue_qqp)  
    - [tldr_headline_gen](https://huggingface.co/predibase/tldr_headline_gen)  
    - [tldr_content_gen](https://huggingface.co/predibase/tldr_content_gen)  
    - [e2e_nlg](https://huggingface.co/predibase/e2e_nlg)  
    - [wikisql](https://huggingface.co/predibase/wikisql)  
    - [hellaswag](https://huggingface.co/predibase/hellaswag)  
    - [hellaswag_processed](https://huggingface.co/predibase/hellaswag_processed)  
    - [legal](https://huggingface.co/predibase/legal)  
    - [jigsaw](https://huggingface.co/predibase/jigsaw)  
    - [bc5cdr](https://huggingface.co/predibase/bc5cdr)  
    - [covid](https://huggingface.co/predibase/covid)  
    - [drop](https://huggingface.co/predibase/drop)  
    - [drop_explained](https://huggingface.co/predibase/drop_explained)  
    - [viggo](https://huggingface.co/predibase/viggo)  
  </details>
</details>





<!-- 
* <p style='text-align: justify;'>Submissions must be reproducible from initial model through fine tuning and inference. Winning models, along with all associated code and data, must be open-sourced and made public after the competition.
* <p style='text-align: justify;'>Submissions must NOT use any copyrighted or proprietary data, code, or closed-source content. The use of data or content that breaks service contracts or trade secrets of any entity is not allowed.
* <p style='text-align: justify;'>Teams are encouraged to use any open-source code and libraries, provided they give proper attribution.
* <p style='text-align: justify;'>Submissions must take less than 24 hours to fine-tune on a single Nvidia A100 or Nvidia 4090 graphics card.
* <p style='text-align: justify;'>For prize eligibility, submissions must meet or exceed a minimum score specified in the metrics section of the challenge.
* <p style='text-align: justify;'>A team can have no more than five members. Teams must self-certify that no individual in the team is participating in other teams for this competition.
* <p style='text-align: justify;'>Teams can submit to either or both Nvidia A100 and Nvidia 4090 hardware tracks.
* <p style='text-align: justify;'>Each team can make three submissions to each track during the competition. The best-performing model will be used to rank the team on the leaderboard and selected for final model evaluation.
* <p style='text-align: justify;'>Teams with one or more members working as full-time employees (FTEs) at Meta or Microsoft are also welcome to participate. Their submissions will be ranked but will not be eligible for cash prizes.
* <p style='text-align: justify;'>Organizers and advisors associated with the competition are not allowed to participate.
* <p style='text-align: justify;'>This competition will be run under the honor system. Teams that submit very similar results or copy another team's solution will be disqualified. Violating the spirit of the honor system or taking unfair advantage of the community, even when not against an explicit rule, may result in disqualification and ineligibility for prizes. -->
