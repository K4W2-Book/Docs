INuiFusionMatchCandidates Interface  
===================================  

[INuiFusionCameraPoseFinder::FindCameraPose](INuiFusionCameraPoseFinder/Methods/FindCameraPose_Method.md)で取得した現在のフレームと類似するフレームのカメラ姿勢の候補。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface INuiFusionMatchCandidates : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**INuiFusionMatchCandidates**は以下のメンバー関数を持ちます。  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/CalculateMinimumDistance.md">CalculateMinimumDistance</a></td>
<td align="left">最も類似するカメラ姿勢の類似度を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/GetMatchPoses_Method.md">GetMatchPoses</a></td>
<td align="left">カメラ姿勢の候補を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/GetMatchSimilarities_Method.md">GetMatchSimilarities</a></td>
<td align="left">カメラ姿勢の候補の類似度を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/MatchPoseCount_Method.md">MatchPoseCount</a></td>
<td align="left">カメラ姿勢の候補の数を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionMatchCandidates/Methods/MatchSimilarityCount_Method.md">MatchSimilarityCount</a></td>
<td align="left">カメラ姿勢の候補の類似度の数を取得する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncameraposefinder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : INuiFusionMatchCandidates Interface
RLTitle : INuiFusionMatchCandidates Interface
KeywordK : INuiFusionMatchCandidates interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : INuiFusionMatchCandidates
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates
KeywordA : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates
AssetID : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionMatchCandidates
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
