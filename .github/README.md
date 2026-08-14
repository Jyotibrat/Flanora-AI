# Flanora AI — Evaluation

This repository contains the evaluation code, results, and generated
outputs used to evaluate **Flanora AI**, a floor-plan generation model
based on a fine-tuned Canny ControlNet and Stable Diffusion v1.5.

## Evaluation

The model was evaluated on a held-out test set of **67 samples**
covering 0–5 bedroom floor plans.

The evaluation includes:

- Automatic image metrics
- Per-class results
- Reliability analysis
- Prompt robustness analysis
- Manual structural evaluation

### Overall Results

For Results check out the `evaluation` Directory.

## Evaluation Results

Detailed results and generated evaluation images are available in the
`evaluation/` directory.

The repository contains:

- `automatic_evaluation_results.csv`
- `manual_evaluation.csv`
- `per_class_results.csv`
- `reliability_results.csv`
- `robustness_results.csv`
- `evaluation_images/`

## Model

**Flanora AI**

**Demo:** [https://flanora-ai.vercel.app/](https://flanora-ai.vercel.app/)

## Author

- **Ansh Gaur**
- **Rana Talukdar ([Rana-15](https://huggingface.co/Rana-15))**
- **Bindupautra Jyotibrat ([BJyotibrat](https://huggingface.co/BJyotibrat))**


## License

This repository is licensed under the [**GNU General Public License
v3.0 (GPL-3.0)**](LICENSE).