KinectSensor クラス  
==================  


Kinectセンサーデバイスを表す。
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
<td align="left"><pre><code>public ref class KinectSensor sealed : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>public sealed class KinectSensor : <a href="../Data/INotifyPropertyChanged.md">INotifyPropertyChanged</a></code></pre></td>
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
<td align="left"><pre><code>var kinectSensor = WindowsPreview.Kinect.KinectSensor;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**KinectSensor** has the following members.  

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
<td align="left"><a href="KinectSensor_Class/Properties/AudioSource_Property.md">AudioSource</a></td>
<td align="left">オーディオフレームのソースを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/BodyFrameSource_Property.md">BodyFrameSource</a></td>
<td align="left">ボディフレームのソースを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/BodyIndexFrameSource.md">BodyIndexFrameSource</a></td>
<td align="left">ボディインデックスフレームのソースを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/ColorFrameSource_Property.md">ColorFrameSource</a></td>
<td align="left">カラーフレームのソースを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/CoordinateMapper_Property.md">CoordinateMapper</a></td>
<td align="left">座標変換オブジェクトを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/DepthFrameSource_Property.md">DepthFrameSource</a></td>
<td align="left">Depthフレームのソースを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/InfraredFrameSource_Property.md">InfraredFrameSource</a></td>
<td align="left">赤外線フレームのソースを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/IsAvailable_Property.md">IsAvailable</a></td>
<td align="left">Kinectの接続状態を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/IsOpen_Property.md">IsOpen</a></td>
<td align="left">Kinectセンサーが開かれているかどうか(実行状態)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/KinectCapabilities_Property.md">KinectCapabilities</a></td>
<td align="left">Kinectセンサーが提供できる機能を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/LongExposureInfraredFrameS.md">LongExposureInfraredFrameSource</a></td>
<td align="left">長時間露光赤外線フレームのソースを取得する。</td>
</tr>

<!-- いまはない
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Properties/Sensors_Property.md">Sensors</a></td>
<td align="left">利用可能なKinectセンサーのリストを取得する。</td>
</tr>
-->

<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Properties/UniqueKinectId_Property.md">UniqueKinectId</a></td>
<td align="left">Kinectセンサーの一意のIDを取得する。</td>
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
<td align="left"><a href="KinectSensor_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Kinectセンサーの動作を停止する。</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Methods/GetDefault_Method.md">GetDefault</a></td>
<td align="left">既定のKinectSensorクラスのインスタンスを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="KinectSensor_Class/Methods/Open_Method.md">Open</a></td>
<td align="left">Kinectの動作を開始する。</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Methods/OpenMultiSourceFrameReader.md">OpenMultiSourceFrameReader</a></td>
<td align="left">MultiSourceFrameReaderを開く。</td>
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
<td align="left"><a href="KinectSensor_Class/Events/IsAvailableChanged_Event.md">IsAvailableChanged</a></td>
<td align="left">Kinectが物理的にコンピュータに接続された/抜かれた時に発生するイベント。</td>
</tr>
<tr class="even">
<td align="left"><a href="KinectSensor_Class/Events/PropertyChanged_Event.md">PropertyChanged</a></td>
<td align="left"><a href="">KinectSensor</a>クラスのプロパティが変更されたときに発生するイベント</td>
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
TOCTitle : KinectSensor Class
RLTitle : KinectSensor Class
KeywordK : KinectSensor class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.KinectSensor
KeywordF : KinectSensor
KeywordF : WindowsPreview.Kinect.KinectSensor
KeywordA : T:WindowsPreview.Kinect.KinectSensor
AssetID : T:WindowsPreview.Kinect.KinectSensor
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectSensor
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
