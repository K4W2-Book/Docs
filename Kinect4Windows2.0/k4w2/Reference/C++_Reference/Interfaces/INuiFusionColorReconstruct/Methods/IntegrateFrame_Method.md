INuiFusionColorReconstruction::IntegrateFrame Method  
====================================================  

指定したカメラ姿勢でDepthとColorを再構成した3次元形状データに統合する。 <span id="syntaxSection"></span>

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
         const NUI_FUSION_IMAGE_FRAME *pColorFrame,  
         USHORT maxIntegrationWeight,  
         FLOAT maxColorIntegrationAngle,  
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

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
再構成した3次元形状データに統合するColor。  

*maxIntegrationWeight*    
Type: USHORT  
Depthを再構成した3次元形状データに統合する時間方向の平滑化ウェイト。[1-]  
指定する値が小さいほどノイズが多くなるが、動いているオブジェクトが素早く取り除かれるため、動的な環境に適している。  
指定する値が大きいほどオブジェクトがゆっくりと統合されるが、ノイズの少ない詳細な形状データを得ることができるため、静的な環境に適している。  

*maxColorIntegrationAngle*    
Type: FLOAT  
Colorを再構成した3次元形状データに統合する法線角度の閾値。[0.0f-90.0f]  
センサーとサーフェスがなす法線の角度が垂直または閾値以内の場合、色データを統合する。  
この値は、色データを統合する法線角度の半分の値を指定する。  
90.0f(180°)を指定すると、センサーとサーフェスがどのような角度でも常に色データを統合します。  
0.0f(0°)を指定すると、センサーとサーフェスが垂直の場合のみ色データを統合します。  
この値を指定すると統合処理に負荷がかかります。  
しかし、この値を指定しないと任意の角度から色データを統合するため、薄いオブジェクトの場合に両面に同じ色を設定する可能性があります。  

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

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IntegrateFrame Method
RLTitle : INuiFusionColorReconstruction::IntegrateFrame Method
KeywordK : IntegrateFrame method
KeywordK : INuiFusionColorReconstruction::IntegrateFrame method
KeywordF : INuiFusionColorReconstruction::IntegrateFrame
KeywordF : IntegrateFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,FLOAT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,FLOAT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.IntegrateFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,FLOAT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::IntegrateFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
