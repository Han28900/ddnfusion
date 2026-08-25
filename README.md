# ddnfusion
DDNFusion: A Hybrid Decomposition Dynamic Network for Infrared and Visible Image Fusion

Datasets
Our data comes from the public datasets TNO, RoadScene and MSRS, which can be obtained from the following links:
TNO: https://figshare.com/articles/dataset/TNO_Image_Fusion_Dataset/1008029
RoadScene: https://github.com/jiayi-ma/RoadScene
MSRS:https://github.com/Linfeng-Tang/MSRS

Experiments
Cross-modal image fusion results of the tested methods on the TNO dataset.
<img width="3128" height="2039" alt="Fig6_01" src="https://github.com/user-attachments/assets/7439a492-f464-42cb-9539-e2b02832c38c" />

Cross-modal image fusion results of the tested methods on the RoadScene dataset.
<img width="3128" height="2034" alt="Fig7_01" src="https://github.com/user-attachments/assets/e7520605-cff0-432a-ac71-03451bcfd3d7" />

## Quantitative metrics of various methods on the TNO dataset

Bold indicates the best results, and underline indicates the second-best results.

| Method | AG↑ | SF↑ | EN↑ | SD↑ | VIF↑ | MI↑ |
|:---|---:|---:|---:|---:|---:|---:|
| PSFusion | 55.558±20.488 | 7.953±1.769 | 7.158±0.388 | 42.756±9.876 | 0.802±0.139 | 2.585±0.550 |
| SeAFusion | <u>60.524±20.312</u> | <u>8.463±1.677</u> | 7.228±0.269 | 45.966±9.753 | <u>0.900±0.203</u> | 3.097±0.595 |
| SFINet | 59.088±17.159 | 8.317±1.539 | 7.152±0.277 | 42.194±7.708 | 0.761±0.176 | 2.470±0.610 |
| RPFNet | 24.071±9.559 | 4.690±1.477 | 6.391±0.464 | 25.620±8.001 | 0.607±0.110 | 2.258±0.442 |
| Crossfuse | 43.552±14.294 | 7.797±1.693 | 7.053±0.325 | 43.375±8.813 | 0.843±0.209 | 3.342±0.421 |
| MDA | 34.588±10.294 | 6.055±1.056 | 6.606±0.289 | 28.369±4.780 | 0.674±0.144 | 2.289±0.435 |
| Dif-Fusion | 52.673±18.677 | 7.581±1.565 | 6.998±0.400 | 39.610±10.774 | 0.777±0.197 | 3.055±0.698 |
| SpTFuse | 47.080±17.621 | 6.631±1.675 | 7.123±0.306 | 39.223±9.060 | 0.807±0.132 | 2.172±0.458 |
| MetaFusion | **81.237±30.958** | **9.716±1.681** | <u>7.251±0.387</u> | <u>48.310±11.996</u> | 0.699±0.149 | 2.200±0.446 |
| DIDFuse | 51.810±16.408 | 7.971±1.628 | 7.087±0.622 | 47.036±12.110 | 0.744±0.150 | 2.675±0.441 |
| CDDFuse | 53.911±19.742 | 8.421±1.737 | 7.155±0.291 | 45.441±9.938 | 0.885±0.192 | <u>3.466±0.811</u> |
| Ours | 48.195±17.568 | 7.580±1.636 | **7.423±0.281** | **57.281±5.261** | **0.975±0.250** | **3.596±0.418** |




