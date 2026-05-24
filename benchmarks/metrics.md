# Metric summary

| Metric | Type | Task | Direction | Main purpose | Notes |
|---|---|---|---|---|---|
| PSNR | Full-reference | LLIE / LLVE | Higher is better | Measures pixel-level fidelity | Sensitive to misalignment and exposure offsets. |
| SSIM | Full-reference | LLIE / LLVE | Higher is better | Measures structural similarity | May not fully reflect perceptual quality. |
| LPIPS | Perceptual full-reference | LLIE / LLVE | Lower is better | Measures deep feature similarity | Useful for perceptual restoration analysis. |
| NIQE | No-reference | LLIE / real LLVE | Lower is better | Measures natural image quality without references | May not always match human preference in enhanced low-light images. |
| BRISQUE | No-reference | LLIE / real LLVE | Lower is better | Measures natural scene statistics without references | Useful when aligned references are unavailable. |
| LOE | Luminance consistency | LLIE | Lower is better | Measures lightness order error | Often used to analyze illumination preservation. |
| CPCQI | Color and perceptual quality | LLIE | Higher is better | Measures color and perceptual consistency | Useful for color distortion analysis. |
| T-Warp-MSE | Temporal consistency | LLVE | Lower is better | Measures warping-based temporal error | Depends on optical flow quality. |
| tLPIPS | Temporal perceptual consistency | LLVE | Lower is better | Measures perceptual variation across frames | Useful for flickering analysis. |
| ALV | Temporal brightness consistency | LLVE | Lower is better | Measures brightness variation consistency | Implementation details should be reported. |
| ALV-Norm | Temporal brightness consistency | LLVE | Lower is better | Measures normalized brightness variation consistency | Luminance extraction and aggregation settings should be reported. |

ALV-Norm is useful for reporting normalized temporal brightness fluctuation, and implementations should report the luminance channel definition, cropping policy, and robust averaging choices for reproducibility.
