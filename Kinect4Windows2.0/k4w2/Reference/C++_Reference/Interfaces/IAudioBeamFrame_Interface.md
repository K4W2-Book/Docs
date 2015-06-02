IAudioBeamFrame Interface  
=========================  

AudioBeamフレーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IAudioBeamFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IAudioBeamFrame**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IAudioBeamFrame_Interface/Methods/get_AudioBeam_Method.md">get_AudioBeam</a></td>
<td align="left">AudioBeamを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamFrame_Interface/Methods/get_AudioSource_Method.md">get_AudioSource</a></td>
<td align="left">AudioBeamフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamFrame_Interface/Methods/get_Duration_Method.md">get_Duration</a></td>
<td align="left">AudioBeamフレームのサンプリング時間を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamFrame_Interface/Methods/get_RelativeTimeStart_Method.md">get_RelativeTimeStart</a></td>
<td align="left">AudioBeamフレームの最初のAudioBeamサブフレームの取得時間(相対時間)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeamFrame_Interface/Methods/get_SubFrameCount_Method.md">get_SubFrameCount</a></td>
<td align="left">AudioBeamサブフレームの数を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeamFrame_Interface/Methods/GetSubFrame_Method.md">GetSubFrame</a></td>
<td align="left">指定したインデックスのAudioBeamサブフレームを取得する。</td>
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
TOCTitle : IAudioBeamFrame Interface
RLTitle : IAudioBeamFrame Interface
KeywordK : IAudioBeamFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IAudioBeamFrame
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrame
KeywordA : T:Microsoft.Kinect.kinect.IAudioBeamFrame
AssetID : T:Microsoft.Kinect.kinect.IAudioBeamFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
