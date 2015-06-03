IDepthFrameSource Interface  
===========================  

DepthフレームのSource。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IDepthFrameSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IDepthFrameSource**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IDepthFrameSource_Interface/Methods/get_DepthMaxReliableDistance.md">get_DepthMaxReliableDistance</a></td>
<td align="left">Depthフレームの精度が確保できる最大距離を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrameSource_Interface/Methods/get_DepthMinReliableDistance.md">get_DepthMinReliableDistance</a></td>
<td align="left">Depthフレームの精度が確保できる最小距離を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrameSource_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Depthフレームの情報を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrameSource_Interface/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">DepthフレームのSourceの動作状況を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrameSource_Interface/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">DepthフレームのSourceを取得したセンサーを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrameSource_Interface/Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">最新のフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrameSource_Interface/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">DepthフレームのReaderを開く。</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrameSource_Interface/Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">最新のフレームが準備できたとき、またはフレームを破棄したときに発効するイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrameSource_Interface/Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
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
TOCTitle : IDepthFrameSource Interface
RLTitle : IDepthFrameSource Interface
KeywordK : IDepthFrameSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IDepthFrameSource
KeywordF : Microsoft.Kinect.kinect.IDepthFrameSource
KeywordA : T:Microsoft.Kinect.kinect.IDepthFrameSource
AssetID : T:Microsoft.Kinect.kinect.IDepthFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
