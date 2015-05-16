INuiFusionColorReconstruction::DepthToDepthFloatFrame Method  
============================================================  

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
<td align="left"><pre><code>public:  
HRESULT DepthToDepthFloatFrame(  
         const UINT16 *pDepthImageData,  
         UINT countDepthImageDataBytes,  
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
Depthデータ。  

*countDepthImageDataBytes*    
Type: UINT  
Depthデータのサイズ。(Byte)  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
NUI\_FUSION\_IMAGE\_FRAMEのアドレス。  

*minDepthClip*    
Type: FLOAT  
Depthデータの最小値の閾値。  
この値以下のDepthデータは変換時に0に設定される。  

*maxDepthClip*    
Type: FLOAT  
Depthデータの最大値の閾値。  
この値以上のDepthデータは変換時に1000に設定される。  

*mirrorDepth*    
Type: BOOL  
Depthデータを反転する場合は**true**、反転しない場合は**false**を指定する。  

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
TOCTitle : DepthToDepthFloatFrame Method
RLTitle : INuiFusionColorReconstruction::DepthToDepthFloatFrame Method
KeywordK : DepthToDepthFloatFrame method
KeywordK : INuiFusionColorReconstruction::DepthToDepthFloatFrame method
KeywordF : INuiFusionColorReconstruction::DepthToDepthFloatFrame
KeywordF : DepthToDepthFloatFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.DepthToDepthFloatFrame(UINT16,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.DepthToDepthFloatFrame(UINT16,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.DepthToDepthFloatFrame(UINT16,UINT,NUI_FUSION_IMAGE_FRAME,FLOAT,FLOAT,BOOL)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::DepthToDepthFloatFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
