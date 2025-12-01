# Bench2Drive Leaderboard
[Bench2Drive](https://github.com/Thinklab-SJTU/Bench2Drive) is a popular autonomous driving benchmark. Over 40 methods have been tested on Bench2Drive. Papers using the benchmark usually only report a few baselines due to space constraints making it hard to keep an overview over the literature.
To solve this, this repository contains a complete list of all methods that have currently been tested on Bench2Drive.

The results are from Bench2Drive version 0.0.3 and self-reported, copied from the respective publications. 
Methods are sorted by Driving Score (DS).
At the bottom of the table, separated by a line, are privileged methods that use ground truth perception as input.
This leaderboard compares the final performance of entire methods, including data acquisition methods, not just architectures.
Methods vary among many axes: driving dataset used, pre-training strategy, training compute, inference compute, number of parameters, IL/RL, etc.
In particular, many (4/5) of the current top-performing methods use the [PDM-Lite dataset](https://github.com/autonomousvision/carla_garage).

To add a new method please open a pull request. For fixing errors please open a GitHub issue.

[Main.tex](main.tex) contains the leaderboard table as latex with the associated citations in CVPR-style.

Last updated: 10. Nov. 2025

## Results:

| Method                                                                                                                          |   DS ↑   |   SR ↑    | Year |      Venue       |
|:--------------------------------------------------------------------------------------------------------------------------------|:--------:|:---------:| :--: |:----------------:|
| [AD-MLP](https://arxiv.org/abs/2305.10430)                                                                                      |  18.05   |   0.00    | 2023 |        -         |
| [TCP](https://arxiv.org/abs/2206.08129)                                                                                         |  40.70   |   15.00   | 2022 |     NeurIPS      |
| [ReAL-AD](https://arxiv.org/abs/2507.12499)                                                                                     |  41.17   |   11.36   | 2025 |        -         |
| [VAD](https://arxiv.org/abs/2303.12077)                                                                                         |  42.35   |   15.00   | 2023 |       ICCV       |
| [SparseDrive](https://arxiv.org/abs/2405.19620)                                                                                 |  44.54   |   16.71   | 2025 |       ICRA       |
| [GenAD](https://arxiv.org/abs/2403.09630)                                                                                       |  44.81   |   15.90   | 2024 |       ECCV       |
| [Dual-AEB](https://arxiv.org/abs/2410.08616)                                                                                    |  45.23   |   10.00   | 2025 |       ICRA       |
| [FUMP](https://arxiv.org/abs/2504.12667)                                                                                        |  45.67   |   16.36   | 2025 |        -         |
| [FocalAD](https://arxiv.org/abs/2506.11419)                                                                                     |  45.77   |   17.30   | 2025 |        -         |
| [UniAD](https://arxiv.org/abs/2212.10156)                                                                                       |  45.81   |   16.36   | 2023 |       CVPR       |
| [MomAD](https://arxiv.org/abs/2503.03125)                                                                                       |  47.91   |   18.11   | 2025 |       CVPR       |
| [CogAD](https://arxiv.org/abs/2505.21581)                                                                                       |  48.30   |   24.00   | 2025 |        -         |
| [AdaptiveAD](https://arxiv.org/abs/2511.13079)                                                                                  |  49.47   |   19.23   | 2025 |        -         |
| [BridgeAD](https://arxiv.org/abs/2503.14182)                                                                                    |  50.06   |   22.73   | 2025 |       CVPR       |
| [E³AD](https://arxiv.org/abs/2511.01334)                                                                                        |  50.07   |   20.12   | 2025 |        -         |
| [X-Driver](https://arxiv.org/abs/2505.05098)                                                                                    |  51.70   |   18.10   | 2025 |        -         |
| [DiFSD](https://arxiv.org/abs/2409.09777)                                                                                       |  52.02   |   21.00   | 2024 |        -         |
| [SpaRC-AD](https://arxiv.org/abs/2508.10567)                                                                                    |  55.60   |   30.00   | 2025 |     Workshop     |
| [SeerDrive](https://arxiv.org/abs/2510.11092)                                                                                   |  58.32   |   30.17   | 2025 |     NeurIPS      |
| [WoTE](https://arxiv.org/abs/2504.01941)                                                                                        |  61.71   |   31.36   | 2025 |       ICCV       |
| [DriveDPO](https://arxiv.org/abs/2509.17940)                                                                                    |  62.02   |   30.62   | 2025 |     NeurIPS      |
| [ThinkTwice](https://arxiv.org/abs/2305.06242)                                                                                  |  62.44   |   31.23   | 2022 |       CVPR       |
| [DriveTransformer-L.](https://arxiv.org/abs/2503.07656)                                                                         |  63.46   |   35.01   | 2025 |       ICLR       |
| [DriveAdapter](https://arxiv.org/abs/2308.00398)                                                                                |  64.22   |   33.08   | 2023 |       ICCV       |
| [VeteranAD](https://arxiv.org/abs/2508.11488)                                                                                   |  64.22   |   33.85   | 2025 |        -         |
| [iPad](https://arxiv.org/abs/2505.15111)                                                                                        |  65.02   |   35.91   | 2025 |        -         |
| [StuckSolver](https://arxiv.org/abs/2510.26023)                                                                                 |  65.23   |   36.32   | 2025 |        -         |
| [GEMINUS](https://arxiv.org/abs/2507.14456)                                                                                     |  65.39   |   37.73   | 2025 |        -         |
| [VDRive](https://arxiv.org/abs/2510.15446)                                                                                      |  66.25   |   50.51   | 2025 |        -         |
| [RAP-ResNet](https://arxiv.org/abs/2510.04333)                                                                                  |  66.42   |   37.27   | 2025 |        -         |
| [CAPS](https://arxiv.org/abs/2503.01650)                                                                                        |  66.76   |   52.87   | 2025 |        -         |
| [SNG](https://zhihua-hua.github.io/NavigationDrive-web/static/NavigationDrive.pdf)                                              |  67.17   |   35.90   | 2025 |        -         |
| [DiffAD](https://arxiv.org/abs/2503.12170)                                                                                      |  67.92   |   38.64   | 2025 |        -         |
| [OAIAD](https://www.mdpi.com/2075-1702/13/10/965)                                                                               |  68.73   |   48.86   | 2025 |     Machines     |
| [DIVER](https://arxiv.org/abs/2507.04049)                                                                                       |  68.90   |   36.75   | 2025 |        -         |
| [Raw2Drive](https://arxiv.org/abs/2505.16394)                                                                                   |  71.36   |   50.24   | 2025 |     NeurIPS      |
| [VL](https://arxiv.org/abs/2406.01544)                                                                                          |  73.29   |   65.44   | 2025 |       ICRA       |
| [Hydra-NeXt](https://arxiv.org/abs/2503.12030)                                                                                  |  73.86   |   50.00   | 2025 |        -         |
| [DriveMoE](https://arxiv.org/abs/2505.16278)                                                                                    |  74.22   |   48.64   | 2025 |        -         |
| [ETA](https://arxiv.org/abs/2506.07725)                                                                                         |  74.33   |   48.33   | 2025 |       ICCV       |
| [GuideFlow](https://arxiv.org/abs/2511.18729)                                                                                   | 75.21 |     51.36      | 2025 |        -         |
| [DiffusionDrive-temp](https://arxiv.org/abs/2411.15139)                                                                         |  77.68   |   52.72   | 2025 |       CVPR       |
| [ORION](https://arxiv.org/abs/2503.19755)                                                                                       |  77.74   |   54.62   | 2025 |       ICCV       |
| [PGS](https://openreview.net/forum?id=PZqII8EoFG&referrer=%5Bthe%20profile%20of%20Yi%20Huang%5D(%2Fprofile%3Fid%3D~Yi_Huang20)) |  78.08   |   48.64   | 2025 |     NeurIPS      |
| [GaussianFusion](https://arxiv.org/abs/2506.00034)                                                                              |  79.10   |   54.40   | 2025 |     NeurIPS      |
| [TF++](https://arxiv.org/abs/2412.09602)                                                                                        |  84.21   |   67.27   | 2024 |        -         |
| [SimLingo](https://arxiv.org/abs/2503.09594)                                                                                    |  85.07   |   67.27   | 2025 |       CVPR       |
| [R2SE](https://arxiv.org/abs/2506.09800)                                                                                        |  86.28   |   69.54   | 2025 |        -         |
| [HiP-AD](https://arxiv.org/abs/2503.08612)                                                                                      |  86.77   |   69.09   | 2025 |       ICCV       |
| [BridgeDrive](https://arxiv.org/abs/2509.23589)                                                                                 |  86.87   | **72.27** | 2025 |        -         |
| [DiffRefiner](https://arxiv.org/abs/2511.17150)                                                                                 | **87.1** |   71.4    | 2025 |        -         |
| ---                                                                                                                             |   ---    |    ---    |  --- |       ---        |
| *[Think2Drive](https://arxiv.org/abs/2402.16720)*                                                                               | *91.85*  |  *85.41*  | 2024 |       ECCV       |
| *[PDM-Lite](https://arxiv.org/abs/2312.14150)*                                                                                  | *97.02*  |  *92.27*  | 2024 |       ECCV       |
