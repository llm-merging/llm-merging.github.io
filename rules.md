---
layout: default
---

## Competition Rules
- Submissions must be reproducible from initial model through merging and fine-tuning. Winning models, along with all associated code and data, must be open-sourced and made public after the competition.
- Submissions must NOT use any copyrighted or proprietary data, code, or closed-source content. The use of data or content that breaks service contracts or trade secrets of any entity is not allowed.
- Submissions must take less than 24 hours to fine-tune on a single Nvidia A100 or Nvidia 4090 graphics card.
- This competition will be run under the honor system. Teams that submit very similar results or copy another team's solution will be disqualified. Violating the spirit of the honor system or taking unfair advantage of the community, even when not against an explicit rule, may result in disqualification and ineligibility for prizes.


### Recommended Models
- Participants in the LLM-Merging competition are allowed to use any publicly available model weights that can be downloaded. 
Specifically, any model that can be shared through huggingface is concerned valide. This flexibility aims to encourage creativity and innovation in model merging techniques. To help participants get started, we have provided a list of recommended models.

#### 1. Base Models 

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
    - [Mistral 7B Instruct v0.2](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2)  
    - [Mistral 7B Instruct v0.1](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)  
    - [Mistral 7B v0.1](https://huggingface.co/mistralai/Mistral-7B-v0.1)
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