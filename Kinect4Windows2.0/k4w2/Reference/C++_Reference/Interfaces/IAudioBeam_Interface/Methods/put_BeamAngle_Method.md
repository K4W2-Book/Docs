IAudioBeam::put\_BeamAngle Method  
=================================  

Beamformingの角度を設定する。 <span id="syntaxSection"></span>

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
HRESULT put_BeamAngle(  
         float beamAngle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*beamAngle*    
Type: float  
Beamformingの角度(ラジアン)。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

Beamformingは[-0.872665f, 0.872665f]\(度数法では[-50.0, 50.0])の範囲で設定できる。  
度数法から弧度法へは、  

    radian = degree * ( π / 180.0f )  

で変換できる。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : put_BeamAngle Method
RLTitle : IAudioBeam::put_BeamAngle Method
KeywordK : put_BeamAngle method
KeywordK : IAudioBeam::put_BeamAngle method
KeywordF : IAudioBeam::put_BeamAngle
KeywordF : put_BeamAngle
KeywordF : Microsoft.Kinect.kinect.IAudioBeam.put_BeamAngle(float)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeam.put_BeamAngle(float)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeam.put_BeamAngle(float)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam::put_BeamAngle
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
