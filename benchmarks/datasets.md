# Dataset summary

| Dataset | Task | Type | Domain | Reference | Link | Main use | Notes |
|---|---|---|---|---|---|---|---|
| LOLv1 | LLIE | Image | sRGB | Paired | https://daooshee.github.io/BMVC2018website/ | Basic full-reference LLIE benchmark | Limited scene diversity. |
| LOLv2 | LLIE | Image | sRGB | Paired | https://github.com/flyywh/CVPR-2020-Semi-Low-Light | Real-captured and synthetic LLIE comparison | Contains real and synthetic subsets. |
| LOL-Blur | LLIE | Image | sRGB | Paired | https://github.com/sczhou/LEDNet | Joint low-light enhancement and deblurring | Useful for blur-aware LLIE evaluation. |
| LSRW | LLIE | Image | sRGB | Paired | https://github.com/JianghaiSCU/R2RNet | Real-device and cross-device robustness | Includes phone and camera subsets. |
| SID | LLIE | Image | RAW | Paired | https://github.com/cchen156/Learning-to-See-in-the-Dark | Extreme low-light RAW restoration | Short-exposure input and long-exposure reference. |
| MIT-Adobe FiveK | LLIE-related | Image | RAW | Unpaired | https://data.csail.mit.edu/graphics/fivek/ | Exposure, tone, and color adjustment | Complementary dataset rather than a dedicated low-light benchmark. |
| SDSD | LLVE | Video | sRGB | Paired | https://github.com/dvlab-research/SDSD | Dynamic LLVE and temporal evaluation | Supports frame-wise and temporal metrics. |
| DRV | LLVE | Video | RAW | Paired | https://github.com/cchen156/DRV | Extreme low-light RAW video restoration | RAW preprocessing should be reported. |
| SMOID | LLVE | Video | RAW | Paired | https://github.com/ziyao-jiang/SMOID | Gain-dependent RAW video enhancement | Useful for temporal noise stability analysis. |
| LLIV-Phone | LLVE | Video | sRGB | Unpaired | https://www.mmlab-ntu.com/project/lliv_survey/index.html | Real mobile LLVE and no-reference assessment | Reflects mobile ISP and compression variation. |
| DID | LLVE | Video | sRGB | Paired | https://github.com/ciki000/DID#dancing-in-the-dark-a-benchmark-towards-general-low-light-video-enhancement | Strong-motion LLVE and flickering analysis | Useful for motion robustness evaluation. |
