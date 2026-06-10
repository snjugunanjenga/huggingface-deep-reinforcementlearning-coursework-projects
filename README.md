# HuggingFace Deep Reinforcement Learning Coursework Projects

Comprehensive collection of course notebooks, experiments, and model assets used to explore deep reinforcement learning, transformers, and vision-language models (VLMs) with Hugging Face tools and PyTorch.

Table of Contents
- Overview
- Repository structure
- Quick start
- Notebooks & models
- Development / Environment
- Contributing
- License & Contact

Overview
--------

This repository collects hands-on coursework and experiments that demonstrate how to build, train, and evaluate deep reinforcement learning agents and transformer-based models using the Hugging Face ecosystem and PyTorch. It also contains exploratory Vision-Language Model (VLM) work under the `nemotron` directory.

Repository structure
--------------------

- `notebooks/` — Course notebooks and lab exercises (unit1, bonus materials, transformer examples).
- `nemotron/` — VLM research artifacts and model notebooks (Llama Nemotron variants).
- `transformers/` — Transformer-focused notebooks and experiments (chapter2 additions).

Quick start
-----------

1. Clone the repository and enter it:

```bash
git clone https://github.com/snjugunanjenga/huggingface-deep-reinforcementlearning-coursework-projects.git
cd huggingface-deep-reinforcementlearning-coursework-projects
```

2. Create a Python virtual environment (recommended) and install dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
# If a requirements file is added, install it like:
# pip install -r requirements.txt
```

3. Launch Jupyter Lab / Notebook and open the examples:

```bash
pip install jupyterlab
jupyter lab
```

Notebooks & models
------------------

- Start with `notebooks/unit1/lunar_landing_reinforcement_learning.ipynb` for a classic RL walkthrough.
- See `notebooks/bonus-unit1/deeprl-training-huggy.ipynb` for bonus experiments and training examples.
- VLM work is under `nemotron/VLM/llama_3.1_nemotron_nano_VL_8B/` — the notebook `Llama_Nemotron_VL_nano_8B.ipynb` contains model-specific experiments and notes.
- New transformer notebooks were added under `transformers/chapter2/` (e.g., `models_pytorch.ipynb`) to illustrate model internals with PyTorch.
	- See `transformers/chapter2/handling_multiple_sequences.ipynb` for a Colab-ready notebook on batching, padding, attention masks, and long-sequence handling.

Development / Environment
-------------------------

- Recommended Python: 3.9+ / 3.10+.
- Use a virtual environment or Conda environment to isolate dependencies.
- If you plan to run GPU workloads, ensure CUDA drivers and PyTorch with CUDA support are installed.

Contributing
------------

Contributions, bug reports, and improvements are welcome — please open an issue or submit a pull request. When contributing notebooks, try to keep outputs cleared and include a short README or notebook header describing the experiment and required dependencies.

License & Contact
-----------------

This repository currently does not include an explicit license file. Add a `LICENSE` if you want to define reuse terms. For questions or collaboration, open a GitHub issue or contact the owner at their GitHub profile: `snjugunanjenga`.

Next steps
----------

- Add a `requirements.txt` capturing tested dependencies.
- Add badges (CI, Python version, license) and a `LICENSE` file if desired.
- Optionally add short README files inside major folders (`notebooks/`, `nemotron/`) explaining their contents.
