**\[15]. Periodic Vibration Gaussian: Dynamic Urban Scene Reconstruction and Real-time Rendering**

* 🧑‍🎓 **Author**：Yurui Chen, Chun Gu, Junzhe Jiang, Xiatian Zhu, Li Zhang
* 🔗 **Link**：\[[arXiv:2311.18561](https://arxiv.org/abs/2311.18561)]
* 🤔 **Challenge**：The modeling challenge for dynamic, large-scale urban scenes lies in their highly complex geometric structures and spatially and temporally unconstrained dynamics. Prior approaches typically employ high-level architectural priors that separate static and dynamic elements, resulting in suboptimal capture of their synergistic interactions.
* 📖 **Introduction**：This paper introduces Periodic Vibration Gaussian (PVG), which builds upon 3DGS by incorporating time-based dynamics driven by periodic vibrations. This innovation enables PVG to elegantly and uniformly represent the characteristics of various objects and elements within dynamic urban scenes.



**\[14]. Speedy-Splat: Fast 3D Gaussian Splatting with Sparse Pixels and Sparse Primitives**

* 🧑‍🎓 **Author**：Alex Hanson, Allen Tu, Geng Lin, Vasu Singla, Matthias Zwicker, Tom Goldstein
* 🔗 **Link**：\[[arXiv:2412.00578](https://arxiv.org/abs/2412.00578)]
* 🤔 **Challenge**：Although recent work on compressing 3D-GS models has achieved some acceleration by reducing the number of parameters, few methods directly target rendering speed.
* 📖 **Introduction**：Speedy-Splat optimizes the rendering pipeline to precisely locate Gaussians within scenes, boosting rendering speed without compromising visual fidelity. Furthermore, it introduces a novel pruning technique integrated into the training pipeline, significantly reducing model size and training time while further accelerating rendering performance.



**\[13]. SplatFlow: Self-Supervised Dynamic Gaussian Splatting in Neural Motion Flow Field for Autonomous Driving**

* 🧑‍🎓 **Author**：Su Sun, Cheng Zhao, Zhuoyang Sun, Yingjie Victor Chen, Mei Chen
* 🔗 **Link**：\[[arXiv:2411.15482](https://arxiv.org/abs/2411.15482)]
* 🤔 **Challenge**：Most existing dynamic Gaussian dispersion methods for complex urban scenes rely on costly, manually labeled, accurate object-level supervision, which limits their scalability in practical applications.
* 📖 **Introduction**：This paper introduces SplatFlow, a self-supervised dynamic Gaussian splatting technique within Neural Motion Flow Fields (NMFF) that learns 4D spatiotemporal representations without tracking 3D bounding boxes. This enables accurate dynamic scene reconstruction and novel view synthesis of RGB/depth/flow.



**\[12]. Das3r: Dynamics-aware gaussian splatting for static scene reconstruction**

* 🧑‍🎓 **Author**：Kai Xu, Tze Ho Elden Tse, Jizong Peng, Angela Yao
* 🔗 **Link**：\[[arXiv:2412.19584](https://arxiv.org/abs/2412.19584)]
* 🤔 **Challenge**：Previous 3DGS dynamic reconstruction methods have encountered difficulties when applied to broader everyday video content involving continuous and numerous dynamic components alongside complex camera movements.
* 📖 **Introduction**：This paper proposes DAS3R for scene segmentation and static background reconstruction from everyday videos. By integrating pre-trained motion masks, modeling static scenes as Gaussian fragments, and performing dynamics-aware optimization, it achieves more accurate background reconstruction results than previous work.



**\[11]. DeSiRe-GS: 4D Street Gaussians for Static-Dynamic Decomposition and Surface Reconstruction for Urban Driving Scenes**

* 🧑‍🎓 **Author**：Chensheng Peng, Chengwei Zhang, Yixiao Wang, Chenfeng Xu, Yichen Xie, Wenzhao Zheng, Kurt Keutzer, Masayoshi Tomizuka, Wei Zhan
* 🔗 **Link**：\[[arXiv:2411.11921](https://arxiv.org/abs/2411.11921)]
* 🤔 **Challenge**：Due to the unbounded nature of outdoor environments, 3DGS faces challenges in reconstruction accuracy and efficiency during dynamic driving scene reconstruction.
* 📖 **Introduction**：This paper proposes DeSiRe-GS, a two-stage optimization pipeline based on dynamic street Gaussians. In the first stage, a two-dimensional motion mask is extracted, as the observed three-dimensional Gaussian distribution inherently can only reconstruct static regions in dynamic environments. These extracted 2D motion priors are then differentially mapped into Gaussian space using the efficient formula of the second-stage dynamic Gaussian. Combined with introduced geometric regularization, this approach resolves overfitting issues caused by data sparsity in autonomous driving while reconstructing physically plausible Gaussians.



**\[10]. Mini-Splatting: Representing Scenes with a Constrained Number of Gaussians**

* 🧑‍🎓 **Author**：Guangchi Fang, Bing Wang
* 🔗 **Link**：\[[arXiv:2403.14166v3](https://arxiv.org/abs/2403.14166v3)]
* 🤔 **Challenge**：Using a finite number of Gaussian representations to effectively model scenes
* 📖 **Introduction**：This paper introduces strategies for densification including blur split and depth reinitialization, and simplification through intersection preserving and sampling. These techniques reorganize the spatial positions of the Gaussians, resulting in significant improvements across various datasets and benchmarks in terms of rendering quality, resource consumption, and storage compression.



**\[9]. Street Gaussians: Modeling Dynamic Urban Scenes with Gaussian Splatting**

* 🧑‍🎓 **Author**：Yunzhi Yan, Haotong Lin, Chenxu Zhou, Weijie Wang, Haiyang Sun, Kun Zhan, Xianpeng Lang, Xiaowei Zhou, Sida Peng
* 🔗 **Link**：\[[arXiv:2401.01339](https://arxiv.org/abs/2401.01339)]
* 🤔 Challenge：3DGS exhibits slow training and rendering speeds when modeling dynamic urban streets in autonomous driving scenarios.
* 📖 **Introduction**：The dynamic urban scenes of Street Gaussians are represented as a set of point clouds equipped with semantic logic and 3D Gaussians, each of which is associated with either a foreground vehicle or the background. To model the dynamics of foreground objects, each object point cloud is optimized using an optimizable tracking pose and a 4D spherical harmonic model for dynamic appearance. Street Gaussians enable scene editing operations and rendering at 135 FPS (1066 x 1600 resolution) within half an hour after training.



**\[8]. 4D Gaussian Splatting for Real-Time Dynamic Scene Rendering**

* 🧑‍🎓 **Author**：Guanjun Wu, Taoran Yi, Jiemin Fang, Lingxi Xie, Xiaopeng Zhang, Wei Wei, Wenyu Liu, Qi Tian, Xinggang Wang
* 🔗 **Link**：\[[arXiv:2310.08528](https://arxiv.org/abs/2310.08528)]
* 🤔 **Challenge**：3DGS accurately models complex motion, which is often difficult to achieve efficiently.
* 📖 **Introduction**：This paper proposes 4D Gaussian Splatting (4D-GS) as a holistic representation of dynamic scenes, rather than applying 3D-GS to each individual frame. In 4D-GS, a novel explicit representation is proposed that simultaneously incorporates 3D Gaussian and 4D neurovoxels.



**\[7]. AutoSplat: Constrained Gaussian Splatting for Autonomous Driving Scene Reconstruction**

* 🧑‍🎓 **Author**：Mustafa Khan, Hamidreza Fazlali, Dhruv Sharma, Tongtong Cao, Dongfeng Bai, Yuan Ren, Bingbing Liu
* 🔗 **Link**：\[[arXiv:2407.02598](https://arxiv.org/abs/2407.02598)]
* 🤔 **Challenge**：3DGS faces challenges in simulating driving scenarios due to complex backgrounds, dynamic objects, and sparse views.
* 📖 **Introduction**：This paper proposes AutoSplat to achieve highly realistic reconstruction of autonomous driving scenes. It decomposes the background and imposes geometric constraints on its road and sky regions to enable multi-view consistent rasterization. It uses 3D templates to initialize foreground Gaussians and combines reflection Gaussian consistency constraints to reconstruct invisible parts from symmetric visible views. It captures the dynamic visual features of foreground objects by estimating time-dependent residual spherical harmonics. AutoSplat outperforms state-of-the-art methods in scene reconstruction and novel view synthesis across various driving scenarios.



**\[6]. VDG: Vision-Only Dynamic Gaussian for Driving Simulation**

* 🧑‍🎓 **Author**：Hao Li, Jingfeng Li, Dingwen Zhang, Chenming Wu, Jieqi Shi, Chen Zhao, Haocheng Feng, Errui Ding, Jingdong Wang, Junwei Han
* 🔗 **Link**：\[[arXiv:2406.18198](https://arxiv.org/abs/2406.18198)]
* 🤔 **Challenge**：Previous works heavily relied on precomputed pose and motion structure (SfM) algorithms or expensive sensors with Gaussian initialization.
* 📖 **Introduction**：This paper promotes pose and depth initialization as well as static-dynamic decomposition by integrating self-supervised VO into our pose-free dynamic Gaussian method (VDG) for the first time. In addition, compared with pose-free dynamic view synthesis methods, VDG can process only RGB image inputs and construct dynamic scenes at a faster speed and with a larger scene.



**\[5]. S3Gaussian: Self-Supervised Street Gaussians for Autonomous Driving**

* 🧑‍🎓 **Author**：Nan Huang, Xiaobao Wei, Wenzhao Zheng, Pengju An, Ming Lu, Wei Zhan, Masayoshi Tomizuka, Kurt Keutzer, Shanghang Zhang
* 🔗 **Link**：\[[arXiv:2405.20323](https://arxiv.org/abs/2405.20323)]
* 🤔 **Challenge**：Most previous street 3DGS methods require tracked 3D vehicle bounding boxes to decompose the static and dynamic elements for effective reconstruction, limiting their applications for in-the-wild scenarios.
* 📖 **Introduction**：This paper proposes a self-supervised street Gaussian (S3Gaussian) method that decomposes dynamic and static elements from 4D consistency. S3Gaussian demonstrates the ability to decompose static and dynamic scenes and achieves optimal performance without using 3D annotations.



**\[4]. DrivingGaussian: Composite Gaussian Splatting for Surrounding Dynamic Autonomous Driving Scenes**

* 🧑‍🎓 **Author**：Xiaoyu Zhou, Zhiwei Lin, Xiaojun Shan, Yongtao Wang, Deqing Sun, Ming-Hsuan Yang
* 🔗 **Link**：\[[arXiv:2312.07920](https://arxiv.org/abs/2312.07920)]
* 🤔 **Challenge**：Previous works focused on individual dynamic objects and were unable to handle complex driving scenarios involving static-dynamic composite areas and multiple high-speed moving objects.
* 📖 **Introduction**：DrivingGaussian uses composite dynamic Gaussian maps to process multiple moving objects, independently reconstructing each object and restoring its accurate position and occlusion relationships in the scene. DrivingGaussian outperforms existing methods in dynamic driving scene reconstruction and can achieve realistic surround synthesis with high fidelity and multi-camera consistency.



**\[3]. HUGS: Holistic Urban 3D Scene Understanding via Gaussian Splatting**

* 🧑‍🎓 **Author**：Hongyu Zhou, Jiahao Shao, Lu Xu, Dongfeng Bai, Weichao Qiu, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao
* 🔗 **Link**：\[[arXiv:2403.12722](https://arxiv.org/abs/2403.12722)]
* 🤔 **Challenge**：Previous works have typically focused on specific aspects of understanding urban scenes based on RGB images, requiring additional inputs such as LiDAR scans or manually annotated 3D bounding boxes.
* 📖 **Introduction**：This paper introduces a new pipeline for understanding urban scenes using 3D Gaussian splatting, which can render new viewpoints in real time, generate high-precision 2D and 3D semantic information, and reconstruct dynamic scenes, even in scenes with high noise in 3D bounding box detection.



**\[2]. Motion-aware 3D Gaussian Splatting  for Efficient Dynamic Scene Reconstruction**

* 🧑‍🎓 **Author**：Zhiyang Guo, Wengang Zhou, Li Li, Min Wang, Houqiang Li
* 🔗 **Link**：\[[arXiv:2403.11447](https://arxiv.org/abs/2403.11447)]
* 🤔 **Challenge**：Previous works have primarily focused on extending static 3DGS to time-varying representations, neglecting the rich motion information carried by two-dimensional observations. This approach suffers from performance degradation and model redundancy issues.
* 📖 **Introduction**：A novel motion-aware enhancement framework for dynamic scene reconstruction is proposed, which extracts useful motion cues from optical flow to improve different paradigms of dynamic 3DGS. Compared with the baselines, our method shows significant superiority in both rendering quality and efficiency.



**\[1]. Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis**

* 🧑‍🎓 **Author**：Jonathon Luiten, Georgios Kopanas, Bastian Leibe, Deva Ramanan
* 🔗 **Link**：\[[arXiv:2308.09713](https://arxiv.org/abs/2308.09713)]
* 🤔 **Challenge**：Extend 3DGS from modeling static scenes only to dynamic scenes.
* 📖 **Introduction**：Dynamic 3D Gaussians solve the task of dynamic scene view synthesis and six degrees of freedom (6-DOF) tracking of all dense scene elements, while supporting a wide range of downstream applications, including first-person view synthesis, dynamic scene synthesis, and 4D video editing.
