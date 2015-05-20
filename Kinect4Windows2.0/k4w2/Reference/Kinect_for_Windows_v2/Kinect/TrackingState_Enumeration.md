TrackingState 列挙体  
=========================  

関節などBodyに関連するものの追跡状態
<span id="syntaxSection"></span>

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
<td align="left"><pre><code>public enum class TrackingState</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public enum TrackingState</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var trackingState = WindowsPreview.Kinect.TrackingState.inferred;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EIB"></span>

メンバ
=======  

| メンバ         | 値 | 説明                                                                                      |
|----------------|-------|--------------------------------------------------------------------------------------------------|
| **Inferred**   | 1     | 関節データは推測状態。追跡精度は低い。 |
| **NotTracked** | 0     | 追跡していない状態。データはない。                             |
| **Tracked**    | 2     | 追跡している状態。データ精度は高い                                     |

<span id="remarks"></span>

Remarks  
=======  

A tracked joint that cannot be seen by the camera is inferred. That is, the joint position is calculated from surrounding joint data rather than captured by the camera.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EUB"></span>

See also  
========  

<span id="ID4EWB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : TrackingState Enumeration
RLTitle : TrackingState Enumeration
KeywordK : TrackingState enumeration
KeywordK : WindowsPreview.Kinect.TrackingState enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.TrackingState
KeywordF : TrackingState
KeywordF : WindowsPreview.Kinect.TrackingState
KeywordA : T:WindowsPreview.Kinect.TrackingState
AssetID : T:WindowsPreview.Kinect.TrackingState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.TrackingState
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
