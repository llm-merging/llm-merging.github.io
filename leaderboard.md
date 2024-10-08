---
layout: default
---

<!-- ## Winners 🏆

Stay tunned! -->

<!-- ### A100 track
1. Percent_bfd: Ao Liu, Zizhen Huang, Jiabin Wang, Hao Lu, Qin Hu [Repo](https://github.com/Percent-BFD/neurips_submission)
2. Tiered Model Ninja Team: Anmol Agarwal, Ajinkya Deshpande, Shashank Shet, Arun Iyer, Suresh Parthasarathy [Repo](https://github.com/anmolagarwal999/Submission-NeurIPS-Large-Language-Model-Efficiency-Challenge-2023) 
3. ReaLLM Conquerors: Mrigank Raman, Kousik Rajesh, Rahul Saxena, Abishek Sridhar, Akanksha Sachan [Repo](https://github.com/MrigankRaman/LLM_Comp/)

Student A100 track
1. ReaLLM Conquerors: Mrigank Raman, Kousik Rajesh, Rahul Saxena, Abishek Sridhar, Akanksha Sachan [Repo](https://github.com/MrigankRaman/LLM_Comp/)
2. NJUST-A!dge: Shupeng Zhong, Yu Xia, Shifeng Yi, Qingguo Chen, Yang Yang [Repo](https://github.com/hqbbzsp/nips_submission_A100) -->

# Leaderboard 
### Full leaderboard at [Huggingface leaderboard](https://huggingface.co/spaces/margsli/merging_competition)

- Validation Benchmark Performance is averaged.
- Final performance will be assessed at the end of the competition on a hidden test set, which may or may not be correlated with Validation performance.
- Higher values are better.

| Rank | 🤖 Model / Submission Name       | ⭐ Validation Performance |
|------|----------------------------------|--------------------------|
| 1    | BVD_Mega                         | 54.5                     |
| 2    | wcf_lar                          | 52.2                     |
| 3    | readapt_median                   | 48.4                     |
| 4    | kobeni                           | 46.7                     |
| 5    | lore_route                       | 45.8                     |
| 6    | shira_llama3_8b_it_algo0         | 44.9                     |
| 7    | basic_merge_00                   | 44.7                     |
| 8    | llama_base_fc                    | 44.2                     |
| 9    | llama_base_qa                    | 44.2                     |
| 10   | shira_qw2_7b_it_algo0            | 44.1                     |
| 11   | llama_merge2                     | 42.7                     |
| 12   | mistral_avg_exp_04               | 42.2                     |
| 13   | shira_mtl7b_0_2_algo0            | 42.0                     |
| 14   | mistral_avg_exp_05               | 41.4                     |
| 15   | mistral_avg_exp_07               | 41.3                     |
| 16   | mistral_avg_exp_06               | 41.2                     |
| 17   | cdutr_AqQ3                       | 41.1                     |
| 18   | shira_ft5_algo0                  | 40.8                     |
| 19   | shira_ft5xl_algo0                | 40.8                     |
| 20   | yi15_exp                         | 40.7                     |
| 21   | yi15_exp                         | 39.9                     |
| 22   | llama_avg                        | 38.5                     |
| 23   | llama_avg (Baseline)             | 38.4                     |
| 24   | knovel_test                      | 38.4                     |
| 25   | abc                              | 38.1                     |
| 26   | flan_t5_avg                      | 38.0                     |
| 27   | llama_optimized                  | 38.0                     |
| 28   | Fbaseline                        | 38.0                     |
| 29   | flan_t5_weights                  | 37.7                     |
| 30   | flan_t5_avg_lora                 | 37.6                     |
| 31   | cdutr_pi5c                       | 37.2                     |
| 32   | my_t5_avg                        | 37.1                     |
| 33   | deepseek_exp                     | 36.5                     |
| 34   | shira_algo_k00                   | 29.5                     |
| 35   | SLM                              | 26.0                     |
| 36   | llama_avg                        | 18.8                     |

*Updated on 08/19/2024. The full leaderboard is hosted on [Huggingface leaderboard](https://huggingface.co/spaces/margsli/merging_competition)*

<!-- <iframe src="https://www.example.com" width="100%" height="600px"></iframe> -->

<!-- 
## Discord Leaderboard
On Discord 
* [4090 Leaderboard](https://discord.com/channels/1124130156336922665/1151568318013132831)
* [A100 Leaderboard](https://discord.com/channels/1124130156336922665/1151568359251509319)

## How to use the leaderboard
The [Lightning AI](https://lightning.ai/) ⚡ team has built us a leaderboard on Discord. This is the single best way you can make sure your submissions actually work before the submission, try to beat the unfinetuned toy submission as a starting point.

You might have noticed a new friendly bot has joined the server called @evalbot  to use it
1. DM the bot with `eval 4090` or `eval A100` and attach a zipped file of your submission to the message (You can also just openly message the bot but DM'ing will protect your secret sauce)
2. If successful the bot will give you a job ID and a running status, the eval will take roughly 1-2h so be patient if you're top of queue
3. Once the bot completes your run it will update either the ⁠leaderboard_4090  or ⁠leaderboard_a100 channel, we will not be monitoring these 2 text channels they will be purely for the bot to post the new updated leaderboard
-->

## How to submit your merging method

- Start from our starter code template [LLM-Merging](https://github.com/llm-merging/LLM-Merging) and build your own merging method.
- Please submit the whole repository. After modifying the files, tar the file into a tarball using the command:
```python
tar -cvf llm-merging.tar LLM-Merging
```
- Submit your tar file using this [form](https://docs.google.com/forms/d/17TPg7N02o8qvw1czx55Zbh_5Kp7-YStUIOhQDJYc23g/edit)

- Please submit a report describing your merging method to our [OpenReview LMC 2024](https://openreview.net/group?id=NeurIPS.cc/2024/Competition/LMC) page. Please follow the standard NeurIPS format [template](https://www.overleaf.com/latex/templates/neurips-2024/tpsbbrdqcmsh). There are no strict restrictions or limitations for the report, but we suggest that the page limit not exceed 4 pages. All submitted reports will be publicly accessible on our website.


**Note**: 
- Each team’s submission will be evaluated at most once per day. Evaluation frequency will increase as the deadline approaches.
- An automatic submission method is comming soon.
