IInfraredFrameReader Interface  
==============================  

InfraredフレームのReader。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IInfraredFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IInfraredFrameReader**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IInfraredFrameReader/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">最新のInfraredフレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrameReader/Methods/get_InfraredFrameSource.md">get_InfraredFrameSource</a></td>
<td align="left">InfraredフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrameReader/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">InfraredフレームのReaderの動作状態を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrameReader/Methods/GetFrameArrivedEventData.md">GetFrameArrivedEventData</a></td>
<td align="left">新しいInfraredフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrameReader/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">InfraredフレームのReaderの動作状態を設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrameReader/Methods/SubscribeFrameArrived_Method.md">SubscribeFrameArrived</a></td>
<td align="left">Infraredフレームの更新を待つイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrameReader/Methods/UnsubscribeFrameArrived.md">UnsubscribeFrameArrived</a></td>
<td align="left">Infraredフレームの更新を待つイベントハンドルを解除する。</td>
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
TOCTitle : IInfraredFrameReader Interface
RLTitle : IInfraredFrameReader Interface
KeywordK : IInfraredFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IInfraredFrameReader
KeywordF : Microsoft.Kinect.kinect.IInfraredFrameReader
KeywordA : T:Microsoft.Kinect.kinect.IInfraredFrameReader
AssetID : T:Microsoft.Kinect.kinect.IInfraredFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IInfraredFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
