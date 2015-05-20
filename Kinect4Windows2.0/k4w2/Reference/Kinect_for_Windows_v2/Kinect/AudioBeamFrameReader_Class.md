AudioBeamFrameReader クラス
==========================  

オーディオビームリーダーを表す。
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
<td align="left"><pre><code>public ref class AudioBeamFrameReader sealed : IClosable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class AudioBeamFrameReader : IDisposable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var audioBeamFrameReader = WindowsPreview.Kinect.AudioBeamFrameReader;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**AudioBeamFrameReader** has the following members.  

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
<td align="left"><a href="AudioBeamFrameReader_Class/Properties/AudioSource_Property.md">AudioSource</a></td>
<td align="left">オーディオフレームソースを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamFrameReader_Class/Properties/IsPaused_Property.md">IsPaused</a></td>
<td align="left">オーディオリーダーの動作状態を取得する。</td>
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
<td align="left"><a href="AudioBeamFrameReader_Class/Methods/AcquireLatestBeamFrames.md">AcquireLatestBeamFrames</a></td>
<td align="left">最新のオーディオビームフレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamFrameReader_Class/Methods/Close_Method.md">Close</a></td>
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
<td align="left"><a href="AudioBeamFrameReader_Class/Events/FrameArrived_Event.md">FrameArrived</a></td>
<td align="left">フレームが更新されたことを通知するイベント。</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioBeamFrameReader_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left"><a href="">AudioBeamFrameReader</a> クラスのプロパティが変更されたことを通知するイベント。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E3"></span>

See also  
========  

<span id="ID4E5"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AudioBeamFrameReader Class
RLTitle : AudioBeamFrameReader Class
KeywordK : AudioBeamFrameReader class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReader
KeywordF : AudioBeamFrameReader
KeywordF : WindowsPreview.Kinect.AudioBeamFrameReader
KeywordA : T:WindowsPreview.Kinect.AudioBeamFrameReader
AssetID : T:WindowsPreview.Kinect.AudioBeamFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioBeamFrameReader
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
