INuiFusionColorReconstruction::GetCurrentWorldToVolumeTransform Method  
======================================================================  

現在のワールド座標系から再構成した3次元形状データのローカル座標系への変換行列を取得する。 <span id="syntaxSection"></span>

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
HRESULT GetCurrentWorldToVolumeTransform(  
         Matrix4 *pWorldToVolumeTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pWorldToVolumeTransform*    
Type: Matrix4  
現在のワールド座標系から再構成した3次元形状データのローカル座標系への変換行列。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

右手座標系で立方体の前面左上(0, 0, 0)が原点です。X軸は原点より右側にいくにつれ増加、Y軸は原点より下側にいくにつれ増加、Z軸は原点から手前にいくにつれ増加します。  

デフォルトの変換行列は、再構成された3次元形状データの前面中心をワールド座標系の原点とするX軸とY軸の平行移動と再構成パラメーターの[VoxelsPerMeter](../../../Structures/NUI_FUSION_RECONSTRUCTION.md)によるスケーリングの組み合わせです。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetCurrentWorldToVolumeTransform Method
RLTitle : INuiFusionColorReconstruction::GetCurrentWorldToVolumeTransform Method
KeywordK : GetCurrentWorldToVolumeTransform method
KeywordK : INuiFusionColorReconstruction::GetCurrentWorldToVolumeTransform method
KeywordF : INuiFusionColorReconstruction::GetCurrentWorldToVolumeTransform
KeywordF : GetCurrentWorldToVolumeTransform
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.GetCurrentWorldToVolumeTransform(Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.GetCurrentWorldToVolumeTransform(Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.GetCurrentWorldToVolumeTransform(Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::GetCurrentWorldToVolumeTransform
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
