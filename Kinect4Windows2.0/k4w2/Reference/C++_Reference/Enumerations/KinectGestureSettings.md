KinectGestureSettings Enumeration  
=================================  

ジェスチャーインタラクションの種類。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _KinectGestureSettings  
{  
    KinectGestureSettings_None = 0,  
    KinectGestureSettings_Tap = 0x1,  
    KinectGestureSettings_ManipulationTranslateX = 0x40,  
    KinectGestureSettings_ManipulationTranslateY = 0x80,  
    KinectGestureSettings_ManipulationTranslateRailsX = 0x100,  
    KinectGestureSettings_ManipulationTranslateRailsY = 0x200,  
    KinectGestureSettings_ManipulationScale = 0x800,  
    KinectGestureSettings_ManipulationTranslateInertia = 0x1000,  
    KinectGestureSettings_KinectHold = 0x10000  
} KinectGestureSettings, KinectGestureSettings_None, KinectGestureSettings_Tap, KinectGestureSettings_ManipulationTranslateX, KinectGestureSettings_ManipulationTranslateY, KinectGestureSettings_ManipulationTranslateRailsX, KinectGestureSettings_ManipulationTranslateRailsY, KinectGestureSettings_ManipulationScale, KinectGestureSettings_ManipulationTranslateInertia, KinectGestureSettings_KinectHold;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EXB"></span>

Constants  
=========  

| Constant                                            | Description                                                                                                                                                                                                                                                                                     |
|-----------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| KinectGestureSettings\_None                         | 無効。                                                                                                                                                                                                                                                 |
| KinectGestureSettings\_Tap                          | タップ。                                                                                                                                                                                                                                                             |
| KinectGestureSettings\_ManipulationTranslateX       | 水平方向(X軸方向)のスライド。<br/>ManipulationStarted、ManipulationUpdated、ManipulationCompletedのイベントが発生します。                      |
| KinectGestureSettings\_ManipulationTranslateY       | 垂直方向(Y軸方向)のスライド。<br/>ManipulationStarted、ManipulationUpdated、ManipulationCompletedのイベントが発生します。                        |
| KinectGestureSettings\_ManipulationTranslateRailsX  | 水平方向(X軸方向)に沿ったスライド。<br/>ManipulationStarted、ManipulationUpdated、ManipulationCompletedのイベントが発生します。 |
| KinectGestureSettings\_ManipulationTranslateRailsY  | 垂直方向(Y軸方向)に沿ったスライド。<br/>ManipulationStarted、ManipulationUpdated、ManipulationCompletedのイベントが発生します。   |
| KinectGestureSettings\_ManipulationScale            | ピンチイン・ピンチアウト。<br/>ManipulationStarted、ManipulationUpdated、ManipulationCompletedのイベントが発生します。     |
| KinectGestureSettings\_ManipulationTranslateInertia | ピンチイン・ピンチアウトの慣性スケーリング。<br/>ManipulationStarted、ManipulationUpdated、ManipulationCompletedのイベントが発生します。                                                                                                               |
| KinectGestureSettings\_KinectHold                   | プレス。<br/>プレスしたまま時間閾値を超えたときにはホールディングのイベントが発生します。                                           |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectGestureSettings Enumeration
RLTitle : KinectGestureSettings Enumeration
KeywordK : KinectGestureSettings enumeration
HelpPriority : 2
KeywordF : KinectGestureSettings
KeywordF : Microsoft.Kinect.kinect.KinectGestureSettings
KeywordA : T:Microsoft.Kinect.kinect.KinectGestureSettings
AssetID : T:Microsoft.Kinect.kinect.KinectGestureSettings
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectGestureSettings
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
