**\[8]. GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guided Generative Gaussian Splatting (ICML 2024)**

* 🧑‍🎓 **Author**：Xiaoyu Zhou, Xingjian Ran, Yajiao Xiong, Jinlin He, Zhiwei Lin, Yongtao Wang, Deqing Sun, Ming-Hsuan Yang
* 🔗 **Link**：\[arXiv:2402.07207]
* 🤔 **Challenge**：Generating complex 3D scenes from text requires precise control over multiple objects and their spatial arrangement; existing holistic generation methods often lack user controllability and struggle with object-scene consistency.
* 📖 **Introduction**：GALA3D employs Large Language Models (LLMs) to generate an initial scene layout from text prompts. This layout acts as a strong prior to guide the optimization of a Gaussian Splatting representation, ensuring that individual objects are generated with high fidelity while maintaining a coherent and user-controllable global scene structure.



**\[7]. Hyper-3DG: Text-to-3D Gaussian Generation via Hypergraph**

* 🧑‍🎓 **Author**：Donglin Di, Jiahui Yang, Chaofan Luo, Zhou Xue, Wei Chen, Xun Yang, Yue Gao
* 🔗 **Link**：\[arXiv:2403.09236]
* 🤔 **Challenge**：Generating high-quality 3D objects from text is difficult due to the sophisticated high-order correlations between geometry and texture; standard optimization often leads to degradation or inconsistencies.
* 📖 **Introduction**：Hyper-3DG utilizes a "Geometry and Texture Hypergraph Refiner" (HGRefiner) to capture high-order correlations within 3D objects. By conducting hypergraph learning on patch-level 3D Gaussians, it refines both explicit attributes and latent visual features, significantly enhancing the quality and detail of text-generated 3D content.



**\[6]. PhiP-G: Physics-Guided Text-to-3D Compositional Scene Generation**

* 🧑‍🎓 **Author**：Qixuan Li, Chao Wang, Zongjin He, Yan Peng
* 🔗 **Link**：\[arXiv:2502.00708]
* 🤔 **Challenge**：Text-to-3D generation often fails when creating compositional scenes because models struggle to ensure that the layout of multiple objects complies with physical laws and accurately reflects complex semantic relationships described in text.
* 📖 **Introduction**：PhiP-G is a physics-guided framework that integrates LLM-based agents with a "world model" for scene layout. It uses LLMs to generate a scene graph and employs a physical pool (with adhesion capabilities) to predict physically plausible layouts, which then guide the generation of 3D Gaussian assets, resulting in scenes that are both semantically correct and physically consistent.



**\[5]. SplatTalk: 3D VQA with Gaussian Splatting (ICCV 2025)**

* 🧑‍🎓 **Author**：Anh Thai, Songyou Peng, Kyle Genova, Leonidas Guibas, Thomas Funkhouser
* 🔗 **Link**：\[arXiv:2503.06271]
* 🤔 **Challenge**：Zero-shot 3D Visual Question Answering (3D VQA) typically requires explicit 3D surface representations (meshes/point clouds) or large-scale 3D-language annotations, which are scarce and difficult to obtain.
* 📖 **Introduction**：SplatTalk introduces a self-supervised framework that lifts 2D vision-language features into a 3D Gaussian field. It extracts "3D tokens" from the Gaussian representation that are directly compatible with pretrained LLMs (like Qwen2), enabling the model to answer complex questions about the 3D scene's content and spatial configuration without any 3D-language supervision.



**\[4]. LIVE-GS: LLM Powers Interactive VR by Enhancing Gaussian Splatting**

* 🧑‍🎓 **Author**：Haotian Mao, Zhuoxiong Xu, Siyue Wei, Yule Quan, Nianchen Deng, Xubo Yang
* 🔗 **Link**：\[arXiv:2408.03326]
* 🤔 **Challenge**：Current interactive VR systems based on 3DGS are often limited to simple elastic deformations due to a lack of semantic understanding and physical properties, leading to unrealistic user experiences.
* 📖 **Introduction**：LIVE-GS is a highly realistic interactive VR system that integrates 3DGS with LLM-driven physics. It uses GPT-4o to analyze the physical properties of objects from images and guides a physics engine (based on the Obi solver) to simulate realistic interactions (like collisions and gravity) in real-time, bridging the gap between visual fidelity and physical plausibility.



**\[3]. ChatSplat: 3D Conversational Gaussian Splatting**

* 🧑‍🎓 **Author**：Hanlin Chen, Fangyin Wei, Gim Hee Lee
* 🔗 **Link**：\[arXiv:2412.00734]
* 🤔 **Challenge**：Interacting with 3D environments via language is often limited to simple segmentation; existing methods lack the ability to support rich, multi-level conversations (object, view, and scene levels) and often suffer from the complexity of prompt engineering.
* 📖 **Introduction**：ChatSplat constructs a 3D language field that enables comprehensive chat-based interaction within 3D space. It distinguishes between object-level, view-level, and scene-level interactions by encoding 3D scenes into "language tokens" that a pretrained LLM can process, allowing users to converse naturally with the scene about object properties and spatial arrangements.



**\[2]. Chain of Semantics Programming in 3D Gaussian Splatting Representation for 3D Vision Grounding (CVPR 2025)**

* 🧑‍🎓 **Author**：Jiaxin Shi, Mingyue Xiang, Hao Sun, Yixuan Huang, Zhi Weng
* 🔗 **Link**：\[arXiv:2509.15871]
* 🤔 **Challenge**：3D Vision Grounding (3DVG) faces difficulties in understanding fine-grained semantics and spatial relationships within implicit 3D representations; existing methods struggle to decouple these complex relationships and typically require expensive per-scene training.
* 📖 **Introduction**：This paper proposes a zero-shot neuro-symbolic framework that utilizes LLMs to perform "Chain of Semantics Programming" (CoSP). It deconstructs complex natural language utterances into a relationship graph and performs step-by-step reasoning directly within the 3D Gaussian Splatting representation, achieving state-of-the-art visual grounding without requiring densification or depth information.



**\[1]. Query3D: LLM-Powered Open-Vocabulary Scene Segmentation with Language Embedded 3D Gaussians**

* 🧑‍🎓 **Author**：Amirhosein Chahe, Lifeng Zhou
* 🔗 **Link**：\[arXiv:2408.03516]
* 🤔 **Challenge**：Open-vocabulary querying in 3D scenes (especially for autonomous driving) is critical but challenging; traditional methods relying on fixed canonical phrases fail to capture the subtle distinctions and deep scene understanding required for complex, context-dependent queries.
* 📖 **Introduction**：Query3D enhances Language Embedded 3D Gaussian Splatting (LE3DGS) with an LLM-powered query processing pipeline. It employs LLMs to dynamically generate "context-aware canonical phrases" and "helping positive words" that serve as semantic anchors, enabling precise, open-vocabulary segmentation and object localization that significantly outperforms fixed-phrase baselines.
