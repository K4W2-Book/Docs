IAudioBeamSubFrame::get\_BeamAngle Method  
=========================================  

AudioBeamの角度を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_BeamAngle(  
         float *beamAngle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*beamAngle*    
Type: float  
[out] AudioBeamの角度(ラジアン)。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

AudioBeamは[-0.872665f, 0.872665f]\(度数法では[-50.0, 50.0])の範囲で取得できる。  
弧度法から度数法へは、  

    degree = ( radian * 180.0f ) / π  

で変換できる。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_BeamAngle Method
RLTitle : IAudioBeamSubFrame::get_BeamAngle Method
KeywordK : get_BeamAngle method
KeywordK : IAudioBeamSubFrame::get_BeamAngle method
KeywordF : IAudioBeamSubFrame::get_BeamAngle
KeywordF : get_BeamAngle
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_BeamAngle(float@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_BeamAngle(float@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_BeamAngle(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame::get_BeamAngle
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
