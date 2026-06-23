# Samuel Gali

**Final-year Computer Science student at the University of Lagos, researching African NLP and building agentic AI systems.**

My work sits between research and applied engineering. On one side, I build language technology for low-resource African languages, mostly Yorùbá, covering diacritic restoration, AI-text detection, and translation-quality evaluation. On the other, I build agentic systems that move past static text processing into reasoning, planning, and autonomous execution. I co-authored a paper at the EACL 2026 AfricaNLP workshop and keep a handful of models and demos on the Hugging Face Hub.

Alongside the building, I write. Putting ideas into words is how I think through problems, and I publish short essays on applied AI and African NLP on [Medium](https://medium.com/@lazy-monster).

## Selected projects

| Project | What it is | Stack | Links |
| :--- | :--- | :--- | :--- |
| **Dyon** | A source-available Python framework (~9,600 LOC) for building agentic cross-domain digital twins, validated by a three-twin Salesman / Customer / Product system. | Python, LangChain, RL, Eclipse Ditto | [PyPI](https://pypi.org/project/dyon/) · [GitHub](https://github.com/lazy-monster/dyon) |
| **Yo-ByT5** | A byte-level T5 that restores tone marks and underdots to plain Yorùbá text, trained on Google Cloud TPUs. 83.8% word accuracy, 83.9 ChrF. | ByT5, TensorFlow, TPU v6e-8 | [Demo](https://huggingface.co/spaces/lazymonster/yobyt5-demo) · [Model](https://huggingface.co/lazymonster/yobyt5-restoration) |
| **Yorùbá AI-Text Detector** | A transformer classifier separating human-written Yorùbá from LLM output, among the first such systems for a low-resource tonal language. | PyTorch, Hugging Face, Gradio | [Demo](https://huggingface.co/spaces/lazymonster/yoruba-ai-detector) |
| **Oracle** | An autonomous agent for a live game economy (Torn City) that ingests data streams, holds persistent state, and acts over the Discord API. | Python, Discord API, state management | Private |
| **FER2013 Classifier** | Benchmarked CNN architectures for facial-expression recognition with ablations on depth and regularisation, then deployed the best model. | PyTorch, fast.ai, CNNs | [Demo](https://huggingface.co/spaces/lazymonster/facial-emotion-recognition) |

## Research

**Trust but Check: LLM-Assisted Review of Human Translations in African Languages**
EACL 2026, AfricaNLP Workshop (published 27 Jan 2026).
Co-authored work using multilingual LLMs to audit translation quality across 11 low-resource African languages, combining LLM-as-a-judge scoring with native-speaker review on the MAFAND-MT test set.
[Read on OpenReview](https://openreview.net/forum?id=8B2WDhIAMV)

## Toolkit

- **Languages:** Python, R, Java, C++
- **Deep learning:** PyTorch, TensorFlow, fast.ai
- **NLP & ML:** Hugging Face Transformers, ByT5 and seq2seq models, scikit-learn
- **Agentic AI:** LangGraph, LLM tool-use, state-aware agents
- **Data & infrastructure:** NumPy, pandas, Google Cloud TPU (v6e-8), Git, SQL

## Contact

Open to research collaborations, contract work, and full-time roles in NLP and agentic AI engineering.

[Email](mailto:galisamuel97@gmail.com) · [LinkedIn](https://www.linkedin.com/in/samuelgali/) · [X](https://x.com/lazy_maxxing) · [Medium](https://medium.com/@lazy-monster) · [Hugging Face](https://huggingface.co/lazymonster)
