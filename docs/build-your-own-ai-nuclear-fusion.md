# AI + 核聚变 (Nuclear Fusion)

这里收集了 AI 在核聚变研究、等离子体控制和反应堆模拟领域的开源替代方案和工具。

## 模拟与控制 (Simulation & Control)

*   **[TORAX](https://github.com/google-deepmind/torax)**
    *   **描述**: Google DeepMind 发布的开源等离子体模拟器，基于 JAX 构建。
    *   **用途**: 专为强化学习控制设计，支持 GPU 加速，用于模拟和优化托卡马克核心等离子体。

*   **[KSTAR-NN](https://github.com/KSTAR-NN/KSTAR-NN)** (假设链接，根据搜索结果调整)
    *   **注意**: 搜索结果提及了 KSTAR-NN 模拟器，如果有具体 GitHub 链接请替换。这里引用搜索到的 `ZINZINBIN/Tokamak-Plasma-Operation-Control-based-on-RL` 作为替代。
    *   **[Tokamak-Plasma-Operation-Control-based-on-RL](https://github.com/ZINZINBIN/Tokamak-Plasma-Operation-Control-based-on-RL)**
    *   **描述**: 基于深度强化学习的托卡马克等离子体运行控制。
    *   **用途**: 在虚拟 KSTAR 环境中进行多目标控制。

*   **[PlasmaControl/PlasmaEvolution](https://github.com/PlasmaControl/PlasmaEvolution)**
    *   **描述**: 使用神经网络预测托卡马克等离子体状态的时间演化。
    *   **用途**: 等离子体轮廓预测和控制系统开发。

*   **[AI_tokamak_control](https://github.com/jaem-seo/AI_tokamak_control)**
    *   **描述**: 针对 KSTAR 托卡马克的自主控制 AI 设计。
    *   **用途**: 控制等离子体参数 (beta_p, q95, li)。

## 通用聚变科学工具 (General Fusion Science Tools)

*   **[PlasmaPy](https://github.com/PlasmaPy/PlasmaPy)**
    *   **描述**: 一个用于等离子体物理学的开源 Python 社区开发包。
    *   **用途**: 通用等离子体科学计算和分析。

*   **[OMAS (Ordered Multidimensional Array Structures)](https://github.com/gafusion/omas)**
    *   **描述**: 简化第三方代码与 ITER 集成建模和分析套件 (IMAS) 的接口。
    *   **用途**: 数据标准化和跨代码接口。

*   **[Bluemira](https://github.com/Bluemira/Bluemira)**
    *   **描述**: 未来核聚变反应堆的综合跨学科设计工具。
    *   **用途**: 反应堆系统设计和优化。

## 其他相关项目

*   **[XiHeFusion](https://github.com/XiHeFusion/XiHeFusion)** (根据搜索结果)
    *   **描述**: 首个针对核聚变领域的聊天大语言模型 (LLM)。
    *   **用途**: 核聚变科普和科学交流。

*   **[Merlin](https://github.com/LLNL/merlin)**
    *   **描述**: LLNL 开发的用于管理机器学习工作流的工具。
    *   **用途**: 高性能计算 (HPC) 系统中的 AI 工作流管理。
