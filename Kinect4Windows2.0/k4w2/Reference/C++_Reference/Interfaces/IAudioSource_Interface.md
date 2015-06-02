IAudioSource Interface  
======================  

AudioフレームのSource。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IAudioSource : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IAudioSource**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IAudioSource_Interface/Methods/get_AudioBeams_Method.md">get_AudioBeams</a></td>
<td align="left">AudioBeamのリストを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/get_AudioCalibrationState.md">get_AudioCalibrationState</a></td>
<td align="left">Audioセンサーのキャリブレーションステータスを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/get_IsActive_Method.md">get_IsActive</a></td>
<td align="left">AudioフレームのSourceの動作状況を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/get_KinectSensor_Method.md">get_KinectSensor</a></td>
<td align="left">AudioフレームのSourceを取得したセンサーを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/get_MaxSubFrameCount_Method.md">get_MaxSubFrameCount</a></td>
<td align="left">AudioBeamサブフレームの最大数を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/get_SubFrameDuration_Method.md">get_SubFrameDuration</a></td>
<td align="left">AudioBeamサブフレームのサンプリング時間を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/get_SubFrameLengthInBytes.md">get_SubFrameLengthInBytes</a></td>
<td align="left">AudioBeamサブフレームのサイズ(Byte)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/GetFrameCapturedEventData.md">GetFrameCapturedEventData</a></td>
<td align="left">最新のフレームが準備できたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">AudioBeamフレームのReaderを開く。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioSource_Interface/Methods/SubscribeFrameCaptured.md">SubscribeFrameCaptured</a></td>
<td align="left">最新のフレームが準備できたとき、またはフレームを破棄したときに発効するイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioSource_Interface/Methods/UnsubscribeFrameCaptured.md">UnsubscribeFrameCaptured</a></td>
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
TOCTitle : IAudioSource Interface
RLTitle : IAudioSource Interface
KeywordK : IAudioSource interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IAudioSource
KeywordF : Microsoft.Kinect.kinect.IAudioSource
KeywordA : T:Microsoft.Kinect.kinect.IAudioSource
AssetID : T:Microsoft.Kinect.kinect.IAudioSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
