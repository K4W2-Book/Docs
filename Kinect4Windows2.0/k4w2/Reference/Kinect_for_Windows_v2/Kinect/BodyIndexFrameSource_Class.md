BodyIndexFrameSource クラス  
==========================  

Kinectセンサーからのボディインデックスのソースを表す。
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
<td align="left"><pre><code>public ref class BodyIndexFrameSource sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class BodyIndexFrameSource : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var bodyIndexFrameSource = WindowsPreview.Kinect.BodyIndexFrameSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**BodyIndexFrameSource** has the following members.  

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
<td align="left"><a href="BodyIndexFrameSource_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">ボディインデックスフレームの情報を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyIndexFrameSource_Class/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">ボディインデックスソースの動作状態を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="BodyIndexFrameSource_Class/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">このボディインデックスソースのKinetセンサーを取得する。</td>
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
<td align="left"><a href="BodyIndexFrameSource_Class/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">ボディインデックスフレームリーダーを作成する。</td>
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
<td align="left"><a href="BodyIndexFrameSource_Class/Events/FrameCaptured_Event.md">FrameCaptured</a></td>
<td align="left">ボディインデックスのデータ更新を通知するイベント。</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyIndexFrameSource_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left"><a href="">BodyIndexFrameSource</a>クラスのプロパティが変更されたことを通知するイベント。</td>
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
TOCTitle : BodyIndexFrameSource Class
RLTitle : BodyIndexFrameSource Class
KeywordK : BodyIndexFrameSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.BodyIndexFrameSource
KeywordF : BodyIndexFrameSource
KeywordF : WindowsPreview.Kinect.BodyIndexFrameSource
KeywordA : T:WindowsPreview.Kinect.BodyIndexFrameSource
AssetID : T:WindowsPreview.Kinect.BodyIndexFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyIndexFrameSource
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
