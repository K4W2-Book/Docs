NuiFusionDepthFloatFrameToPointCloud  
====================================  

DepthデータをPoint Cloudデータに変換する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionDepthFloatFrameToPointCloud(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const NUI_FUSION_IMAGE_FRAME *pPointCloudFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in] 変換するDepthデータ。  

*pPointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in, out] 変換されたPoint Cloudデータ。  

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
TOCTitle : NuiFusionDepthFloatFrameToPointCloud
RLTitle : NuiFusionDepthFloatFrameToPointCloud
KeywordK : NuiFusionDepthFloatFrameToPointCloud
KeywordF : NuiFusionDepthFloatFrameToPointCloud
KeywordF : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthFloatFrameToPointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
KeywordA : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthFloatFrameToPointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
AssetID : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthFloatFrameToPointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthFloatFrameToPointCloud
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
