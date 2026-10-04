<div align="center">
    <p align="center">
        <a href="https://wikipedia.org/wiki/PyTorch">
          <img width="25%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/PyTorch_logo.svg" />
        </a>
    </p>

```mermaid
graph TD

    PT[PyTorch]

    PT --> CV[Computer Vision]
    PT --> NLP[Natural Language Processing]
    PT --> GNN[Graph Neural Networks]
    PT --> RL[Reinforcement Learning]
    PT --> LLM[Large Language Models]
    PT --> MLOPS[MLOps]

    CV --> TV[TorchVision]
    CV --> DET[Detectron2]
    CV --> MMDET[MMDetection]

    NLP --> HF[Transformers]
    NLP --> FS[Fairseq]
    NLP --> SB[Sentence Transformers]

    GNN --> PYG[PyTorch Geometric]
    GNN --> DGL[Deep Graph Library]

    RL --> TRL[TorchRL]
    RL --> SB3[Stable Baselines3]

    LLM --> HF2[HuggingFace]
    LLM --> PEFT[PEFT]
    LLM --> TRL2[Transformer RLHF]
    LLM --> DeepSpeed
    LLM --> MegatronLM

    MLOPS --> Lightning[Lightning AI]
    MLOPS --> MLflow
    MLOPS --> WeightsBiases
    MLOPS --> Kubeflow
```

# **`Awesome`** [PyTorch](https://pytorch.org/) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/pytorch/new/)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefence"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
timeline
    title PyTorch Evolution Timeline

    2016 : PyTorch Initial Release
         : Dynamic Computation Graph
         : Torch + Python Integration

    2017 : Growing Research Adoption
         : Autograd Improvements
         : CUDA Optimization

    2018 : PyTorch 1.0 Announcement
         : Unified Frontend
         : TorchScript Introduced

    2019 : PyTorch 1.2
         : TorchServe
         : Quantization Support

    2020 : PyTorch Lightning Popularity
         : Distributed Training Expansion

    2021 : PyTorch 1.10
         : Better Mobile Support
         : Ecosystem Growth

    2022 : PyTorch 2.0 Preview
         : TorchDynamo
         : TorchInductor

    2023 : PyTorch 2.0 Release
         : Compile Mode
         : Faster Execution

    2024 : Advanced AI Ecosystem
         : LLM Training Frameworks
         : Multimodal Models

    2025+ : Agentic AI
          : Large-scale Foundation Models
          : Enterprise AI Deployment
```

## 📖 Contents
- [Installation Steps](#installation-steps)
- [My Awesome Lists](#my-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)

---
---

## Installation Steps

* Linux
    * CPU
        ```bash
        pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cpu
        ```
    * GPU
        ```bash
        pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu130
        ```
* Windows
  * CPU
      ```powershell
      pip3 install torch torchvision
      ```
  * GPU
      ```powershell
      pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu130
      ```
Test
```shell
python -c "import torch; print(torch.__version__)"
```

##

### My Awesome Lists
You can access the my awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-pytorch/graphs/contributors)!

[🔼 Back to top](#awesome-pytorch-)
