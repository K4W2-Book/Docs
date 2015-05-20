INuiFusionReconstruction::AlignPointClouds Method  
=================================================  

重複する部分のある2つのPoint Cloudを位置合わせして相対的なカメラ姿勢を計算する。 <span id="syntaxSection"></span>

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
HRESULT AlignPointClouds(  
         const NUI_FUSION_IMAGE_FRAME *pReferencePointCloudFrame,  
         const NUI_FUSION_IMAGE_FRAME *pObservedPointCloudFrame,  
         USHORT maxAlignIterationCount,  
         const NUI_FUSION_IMAGE_FRAME *pDeltaFromReferenceFrame,  
         FLOAT *pAlignmentEnergy,  
         Matrix4 *pReferenceToObservedTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pReferencePointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
位置合わせの基準となるPoint Cloud。  
位置合わせするPoint Cloudと同じサイズとカメラパラメーターである必要がある。  

*pObservedPointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
位置合わせするPoint Cloud。  
位置合わせの基準となるPoint Cloudと同じサイズとカメラパラメーターである必要がある。  

*maxAlignIterationCount*    
Type: USHORT  
位置合わせのための反復アルゴリズムの最大反復回数。[1,  
反復回数が少ない場合、高速に動作するが正しい位置に収束しない可能性があります。  

*pDeltaFromReferenceFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
位置合わせのためのアルゴリズムで用いられる補助データ。  
このデータを必要としない場合、nullptrを指定します。  

*pAlignmentEnergy*    
Type: FLOAT  
位置合わせのためのアルゴリズムで用いられる閾値。[0.0f,1.0f]  

*pReferenceToObservedTransform*    
Type: Matrix4  
相対的なカメラ姿勢。  

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
TOCTitle : AlignPointClouds Method
RLTitle : INuiFusionReconstruction::AlignPointClouds Method
KeywordK : AlignPointClouds method
KeywordK : INuiFusionReconstruction::AlignPointClouds method
KeywordF : INuiFusionReconstruction::AlignPointClouds
KeywordF : AlignPointClouds
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.AlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.AlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.AlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,FLOAT,Matrix4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::AlignPointClouds
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
