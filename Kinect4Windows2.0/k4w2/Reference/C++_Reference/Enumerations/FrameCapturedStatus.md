FrameCapturedStatus Enumeration  
===============================  

フレームキャプチャーステータス。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _FrameCapturedStatus  
{  
    FrameCapturedStatus_Unknown = 0,  
    FrameCapturedStatus_Queued = 1,  
    FrameCapturedStatus_Dropped = 2  
} FrameCapturedStatus, FrameCapturedStatus_Unknown, FrameCapturedStatus_Queued, FrameCapturedStatus_Dropped;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E6"></span>

Constants  
=========  

| Constant                     | Description                      |
|------------------------------|----------------------------------|
| FrameCapturedStatus\_Unknown | 不明。   |
| FrameCapturedStatus\_Queued  | フレームをキューイングした。 |
| FrameCapturedStatus\_Dropped | フレームをドロップした。           |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameCapturedStatus Enumeration
RLTitle : FrameCapturedStatus Enumeration
KeywordK : FrameCapturedStatus enumeration
HelpPriority : 2
KeywordF : FrameCapturedStatus
KeywordF : Microsoft.Kinect.kinect.FrameCapturedStatus
KeywordA : T:Microsoft.Kinect.kinect.FrameCapturedStatus
AssetID : T:Microsoft.Kinect.kinect.FrameCapturedStatus
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.FrameCapturedStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
