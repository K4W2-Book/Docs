IAudioBeam::put\_AudioBeamMode Method  
=====================================  

Beamformingの角度を測定するモードを設定する。 <span id="syntaxSection"></span>

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
HRESULT put_AudioBeamMode(  
         <a href="../../../Enumerations/AudioBeamMode_Enumeration.md">AudioBeamMode</a> audioBeamMode  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*audioBeamMode*    
Type: [AudioBeamMode](../../../Enumerations/AudioBeamMode_Enumeration.md)  
Beamformingの角度を測定するモード  

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
TOCTitle : put_AudioBeamMode Method
RLTitle : IAudioBeam::put_AudioBeamMode Method
KeywordK : put_AudioBeamMode method
KeywordK : IAudioBeam::put_AudioBeamMode method
KeywordF : IAudioBeam::put_AudioBeamMode
KeywordF : put_AudioBeamMode
KeywordF : Microsoft.Kinect.kinect.IAudioBeam.put_AudioBeamMode(Microsoft.Kinect.kinect.AudioBeamMode)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeam.put_AudioBeamMode(Microsoft.Kinect.kinect.AudioBeamMode)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeam.put_AudioBeamMode(Microsoft.Kinect.kinect.AudioBeamMode)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam::put_AudioBeamMode
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
