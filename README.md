# LLM-Zoo

# Open-Sourced LLMs

| Model        | Version                        | Release Time | Size           | Backbone           | Langs          | Domain   | Training Data                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | GitHub                                                             | HF                                                                              | Paper                                      | Demo                                                             | Official Blog                                                                                                   |
| :------------: | :------------------------------: | :------------: | :--------------: | :------------------: | :--------------: | :--------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------: | :-------------------------------------------------------------------------------: | :------------------------------------------: | :----------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------: |
| LLaMA        | llama-7b/13b/33b/65b           | 2023.02.27   | 7B/13B/33B/65B | \-                 | en             | General  | <details><summary><b>detail</b></summary>1T tokens (English CommonCrawl, C4, Github, Wikipedia, Gutenberg and Books3, ArXiv, Stack Exchange)</details>                                                                                                                                                                                                                                                                                                                                                                                                      | [[link](https://github.com/facebookresearch/llama)]                | [[link](https://huggingface.co/decapoda-research/llama-7b-hf)]                  | [[link](https://arxiv.org/abs/2302.13971)] | \-                                                               | [[link](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)]                                      |
| Alpaca       | alpaca-7b/13b                  | 2023.03.13   | 7B/13B         | LLaMA              | en             | General  | <details><summary><b>detail</b></summary>52k instruction-following data generated by InstructGPT [[link](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)]</details>                                                                                                                                                                                                                                                                                                                                                                | [[link](https://github.com/tatsu-lab/stanford_alpaca)]             | [[link](https://huggingface.co/tatsu-lab/alpaca-7b-wdiff)]                      | \-                                         | [[link](https://alpaca-ai.ngrok.io/)]                            | [[link](https://crfm.stanford.edu/2023/03/13/alpaca.html)]                                                      |
| Vicuna       | vicuna-7b/13b-delta-v1.1       | 2023.03.13   | 7B/13B         | LLaMA              | en             | General  | <details><summary><b>detail</b></summary>70K samples from sharedGPT</details>                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | [[link](https://github.com/lm-sys/FastChat)]                       | [[link](https://huggingface.co/lmsys/vicuna-7b-delta-v1.1)]                     | \-                                         | [[link](https://chat.lmsys.org/)]                                | [[link](https://vicuna.lmsys.org/)]                                                                             |
| ChatGLM      | chatglm-6b                     | 2023.03.14   | 6B             | GLM                | zh, en         | General  | <details><summary><b>detail</b></summary>supervised fine-tuning, feedback bootstrap, and reinforcement learning with human feedback</details>                                                                                                                                                                                                                                                                                                                                                                                                               | [[link](https://github.com/THUDM/ChatGLM-6B)]                      | [[link](https://huggingface.co/THUDM/chatglm-6b)]                               | \-                                         | \-                                                               | [[link](https://chatglm.cn/blog)]                                                                               |
| ChatGLM      | chatglm-130b                   | 2023.03.14   | 130B           | GLM                | zh, en         | General  | <details><summary><b>detail</b></summary>supervised fine-tuning, feedback bootstrap, and reinforcement learning with human feedback</details>                                                                                                                                                                                                                                                                                                                                                                                                               | [[link](https://github.com/THUDM/GLM-130B)]                        | \-                                                                              | [[link](https://arxiv.org/abs/2210.02414)] | [[link](https://chatglm.cn/login?redirect=%2F)]                  | [[link](https://chatglm.cn/blog)]                                                                               |
| Guanaco      | \-                             | 2023.03.16   | 7B             | LLaMA              | ja, zh, en, de | General  | <details><summary><b>detail</b></summary>multilingual datasets [[link](https://huggingface.co/datasets/JosephusCheung/GuanacoDataset)]</details>                                                                                                                                                                                                                                                                                                                                                                                                            | [[link](https://github.com/Guanaco-Model/Guanaco-Model.github.io)] | [[link](https://huggingface.co/JosephusCheung/Guanaco)]                         | \-                                         | \-                                                               | \-                                                                                                              |
| Dolly        | dolly-v1-6b                    | 2023.03.24   | 6B             | GPT-J-6B           | en             | General  | <details><summary><b>detail</b></summary>52k stanford alpaca instruction-following data [[link](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)]</details>                                                                                                                                                                                                                                                                                                                                                                         | \-                                                                 | [[link](https://huggingface.co/databricks/dolly-v1-6b)]                         | \-                                         | \-                                                               | [[link](https://www.databricks.com/blog/2023/03/24/hello-dolly-democratizing-magic-chatgpt-open-models.html)]   |
| ChatDoctor   | \-                             | 2023.03.24   | 7B             | LLaMA              | en             | Medicine | <details><summary><b>detail</b></summary>52K stanford alpaca [[link](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)], 100K HealthCareMagic [[link](https://drive.google.com/file/d/1lyfqIwlLSClhgrCutWuEe_IACNq6XNUt/view)], 10K icliniq [[link](https://drive.google.com/file/d/1ZKbqgYqWc7DJHs3N9TQYQVPdDQmZaClA/view)], 5K GenMedGPT-5k [[link](https://drive.google.com/file/d/1nDTKZ3wZbZWTkFMBkxlamrzbNz0frugg/view)]</details>                                                                                             | [[link](https://github.com/Kent0n-Li/ChatDoctor)]                  | \-                                                                              | [[link](https://arxiv.org/abs/2303.14070)] | [[link](https://huggingface.co/spaces/kenton-li/chatdoctor_csv)] | \-                                                                                                              |
| LuoTuo       | Chinese-alpaca-lora            | 2023.03.25   | 7B             | LLaMA              | zh, en         | General  | <details><summary><b>detail</b></summary>Translated 52k stanford alpaca instruction-following data [[link](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)], guanaco [[link](https://huggingface.co/datasets/JosephusCheung/GuanacoDataset)]</details>                                                                                                                                                                                                                                                                             | [[link](https://github.com/LC1332/Chinese-alpaca-lora)]            | [[link](https://huggingface.co/silk-road/luotuo-lora-7b-1.0)]                   | \-                                         | \-                                                               | \-                                                                                                              |
| BELLE        | BELLE-7B-0.2M/0.6M/1M/2M       | 2023.03.26   | 7B             | BLOOMZ-7B1-mt      | zh, en         | General  | <details><summary><b>detail</b></summary>0.2M/0.6M/1M/2M Chinese data [[link](https://github.com/LianjiaTech/BELLE/tree/main/data)], 52k stanford alpaca instruction-following data [[link](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)]</details>                                                                                                                                                                                                                                                                             | [[link](https://github.com/LianjiaTech/BELLE)]                     | [[link](https://huggingface.co/BelleGroup/BELLE-7B-0.2M)]                       | [[link](https://arxiv.org/abs/2303.14742)] | \-                                                               | \-                                                                                                              |
| Linly (伶荔)   | Linly-Chinese-LLaMA 7b/13b/33b | 2023.03.28   | 7B/13B/33B     | LLaMA              | zh             | General  | <details><summary><b>detail</b></summary>Chinese-English parallel corpora [[link](https://statmt.org/wmt18/translation-task.html#download)], Chinese Wikipedia, community interaction, news data [[link](https://github.com/CLUEbenchmark/CLUECorpus2020)], scientific literature [[link](https://github.com/ydli-ai/CSL)]</details>                                                                                                                                                                                                                        | [[link](https://github.com/CVI-SZU/Linly)]                         | [[link](https://huggingface.co/P01son/Linly-Chinese-LLaMA-7b-hf)]               | \-                                         | \-                                                               | \-                                                                                                              |
| Linly (伶荔)   | Linly-ChatFlow 7b/13b          | 2023.03.28   | 7B/13B         | LLaMA              | zh             | General  | <details><summary><b>detail</b></summary>BELLE [[link](https://github.com/LianjiaTech/BELLE)], pCLUE [[link](https://github.com/CLUEbenchmark/pCLUE)], CSL [[link](https://github.com/ydli-ai/CSL)], GuanacoDataset [[link](https://huggingface.co/datasets/JosephusCheung/GuanacoDataset)], Chain-of-Thought [[link](https://github.com/CVI-SZU/Linly/tree/main/instructions)], news_commentary [[link](https://github.com/CVI-SZU/Linly/tree/main/instructions)], firefly [[link](https://huggingface.co/datasets/YeungNLP/firefly-train-1.1M)]</details> | [[link](https://github.com/CVI-SZU/Linly)]                         | [[link](https://huggingface.co/P01son/Linly-ChatFlow-13b-hf)]                   | \-                                         | \-                                                               | [[link](https://zhuanlan.zhihu.com/p/616748134)]                                                                |
| BAIZE        | baize-7B/13B/30B               | 2023.04.01   | 7B/13B/30B     | LLaMA              | en             | General  | <details><summary><b>detail</b></summary>52K Stanford Alpaca [[link](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)], 54K Quora [[link](https://github.com/project-baize/baize-chatbot/blob/main/data/quora_chat_data.json)], 57K StackOverFlow [[link](https://github.com/project-baize/baize-chatbot/blob/main/data/stackoverflow_chat_data.json)]</details>                                                                                                                                                                    | [[link](https://github.com/project-baize/baize-chatbot)]           | [[link](https://huggingface.co/project-baize/baize-lora-7B)]                    | [[link](https://arxiv.org/abs/2304.01196)] | [[link](https://huggingface.co/spaces/project-baize/Baize-7B)]     | \-                                                                                                              |
| Koala        | \-                             | 2023.04.03   | 13B            | LLaMA              | en             | General  | <details><summary><b>detail</b></summary>ShareGPT, HC3 [[link](https://arxiv.org/abs/2301.07597)], OIG [[link](https://laion.ai/blog/oig-dataset/)], Stanford alpaca [[link](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)], Anthropic HH [[link](https://huggingface.co/datasets/Anthropic/hh-rlhf)], OpenAI WebGPT [[link](https://huggingface.co/datasets/openai/webgpt_comparisons)], OpenAI Summarization [[link](https://huggingface.co/datasets/openai/summarize_from_feedback)]</details>                                | \-                                                                 | [[link](https://huggingface.co/young-geng/koala)]                               | \-                                         | [[link](https://chat.lmsys.org/)]                                | [[link](https://bair.berkeley.edu/blog/2023/04/03/koala/)]                                                      |
| BAIZE        | baize-healthcare-7b            | 2023.04.03   | 7B             | LLaMA              | en             | Medicine | <details><summary><b>detail</b></summary>54K Quora [[link](https://github.com/project-baize/baize-chatbot/blob/main/data/quora_chat_data.json)], 47K medical dialogs [[link](https://github.com/project-baize/baize-chatbot/blob/main/data/medical_chat_data.json)]</details>                                                                                                                                                                                                                                                                               | [[link](https://github.com/project-baize/baize-chatbot)]           | [[link](https://huggingface.co/project-baize/baize-healthcare-lora-7B)]         | \-                                         | \-                                                               | \-                                                                                                              |
| Firefly (流萤) | firefly-1b4/2b6                | 2023.04.06   | 1.4B/2.6B      | BLOOM-ZH           | zh             | General  | <details><summary><b>detail</b></summary>Chinese question-answering pairs [[link](https://huggingface.co/datasets/YeungNLP/firefly-train-1.1M)], [[link](https://huggingface.co/datasets/BelleGroup/train_0.5M_CN)]</details>                                                                                                                                                                                                                                                                                                                               | [[link](https://github.com/yangjianxin1/Firefly)]                  | [[link](https://huggingface.co/YeungNLP/firefly-2b6)]                           | \-                                         | \-                                                               | \-                                                                                                              |
| Phoenix      | Phoenix-chat-7b                | 2023.04.08   | 7B             | BLOOMZ             | multi          | General  | <details><summary><b>detail</b></summary>conversation data [[link](https://huggingface.co/datasets/FreedomIntelligence/phoenix-sft-data-v1)]</details>                                                                                                                                                                                                                                                                                                                                                                                                      | [[link](https://github.com/FreedomIntelligence/LLMZoo)]            | [[link](https://huggingface.co/FreedomIntelligence/phoenix-chat-7b)]            | \-                                         | \-                                                               | \-                                                                                                              |
| Phoenix      | Phoenix-inst-chat-7b           | 2023.04.09   | 7B             | BLOOMZ             | multi          | General  | <details><summary><b>detail</b></summary>conversation data [[link](https://huggingface.co/datasets/FreedomIntelligence/phoenix-sft-data-v1)], instruction data</details>                                                                                                                                                                                                                                                                                                                                                                                    | [[link](https://github.com/FreedomIntelligence/LLMZoo)]            | [[link](https://huggingface.co/FreedomIntelligence/phoenix-inst-chat-7b)]       | \-                                         | \-                                                               | \-                                                                                                              |
| Chimera      | chimera-chat-7b/13b            | 2023.04.10   | 7B/13B         | LLaMA              | latin          | General  | <details><summary><b>detail</b></summary>conversation data [[link](https://huggingface.co/datasets/FreedomIntelligence/phoenix-sft-data-v1)]</details>                                                                                                                                                                                                                                                                                                                                                                                                      | [[link](https://github.com/FreedomIntelligence/LLMZoo)]            | [[link](https://huggingface.co/FreedomIntelligence/chimera-chat-7b-delta)]      | \-                                         | \-                                                               | \-                                                                                                              |
| Chimera      | chimera-inst-chat-7b/13b       | 2023.04.11   | 7B/13B         | LLaMA              | latin          | General  | <details><summary><b>detail</b></summary>conversation data [[link](https://huggingface.co/datasets/FreedomIntelligence/phoenix-sft-data-v1)], instruction data</details>                                                                                                                                                                                                                                                                                                                                                                                    | [[link](https://github.com/FreedomIntelligence/LLMZoo)]            | [[link](https://huggingface.co/FreedomIntelligence/chimera-inst-chat-7b-delta)] | \-                                         | \-                                                               | \-                                                                                                              |
| Dolly        | dolly-v2-12b                   | 2023.04.12   | 12B            | pythia-12b         | en             | General  | <details><summary><b>detail</b></summary>15k human-generated prompt/response pairs [[link](https://huggingface.co/datasets/databricks/databricks-dolly-15k)]</details>                                                                                                                                                                                                                                                                                                                                                                                      | [[link](https://github.com/databrickslabs/dolly)]                  | [[link](https://huggingface.co/databricks/dolly-v2-12b)]                        | \-                                         | \-                                                               | [[link](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm)] |
| MedAlpaca    | medalpaca 7b/13b               | 2023.04.14   | 7B/13B         | LLaMA              | en             | Medicine | <details><summary><b>detail</b></summary>question-answering pairs from flash card, wikidoc, stackexchange and ChatDoctor</details>                                                                                                                                                                                                                                                                                                                                                                                                                          | [[link](https://github.com/kbressem/medAlpaca)]                    | [[link](https://huggingface.co/medalpaca/medalpaca-7b)]                         | [[link](https://arxiv.org/abs/2304.08247)] | \-                                                               | \-                                                                                                              |
| BELLE        | BELLE-LLaMA-7B/13B-2M          | 2023.04.19   | 7B/13B         | LLaMA              | zh, en         | General  | <details><summary><b>detail</b></summary>2M Chinese data [[link](https://github.com/LianjiaTech/BELLE/tree/main/data)], 52k stanford alpaca instruction-following data [[link](https://github.com/tatsu-lab/stanford_alpaca/blob/main/alpaca_data.json)]</details>                                                                                                                                                                                                                                                                                          | [[link](https://github.com/LianjiaTech/BELLE)]                     | [[link](https://huggingface.co/BelleGroup/BELLE-LLaMA-7B-2M-enc)]               | [[link](https://arxiv.org/abs/2303.14742)] | \-                                                               | \-                                                                                                              |
| MOSS         | moss-moon-003-base             | 2023.04.21   | 16B            | CodeGen            | zh, en         | General  | <details><summary><b>detail</b></summary>100B Chinese tokens and 20B English tokens</details>                                                                                                                                                                                                                                                                                                                                                                                                                                                               | [[link](https://github.com/OpenLMLab/MOSS)]                        | [[link](https://huggingface.co/fnlp/moss-moon-003-base)]                        | \-                                         | [[link](https://moss.fastnlp.top/)]                              | [[link](https://txsun1997.github.io/blogs/moss.html)]                                                           |
| MOSS         | moss-moon-003-sft              | 2023.04.21   | 16B            | moss-moon-003-base | zh, en         | General  | <details><summary><b>detail</b></summary>1.1M multi-turn conversational data (generated from ChatGPT) [[link](https://github.com/OpenLMLab/MOSS/tree/main/SFT_data/conversations/conversation_without_plugins)]</details>                                                                                                                                                                                                                                                                                                                                   | [[link](https://github.com/OpenLMLab/MOSS)]                        | [[link](https://huggingface.co/fnlp/moss-moon-003-sft)]                         | \-                                         | [[link](https://moss.fastnlp.top/)]                              | [[link](https://txsun1997.github.io/blogs/moss.html)]                                                           |
| MOSS         | moss-moon-003-sft-plugin       | 2023.04.21   | 16B            | moss-moon-003-base | zh, en         | General  | <details><summary><b>detail</b></summary>1.1M multi-turn conversational data [[link](https://github.com/OpenLMLab/MOSS/tree/main/SFT_data/conversations/conversation_without_plugins)], 300K plugin-augmented data (generated by InstructGPT) [[link](https://github.com/OpenLMLab/MOSS/tree/main/SFT_data/conversations/conversation_with_plugins)]</details>                                                                                                                                                                                              | [[link](https://github.com/OpenLMLab/MOSS)]                        | [[link](https://huggingface.co/fnlp/moss-moon-003-sft-plugin)]                  | \-                                         | [[link](https://moss.fastnlp.top/)]                              | [[link](https://txsun1997.github.io/blogs/moss.html)]                                                           |
| HuggingChat  | oasst-sft-6-llama-30b          | 2023.04.22   | 30B            | LLaMA              | multi          | General  | <details><summary><b>detail</b></summary>human-generated, human-annotated assistant-style conversation corpus consisting of 161k messages in 35 languages [[link](https://huggingface.co/datasets/OpenAssistant/oasst1)]</details>                                                                                                                                                                                                                                                                                                                          | [[link](https://github.com/LAION-AI/Open-Assistant)]               | [[link](https://huggingface.co/OpenAssistant/oasst-sft-6-llama-30b-xor)]        | \-                                         | [[link](https://huggingface.co/chat/)]                           | \-                                                                                                              |


# Closed-Sourced LLMs