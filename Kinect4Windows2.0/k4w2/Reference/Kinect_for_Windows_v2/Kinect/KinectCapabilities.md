KinectCapabilities 列挙体  
==============================  

Kinectセンサーが提供する機能。
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
public enum class KinectCapabilities</code></pre></td>
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
public enum KinectCapabilities</code></pre></td>
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
<td align="left"><pre><code>var kinectCapabilities = WindowsPreview.Kinect.KinectCapabilities.audio;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EDC"></span>

メンバ
=======  

| メンバ          | 値 | 説明                      |
|-----------------|-------|----------------------------------|
| **Audio**       | 2     | オーディオをサポートしている。              |
| **Expressions** | 8     | 表情推定をサポートしている。       |
| **Face**        | 4     | 顔検出をサポートしてる。 |
| **Gamechat**    | 16    | ゲームチャットをサポートしている。          |
| **None**        | 0     | どの機能もさぽーとしていない。   |
| **Vision**      | 1     | ビジョン(画像系)をサポートしている。            |

<span id="remarks"></span>

Remarks  
=======  

A title declares these capabilities in the **mx:Capability** element in its application manifest file.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4ESC"></span>

See also  
========  

<span id="ID4EUC"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectCapabilities Enumeration
RLTitle : KinectCapabilities Enumeration
KeywordK : KinectCapabilities enumeration
KeywordK : WindowsPreview.Kinect.KinectCapabilities enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.KinectCapabilities
KeywordF : KinectCapabilities
KeywordF : WindowsPreview.Kinect.KinectCapabilities
KeywordA : T:WindowsPreview.Kinect.KinectCapabilities
AssetID : T:WindowsPreview.Kinect.KinectCapabilities
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectCapabilities
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
