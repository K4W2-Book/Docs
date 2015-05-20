BodyIndexFrame クラス  
====================  

ピクセル単位での人の位置を示すボディインデックスのフレーム。
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
<td align="left"><pre><code>public ref class BodyIndexFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class BodyIndexFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var bodyIndexFrame = WindowsPreview.Kinect.BodyIndexFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**BodyIndexFrame** has the following members.  

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
<td align="left"><a href="BodyIndexFrame_Class/Properties/BodyIndexFrameSource.md">BodyIndexFrameSource</a></td>
<td align="left">このボディインデックスフレームのソースを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyIndexFrame_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">ボディインデックスフレームの情報を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="BodyIndexFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
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
<td align="left"><a href="BodyIndexFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">システムリソースを解放する。</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyIndexFrame_Class/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">ボディインデックスデータを配列にコピーする。</td>
</tr>
<tr class="odd">
<td align="left"><a href="BodyIndexFrame_Class/Methods/CopyFrameDataToBuffer_Method.md">CopyFrameDataToBuffer</a></td>
<td align="left">ボディインデックスデータをメモリ位置をコピーする。</td>
</tr>
<tr class="even">
<td align="left"><a href="BodyIndexFrame_Class/Methods/LockImageBuffer_Method.md">LockImageBuffer</a></td>
<td align="left">システムで管理しているボディインデックスデータを取得する。</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

The pixel values in this frame are 8-bit unsigned integers, where 0-5 map directly to the BodyData index in the [BodyFrame](BodyFrame_Class.md). Values greater than the value obtained from [BodyCount](BodyFrameSource_Class/Properties/BodyCount_Property.md) indicate the pixel is part of the background, not associated with a tracked body. This frame is useful for green screening applications, or any scenario where you want to display the silhouette of the user. It also provides a good starting bounds for custom depth algorithms.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4EIB"></span>

See also  
========  

<span id="ID4EKB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : BodyIndexFrame Class
RLTitle : BodyIndexFrame Class
KeywordK : BodyIndexFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.BodyIndexFrame
KeywordF : BodyIndexFrame
KeywordF : WindowsPreview.Kinect.BodyIndexFrame
KeywordA : T:WindowsPreview.Kinect.BodyIndexFrame
AssetID : T:WindowsPreview.Kinect.BodyIndexFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.BodyIndexFrame
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
