IColorFrame Interface  
=====================  

Colorフレーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IColorFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IColorFrame**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IColorFrame_Interface/Methods/AccessRawUnderlyingBuffer.md">AccessRawUnderlyingBuffer</a></td>
<td align="left">Colorフレームのデータを取得する。(ポインタ参照)</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrame_Interface/Methods/CopyConvertedFrameDataToAr.md">CopyConvertedFrameDataToArray</a></td>
<td align="left">フォーマット指定してColorフレームのデータを取得する。(コピー)</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrame_Interface/Methods/CopyRawFrameDataToArray.md">CopyRawFrameDataToArray</a></td>
<td align="left">ColorフレームのRAWデータを取得する。(コピー)</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrame_Interface/Methods/CreateFrameDescription.md">CreateFrameDescription</a></td>
<td align="left">フォーマットを指定してColorフレームの情報を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrame_Interface/Methods/get_ColorCameraSettings.md">get_ColorCameraSettings</a></td>
<td align="left">Colorカメラの設定を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrame_Interface/Methods/get_ColorFrameSource_Method.md">get_ColorFrameSource</a></td>
<td align="left">ColorフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrame_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Colorフレームの情報を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IColorFrame_Interface/Methods/get_RawColorImageFormat.md">get_RawColorImageFormat</a></td>
<td align="left">ColorフレームのRAWデータのフォーマットを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IColorFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Colorフレームを取得した時間(相対時間)を取得する。</td>
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
TOCTitle : IColorFrame Interface
RLTitle : IColorFrame Interface
KeywordK : IColorFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IColorFrame
KeywordF : Microsoft.Kinect.kinect.IColorFrame
KeywordA : T:Microsoft.Kinect.kinect.IColorFrame
AssetID : T:Microsoft.Kinect.kinect.IColorFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
