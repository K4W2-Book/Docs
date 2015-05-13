FaceProperty Enumeration  
========================  

顔の付随情報の種類。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _FaceProperty  
{  
    FaceProperty_Happy = 0,  
    FaceProperty_Engaged = 1,  
    FaceProperty_WearingGlasses = 2,  
    FaceProperty_LeftEyeClosed = 3,  
    FaceProperty_RightEyeClosed = 4,  
    FaceProperty_MouthOpen = 5,  
    FaceProperty_MouthMoved = 6,  
    FaceProperty_LookingAway = 7,  
    FaceProperty_Count = (FaceProperty_LookingAway+1)  
} FaceProperty, FaceProperty_Happy, FaceProperty_Engaged, FaceProperty_WearingGlasses, FaceProperty_LeftEyeClosed, FaceProperty_RightEyeClosed, FaceProperty_MouthOpen, FaceProperty_MouthMoved, FaceProperty_LookingAway, FaceProperty_Count;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EXB"></span>

Constants  
=========  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Constant</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">FaceProperty_Happy</td>
<td align="left">笑顔の状態。</td>
</tr>
<tr class="even">
<td align="left">FaceProperty_Engaged</td>
<td align="left">付随情報が取得できている状態。</td>
</tr>
<tr class="odd">
<td align="left">FaceProperty_WearingGlasses</td>
<td align="left">眼鏡を掛けている状態。</td>
</tr>
<tr class="even">
<td align="left">FaceProperty_LeftEyeClosed</td>
<td align="left">左目を閉じている状態。</td>
</tr>
<tr class="odd">
<td align="left">FaceProperty_RightEyeClosed</td>
<td align="left">右目を閉じている状態。</td>
</tr>
<tr class="even">
<td align="left">FaceProperty_MouthOpen</td>
<td align="left">口が開いている状態。</td>
</tr>
<tr class="odd">
<td align="left">FaceProperty_MouthMoved</td>
<td align="left">口が動いている状態。</td>
</tr>
<tr class="even">
<td align="left">FaceProperty_LookingAway</td>
<td align="left">顔がセンサーの方向を向いていない状態。</td>
</tr>
<tr class="odd">
<td align="left">FaceProperty_Count</td>
<td align="left">FacePropertyの数。(8)</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceProperty Enumeration
RLTitle : FaceProperty Enumeration
KeywordK : FaceProperty enumeration
HelpPriority : 2
KeywordF : FaceProperty
KeywordF : Microsoft.Kinect.face.FaceProperty
KeywordA : T:Microsoft.Kinect.face.FaceProperty
AssetID : T:Microsoft.Kinect.face.FaceProperty
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.FaceProperty
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
