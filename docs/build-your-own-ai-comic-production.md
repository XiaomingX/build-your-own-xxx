# AI + 漫剧制作 (Comic/Manga Production)

这里收集了 AI 在漫画/漫剧生成、分镜脚本自动化、角色一致性保持和气泡排版领域的开源替代方案和工具。

## 综合漫画/漫剧生成 (Comprehensive Comic/Manga Generation)

*   **[LlamaGen.Ai](https://github.com/LlamaGenAI)** (组织链接)
    *   **描述**: 一个"AI 漫画工厂"，专注于生成漫画、Webtoon 和动漫。相关项目包括 `LlamaGen` (漫画生成) 和 `webtoon` SDK。
    *   **用途**: 制作可扩展的动漫和漫画内容。

*   **[AI-Comic-Generation](https://github.com/alsaif1431/AI-Comic-Generation)**
    *   **描述**: 使用 Generative AI (OpenAI API + Stable Diffusion) 从简短场景生成完整漫画条的概念验证项目。
    *   **用途**: 自动化漫画生成实验。

*   **[Komiko](https://github.com/Story-Engine-Inc/Komiko)**
    *   **描述**: 一站式 AI 创作平台，用于漫画、Manhwa 和动漫。提供专业绘画、填色和设计工具。
    *   **用途**: 辅助专业漫画制作流程。

*   **[AI Comic Factory](https://github.com/jbilcke-hf/ai-comic-factory)**
    *   **描述**: 使用 LLM 和 SDXL 生成漫画分镜面板的项目，由 Hugging Face 支持。
    *   **用途**: 快速生成可视化的漫画故事板。

## 分镜与故事板 (Storyboarding)

*   **[AI Storyboard Generator](https://github.com/buildappslive/ai-storyboardapp)**
    *   **描述**: 将文本脚本转换为可视化故事板的智能应用，集成 Gemini API。
    *   **用途**: 视频和漫画的前期分镜规划。

*   **[AI-Storyboard-Stable-Diffusion](https://github.com/.../AI-Storyboard-Stable-Diffusion)** (请在 GitHub 搜索确认具体链接)
    *   **描述**: 利用 Stable Diffusion 从用户提示生成故事板。

## 角色一致性与辅助工具 (Character Consistency & Helpers)

*   **[ControlNet](https://github.com/Mikubill/sd-webui-controlnet)** (Stable Diffusion 插件)
    *   **描述**: 极其强大的控制工具，通过骨架、边缘检测等控制图像生成。
    *   **用途**: 保持角色姿势和构图的精确控制，这对漫画叙事至关重要。

*   **[ADetailer](https://github.com/Bing-su/adetailer)**
    *   **描述**: 用于修复和增强生成的面部细节。
    *   **用途**: 确保远景或复杂角度下的角色面部崩坏问题得到解决。

*   **[Textual Inversion / LoRA 训练]**
    *   **描述**: 虽然不是单一工具，但使用如 `kohya_ss` 等工具训练 LoRA 是保持角色一致性的行业标准方法。

## 气泡与排版 (Speech Bubbles & Layout)

*   **[Image Speech Bubble Generation](https://github.com/.../speech-bubble-generator)** (通用脚本)
    *   **描述**: 一些 Python 脚本支持通过命令行向图片添加气泡。目前完全自动化的开源智能排版工具较少，多依赖手动或半自动脚本。
