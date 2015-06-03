IBodyIndexFrameReader Interface  
===============================  

BodyIndexフレームのReader。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBodyIndexFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBodyIndexFrameReader**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IBodyIndexFrameReader/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">最新のBodyIndexフレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrameReader/Methods/get_BodyIndexFrameSource.md">get_BodyIndexFrameSource</a></td>
<td align="left">BodyIndexフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrameReader/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">BodyIndexフレームのReaderの動作状態を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrameReader/Methods/GetFrameArrivedEventData.md">GetFrameArrivedEventData</a></td>
<td align="left">新しいBodyIndexフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrameReader/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">BodyIndexフレームのReaderの動作状態を設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrameReader/Methods/SubscribeFrameArrived_Method.md">SubscribeFrameArrived</a></td>
<td align="left">BodyIndexフレームの更新を待つイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrameReader/Methods/UnsubscribeFrameArrived.md">UnsubscribeFrameArrived</a></td>
<td align="left">BodyIndexフレームの更新を待つイベントハンドルを解除する。</td>
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
TOCTitle : IBodyIndexFrameReader Interface
RLTitle : IBodyIndexFrameReader Interface
KeywordK : IBodyIndexFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBodyIndexFrameReader
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrameReader
KeywordA : T:Microsoft.Kinect.kinect.IBodyIndexFrameReader
AssetID : T:Microsoft.Kinect.kinect.IBodyIndexFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
