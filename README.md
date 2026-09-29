# deep-research

A curated directory of community research, applications, and secondary development built on **DEEP Robotics products**.

云深处机器人产品二次开发项目索引：收录社区的研究、应用、算法与工程实践，并链接至原作者仓库。

This repository links to external projects maintained by their respective authors. It covers navigation, perception, locomotion, simulation, and robot applications. The initial collection comes from the GOAI 2026 all-terrain patrol open-source submission spreadsheet; contributions for other DEEP Robotics products and events are welcome.

## Community projects

Last checked: **2026-09-29**. Six of the eight submitted repository links currently resolve to public repositories. Descriptions summarize the upstream documentation; hardware performance and end-to-end reproducibility have not been independently tested.

### Navigation, perception, and patrol

| Repository | Team | Product | Focus | License / release scope |
| --- | --- | --- | --- | --- |
| [syh486/goai_drl_submission](https://github.com/syh486/goai_drl_submission) | 深度强化学习 | Lynx S10 | SRU navigation, dual-LiDAR encoding, route mapping/localization, and HIMLoco locomotion training. | BSD-3-Clause detected. Full route maps and raw robot data are excluded. |
| [tangyipeng100/GOAI2026_kbrs](https://github.com/tangyipeng100/GOAI2026_kbrs) | 恐怖如斯队 | Lynx S10 | Goal Point visual-language navigation, multi-frame and multi-view inference, coordinate transforms, and segment replay/evaluation. | Apache-2.0 detected. Full model weights, raw Gaussian scans, and private training/inference services are excluded. |
| [bowenwan6/goai26-s10-racing](https://github.com/bowenwan6/goai26-s10-racing) | GOAI LAI（狗來） | Lynx S10 | Taught-route navigation, terrain-aware local planning and gait selection, MuJoCo simulation, RL training, and ROS sensor integration. | BSD-3-Clause detected. Third-party components retain their own terms. |

### Locomotion and training

| Repository | Team | Product | Focus | License / release scope |
| --- | --- | --- | --- | --- |
| [Jack15678/rl_training](https://github.com/Jack15678/rl_training) | GOAI LAI（狗來） | Lite3, M20, DR02 documented upstream | Community fork of the DEEP Robotics Isaac Lab training framework. Submitted with the team's S10 project; S10 support is not documented in its current root README. | BSD-3-Clause detected. |

### Public source — license clarification needed

These repositories are publicly accessible, but GitHub detects no repository-level license and no top-level license file was found during review. Public visibility alone does not establish permission to reuse the code. Consult the maintainers and component-specific terms.

| Repository | Team | Product | Focus | Notes |
| --- | --- | --- | --- | --- |
| [TransformBrino/goai2026-s10-patrol](https://github.com/TransformBrino/goai2026-s10-patrol) | 传化具身智能（Transfar Embodied AI） | Lynx S10 | Navigation tools, FAST-LIO2 perception integration, and experimental RL training/deployment. | Currently public, although the submission spreadsheet and README describe restricted reviewer access. Built-in locomotion and third-party navigation are closed-source dependencies; experimental RL control was not used in the final competition. |
| [luogantt/robot_dog](https://github.com/luogantt/robot_dog) | 维金战船 | Lynx S10 | ASDU/Web control, AprilTag following, and SLAM navigation with Lightning-LM, Pure Pursuit, obstacle avoidance, and command arbitration. | Field recordings, maps, routes, and selected third-party binaries/assets are excluded. |

## Add or update a project

Open a pull request or issue with:

- The public GitHub repository URL and project/team name.
- The DEEP Robotics product used and a short description of the secondary development.
- Setup or reproduction documentation, including the relevant branch/tag if needed.
- The license and any unavailable code, weights, datasets, assets, or proprietary dependencies.

Place the entry in the appropriate category, link to the original repository, and describe only what the project documents. Identify forks and distinguish simulation results from real-robot results. Corrections to availability, product support, and license information are welcome.

## Scope and attribution

This is a growing index, not an exhaustive inventory of every external DEEP Robotics project. The initial review accounts for all **8 links across 5 teams** in the supplied patrol spreadsheet: **6 public repositories included**; 2 unavailable links and 3 teams without links are omitted.

License labels reflect GitHub metadata at the review date, not a file-by-file license audit. Each upstream project's code, models, data, media, and dependencies remain subject to its own terms. Inclusion does not imply official maintenance or independent validation by DEEP Robotics.

For official SDKs, robot models, and development tools, visit [DeepRoboticsLab](https://github.com/DeepRoboticsLab).
