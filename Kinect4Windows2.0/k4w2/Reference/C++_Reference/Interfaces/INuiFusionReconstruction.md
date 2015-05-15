INuiFusionReconstruction Interface  
==================================  

Dephtデータから3次元形状を再構成する。 <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>interface INuiFusionReconstruction : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**INuiFusionReconstruction**は以下のメンバー関数を持ちます。  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/AlignDepthFloatToReconstru.md">AlignDepthFloatToReconstruction</a></td>
<td align="left">Depthを再構成している3次元形状データに位置合わせしてカメラ姿勢を計算する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/AlignPointClouds_Method.md">AlignPointClouds</a></td>
<td align="left">重複する部分のある2つのPoint Cloudを位置合わせして相対的なカメラ姿勢を計算する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/CalculateMesh_Method.md">CalculateMesh</a></td>
<td align="left">再構成した3次元形状データからメッシュデータを計算してエクスポートする。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/CalculatePointCloud_Method.md">CalculatePointCloud</a></td>
<td align="left">再構成した3次元形状データをレイキャストすることでPoint Cloudを計算する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/CalculatePointCloudAndDepth.md">CalculatePointCloudAndDepth</a></td>
<td align="left">再構成した3次元形状データをレイキャストすることでPoint CloudとDepthを計算する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/DepthToDepthFloatFrame.md">DepthToDepthFloatFrame</a></td>
<td align="left">DepthデータをNUI_FUSION_IMAGE_FRAMEに変換する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/ExportVolumeBlock_Method.md">ExportVolumeBlock</a></td>
<td align="left">再構成した3次元形状データを配列にエクスポートする。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/GetCurrentWorldToCameraTra.md">GetCurrentWorldToCameraTransform</a></td>
<td align="left">現在のワールド座標系からカメラ座標系への変換行列(カメラ姿勢)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/GetCurrentWorldToVolumeTra.md">GetCurrentWorldToVolumeTransform</a></td>
<td align="left">現在のワールド座標系から再構成した3次元形状データのローカル座標系への変換行列を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/ImportVolumeBlock_Method.md">ImportVolumeBlock</a></td>
<td align="left">配列から3次元形状データをインポートする。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/IntegrateFrame_Method.md">IntegrateFrame</a></td>
<td align="left">指定したカメラ姿勢でDepthとColorを再構成した3次元形状データに統合する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/ProcessFrame_Method.md">ProcessFrame</a></td>
<td align="left">DpehtをKinect Fusionの各処理をまとめたパイプラインに流し込んで計算する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/ResetReconstruction_Method.md">ResetReconstruction</a></td>
<td align="left">再構成した3次元形状データを破棄、カメラ姿勢を初期化してKinect Fusionをリセットする。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionReconstruction/Methods/SetAlignDepthFloatToRecons.md">SetAlignDepthFloatToReconstructionReferenceFrame</a></td>
<td align="left"><a href="INuiFusionReconstruction/Methods/AlignDepthFloatToReconstru.md">AlignDepthFloatToReconstruction</a>でカメラ姿勢を計算するときに内部で用いられる基準となるDepthを設定する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionReconstruction/Methods/SmoothDepthFloatFrame_Method.md">SmoothDepthFloatFrame</a></td>
<td align="left">エッジ保存型のフィルタを用いてDepthを平滑化する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : INuiFusionReconstruction Interface
RLTitle : INuiFusionReconstruction Interface
KeywordK : INuiFusionReconstruction interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : INuiFusionReconstruction
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction
KeywordA : T:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction
AssetID : T:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
