IVisualGestureBuilderFrameReader Interface  
==========================================  

Visaul Gesture Builder(VGB)フレームのReader。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IVisualGestureBuilderFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IVisualGestureBuilderFrameReader**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IVisualGestureBuilderFrameReader/Methods/CalculateAndAcquireLatestF.md">CalculateAndAcquireLatestFrame</a></td>
<td align="left">最新のVGBフレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameReader/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">VGBフレームのReaderの動作状態を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameReader/Methods/get_FrameSource_Method.md">get_VisualGestureBuilderFrameSource</a></td>
<td align="left">VGBフレームのSourceを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameReader/Methods/GetFrameArrivedEventData.md">GetFrameArrivedEventData</a></td>
<td align="left">新しいVGBフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameReader/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">VGBフレームのReaderの動作状態を設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameReader/Methods/SubscribeFrameArrived_Method.md">SubscribeFrameArrived</a></td>
<td align="left">VGBフレームの更新を待つイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameReader/Methods/UnsubscribeFrameArrived.md">UnsubscribeFrameArrived</a></td>
<td align="left">VGBフレームの更新を待つイベントハンドルを解除する。</td>
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
TOCTitle : IVisualGestureBuilderFrameReader Interface
RLTitle : IVisualGestureBuilderFrameReader Interface
KeywordK : IVisualGestureBuilderFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IVisualGestureBuilderFrameReader
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReader
KeywordA : T:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReader
AssetID : T:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
