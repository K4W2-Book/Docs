IBodyFrameReader Interface  
==========================  

BodyフレームのReader。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBodyFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBodyFrameReader**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IBodyFrameReader_Interface/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">最新のBodyフレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/get_BodyFrameSource_Method.md">get_BodyFrameSource</a></td>
<td align="left">BodyフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">BodyフレームのReaderの動作状態を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/GetFrameArrivedEventData.md">GetFrameArrivedEventData</a></td>
<td align="left">新しいBodyフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">BodyフレームのReaderの動作状態を設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/SubscribeFrameArrived_Method.md">SubscribeFrameArrived</a></td>
<td align="left">Bodyフレームの更新を待つイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyFrameReader_Interface/Methods/UnsubscribeFrameArrived.md">UnsubscribeFrameArrived</a></td>
<td align="left">Bodyフレームの更新を待つイベントハンドルを解除する。</td>
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
TOCTitle : IBodyFrameReader Interface
RLTitle : IBodyFrameReader Interface
KeywordK : IBodyFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBodyFrameReader
KeywordF : Microsoft.Kinect.kinect.IBodyFrameReader
KeywordA : T:Microsoft.Kinect.kinect.IBodyFrameReader
AssetID : T:Microsoft.Kinect.kinect.IBodyFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
