IAudioBeam Interface  
====================  

Audioビーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IAudioBeam : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IAudioBeam**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IAudioBeam_Interface/Methods/get_AudioBeamMode_Method.md">get_AudioBeamMode</a></td>
<td align="left">Beamformingの角度を測定するモードを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_AudioSource_Method.md">get_AudioSource</a></td>
<td align="left">[IAudioSource](IAudioSource_Interface.md)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_BeamAngle_Method.md">get_BeamAngle</a></td>
<td align="left">Beamformingの角度を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_BeamAngleConfidence.md">get_BeamAngleConfidence</a></td>
<td align="left">Beamformingの角度の信頼値を取得する。<br/>信頼値は[0.0f,1.0f]の範囲で、値が大きいほど角度は信頼できます。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Beamformingを取得した時間(相対時間)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/OpenInputStream_Method.md">OpenInputStream</a></td>
<td align="left">音声データの入力ストリームを開く。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IAudioBeam_Interface/Methods/put_AudioBeamMode_Method.md">put_AudioBeamMode</a></td>
<td align="left">Beamformingの角度を測定するモードを設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IAudioBeam_Interface/Methods/put_BeamAngle_Method.md">put_BeamAngle</a></td>
<td align="left">Beamformingの角度を設定する。</td>
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
TOCTitle : IAudioBeam Interface
RLTitle : IAudioBeam Interface
KeywordK : IAudioBeam interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IAudioBeam
KeywordF : Microsoft.Kinect.kinect.IAudioBeam
KeywordA : T:Microsoft.Kinect.kinect.IAudioBeam
AssetID : T:Microsoft.Kinect.kinect.IAudioBeam
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
