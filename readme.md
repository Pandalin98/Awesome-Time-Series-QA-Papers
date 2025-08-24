# Awesome Time Series Question Answering Papers

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated collection of research papers, code implementations, datasets, and models for Time Series Question Answering (TSQA). This repository aims to provide a comprehensive resource for researchers and practitioners working on time series analysis and natural language processing intersection.

## 📋 Table of Contents

- [Overview](#overview)
- [Recent Papers (2025)](#recent-papers-2025)
- [Papers by Year](#papers-by-year)
  - [2024](#2024)
- [Datasets](#datasets)
- [Code Implementations](#code-implementations)
- [Pre-trained Models](#pre-trained-models)
- [Benchmarks](#benchmarks)
- [Surveys](#tutorials--surveys)
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

## 📈 Recent Papers (2025)

### 2025

### Conference Papers

| Paper                                                        | Venue                                         | Code                                                  | Dataset                                                      | Model |
| ------------------------------------------------------------ | --------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------ | ----- |
| **ITFormer: Bridging Time Series and Natural Language for Multi-Modal QA with Large-Scale Multitask Dataset** | [ICML 2025](http://arxiv.org/abs/2506.20093)  | [Github](https://pandalin98.github.io/itformer_site/) | [EngineMT-QA Dataset](https://pandalin98.github.io/itformer_site/) | -     |
| **ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data** | [AAAI 2025](https://arxiv.org/pdf/2412.11376) | [GitHub](https://github.com/ForestsKing/ChatTime)     | [ChatTime Dataset](https://github.com/ForestsKing/ChatTime/tree/main/dataset) | -     |
| **ChatTS: Aligning Time Series with LLMs via Synthetic Data for Enhanced Understanding and Reasoning** | [VLDB 2025](https://arxiv.org/abs/2412.03104) | [GitHub](https://github.com/NetManAIOps/ChatTS)     | [Huggingface](https://huggingface.co/datasets/ChatTSRepo/ChatTS-Training-Dataset) | [Huggingface](https://huggingface.co/bytedance-research/ChatTS-14B)     |

### Preprints

| Paper                                                        | ArXiv                                                  | Code                                                         | Dataset                                                      | Model                                          |
| ------------------------------------------------------------ | ------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------- |
| **Time-MQA: Time Series Multi-Task Question Answering with Context Enhancement** | [arxiv:202503.01875](https://arxiv.org/pdf/2503.01875) | [Hugging Face](https://huggingface.co/Time-QA)               | [Hugging Face](https://huggingface.co/Time-QA)               | [Hugging Face](https://huggingface.co/Time-QA) |
| **MTBench: A Multimodal Time Series Benchmark for Temporal Reasoning and Question Answering** | [arxiv:202503.16858](https://arxiv.org/pdf/2503.16858) | [Github](https://github.com/Graph-and-Geometric-Learning/MTBench) | [MTBench Dateset](https://github.com/Graph-and-Geometric-Learning/MTBench/tree/mainline/data_preparation) | -                                              |
| **SensorQA: A Question Answering Benchmark for Daily-Life Monitoring** | [arxiv:202501.04974](https://arxiv.org/pdf/2501.04974) | [Github](https://github.com/benjamin-reichman/SensorQA)      | [SensorQA Dataset](https://github.com/benjamin-reichman/SensorQA?tab=readme-ov-file) | -                                              |
| **SensorChat: Answering Qualitative and Quantitative Questions during Long-Term Multimodal Sensor Interactions** | [arxiv:202502.02883](https://arxiv.org/pdf/2502.02883) | [Github](https://github.com/benjamin-reichman/SensorQA)      | [SensorChat Dataset](https://github.com/benjamin-reichman/SensorQA?tab=readme-ov-file) | -                                              |
| **Heartcare Suite: Multi-dimensional Understanding of ECGwith RawMulti-lead Signal Modeling** | [arxiv:202506.05831](https://arxiv.org/pdf/2506.05831) | [Github](https://github.com/DCDmllm/Heartcare-Suite)         | [Heartcare-220K](https://arxiv.org/pdf/2506.05831)           | -                                              |
| **Chat-TS: Enhancing Multi-Modal Reasoning Over Time-Series and Natural Language Data** | [arxiv:202503.10883](https://arxiv.org/pdf/2503.10883) | -                                                            | -                                                            | -                                              |
| **ChronoSteer: Bridging Large Language Model and Time Series Foundation Model via Synthetic Data** | [arXiv:202505.10083](https://arxiv.org/pdf/2505.10083) | -                                                            | -                                                            | -                                              |

## 📚 Papers by Year

### 2024

### Conference Papers

| Paper                                                        | Venue                                                        | Code                                                       | Dataset                                                      | Model |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------------------- | ------------------------------------------------------------ | ----- |
| **Language Models Still Struggle to Zero-shot Reason about Time Series** | [ACL 2024](https://aclanthology.org/2024.findings-emnlp.201.pdf) | [Github](https://github.com/behavioral-data/TSandLanguage) | [TSandLanguage Data](https://github.com/behavioral-data/TSandLanguage/tree/main/data) | -     |
| **Demo: A Real Time Question Answering System for Multimodal Sensors using LLMs** | [SENSYS 2024](https://dl.acm.org/doi/proceedings/10.1145/3666025) | -                                                          | -                                                            | -     |

### Preprints

| Paper                                                | ArXiv                                                | Code                                                         | Dataset                                                      | Model |
| ---------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----- |
| **Interpretable LLM-based Table Question Answering** | [arXiv:2412.12386](https://arxiv.org/abs/2412.12386) | [Github](https://github.com/giangnguyen2412/Plan-of-SQLs-TMLR2025) | [TMLR Dataset](https://github.com/giangnguyen2412/Plan-of-SQLs-TMLR2025/blob/main/data.zip) | -     |
| **Can LLMs Serve As Time Series Anomaly Detectors?** | [arXiv:2408.03475](https://arxiv.org/abs/2408.03475) | -                                                            | -                                                            | -     |
| **Towards Time Series Reasoning with LLMs**          | [arXiv:2409.11376](https://arxiv.org/pdf/2409.11376) | -                                                            | -                                                            | -     |

## 📊 Datasets

### Public Datasets

| Dataset                 | Description                                                  | Size           | Domain                   | Paper                                                      | Download                                                     |
| ----------------------- | ------------------------------------------------------------ | -------------- | ------------------------ | ---------------------------------------------------------- | ------------------------------------------------------------ |
| **EngineMT-QA Dataset** | The field of aero engines time series QA dataset             | 110K Q&A pairs | Aero Engine              | [Paper](http://arxiv.org/abs/2506.20093)                   | [Github](https://pandalin98.github.io/itformer_site/)        |
| **Chat-Time QA**        | General time series QA dataset                               | 48K Q&A pairs  | General                  | [Paper](https://huggingface.co/datasets/ChengsenWang/TSQA) | [HuggingFace](https://huggingface.co/datasets/ChengsenWang/TSQA) |
| **SensorQA**            | Wearable device TS - Text question and answer pairs          | 5.6K Q&A pairs | Sensor                   | [Paper](https://arxiv.org/pdf/2501.04974)                  | [Github](https://github.com/benjamin-reichman/SensorQA?tab=readme-ov-file) |
| **Heartcare-220K**      | Time series QA dataset in the field of electrocardiogram signals | 220K Q&A pairs | Electrocardiogram signal | [Paper](https://arxiv.org/pdf/2506.05831)                  | [Github](https://arxiv.org/pdf/2506.05831)                   |
| **TMLR Dataset**        | Three standard Table QA datasets: fact verification, question answering, and free-form generation | 8k Q&A pairs   | General                  | [Paper](https://arxiv.org/pdf/2412.12386)                  | [Github](https://github.com/giangnguyen2412/Plan-of-SQLs-TMLR2025/blob/main/data.zip) |
| **Time-MQA**            | General time series QA dataset                               | 200k Q&A pairs | General                  | [Paper](https://arxiv.org/pdf/2503.01875)                  | [Hugging Face](https://huggingface.co/Time-QA)               |
| **MTBench-Dateset**     | The field of finance and weather time series QA dataset      | -              | Finance & Weather        | [paper](https://arxiv.org/pdf/2503.16858)                  | [MTBench Dateset](https://github.com/Graph-and-Geometric-Learning/MTBench/tree/mainline/data_preparation) |

### Synthetic Datasets

| Dataset             | Description                                                  | Generator | Paper                                                        | Download                                                     |
| ------------------- | ------------------------------------------------------------ | --------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **TS and Language** | Contains 87,000 pairs of time series and text descriptions covering 10 areas such as health care, finance, agriculture, transportation, entertainment, etc. | GPT-4     | [ACL 2024](https://aclanthology.org/2024.findings-emnlp.201.pdf) | [Github](https://github.com/behavioral-data/TSandLanguage/tree/main/data) |

## 💻 Code Implementations

### Official Implementations

| Method                                                       | Paper                                                        | Code                                                         | Framework | License      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | --------- | ------------ |
| **ITFormer: Bridging Time Series and Natural Language for Multi-Modal QA with Large-Scale Multitask Dataset** | [ICML 2025](http://arxiv.org/abs/2506.20093)                 | [Github](https://pandalin98.github.io/itformer_site/)        | Pytorch   | MIT          |
| **ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data** | [arxiv:2412.11376](https://arxiv.org/pdf/2412.11376)         | [GitHub](https://github.com/ForestsKing/ChatTime)            | Pytorch   | -            |
| **MTBench: A Multimodal Time Series Benchmark for Temporal Reasoning and Question Answering** | [arxiv:202503.16858](https://arxiv.org/pdf/2503.16858)       | [Github](https://github.com/Graph-and-Geometric-Learning/MTBench) | Pytorch   | MIT          |
| **SensorQA: A Question Answering Benchmark for Daily-Life Monitoring** | [arxiv:202501.04974](https://arxiv.org/pdf/2501.04974)       | [Github](https://github.com/benjamin-reichman/SensorQA)      | Pytorch   | CC BY-SA 4.0 |
| **Heartcare Suite: Multi-dimensional Understanding of ECG with Raw Multi-lead Signal Modeling** | [arxiv:202506.05831](https://arxiv.org/pdf/2506.05831)       | [Github](https://arxiv.org/pdf/2506.05831)                   | Pytorch   | -            |
| **Interpretable LLM-based Table Question Answering**         | [arXiv:2412.12386](https://arxiv.org/pdf/2412.12386)         | [Github](https://github.com/giangnguyen2412/Plan-of-SQLs-TMLR2025) | -         | MIT          |
| **Language Models Still Struggle to Zero-shot Reason about Time Series** | [ACL 2024](https://aclanthology.org/2024.findings-emnlp.201.pdf) | [Github](https://github.com/behavioral-data/TSandLanguage)   | -         | MIT          |

### Third-party Implementations

| Method         | Original Paper                               | Implementation                                          | Framework | License      |
| -------------- | -------------------------------------------- | ------------------------------------------------------- | --------- | ------------ |
| **SensorChat** | [SensorQA](https://arxiv.org/pdf/2501.04974) | [Github](https://github.com/benjamin-reichman/SensorQA) | Pytoch    | CC BY-SA 4.0 |

### Benchmarking Tools

| Tool                                                         | Description                                  | Code                                                         | License |
| ------------------------------------------------------------ | -------------------------------------------- | ------------------------------------------------------------ | ------- |
| **MTBench: A Multimodal Time Series Benchmark for Temporal Reasoning and Question Answering** | Finance & Weather benchmarking suite         | [Github](https://github.com/Graph-and-Geometric-Learning/MTBench) | -       |
| **Heartcare Suite: Multi-dimensional Understanding of ECG with Raw Multi-lead Signal Modeling** | Benchmarks in the field of electrocardiogram | [Github](https://arxiv.org/pdf/2506.05831)                   | -       |
| **Interpretable LLM-based Table Question Answering**         | Comprehensive benchmarking suite             | [Github](https://github.com/giangnguyen2412/Plan-of-SQLs-TMLR2025) | -       |

## 🤖 Pre-trained Models

### Language Models

| Model              | Size | Domain  | Training Data | HuggingFace                                                  | Paper                                                      |
| ------------------ | ---- | ------- | ------------- | ------------------------------------------------------------ | ---------------------------------------------------------- |
| **Chat-Time-1-7B** | 7B   | General | Mixed TS+Text | [HuggingFace](https://huggingface.co/ChengsenWang/ChatTime-1-7B-Chat) | [Paper](https://huggingface.co/datasets/ChengsenWang/TSQA) |

## 🏆 Benchmarks

### Standard Benchmarks

| Benchmark        | Metrics                                | Datasets   | Leaderboard | Paper                                     |
| ---------------- | -------------------------------------- | ---------- | ----------- | ----------------------------------------- |
| **TMLR Dataset** | QA Accuracy\Interpretability\Agreement | 3 datasets | -           | [Paper](https://arxiv.org/pdf/2412.12386) |

### Domain-specific Benchmarks

| Benchmark                                                    | Domain            | Metrics                | Paper                                     |
| ------------------------------------------------------------ | ----------------- | ---------------------- | ----------------------------------------- |
| **MTBench: A Multimodal Time Series Benchmark for Temporal Reasoning and Question Answering** | Finance & Weather | MAE & MSE & Acc        | [Paper](https://arxiv.org/pdf/2503.16858) |
| **Heartcare Suite: Multi-dimensional Understanding of ECG with Raw Multi-lead Signal Modeling** | electrocardiogram | Acc & F1-Rad & Rouge-L | [Paper](https://arxiv.org/pdf/2506.05831) |

## 📖 Tutorials & Surveys

### Surveys

| Title                                                        | Venue | Year | Link                                              |
| ------------------------------------------------------------ | ----- | ---- | ------------------------------------------------- |
| **How Can Time Series Analysis Benefit From Multiple Modalities? A Survey and Outlook** | arxiv | 2025 | [Paper](https://arxiv.org/abs/2503.11835)         |
| **Position: What Can Large Language Models Tell Us about Time Series Analysis** | ICML  | 2024 | [Paper](https://openreview.net/pdf?id=iroZNDxFJZ) |

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

*Last updated: August 2025