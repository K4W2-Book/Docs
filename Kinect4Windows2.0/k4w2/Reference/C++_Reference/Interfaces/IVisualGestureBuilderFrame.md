IVisualGestureBuilderFrame Interface  
==========================================  

Visaul Gesture Builder(VGB)フレーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IVisualGestureBuilderFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IVisualGestureBuilderFrame**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IVisualGestureBuilderFrame/Methods/get_ContinuousGestureResult.md">get_ContinuousGestureResult</a></td>
<td align="left">Continuous(連続的)ジェスチャーの結果を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrame/Methods/get_DiscreteGestureResult.md">get_DiscreteGestureResult</a></td>
<td align="left">Discrete(離散的)ジェスチャーの結果を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrame/Methods/get_TrackingId_Method.md">get_TrackingId</a></td>
<td align="left">トラッキングIDを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrame/Methods/get_IsTrackingIdValid_Method.md">get_IsTrackingIdValid</a></td>
<td align="left">トラッキングIDが有効であるかを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrame/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">VGBフレームを取得した時間(相対時間)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrame/Methods/get_FrameSource_Method.md">get_VisualGestureBuilderFrameSource</a></td>
<td align="left">VGBフレームのSourceを取得する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IVisualGestureBuilderFrame Interface
RLTitle : IVisualGestureBuilderFrame Interface
KeywordK : IVisualGestureBuilderFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IVisualGestureBuilderFrame
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame
KeywordA : T:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame
AssetID : T:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
