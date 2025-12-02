**\[15]. Graph-Guided Scene Reconstruction from Images with 3D Gaussian Splatting (ICLR 2025)**

* 🧑‍🎓 **Author**：Chong Cheng, Gaochao Song, Yiyang Yao, Qinzheng Zhou, Gangjian Zhang, Hao Wang
* 🔗 **Link**：\[[arXiv:2502.17377](https://arxiv.org/abs/2502.17377)]
* 🤔 **Challenge**：Existing methods need precise poses and dense views; 3DGS overfits sparse viewpoints, slowing large open scene reconstruction.
* 📖 **Introduction**：GraphGS estimates scene structure via spatial priors to build camera graphs, then applies graph-guided consistency constraints and adaptive sampling for optimized 3DGS, enabling efficient high-fidelity reconstruction from uncalibrated RGB images.



**\[14]. GeoProg3D: Compositional Visual Reasoning for City-Scale 3D Language Fields (ICCV 2025)**

* 🧑‍🎓 **Author**：Shunsuke Yasuki, Taiki Miyanishi, Nakamasa Inoue, Shuhei Kurita, Koya Sakamoto, Daichi Azuma, Masato Taki, Yutaka Matsuo
* 🔗 **Link**：\[[arXiv:2506.23352](https://arxiv.org/abs/2506.23352)]
* 🤔 **Challenge**：Existing 3D language fields are confined to small-scale scenes, lacking scalability and compositional reasoning for complex city-scale urban environments.
* 📖 **Introduction**：GeoProg3D is a visual programming framework with Geography-aware City-scale 3D Language Field (GCLF) for memory-efficient hierarchical modeling and Geographical Vision APIs (GV-APIs) driven by LLMs for natural language queries. It introduces GeoEval3D benchmark with 952 pairs across five tasks, achieving SOTA in geographic reasoning.



**\[13]. CityGS-X: A Scalable Architecture for Efficient and Geometrically Accurate Large-Scale Scene Reconstruction (ICCV 2025)**

* 🧑‍🎓 **Author**：Yuanyuan Gao, Hao Li, Jiaqi Chen, Zhengyu Zou, Zhihang Zhong, Dingwen Zhang, Xiao Sun, Junwei Han
* 🔗 **Link**：\[[arXiv:2503.23044](https://arxiv.org/abs/2503.23044)]
* 🤔 **Challenge**：3DGS faces slow processing, high costs, limited accuracy from unstructured design and poor parallelization, causing OOM in large scenes (5k+ images).
* 📖 **Introduction**：CityGS-X uses parallelized hybrid hierarchical 3D representation (PH^2-3D) with batch-level multi-task rendering and dynamic LOD voxels for efficient multi-GPU training, enabling faster times, larger capacity, and superior geometry.



**\[12]. Gaussian Splatting for Large-Scale Aerial Scene Reconstruction From Ultra-High-Resolution Images (Computer Graphics Forum 2025)**

* 🧑‍🎓 **Author**：Qiulin Sun, Wei Lai, Yixian Li, Yanci Zhang
* 🔗 **Link**：\[[DOI:10.1111/cgf.70265](https://onlinelibrary.wiley.com/doi/10.1111/cgf.70265)]
* 🤔 **Challenge**：Reconstructing large-scale aerial scenes via 3DGS from ultra-high-res (9K) images exceeds single-GPU memory limits, causing scalability issues.
* 📖 **Introduction**：Introduces a task partitioning algorithm in object and image space to create small subtasks, enabling efficient reconstruction on a single RTX 4090 GPU.



**\[11]. Robust and Efficient 3D Gaussian Splatting for Urban Scene Reconstruction (ICCV 2025)**

* 🧑‍🎓 **Author**：Zhensheng Yuan, Haozhi Huang, Zhen Xiong, Di Wang, Guanghua Yang
* 🔗 **Link**：\[[arXiv:2507.23006](https://arxiv.org/abs/2507.23006)]
* 🤔 **Challenge**：Handling appearance variations in urban multi-view captures causing inconsistencies; optimizing training for large scenes without losing speed/quality; balancing Gaussian density for real-time rendering under budgets.
* 📖 **Introduction**：REUrbanGS enables fast reconstruction and real-time rendering of urban scenes via scene partitioning with visibility-based image selection for parallel training, controllable LOD for Gaussian density, appearance transformation for inconsistency mitigation, and enhancements like depth/scale regularization and antialiasing, outperforming priors in efficiency and quality.



**\[10]. Horizon-GS: Unified 3D Gaussian Splatting for Large-Scale Aerial-to-Ground Scenes (CVPR 2025)**

* 🧑‍🎓 **Author**：Lihan Jiang, Kerui Ren, Mulin Yu, Linning Xu, Junting Dong, Tao Lu, Feng Zhao, Dahua Lin, Bo Dai
* 🔗 **Link**：\[[arXiv:2412.01745](https://arxiv.org/abs/2412.01745)]
* 🤔 **Challenge**：Integrating aerial and street views in neural reconstruction is limited by single-domain focus, hindering immersive exploration with large viewpoint changes horizontally/vertically.
* 📖 **Introduction**：Horizon-GS employs Gaussian Splatting with a novel training strategy to unify aerial-to-ground reconstruction, bridging viewpoint gaps for high-fidelity scenes. It curates a synthetic/real dataset and excels on urban benchmarks.



**\[9]. FlashGS: Efficient 3D Gaussian Splatting for Large-scale and High-resolution Rendering (CVPR 2025)**

* 🧑‍🎓 **Author**：Guofeng Feng, Siyan Chen, Rong Fu, Zimu Liao, Yi Wang, Tao Liu, Zhilin Pei, Hengjie Li, Xingcheng Zhang, Bo Dai
* 🔗 **Link**：\[[arXiv:2408.07967](https://arxiv.org/abs/2408.07967)]
* 🤔 **Challenge**：Vanilla 3DGS rasterization is inefficient for large-scale scenes and high-res rendering, especially on mobile GPUs, due to redundancy, suboptimal pipelining, scheduling, and memory access.
* 📖 **Introduction**：FlashGS is an open-source CUDA Python library optimizing 3DGS differentiable rasterization via redundancy elimination, efficient pipelining, refined control/scheduling, and memory optimizations. It achieves 4x average speedup and lower memory on mobile GPUs across diverse large scenes.



**\[8]. Generative Gaussian Splatting for Unbounded 3D City Generation (CVPR 2025)**

* 🧑‍🎓 **Author**：Haozhe Xie, Zhaoxi Chen, Fangzhou Hong, Ziwei Liu
* 🔗 **Link**：\[[arXiv:2406.06526](https://arxiv.org/abs/2406.06526)]
* 🤔 **Challenge**：NeRF-based city generation is inefficient; scaling 3DGS to unbounded cities incurs massive VRAM from billions of points, causing out-of-memory issues.
* 📖 **Introduction**：GaussianCity employs BEV-Point for compact intermediate representation to maintain constant VRAM, and a spatial-aware decoder integrating structural/contextual features for Gaussian attributes, enabling single-pass unbounded city synthesis at SOTA quality and 60x speedup over CityDreamer.



**\[7]. Octree-GS: Towards Consistent Real-time Rendering with LOD-Structured 3D Gaussians**

* 🧑‍🎓 **Author**：Kerui Ren, Lihan Jiang, Tao Lu, Mulin Yu, Linning Xu, Zhangkai Ni, Bo Dai
* 🔗 **Link**：\[[arXiv:2403.17898](https://arxiv.org/abs/2403.17898)]
* 🤔 **Challenge**：3DGS faces bottlenecks in large scenes from excessive Gaussians in frustum, causing inconsistent speeds in zoom-out views; heuristic density control fails to capture multi-scale details.
* 📖 **Introduction**：Octree-GS employs LOD-structured Gaussians with multi-resolution anchors for dynamic level selection, ensuring consistent real-time rendering and high-fidelity across scales.



**\[6]. A Hierarchical 3D Gaussian Representation for Real-Time Rendering of Very Large Datasets (SIGGRAPH 2024)**

* 🧑‍🎓 **Author**：Bernhard Kerbl, Andréas Meuleman, Georgios Kopanas, Michael Wimmer, Alexandre Lanvin, George Drettakis
* 🔗 **Link**：\[[arXiv:2406.12080](https://arxiv.org/abs/2406.12080)]
* 🤔 **Challenge**：Existing radiance field methods, including 3DGS, cannot scale to very large scenes due to training/rendering resource limits; sparse image coverage causes optimization issues like poor geometry and artifacts.
* 📖 **Introduction**：Hierarchical 3DGS subdivides large scenes into chunks for parallel training, builds a Gaussian hierarchy with optimized interior nodes for LOD rendering and smooth transitions. It adapts training with regularization for sparse data, enabling real-time rendering of km-scale trajectories.



**\[5]. Scaffold-GS: Structured 3D Gaussians for View-Adaptive Rendering (CVPR 2024)**

* 🧑‍🎓 **Author**：Tao Lu, Mulin Yu, Linning Xu, Yuanbo Xiangli, Limin Wang, Dahua Lin, Bo Dai
* 🔗 **Link**：\[[arXiv:2312.00109](https://arxiv.org/abs/2312.00109)]
* 🤔 **Challenge**：3DGS generates redundant Gaussians fitting all views, ignoring geometry, causing poor robustness to view changes, texture-less regions, and lighting effects.
* 📖 **Introduction**：Scaffold-GS anchors Gaussians on sparse grids, spawning view-adaptive neural Gaussians predicted by direction/distance. With anchor growing/pruning for coverage, it reduces redundancy, boosts quality in diverse scenes, and maintains real-time speed.



**\[4]. CityDreamer: Compositional Generative Model of Unbounded 3D Cities (CVPR 2024)**

* 🧑‍🎓 **Author**：Haozhe Xie, Zhaoxi Chen, Fangzhou Hong, Ziwei Liu
* 🔗 **Link**：\[[arXiv:2309.00610](https://arxiv.org/abs/2309.00610)]
* 🤔 **Challenge**：3D city generation faces structural distortions sensitivity and building appearance diversity; prior works excel in natural scenes but fail in urban due to inconsistent building representations.
* 📖 **Introduction**：CityDreamer composes neural fields for building instances and background stuff in bird's-eye view, using volumetric rendering with generative hash grids and periodic embeddings. It introduces CityGen datasets (OSM/GoogleEarth) for realistic layouts/appearances, achieving SOTA generation and localized editing.



**\[3]. HGS-Mapping: Online Dense Mapping Using Hybrid Gaussian Representation in Urban Scenes**

* 🧑‍🎓 **Author**：Ke Wu, Kaizhao Zhang, Zhiwei Zhang, Shanshuai Yuan, Muer Tie, Julong Wei, Zijun Xu, Jieru Zhao, Zhongxue Gan, Wenchao Ding
* 🔗 **Link**：\[[arXiv:2403.20159](https://arxiv.org/abs/2403.20159)]
* 🤔 **Challenge**：Integrating 3DGS into urban online dense mapping yields incomplete reconstruction beyond LiDAR coverage and high compute/memory demands; prior works limit to indoors or rely on slow SfM initialization unsuitable for real-time.
* 📖 **Introduction**：HGS-Mapping enables online dense mapping in large urban scenes via Hybrid Gaussian Representation (Sphere, 3D, 2D Gaussians) for full coverage. With hybrid initialization and adaptive densification/pruning, it achieves SOTA rendering quality/speed using 66% fewer Gaussians—first Gaussian-based framework for urban online mapping.



**\[2]. VastGaussian: Vast 3D Gaussians for Large Scene Reconstruction (CVPR 2024)**

* 🧑‍🎓 **Author**：Jiaqi Lin, Zhihao Li, Xiao Tang, Jianzhuang Liu, Shiyong Liu, Jiayue Liu, Yangdi Lu, Xiaofei Wu, Songcen Xu, Youliang Yan, Wenming Yang
* 🔗 **Link**：\[[arXiv:2402.17427](https://arxiv.org/abs/2402.17427)]
* 🤔 **Challenge**：NeRF-based methods for large scenes lack visual quality and rendering speed; scaling 3DGS faces video memory limits, long optimization times, and appearance variations causing floaters.
* 📖 **Introduction**：VastGaussian partitions large scenes into cells using progressive visibility-based data selection for parallel optimization and seamless merging. It introduces decoupled appearance modeling during training to suppress floaters, discarded post-optimization for real-time rendering, outperforming NeRF baselines on large datasets.



**\[1]. GauU-Scene: A Scene Reconstruction Benchmark on Large Scale 3D Reconstruction Dataset Using Gaussian Splatting**

* 🧑‍🎓 **Author**：Butian Xiong, Zhuo Li, Zhen Li
* 🔗 **Link**：\[[arXiv:2401.14032](https://arxiv.org/abs/2401.14032)]
* 🤔 **Challenge**：Existing large-scale datasets lack precise LiDAR ground truth, suffer from image-time differences, or fail to correlate point clouds with images; Gaussian Splatting blurs in close views and inadequately handles rooftop/drone data.
* 📖 **Introduction**：GauU-Scene introduces a 1.5 km² dataset with drone-captured RGB images and high-accuracy LiDAR point clouds across urban/academic scenes. It benchmarks Gaussian Splatting, proposes a LiDAR-Image fusion method to boost reconstruction via Gaussian priors, and reveals gaps in large-scale drone-based 3D reconstruction.
