
## fine-tuning

https://github.com/Curated-Awesome-Lists/awesome-llms-fine-tuning
https://github.com/mmarius/awesome-finetuning


## ml

https://github.com/underlines/awesome-ml


## article

### [Simple, Scalable Adaptation for Neural Machine Translation](https://aclanthology.org/D19-1165/)

レイヤーを追加するアプローチ  
openaiのfine tuningでは使えない

https://claude.ai/chat/f5f4fd71-18ea-4600-a7cf-292695f8f4ca

### [Building Accurate Translation-Tailored LLMs with Language Aware Instruction Tuning](https://arxiv.org/html/2403.14399v1)

指示矛盾サンプルを用いたunlikelihood訓練により、大規模言語モデルのゼロショット翻訳能力を向上させる手法

https://claude.ai/chat/63d69da8-4e8e-4d98-ae14-48a69873ed04

### [Fine-tuning Large Language Models for Domain-specific Machine Translation](https://arxiv.org/html/2402.15061v1)

大規模言語モデルを効率的にファインチューニングし、ドメイン固有の機械翻訳タスクに適応させる手法の提案

IT分野での翻訳タスクで問題があるそう

https://claude.ai/chat/09d0f6b3-632d-440f-993a-817297ab9de0

### [Learning From Failure: Integrating Negative Examples when Fine-tuning Large Language Models as Agents](https://arxiv.org/html/2402.11651v1)

大規模言語モデルをエージェントとして微調整する際に、失敗事例を活用することで性能を向上させる新しい学習手法（Negative-Aware Training）を提案し、その有効性を実証した研究

https://claude.ai/chat/cf744d71-02b1-4e23-a583-825eadc3bfbe

### [The Fine-Tuning Paradox: Boosting Translation Quality Without Sacrificing LLM Abilities](https://aclanthology.org/2024.acl-long.336/)

大規模言語モデルを機械翻訳用にファインチューニングすると全体的な翻訳品質は向上するが、モデルの特殊能力（フォーマリティ制御、少数事例学習、文脈化など）が低下する現象を発見し、その対策を提案した

https://claude.ai/chat/0d3ad431-5e9a-47f4-ae3c-c6132e967018

### [Fine-tuning Large Language Models for Adaptive Machine Translation](https://arxiv.org/abs/2312.12740)

Mistral 7Bという大規模言語モデルを適応的機械翻訳のために微調整し、ゼロショットおよびワンショット翻訳の品質を大幅に向上させた

Mistral 7Bという言語モデルを改良し、リアルタイムで専門用語や文脈に適応できる高品質な翻訳システムを開発した

https://claude.ai/chat/05245a64-506f-4b51-a637-046e8612975f

### [Improving Neural Machine Translation Models with Monolingual Data](https://arxiv.org/abs/1511.06709)

2016年の論文

バックトランスレーションを用いて単言語データから擬似的な対訳データを作成し、それをニューラル機械翻訳(NMT)の訓練に活用することで、翻訳性能を大幅に向上させる手法を提案している

https://claude.ai/chat/a461c1e5-2178-4ad0-8098-3f047f934f6b

### [Adapting Large Language Models for Document-Level Machine Translation](https://arxiv.org/abs/2401.06468)

中規模の大規模言語モデル(LLM)を文書レベル機械翻訳に適応させる方法を広範に調査し、その可能性と課題を明らかにした研究

https://claude.ai/chat/32ef6bd2-1964-414d-ae5e-5289d74e05a6


### [Machine Translation with Large Language Models: Prompting, Few-shot Learning, and Fine-tuning with QLoRA](https://aclanthology.org/2023.wmt-1.43/)

大規模言語モデル(LLM)をQLoRAでファインチューニングすることで、効率的かつ高性能な機械翻訳システムを構築できる

https://claude.ai/chat/ff66b46c-323c-479d-b1bf-2554d6ba4b32

### [Adaptive Machine Translation with Large Language Models](https://arxiv.org/abs/2301.13294)

大規模言語モデル(LLM)のin-context learning能力を活用することで、リアルタイムの適応的機械翻訳が可能になり、特に高リソース言語では従来のMTシステムを上回る性能を示した

https://claude.ai/chat/78faae9b-ed3b-4811-91a0-bf403e102d94

### [Efficiently Exploring Large Language Models for Document-Level Machine Translation with In-context Learning]()

CAPは、LLMを用いたDOCMTの課題に対処し、より正確で一貫性のある翻訳を可能にする。

https://claude.ai/chat/c81cfe95-354f-4dea-b652-fb81e0081bd7


## dataset

https://www2.nict.go.jp/astrec-att/member/mutiyama/align/index.html

小説のコーパスデータ

https://www.jta-net.or.jp/useful_tools2.html

https://blog.statsbeginner.net/entry/2023/08/27/225542


https://huggingface.co/datasets/mpasila/ParallelFiction-Ja_En-100k-json/viewer/default/train?p=4&row=400

日本語と英語が一致していないものもあるので、使う時は気を付ける

https://huggingface.co/datasets/Hoshikuzu/opus-100-en-ja

https://huggingface.co/datasets/Hoshikuzu/ccmatrix-en-ja

https://huggingface.co/datasets/hpprc/alt-parallel-en-ja

https://github.com/kunishou/databricks-dolly-15k-ja



https://scholar.google.co.jp/scholar?as_ylo=2023&q=Fine+tuning+large+language+models+for+adaptive+machine+translation&hl=ja&as_sdt=0,5&as_vis=1

## How to Embedding

https://qiita.com/rairaii/items/f365d96bb11b72f9ea78

https://zenn.dev/libratech/articles/afe9c5b30668bb

https://qiita.com/matntntn/items/7cdca4f33ce03970ef20

https://qiita.com/akeyhero/items/ce371bfed64399027c23

## what is ALT Project

https://www2.nict.go.jp/astrec-att/member/mutiyama/ALT/

## Evaluate Translation

https://www.getblend.com/blog/evaluate-translation-checklist/

https://github.com/openai/evals


## System prompt

[Claude system prompt](https://docs.anthropic.com/en/release-notes/system-prompts#july-12th-2024)

## openai fine tuning info

https://platform.openai.com/docs/guides/model-selection/practical-example