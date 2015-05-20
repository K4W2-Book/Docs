FrameSourceTypes Enumeration  
============================  

フレームの種類。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _FrameSourceTypes  
{  
    FrameSourceTypes_None = 0,  
    FrameSourceTypes_Color = 0x1,  
    FrameSourceTypes_Infrared = 0x2,  
    FrameSourceTypes_LongExposureInfrared = 0x4,  
    FrameSourceTypes_Depth = 0x8,  
    FrameSourceTypes_BodyIndex = 0x10,  
    FrameSourceTypes_Body = 0x20,  
    FrameSourceTypes_Audio = 0x40  
} FrameSourceTypes, FrameSourceTypes_None, FrameSourceTypes_Color, FrameSourceTypes_Infrared, FrameSourceTypes_LongExposureInfrared, FrameSourceTypes_Depth, FrameSourceTypes_BodyIndex, FrameSourceTypes_Body, FrameSourceTypes_Audio;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ETB"></span>

Constants  
=========  

| Constant                               | Description                           |
|----------------------------------------|---------------------------------------|
| FrameSourceTypes\_None                 | なし。             |
| FrameSourceTypes\_Color                | Colorストリーム。                  |
| FrameSourceTypes\_Infrared             | Infraredストリーム。               |
| FrameSourceTypes\_LongExposureInfrared | Infrared(長時間露光)ストリーム。 |
| FrameSourceTypes\_Depth                | Depthストリーム。                   |
| FrameSourceTypes\_BodyIndex            | BodyIndexストリーム             |
| FrameSourceTypes\_Body                 | Bodyストリーム。                   |
| FrameSourceTypes\_Audio                | Audioストリーム。                  |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameSourceTypes Enumeration
RLTitle : FrameSourceTypes Enumeration
KeywordK : FrameSourceTypes enumeration
HelpPriority : 2
KeywordF : FrameSourceTypes
KeywordF : Microsoft.Kinect.kinect.FrameSourceTypes
KeywordA : T:Microsoft.Kinect.kinect.FrameSourceTypes
AssetID : T:Microsoft.Kinect.kinect.FrameSourceTypes
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.FrameSourceTypes
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
