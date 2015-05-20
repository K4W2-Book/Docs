FrameSourceTypes 列挙体  
============================  

MultiSourceReaderで取得するフレームを表す。
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
public enum class FrameSourceTypes</code></pre></td>
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
public enum FrameSourceTypes</code></pre></td>
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
<td align="left"><pre><code>var frameSourceTypes = WindowsPreview.Kinect.FrameSourceTypes.audio;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ERC"></span>

メンバ
=======  

| メンバ                   | 値 | 説明                           |
|--------------------------|-------|---------------------------------------|
| **Audio**                | 64    | オーディオストリーム                 |
| **Body**                 | 32    | ボディストリーム                   |
| **BodyIndex**            | 16    | ボディインデックスストリーム             |
| **Color**                | 1     | カラーストリーム                  |
| **Depth**                | 8     | Depthストリーム                  |
| **Infrared**             | 2     | 赤外線ストリーム               |
| **LongExposureInfrared** | 4     | 長時間露光赤外線ストリーム |
| **None**                 | 0     | なし                            |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EYC"></span>

See also  
========  

<span id="ID4E1C"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FrameSourceTypes Enumeration
RLTitle : FrameSourceTypes Enumeration
KeywordK : FrameSourceTypes enumeration
KeywordK : WindowsPreview.Kinect.FrameSourceTypes enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.FrameSourceTypes
KeywordF : FrameSourceTypes
KeywordF : WindowsPreview.Kinect.FrameSourceTypes
KeywordA : T:WindowsPreview.Kinect.FrameSourceTypes
AssetID : T:WindowsPreview.Kinect.FrameSourceTypes
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.FrameSourceTypes
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
