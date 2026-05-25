# Transformer-related low-light image enhancement methods

## End-to-end methods

| Year | Method | Venue | Paper | Code | Transformer-related role | Key idea |
|---|---|---|---|---|---|---|
| 2021 | STAR | ICCV 2021 | https://doi.org/10.1109/ICCV48922.2021.00407 | https://github.com/zzyfd/STAR-pytorch | Uses Transformer-related representation learning for direct enhancement. | Early Transformer-related LLIE method. |
| 2022 | TPET | Engineering Applications of Artificial Intelligence 2022 | https://doi.org/10.1016/j.engappai.2022.105411 | Not given | Uses Transformer-related modules for direct exposure-aware processing. | Focuses on Transformer-related exposure or enhancement modeling. |
| 2023 | LLFormer | AAAI 2023 | https://doi.org/10.1609/aaai.v37i3.25364 | https://github.com/TaoWangzj/LLFormer | Uses efficient Transformer design in an end-to-end LLIE pipeline. | Focuses on UHD low-light image enhancement. |
| 2023 | Retinexformer | ICCV 2023 | https://doi.org/10.1109/ICCV51070.2023.01149 | https://github.com/caiyuanhao1998/Retinexformer | Uses illumination-guided Transformer interaction in a one-stage Retinex-based framework. | Uses illumination-aware Retinex-guided enhancement. |
| 2023 | LRT | IEEE Transactions on Image Processing 2023 | https://doi.org/10.1109/TIP.2023.3297412 | Not given | Uses Transformer-related restoration modeling for dark light-field images. | Focuses on low-light restoration for dark light-field inputs. |
| 2023 | STGNet | IEEE Transactions on Circuits and Systems for Video Technology 2023 | https://doi.org/10.1109/TCSVT.2023.3239511 | Not given | Uses structure-guided Transformer-related feature processing. | Uses stage-transformer guidance for structure-preserving enhancement. |
| 2024 | BiFormer | IEEE Transactions on Multimedia 2024 | https://doi.org/10.1109/TMM.2024.3413293 | Not given | Uses bilateral interaction with Transformer-related feature modeling. | Uses bilateral interaction for local-global collaborative perception. |
| 2024 | MPC-Net | IEEE Transactions on Circuits and Systems for Video Technology 2024 | https://doi.org/10.1109/TCSVT.2024.3408007 | https://github.com/Shecyy/MPC-Net | Uses multi-prior collaborative modeling with Transformer-related components. | Uses prior-guided low-light enhancement. |
| 2025 | SG-LLIE | arXiv 2025 | https://arxiv.org/abs/2504.14075 | https://github.com/minyan8/imagine | Uses structure-guided CNN-Transformer hybrid aggregation. | Uses scale-aware and structure-guided low-light enhancement. |
| 2026 | PTM-SNet | Neural Networks 2026 | https://doi.org/10.1016/j.neunet.2025.108351 | https://github.com/kbzhang0505/PTMSNet | Uses pseudo-texture-aware or frequency-aware Transformer processing. | Focuses on progressive frequency-aware multi-scale enhancement. |

## Decomposition-based methods

| Year | Method | Venue | Paper | Code | Transformer-related role | Key idea |
|---|---|---|---|---|---|---|
| 2025 | TIMRetinex-Net | Engineering Applications of Artificial Intelligence 2025 | https://doi.org/10.1016/j.engappai.2025.112414 | Not given | Uses Retinex decomposition with Transformer-related illumination-aware mechanisms. | Uses Retinex-based decomposition for controllable enhancement. |
| 2025 | HVI-CIDNet | CVPR 2025 | https://doi.org/10.1109/CVPR52734.2025.00533 | https://github.com/Fediory/HVI-CIDNet | Uses Transformer-related interaction under HVI-oriented representation. | Uses HVI color representation and color-intensity decoupling. |
| 2026 | DecoupleNet | Pattern Recognition 2026 | https://doi.org/10.1016/j.patcog.2025.112203 | https://github.com/drafly/decouplenet | Uses decoupled Transformer-related components for restoration stages. | Uses domain-specific task decoupling for low-light enhancement. |

## Condition-based methods

| Year | Method | Venue | Paper | Code | Transformer-related role | Key idea |
|---|---|---|---|---|---|---|
| 2022 | SNR-aware Enhancement | CVPR 2022 | https://doi.org/10.1109/CVPR52688.2022.01719 | https://github.com/JIA-Lab-research/SNR-Aware-Low-Light-Enhance | Uses condition-aware Transformer-related adaptation from SNR priors. | Uses SNR priors for spatially adaptive enhancement. |
| 2022 | IAT | BMVC 2022 | https://arxiv.org/abs/2205.14871 | https://github.com/cuiziteng/Illumination-Adaptive-Transformer | Uses illumination-adaptive transformation with Transformer-related modeling. | Uses illumination-adaptive transformation for exposure correction. |
| 2023 | Wang et al. | ICCV 2023 | https://doi.org/10.1109/ICCV51070.2023.01207 | Not given | Uses illumination-aware gamma correction and complete image modeling. | Uses curve-related guidance for low-light enhancement. |
| 2024 | CodedBGT | IEEE Transactions on Multimedia 2024 | https://doi.org/10.1109/TMM.2024.3400668 | Not given | Uses code-bank guidance with Transformer-related enhancement blocks. | Uses coded brightness transformation for low-light enhancement. |
| 2024 | Liang et al. | IEEE Internet of Things Journal 2025 | https://doi.org/10.1109/JIOT.2024.3503766 | Not given | Uses multi-scale Transformer modeling with visible-infrared cues. | Connects low-light enhancement with visible-infrared person re-identification. |
| 2024 | UPT-Flow | Pattern Recognition 2025 | https://doi.org/10.1016/j.patcog.2024.111076 | https://github.com/NJUPT-IPR-XuLintao/UPT-Flow | Uses flow-related generative modeling with Transformer-related design. | Uses unbalanced point-map guidance and normalizing flow. |
| 2026 | CSTG-CWHFlow | Pattern Recognition 2026 | https://doi.org/10.1016/j.patcog.2026.113536 | https://github.com/NJUPT-IPR-JingDH/CSTG-CWHFlow | Uses flow-oriented conditional modeling with Transformer-related design. | Uses compressive self-attention and flow-related enhancement. |
| 2026 | IGA-Net | Expert Systems with Applications 2026 | https://doi.org/10.1016/j.eswa.2025.129492 | Not given | Uses illumination-guided adaptive feature optimization. | Uses iterative illumination-guided enhancement. |
| 2026 | Mao et al. | IEEE Transactions on Pattern Analysis and Machine Intelligence 2026 | https://doi.org/10.1109/TPAMI.2026.3658598 | https://github.com/XLearning-SCU/Awesome-All-In-One-Image-Restoration | Uses all-in-one Transformer restoration under adverse degradations. | Provides a degradation-conditioned restoration reference beyond pure LLIE. |

## Frequency-domain methods

| Year | Method | Venue | Paper | Code | Transformer-related role | Key idea |
|---|---|---|---|---|---|---|
| 2024 | SFHFormer | ECCV 2024 | https://doi.org/10.1007/978-3-031-72995-9_22 | https://github.com/deng-ai-lab/SFHformer | Uses frequency-related Transformer feature modeling. | Focuses on spatial-frequency hybrid image restoration. |
| 2025 | Tu et al. | IEEE Transactions on Image Processing 2025 | https://doi.org/10.1109/TIP.2025.3592559 | https://github.com/Jabruson/FDN-TIP2025 | Uses Fourier-domain decoupling with cross-domain modeling. | Balances low-light enhancement and deblurring through Fourier priors. |
| 2025 | DarkIR | CVPR 2025 | https://doi.org/10.1109/CVPR52734.2025.01016 | https://github.com/cidautai/DarkIR | Uses spatial-frequency processing for dark image restoration. | Focuses on robust low-light image restoration. |
| 2026 | LFT-Net | Pattern Recognition 2026 | https://doi.org/10.1016/j.patcog.2025.112887 | https://github.com/Qqsoe/low-light-enhancement | Uses Fourier-related Transformer components. | Focuses on lightweight frequency-based enhancement. |
| 2025 | SDTL | IEEE Transactions on Multimedia 2025 | https://doi.org/10.1109/TMM.2025.3613117 | Not given | Uses wavelet-domain diffusion Transformer modeling. | Connects frequency-domain modeling with generative restoration. |

## Generative methods

| Year | Method | Venue | Paper | Code | Transformer-related role | Key idea |
|---|---|---|---|---|---|---|
| 2024 | RetiDiff | arXiv 2024 | https://arxiv.org/abs/2311.11638 | https://github.com/ChunmingHe/Reti-Diff | Uses generative diffusion with Transformer-related components. | Uses Retinex-related latent diffusion for illumination degradation restoration. |
| 2025 | GPP-LLIE | AAAI 2025 | https://doi.org/10.1609/aaai.v39i10.33168 | https://github.com/LowLevelAI/GPP-LLIE | Uses generative perceptual priors with Transformer-related modeling. | Uses generative priors for low-light enhancement. |
| 2025 | Reffusion | Knowledge-Based Systems 2025 | https://doi.org/10.1016/j.knosys.2025.112998 | Not given | Uses diffusion with dual-domain Transformer interaction. | Combines conditional diffusion with spatial-frequency restoration. |
| 2025 | TransDiff | Neurocomputing 2025 | https://doi.org/10.1016/j.neucom.2025.131174 | Not given | Uses Transformer-based diffusion modeling. | Uses diffusion restoration for low-light image enhancement. |
