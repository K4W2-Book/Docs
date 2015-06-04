IKinectSensor Interface  
=======================  

Kinectセンサー。 <span id="syntaxSection"></span>

Syntax  
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
<td align="left"><pre><code>interface IKinectSensor : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IKinectSensor**は以下のメンバー関数を持ちます。  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/Close_Method.md">Close</a></td>
<td align="left">Kinectセンサーのストリームを閉じる。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_AudioSource_Method.md">get_AudioSource</a></td>
<td align="left">AudioのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_BodyFrameSource_Method.md">get_BodyFrameSource</a></td>
<td align="left">BodyフレームのSourceを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_BodyIndexFrameSource.md">get_BodyIndexFrameSource</a></td>
<td align="left">BodyIndexフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_ColorFrameSource_Method.md">get_ColorFrameSource</a></td>
<td align="left">ColorフレームのSourceを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_CoordinateMapper_Method.md">get_CoordinateMapper</a></td>
<td align="left">Coordinate Mapperを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_DepthFrameSource_Method.md">get_DepthFrameSource</a></td>
<td align="left">DepthフレームのSourceを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_InfraredFrameSource.md">get_InfraredFrameSource</a></td>
<td align="left">InfraredフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_IsAvailable_Method.md">get_IsAvailable</a></td>
<td align="left">Kinectセンサーが利用可能であるかを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_IsOpen_Method.md">get_IsOpen</a></td>
<td align="left">Kinectセンサーがストリームを開いているかを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_KinectCapabilities.md">get_KinectCapabilities</a></td>
<td align="left">Kinectセンサーがサポートする機能を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/get.md">get_LongExposureInfraredFrameSource</a></td>
<td align="left">長時間露光InfraredフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/get_UniqueKinectId_Method.md">get_UniqueKinectId</a></td>
<td align="left">KinectセンサーのユニークIDを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/GetIsAvailableChangedEvent.md">GetIsAvailableChangedEventData</a></td>
<td align="left">Kinectセンサーが変更されたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/Open_Method.md">Open</a></td>
<td align="left">Kinectセンサーのストリームを開く。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/OpenMultiSourceFrameReader.md">OpenMultiSourceFrameReader</a></td>
<td align="left">MultiSourceフレームのReaderを開く。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IKinectSensor_Interface/Methods/SubscribeIsAvailableChanged.md">SubscribeIsAvailableChanged</a></td>
<td align="left">Kinectセンサーが変更されたときに発効するイベントハンドルを登録する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IKinectSensor_Interface/Methods/UnsubscribeIsAvailableChan.md">UnsubscribeIsAvailableChanged</a></td>
<td align="left">Kinectセンサーが変更されたときに発効するイベントハンドルを解除する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IKinectSensor Interface
RLTitle : IKinectSensor Interface
KeywordK : IKinectSensor interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IKinectSensor
KeywordF : Microsoft.Kinect.kinect.IKinectSensor
KeywordA : T:Microsoft.Kinect.kinect.IKinectSensor
AssetID : T:Microsoft.Kinect.kinect.IKinectSensor
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
