# Model submissions

| Model | HF weights / revision | Public results | Inference code / commit | Hardware and settings |
|---|---|---|---|---|
| Senova-4B-v2 | [weights @ 570183f](https://huggingface.co/WangSenQWQ/Senova-4B-v2/tree/570183f81ca497cb49d62f4f582155ad3fdca5e0) | [public 0.3 index 66.87; scores.json @ 1bc514c](https://huggingface.co/datasets/WangSenQWQ/Senova-4B-v2-decision-index-results/blob/1bc514c446b04d1838956165f91033b290a77363/runs/senova_4b_v2_readtwice/scores.json) | [code @ 6f8f9e8](https://github.com/wswsddd/Senova-4B-v2-inference/tree/6f8f9e815c2f2960a553ad6bd26032788c3bf1fd) | Public: NVIDIA H100 80GB, 8 endpoints, 288 workers, TP=2/DP=4 per endpoint. Maintainer deployment: 1× RTX PRO 6000 96GB, TP=1/DP=1. Read Twice on; thinking off; one next-token distribution per question. [Exact settings and limits](https://github.com/wswsddd/Senova-4B-v2-inference/blob/6f8f9e815c2f2960a553ad6bd26032788c3bf1fd/README.md#4-exact-inference-settings-and-limits). |
