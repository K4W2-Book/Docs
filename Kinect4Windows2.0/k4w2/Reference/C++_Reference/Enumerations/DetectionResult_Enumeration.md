DetectionResult Enumeration  
===========================  

顔の付随情報の検出結果。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _DetectionResult  
{  
    DetectionResult_Unknown = 0,  
    DetectionResult_No = 1,  
    DetectionResult_Maybe = 2,  
    DetectionResult_Yes = 3  
} DetectionResult, DetectionResult_Unknown, DetectionResult_No, DetectionResult_Maybe, DetectionResult_Yes;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EDB"></span>

Constants  
=========  

| Constant                 | Description                                                    |
|--------------------------|----------------------------------------------------------------|
| DetectionResult\_Unknown | 不明。                                                           |
| DetectionResult\_No      | 検出していない。                                                    |
| DetectionResult\_Maybe   | 検出しているかもしれない。                                             |
| DetectionResult\_Yes     | 検出している。                                                     |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : DetectionResult Enumeration
RLTitle : DetectionResult Enumeration
KeywordK : DetectionResult enumeration
HelpPriority : 2
KeywordF : DetectionResult
KeywordF : Microsoft.Kinect.kinect.DetectionResult
KeywordA : T:Microsoft.Kinect.kinect.DetectionResult
AssetID : T:Microsoft.Kinect.kinect.DetectionResult
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.DetectionResult
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
