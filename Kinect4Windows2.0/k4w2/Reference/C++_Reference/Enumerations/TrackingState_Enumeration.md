TrackingState Enumeration  
=========================  

Joint(関節)のトラッキングステータス。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _TrackingState  
{  
    TrackingState_NotTracked = 0,  
    TrackingState_Inferred = 1,  
    TrackingState_Tracked = 2  
} TrackingState, TrackingState_NotTracked, TrackingState_Inferred, TrackingState_Tracked;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E6"></span>

Constants  
=========  

| Constant                  | Description                                                              |
|---------------------------|--------------------------------------------------------------------------|
| TrackingState\_NotTracked | トラッキングされていない。                                                        |
| TrackingState\_Inferred   | 推測されたデータであり、位置の信頼度はとても低い。                                    |
| TrackingState\_Tracked    | トラッキングされている。             |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TrackingState Enumeration
RLTitle : TrackingState Enumeration
KeywordK : TrackingState enumeration
HelpPriority : 2
KeywordF : TrackingState
KeywordF : Microsoft.Kinect.kinect.TrackingState
KeywordA : T:Microsoft.Kinect.kinect.TrackingState
AssetID : T:Microsoft.Kinect.kinect.TrackingState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.TrackingState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
