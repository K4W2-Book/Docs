INuiFusionColorReconstruction::ResetReconstruction Method  
=========================================================  

再構成した3次元形状データを破棄、カメラ姿勢を初期化してKinect Fusionをリセットする。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
HRESULT ResetReconstruction(  
         const Matrix4 *pInitialWorldToCameraTransform,  
         const Matrix4 *pWorldToVolumeTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pInitialWorldToCameraTransform*    
Type: Matrix4  
初期化するカメラ姿勢。  
デフォルトのカメラ姿勢を使用するには単位行列を指定します。  

*pWorldToVolumeTransform*    
Type: Matrix4  
初期化するワールド座標系から3次元形状データのローカル座標系への変換行列。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

独自のワールド座標系から3次元形状データのローカル座標系への変換行列を作成するには、[GetCurrentWorldToVolumeTransform](GetCurrentWorldToVolumeTra.md)で取得した変換行列に対し回転・平行移動などの行列を掛けることで作成します。<br/>ただし、スキューのような変換はサポートされていません。  

ワールド座標系から3次元形状データのローカル座標系への変換行列を保ちながらリセットするには[GetCurrentWorldToVolumeTransform](GetCurrentWorldToVolumeTra.md)で取得した変換行列をResetReconstructionに指定します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ResetReconstruction Method
RLTitle : INuiFusionColorReconstruction::ResetReconstruction Method
KeywordK : ResetReconstruction method
KeywordK : INuiFusionColorReconstruction::ResetReconstruction method
KeywordF : INuiFusionColorReconstruction::ResetReconstruction
KeywordF : ResetReconstruction
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ResetReconstruction(Matrix4,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ResetReconstruction(Matrix4,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ResetReconstruction(Matrix4,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::ResetReconstruction
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
