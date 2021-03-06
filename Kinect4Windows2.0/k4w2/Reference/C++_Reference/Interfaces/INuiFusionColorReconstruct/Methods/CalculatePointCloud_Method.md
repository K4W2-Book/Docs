INuiFusionColorReconstruction::CalculatePointCloud Method  
=========================================================  

再構成した3次元形状データをレイキャストすることでPoint Cloudを計算する。 <span id="syntaxSection"></span>

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
HRESULT CalculatePointCloud(  
         const NUI_FUSION_IMAGE_FRAME *pPointCloudFrame,  
         const NUI_FUSION_IMAGE_FRAME *pColorFrame,  
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

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
レンダリングされたSurface画像。  

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

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculatePointCloud Method
RLTitle : INuiFusionColorReconstruction::CalculatePointCloud Method
KeywordK : CalculatePointCloud method
KeywordK : INuiFusionColorReconstruction::CalculatePointCloud method
KeywordF : INuiFusionColorReconstruction::CalculatePointCloud
KeywordF : CalculatePointCloud
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.CalculatePointCloud(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::CalculatePointCloud
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
