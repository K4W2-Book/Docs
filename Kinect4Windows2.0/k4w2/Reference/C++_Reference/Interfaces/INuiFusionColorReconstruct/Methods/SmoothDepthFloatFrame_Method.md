INuiFusionColorReconstruction::SmoothDepthFloatFrame Method  
===========================================================  

エッジ保存型のフィルタを用いてDepthを平滑化する。 <span id="syntaxSection"></span>

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
HRESULT SmoothDepthFloatFrame(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const NUI_FUSION_IMAGE_FRAME *pSmoothDepthFloatFrame,  
         UINT kernelWidth,  
         FLOAT distanceThreshold  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
平滑化するDepth画像フレーム。  

*pSmoothDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
平滑化されたDepth画像フレーム。  

*kernelWidth*    
Type: UINT  
平滑化カーネルの大きさ。  

| *kernelWidth value* | Smoothing kernel block size |
|---------------------|-----------------------------|
| 1                   | 3×3                         |
| 2                   | 5×5                         |
| 3                   | 7×7                         |

*distanceThreshold*    
Type: FLOAT  
平滑化の閾値。[0.01f,0.1f]  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SmoothDepthFloatFrame Method
RLTitle : INuiFusionColorReconstruction::SmoothDepthFloatFrame Method
KeywordK : SmoothDepthFloatFrame method
KeywordK : INuiFusionColorReconstruction::SmoothDepthFloatFrame method
KeywordF : INuiFusionColorReconstruction::SmoothDepthFloatFrame
KeywordF : SmoothDepthFloatFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SmoothDepthFloatFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,UINT,FLOAT)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SmoothDepthFloatFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,UINT,FLOAT)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.SmoothDepthFloatFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,UINT,FLOAT)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::SmoothDepthFloatFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
