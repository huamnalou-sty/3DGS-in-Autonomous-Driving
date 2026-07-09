**\[7]. GS-Occ3D: Scaling Vision-only Occupancy Reconstruction for Autonomous Driving with Gaussian Splatting**

* 🧑‍🎓 **Author**：Baijun Ye, Minghui Qin, Saining Zhang, Moonjun Gong, Shaoting Zhu, Zebang Shen, Luan Zhang, Lu Zhang, Hao Zhao, Hang Zhao
* 🔗 **Link**：\[[arXiv:2507.19451](https://arxiv.org/abs/2507.19451)]
* 🤔 **Challenge**：Large-scale occupancy labels for autonomous driving are hard to obtain with LiDAR, and vision-only occupancy reconstruction suffers from sparse views, occlusion, and dynamic scenes.
* 📖 **Introduction**：GS-Occ3D uses an octree-based Gaussian surfel representation to reconstruct occupancy from vision-only data. It separately models static background, ground, and dynamic objects, enabling scalable occupancy auto-labeling on Waymo-style driving scenes.



**\[6]. ST-GS: Vision-Based 3D Semantic Occupancy Prediction with Spatial-Temporal Gaussian Splatting**

* 🧑‍🎓 **Author**：Xiaoyang Yan, Muleilan Pei, Shaojie Shen
* 🔗 **Link**：\[[arXiv:2509.16552](https://arxiv.org/abs/2509.16552)]
* 🤔 **Challenge**：Gaussian occupancy pipelines are limited by insufficient multi-view spatial interaction and weak temporal consistency across frames.
* 📖 **Introduction**：ST-GS adds guidance-informed spatial aggregation and geometry-aware temporal fusion to Gaussian-based occupancy prediction. It improves spatial reasoning and temporal continuity for vision-centric autonomous-driving occupancy.



**\[5]. GraphGSOcc: Semantic and Geometric Graph Transformer for 3D Gaussian Splatting-based Occupancy Prediction**

* 🧑‍🎓 **Author**：Ke Song, Yunhe Wu, Chunchit Siu, Huiyuan Xiong
* 🔗 **Link**：\[[arXiv:2506.14825](arXiv:2506.14825%5D)]
* 🤔 **Challenge**：Existing 3DGS occupancy methods can neglect semantic correlations among similar regions and suffer boundary ambiguity due to weak geometric constraints.
* 📖 **Introduction**：GraphGSOcc builds dual graph attention over Gaussians: one graph captures geometry-aware neighborhoods and another captures semantic similarity. Multi-scale graph attention improves boundary details and object-level topology for driving-scene occupancy prediction.



**\[4]. S2GO: Streaming Sparse Gaussian Occupancy Prediction**

* 🧑‍🎓 **Author**：Jinhyung Park, Yihan Hu, Chensheng Peng, Wenzhao Zheng, Kris Kitani, Wei Zhan
* 🔗 **Link**：\[[arXiv:2506.05473](https://arxiv.org/abs/2506.05473)]
* 🤔 **Challenge**：Dense voxel or dense Gaussian representations are slow and inflexible for online occupancy prediction in dynamic driving scenes.
* 📖 **Introduction**：S2GO represents the scene using compact 3D queries propagated through time and decoded into semantic Gaussians. Its denoising rendering objective helps capture geometry while enabling faster streaming occupancy prediction on nuScenes and KITTI occupancy benchmarks.



**\[3]. GaussianFormer3D: Multi-modal Gaussian-based Semantic Occupancy Prediction with 3D Deformable Attention**

* 🧑‍🎓 **Author**：Lingjun Zhao, Sizhe Wei, James Hays, Lu Gan
* 🔗 **Link**：\[[arXiv:2505.10685](https://arxiv.org/abs/2505.10685)]
* 🤔 **Challenge**：Fusing multi-modal data for 3D occupancy is often inefficient, and standard 3DGS-based perception lacks the ability to adaptively capture localized semantic features across different sensors.
* 📖 **Introduction**：The authors propose a multi-modal perception framework that utilizes 3D deformable attention to adaptively aggregate features from cameras and LiDAR into Gaussian primitives. By treating 3D Gaussians as unified kernels for both geometry and semantics, the model enables robust semantic occupancy prediction and enhanced multi-view consistency in challenging weather and lighting conditions.



**\[2]. GaussianFormer-2: Probabilistic Gaussian Superposition for Efficient 3D Occupancy Prediction (CVPR/2025)**

* 🧑‍🎓 **Author**：Yuanhui Huang, Amonnut Thammatadatrakoon, Wenzhao Zheng, Yunpeng Zhang, Dalong Du, Jiwen Lu
* 🔗 **Link**：\[[arXiv:2412.04384](https://arxiv.org/abs/2412.04384)]
* 🤔 **Challenge**：Traditional voxel-based occupancy methods suffer from heavy computational costs, while existing Gaussian-based methods struggle to accurately represent complex spatial probability distributions in sparse-view driving scenarios.
* 📖 **Introduction**：This paper introduces a probabilistic Gaussian superposition mechanism that models 3D occupancy as a summation of Gaussian probability density functions. By shifting the perception task from dense voxel grids to a sparse set of learnable Gaussian queries, the framework achieves high-fidelity 3D occupancy prediction with significantly reduced memory footprint and faster inference speed.



**\[1]. GaussianFormer: Scene as Gaussians for Vision-Based 3D Semantic Occupancy Prediction (ECCV/2024)**

* 🧑‍🎓 **Author**：Yuanhui Huang, Wenzhao Zheng, Yunpeng Zhang, Jie Zhou, Jiwen Lu
* 🔗 **Link**：\[[arXiv:2405.17429](https://arxiv.org/abs/2405.17429)]
* 🤔 **Challenge**：Cross-view spatial alignment in 3DGS is often suboptimal when relying solely on SfM points, especially in sparse-view driving scenarios.
* 📖 **Introduction**：This paper proposes a Transformer-based architecture that treats 3D Gaussians as learnable queries within a perception pipeline. By attending to multi-camera features, the "Gaussian-Former" refines the spatial distribution of primitives, enhancing 3D object detection and panoptic segmentation performance.

