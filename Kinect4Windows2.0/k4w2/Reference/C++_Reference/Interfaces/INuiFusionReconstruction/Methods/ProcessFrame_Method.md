INuiFusionReconstruction::ProcessFrame Method  
=============================================  

DpehtをKinect Fusionの各処理をまとめたパイプラインに流し込んで計算する。 <span id="syntaxSection"></span>

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
         USHORT maxAlignIterationCount,  
         USHORT maxIntegrationWeight,  
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

*maxAlignIterationCount*    
Type: USHORT  
位置合わせのための反復アルゴリズムの最大反復回数。[1-]  
反復回数が少ない場合、高速に動作するが正しい位置に収束しない可能性があります。  

*maxIntegrationWeight*    
Type: USHORT  
Depthを再構成した3次元形状データに統合する時間方向の平滑化ウェイト。[1-]  
指定する値が小さいほどノイズが多くなるが、動いているオブジェクトが素早く取り除かれるため、動的な環境に適している。  
指定する値が大きいほどオブジェクトがゆっくりと統合されるが、ノイズの少ない詳細な形状データを得ることができるため、静的な環境に適している。  

*pAlignmentEnergy*    
Type: FLOAT  
位置合わせのためのアルゴリズムで用いられる閾値。[0.0f-1.0f]  

*pWorldToCameraTransform*    
Type: Matrix4  
現在の推測されたカメラ姿勢。  
通常、[GetCurrentWorldToCameraTransform](GetCurrentWorldToCameraTra.md)で取得した最新のカメラ姿勢を指定する。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

This method is equivalent to calling the [AlignDepthFloatToReconstruction](AlignDepthFloatToReconstru.md) and [IntegrateFrame](IntegrateFrame_Method.md) methods on the specified depth frame. You can call these low-level methods individually to have more control over the operation, but calling ProcessFrame will complete faster due to the integrated nature of the calls.  
| ![](../../../../../../resources/note.gif)Note                                                                                                                      |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| If a tracking error occurs during the AlignDepthFloatToReconstruction call, no depth data integration will be performed and the camera pose will remain unchanged. |

If you need a visible output image of the reconstruction, call the [CalculatePointCloud](CalculatePointCloud_Method.md) method and then call the [NuiFusionShadePointCloud](../../../Functions/NuiFusionShadePointCloud.md) function.  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessFrame Method
RLTitle : INuiFusionReconstruction::ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : INuiFusionReconstruction::ProcessFrame method
KeywordF : INuiFusionReconstruction::ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ProcessFrame(NUI_FUSION_IMAGE_FRAME,USHORT,USHORT,FLOAT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::ProcessFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
