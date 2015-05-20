HandState 列挙体  
=====================  

手の状態を表す。
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
<td align="left"><pre><code>public enum class HandState</code></pre></td>
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
<td align="left"><pre><code>public enum HandState</code></pre></td>
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
<td align="left"><pre><code>var handState = WindowsPreview.Kinect.HandState.closed;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EWB"></span>

メンバ
=======  

| メンバ         | 値 | 説明                       |
|----------------|-------|-----------------------------------|
| **Closed**     | 3     | 閉じている(グーの状態)               |
| **Lasso**      | 4     | 投げなわのポーズ(チョキの状態)   |
| **NotTracked** | 1     | 手を追跡していない。        |
| **Open**       | 2     | 開いている(パーの状態)                 |
| **Unknown**    | 0     | 不明 |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E4B"></span>

See also  
========  

<span id="ID4E6B"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : HandState Enumeration
RLTitle : HandState Enumeration
KeywordK : HandState enumeration
KeywordK : WindowsPreview.Kinect.HandState enumeration
HelpPriority : 2
KeywordF : WindowsPreview.Kinect.HandState
KeywordF : HandState
KeywordF : WindowsPreview.Kinect.HandState
KeywordA : T:WindowsPreview.Kinect.HandState
AssetID : T:WindowsPreview.Kinect.HandState
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.HandState
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
