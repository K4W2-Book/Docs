InfraredFrameReader クラス  
=========================  

赤外線フレームリーダーを表す。
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
<td align="left"><pre><code>public ref class InfraredFrameReader sealed : IClosable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class InfraredFrameReader : IDisposable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var infraredFrameReader = WindowsPreview.Kinect.InfraredFrameReader;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**InfraredFrameReader** has the following members.  

<span id="publicpropertiesSection"></span>

プロパティ  
==========  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">名前</th>
<th align="left">説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="InfraredFrameReader_Class/Properties/InfraredFrameSource_Property.md">InfraredFrameSource</a></td>
<td align="left">赤外線フレームソースを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrameReader_Class/Properties/IsPaused_Property.md">IsPaused</a></td>
<td align="left">赤外線フレームリーダーの動作状態を取得する。</td>
</tr>
</tbody>
</table>

<span id="publicmethodsSection"></span>

メソッド
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">名前</th>
<th align="left">説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="InfraredFrameReader_Class/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">最新の赤外線フレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrameReader_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">システムリソースを解放する。</td>
</tr>
</tbody>
</table>

<span id="publiceventsSection"></span>

イベント
======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">名前</th>
<th align="left">説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="InfraredFrameReader_Class/Events/FrameArrived_Event.md">FrameArrived</a></td>
<td align="left">フレームが更新されたことを通知するイベント。</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrameReader_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left"><a href="">InfraredFrameReader</a> クラスのプロパティが変更されたことを通知するイベント。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E6"></span>

See also  
========  

<span id="ID4EBB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : InfraredFrameReader Class
RLTitle : InfraredFrameReader Class
KeywordK : InfraredFrameReader class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.InfraredFrameReader
KeywordF : InfraredFrameReader
KeywordF : WindowsPreview.Kinect.InfraredFrameReader
KeywordA : T:WindowsPreview.Kinect.InfraredFrameReader
AssetID : T:WindowsPreview.Kinect.InfraredFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.InfraredFrameReader
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
