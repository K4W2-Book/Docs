Activity Enumeration  
====================  

Activityの種類。
この機能はKinect for Windowsアプリケーションではサポートされません。
この列挙体はXbox One SDKとのクロスコンパイルをサポートするために含まれています。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _Activity  
{  
    Activity_EyeLeftClosed = 0,  
    Activity_EyeRightClosed = 1,  
    Activity_MouthOpen = 2,  
    Activity_MouthMoved = 3,  
    Activity_LookingAway = 4,  
    Activity_Count = (Activity_LookingAway+1)  
} Activity, Activity_EyeLeftClosed, Activity_EyeRightClosed, Activity_MouthOpen, Activity_MouthMoved, Activity_LookingAway, Activity_Count;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ELB"></span>

Constants  
=========  

| Constant                 | Description                                 |
|--------------------------|---------------------------------------------|
| Activity\_EyeLeftClosed  | 左目が閉じている。                               |
| Activity\_EyeRightClosed | 右目が閉じている。                               |
| Activity\_MouthOpen      | 口が開いている。                                 |
| Activity\_MouthMoved     | 口が動いている。                                 |
| Activity\_LookingAway    | 顔がセンサーの方向を向いていない。                    |
| Activity\_Count          | Activityの数。(5)                             |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Activity Enumeration
RLTitle : Activity Enumeration
KeywordK : Activity enumeration
HelpPriority : 2
KeywordF : Activity
KeywordF : Microsoft.Kinect.kinect.Activity
KeywordA : T:Microsoft.Kinect.kinect.Activity
AssetID : T:Microsoft.Kinect.kinect.Activity
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.Activity
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
