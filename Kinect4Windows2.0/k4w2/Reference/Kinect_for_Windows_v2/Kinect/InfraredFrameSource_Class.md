InfraredFrameSource クラス 
=========================  

KinectSensorからの赤外線フレームを表す。 
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
<td align="left"><pre><code>public ref class InfraredFrameSource sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class InfraredFrameSource : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var infraredFrameSource = WindowsPreview.Kinect.InfraredFrameSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**InfraredFrameSource** has the following members.  

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
<td align="left"><a href="InfraredFrameSource_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">フレーム情報を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrameSource_Class/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">赤外線フレームの動作状況を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="InfraredFrameSource_Class/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">この赤外線フレームのKinectセンサーをしゅとくする。</td>
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
<td align="left"><a href="InfraredFrameSource_Class/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">赤外線フレームリーダーを開く。</td>
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
<td align="left"><a href="InfraredFrameSource_Class/Events/FrameCaptured_Event.md">FrameCaptured</a></td>
<td align="left">新しいフレームが来たことを通知するイベント。</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrameSource_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left"><a href="">InfraredFrameSource</a> クラスのプロパティが変更されたことを通知するイベント。</td>
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
TOCTitle : InfraredFrameSource Class
RLTitle : InfraredFrameSource Class
KeywordK : InfraredFrameSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.InfraredFrameSource
KeywordF : InfraredFrameSource
KeywordF : WindowsPreview.Kinect.InfraredFrameSource
KeywordA : T:WindowsPreview.Kinect.InfraredFrameSource
AssetID : T:WindowsPreview.Kinect.InfraredFrameSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.InfraredFrameSource
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
