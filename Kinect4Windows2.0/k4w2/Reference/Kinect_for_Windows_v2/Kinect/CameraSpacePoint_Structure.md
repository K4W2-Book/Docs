CameraSpacePoint 構造体  
==========================  

カメラ(Kinect)を原点(0,0,0)とした、メートル単位の3次元のカメラ座標系。
<span id="syntaxSection"></span>

構文
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
<td align="left"><pre><code>public value struct CameraSpacePoint</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public struct CameraSpacePoint</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var cameraSpacePoint = {  
      x : /* Your value */,   
      y : /* Your value */,   
      z : /* Your value */  
}</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**CameraSpacePoint** has the following members.  

<span id="publicfieldsSection"></span>

フィールド
======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">名前</th>
<th align="left">説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="CameraSpacePoint_Structure/CameraSpacePoint_Fields/X_Field.md">X</a></td>
<td align="left">メートル単位でのX座標。</td>
</tr>
<tr class="even">
<td align="left"><a href="CameraSpacePoint_Structure/CameraSpacePoint_Fields/Y_Field.md">Y</a></td>
<td align="left">メートル単位でのY座標。</td>
</tr>
<tr class="odd">
<td align="left"><a href="CameraSpacePoint_Structure/CameraSpacePoint_Fields/Z_Field.md">Z</a></td>
<td align="left">メートル単位でのZ座標。</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

Camera space refers to the 3D coordinate system used by Kinect. The coordinate system is defined as follows:  

-   The origin (x=0, y=0, z=0) is located at the center of the IR sensor on Kinect  
-   X grows to the sensor’s left  
-   Y grows up (note that this direction is based on the sensor’s tilt)  
-   Z grows out in the direction the sensor is facing  
-   1 unit = 1 meter  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EEB"></span>

See also  
========  

<span id="ID4EGB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  
 [Body tracking](../../../Programming_Guide/Body_tracking.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CameraSpacePoint Structure
RLTitle : CameraSpacePoint Structure
KeywordK : CameraSpacePoint structure, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.CameraSpacePoint
KeywordF : CameraSpacePoint
KeywordF : WindowsPreview.Kinect.CameraSpacePoint
KeywordA : T:WindowsPreview.Kinect.CameraSpacePoint
AssetID : T:WindowsPreview.Kinect.CameraSpacePoint
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.CameraSpacePoint
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
