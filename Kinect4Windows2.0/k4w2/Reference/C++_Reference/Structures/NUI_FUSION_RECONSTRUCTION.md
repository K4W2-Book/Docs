NUI\_FUSION\_RECONSTRUCTION\_PARAMETERS Structure  
=================================================  

Kinect Fusionの3次元形状の再構成パラメーター。
このパラメーターにより、3次元形状を再構成できる最大範囲が決まります。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _NUI_FUSION_RECONSTRUCTION_PARAMETERS {  
    FLOAT voxelsPerMeter;  
    UINT voxelCountX;  
    UINT voxelCountY;  
    UINT voxelCountZ;  
} NUI_FUSION_RECONSTRUCTION_PARAMETERS;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**voxelsPerMeter**    
メートルあたりのボクセルの数。  

**voxelCountX**    
X軸方向の再構成に使うボクセル数。  

**voxelCountY**    
Y軸方向の再構成に使うボクセル数。  

**voxelCountZ**    
Z軸方向の再構成に使うボクセル数。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NUI_FUSION_RECONSTRUCTION_PARAMETERS Structure
RLTitle : NUI_FUSION_RECONSTRUCTION_PARAMETERS Structure
KeywordK : NUI_FUSION_RECONSTRUCTION_PARAMETERS structure
KeywordF : NUI_FUSION_RECONSTRUCTION_PARAMETERS
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_RECONSTRUCTION_PARAMETERS
KeywordA : T:Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_RECONSTRUCTION_PARAMETERS
AssetID : T:Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_RECONSTRUCTION_PARAMETERS
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_RECONSTRUCTION_PARAMETERS
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
