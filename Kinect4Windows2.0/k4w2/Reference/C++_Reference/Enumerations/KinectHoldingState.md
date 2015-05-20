KinectHoldingState Enumeration  
==============================  

ホールディングイベントステータス。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _KinectHoldingState  
{  
    KinectHoldingState_Started = 0,  
    KinectHoldingState_Completed = 1,  
    KinectHoldingState_Canceled = 2  
} KinectHoldingState, KinectHoldingState_Started, KinectHoldingState_Completed, KinectHoldingState_Canceled;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E6"></span>

Constants  
=========  

| Constant                      | Description                                                                                                                                                |
|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| KinectHoldingState\_Started   | ホールディングが検出された。<br/>ホールディングの時間閾値を超えた。<br/>別のホールディングまたはジェスチャーが検出された。 |
| KinectHoldingState\_Completed | ホールディングが解除された。                                                                                                                              |
| KinectHoldingState\_Canceled  | 追加のホールディングが検出され、その後に続くジェスチャーが検出された(スライドなど)。または、CompleteGestureが呼び出された。                            |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectHoldingState Enumeration
RLTitle : KinectHoldingState Enumeration
KeywordK : KinectHoldingState enumeration
HelpPriority : 2
KeywordF : KinectHoldingState
KeywordF : Microsoft.Kinect.kinect.KinectHoldingState
KeywordA : T:Microsoft.Kinect.kinect.KinectHoldingState
AssetID : T:Microsoft.Kinect.kinect.KinectHoldingState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectHoldingState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
