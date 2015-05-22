FaceFrameReader クラス  
=====================  

FaceフレームのReader。
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
<td align="left"><pre><code>public ref class FaceFrameReader sealed : IClosable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class FaceFrameReader : IDisposable, <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var faceFrameReader = Microsoft.Kinect.Face.FaceFrameReader;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**FaceFrameReader** has the following members.  

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
<td align="left"><a href="FaceFrameReader_Class/Properties/FaceFrameSource_Property.md">FaceFrameSource</a></td>
<td align="left">FaceフレームのSourceを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="FaceFrameReader_Class/Properties/IsPaused_Property.md">IsPaused</a></td>
<td align="left">FaceフレームのReaderの動作状態を取得する。</td>
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
<td align="left"><a href="FaceFrameReader_Class/Methods/AcquireLatestFrame_Method.md">AcquireLatestFrame</a></td>
<td align="left">最新のFaceフレームを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="FaceFrameReader_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">FaceFrameReaderを閉じる。</td>
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
<td align="left"><a href="FaceFrameReader_Class/Events/FrameArrived_Event.md">FrameArrived</a></td>
<td align="left">Faceフレームの更新イベント</td>
</tr>
<tr class="even">
<td align="left"><a href="FaceFrameReader_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left"><a href="">FaceFrameReader</a>クラスのプロパティが変更されたことを通知するイベント。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4E4"></span>

See also  
========  

<span id="ID4E6"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceFrameReader Class
RLTitle : FaceFrameReader Class
KeywordK : FaceFrameReader class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Face.FaceFrameReader
KeywordF : FaceFrameReader
KeywordF : Microsoft.Kinect.Face.FaceFrameReader
KeywordA : T:Microsoft.Kinect.Face.FaceFrameReader
AssetID : T:Microsoft.Kinect.Face.FaceFrameReader
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceFrameReader
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
