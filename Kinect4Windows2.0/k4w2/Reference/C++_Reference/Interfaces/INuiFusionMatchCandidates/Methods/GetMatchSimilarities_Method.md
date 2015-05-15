INuiFusionMatchCandidates::GetMatchSimilarities Method  
======================================================  

カメラ姿勢の候補の類似度を取得する。 <span id="syntaxSection"></span>

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
HRESULT GetMatchSimilarities(  
         const FLOAT **pSimilarityMeasurements  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pSimilarityMeasurements*    
Type: FLOAT  
現在のフレームと類似するフレームの類似度の配列のアドレス。  

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
TOCTitle : GetMatchSimilarities Method
RLTitle : INuiFusionMatchCandidates::GetMatchSimilarities Method
KeywordK : GetMatchSimilarities method
KeywordK : INuiFusionMatchCandidates::GetMatchSimilarities method
KeywordF : INuiFusionMatchCandidates::GetMatchSimilarities
KeywordF : GetMatchSimilarities
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.GetMatchSimilarities(FLOAT)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.GetMatchSimilarities(FLOAT)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.GetMatchSimilarities(FLOAT)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates::GetMatchSimilarities
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
