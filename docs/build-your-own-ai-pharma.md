# AI + 制药 (Pharma & Drug Discovery)

这里收集了 AI 在制药、药物发现、蛋白质折叠和分子生成领域的开源替代方案和工具。

## 综合框架 (Comprehensive Frameworks)

*   **[DeepMol](https://github.com/DeepMol/DeepMol)**
    *   **描述**: 一个基于 Python 的框架，用于处理药物发现和化学信息学问题。它利用 TensorFlow, Keras, Scikit-learn, DeepChem 和 RDKit 构建自定义模型或使用预构建模型。
    *   **用途**: 机器学习和深度学习在化学中的应用，提供统一的接口。

*   **[DeepChem](https://github.com/deepchem/deepchem)**
    *   **描述**: 一个旨在使深度学习在药物发现、材料科学、量子化学和生物学中普及的库。
    *   **用途**: 药物发现的“瑞士军刀”，包含大量数据集和模型实现。

*   **[AI-Drug-Discovery-Design](https://github.com/itWangCode/AI-Drug-Discovery-Design)**
    *   **描述**: 专注于 AI 在药物发现和设计中的应用，涵盖化合物筛选、靶点预测、药物生成和 ADMET 分析。
    *   **用途**: 提高药物研发效率的综合资源库。

## 蛋白质折叠与结构预测 (Protein Folding & Structure)

*   **[Uni-Fold](https://github.com/dptech-corp/Uni-Fold)**
    *   **描述**: DeepMind AlphaFold 的开源 PyTorch 实现。它不仅复现了 AlphaFold 和 AlphaFold-Multimer，还声称具有更快的训练效率（约 2.2 倍）。
    *   **用途**: 高精度蛋白质结构预测，AlphaFold 的强力替代方案。

*   **[OpenFold](https://github.com/aqlaboratory/openfold)**
    *   **描述**: AlphaFold2 的可训练、内存高效的 PyTorch 复现。
    *   **用途**: 从头训练蛋白质折叠模型，研究模型架构。

*   **[ColabFold](https://github.com/sokrypton/ColabFold)**
    *   **描述**: 使 AlphaFold2 更易于访问，利用 MMseqs2 加速同源序列搜索。
    *   **用途**: 快速、轻量级的蛋白质结构预测。

## 分子生成与设计 (Molecular Generation & Design)

*   **[REINVENT4](https://github.com/MolecularAI/REINVENT4)**
    *   **描述**: 一个用于分子从头设计 (De Novo Design) 的 AI 工具，使用强化学习 (RL)。
    *   **用途**: 骨架跃迁 (Scaffold Hopping)、R 基团替换、连接体设计和分子优化。

*   **[MoLeR (molecule-generation)](https://github.com/microsoft/molecule-generation)**
    *   **描述**: Microsoft 发布的基于图的分子生成模型。
    *   **用途**: 支持骨架约束的分子生成。

*   **[GT4SD (Generative Toolkit for Scientific Discovery)](https://github.com/GT4SD/molecular-design)**
    *   **描述**: 一个用于基于靶点的分子设计的综合计算管道。
    *   **用途**: 迭代分子生成、优化和合成路线设计。

## 其他工具 (Other Tools)

*   **[MolPipeline](https://github.com/basf/MolPipeline)**: 结合 Scikit-learn 和 RDKit 进行分子数据处理。
*   **[DrugEx](https://github.com/CDDLeiden/DrugEx)**: 使用 RNN 和 Transformer 进行药物从头设计。
*   **[DiffInt](https://github.com/sekijima-lab/DiffInt)**: 基于扩散模型的结构化药物设计工具。
