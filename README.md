# Awesome Embodied AI  

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  
[![GitHub stars](https://img.shields.io/github/stars/TinyEmbodiedAI/awesome-embodied-ai.svg)](https://github.com/TinyEmbodiedAI/awesome-embodied-ai/stargazers)  
[![GitHub forks](https://img.shields.io/github/forks/TinyEmbodiedAI/awesome-embodied-ai.svg)](https://github.com/TinyEmbodiedAI/awesome-embodied-ai/network)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)  

A curated list of awesome Embodied AI resources, frameworks, libraries, papers, and projects. Embodied AI focuses on developing intelligent systems that learn through physical or virtual interaction with their environment.  

## Contents  

- [Introduction](#introduction)  
- [Getting Started](#getting-started)  
- [Papers](#papers)  
- [Software & Tools](#software--tools)  
- [Datasets](#datasets)  
- [Courses & Tutorials](#courses--tutorials)  
- [Projects](#projects)  
- [Conferences & Workshops](#conferences--workshops)  
- [Research Groups](#research-groups)  
- [Companies & Organizations](#companies--organizations)  
- [Contributing](#contributing)  

## Introduction  

Embodied AI represents a paradigm shift in artificial intelligence research, emphasizing the importance of physical or virtual embodiment in developing intelligent systems. This list aims to provide a comprehensive collection of resources for researchers, developers, and enthusiasts in the field.  

### What is Embodied AI?  
- The integration of perception, action, and learning in physical or simulated environments  
- Focus on interactive and experiential learning  
- Emphasis on real-world or realistic virtual environment interaction  

## Getting Started  

### Essential Concepts  
- Sensorimotor Learning  
- Active Perception  
- Environmental Interaction  
- Embodied Learning  
- Cognitive Development  

### Key Resources for Beginners  
- [Introduction to Embodied AI](link) - A comprehensive overview  
- [Embodied AI Tutorial](link) - Step-by-step guide  
- [Basic Concepts and Principles](link) - Fundamental theories

## Papers  

### Survey Papers  
- [Pfeifer, Rolf, and Fumiya Iida. "Embodied artificial intelligence: Trends and challenges." Lecture notes in computer science (2004): 1-26.](https://people.csail.mit.edu/iida/papers/PfeiferIidaEAIDags.pdf) - Description (2004)  
- [Duan, Jiafei, et al. "A survey of embodied ai: From simulators to research tasks." IEEE Transactions on Emerging Topics in Computational Intelligence 6.2 (2022): 230-244.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9687596) - Description (2022) 
- [Liu, Yang, et al. "Aligning cyber space with physical world: A comprehensive survey on embodied ai." arXiv preprint arXiv:2407.06886 (2024).](https://arxiv.org/pdf/2407.06886) - Description (2024)
- [Moulin-Frier, Clément, et al. "Embodied artificial intelligence through distributed adaptive control: An integrated framework." 2017 Joint IEEE International Conference on Development and Learning and Epigenetic Robotics (ICDL-EpiRob). IEEE, 2017.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8329825) - Description (2017) 
  
### Foundational Papers  
- [Paolo, Giuseppe, Jonas Gonzalez-Billandon, and Balázs Kégl. "A call for embodied AI." arXiv preprint arXiv:2402.03824 (2024).](https://arxiv.org/pdf/2402.03824) - Description (2024)  
- [Majumdar, Arjun, et al. "Openeqa: Embodied question answering in the era of foundation models." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2024.](Majumdar_OpenEQA_Embodied_Question_Answering_in_the_Era_of_Foundation_Models_CVPR_2024_paper) - Description (2024)
- [Tao, Stone, et al. "Maniskill3: Gpu parallelized robotics simulation and rendering for generalizable embodied ai." arXiv preprint arXiv:2410.00425 (2024).](https://arxiv.org/pdf/2410.00425) - Description (2024)
  

### Recent Advances  
- [Duan, Jiafei, et al. "A survey of embodied ai: From simulators to research tasks." IEEE Transactions on Emerging Topics in Computational Intelligence 6.2 (2022): 230-244.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9687596) - Description (2022)  
- [Xu, Zhiyuan, et al. "A survey on robotics with foundation models: toward embodied ai." arXiv preprint arXiv:2402.02385 (2024).](https://arxiv.org/pdf/2402.02385) - Description (2024)
- [Title](link) - Description (Year)
  
## Software & Tools  

### Simulation Platforms  
- 常见仿真器wiki:(https://simulately.wiki/)
- MimicGen  paper:(https://arxiv.org/abs/2310.17596)  code:(https://github.com/NVlabs/mimicgen_environments)
- RoboGen  paper:(https://arxiv.org/abs/2311.01455)  code:(https://github.com/Genesis-Embodied-AI/RoboGen)
- 具身人工智能的模仿学习平台:(https://github.com/OpenGHz/Imitate-All)

### Development Frameworks  

### Libraries  
- 具身智能相关视频：(https://space.bilibili.com/350563565)
- 具身智能阅读仓库:(https://github.com/StarCycle/EmbodiedAI-Reading-List-For-Lists?tab=readme-ov-file)
- Platform to simulate real world environments:(https://github.com/chengaopro/Awesome-EmbodiedAI)
### Read Tools
- [Citation2Prompt](https://github.com/StarCycle/Citation2Prompt)
- [repo2txt](https://github.com/abinthomasonline/repo2txt)
- [connectedpapers](https://www.connectedpapers.com/)
- 具身智能生产工具：(https://github.com/LoopMind-AI/loopquest)

## Datasets

### Benchmark Datasets  
- 具身智能常用benchmark：(https://zhuanlan.zhihu.com/p/695342864)
- 相关数据集仓库：(https://github.com/mint-lab/awesome-robotics-datasets)
- Embodied datasets built upon simulators (https://github.com/chengaopro/Awesome-EmbodiedAI)
- [thanhqt2002/embodied-spatial-reasoning](https://hf-mirror.com/datasets/thanhqt2002/embodied-spatial-reasoning) - 发布时间：2024-06-02  数据集内容：该数据集是embodied-spatial-reasoning项目的一部分，旨在让代理主动探索环境以确定某些空间关系是否成立。任务涉及对各种对象和场景进行空间推理。每个任务包含一个关于场景内对象之间空间关系的查询，代理必须通过探索来验证。
- [EgoPlan-Bench](https://chenyi99.github.io/ego_plan/) - 发布时间：2024-06-02  数据集内容：该数据集是embodied-spatial-reasoning项目的一部分，旨在让代理主动探索环境以确定某些空间关系是否成立。任务涉及对各种对象和场景进行空间推理。每个任务包含一个关于场景内对象之间空间关系的查询，代理必须通过探索来验证。
- [byeonghwikim/hssd-hab](https://hf-mirror.com/datasets/byeonghwikim/hssd-hab) - 发布时间：2023-11-06  数据集内容：Habitat Synthetic Scenes Dataset（HSSD）是一个由人类作者创建的3D场景数据集，比之前的其他数据集更接近真实场景。该数据集包含211个多样化的场景和超过18000个真实世界对象的模型，支持Habitat 3.0的具身重排任务。
- [具身智能商超交互式合成数据集](https://www.selectdataset.com/dataset/e3a74b23a0836eac3d31ac356d28c78c) - 发布时间：2023-09-03  数据集内容：涉及物体检测（2D/3D）、分割、姿态估计、机器人视觉SLAM、占用网络多个任务数据规模：20个商超布局，300种可交互的中国资产品类。
- [Habitat-Matterport 3D Semantics (HM3DSEM)](https://www.selectdataset.com/dataset/2161fde4172f1184ebe41baf9c456a2d) - 发布时间：2022-10-12  数据集内容：HM3DSEM数据集是由Meta AI等机构创建的，是目前学术界可用的最大3D真实世界空间密集语义标注数据集。该数据集包含216个高分辨率3D扫描场景，覆盖3100个房间，总计142,646个对象实例标注。数据集的创建过程涉及大量人工标注和验证，总计超过14,200小时。HM3DSEM数据集主要用于提升下游具身AI任务的性能，特别是在Object Goal Navigation任务中，通过不同学习方法训练的策略在跨数据集泛化性能上均有显著提升。
- [AI2-THOR](https://opendatalab.org.cn/OpenDataLab/AI2-THOR) - 发布时间：2022-08-16  数据集内容：AI2-Thor 是具身人工智能的交互式环境。它包含厨房、客厅、卧室和浴室四种场景，每个场景包括30个房间，每个房间在家具摆放和物品类型上都是独一无二的。有超过 2000 个独特的对象可供 AI 代理与之交互。
- [BEHAVIOR](https://www.selectdataset.com/dataset/020e26cafd8c53ef1c234d0d60131f0e) - 发布时间：2021-08-07  数据集内容：一个包含100种日常家庭活动（如清洁、维护和食物准备）的具身AI基准，旨在重现代理在现实世界中必须面对的挑战。
- [Human3.6M](https://www.selectdataset.com/dataset/553d12722f536fc5718ad878a2095c9e) - 发布时间：2014-05-01  数据集内容：Human3.6M是一个大规模的人体运动数据集，包含360万帧高质量的3D人体姿势数据。该数据集由11名专业演员在受控环境中表演15种日常活动，如走路、坐下、站立等。数据集还包括2D和3D的骨骼关节位置、深度图像和视频序列。
- Grasp Datasets
- [QDGset: A Large Scale Grasping Dataset Generated with Quality-Diversity] paper:(https://arxiv.org/abs/2410.02319)
- [Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection] paper:(https://arxiv.org/abs/2410.06521)  code:(https://isee-laboratory.github.io/R2SGrasp/)
- [Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance]paper:(https://arxiv.org/abs/2407.13842)  code:(https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance)
- [Language-driven Grasp Detection] paper:(https://arxiv.org/abs/2406.09489)  code:(https://github.com/Fsoft-AIC/LGD)
- [Grasp-Anything: Large-scale Grasp Dataset from Foundation Models] paper:(https://arxiv.org/abs/2309.09818) code:(https://github.com/Fsoft-AIC/Grasp-Anything)
- [GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping] paper:(https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf) code:(https://github.com/graspnet/graspnet-baseline)
- Manipulation Benchmarks (https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation?tab=readme-ov-file#grasp-datasets)
- Cross-Embodiment Benchmarks (https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation?tab=readme-ov-file#grasp-datasets)

### Research Datasets  
- [Ramakrishnan, Santhosh K., et al. "Habitat-matterport 3d dataset (hm3d): 1000 large-scale 3d environments for embodied ai." arXiv preprint arXiv:2109.08238 (2021).](https://arxiv.org/pdf/2109.08238) - Description  
- [Zhao, Qianfan, et al. "A real 3d embodied dataset for robotic active visual learning." IEEE Robotics and Automation Letters 7.3 (2022): 6646-6652.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9729641&tag=1) - Description  

## Courses & Tutorials  

### Online Courses  
- [Building and Working in Environments for Embodied AI](https://ai-workshops.github.io/building-and-working-in-environments-for-embodied-ai-cvpr-2022/) - Simon Fraser University, Angel Xuan Chang

### Video Tutorials  
- [CS539 - Embodied AI](https://web.engr.oregonstate.edu/~leestef/courses/2019/fall/cs539.html) - We will read and analyze the strengths and weaknesses of recent research papers on a variety of topics in embodied AI and identify open research questions. 

### Books & Reading Materials  
- [Multimodal Large Models: The New Paradigm of Artificial General Intelligence](https://hcplab-sysu.github.io/Book-of-MLM/) - Yang Liu, Liang Lin, 2024

## Projects  

### Open Source Projects  
- [CogAgent: Visual Expert for Pretrained Language Models](https://github.com/THUDM/CogVLM?tab=readme-ov-file) - CogAgent is an open-source visual language model improved based on CogVLM.
- [All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents](https://imaei.github.io/project_pages/ario/) - we introduce ARIO (All Robots In One), a new data standard that enhances existing datasets by offering a unified data format, comprehensive sensory modalities, and a combination of real-world and simulated data.
- [Language Guided Generation of 3D Embodied AI Environments](https://github.com/allenai/Holodeck) - Description

### Research Projects  
- [ProAgent: From Robotic Process Automation to Agentic Process Automation](https://github.com/OpenBMB/ProAgent) - Tsinghua University, this paper introduces (APA), a groundbreaking automation paradigm using LLM-based agents for advanced automation by offloading the human labor to agents associated with construction and execution.

### Demo Applications  
- [Application Name](link) - Description  
- [Application Name](link) - Description  

## Conferences & Workshops  

### Major Conferences  
- [The Fifth Annual Embodied AI Workshop](https://embodied-ai.org/) - Tuesday, June 18 from 8:50am to 5:30pm Pacific, 2024, Seattle Convention Center
- [RoboTHOR: An Open Simulation-to-Real Embodied AI Platform](https://openaccess.thecvf.com/content_CVPR_2020/papers/Deitke_RoboTHOR_An_Open_Simulation-to-Real_Embodied_AI_Platform_CVPR_2020_paper.pdf) - 2020
- [Habitat: A Platform for Embodied AI Research](https://openaccess.thecvf.com/content_ICCV_2019/html/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.html) - 2019

### Workshops & Symposiums  
- [Retrospectives on the Embodied AI Workshop](https://arxiv.org/pdf/2210.06849) - Associated Conference, 13 Oct 2022
- [Workshop on Embodied Intelligence with Large Language Models In Open City Environment](https://openreview.net/pdf?id=zIybgEio8Y) - Associated Conference,  03 Dec 2024

## Research Groups  

### Academic Research Groups  
- [Group Name](link) - Institution, Focus Areas  
- [Group Name](link) - Institution, Focus Areas  

### Industry Research Labs  
- [Lab Name](link) - Company, Focus Areas  
- [Lab Name](link) - Company, Focus Areas  

## Companies & Organizations  

### Companies Working on Embodied AI  
- [Company Name](link) - Focus Areas  
- [Company Name](link) - Focus Areas  

### Organizations & Foundations  
- [Organization Name](link) - Mission  
- [Organization Name](link) - Mission  

## Contributing  

### How to Contribute  
1. Fork the repository  
2. Create a new branch: `git checkout -b add-new-resource`  
3. Add your changes following the formatting guidelines  
4. Submit a pull request  

### Contribution Guidelines  
- Ensure the resource is relevant to Embodied AI  
- Provide a clear description  
- Include necessary links and references  
- Follow the existing format  
- Verify links are working  
- Add new resources to the appropriate section  

### Quality Standards  
- Resources should be actively maintained  
- Content must be high quality and informative  
- Commercial resources should be clearly marked  
- Avoid duplicates  

## License  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  

## Acknowledgments  

Special thanks to all contributors who have helped to build and maintain this awesome list!  

---  

## Star History  

[![Star History Chart](https://api.star-history.com/svg?repos=tinyEmbodiedAI/awesome-embodied-ai&type=Date)](https://star-history.com/#tinyEmbodiedAI/awesome-embodied-ai&Date)  

## Contact  

For questions, suggestions, or issues, please:  
- Open an issue  
- Submit a pull request  
- Contact maintainers: [maintainer@email.com](mailto:jqwang16@icloud.com)  

---  

If you find this resource helpful, please consider giving it a ⭐️ to help others discover it!
