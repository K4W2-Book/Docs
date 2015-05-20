JointOrientation Structure  
==========================  

Joint(関節)の回転方向。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _JointOrientation {  
    JointType JointType;  
    Vector4 Orientation;  
} JointOrientation;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**JointType**    
Jointの種類。  

**Orientation**    
1つ上の親Jointへの相対的な方向。(クォータニオン)  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : JointOrientation Structure
RLTitle : JointOrientation Structure
KeywordK : JointOrientation structure
KeywordF : JointOrientation
KeywordF : Microsoft.Kinect.kinect.JointOrientation
KeywordA : T:Microsoft.Kinect.kinect.JointOrientation
AssetID : T:Microsoft.Kinect.kinect.JointOrientation
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.JointOrientation
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
