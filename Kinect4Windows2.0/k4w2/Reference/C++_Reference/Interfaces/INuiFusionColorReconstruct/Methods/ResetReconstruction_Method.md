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

To create your own world-to-volume transformation, call the [GetCurrentWorldToVolumeTransform](GetCurrentWorldToVolumeTra.md) method, and then either modify the returned matrix directly or multiply with your own similarity matrix to alter the volume translation or rotation with respect to the world coordinate system. Other transforms, such as skew, are not supported.  

To reset the volume while keeping the same world-to-volume transform, call the [GetCurrentWorldToVolumeTransform](GetCurrentWorldToVolumeTra.md) method, and then pass the returned matrix to the pWorldToVolumeTransform parameter of the ResetReconstruction method.  

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
