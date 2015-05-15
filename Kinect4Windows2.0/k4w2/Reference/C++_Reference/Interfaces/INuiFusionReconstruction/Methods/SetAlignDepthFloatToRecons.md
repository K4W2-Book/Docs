INuiFusionReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame Method  
=================================================================================  

[AlignDepthFloatToReconstruction](AlignDepthFloatToReconstru.md)でカメラ姿勢を計算するときに内部で用いられる基準となるDepthを設定する。 <span id="syntaxSection"></span>

| ![](../../../../../../resources/note.gif)Note                                                         |
|-------------------------------------------------------------------------------------------------------|
| Kinect Fusionのデフォルトのトラッキング処理を利用していない場合のみ、このAPIを呼び出す必要がある。 |

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
HRESULT SetAlignDepthFloatToReconstructionReferenceFrame(  
         const NUI_FUSION_IMAGE_FRAME *pReferenceDepthFloatFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EL"></span>
#### Parameters  

*pReferenceDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
基準となるDepth画像フレーム、またはレイキャストされたDepth画像フレーム。  

<span id="ID4EU"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SetAlignDepthFloatToReconstructionReferenceFrame Method
RLTitle : INuiFusionReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame Method
KeywordK : SetAlignDepthFloatToReconstructionReferenceFrame method
KeywordK : INuiFusionReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame method
KeywordF : INuiFusionReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame
KeywordF : SetAlignDepthFloatToReconstructionReferenceFrame
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(NUI_FUSION_IMAGE_FRAME)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(NUI_FUSION_IMAGE_FRAME)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.SetAlignDepthFloatToReconstructionReferenceFrame(NUI_FUSION_IMAGE_FRAME)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
