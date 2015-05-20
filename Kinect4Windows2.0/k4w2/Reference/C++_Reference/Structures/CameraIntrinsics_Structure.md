CameraIntrinsics Structure  
==========================  

Depthセンサーのキャリブレーションデータ。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _CameraIntrinsics {  
    float FocalLengthX;  
    float FocalLengthY;  
    float PrincipalPointX;  
    float PrincipalPointY;  
    float RadialDistortionSecondOrder;  
    float RadialDistortionFourthOrder;  
    float RadialDistortionSixthOrder;  
} CameraIntrinsics;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**FocalLengthX**    
X軸の焦点距離。(pixel)  

**FocalLengthY**    
Y軸の焦点距離。(pixel)  

**PrincipalPointX**    
X軸の主点。(pixel)  

**PrincipalPointY**    
Y軸の主点。(pixel)  

**RadialDistortionSecondOrder**    
半径方向の歪み係数。(2次)  

**RadialDistortionFourthOrder**    
半径方向の歪み係数。(4次)  

**RadialDistortionSixthOrder**    
半径方向の歪み係数。(6次)  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CameraIntrinsics Structure
RLTitle : CameraIntrinsics Structure
KeywordK : CameraIntrinsics structure
KeywordF : CameraIntrinsics
KeywordF : Microsoft.Kinect.kinect.CameraIntrinsics
KeywordA : T:Microsoft.Kinect.kinect.CameraIntrinsics
AssetID : T:Microsoft.Kinect.kinect.CameraIntrinsics
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.CameraIntrinsics
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
