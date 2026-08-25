# ddnfusion
DDNFusion: A Hybrid Decomposition Dynamic Network for Infrared and Visible Image Fusion

## Datasets
Our data comes from the public datasets TNO, RoadScene and MSRS, which can be obtained from the following links:

TNO: https://figshare.com/articles/dataset/TNO_Image_Fusion_Dataset/1008029

RoadScene: https://github.com/jiayi-ma/RoadScene

MSRS:https://github.com/Linfeng-Tang/MSRS

## Experiments
Cross-modal image fusion results of the tested methods on the TNO dataset.
<img width="3128" height="2039" alt="Fig6_01" src="https://github.com/user-attachments/assets/7439a492-f464-42cb-9539-e2b02832c38c" />

Cross-modal image fusion results of the tested methods on the RoadScene dataset.
<img width="3128" height="2034" alt="Fig7_01" src="https://github.com/user-attachments/assets/e7520605-cff0-432a-ac71-03451bcfd3d7" />

## Quantitative metrics of various methods on the TNO dataset

Bold indicates the best results, and underline indicates the second-best results.

<table>
<thead>
<tr>
<th>Method</th>
<th>AG↑</th>
<th>SF↑</th>
<th>EN↑</th>
<th>SD↑</th>
<th>VIF↑</th>
<th>MI↑</th>
</tr>
</thead>

<tbody>
<tr>
<td>SeAFusion</td>
<td><u>60.524±20.312</u></td>
<td><u>8.463±1.677</u></td>
<td>7.228±0.269</td>
<td>45.966±9.753</td>
<td><u>0.900±0.203</u></td>
<td>3.097±0.595</td>
</tr>

<tr>
<td>MetaFusion</td>
<td><b>81.237±30.958</b></td>
<td><b>9.716±1.681</b></td>
<td><u>7.251±0.387</u></td>
<td><u>48.310±11.996</u></td>
<td>0.699±0.149</td>
<td>2.200±0.446</td>
</tr>

<tr>
<td>CDDFuse</td>
<td>53.911±19.742</td>
<td>8.421±1.737</td>
<td>7.155±0.291</td>
<td>45.441±9.938</td>
<td>0.885±0.192</td>
<td><u>3.466±0.811</u></td>
</tr>

<tr>
<td>Ours</td>
<td>48.195±17.568</td>
<td>7.580±1.636</td>
<td><b>7.423±0.281</b></td>
<td><b>57.281±5.261</b></td>
<td><b>0.975±0.250</b></td>
<td><b>3.596±0.418</b></td>
</tr>

</tbody>
</table>




