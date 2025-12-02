**\[11]. EGS-SLAM: RGB-D Gaussian Splatting SLAM with Events**

* 🧑‍🎓 **Author**：Siyu Chen, Shenghai Yuan, Thien-Minh Nguyen, Zhuyu Huang, Chenyang Shi, Jin Jing, Lihua Xie
* 🔗 **Link**：\[arXiv:2508.07003]
* 🤔 **Challenge**：Standard RGB-D SLAM fails in high-speed motion scenarios due to motion blur, while event cameras (which have high temporal resolution) are sparse and lack texture, making it difficult to produce photorealistic reconstructions.
* 📖 **Introduction**：EGS-SLAM fuses event data with RGB-D inputs to handle motion blur and fast dynamics. It explicitly models the camera's continuous trajectory during exposure time to deblur images using event data. Simultaneously, it uses a unified Gaussian representation that is optimized by both the deblurred images and the event stream, achieving robust tracking and high-fidelity reconstruction even in severe motion blur conditions.



**\[10]. VPGS-SLAM: Voxel-based Progressive 3D Gaussian SLAM in Large-Scale Scenes**

* 🧑‍🎓 **Author**：Tianchen Deng, Wenhua Wu, Weidong Chen
* 🔗 **Link**：
* 🤔 **Challenge**：Maintaining a globally consistent Gaussian map in large-scale scenes is memory-intensive and prone to tracking failure; existing submap-based methods may suffer from boundary artifacts or slow retrieval speeds.
* 📖 **Introduction**：VPGS-SLAM proposes a voxel-based progressive mapping strategy. It divides the space into voxels, where each voxel manages its own set of Gaussians. As the camera moves, the system progressively activates and deactivates voxels, ensuring constant-time tracking complexity and efficient memory usage. This allows for seamless transitions between submaps and robust performance in extended large-scale trajectories.



**\[9]. Large-Scale Gaussian Splatting SLAM (ICRA 2025)**

* 🧑‍🎓 **Author**：Zhe Xin, Chenyang Wu, Penghui Huang, Yanyong Zhang, Yinian Mao, Guoquan Huang
* 🔗 **Link**：\[arXiv:2505.09915]
* 🤔 **Challenge**：Scaling 3DGS SLAM to large environments is difficult due to memory limitations and drift; a single global Gaussian map becomes unmanageable, and standard frame-to-frame tracking drifts significantly over long trajectories.
* 📖 **Introduction**：This paper, termed LSG-SLAM, presents a large-scale stereo visual SLAM system. It divides the scene into continuous "Gaussian Submaps" to manage memory and scale. It introduces a "feature-alignment warping constraint" to improve tracking robustness against appearance similarities and employs a global optimization backend that merges submaps via loop closure, enabling consistent reconstruction of city-scale environments.



**\[8]. HI-SLAM2: Geometry-Aware Gaussian SLAM for Fast Monocular Scene Reconstruction**

* 🧑‍🎓 **Author**：Wei Zhang, Qing Cheng, David Skuddis, Niclas Zeller, Daniel Cremers, Norbert Haala
* 🔗 **Link**：
* 🤔 **Challenge**：Monocular 3DGS SLAM systems often suffer from scale ambiguity and geometric distortion; purely photometric losses are insufficient to constrain the geometry of the Gaussians, leading to "floaters" and inaccurate surface reconstruction.
* 📖 **Introduction**：HI-SLAM2 introduces a geometry-aware optimization strategy for monocular Gaussian SLAM. It incorporates geometric regularization terms (such as depth consistency and normal alignment) into the Gaussian optimization process. This ensures that the reconstructed map is not only visually pleasing but also geometrically accurate, enabling fast and high-quality scene reconstruction from a single camera.



**\[7]. GSPR: Multimodal Place Recognition Using 3D Gaussian Splatting for Autonomous Driving**

* 🧑‍🎓 **Author**：Zhangshuo Qi, Junyi Ma, Jingyi Xu, Zijie Zhou, Luqi Cheng, Guangming Xiong
* 🔗 **Link**：\[arXiv:2410.00299]
* 🤔 **Challenge**：Place recognition in autonomous driving is critical for loop closure but challenging due to viewpoint changes and environmental variations. Existing methods using 2D images or point clouds separately struggle to capture the comprehensive structural and textural information of a scene.
* 📖 **Introduction**：GSPR exploits 3D Gaussian Splatting as a unified scene representation for multimodal place recognition. It constructs a "Multimodal Gaussian Splatting" (MGS) representation combining LiDAR geometry and visual appearance. A custom network with 3D graph convolutions and transformers then extracts global descriptors from these Gaussian scenes, significantly improving place recognition accuracy compared to unimodal approaches.



**\[6]. RGB-Only Gaussian Splatting SLAM for Unbounded Outdoor Scenes (ICRA 2025)**

* 🧑‍🎓 **Author**：Sicheng Yu, Chong Cheng, Yifan Zhou, Xiaojun Yang, Hao Wang
* 🔗 **Link**：\[arXiv:2502.15633]
* 🤔 **Challenge**：Most 3DGS-based SLAM systems rely on depth sensors (RGB-D) and fail in unbounded outdoor scenarios where depth is unavailable; estimating accurate depth and scale solely from RGB images for Gaussian initialization is highly unstable.
* 📖 **Introduction**：Also known as OpenGS-SLAM, this method proposes an RGB-only pipeline tailored for unbounded outdoor scenes. It utilizes a "pointmap regression network" to generate consistent geometry across frames for pose estimation and initialization. By integrating this with an end-to-end differentiable rendering pipeline, it simultaneously optimizes camera poses and scene parameters, achieving high-fidelity outdoor mapping without LiDAR or depth sensors.



**\[5]. LiV-GS: LiDAR-Vision Integration for 3D Gaussian Splatting SLAM in Outdoor Environments**

* 🧑‍🎓 **Author**：Xiaolei Lang, Jiajun Lv, Kai Tang, Xingxing Zuo
* 🔗 **Link**：\[arXiv:2405.19632]
* 🤔 **Challenge**：Applying 3DGS to large-scale outdoor SLAM is difficult because sparse LiDAR data does not naturally align with the continuous Gaussian representation, and visual-only initialization often fails in open, texture-poor areas.
* 📖 **Introduction**：LiV-GS is an outdoor SLAM system that tightly couples LiDAR and visual data. It adaptively initializes 3D Gaussians from LiDAR measurements to constrain scene geometry and employs a sliding window optimization to refine both the trajectory and the Gaussian map. This integration ensures geometric accuracy from LiDAR and photorealistic appearance from vision, surpassing single-sensor baselines.



**\[4]. LoopSplat: Loop Closure by Registering 3D Gaussian Splats (3DV 2025)**

* 🧑‍🎓 **Author**：Liyuan Zhu, Yue Li, Erik Sandström, Shengyu Huang, Konrad Schindler, Iro Armeni
* 🔗 **Link**：\[arXiv:2410.16273]
* 🤔 **Challenge**：Standard Gaussian Splatting SLAM lacks a robust loop closure mechanism; traditional point cloud registration methods (like ICP) are not directly applicable to the splat representation, leading to accumulated drift and inconsistent maps over long trajectories.
* 📖 **Introduction**：LoopSplat introduces a novel loop closure module that registers 3D Gaussian submaps directly. Instead of converting splats to meshes or points, it aligns two Gaussian representations by minimizing a 3D-to-3D registration energy function tailored for splats. This allows the system to correct drift and merge maps globally, ensuring consistent large-scale reconstruction.



**\[3]. Photo-SLAM: Real-Time Simultaneous Localization and Photorealistic Mapping for Monocular, Stereo, and RGB-D Cameras (CVPR 2024)**

* 🧑‍🎓 **Author**：Huajian Huang, Longwei Li, Hui Cheng, Sai-Kit Yeung
* 🔗 **Link**：\[arXiv:2311.16728]
* 🤔 **Challenge**：Existing SLAM systems typically struggle to balance localization accuracy with photorealistic mapping quality; purely geometric SLAM lacks visual fidelity, while NeRF-based SLAM is computationally heavy and often fails to run in real-time on embedded devices.
* 📖 **Introduction**：Photo-SLAM presents a modular framework that decouples tracking and mapping by using "Hyper Primitives"—combining explicit geometric features (ORB) for robust localization with a 3D Gaussian map for photorealistic rendering. This hybrid approach enables state-of-the-art rendering quality and real-time performance on varied hardware (from PCs to embedded systems) across monocular, stereo, and RGB-D settings.



**\[2]. GS-SLAM: Dense Visual SLAM with 3D Gaussian Splatting (CVPR 2024)**

* 🧑‍🎓 **Author**：Chi Yan, Delin Qu, Dong Wang, Dan Xu, Zhigang Wang, Bin Zhao, Xuelong Li
* 🔗 **Link**：\[arXiv:2311.11700]
* 🤔 **Challenge**：Traditional dense SLAM methods relying on neural implicit representations (like NeRF) suffer from slow rendering speeds and expensive optimization, making them unsuitable for real-time applications that require both accurate mapping and high-fidelity re-rendering.
* 📖 **Introduction**：GS-SLAM is the first RGB-D SLAM system to utilize 3D Gaussian Splatting for both tracking and mapping. It introduces an adaptive expansion strategy to dynamically add or prune Gaussians based on geometric errors and coverage, enabling the system to efficiently reconstruct new scene geometry while maintaining a compact map size and achieving real-time performance.



**\[1]. MM-Gaussian: 3D Gaussian-based Multi-modal Fusion for Localization and Reconstruction in Unbounded Scenes (IROS 2024)**

* 🧑‍🎓 **Author**：Chenyang Wu, Yifan Duan, Xinran Zhang, Yu Sheng, Jianmin Ji, Yanyong Zhang
* 🔗 **Link**：\[arXiv:2404.04026]
* 🤔 **Challenge**：In large-scale unbounded scenes, single-modal SLAM often fails; camera-only methods suffer from depth ambiguity, while LiDAR-only methods lack texture and color information, making it difficult to achieve both precise localization and high-fidelity photorealistic reconstruction simultaneously.
* 📖 **Introduction**：MM-Gaussian proposes a multi-modal fusion framework that integrates LiDAR and camera data into a unified 3D Gaussian representation. It utilizes LiDAR point clouds to initialize Gaussians, providing accurate geometry, while optimizing color and texture from images. This tight coupling allows for robust tracking in challenging lighting conditions and enables high-quality real-time rendering of large-scale outdoor environments.
