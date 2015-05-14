IHighDefinitionFaceFrameReader Interface  
==========================  

HDFaceフレームのReader。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IHighDefinitionFaceFrameReader : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IHighDefinitionFaceFrameReader**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IHighDefinitionFaceFrameReader_Interface/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">最新のHDFaceフレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameReader_Interface/Methods/get_HighDefinitionFaceFrameSource_Method.md">get_HighDefinitionFaceFrameSource</a></td>
<td align="left">HDFaceフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameReader_Interface/Methods/get_IsPaused_Method.md">get_IsPaused</a></td>
<td align="left">HDFaceフレームのReaderの動作状態を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameReader_Interface/Methods/GetFrameArrivedEventData.md">GetFrameArrivedEventData</a></td>
<td align="left">新しいHDFaceフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameReader_Interface/Methods/put_IsPaused_Method.md">put_IsPaused</a></td>
<td align="left">HDFaceフレームのReaderの動作状態を設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IHighDefinitionFaceFrameReader_Interface/Methods/SubscribeFrameArrived_Method.md">SubscribeFrameArrived</a></td>
<td align="left">HDFaceフレームの更新を待つイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IHighDefinitionFaceFrameReader_Interface/Methods/UnsubscribeFrameArrived.md">UnsubscribeFrameArrived</a></td>
<td align="left">HDFaceフレームの更新を待つイベントハンドルを解除する。</td>
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
TOCTitle : IHighDefinitionFaceFrameReader Interface
RLTitle : IHighDefinitionFaceFrameReader Interface
KeywordK : IHighDefinitionFaceFrameReader interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IHighDefinitionFaceFrameReader
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader
KeywordA : T:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader
AssetID : T:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
