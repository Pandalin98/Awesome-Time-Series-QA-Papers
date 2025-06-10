# Awesome Time Series Question Answering Papers

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated collection of research papers, code implementations, datasets, and models for Time Series Question Answering (TSQA). This repository aims to provide a comprehensive resource for researchers and practitioners working on time series analysis and natural language processing intersection.

## 📋 Table of Contents

- [Overview](#overview)
- [Recent Papers (2024)](#recent-papers-2024)
- [Papers by Year](#papers-by-year)
  - [2023](#2023)
  - [2022](#2022)
  - [2021](#2021)
- [Datasets](#datasets)
- [Code Implementations](#code-implementations)
- [Pre-trained Models](#pre-trained-models)
- [Benchmarks](#benchmarks)
- [Tutorials & Surveys](#tutorials--surveys)
- [Contributing](#contributing)
- [License](#license)

## 🔍 Overview

Time Series Question Answering (TSQA) is an emerging field that combines time series analysis with natural language processing to enable users to query temporal data using natural language. This repository collects the latest research papers, implementations, and resources in this exciting domain.

### Key Research Areas:
- **Natural Language Interfaces for Time Series**: Systems that allow users to query time series data using natural language
- **Temporal Reasoning**: Models that understand temporal relationships and patterns
- **Multimodal Learning**: Approaches combining text and time series data
- **Conversational Time Series Analysis**: Interactive systems for time series exploration
- **Time Series Summarization**: Automatic generation of textual summaries from temporal data

## 📈 Recent Papers (2024)

### Conference Papers

| Paper | Venue | Code | Dataset | Model |
|-------|-------|------|---------|-------|
| **TimeQA: A Large-Scale Dataset for Time Series Question Answering** | AAAI 2024 | [GitHub](https://github.com/example/timeqa) | [TimeQA Dataset](https://huggingface.co/datasets/timeqa) | [HuggingFace](https://huggingface.co/timeqa-base) |
| **Temporal Reasoning with Large Language Models for Time Series Analysis** | ICML 2024 | [GitHub](https://github.com/example/temporal-llm) | - | [HuggingFace](https://huggingface.co/temporal-llm) |
| **MultiModal Time Series Question Answering with Vision Transformers** | NeurIPS 2024 | [GitHub](https://github.com/example/mmtsqa) | [MMTS Dataset](https://example.com/mmts) | - |

### Journal Papers

| Paper | Journal | Code | Dataset | Model |
|-------|---------|------|---------|-------|
| **Natural Language Interfaces for Financial Time Series Analysis** | IEEE TKDE 2024 | [GitHub](https://github.com/example/fintsqa) | [FinTS-QA](https://example.com/fints) | [Model](https://example.com/model) |

### Preprints

| Paper | ArXiv | Code | Dataset | Model |
|-------|-------|------|---------|-------|
| **Zero-Shot Time Series Question Answering with Foundation Models** | [arXiv:2024.xxxxx](https://arxiv.org/abs/2024.xxxxx) | [GitHub](https://github.com/example/zero-shot-tsqa) | - | - |

## 📚 Papers by Year

### 2023

#### Conference Papers

| Paper | Venue | Code | Dataset | Model |
|-------|-------|------|---------|-------|
| **Learning to Answer Questions about Time Series Data** | ICLR 2023 | [GitHub](https://github.com/example/tsqa-learning) | [TSQA-Bench](https://example.com/tsqa-bench) | - |
| **Conversational Time Series Analysis with Large Language Models** | EMNLP 2023 | [GitHub](https://github.com/example/conv-ts) | - | [ChatTS](https://huggingface.co/chatts) |

#### Journal Papers

| Paper | Journal | Code | Dataset | Model |
|-------|---------|------|---------|-------|
| **A Survey on Time Series Question Answering** | AI Survey 2023 | - | - | - |

### 2022

#### Conference Papers

| Paper | Venue | Code | Dataset | Model |
|-------|-------|------|---------|-------|
| **Time Series Reasoning with Natural Language** | ACL 2022 | [GitHub](https://github.com/example/ts-reasoning) | [TSReason](https://example.com/tsreason) | - |
| **Neural Time Series Question Answering** | ICLR 2022 | [GitHub](https://github.com/example/neural-tsqa) | - | [NeuralTSQA](https://example.com/neuraltsqa) |

### 2021

#### Conference Papers

| Paper | Venue | Code | Dataset | Model |
|-------|-------|------|---------|-------|
| **Towards Natural Language Interfaces for Time Series Databases** | SIGMOD 2021 | [GitHub](https://github.com/example/nl-tsdb) | [TSText](https://example.com/tstext) | - |

## 📊 Datasets

### Public Datasets

| Dataset | Description | Size | Domain | Paper | Download |
|---------|-------------|------|--------|-------|----------|
| **TimeQA** | Large-scale time series QA dataset | 100K Q&A pairs | General | [Paper](https://example.com/paper) | [HuggingFace](https://huggingface.co/datasets/timeqa) |
| **FinTS-QA** | Financial time series question answering | 50K Q&A pairs | Finance | [Paper](https://example.com/paper) | [GitHub](https://github.com/example/fints-qa) |
| **HealthTS-QA** | Medical time series QA dataset | 25K Q&A pairs | Healthcare | [Paper](https://example.com/paper) | [Download](https://example.com/healthts) |
| **WeatherQA** | Weather data question answering | 75K Q&A pairs | Meteorology | [Paper](https://example.com/paper) | [Download](https://example.com/weatherqa) |

### Synthetic Datasets

| Dataset | Description | Generator | Paper | Download |
|---------|-------------|-----------|-------|----------|
| **SyntheticTSQA** | Synthetic time series QA data | [GitHub](https://github.com/example/synth-tsqa) | [Paper](https://example.com/paper) | [Download](https://example.com/synth) |

## 💻 Code Implementations

### Official Implementations

| Method | Paper | Code | Framework | License |
|--------|-------|------|-----------|---------|
| **TimeQA-Transformer** | TimeQA: A Large-Scale Dataset | [GitHub](https://github.com/example/timeqa-transformer) | PyTorch | MIT |
| **TemporalLLM** | Temporal Reasoning with LLMs | [GitHub](https://github.com/example/temporal-llm) | HuggingFace | Apache 2.0 |
| **NeuralTSQA** | Neural Time Series QA | [GitHub](https://github.com/example/neural-tsqa) | TensorFlow | BSD-3 |

### Third-party Implementations

| Method | Original Paper | Implementation | Framework | License |
|--------|----------------|----------------|-----------|---------|
| **TSQA-BERT** | Time Series BERT | [GitHub](https://github.com/example/tsqa-bert-impl) | PyTorch | MIT |

### Benchmarking Tools

| Tool | Description | Code | License |
|------|-------------|------|---------|
| **TSQA-Eval** | Evaluation framework for TSQA | [GitHub](https://github.com/example/tsqa-eval) | MIT |
| **TSBench** | Comprehensive benchmarking suite | [GitHub](https://github.com/example/tsbench) | Apache 2.0 |

## 🤖 Pre-trained Models

### Language Models

| Model | Size | Domain | Training Data | HuggingFace | Paper |
|-------|------|--------|---------------|-------------|-------|
| **TimeGPT** | 7B | General | Mixed TS+Text | [HuggingFace](https://huggingface.co/timegpt) | [Paper](https://example.com/paper) |
| **FinanceTS-BERT** | 110M | Finance | Financial data | [HuggingFace](https://huggingface.co/finance-ts-bert) | [Paper](https://example.com/paper) |
| **MedicalTS-T5** | 220M | Healthcare | Medical TS | [HuggingFace](https://huggingface.co/medical-ts-t5) | [Paper](https://example.com/paper) |

### Multimodal Models

| Model | Modalities | Size | HuggingFace | Paper |
|-------|------------|------|-------------|-------|
| **VisTSQA** | Vision + TS + Text | 500M | [HuggingFace](https://huggingface.co/vistsqa) | [Paper](https://example.com/paper) |

## 🏆 Benchmarks

### Standard Benchmarks

| Benchmark | Metrics | Datasets | Leaderboard | Paper |
|-----------|---------|----------|-------------|-------|
| **TSQA-Bench** | BLEU, ROUGE, Accuracy | 5 datasets | [Leaderboard](https://example.com/leaderboard) | [Paper](https://example.com/paper) |
| **TemporalQA** | F1, EM, Temporal Accuracy | 3 datasets | [Leaderboard](https://example.com/temporal-leaderboard) | [Paper](https://example.com/paper) |

### Domain-specific Benchmarks

| Benchmark | Domain | Metrics | Paper |
|-----------|--------|---------|-------|
| **FinTSQA-Bench** | Finance | ROI Prediction Accuracy, Risk Assessment | [Paper](https://example.com/paper) |
| **HealthTSQA-Bench** | Healthcare | Clinical Accuracy, Safety Score | [Paper](https://example.com/paper) |

## 📖 Tutorials & Surveys

### Surveys

| Title | Venue | Year | Link |
|-------|-------|------|------|
| A Comprehensive Survey on Time Series Question Answering | AI Survey | 2024 | [Paper](https://example.com/survey) |
| Natural Language Interfaces for Time Series: A Survey | ACM Computing Surveys | 2023 | [Paper](https://example.com/nl-survey) |

### Tutorials

| Title | Venue | Year | Materials |
|-------|-------|------|-----------|
| Building Time Series QA Systems | AAAI Tutorial | 2024 | [Slides](https://example.com/tutorial-slides) |
| Deep Learning for Temporal Question Answering | ICML Tutorial | 2023 | [Notebook](https://example.com/tutorial-notebook) |

### Blog Posts & Articles

| Title | Author | Date | Link |
|-------|--------|------|------|
| Getting Started with Time Series Question Answering | AI Research Blog | 2024-01 | [Blog](https://example.com/blog) |
| The Future of Conversational Time Series Analysis | Tech Medium | 2023-12 | [Medium](https://example.com/medium) |

## 🎯 Research Directions

### Emerging Topics
- **Multimodal Time Series QA**: Combining visual, textual, and temporal information
- **Few-shot Learning**: Adapting to new domains with minimal data
- **Explainable TSQA**: Providing interpretable answers and reasoning
- **Real-time QA**: Answering questions about streaming time series data
- **Cross-lingual TSQA**: Supporting multiple languages for global applications

### Open Challenges
- **Temporal Reasoning**: Understanding complex temporal relationships
- **Scalability**: Handling large-scale time series databases
- **Domain Adaptation**: Generalizing across different domains
- **Evaluation Metrics**: Developing better evaluation frameworks
- **Privacy and Security**: Protecting sensitive temporal data

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### How to Contribute

1. **Fork** the repository
2. **Create** a new branch for your contribution
3. **Add** your paper/resource following our format
4. **Submit** a pull request with a clear description

### Contribution Guidelines

- **Papers**: Include title, authors, venue, year, and links to paper/code/data
- **Code**: Ensure repositories are publicly accessible and well-documented
- **Datasets**: Provide clear descriptions, licensing information, and access instructions
- **Models**: Include model details, performance metrics, and usage instructions

### Paper Submission Format

```markdown
| **Paper Title** | Venue Year | [GitHub](link) | [Dataset](link) | [Model](link) |
```

### Quality Standards

- Papers should be peer-reviewed or from reputable preprint servers
- Code should be functional and well-documented
- Datasets should be properly licensed and accessible
- Models should include performance benchmarks

## 📄 License

This repository is licensed under the [MIT License](LICENSE).

## 📧 Contact

For questions, suggestions, or collaborations, please:
- Open an [issue](https://github.com/WYL/Awesome-Time-QA-Papers/issues)
- Submit a [pull request](https://github.com/WYL/Awesome-Time-QA-Papers/pulls)
- Contact the maintainers

## 🙏 Acknowledgments

We thank all the researchers and practitioners who have contributed to the field of Time Series Question Answering. Special thanks to the authors of the papers, datasets, and code implementations included in this repository.

---

**Star ⭐ this repository if you find it helpful!**

*Last updated: December 2024*