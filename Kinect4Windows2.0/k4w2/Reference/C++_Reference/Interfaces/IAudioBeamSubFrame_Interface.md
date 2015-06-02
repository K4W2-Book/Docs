IAudioBeamSubFrame Interface  
============================  

AudioBeamサブフレーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IAudioBeamSubFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IAudioBeamSubFrame**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/AccessUnderlyingBuffer.md">AccessUnderlyingBuffer</a></td>
<td align="left">AudioBeamサブフレームのデータを取得する。(ポインタ参照)</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">AudioBeamサブフレームのデータを取得する。(コピー)</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_AudioBeamMode_Method.md">get_AudioBeamMode</a></td>
<td align="left">AudioBeamの角度を測定するモードを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get.md">get_AudioBodyCorrelationCount</a></td>
<td align="left">AudioBeamサブフレームに関連するBodyの数を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_BeamAngle_Method.md">get_BeamAngle</a></td>
<td align="left">AudioBeamの角度を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_BeamAngleConfidence.md">get_BeamAngleConfidence</a></td>
<td align="left">AudioBeamの角度の信頼値を取得する。<br/>信頼値は[0.0f,1.0f]の範囲で、値が大きいほど角度は信頼できます。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_Duration_Method.md">get_Duration</a></td>
<td align="left">AudioBeamサブフレームのサンプリング時間を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_FrameLengthInBytes.md">get_FrameLengthInBytes</a></td>
<td align="left">AudioBeamサブフレームのサイズ(Byte)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">AudioBeamサブフレームの取得時間(相対時間)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamSubFrame_Interface/Methods/GetAudioBodyCorrelation.md">GetAudioBodyCorrelation</a></td>
<td align="left">AudioBeamサブフレームに関連するBodyを取得する。</td>
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
TOCTitle : IAudioBeamSubFrame Interface
RLTitle : IAudioBeamSubFrame Interface
KeywordK : IAudioBeamSubFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IAudioBeamSubFrame
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame
KeywordA : T:Microsoft.Kinect.kinect.IAudioBeamSubFrame
AssetID : T:Microsoft.Kinect.kinect.IAudioBeamSubFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
