ColorFrame クラス  
================  

カラーフレームを表します。
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
<td align="left"><pre><code>public ref class ColorFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class ColorFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var colorFrame = WindowsPreview.Kinect.ColorFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**ColorFrame** has the following members.  

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
<td align="left"><a href="ColorFrame_Class/Properties/ColorCameraSettings_Property.md">ColorCameraSettings</a></td>
<td align="left">カラーカメラの設定を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Properties/ColorFrameSource_Property.md">ColorFrameSource</a></td>
<td align="left">このカラーフレームのソースを取得する</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">カラーフレームの情報を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Properties/RawColorImageFormat_Property.md">RawColorImageFormat</a></td>
<td align="left">カラーフレームデータのフォーマットを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
<td align="left">カラーフレームのタイムスタンプを取得する。</td>
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
<td align="left"><a href="ColorFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">カラーフレームのリソースを解放する。</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Methods/CopyConvertedFrameDataToAr.md">CopyConvertedFrameDataToArray</a></td>
<td align="left">生データを指定したフォーマットに変換して、配列にコピーする。</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Methods/CopyConvertedFrameDataToBu.md">CopyConvertedFrameDataToBuffer</a></td>
<td align="left">生データを指定したフォーマットに変換して、そのポインタをコピーする。</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Methods/CopyRawFrameDataToArray.md">CopyRawFrameDataToArray</a></td>
<td align="left">生データを配列にコピーする。</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Methods/CopyRawFrameDataToBuffer.md">CopyRawFrameDataToBuffer</a></td>
<td align="left">生データのポインタをコピーする。</td>
</tr>
<tr class="even">
<td align="left"><a href="ColorFrame_Class/Methods/CreateFrameDescription.md">CreateFrameDescription</a></td>
<td align="left">指定したフォーマットでのフレーム情報を作成する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="ColorFrame_Class/Methods/LockRawImageBuffer_Method.md">LockRawImageBuffer</a></td>
<td align="left">システムで使っているフレームバッファをロックする。</td>
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
TOCTitle : ColorFrame Class
RLTitle : ColorFrame Class
KeywordK : ColorFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.ColorFrame
KeywordF : ColorFrame
KeywordF : WindowsPreview.Kinect.ColorFrame
KeywordA : T:WindowsPreview.Kinect.ColorFrame
AssetID : T:WindowsPreview.Kinect.ColorFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.ColorFrame
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
