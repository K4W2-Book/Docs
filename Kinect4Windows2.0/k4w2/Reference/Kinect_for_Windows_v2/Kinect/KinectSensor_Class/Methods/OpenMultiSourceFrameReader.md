KinectSensor.OpenMultiSourceFrameReader Method  
==============================================  

マルチフレームリーダーを開く。
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
<td align="left"><pre><code>public:  
<a href="../../MultiSourceFrameReader_Class.md">MultiSourceFrameReader</a>^ OpenMultiSourceFrameReader(  
         <a href="../../FrameSourceTypes_Enumeration.md">FrameSourceTypes</a> enabledFrameSourceTypes  
)</code></pre></td>
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
<td align="left"><pre><code>public <a href="../../MultiSourceFrameReader_Class.md">MultiSourceFrameReader</a>OpenMultiSourceFrameReader (  
         <a href="../../FrameSourceTypes_Enumeration.md">FrameSourceTypes</a> enabledFrameSourceTypes  
)</code></pre></td>
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
<td align="left"><pre><code>var multiSourceFrameReader = kinectSensor.openMultiSourceFrameReader(enabledFrameSourceTypes);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EJ"></span>
#### 引数  

*enabledFrameSourceTypes*    
型: [FrameSourceTypes](../../FrameSourceTypes_Enumeration.md)  
 取得するフレームの種別

<span id="ID4ES"></span>
#### 戻り値  

型: [MultiSourceFrameReader](../../MultiSourceFrameReader_Class.md)  
新しいマルチフレームリーダー

<span id="remarks"></span>

Remarks  
=======  

*enabledFrameSourceTypes*で取り込むフレームを選択できます。  

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Value</th>
<th align="left">Meaning</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">FrameSourceTypes::Color</td>
<td align="left">MultiSourceFrameReaderでカラーフレームを取り込む。 
<div class="alert">
<table>
<thead>
<tr class="header">
<th align="left"><img src="../../../../../../resources/note.gif" />Note</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">MultiSourceFrameReader will align to the slowest framerate of any subscribed source. In lowlight scenarios, the color stream may drop to 15 FPS. If this happens, and MultiSourceFrameReader is subscribed to color as one of its subscribed sources, the rate of delivered frames will drop to 15 FPS for the entire instance of this MultiSourceFrameReader</td>
</tr>
</tbody>
</table>
</div></td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes::Infrared</td>
<td align="left">MultiSourceFrameReaderで赤外線フレームを取り込む。</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes::Audio</td>
<td align="left">MultiSourceFrameReaderは音声フレームをサポートしません。この値を設定するとメソッドは失敗します。</td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes::LongExposureInfrared</td>
<td align="left">MultiSourceFrameReaderで長時間露光赤外線フレームを取り込む。</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes::Depth</td>
<td align="left">MultiSourceFrameReaderでDepthフレームを取り込む。</td>
</tr>
<tr class="even">
<td align="left">FrameSourceTypes::BodyIndex</td>
<td align="left">MultiSourceFrameReaderでボディインデックスフレームを取り込む。</td>
</tr>
<tr class="odd">
<td align="left">FrameSourceTypes::Body</td>
<td align="left">MultiSourceFrameReaderでボディフレームを取り込む。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EPD"></span>

See also  
========  

<span id="ID4ERD"></span>
#### Reference  

[KinectSensor Class](../../KinectSensor_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OpenMultiSourceFrameReader Method
RLTitle : KinectSensor.OpenMultiSourceFrameReader Method
KeywordK : OpenMultiSourceFrameReader method
KeywordK : KinectSensor.OpenMultiSourceFrameReader method
KeywordF : WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader
KeywordF : KinectSensor.OpenMultiSourceFrameReader
KeywordF : OpenMultiSourceFrameReader
KeywordF : WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader(WindowsPreview.Kinect.FrameSourceTypes)
KeywordA : M:WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader(WindowsPreview.Kinect.FrameSourceTypes)
AssetID : M:WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader(WindowsPreview.Kinect.FrameSourceTypes)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.KinectSensor.OpenMultiSourceFrameReader
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
