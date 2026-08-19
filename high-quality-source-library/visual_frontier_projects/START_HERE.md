# 视觉前沿论文、项目视频与个人作品集扩展包

快照日期：2026-08-18

## 内容规模

- 去重后的新增来源：136
- 可导入 Feed：60
- 前沿论文与项目视频：51
- 个人项目作品集：40
- 视觉发现平台：45

## 优质课程资源

本目录新增 `courses/` 子目录，收录名校、专业机构、个人/社区维护的优质课程，以及专门持续搜集课程、开放教材和学习路线的二阶信源。课程模块与上面的 136 个视觉信源独立计数。

- 从 `courses/START_HERE.md` 了解筛选与引用边界。
- 用 `courses/course_sources.json` 让 Agent 按学科、水平、费用、视觉性、项目性和证据性筛选。
- 想继续发现新课程时，优先读 `courses/RESOURCE_CURATORS.md`。
- 想按方向开始学习时，读 `courses/LEARNING_PATHS.md`。
- 可订阅且通过验证的课程/频道 Feed 在 `courses/course_video_feeds.opml`。

## Agent 使用顺序

1. 从 `visual_sources.json` 按 `source_group`、`domains`、`visual_score` 和 `evidence_score` 过滤。
2. 前沿研究主张优先使用“前沿论文与项目视频”中的证据源，并打开具体论文或项目页。
3. 个人作品集和视觉发现平台主要承担案例、表达、构图和交互灵感，不应替代事实证据。
4. `representative_url` 是快速预览入口；发布时应核对作者、项目名、年份和具体权利声明。
5. 视觉素材默认不可直接转载。优先链接、嵌入官方视频或重新制作图解；截图、动图和作品图需逐项检查许可并署名。

## 字段要点

- `visual_formats`：视频、交互 Demo、动图、3D、图表、装置影像等。
- `visual_score`：视觉素材密度，1–5。
- `evidence_score`：作为事实依据的强度，1–5；与审美质量无关。
- `citation_role`：证据源、解释源、观点源、线索源或灵感源。
- `homepage_status` / `feed_status`：2026-08-18 的网络检查，仅反映可访问性。

## S 级快速入口（前 30 条）

| 来源 | 分组 | 领域 | 视觉 | 证据 | 最适合 |
|---|---|---|---:|---:|---|
| [ACM Multimedia 2025 Demo / Video Papers](https://acmmm2025.org/) | 前沿论文与项目视频 | 多媒体、视频理解、生成媒体、交互媒体 | 5 | 5 | 视频、音频、跨模态和多媒体系统的可视化研究 |
| [Conference on Robot Learning Videos](https://www.corl.org/) | 前沿论文与项目视频 | 机器人学习、模仿学习、强化学习、具身智能 | 5 | 5 | 具身智能和机器人学习的论文演示 |
| [CVPR 2026 Events with Videos](https://cvpr.thecvf.com/Conferences/2026) | 前沿论文与项目视频 | 计算机视觉、多模态、视频生成、3D 视觉 | 5 | 5 | 计算机视觉最密集的论文视频、口头报告与项目展示 |
| [ECCV Virtual Video Archive](https://eccv.ecva.net/Conferences/2026) | 前沿论文与项目视频 | 计算机视觉、3D 视觉、视频理解、生成视觉 | 5 | 5 | 欧洲计算机视觉旗舰会议的论文与视频档案 |
| [ETH Robotics Systems Lab Videos](https://rsl.ethz.ch/) | 前沿论文与项目视频 | 腿式机器人、自主导航、野外机器人、感知 | 5 | 5 | 腿式机器人在复杂真实环境中的研究 |
| [IEEE ICRA 2026 Program and RAS Videos](https://2026.ieee-icra.org/) | 前沿论文与项目视频 | 机器人、自动化、操作、自主系统 | 5 | 5 | 机器人旗舰会议的论文、展示和竞赛 |
| [IEEE VIS 2025 Program and Recordings](https://ieeevis.org/year/2025/welcome) | 前沿论文与项目视频 | 数据可视化、科学可视化、视觉分析、HCI | 5 | 5 | 数据可视化、科学可视化和视觉分析研究 |
| [IEEE VR 2026 Research Demos and Paper Videos](https://ieeevr.org/2026/) | 前沿论文与项目视频 | XR、3DUI、触觉、沉浸式可视化 | 5 | 5 | XR、触觉、沉浸式交互和 3D 界面原型 |
| [Max Planck Intelligent Systems Videos](https://is.mpg.de/) | 前沿论文与项目视频 | 机器人、计算机视觉、软体机器人、机器学习 | 5 | 5 | 软体、微型与生物启发机器人及视觉研究 |
| [Robotics: Science and Systems 2025 Video Presentations](https://roboticsconference.org/2025/) | 前沿论文与项目视频 | 机器人、规划、控制、具身智能 | 5 | 5 | 高质量机器人论文及作者演示 |
| [Stanford ILIAD Robot Interaction Demos](https://iliad.stanford.edu/) | 前沿论文与项目视频 | 人机协作、机器人学习、规划、具身 AI | 5 | 5 | 交互式机器人学习与人机协作论文 |
| [UbiComp / ISWC Video Archive](https://www.ubicomp.org/) | 前沿论文与项目视频 | 可穿戴、普适计算、移动感知、HCI | 5 | 5 | 可穿戴设备、移动感知和日常计算研究 |
| [UIST 2025 Video Previews](https://uist.acm.org/2025/) | 前沿论文与项目视频 | HCI、新型界面、触觉、交互硬件 | 5 | 5 | 快速扫描交互技术论文和原型 |
| [ACM DIS 2026 Interactivity](https://dis.acm.org/2026/) | 前沿论文与项目视频 | 交互设计、HCI、物理计算、研究型设计 | 5 | 4 | 具有批判性、体验性和设计研究价值的互动原型 |
| [ACM SIGGRAPH Video Channel](https://www.siggraph.org/) | 前沿论文与项目视频 | 计算机图形学、动画、渲染、XR | 5 | 4 | 图形学论文第一眼筛选与高视觉密度 Demo |
| [ACM TEI 2026 Projects](https://tei.acm.org/2026/) | 前沿论文与项目视频 | 可穿戴、触觉、实体交互、智能材料 | 5 | 4 | 有形、嵌入式、身体化交互和可穿戴研究 |
| [CHI 2025 Video Showcase](https://chi2025.acm.org/) | 前沿论文与项目视频 | HCI、交互设计、可访问性、社会计算 | 5 | 4 | 兼具研究内容与叙事创意的 HCI 视频 |
| [Disney Research Video Demos](https://www.disneyresearch.com/) | 前沿论文与项目视频 | 计算机图形学、机器人、动画、HCI | 5 | 4 | 角色动画、机器人表现力和沉浸式娱乐技术 |
| [Google DeepMind Research Videos](https://deepmind.google/) | 前沿论文与项目视频 | 基础模型、强化学习、机器人、科学 AI | 5 | 4 | 大型 AI 研究项目、科学 AI 与具身研究演示 |
| [IROS 2025 Video and Live Stream Hub](https://www.iros25.org/) | 前沿论文与项目视频 | 机器人、智能系统、人形机器人、工业自动化 | 5 | 4 | 机器人论文、现场展示和产业研究交汇 |
| [Meta AI Research Videos](https://ai.meta.com/) | 前沿论文与项目视频 | 计算机视觉、多模态、具身 AI、AR/VR | 5 | 4 | 视觉基础模型、感知、生成与 Reality Labs 研究 |
| [NASA JPL Robotics Videos](https://www-robotics.jpl.nasa.gov/) | 前沿论文与项目视频 | 太空机器人、自主导航、计算机视觉、科学任务 | 5 | 4 | 极端环境机器人、太空任务和科学成像 |
| [SIGGRAPH Asia Visual Research Programs](https://asia.siggraph.org/2025/) | 前沿论文与项目视频 | 计算机图形学、动画、XR、新兴技术 | 5 | 4 | 亚洲图形学、实时演示、动画和 XR 项目 |
| [USC ICT Research Videos](https://ict.usc.edu/) | 前沿论文与项目视频 | 虚拟人、XR、HCI、仿真训练 | 5 | 4 | 虚拟人、沉浸式训练和人机交互研究 |
| [Bostock Portfolio](https://bost.ocks.org/) | 个人项目作品集 | 数据可视化、D3、交互编程 | 5 | 5 | D3范式、图表实现与可运行示例 |
| [Inigo Quilez](https://iquilezles.org/) | 个人项目作品集 | 计算机图形学、Shader、距离场 | 5 | 5 | SDF、光线步进和程序化图形技术 |
| [Patricio Gonzalez Vivo](https://patriciogonzalezvivo.com/) | 个人项目作品集 | 创意编程、着色器、生成艺术 | 5 | 5 | GLSL学习、实时生成视觉与图形学直觉 |
| [Formafantasma](https://formafantasma.com/) | 个人项目作品集 | 产品设计、研究设计、材料文化 | 5 | 4 | 材料、生态、供应链与批判性设计研究 |
| [Golan Levin Archive](https://flong.com/) | 个人项目作品集 | 交互艺术、创意编程、媒体艺术 | 5 | 4 | 交互艺术史、身体界面与批判性技术艺术 |
| [Inconvergent](https://inconvergent.net/) | 个人项目作品集 | 生成艺术、计算几何、创意编程 | 5 | 4 | 路径、网络、生长系统与笔式绘图 |

## 推荐发帖结构

- Hook：先给视觉反差或项目结果。
- 证据：链接论文、项目页、代码或官方演示。
- 拆解：解释“它如何实现”，不要只转发炫酷画面。
- 限制：说明样本、演示条件、失败案例或不可复现因素。
- 利他价值：给出可学习的方法、工具、数据或设计原则。
