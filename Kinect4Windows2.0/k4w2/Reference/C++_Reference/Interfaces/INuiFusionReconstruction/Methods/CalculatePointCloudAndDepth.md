INuiFusionReconstruction::CalculatePointCloudAndDepth Method  
============================================================  

再構成した3次元形状データをレイキャストすることでPoint CloudとDepthを計算する。 <span id="syntaxSection"></span>

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
HRESULT CalculatePointCloudAndDepth(  
         const NUI_FUSION_IMAGE_FRAME *pPointCloudFrame,  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const Matrix4 *pWorldToCameraTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pPointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
計算されたPoint Cloud。
このPoint Cloudは、シェーディングして画像をレンダリングする[NuiFusionShadePointCloud](../../../Functions/NuiFusionShadePointCloud.md)の入力データ、または次のフレームの[AlignPointClouds](AlignPointClouds_Method.md)の補助データとして利用できる。  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
計算されたDepth。  
このDepthを[INuiFusionReconstruction::SetAlignDepthFloatToReconstructionReferenceFrame](SetAlignDepthFloatToRecons.md)で設定し[AlignDepthFloatToReconstruction](AlignDepthFloatToReconstru.md)の補助データとして使用することで、より広い範囲をトラッキングすることができる。  

*pWorldToCameraTransform*    
Type: Matrix4  
レイキャストするカメラ姿勢。  

<span id="ID4EP"></span>
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
TOCTitle : CalculatePointCloudAndDepth Method
RLTitle : INuiFusionReconstruction::CalculatePointCloudAndDepth Method
KeywordK : CalculatePointCloudAndDepth method
KeywordK : INuiFusionReconstruction::CalculatePointCloudAndDepth method
KeywordF : INuiFusionReconstruction::CalculatePointCloudAndDepth
KeywordF : CalculatePointCloudAndDepth
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.CalculatePointCloudAndDepth(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.CalculatePointCloudAndDepth(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.CalculatePointCloudAndDepth(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::CalculatePointCloudAndDepth
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
