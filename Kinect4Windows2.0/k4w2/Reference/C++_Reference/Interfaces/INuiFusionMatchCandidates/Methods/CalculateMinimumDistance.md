INuiFusionMatchCandidates::CalculateMinimumDistance Method  
==========================================================  

最も類似するカメラ姿勢の類似度を取得する。 <span id="syntaxSection"></span>

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
HRESULT CalculateMinimumDistance(  
         FLOAT *pMinimumDistance  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pMinimumDistance*    
Type: FLOAT  
現在のフレームと最も類似するフレームのカメラ姿勢の類似度。  

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
TOCTitle : CalculateMinimumDistance Method
RLTitle : INuiFusionMatchCandidates::CalculateMinimumDistance Method
KeywordK : CalculateMinimumDistance method
KeywordK : INuiFusionMatchCandidates::CalculateMinimumDistance method
KeywordF : INuiFusionMatchCandidates::CalculateMinimumDistance
KeywordF : CalculateMinimumDistance
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.CalculateMinimumDistance(FLOAT)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.CalculateMinimumDistance(FLOAT)
AssetID : M:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates.CalculateMinimumDistance(FLOAT)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates::CalculateMinimumDistance
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
