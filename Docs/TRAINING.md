# Training

The model was fine-tuned using Stable Diffusion
v1.5 with a Canny ControlNet.

The training pipeline consisted of:

1. Floor-plan dataset preprocessing
2. Canny edge extraction
3. Bedroom-category labeling
4. Stratified train/validation/test splitting
5. Stable Diffusion v1.5 initialization
6. Canny ControlNet initialization
7. ControlNet fine-tuning
8. Weights & Biases training logging

The complete training notebook can be added to this
directory separately if reproducibility is required.
