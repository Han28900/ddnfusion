# DDNFusion: A Hybrid Decomposition Dynamic Network for Infrared and Visible Image Fusion

# We sincerely appreciate your interest and support. The README will be further improved after acceptance.

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

<table>
<caption>
## Quantitative metrics of various methods on the TNO dataset. Bold indicates the best results.
</caption>

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
<td>PSFusion</td>
<td>55.558±20.488</td>
<td>7.953±1.769</td>
<td>7.158±0.388</td>
<td>42.756±9.876</td>
<td>0.802±0.139</td>
<td>2.585±0.550</td>
</tr>

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
<td>SFINet</td>
<td>59.088±17.159</td>
<td>8.317±1.539</td>
<td>7.152±0.277</td>
<td>42.194±7.708</td>
<td>0.761±0.176</td>
<td>2.470±0.610</td>
</tr>

<tr>
<td>RPFNet</td>
<td>24.071±9.559</td>
<td>4.690±1.477</td>
<td>6.391±0.464</td>
<td>25.620±8.001</td>
<td>0.607±0.110</td>
<td>2.258±0.442</td>
</tr>

<tr>
<td>Crossfuse</td>
<td>43.552±14.294</td>
<td>7.797±1.693</td>
<td>7.053±0.325</td>
<td>43.375±8.813</td>
<td>0.843±0.209</td>
<td>3.342±0.421</td>
</tr>

<tr>
<td>MDA</td>
<td>34.588±10.294</td>
<td>6.055±1.056</td>
<td>6.606±0.289</td>
<td>28.369±4.780</td>
<td>0.674±0.144</td>
<td>2.289±0.435</td>
</tr>

<tr>
<td>Dif-Fusion</td>
<td>52.673±18.677</td>
<td>7.581±1.565</td>
<td>6.998±0.400</td>
<td>39.610±10.774</td>
<td>0.777±0.197</td>
<td>3.055±0.698</td>
</tr>

<tr>
<td>SpTFuse</td>
<td>47.080±17.621</td>
<td>6.631±1.675</td>
<td>7.123±0.306</td>
<td>39.223±9.060</td>
<td>0.807±0.132</td>
<td>2.172±0.458</td>
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
<td>DIDFuse</td>
<td>51.810±16.408</td>
<td>7.971±1.628</td>
<td>7.087±0.622</td>
<td>47.036±12.110</td>
<td>0.744±0.150</td>
<td>2.675±0.441</td>
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


<table>
<caption>
## Quantitative metrics of various methods on the RoadScene dataset. Bold indicates the best results.
</caption>

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
<td>PSFusion</td>
<td>72.275±15.467</td>
<td>8.738±1.009</td>
<td><u>7.382±0.158</u></td>
<td>47.664±5.482</td>
<td>0.736±0.134</td>
<td>2.886±0.558</td>
</tr>

<tr>
<td>SeAFusion</td>
<td>77.540±17.842</td>
<td>9.079±0.950</td>
<td>7.362±0.190</td>
<td>51.178±7.610</td>
<td><u>0.807±0.135</u></td>
<td>3.201±0.482</td>
</tr>

<tr>
<td>SFINet</td>
<td>71.305±13.480</td>
<td>8.788±0.963</td>
<td>7.088±0.138</td>
<td>38.637±2.896</td>
<td>0.616±0.112</td>
<td>2.400±0.361</td>
</tr>

<tr>
<td>RPFNet</td>
<td>32.512±7.178</td>
<td>5.908±0.882</td>
<td>6.749±0.332</td>
<td>31.308±6.879</td>
<td>0.650±0.114</td>
<td>2.900±0.505</td>
</tr>

<tr>
<td>Crossfuse</td>
<td>52.856±13.541</td>
<td>7.757±1.073</td>
<td>7.203±0.219</td>
<td>45.306±8.473</td>
<td>0.786±0.119</td>
<td><u>3.466±0.523</u></td>
</tr>

<tr>
<td>MDA</td>
<td>43.927±9.830</td>
<td>6.958±0.900</td>
<td>6.921±0.217</td>
<td>33.649±4.931</td>
<td>0.681±0.119</td>
<td>2.716±0.508</td>
</tr>

<tr>
<td>Dif-Fusion</td>
<td>69.515±14.604</td>
<td>8.577±0.911</td>
<td>7.177±0.223</td>
<td>43.043±6.700</td>
<td>0.745±0.115</td>
<td>3.114±0.407</td>
</tr>

<tr>
<td>SpTFuse</td>
<td>62.880±13.849</td>
<td>7.949±0.966</td>
<td>7.286±0.186</td>
<td>42.504±6.053</td>
<td>0.749±0.114</td>
<td>2.377±0.392</td>
</tr>

<tr>
<td>MetaFusion</td>
<td><b>95.264±20.905</b></td>
<td><b>9.597±0.934</b></td>
<td>7.368±0.241</td>
<td>50.507±6.378</td>
<td>0.657±0.125</td>
<td>2.598±0.465</td>
</tr>

<tr>
<td>DIDFuse</td>
<td>64.501±14.234</td>
<td>8.411±1.019</td>
<td>7.371±0.274</td>
<td>53.211±13.278</td>
<td>0.743±0.141</td>
<td>3.239±0.626</td>
</tr>

<tr>
<td>CDDFuse</td>
<td><u>81.216±19.940</u></td>
<td><u>9.118±1.001</u></td>
<td><b>7.493±0.184</b></td>
<td><b>58.096±7.708</b></td>
<td>0.802±0.134</td>
<td>3.309±0.509</td>
</tr>

<tr>
<td>Ours</td>
<td>52.619±12.629</td>
<td>7.091±0.919</td>
<td>7.246±0.298</td>
<td><u>54.761±8.679</u></td>
<td><b>0.872±0.105</b></td>
<td><b>3.819±0.457</b></td>
</tr>

</tbody>
</table>




