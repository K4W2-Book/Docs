NUI\_FUSION\_IMAGE\_FRAME Structure  
===================================  

Kinect Fusionの入出力に用いる画像フレーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _NUI_FUSION_IMAGE_FRAME {  
    UINT width;  
    UINT height;  
    NUI_FUSION_IMAGE_TYPE imageType;  
    NUI_FUSION_CAMERA_PARAMETERS *pCameraParameters;  
    NUI_FUSION_BUFFER *pFrameBuffer;  
} NUI_FUSION_IMAGE_FRAME;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**width**    
画像の幅(pixel)。  

**height**    
画像の高さ(pixel)。  

**imageType**    
画像の種類。  

**pCameraParameters**    
カメラパラメーター。  

**pFrameBuffer**    
画像データのバッファ。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NUI_FUSION_IMAGE_FRAME Structure
RLTitle : NUI_FUSION_IMAGE_FRAME Structure
KeywordK : NUI_FUSION_IMAGE_FRAME structure
KeywordF : NUI_FUSION_IMAGE_FRAME
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_IMAGE_FRAME
KeywordA : T:Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_IMAGE_FRAME
AssetID : T:Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_IMAGE_FRAME
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.NUI_FUSION_IMAGE_FRAME
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
