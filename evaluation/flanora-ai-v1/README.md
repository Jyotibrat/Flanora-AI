# Flanora AI v1 — Evaluation

This directory contains the evaluation results and generated images for
**Flanora AI v1**.

The model was evaluated on a held-out test set of **67 samples** covering
0–5 bedroom floor plans.

## Contents

```
flanora-ai-v1/
├── evaluation_images/
├── automatic_evaluation_results.csv
├── manual_evaluation.csv
├── per_class_results.csv
├── reliability_results.csv
└── robustness_results.csv
```

# Evaluation Files

- **automatic_evaluation_results.csv** — Automatic image-based metrics
including Edge IoU, Chamfer Distance, Edge SSIM, and CLIP Similarity.
- **manual_evaluation.csv** — Manually evaluated structural properties
including bedroom count, room connectivity, wall validity, and door
validity.
- **per_class_results.csv** — Results grouped by bedroom-count category.
- **reliability_results.csv** — Reliability and consistency results,
including Mean Consistency Edge IoU.
- **robustness_results.csv** — Prompt robustness evaluation results.
- **evaluation_images/** — Generated images from the evaluation set.
# Overall Results

| Metric | Result |
|---|---:|
| Mean Edge IoU | 0.1341 |
| Median Edge IoU | 0.1316 |
| Mean Chamfer Distance | 4.3802 |
| Median Chamfer Distance | 3.9137 |
| Mean Edge SSIM | 0.7433 |
| Mean CLIP Similarity | 0.3071 |
| Mean Consistency Edge IoU | 0.1531 |
| Mean Prompt Robustness Edge IoU | 0.3509 |

The individual CSV files contain the detailed evaluation results.

# Related

- **Dataset:** https://huggingface.co/datasets/BJyotibrat/ROBIN-ImagesGT-Merged-Flanora-AI-v1
- **Demo:** https://flanora-ai.vercel.app/