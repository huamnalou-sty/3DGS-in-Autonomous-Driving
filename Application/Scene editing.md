**\[14]. GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting (CVPR 2024)**

* 🧑‍🎓 **Author**：Yiwen Chen, Zilong Chen, Chi Zhang, Feng Wang, Xiaofeng Yang, Yikai Wang, Zhongang Cai, Lei Yang, Huaping Liu, Guosheng Lin
* 🔗 **Link**：\[[arXiv:2311.14521](https://arxiv.org/abs/2311.14521)]
* 🤔 **Challenge**：Existing 3D editing methods suffer from high latency and limited controllability, making real-time or interactive editing difficult.
* 📖 **Introduction**：GaussianEditor introduces a fast Gaussian reconstruction strategy and progressive refinement scheme, enabling interactive 3D editing with text, masks, or geometric handles. It significantly reduces optimization overhead and provides fine-grained controls over appearance and structure.



**\[13]. 3DitScene: Editing Any Scene via Language-Guided Disentangled Gaussian Splatting**

* 🧑‍🎓 **Author**：Qihang Zhang, Yinghao Xu, Chaoyang Wang, Hsin-Ying Lee, Gordon Wetzstein, Bolei Zhou, Ceyuan Yang
* 🔗 **Link**：\[[arXiv:2405.18424](https://arxiv.org/abs/2405.18424)]
* 🤔 **Challenge**：Achieving precise text-driven control in 3D scenes is difficult because semantic features are entangled within Gaussian appearance and geometry.
* 📖 **Introduction**：3DitScene learns a language-guided disentangled Gaussian representation by aligning Gaussians with CLIP semantic space. This enables accurate semantic localization and supports object replacement, pose modification, and material editing through natural language instructions.



**\[12]. EditSplat: Multi-View Fusion and Attention-Guided Trimming for Text-Driven 3D Editing (CVPR 2025)**

* 🧑‍🎓 **Author**：Dong In Lee, Hyeongcheol Park, Jiyoung Seo, Eunbyung Park, Hyunje Park, Ha Dam Baek, Sangheon Shin, Sangmin Kim, Sangpil Kim
* 🔗 **Link**：\[[arXiv:2412.11520](https://arxiv.org/abs/2412.11520)]
* 🤔 **Challenge**：Directly editing Gaussians often leaves redundant or conflicting appearance features, slowing optimization and reducing visual fidelity.
* 📖 **Introduction**：EditSplat proposes multi-view fusion guidance (MFG) and attention-guided trimming (AGT) to refine Gaussian sets before editing. By removing irrelevant Gaussians and reconstructing only the necessary regions, the model accelerates text-driven editing and improves multi-view consistency.



**\[11]. GSEdit: Efficient Text-Guided Editing of 3D Objects via Gaussian Splatting**

* 🧑‍🎓 **Author**：Francesco Palandra, Andrea Sanchietti, Daniele Baieri, Emanuele Rodolà
* 🔗 **Link**：\[[arXiv:2403.05154](https://arxiv.org/abs/2403.05154)]
* 🤔 **Challenge**：Performing high-quality text-guided appearance editing on 3D objects is computationally expensive and often breaks structure.
* 📖 **Introduction**：GSEdit leverages 3D Gaussian Splatting and incremental Gaussian optimization to enable fast and semantically consistent appearance editing. By using pre-trained diffusion models for supervision, the method achieves high-quality text-aligned editing in minutes on consumer GPUs while preserving geometric structure.



**\[10]. View-Consistent 3D Editing with Gaussian Splatting (ECCV 2024)**

* 🧑‍🎓 **Author**：Yuxuan Wang, Xuanyu Yi, Zike Wu, Na Zhao, Long Chen, Hanwang Zhang
* 🔗 **Link**：\[[arXiv:2403.11868](https://arxiv.org/abs/2403.11868)]
* 🤔 **Challenge**：Image-space diffusion guidance often causes view inconsistency and introduces artifacts when applied to 3D scene editing.
* 📖 **Introduction**：VcEdit introduces a view-consistent editing mechanism by jointly optimizing camera-space diffusion outputs and Gaussian parameters. It enforces multi-view coherence through cross-view fusion and geometric constraints, enabling text-guided and mask-guided editing with significantly reduced inconsistencies.



**\[9]. 3DSceneEditor: Controllable 3D Scene Editing with Gaussian Splatting**

* 🧑‍🎓 **Author**：Ziyang Yan, Lei Li, Yihua Shao, Siyu Chen, Zongkai Wu, Jenq-Neng Hwang, Hao Zhao, Fabio Remondino
* 🔗 **Link**：\[[arXiv:2412.01583](https://arxiv.org/abs/2412.01583)]
* 🤔 **Challenge**：Existing diffusion-based or 2D-driven editing pipelines often fail to enforce multi-view consistency and lack precise control over 3D structures.
* 📖 **Introduction**：3DSceneEditor proposes a fully 3D-aware editing framework directly built upon 3D Gaussian Splatting. It introduces semantic labeling, CLIP-based guidance, and Gaussian-level operations such as addition, deletion, recoloring, and relocation. The system achieves multi-view consistent object-level editing and improves stability over 2D-driven editing methods.



**\[8]. ABC-GS: Alignment-Based Controllable Style Transfer for 3D Gaussian Splatting (ICME 2025)**

* 🧑‍🎓 **Author**：Wenjie Liu, Zhongliang Liu, Xiaoyan Yang, Man Sha, Yang Li
* 🔗 **Link**：\[[arXiv:2503.22218](https://arxiv.org/abs/2503.22218?utm_source=chatgpt.com)]
* 🤔 **Challenge**：Existing 3DGS stylization lacks global alignment and region-level control, often causing inconsistent multi-view appearance.
* 📖 **Introduction**：ABC-GS introduces an alignment-based controllable pipeline for 3D Gaussian Splatting. It performs segmentation-guided content–style alignment, applies feature-based style transfer on Gaussians, and preserves geometry through consistency regularization, enabling coherent and controllable 3D stylization.



**\[7]. InstDrive: Instance-Aware 3D Gaussian Splatting for Driving Scenes**

* 🧑‍🎓 **Author**：Fuying Wang, Cheng Chen, Jiacheng Liao, Tianchen Deng, Kecheng Zheng, Yiwei Ma, Wenbing Tao, Yu-Kun Lai, Liang Pan
* 🔗 **Link**：\[[arXiv:2508.12015](https://arxiv.org/abs/2508.12015)]
* 🤔 **Challenge**：Existing 3DGS-based driving scene reconstruction methods treat the scene holistically or separate only static/dynamic components, lacking explicit instance-level modeling of dynamic traffic participants (vehicles, pedestrians, cyclists). This limits downstream tasks such as object-level editing, tracking, simulation, and closed-loop evaluation.
* 📖 **Introduction**：InstDrive proposes the first instance-aware 3D Gaussian Splatting framework tailored for large-scale driving scenes. It decomposes the scene into static background Gaussians and per-instance dynamic Gaussians with learned canonical representations, enabling instance segmentation, independent motion control, and high-quality novel-view rendering at 120+ FPS. InstDrive achieves SOTA reconstruction quality on nuScenes and KITTI-360 while supporting fine-grained instance manipulation and relighting for advanced autonomous driving applications.



**\[6]. MultiEditor: Controllable Multimodal Object Editing for Driving Scenarios Using 3D Gaussian Splatting Priors**

* 🧑‍🎓 **Author**：Shouyi Lu, Yufei Wang, Ziyu Chen, Yifan Wang, Yue Wang, Marco Pavone
* 🔗 **Link**：\[[arXiv:2507.21872](https://arxiv.org/abs/2507.21872)]
* 🤔 **Challenge**：Autonomous driving systems rely on multimodal perception data, but the long-tailed distribution of real-world data hinders generalization, especially for rare but safety-critical vehicle categories; existing editing methods for images or LiDAR point clouds lack joint consistency, object-level structural priors, and precise controllability, leading to artifacts and semantic drift.
* 📖 **Introduction**：MultiEditor introduces a dual-branch latent diffusion framework that jointly edits images and LiDAR point clouds in driving scenarios, leveraging 3D Gaussian Splatting (3DGS) as a unified prior for target object structure and appearance. This enables flexible, high-fidelity editing of atypical vehicles with precise pose control and multi-view consistency, outperforming prior methods in generating diverse, safety-critical scenarios for robust perception training.



**\[5]. Gaussian-UDSR: Real-Time Unbounded Dynamic Scene Reconstruction with 3D Gaussian Splatting**

* 🧑‍🎓 **Author**：Yiming Wang, Zhiyu Tan, Haotian Zhang, Yifan Wang, Yulan Guo
* 🔗 **Link**：\[[DOI:10.3390/app15116262](https://www.mdpi.com/2076-3417/15/11/6262)]
* 🤔 **Challenge**：Existing methods struggle to reconstruct dynamic scenes in unbounded outdoor environments due to challenges such as lighting variation, object motion, and sensor limitations, leading to inaccurate geometry and low rendering fidelity.
* 📖 **Introduction**：Gaussian-UDSR proposes a novel 3D Gaussian-based representation that efficiently reconstructs and renders high-quality, unbounded dynamic scenes in real time. It adopts 3D Gaussian splatting as a unified representation to jointly model static backgrounds and dynamic foreground objects, incorporating LiDAR-SfM point cloud fusion, a Gaussian color feature prediction network, and a pose-tracking mechanism for high-fidelity autonomous driving scene reconstruction.



**\[4]. OmniRe: Omni Urban Scene Reconstruction (ICLR 2025)**

* 🧑‍🎓 **Author**：Ziyu Chen, Jiawei Yang, Jiahui Huang, Riccardo de Lutio, Janick Martinez Esturo, Boris Ivanovic, Or Litany, Zan Gojcic, Sanja Fidler, Marco Pavone, Li Song, Yue Wang
* 🔗 **Link**：\[[arXiv:2408.16760](https://arxiv.org/abs/2408.16760)]
* 🤔 **Challenge**：Existing neural field/3DGS methods focus on vehicles, lacking holistic reconstruction of diverse dynamic foregrounds (pedestrians, cyclists) for full urban simulations like human behavior.
* 📖 **Introduction**：OmniRe builds scene graphs on 3DGS with canonical Gaussian representations for all dynamic actors from on-device logs. It enables ~60Hz holistic simulations including human-vehicle interactions, outperforming SOTA on Waymo and generalizing to other datasets.



**\[3]. DENSER: 3D Gaussians Splatting for Scene Reconstruction of Dynamic Urban Environments**

* 🧑‍🎓 **Author**：Mahmud A. Mohamad, Gamal Elghazaly, Arthur Hubert, Raphael Frank
* 🔗 **Link**：\[[arXiv:2409.10041](https://arxiv.org/abs/2409.10041)]
* 🤔 **Challenge**：NeRF/3DGS struggle with dynamic urban scenes, causing artifacts in foreground objects' appearance, especially distant ones under varying conditions; scene graph methods overlook time-varying details.
* 📖 **Introduction**：DENSER employs scene graphs with 3DGS for static/dynamic decomposition, dynamically estimates SH via wavelets for spatiotemporal appearance, and multi-frame point cloud densification for shape. It outperforms SOTA on KITTI with fast convergence and editing features.



**\[2]. Street Gaussians: Modeling Dynamic Urban Scenes with Gaussian Splatting (ECCV 2024)**

* 🧑‍🎓 **Author**：Yunzhi Yan, Haotong Lin, Chenxu Zhou, Weijie Wang, Haiyang Sun, Kun Zhan, Xianpeng Lang, Xiaowei Zhou, Sida Peng
* 🔗 **Link**：\[[arXiv:2401.01339](https://arxiv.org/abs/2401.01339)]
* 🤔 **Challenge**：NeRF extensions for dynamic urban scenes with vehicle poses enable photo-realism but suffer from slow training/rendering; need efficient representation for autonomous driving.
* 📖 **Introduction**：Street Gaussians represents scenes via point clouds with semantic logits and 3D Gaussians for vehicles (optimized poses + 4D SH appearance) and background. It enables composition/editing, 30-min training, 135 FPS rendering, and SOTA on KITTI/Waymo.



**\[1]. SpectralGaussians: Semantic, spectral 3D Gaussian splatting for multi-spectral scene representation, visualization and analysis**

* 🧑‍🎓 **Author**：Saptarshi Neil Sinha, Holger Graf, Michael Weinmann
* 🔗 **Link**：\[[arXiv:2408.06975](https://arxiv.org/abs/2408.06975)]
* 🤔 **Challenge**：Multi-spectral scene representation, rendering, and editing lack accuracy; existing methods (XNeRF, SpectralNeRF) fail to capture semantic/material insights across spectra.
* 📖 **Introduction**：SpectralGaussians extends 3DGS for cross-spectral rendering, generating semantic splats from multi-view spectra/segmentations. It introduces per-spectrum PBR estimating reflectance/lights, enabling style transfer/inpainting/removal, outperforming spectral/non-spectral baselines.
