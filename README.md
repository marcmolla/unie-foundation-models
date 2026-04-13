# Foundation Model Laboratories

**Laboratory notebooks** for the Foundation Models subject, covering the full lifecycle of working with large language models: from first inference to building AI agents.

**Purpose**

This repository provides hands-on labs that progressively introduce how to use, adapt, and deploy foundation models. Topics include prompt engineering, retrieval-augmented generation, fine-tuning, quantization, knowledge distillation, and AI agent development with LangChain.

## Project Structure

```bash
.
├── datasets/                                       # Datasets for labs (if applicable)
├── src/
│   ├── Lab 1. Introduction.ipynb                   # Environment setup, pipelines, chat format
│   ├── Lab 2. Architecture.ipynb                   # Models, tokenizers, attention internals
│   ├── Lab 3. Adaptations.ipynb                    # Prompt engineering, RAG, fine-tuning, quantization
│   ├── Lab 4. Agents.ipynb                         # AI agents with LangChain, tools, skills, routers
│   ├── Lab 5. SotA and Future Directions.ipynb     # State of the art and future directions
│   └── img/                                        # Images used in notebooks
├── requirements.txt
├── local_requirements.txt                          # Full Kaggle-compatible dependencies
├── LICENSE                                         # MIT License
└── README.md
```

## Copyright and License

- **© 2026 Marc Mollà Roselló**
- **Code**: MIT License

Developed and tested on:

- **Python ≥ 3.12**
- **Dependencies:** see requirements.txt file

## Quick start

```bash
# Create and activate environment
python3 -m venv .venv
source .venv/bin/activate      # macOS/Linux
.venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt

# Run notebooks
jupyter notebook src/
```

> **Note:** The default installation uses PyTorch compatible with CPU. On Mac with Apple Silicon, `mps` is used automatically. For GPU support on Linux/Windows, install the appropriate CUDA version of PyTorch. See `local_requirements.txt` for the full Kaggle-compatible environment.

**Disclaimer**: Provided *as is*, for academic use only.
