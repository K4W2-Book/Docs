InfraredFrame クラス
===================  

<!--Represents a frame that provides a view of the scene that looks just like a black and white photograph, but is actively lit, so brightness is consistent regardless of location and room brightness.--> 
赤外線画像のフレームを表します。赤外線フレームで取得できる画像は、明るさに関係ない白黒写真のような画像となります。
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
<td align="left"><pre><code>public ref class InfraredFrame sealed : IClosable</code></pre></td>
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
<td align="left"><pre><code>public sealed class InfraredFrame : IDisposable</code></pre></td>
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
<td align="left"><pre><code>var infraredFrame = WindowsPreview.Kinect.InfraredFrame;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**InfraredFrame** has the following members.  

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
<td align="left"><a href="InfraredFrame_Class/Properties/FrameDescription_Property.md">FrameDescription</a></td>
<td align="left">フレームの情報を取得する</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrame_Class/Properties/InfraredFrameSource_Property.md">InfraredFrameSource</a></td>
<td align="left">赤外線フレームのソースを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="InfraredFrame_Class/Properties/RelativeTime_Property.md">RelativeTime</a></td>
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
<td align="left"><a href="InfraredFrame_Class/Methods/Close_Method.md">Close</a></td>
<td align="left">システムリソースを解放する。</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrame_Class/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">赤外線フレームデータを配列にコピーする。</td>
</tr>
<tr class="odd">
<td align="left"><a href="InfraredFrame_Class/Methods/CopyFrameDataToBuffer_Method.md">CopyFrameDataToBuffer</a></td>
<td align="left">赤外線フレームデータのメモリ位置をコピーする。</td>
</tr>
<tr class="even">
<td align="left"><a href="InfraredFrame_Class/Methods/LockImageBuffer_Method.md">LockImageBuffer</a></td>
<td align="left">システムで管理しているバッファを取得する。</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

備考  
=======  

赤外線フレームは、顔認識などのテクスチャが重要なコンピュータビジョンアルゴリズムに最適です。データは16ビットの符号なし整数として格納されます。赤外線フレームは、反射マーカーを追跡し、低リターン（ジッタ）のDepthのピクセルをフィルタリング、緑のスクリーニングにも最適です。赤外線フレームはDepthと同じセンサーから導出されるので、座標は同じになります。。たとえば、5行9列の赤外線データは5行9列のDepthピクセルになります。

<!--The infrared frame is great for computer vision algorithms where texture is important, such as facial recognition. Data is stored as 16-bit unsigned integers. The infrared frame is also great for green screening, tracking reflective markers, and filtering out low-return (and therefore jittery) depth pixels. Note that the infrared frame is derived from the same sensor as depth, so the images are perfectly aligned. For example, the infrared pixel at row 5 col 9 goes with the depth pixel at row 5 col 9.-->  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[WindowsPreview.Kinect Namespace](../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : InfraredFrame Class
RLTitle : InfraredFrame Class
KeywordK : InfraredFrame class, about
HelpPriority : 2
TopicType : apiref
KeywordF : WindowsPreview.Kinect.InfraredFrame
KeywordF : InfraredFrame
KeywordF : WindowsPreview.Kinect.InfraredFrame
KeywordA : T:WindowsPreview.Kinect.InfraredFrame
AssetID : T:WindowsPreview.Kinect.InfraredFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.InfraredFrame
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
