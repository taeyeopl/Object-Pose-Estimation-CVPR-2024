# **2024 CVPR Object Pose Estimation**

# **Object Pose Estimation in CVPR 2024**

**[[ALL CVPR Accepted Papers](https://cvpr.thecvf.com/Conferences/2024/AcceptedPapers)]**

## **Novel Object**

1. **FoundationPose: Unified 6D Pose Estimation and Tracking of Novel Objects [[page](https://nvlabs.github.io/FoundationPose/)] [[pdf](https://arxiv.org/pdf/2312.08344)] [[code](https://github.com/NVlabs/FoundationPose)]**
    1. Input: RGBD, CAD or Reference Images
    2. Pose Estimation: Pose Hypothesis + Pose Selection
2. **SAM-6D: Segment Anything Model Meets Zero-Shot 6D Object Pose Estimation [[pdf](https://arxiv.org/pdf/2311.15707)] [[code](https://github.com/JiehongLin/SAM-6D?utm_source=catalyzex.com)]**
    1. Input: RGBD, CAD
    2. Pose Estimation: Point Registration →  Coarse([Geometric Transformer](https://github.com/qinzheng93/GeoTransformer?utm_source=catalyzex.com)) + Fine(SDPT)
3. **MatchU: Matching Unseen Objects for 6D Pose Estimation from RGB-D Images [[pdf](https://arxiv.org/pdf/2403.01517.pdf)]**
    1. Input: RGBD, CAD
    2. Pose Estimation: Pose Hypothese ([RoITr](https://github.com/haoyu94/RoITr)) + RANSAC + Optimization
4. **GigaPose: Fast and Robust Novel Object Pose Estimation via One Correspondence [[page](https://nv-nguyen.github.io/gigaPose/)] [[pdf](https://arxiv.org/pdf/2311.14155)] [[code](https://nv-nguyen.github.io/gigaPose/)]**
    1. Input: RGB, CAD
    2. Pose Estimation: RANSAC + ePnP (Kabsch)
5. **GenFlow: Generalizable Recurrent Flow for 6D Pose Refinement of Novel Objects [[pdf](https://arxiv.org/pdf/2403.11510.pdf)]**
    1. Input: RGB or RGBD, CAD
    2. Pose Estimation: Pose hypothese (GMM) + Refinement + Cascade
6. **NOPE: Novel Object Pose Estimation from a Single Image [[page](https://nv-nguyen.github.io/nope/)] [[pdf](https://arxiv.org/pdf/2303.13612)] [[code](https://github.com/nv-nguyen/nope)]**
    1. Input: RGB, Reference RGB Image
    2. Pose Estimation: Template mataching + Pose Ambiguities
7. **Open-vocabulary object 6D pose estimation [[page](https://jcorsetti.github.io/oryon/)] [[pdf](https://arxiv.org/pdf/2312.00690.pdf)] [[code](https://github.com/jcorsetti/oryon)]**
    1. Input: RGBD, Text Prompt 
    2. Pose Estimation: Point Registration([PointDSC](https://github.com/XuyangBai/PointDSC))

## **Category-level Object**

1. **HouseCat6D -- A Large-Scale Multi-Modal Category Level 6D Object Perception Dataset with Household Objects in Realistic Scenarios [[page](https://sites.google.com/view/housecat6d)] [[pdf](https://arxiv.org/pdf/2212.10428.pdf)] [[code](https://github.com/Junggy/HouseCat6D?utm_source=catalyzex.com)]**
2. **SecondPose: SE(3)-Consistent Dual-Stream Feature Fusion for Category-Level Pose Estimation [[pdf](https://arxiv.org/pdf/2311.11125.pdf)] [[code](https://github.com/NOrangeeroli/SecondPose)]**
3. **Instance-Adaptive and Geometric-Aware Keypoint Learning for Category-Level 6D Object Pose Estimation**
4. **GeoReF: Geometric Alignment Across Shape Variation for Category-level Object Pose Refinement**
5. **Category-Level Multi-Part Multi-Joint 3D Shape Assembly [[pdf](https://arxiv.org/pdf/2303.06163.pdf)]**

## **Instance-level Object**

1. **HiPose: Hierarchical Binary Surface Encoding and Correspondence Pruning for RGB-D 6DoF Object Pose Estimation [[pdf](https://arxiv.org/pdf/2311.12588.pdf)]**
2. **6-DoF Pose Estimation with MultiScale Residual Correlation [[pdf](https://arxiv.org/pdf/2403.08019.pdf)]**

## **Diffusion Based Method**

1. **Confronting Ambiguity in 6D Object Pose Estimation via Score-Based Diffusion on SE(3) [[pdf](https://arxiv.org/pdf/2305.15873.pdf)]**
2. **Object Pose Estimation via the Aggregation of Diffusion Features**

## **Not Yet**

1. **Towards Co-Evaluation of Cameras, HDR, and Algorithms for Industrial-Grade 6DoF Pose Estimation**
2. **Unsupervised Learning of Category-Level 3D Pose from Object-Centric Videos**
