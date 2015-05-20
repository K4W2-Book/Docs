InfraredFrame.LockImageBuffer メソッド  
====================================  

システムで管理しているバッファを取得する。
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
IBuffer^ LockImageBuffer()</code></pre></td>
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
<td align="left"><pre><code>public IBufferLockImageBuffer ()</code></pre></td>
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
<td align="left"><pre><code>var iBuffer = infraredFrame.lockImageBuffer();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EP"></span>
#### 戻り値  

Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
システムで管理しているバッファ。  

<span id="remarks"></span>

Remarks  
=======  

When you are finished reading the data, unlock the buffer.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**WindowsPreview.Kinect  
**Metadata:**windowspreview.kinect.winmd  

<span id="ID4E6"></span>

See also  
========  

<span id="ID4EBB"></span>
#### Reference  

[InfraredFrame Class](../../InfraredFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : LockImageBuffer Method
RLTitle : InfraredFrame.LockImageBuffer Method
KeywordK : LockImageBuffer method
KeywordK : InfraredFrame.LockImageBuffer method
KeywordF : WindowsPreview.Kinect.InfraredFrame.LockImageBuffer
KeywordF : InfraredFrame.LockImageBuffer
KeywordF : LockImageBuffer
KeywordF : WindowsPreview.Kinect.InfraredFrame.LockImageBuffer
KeywordA : M:WindowsPreview.Kinect.InfraredFrame.LockImageBuffer
AssetID : M:WindowsPreview.Kinect.InfraredFrame.LockImageBuffer
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.InfraredFrame.LockImageBuffer
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
