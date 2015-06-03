IInfraredFrame Interface  
========================  

Infraredフレーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IInfraredFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IInfraredFrame**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IInfraredFrame_Interface/Methods/AccessUnderlyingBuffer.md">AccessUnderlyingBuffer</a></td>
<td align="left">Infraredフレームのデータを取得する。(ポインタ参照)</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrame_Interface/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Infraredフレームのデータを取得する。(コピー)</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrame_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Infraredフレームの情報を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IInfraredFrame_Interface/Methods/get_InfraredFrameSource.md">get_InfraredFrameSource</a></td>
<td align="left">InfraredフレームのSourceを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IInfraredFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Infraredフレームを取得した時間(相対時間)を取得する。</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

このフレームの画素値は16bitの符号なし整数(unsigned short)で赤外線エミッターから照射した赤外線の反射強度を示す。  
InfraredデータはDepthデータと同じ座標系をとる。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IInfraredFrame Interface
RLTitle : IInfraredFrame Interface
KeywordK : IInfraredFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IInfraredFrame
KeywordF : Microsoft.Kinect.kinect.IInfraredFrame
KeywordA : T:Microsoft.Kinect.kinect.IInfraredFrame
AssetID : T:Microsoft.Kinect.kinect.IInfraredFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IInfraredFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
