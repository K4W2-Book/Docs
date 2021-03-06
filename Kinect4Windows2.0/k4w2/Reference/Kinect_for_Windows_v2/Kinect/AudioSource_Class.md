AudioSource クラス  
=================  

オーディオフレームソースを表す。
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
<td align="left"><pre><code>public ref class AudioSource sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class AudioSource : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var audioSource = WindowsPreview.Kinect.AudioSource;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**AudioSource** has the following members.  

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
<td align="left"><a href="AudioSource_Class/Properties/AudioBeams_Property.md">AudioBeams</a></td>
<td align="left">オーディオビーム(複数)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioSource_Class/Properties/AudioCalibrationState.md">AudioCalibrationState</a></td>
<td align="left"><!--Gets a value that indicates whether or not the Kinect Sensor is properly calibrated to listen for audio. This API is not implemented in the Kinect for Windows v2 SDK and will always return Calibrated. It is included to support cross-compilation with the Xbox SDK.-->
このプロパティはXbox SDKとのクロスコンパイルのために含まれています。Kinect for Windows v2では実装おらず、常にCalibratedが返ります。
</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioSource_Class/Properties/IsActive_Property.md">IsActive</a></td>
<td align="left">オーディオソースの動作状態を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioSource_Class/Properties/KinectSensor_Property.md">KinectSensor</a></td>
<td align="left">このオーディオソースのKinectセンサーを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioSource_Class/Properties/MaxSubFrameCount_Property.md">MaxSubFrameCount</a></td>
<td align="left">サブフレームの最大数を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioSource_Class/Properties/SubFrameDuration_Property.md">SubFrameDuration</a></td>
<td align="left">サブフレームの時間を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="AudioSource_Class/Properties/SubFrameLengthInBytes.md">SubFrameLengthInBytes</a></td>
<td align="left">バイト単位でのサブフレームのデータ長を取得する。</td>
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
<td align="left"><a href="AudioSource_Class/Methods/OpenReader_Method.md">OpenReader</a></td>
<td align="left">オーディオリーダーを開く。</td>
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
<td align="left"><a href="AudioSource_Class/Events/FrameCaptured_Event.md">FrameCaptured</a></td>
<td align="left">フレームが更新されたことを通知するイベント。</td>
</tr>
<tr class="even">
<td align="left"><a href="AudioSource_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left"><a href="">AudioSource</a> クラスのプロパティが変更されたことを通知するイベント。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EZ"></span>

See also  
========  

<span id="ID4E2"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AudioSource Class
RLTitle : AudioSource Class
KeywordK : AudioSource class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.AudioSource
KeywordF : AudioSource
KeywordF : WindowsPreview.Kinect.AudioSource
KeywordA : T:WindowsPreview.Kinect.AudioSource
AssetID : T:WindowsPreview.Kinect.AudioSource
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.AudioSource
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
