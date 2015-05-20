INuiFusionColorReconstruction::ProcessFrame Method  
==================================================  

DpehtとColorをKinect Fusionの各処理をまとめたパイプラインに流し込んで計算する。 <span id="syntaxSection"></span>

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
HRESULT ProcessFrame(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const NUI_FUSION_IMAGE_FRAME *pColorFrame,  
         USHORT maxAlignIterationCount,  
         USHORT maxIntegrationWeight,  
         FLOAT maxColorIntegrationAngle,  
         FLOAT *pAlignmentEnergy,  
         const Matrix4 *pWorldToCameraTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
入力するDepth画像フレーム。  
この画像フレームの最大解像度は640×480です。  

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
入力するColor画像フレーム。  
この画像フレームの最大解像度は640×480です。  

*maxAlignIterationCount*    
Type: USHORT  
位置合わせのための反復アルゴリズムの最大反復回数。[1,  
反復回数が少ない場合、高速に動作するが正しい位置に収束しない可能性があります。  

*maxIntegrationWeight*    
Type: USHORT  
Depthを再構成した3次元形状データに統合する時間方向の平滑化ウェイト。[1,  
指定する値が小さいほどノイズが多くなるが、動いているオブジェクトが素早く取り除かれるため、動的な環境に適している。  
指定する値が大きいほどオブジェクトがゆっくりと統合されるが、ノイズの少ない詳細な形状データを得ることができるため、静的な環境に適している。  

*maxColorIntegrationAngle*    
Type: FLOAT  
Colorを再構成した3次元形状データに統合する法線角度の閾値。[0.0f,90.0f]  
センサーとサーフェスがなす法線の角度が垂直または閾値以内の場合、色データを統合する。  
この値は、色データを統合する法線角度の半分の値を指定する。  
90.0f(180°)を指定すると、センサーとサーフェスがどのような角度でも常に色データを統合します。  
0.0f(0°)を指定すると、センサーとサーフェスが垂直の場合のみ色データを統合します。  
この値を指定すると統合処理に負荷がかかります。  
しかし、この値を指定しないと任意の角度から色データを統合するため、薄いオブジェクトの場合に両面に同じ色を設定する可能性があります。  

*pAlignmentEnergy*    
Type: FLOAT  
位置合わせのためのアルゴリズムで用いられる閾値。[0.0f,1.0f]  

*pWorldToCameraTransform*    
Type: Matrix4  
現在の推測されたカメラ姿勢。  
通常、[GetCurrentWorldToCameraTransform](GetCurrentWorldToCameraTra.md)で取得した最新のカメラ姿勢を指定する。  

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
TOCTitle : ProcessFrame Method
RLTitle : INuiFusionColorReconstruction::ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : INuiFusionColorReconstruction::ProcessFrame method
KeywordF : INuiFusionColorReconstruction::ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,FLOAT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,FLOAT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,FLOAT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::ProcessFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
