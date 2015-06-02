IAudioBeam::get\_AudioBeamMode Method  
=====================================  

Beamformingの角度を測定するモードを取得する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
HRESULT get_AudioBeamMode(  
         AudioBeamMode *audioBeamMode  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*audioBeamMode*    
Type: AudioBeamMode  
[out] Beamformingの角度を測定するモード  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

AudioBeamMode\_Automaticに設定されている場合、Beamformingは音源方向を向きます。  
AudioBeamMode\_Manualに設定されている場合、Beamformingは[put\_BeamAngle](put_BeamAngle_Method.md)で設定された値に固定されます。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_AudioBeamMode Method
RLTitle : IAudioBeam::get_AudioBeamMode Method
KeywordK : get_AudioBeamMode method
KeywordK : IAudioBeam::get_AudioBeamMode method
KeywordF : IAudioBeam::get_AudioBeamMode
KeywordF : get_AudioBeamMode
KeywordF : Microsoft.Kinect.kinect.IAudioBeam.get_AudioBeamMode(AudioBeamMode@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeam.get_AudioBeamMode(AudioBeamMode@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeam.get_AudioBeamMode(AudioBeamMode@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam::get_AudioBeamMode
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
