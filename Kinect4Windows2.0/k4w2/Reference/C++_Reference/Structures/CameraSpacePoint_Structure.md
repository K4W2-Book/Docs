CameraSpacePoint Structure  
==========================  

Camera座標系の3次元位置。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _CameraSpacePoint {  
    float X;  
    float Y;  
    float Z;  
} CameraSpacePoint;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**X**    
X座標。  

**Y**    
Y座標。  

**Z**    
Z座標。  

<span id="remarks"></span>

Remarks  
=======  

Camera座標系はKinectを中心とし3次元位置を表します。  
Camera座標系は以下のように定義される。  

-   Camera座標系の原点(0, 0, 0)は、KinectのIRカメラの中心にある。  
-   X軸はKinectを後ろから見たときに原点を中心として左方向に増加、右方向に減少する。  
-   Y軸は原点を中心として上方向に増加、下方向に減少する。 (この軸はセンサーの角度に依存する。)  
-   Z軸は原点を中心として前方向に増加する。  
-   単位はメートル。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  

<span id="ID4EWB"></span>

See also  
========  

<span id="ID4EYB"></span>
#### Reference  

[Body tracking](../../../Programming_Guide/Body_tracking.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CameraSpacePoint Structure
RLTitle : CameraSpacePoint Structure
KeywordK : CameraSpacePoint structure
KeywordF : CameraSpacePoint
KeywordF : Microsoft.Kinect.kinect.CameraSpacePoint
KeywordA : T:Microsoft.Kinect.kinect.CameraSpacePoint
AssetID : T:Microsoft.Kinect.kinect.CameraSpacePoint
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.CameraSpacePoint
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
