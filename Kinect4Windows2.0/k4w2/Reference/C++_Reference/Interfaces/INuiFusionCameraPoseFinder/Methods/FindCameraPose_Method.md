INuiFusionCameraPoseFinder::FindCameraPose Method  
=================================================  

現在のフレームと最も類似するフレームのカメラポーズをデータベースから取得する。 <span id="syntaxSection"></span>

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
HRESULT FindCameraPose(  
         const NUI_FUSION_IMAGE_FRAME *pDepthFloatFrame,  
         const NUI_FUSION_IMAGE_FRAME *pColorFrame,  
         INuiFusionMatchCandidates **ppMatchCandidates  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pDepthFloatFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
Depth画像フレーム。  
このフレームは有効なカメラパラメーターを持っている必要がある。  

*pColorFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
Color画像フレーム。  
このフレームは有効なカメラパラメーターを持っている必要がある。  

*ppMatchCandidates*    
Type: INuiFusionMatchCandidates  
INuiFusionMatchCandidatesのポインタのアドレス。  
このカメラ姿勢・類似度は似ている順にソートされている。  

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
TOCTitle : FindCameraPose Method
RLTitle : INuiFusionCameraPoseFinder::FindCameraPose Method
KeywordK : FindCameraPose method
KeywordK : INuiFusionCameraPoseFinder::FindCameraPose method
KeywordF : INuiFusionCameraPoseFinder::FindCameraPose
KeywordF : FindCameraPose
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.FindCameraPose(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,INuiFusionMatchCandidates)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.FindCameraPose(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,INuiFusionMatchCandidates)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder.FindCameraPose(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,INuiFusionMatchCandidates)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder::FindCameraPose
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
