FrameEdges 列挙体  
======================  

ユーザーの体がカメラの画角から外れた位置を表す。 
<span id="syntaxSection"></span>

構文
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
<td align="left"><pre><code>[FlagsAttribute]  
public enum class FrameEdges</code></pre></td>
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
<td align="left"><pre><code>[FlagsAttribute]  
public enum FrameEdges</code></pre></td>
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
<td align="left"><pre><code>var frameEdges = WindowsPreview.Kinect.FrameEdges.bottom;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4E3B"></span>

メンバ
=======  

| メンバ     | 値 | 説明                                                                              |
|------------|-------|------------------------------------------------------------------------------------------|
| **Bottom** | 8     | ユーザーの下側がカメラの画角から外れている。                                |
| **Left**   | 2     | ユーザーの左側がカメラの画角から外れている。                       |
| **None**   | 0     | ユーザー全体がカメラの画角からhずれている。|
| **Right**  | 1     | ユーザーの右側がカメラの画角から外れている。                      |
| **Top**    | 4     | ユーザーの上側がカメラの画角から外れている。                               |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EDC"></span>

See also  
========  

<span id="ID4EFC"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameEdges Enumeration
RLTitle : FrameEdges Enumeration
KeywordK : FrameEdges enumeration
KeywordK : WindowsPreview.Kinect.FrameEdges enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.FrameEdges
KeywordF : FrameEdges
KeywordF : WindowsPreview.Kinect.FrameEdges
KeywordA : T:WindowsPreview.Kinect.FrameEdges
AssetID : T:WindowsPreview.Kinect.FrameEdges
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.FrameEdges
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
