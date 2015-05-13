NuiFusionCreateImageFrame  
=========================  

[NUI_FUSION_IMAGE_FRAME](Structures/NUI_FUSION_IMAGE_FRAME.md)を作成する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionCreateImageFrame(  
         NUI_FUSION_IMAGE_TYPE frameType,  
         UINT width,  
         UINT height,  
         const NUI_FUSION_CAMERA_PARAMETERS *pCameraParameters,  
         NUI_FUSION_IMAGE_FRAME **ppImageFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*frameType*    
Type: NUI\_FUSION\_IMAGE\_TYPE  
[in] 画像の種類。  

*width*    
Type: UINT  
[in] 画像の幅(pixel)。  

*height*    
Type: UINT  
[in] 画像の高さ(pixel)。  

*pCameraParameters*    
Type: NUI\_FUSION\_CAMERA\_PARAMETERS  
[in, optional] カメラの内部パラメーター。  

*ppImageFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[out] NUI\_FUSION\_IMAGE\_FRAMEのポインタのアドレス。  

<span id="ID4EN"></span>
#### Return value  

Type: HRESULT FUSIONAPI  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusiondepthprocessor.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NuiFusionCreateImageFrame
RLTitle : NuiFusionCreateImageFrame
KeywordK : NuiFusionCreateImageFrame
KeywordF : NuiFusionCreateImageFrame
KeywordF : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionCreateImageFrame(NUI_FUSION_IMAGE_TYPE,UINT,UINT,NUI_FUSION_CAMERA_PARAMETERS,NUI_FUSION_IMAGE_FRAME@)
KeywordA : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionCreateImageFrame(NUI_FUSION_IMAGE_TYPE,UINT,UINT,NUI_FUSION_CAMERA_PARAMETERS,NUI_FUSION_IMAGE_FRAME@)
AssetID : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionCreateImageFrame(NUI_FUSION_IMAGE_TYPE,UINT,UINT,NUI_FUSION_CAMERA_PARAMETERS,NUI_FUSION_IMAGE_FRAME@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionCreateImageFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
