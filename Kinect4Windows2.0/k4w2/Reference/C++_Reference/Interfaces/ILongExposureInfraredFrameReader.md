ILongExposureInfraredFrameReader Interface  
==========================================  

長時間露光InfraredフレームのReader。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface ILongExposureInfraredFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**ILongExposureInfraredFrameReader**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="ILongExposureInfraredFrameReader/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">最新の長時間露光Infraredフレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="ILongExposureInfraredFrameReader/Methods/get.md">get_InfraredFrameSource</a></td>
<td align="left">長時間露光InfraredフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="ILongExposureInfraredFrameReader/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">長時間露光InfraredフレームのReaderの動作状態を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="ILongExposureInfraredFrameReader/Methods/GetFrameArrivedEventData.md">GetFrameArrivedEventData</a></td>
<td align="left">新しい長時間露光Infraredフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="ILongExposureInfraredFrameReader/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">長時間露光InfraredフレームのReaderの動作状態を設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="ILongExposureInfraredFrameReader/Methods/SubscribeFrameArrived_Method.md">SubscribeFrameArrived</a></td>
<td align="left">長時間露光Infraredフレームの更新を待つイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="ILongExposureInfraredFrameReader/Methods/UnsubscribeFrameArrived.md">UnsubscribeFrameArrived</a></td>
<td align="left">長時間露光Infraredフレームの更新を待つイベントハンドルを解除する。</td>
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
TOCTitle : ILongExposureInfraredFrameReader Interface
RLTitle : ILongExposureInfraredFrameReader Interface
KeywordK : ILongExposureInfraredFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : ILongExposureInfraredFrameReader
KeywordF : Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader
KeywordA : T:Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader
AssetID : T:Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
