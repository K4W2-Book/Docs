IVisualGestureBuilderFrameSource Interface  
==========================================  

Visual Gesture Builder(VGB)フレームのSource。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IVisualGestureBuilderFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IVisualGestureBuilderFrameSource**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/AddGesture_Method.md">AddGesture</a></td>
<td align="left">識別器を追加する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/AddGestures_Method.md">AddGestures</a></td>
<td align="left">複数の識別器を追加する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/get_GestureCount_Method.md">get_GestureCount</a></td>
<td align="left">含まれている識別器の数を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/get_Gestures_Method.md">get_Gestures</a></td>
<td align="left">含まれている識別器を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/get_HorizontalMirror_Method.md">get_HorizontalMirror</a></td>
<td align="left">水平方向ミラーリングの設定状況を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">VGBフレームのSourceの動作状況を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/get_IsTrackingIdValid_Method.md">get_IsTrackingIdValid</a></td>
<td align="left">トラッキングIDが有効であるかを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">VGBフレームのSourceを取得したセンサーを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/get_TrackingId_Method.md">get_TrackingId</a></td>
<td align="left">トラッキングIDを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/GetIsEnabled_Method.md">GetIsEnabled</a></td>
<td align="left">指定した識別器の設定状況を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/GetTrackingIdLostEventData.md">GetTrackingIdLostEventData</a></td>
<td align="left">トラッキングIDがロストしたとき、イベントデータを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">VGBフレームのReaderを開く。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/put_HorizontalMirror_Method.md">put_HorizontalMirror</a></td>
<td align="left">水平方向ミラーリングの有効・無効を設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/put_TrackingId_Method.md">put_TrackingId</a></td>
<td align="left">トラッキングIDを設定する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/RemoveGesture_Method.md">RemoveGesture</a></td>
<td align="left">含まれている識別器を削除する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/SetIsEnabled_Method.md">SetIsEnabled</a></td>
<td align="left">指定した識別器の有効・無効を設定する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/SubscribeTrackingIdLost.md">SubscribeTrackingIdLost</a></td>
<td align="left">トラッキングIDがロストしたとき発効するイベントハンドルを登録する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IVisualGestureBuilderFrameSource/Methods/UnsubscribeTrackingIdLost.md">UnsubscribeTrackingIdLost</a></td>
<td align="left">トラッキングIDがロストしたとき発効するイベントハンドルを解除する。</td>
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
TOCTitle : IVisualGestureBuilderFrameSource Interface
RLTitle : IVisualGestureBuilderFrameSource Interface
KeywordK : IVisualGestureBuilderFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IVisualGestureBuilderFrameSource
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource
KeywordA : T:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource
AssetID : T:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
