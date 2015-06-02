IBody Interface  
===============  

Body。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBody : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBody**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IBody_Interface/Methods/get_ClippedEdges_Method.md">get_ClippedEdges</a></td>
<td align="left">人物がカメラの視野に収まっていない端を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_Engaged_Method.md">get_Engaged</a></td>
<td align="left">付随情報の検出結果を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_HandLeftConfidence.md">get_HandLeftConfidence</a></td>
<td align="left">左手のトラッキングの信頼度を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_HandLeftState_Method.md">get_HandLeftState</a></td>
<td align="left">左手のハンドステータスを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_HandRightConfidence.md">get_HandRightConfidence</a></td>
<td align="left">右手のトラッキングの信頼度を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_HandRightState_Method.md">get_HandRightState</a></td>
<td align="left">右手のハンドステータスを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_IsRestricted_Method.md">get_IsRestricted</a></td>
<td align="left">身体の動きが制限されているかを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_IsTracked_Method.md">get_IsTracked</a></td>
<td align="left">身体のトラッキングステータスを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_Lean_Method.md">get_Lean</a></td>
<td align="left">身体の傾きを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/get_LeanTrackingState_Method.md">get_LeanTrackingState</a></td>
<td align="left">身体の傾きのトラッキングステータスを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/get_TrackingId_Method.md">get_TrackingId</a></td>
<td align="left">トラッキングIDを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/GetActivityDetectionResults.md">GetActivityDetectionResults</a></td>
<td align="left">Activityの検出結果を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/GetAppearanceDetectionResu.md">GetAppearanceDetectionResults</a></td>
<td align="left">Appearanceの検出結果を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/GetExpressionDetectionResu.md">GetExpressionDetectionResults</a></td>
<td align="left">Expressionの検出結果を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBody_Interface/Methods/GetJointOrientations_Method.md">GetJointOrientations</a></td>
<td align="left">Jointの向きを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBody_Interface/Methods/GetJoints_Method.md">GetJoints</a></td>
<td align="left">Jointを取得する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IBody Interface
RLTitle : IBody Interface
KeywordK : IBody interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBody
KeywordF : Microsoft.Kinect.kinect.IBody
KeywordA : T:Microsoft.Kinect.kinect.IBody
AssetID : T:Microsoft.Kinect.kinect.IBody
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
