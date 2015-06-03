IInfraredFrameSource Interface  
==============================  

InfraredフレームのSource。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IInfraredFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IInfraredFrameSource**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IInfraredFrameSource/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Infraredフレームの情報を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrameSource/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">InfraredフレームのSourceの動作状況を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrameSource/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">InfraredフレームのSourceを取得したセンサーを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrameSource/Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">最新のフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrameSource/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">InfraredフレームのReaderを開く。</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrameSource/Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">最新のフレームが準備できたとき、またはフレームを破棄したときに発効するイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrameSource/Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
<td align="left">最新のフレームが準備できたとき、またはフレームを破棄したときに発効するイベントハンドルを解除する。</td>
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
TOCTitle : IInfraredFrameSource Interface
RLTitle : IInfraredFrameSource Interface
KeywordK : IInfraredFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IInfraredFrameSource
KeywordF : Microsoft.Kinect.kinect.IInfraredFrameSource
KeywordA : T:Microsoft.Kinect.kinect.IInfraredFrameSource
AssetID : T:Microsoft.Kinect.kinect.IInfraredFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IInfraredFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
