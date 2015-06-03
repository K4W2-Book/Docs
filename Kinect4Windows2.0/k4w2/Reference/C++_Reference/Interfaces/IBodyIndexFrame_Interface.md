IBodyIndexFrame Interface  
=========================  

BodyIndexフレーム。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IBodyIndexFrame : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IBodyIndexFrame**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/AccessUnderlyingBuffer.md">AccessUnderlyingBuffer</a></td>
<td align="left">BodyIndexフレームのデータを取得する。(ポインタ参照)</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/CopyFrameDataToArray_Method.md">CopyFrameDataToArray</a></td>
<td align="left">BodyIndexフレームのデータを取得する。(コピー)</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/get_BodyIndexFrameSource.md">get_BodyIndexFrameSource</a></td>
<td align="left">BodyIndexフレームのSourceを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/get_FrameDescription_Method.md">get_FrameDescription</a></td>
<td align="left">BodyIndexフレームの情報を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IBodyIndexFrame_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">BodyIndexフレームを取得した時間(相対時間)を取得する。</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

このフレームの画素値は8bitの符号なし整数(unsigned char)で0~5のBodyのインデックスを示す。  
また、[IBodyFrameSource::get\_BodyCount](IBodyFrameSource_Interface/Methods/get_BodyCount_Method.md)で取得したトラッキングできる最大人数よりも多い画素値は背景を示す。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IBodyIndexFrame Interface
RLTitle : IBodyIndexFrame Interface
KeywordK : IBodyIndexFrame interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IBodyIndexFrame
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrame
KeywordA : T:Microsoft.Kinect.kinect.IBodyIndexFrame
AssetID : T:Microsoft.Kinect.kinect.IBodyIndexFrame
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
