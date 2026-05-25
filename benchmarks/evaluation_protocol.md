# Evaluation protocol notes

## Paired sRGB image enhancement

- Use LOLv1 and LOLv2 as paired sRGB LLIE benchmarks.
- Report PSNR, SSIM, and LPIPS for full-reference quality.
- NIQE and BRISQUE can be reported as supplementary no-reference indicators.

## Joint low-light enhancement and deblurring

- Use LOL-Blur for paired low-light and blur-aware evaluation.
- Report PSNR, SSIM, and LPIPS for restoration quality.
- Report LOE or CPCQI when illumination and color behavior is analyzed.

## RAW extreme low-light image restoration

- Use SID for RAW low-light image restoration.
- Report RAW preprocessing details and evaluation conversion settings.
- Report PSNR, SSIM, and optional LPIPS after consistent processing.

## Paired sRGB low-light video enhancement

- Use SDSD and DID for paired sRGB LLVE evaluation.
- Report frame-wise metrics and temporal metrics jointly.
- Include T-Warp-MSE, tLPIPS, ALV, or ALV-Norm for temporal consistency.

## RAW low-light video restoration

- Use DRV and SMOID for RAW LLVE evaluation.
- Report RAW pipeline details, including demosaicing and normalization.
- Include PSNR/SSIM and temporal metrics for stability analysis.

## Real mobile low-light video

- Use LLIV-Phone for real mobile low-light video analysis.
- Prefer no-reference metrics such as NIQE and BRISQUE when references are unavailable.
- Report temporal metrics when frame correspondences are available.
