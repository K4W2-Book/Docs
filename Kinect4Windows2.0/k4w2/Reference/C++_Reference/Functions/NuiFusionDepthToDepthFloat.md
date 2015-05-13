NuiFusionDepthToDepthFloatFrame  
===============================  

DepthデータをNUI\_FUSION\_IMAGE\_FRAMEに変換する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionDepthToDepthFloatFrame(  
         const UINT16 *pDepthImageData,  
         UINT depthImageDataWidth,  
         UINT depthImageDataHeight,  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         FLOAT minDepthClip,  
         FLOAT maxDepthClip,  
         BOOL mirrorDepth  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthImageData*    
Type: UINT16  
[in] Depthデータ。  

*depthImageDataWidth*    
Type: UINT  
[in] 画像の幅(pixel)。  

*depthImageDataHeight*    
Type: UINT  
[in] 画像の高さ(pixel)。  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in] NUI\_FUSION\_IMAGE\_FRAMEのアドレス。  

*minDepthClip*    
Type: FLOAT  
[in] Depthデータの最小値の閾値。  
この値以下のDepthデータは変換時に0に設定される。  

*maxDepthClip*    
Type: FLOAT  
[in] Depthデータの最大値の閾値。  
この値以上のDepthデータは変換時に1000に設定される。  

*mirrorDepth*    
Type: BOOL  
[in] Depthデータを反転する場合はtrue、反転しない場合はfalseをしてする。  

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
TOCTitle : NuiFusionDepthToDepthFloatFrame
RLTitle : NuiFusionDepthToDepthFloatFrame
KeywordK : NuiFusionDepthToDepthFloatFrame
KeywordF : NuiFusionDepthToDepthFloatFrame
KeywordF : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthToDepthFloatFrame(UINT16,UINT,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
KeywordA : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthToDepthFloatFrame(UINT16,UINT,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
AssetID : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthToDepthFloatFrame(UINT16,UINT,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionDepthToDepthFloatFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
