**\[4].**

* 🧑‍🎓 **Author**：
* 🔗 **Link**：
* 🤔 **Challenge**：
* 📖 **Introduction**：



**\[4].**

* 🧑‍🎓 **Author**：
* 🔗 **Link**：
* 🤔 **Challenge**：
* 📖 **Introduction**：



**\[4]. GS2Mesh: Surface Reconstruction from Gaussian Splatting via Novel Stereo Views**

* 🧑‍🎓 **Author**：Yaniv Wolf, Amit Bracha, Ron Kimmel
* 🔗 **Link**：\[[arXiv:2404.01810](https://arxiv.org/abs/2404.01810)]
* 🤔 **Challenge**：Directly extracting scene geometry from Gaussian properties remains challenging, as these properties are optimized based on photometric loss. While some concurrent models attempt to incorporate geometric constraints during Gaussian optimization, they still produce noisy, unrealistic surfaces.
* 📖 **Introduction**：This paper proposes GS2Mesh, bridging the gap between noisy 3D GS representations and smooth 3D mesh representations by infusing real-world knowledge into the deep extraction process.



**\[3]. Gaussian Grouping: Segment and Edit Anything in 3D Scenes**

* 🧑‍🎓 **Author**：Mingqiao Ye, Martin Danelljan, Fisher Yu, Lei Ke
* 🔗 **Link**：\[[arXiv:2312.00732](https://arxiv.org/abs/2312.00732)]
* 🤔 **Challenge**：Previous works focused solely on appearance and geometric modeling, lacking fine-grained object-level scene understanding.
* 📖 **Introduction**：This paper proposes Gaussian Grouping, which employs compact identity encoding to enhance each Gaussian. By leveraging the 2D mask predictions from the Segment Anything Model (SAM) and introducing 3D spatial consistency regularization to supervise identity encoding during differentiable rendering, it enables grouping Gaussians based on their object instance or membership within objects in a 3D scene.



**\[2]. GaussianPro: 3D Gaussian Splatting with Progressive Propagation**

* 🧑‍🎓 **Author**：Kai Cheng, Xiaoxiao Long, Kaizhi Yang, Yao Yao, Wei Yin, Yuexin Ma, Wenping Wang, Xuejin Chen
* 🔗 **Link**：\[[arXiv:2402.14650](https://arxiv.org/abs/2402.14650)]
* 🤔 **Challenge**：When processing large-scale scenes that inevitably include untracked surfaces, SfM technology consistently fails to generate sufficient points on these surfaces and cannot provide a good initialization for 3DGS.
* 📖 **Introduction**：Inspired by the classic Multi-View Stereo (MVS) technique, we propose GaussianPro, a novel approach that employs a progressive propagation strategy to guide 3D Gaussian densification. Unlike the simple splitting and cloning strategies used in 3DGS, our method leverages prior knowledge of existing reconstructed geometry in the scene and patch matching techniques to generate new Gaussian units.



**\[1]. ⭐3D Gaussian Splatting for Real-Time Radiance Field Rendering**

* 🧑‍🎓 **Author**：Bernhard Kerbl, Georgios Kopanas, Thomas Leimkühler, George Drettakis
* 🔗 **Link**：\[[arXiv:2308.04079](https://arxiv.org/abs/2308.04079)]
* 🤔 **Challenge**：For boundless and complete scenes (rather than isolated objects) and high-resolution rendering, there is currently no method capable of achieving real-time display rates.
* 📖 **Introduction**：3DGS begins with sparse points generated during camera calibration, representing the scene using 3D Gaussians. These Gaussians preserve the ideal properties of continuous volumetric radiation fields for scene optimization while avoiding unnecessary computations in empty space. Subsequently, the 3D Gaussians undergo interleaved optimization/density control, specifically optimizing anisotropic covariance to achieve accurate scene representation. Finally, a fast visible-light-perception rendering algorithm supporting anisotropic scattering accelerates training while enabling real-time rendering.
