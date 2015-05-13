FacePointType Enumeration  
=========================  

顔パーツの種類。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _FacePointType  
{  
    FacePointType_None = -1,  
    FacePointType_EyeLeft = 0,  
    FacePointType_EyeRight = 1,  
    FacePointType_Nose = 2,  
    FacePointType_MouthCornerLeft = 3,  
    FacePointType_MouthCornerRight = 4,  
    FacePointType_Count = (FacePointType_MouthCornerRight+1)  
} FacePointType, FacePointType_None, FacePointType_EyeLeft, FacePointType_EyeRight, FacePointType_Nose, FacePointType_MouthCornerLeft, FacePointType_MouthCornerRight, FacePointType_Count;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EPB"></span>

Constants  
=========  

| Constant                        | Description                                      |
|---------------------------------|--------------------------------------------------|
| FacePointType\_None             | なし。                                             |
| FacePointType\_EyeLeft          | 左目。                                        |
| FacePointType\_EyeRight         | 右目。                                       |
| FacePointType\_Nose             | 鼻。                                             |
| FacePointType\_MouthCornerLeft  | 左口角。                        |
| FacePointType\_MouthCornerRight | 右口角。                       |
| FacePointType\_Count            | FacePointTypeの数。(5) |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FacePointType Enumeration
RLTitle : FacePointType Enumeration
KeywordK : FacePointType enumeration
HelpPriority : 2
KeywordF : FacePointType
KeywordF : Microsoft.Kinect.face.FacePointType
KeywordA : T:Microsoft.Kinect.face.FacePointType
AssetID : T:Microsoft.Kinect.face.FacePointType
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.FacePointType
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
