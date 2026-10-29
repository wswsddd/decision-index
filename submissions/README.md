# Model submissions

| Model | HF weights / revision | Public results | Inference code / commit | Hardware and settings |
|---|---|---|---|---|
| Senova-4B-v2 | [weights @ 61170a5](https://huggingface.co/WangSenQWQ/Senova-4B-v2/tree/61170a55c975227588109dc080b2b7bf259d3cb6) | [public 0.3 index 67.27; scores.json @ bbd5bd0](https://huggingface.co/datasets/WangSenQWQ/Senova-4B-v2-decision-index-results/blob/bbd5bd0ca5769367b38aa0aa279763a276689a45/runs/senova_4b_v2_readtwice/scores.json) | [code @ ac25f3f](https://github.com/wswsddd/Senova-4B-v2-inference/tree/ac25f3fc3750f56496d7cc4f37c56415d23e1a1e) | Public: NVIDIA H100 80GB, 8 endpoints, 288 workers, TP=2/DP=4 per endpoint. Maintainer deployment: 1× RTX PRO 6000 96GB, TP=1/DP=1. Read Twice on; thinking off; SGLang native selected-token next-token logprobs. [Exact settings and limits](https://github.com/wswsddd/Senova-4B-v2-inference/blob/ac25f3fc3750f56496d7cc4f37c56415d23e1a1e/README.md#4-exact-inference-settings-and-limits). |
