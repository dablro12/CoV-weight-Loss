# CoV-weight-Loss
2023-ICMRI Accepted Abstract : How to optimize weighted losses with automatic system

Title
Automatic optimization of Multi-Loss Weights for MR image synthesis using Coefficient of Variation Analysis
 
Authors 정우진, 최대현, 강연아, 이호준, 남윤호
 
Objective
Recently, deep learning-based medical image synthesis has been suggested in various applications such as modality or contrast conversion tasks. In these tasks, it is common to use a combination of multiple loss functions to improve the quality of synthetic images. However, most previous studies rely on empirical methods to determine the weight of each loss function. This heuristic approach is difficult to guarantee optimal results and can be time-consuming. In this work, we investigate an automatic algorithm for determining the optimal combination of loss function weights for medical image synthesis.
 
Methods
We synthesized the delayed post contrast MR images (1 hour) from the early post contrast MR images (10 minutes) using MRI collected from 80 subjects (56 for model train and 24 model test) as described in Figure 1. To determine the weights of multiple loss functions automatically, we implemented a method based on coefficient of variation for loss functions summarized in the following four steps: 1) Setting up multiple loss functions. 2) Calculate the rate of change of loss functions. 3) Introduction of Coefficient of Variation (CoV) algorithm. 4) Performance optimization. For comparison, training with only a single loss, training with equal weights and training with heuristic approaches (hand-tuned weights) were also performed. To evaluate quantitatively, PSNR, SSIM, RMSE metrics were calculated for test set (N=24).
 
 
Results
The quantitative results for test set are summarized in Figure 3. The proposed method showed the best performance for PSNR and RMSE, and the hand-tuned method showed the best performance for SSIM. Figure 4 shows the representative synthesized images with the corresponding actual MR images.
 
Conclusions
The proposed method demonstrated the ability of automatic optimization for the weights of multiple loss functions. This could reduce the time and computational cost of adjusting the weight ratios of multiple loss functions.
 
Keywords
Multi Loss function, Image synthesis, coefficient of variation, loss combination.
