**\[7]. PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics (CVPR 2024)**

* 🧑‍🎓 **Author**：Tianyi Xie, Zeshun Zong, Yuxing Qiu, Xuan Li, Yutao Feng, Yin Yang, Chenfanfu Jiang
* 🔗 **Link**：\[[arXiv:2311.12198](https://arxiv.org/abs/2311.12198)]
* 🤔 **Challenge**：Generating realistic dynamics from static images is challenging because standard rendering primitives (like 3D Gaussians) do not inherently possess physical attributes such as mass, velocity, or stress. Existing methods often require converting these representations into meshes for simulation, which introduces a "rendering gap" and loss of fidelity between the physical simulation and the final visual synthesis.
* 📖 **Introduction**：PhysGaussian introduces a unified simulation-rendering pipeline that seamlessly integrates continuum mechanics into 3D Gaussian Splatting. By employing a custom Material Point Method (MPM), it treats 3D Gaussian kernels as both visual elements and physical particles, enriching them with kinematic deformation and mechanical stress attributes. This allows for high-quality, physics-based motion synthesis—including elastic, plastic, and fluid dynamics—directly from the visual representation without the need for explicit meshing.



**\[6]. GASP: Gaussian Splatting for Physic-Based Simulations**

* 🧑‍🎓 **Author**：Piotr Borycki, Weronika Smolak, Joanna Waczyńska, Marcin Mazur, Sławomir Tadeja, Przemysław Spurek
* 🔗 **Link**：\[[arXiv:2409.05819](https://arxiv.org/abs/2409.05819)]
* 🤔 **Challenge**：3D Gaussian Splatting is primarily a visual rendering technique lacking inherent physical properties, making it difficult to integrate directly with physics engines for interactive simulations involving collisions or deformations.
* 📖 **Introduction**：GASP introduces a pipeline that bridges 3DGS with physics-based simulations by parameterizing "flat" Gaussians via triangle mesh vertices. This allows the system to utilize standard "black box" physics engines to drive the dynamics of the Gaussian scene—enabling realistic interactions like collisions—without modifying the underlying physics solvers.



**\[5]. DeSiRe-GS: 4D Street Gaussians for Static-Dynamic Decomposition and Surface Reconstruction for Urban Driving Scenes (CVPR 2025)**

* 🧑‍🎓 **Author**：Chensheng Peng, Chengwei Zhang, Yixiao Wang, Chenfeng Xu, Yichen Xie, Wenzhao Zheng, Kurt Keutzer, Masayoshi Tomizuka, Wei Zhan
* 🔗 **Link**：\[[arXiv:2411.11921](https://arxiv.org/abs/2411.11921)]
* 🤔 **Challenge**：Accurately separating static backgrounds from dynamic objects in complex urban scenes is difficult, as existing methods often produce artifacts or rely heavily on expensive explicit 3D bounding box annotations.
* 📖 **Introduction**：DeSiRe-GS proposes a self-supervised 4D Gaussian Splatting framework for effective static-dynamic decomposition and surface reconstruction without 3D annotations. It employs a two-stage optimization pipeline that extracts 2D motion priors and maps them into Gaussian space to model dynamic objects and static backgrounds efficiently.



**\[4]. GSAVS: Gaussian Splatting-based Autonomous Vehicle Simulator**

* 🧑‍🎓 **Author**：Rami Wilson
* 🔗 **Link**：\[[arXiv:2412.18816](https://arxiv.org/abs/2412.18816)]
* 🤔 **Challenge**：Traditional mesh-based simulators often lack photorealism, while replicating dangerous driving scenarios (such as crashes) in the real world for data collection is unsafe and impractical.
* 📖 **Introduction**：GSAVS is an autonomous vehicle simulator where every asset (vehicles, environment) is represented as a 3D Gaussian splat. By integrating 3DGS into the Unity game engine, it combines real-time photorealistic rendering with the flexibility of traditional engines to safely simulate complex static and dynamic driving environments.



**\[3]. Unraveling the Effects of Synthetic Data on End-to-End Autonomous Driving (ICCV 2025)**

* 🧑‍🎓 **Author**：Junhao Ge, Zuhong Liu, Longteng Fan, Yifan Jiang, Jiaqi Su, Yiming Li, Zhejun Zhang, Siheng Chen
* 🔗 **Link**：\[[arXiv:2503.18108](https://arxiv.org/abs/2503.18108)]
* 🤔 **Challenge**：Collecting large-scale real-world driving data is expensive and time-consuming, while existing simulators often fail to produce diverse, high-fidelity sensor data required to robustly train end-to-end autonomous driving models.
* 📖 **Introduction**：This study utilizes "SceneCrafter," a 3DGS-based simulator, to systematically investigate the impact of synthetic data on end-to-end models. It demonstrates a power-law relationship between model performance and synthetic data volume, proving that high-quality, diverse synthetic data significantly enhances model robustness and generalization.



**\[2]. 3DGAA: Realistic and Robust 3D Gaussian-based Adversarial Attack for Autonomous Driving**

* 🧑‍🎓 **Author**：Yixun Zhang, Lizhi Wang, Junjun Zhao, Wending Zhao, Feng Zhou, Yonghao Dang, Jianqin Yin
* 🔗 **Link**：\[[arXiv:2507.09993](https://arxiv.org/abs/2507.09993)]
* 🤔 **Challenge**：Existing physical adversarial attacks typically focus on 2D images or textures, struggling to balance physical realism with attack robustness; they often fail to jointly optimize geometry and appearance, limiting their effectiveness in real-world environments.
* 📖 **Introduction**：3DGAA is the first framework to leverage the full 14-dimensional parameter space of 3D Gaussian Splatting for adversarial attacks. By jointly perturbing geometric attributes (shape, scale, rotation) and appearance (color, opacity), it generates physically realistic adversarial objects that drastically reduce detection accuracy (e.g., lowering mAP from 87.21% to 7.38%).



**\[1]. R3D2: Realistic 3D Asset Insertion via Diffusion for Autonomous Driving Simulation**

* 🧑‍🎓 **Author**：William Ljungbergh, Bernardo Taveira, Wenzhao Zheng, Adam Tonderski, Chensheng Peng, Fredrik Kahl, Christoffer Petersson, Michael Felsberg, Kurt Keutzer, Masayoshi Tomizuka, Wei Zhan
* 🔗 **Link**：\[[arXiv:2506.07826](https://arxiv.org/abs/2506.07826)]
* 🤔 **Challenge**：Autonomous driving simulations suffer from a "sim-to-real" gap, where inserting new 3D assets into neural scene reconstructions often results in unrealistic visuals due to inconsistent lighting, shadows, and reflections.
* 📖 **Introduction**：R3D2 introduces a lightweight, one-step diffusion model designed to photorealistically insert complete 3D assets into neural scene reconstructions. It learns to generate plausible rendering effects—such as shadows and consistent lighting—essential for seamless asset integration, significantly improving the realism of simulated scenarios.
