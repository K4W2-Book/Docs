IDepthFrame Interface  
=====================  

Depthフレーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IDepthFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IDepthFrame**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IDepthFrame_Interface/Methods/AccessUnderlyingBuffer.md">AccessUnderlyingBuffer</a></td>
<td align="left">Depthフレームのデータを取得する。(ポインタ参照)</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrame_Interface/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">Depthフレームのデータを取得する。(コピー)</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_DepthFrameSource_Method.md">get_DepthFrameSource</a></td>
<td align="left">DepthフレームのSourceを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_DepthMaxReliableDistance.md">get_DepthMaxReliableDistance</a></td>
<td align="left">Depthフレームの精度が確保できる最大距離を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_DepthMinReliableDistance.md">get_DepthMinReliableDistance</a></td>
<td align="left">Depthフレームの精度が確保できる最小距離を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">Depthフレームの情報を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IDepthFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Depthフレームを取得した時間(相対時間)を取得する。</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

このフレームの画素値は16bitの符号なし整数(unsigned short)でミリメートル単位の距離を示す。  
精度が確保できる最大距離は4.5[m]だが、取得できる最大距離は8.0[m]です。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IDepthFrame Interface
RLTitle : IDepthFrame Interface
KeywordK : IDepthFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IDepthFrame
KeywordF : Microsoft.Kinect.kinect.IDepthFrame
KeywordA : T:Microsoft.Kinect.kinect.IDepthFrame
AssetID : T:Microsoft.Kinect.kinect.IDepthFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
