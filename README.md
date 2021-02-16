# Visual-Based-Localization-Papers

Contributed by Dehao Zhang.

The relocalization task aims to estimate the 6-DoF pose of a novel (unseen) frame in the coordinate system given by the prior model of the world.  The most related academic topics are SLAM and SfM and it's widely applied in AR, Robotic, etc.


<h1 id="Surveys">Survey</h1>

- **[Image-based camera localization: an overview]** Yihong Wu. Visual Computing for Industry, Biomedicine, and Art, 2018. [**[paper]**](https://arxiv.org/abs/1610.03660)


<h1 id="system">System</h1>

- **[Wide area localization on mobile phones]** Clemens Arth. ISMAR, 2009. [**[paper]**](https://www.researchgate.net/publication/221221483_Wide_Area_Localization_on_Mobile_Phones)

- **[Real-time self-localization from panoramic images on mobile devices]** Clemens Arth. ISMAR, 2011. [**[paper]**](https://ieeexplore.ieee.org/document/6162870)

- **[Parallel Tracking and Mapping on a Camera Phone]** ISMAR, 2009. [**[paper]**](https://ieeexplore.ieee.org/document/5336495)


- **[Scalable 6-DOF Localization on Mobile Devices]** Iven Middelberg, Torsten Sattler. ECCV, 2014. [**[paper]**](https://www.graphics.rwth-aachen.de/media/**paper**s/ECCV14_preprint.pdf)

- **[6D dynamic camera relocalization from single reference image]** Feng W. CVPR 2016. [**[paper]**](http://openaccess.thecvf.com/content_cvpr_2016/**paper**s/Feng_6D_Dynamic_Camera_CVPR_2016_**paper**.pdf)


- **[Image Matching Across Wide Baselines: From Paper to Practice]** Yuehe, Jin. CVPR, 2020. [**[paper]**](https://arxiv.org/abs/2003.01587) [**[code]**](https://github.com/ubc-vision/image-matching-benchmark) 


- **[GN-Net: The Gauss-Newton Loss for Multi-Weather Relocaliza-tion]** L. von Stumberg, P. Wenzel, Q. Khan, and D. Cremers. ICRA, 2020. [**[paper]**](https://arxiv.org/abs/1904.11932) [**[code]**](https://github.com/Artisense-ai/GN-Net-Benchmark)

- **[Using Image Sequences for Long-Term Visual Localization]** Erik Stenborg, Torsten Sattler and Lars Hammarstrand. 3DV, 2020. [**[paper]**](https://ieeexplore.ieee.org/document/9320360) [**[code]**](https://github.com/rulllars/SequentialVisualLocalization)

- **[LM-Reloc: Levenberg-Marquardt Based Direct Visual Relocalization]** Lukas von Stumberg, Patrick Wenzel, Nan Yang, Daniel Cremers. 3DV, 2020.** [**[paper]**](https://arxiv.org/abs/2010.06323)

<h1 id="FeatureExtration">Feature Extracting</h1>

<h1 id="FeatureMatch">Feature Matching</h1>

- **[SuperGlue: Learning Feature Matching with Graph Neural Networks]  ** Paul-Edouard Sarlin. CVPR, 2020. [**[paper]**](https://arxiv.org/abs/1911.11763) [**[code]**](https://github.com/magicleap/SuperGluePretrainedNetwork) 

- **[Learning Feature Descriptors using Camera Pose Supervision]  ** Qianqian Wang. ECCV, 2020(oral). [**[paper]**](https://arxiv.org/abs/2004.13324) [**[code]**](https://github.com/qianqianwang68/caps)


<h1 id="Retrieval">Retrieval Methods</h1>

- **[Visual Categorization with Bags of Keypoints]** G. Csurka. ECCV, 2004. [**[paper]**](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/csurka-eccv-04.pdf)

- **[Total Recall: Automatic Query Expansion
with a Generative Feature Model for Object Retrieval]** Chum, O. ICCV, 2007. [**[paper]**](https://www.robots.ox.ac.uk/~vgg/publications/**paper**s/chum07b.pdf)

- **[Fisher Kernels on Visual Vocabularies for Image Categorization]** F. Perronnin and C. Dance. CVPR, 2007. [**[paper]**](https://ieeexplore.ieee.org/document/4270291)

- **[Aggregating Local Descriptors Into a Compact Image Representation]** H. Jegou. CVPR, 2010. [**[paper]**](https://lear.inrialpes.fr/pubs/2010/JDSP10/jegou_compactimagerepresentation.pdf)

- **[Fast image-based localization using direct 2D to-3D matching]** Sattler T. ICCV, 2011. [**[paper]**](https://graphics.rwth-aachen.de/media/**paper**s/sattler_iccv11_preprint_011.pdf) [**[code]**](https://www.graphics.rwth-aachen.de/software/image-localization/)

- **[Improving image-based localization by active correspondence search]** ECCV, 2012. [**[paper]**](https://graphics.rwth-aachen.de/media/**paper**s/sattler_eccv12_preprint_1.pdf)

- ** [Aggregating Deep Convolutional Features for Image Retrieval]** A. Babenko and V. Lempitsky. ICCV, 2015. [**[paper]**](https://arxiv.org/abs/1510.07493)

- **[A Vote-and-Verify Strategy for Fast Spatial Verification in Image Retrieval]** Johannes L. Sch¨onberger. ACCV, 2016. [**[paper]**](https://frahm.web.unc.edu/wp-content/uploads/sites/6231/2016/06/schoenberger2016vote.pdf) [**[code]**](https://frahm.web.unc.edu/wp-content/uploads/sites/6231/2016/06/schoenberger2016vote.pdf)

- **[NetVLAD: CNN Architecture for Weakly Supervised Place Recognition]** R. Arandjelovic. CVPR, 2016. [**[paper]**](https://arxiv.org/abs/1511.07247)

- **[Crossdimensional Weighting for Aggregated Deep Convolutional Features]** Y. Kalantidis. ECCV, 2016. [**[paper]**](https://arxiv.org/abs/1512.04065) [**[code]**](https://github.com/yahoo/crow)

- **[Fine-Tuning CNN Image Retrieval with no Human Annotation]** F. Radenovic, G. PAMI, 2017. [**[paper]**](https://arxiv.org/pdf/1711.02512) [**[code]**](https://arxiv.org/pdf/1711.02512)

- **[Efficient diffusion on region manifolds: Recovering small objects with compact cnn representations]** A. Iscen. CVPR, 2017. [**[paper]**](https://arxiv.org/abs/1611.05113)

- **[Revisiting Oxford and Paris: Large-scale Image Retrieval Benchmarking]** F. Radenovic, G. CVPR, 2018.  [**[paper]**](https://arxiv.org/abs/1803.11285)

- **[Learning with Average Precision: Training Image Retrieval with a Listwise Loss]** J. Revaud. ICCV, 2019. [**[paper]**](https://arxiv.org/abs/1906.07589)


- **[Benchmarking Image Retrieval for Visual Localization]** Noé Pion,..., Torsten Sattler. 3DV, 2020. [**[paper]**](https://arxiv.org/abs/2011.11946) <a href="https://github.com/naver/kapture-localization">**[code]**</a> 

<h1 id="Pose">Pose Estimation</h1>

- **[Fixing the Locally Optimized RANSAC]**  Karel Lebeda. BMVC, 2012. [**[paper]**](http://www.bmva.org/bmvc/2012/BMVC/**paper**095/**paper**095.pdf)

- **[DSAC - Differentiable RANSAC for Camera Localization]**E. Brachmann. CVPR, 2017. [**[paper]**](https://arxiv.org/abs/1611.05705)

- **[MAGSAC: marginalizing sample consensus]**  Barath, D. CVPR, 2019. [**[paper]**](https://arxiv.org/abs/1803.07469)


<h1 id="Fusion">Multi-sensors Fusion</h1>

<h2 id="Fusion with IMU">Fusion with IMU</h2>

- **[DARNavi: An Indoor-Outdoor Immersive Navigation System with Augmented Reality]**Didi Chuxing. CVPR, 2020. [**[paper]**](https://**paper**.nweon.com/2688)

<h2 id="Fusion with GPS">Fusion with GPS</h2>

- **[Multi-sensor navigation algorithm using monocular camera, imu and gps for large scale augmented reality]** T. Oskiper. ISMAR, 2012. [**[paper]**](https://ieeexplore.ieee.org/document/6402541)

- **[Gomsf: Graph-optimization based multi-sensor fusion for robust uav pose estimation]** R. Mascaro, L. ICRA 2018. [**[paper]**](https://ieeexplore.ieee.org/document/8460193)

- **[Intermittent GPS-aided VIO: Online Initialization and Calibration]** Woosik Lee. ICRA, 2020. [**[paper]**](https://ieeexplore.ieee.org/document/9197029)

- **[Vins Fusion — A General Optimization-based Framework for Global
Pose Estimation with Multiple Sensors]** Tong Qin. [**[paper]**](https://arxiv.org/abs/1901.03642)



<h1 id="SLAM">SLAM</h1>

- **[Neural Topological SLAM for Visual Navigation]** Devendra Singh Chaplot. CVPR, 2020. [**[paper]**](https://arxiv.org/abs/2005.12256)


<h1 id="SfM">SfM</h1>

- **[Consistent Video Depth Estimation]** XUAN LUO. SIGGRAPH 2020. [**[paper]**](https://arxiv.org/abs/2004.15021)

- **[DeepSFM: Structure From Motion Via Deep Bundle Adjustment]** ECCV 2020. [**[paper]**](https://arxiv.org/abs/1912.09697)


<h1 id="Wait">Waiting to sort</h1>

- **[FREAK:Fast Retina Keypoint.]** A. Amit. CVPR, 2012.

- **[Three things evereyone should know to improve object retrieval]** R. Arandjelovic. CVPR, 2012. 

- **[Learning local feature descriptors with triplets and shallow convolutional neural networks]** V. Balntas. BMVC, 2016. 

- **[Learning 6D Object Pose Estimation Using 3D Objet Coordinates]** E.Brachmann. ECCV, 2014.

- **[DSAC-Differentiable RANSAC for Camera Localization]** E.Brachmann. CVPR, 2017. 

- **[Discriminative Learning of Local Image Descriptors]** TPAMI, 2011.


- **[MatchNet: Unifying feature and metric learning for patch-based matching]**X. Han. CVPR, 2015. 

- **[Comparative evaluation of binary features]**J. Heinly. ECCV. 

- **[PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization]**A. Kendall, M. ICCV, 2015. -

- **[LIFT: Learned Invariant Feature Transform]** M.Kwang. ECCV, 2016.

- **[Semantic Visual Localization]** J. L. Schonberger. CVPR, 2018. 

- **[Camera Pose Voting for Large-Scale Image-Based Localization]** B. Zeisl. ICCV, 2015.. 

- **[ASLFeat: Learning Local Features of Accurate Shape and Localization]** Zixin, Lup. CVPR, 2020. 

- **[City-Scale Localization for Cameras with Known Vertical Direction]** Linus Svarm. TAPMI, 2016. 

- **[ACNe: Attentive Context Normalization for Robust PermutationEquivariant Learning]** Sun, W. CVPR, 2020.

- **[Is there anything new to say about SIFT matching?]** Fabio Bellavia. IJCV, 2020.

- **[Learning to Find Good Correspondences]** Kwang Moo Yi. CVPR, 2018, oral.





