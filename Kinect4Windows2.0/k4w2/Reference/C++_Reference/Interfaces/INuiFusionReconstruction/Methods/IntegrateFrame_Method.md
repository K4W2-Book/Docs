INuiFusionReconstruction::IntegrateFrame Method  
===============================================  

指定したカメラ姿勢でDepthを再構成した3次元形状データに統合する。 <span id="syntaxSection"></span>

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
HRESULT IntegrateFrame(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         USHORT maxIntegrationWeight,  
         const Matrix4 *pWorldToCameraTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
再構成した3次元形状データに統合するDepth。  

*maxIntegrationWeight*    
Type: USHORT  
Depthを再構成した3次元形状データに統合する時間方向の平滑化ウェイト。[1-]  
指定する値が小さいほどノイズが多くなるが、動いているオブジェクトが素早く取り除かれるため、動的な環境に適している。  
指定する値が大きいほどオブジェクトがゆっくりと統合されるが、ノイズの少ない詳細な形状データを得ることができるため、静的な環境に適している。  

*pWorldToCameraTransform*    
Type: Matrix4  
カメラ姿勢。  
通常、[AlignPointClouds](AlignPointClouds_Method.md)または[AlignDepthFloatToReconstruction](AlignDepthFloatToReconstru.md)で計算されたカメラ姿勢を使います。  

| ![](../../../../../../resources/note.gif)Note                |
|--------------------------------------------------------------|
| このAPIはこのカメラ姿勢を内部のカメラ姿勢に設定します。 |

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
TOCTitle : IntegrateFrame Method
RLTitle : INuiFusionReconstruction::IntegrateFrame Method
KeywordK : IntegrateFrame method
KeywordK : INuiFusionReconstruction::IntegrateFrame method
KeywordF : INuiFusionReconstruction::IntegrateFrame
KeywordF : IntegrateFrame
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,USHORT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,USHORT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,USHORT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::IntegrateFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
