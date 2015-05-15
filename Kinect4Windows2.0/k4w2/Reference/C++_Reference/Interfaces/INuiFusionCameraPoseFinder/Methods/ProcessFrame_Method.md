INuiFusionCameraPoseFinder::ProcessFrame Method  
===============================================  

データベースに含まれるフレーム・カメラ姿勢と十分に異なる場合、新たにデータベースに登録する。 <span id="syntaxSection"></span>

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
         const Matrix4 *pWorldToCameraTransform,  
         FLOAT minimumDistanceThreshold,  
         BOOL *pAddedPose,  
         BOOL *pHistoryTrimmed  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
Depth画像フレーム。  
このフレームは有効なカメラパラメーターを持っており、80×60以上のサイズである必要がある。  

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
Color画像フレーム。  
このフレームは有効なカメラパラメーターを持っており、80×60以上のサイズである必要がある。  
  

*pWorldToCameraTransform*    
Type: Matrix4  
入力フレームのカメラ姿勢。  
通常、AlignPointClouds()またはAlignDepthFloatToReconstruction()の出力結果を指定する。

*minimumDistanceThreshold*    
Type: FLOAT  
データベースに含まれるカメラ姿勢と十分に異なると判定される閾値。[0.0f-1.0f]  
この閾値を超えるフレーム・カメラ姿勢は新たにデータベースに登録される。  
常に入力されたフレーム・カメラ姿勢をデータベースに登録したい場合は、0.0fを指定する。  
ただし、多くの重複したカメラ姿勢がデータベースに登録されるため、データベースが肥大化しパフォーマンスが低下する恐れがある。

*pAddedPose*    
Type: BOOL  
フレーム・カメラ姿勢が新たにデータベースに登録された場合は**true**、破棄された場合は**false**。  

*pHistoryTrimmed*    
Type: BOOL  
パフォーマンスを確保するためにデータベースから古いフレーム・カメラ姿勢を削除した場合は**true**、削除していない場合は**false**。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncameraposefinder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ProcessFrame Method
RLTitle : INuiFusionCameraPoseFinder::ProcessFrame Method
KeywordK : ProcessFrame method
KeywordK : INuiFusionCameraPoseFinder::ProcessFrame method
KeywordF : INuiFusionCameraPoseFinder::ProcessFrame
KeywordF : ProcessFrame
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4,FLOAT,BOOL,BOOL)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4,FLOAT,BOOL,BOOL)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.ProcessFrame(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,Matrix4,FLOAT,BOOL,BOOL)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder::ProcessFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
