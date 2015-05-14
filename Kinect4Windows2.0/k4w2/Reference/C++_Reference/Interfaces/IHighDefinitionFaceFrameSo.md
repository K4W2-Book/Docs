IHighDefinitionFaceFrameSource Interface  
========================================  

HDFaceフレームのSource。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IHighDefinitionFaceFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IHighDefinitionFaceFrameSource**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/FeedAndCalculateFrameData.md">FeedAndCalculateFrameData</a></td>
<td align="left">HDFaceフレームを計算する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/get_FaceModel_Method.md">get_FaceModel</a></td>
<td align="left">顔モデルを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">HDFaceフレームのSourceの動作状況を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/get_IsOnline_Method.md">get_IsOnline</a></td>
<td align="left">HDFaceフレームのSourceのオンラインステータスを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/get_IsTrackingIdValid_Method.md">get_IsTrackingIdValid</a></td>
<td align="left">トラッキングIDが有効であるかを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">HDFaceフレームのSourceを取得したセンサーを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/get_TrackingId_Method.md">get_TrackingId</a></td>
<td align="left">トラッキングIDを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/get_TrackingQuality_Method.md">get_TrackingQuality</a></td>
<td align="left">顔のトラッキング品質を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/GetTrackingIdLostEventData.md">GetTrackingIdLostEventData</a></td>
<td align="left">トラッキングIDがロストしたとき、イベントデータを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/OpenModelBuilder_Method.md">OpenModelBuilder</a></td>
<td align="left">FaceModelBuilderを開く。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">HDFaceフレームのReaderを開く。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/put_FaceModel_Method.md">put_FaceModel</a></td>
<td align="left">顔モデルを設定する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/put_IsOnline_Method.md">put_IsOnline</a></td>
<td align="left">HDFaceフレームのSourceのオンラインステータスを設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/put_TrackingId_Method.md">put_TrackingId</a></td>
<td align="left">トラッキングIDを設定する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/put_TrackingQuality_Method.md">put_TrackingQuality</a></td>
<td align="left">顔のトラッキング品質を設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/SubscribeTrackingIdLost.md">SubscribeTrackingIdLost</a></td>
<td align="left">トラッキングIDがロストしたとき発効するイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameSo/Methods/UnsubscribeTrackingIdLost.md">UnsubscribeTrackingIdLost</a></td>
<td align="left">トラッキングIDがロストしたとき発効するイベントハンドルを解除する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IHighDefinitionFaceFrameSource Interface
RLTitle : IHighDefinitionFaceFrameSource Interface
KeywordK : IHighDefinitionFaceFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IHighDefinitionFaceFrameSource
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource
KeywordA : T:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource
AssetID : T:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
