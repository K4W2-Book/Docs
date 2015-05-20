DepthFrame クラス  
================  

Depthフレームを表す。Depthフレームからはミリメートル単位でピクセルごとの距離データが取得できる。 
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
<td align="left"><pre><code>public ref class DepthFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class DepthFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var depthFrame = WindowsPreview.Kinect.DepthFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**DepthFrame** has the following members.  

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
<td align="left"><a href="DepthFrame_Class/Properties/DepthFrameSource_Property.md">DepthFrameSource</a></td>
<td align="left">このフレームのDepthフレームソースを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="DepthFrameSource_Class/Properties/DepthMaxReliableDistance.md">DepthMaxReliableDistance</a></td>
<td align="left">ミリメートル単位での最大Depth認識距離を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="DepthFrameSource_Class/Properties/DepthMinReliableDistance.md">DepthMinReliableDistance</a></td>
<td align="left">ミリメートル単位での最小Depth認識距離を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="DepthFrameSource_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">フレーム情報を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="DepthFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">フレームの相対時間を取得する。</td>
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
<td align="left"><a href="DepthFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">Depthフレームのリソースを解放する。</td>
</tr>
<tr class="even">
<td align="left"><a href="DepthFrame_Class/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Depthフレームのデータを配列にコピーする。</td>
</tr>
<tr class="odd">
<td align="left"><a href="DepthFrame_Class/Methods/CopyFrameDataToBuffer_Method.md">CopyFrameDataToBuffer</a></td>
<td align="left">Depthフレームのデータのメモリ位置をバッファにコピーする。</td>
</tr>
<tr class="even">
<td align="left"><a href="DepthFrame_Class/Methods/LockImageBuffer_Method.md">LockImageBuffer</a></td>
<td align="left">システムで管理しているDepthフレームデータバッファをロックする。</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The data for this frame is stored as 16-bit unsigned integers, where each value represents the distance in millimeters. The maximum depth distance is 8 meters, although reliability starts to degrade at around 4.5 meters. Developers can use the depth frame to build custom tracking algorithms in cases where the [BodyFrame](BodyFrame_Class.md) isn’t enough.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EFB"></span>

See also  
========  

<span id="ID4EHB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : DepthFrame Class
RLTitle : DepthFrame Class
KeywordK : DepthFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.DepthFrame
KeywordF : DepthFrame
KeywordF : WindowsPreview.Kinect.DepthFrame
KeywordA : T:WindowsPreview.Kinect.DepthFrame
AssetID : T:WindowsPreview.Kinect.DepthFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.DepthFrame
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
