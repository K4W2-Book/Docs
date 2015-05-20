DepthFrame.CopyFrameDataToBuffer メソッド  
=======================================  

Depthフレームのデータのメモリ位置をバッファにコピーする。
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
void CopyFrameDataToBuffer(  
         IBuffer^ buffer  
)</code></pre></td>
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
<td align="left"><pre><code>public void CopyFrameDataToBuffer (  
         IBufferbuffer  
)</code></pre></td>
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
<td align="left"><pre><code>depthFrame.copyFrameDataToBuffer(buffer);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### 引数  

*buffer*    
Type: [IBuffer](http://msdn.microsoft.com/en-us/library/windows.storage.streams.ibuffer.aspx)  
Depthデータを受け取るバッファ

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

[DepthFrame Class](../../DepthFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyFrameDataToBuffer Method
RLTitle : DepthFrame.CopyFrameDataToBuffer Method
KeywordK : CopyFrameDataToBuffer method
KeywordK : DepthFrame.CopyFrameDataToBuffer method
KeywordF : WindowsPreview.Kinect.DepthFrame.CopyFrameDataToBuffer
KeywordF : DepthFrame.CopyFrameDataToBuffer
KeywordF : CopyFrameDataToBuffer
KeywordF : WindowsPreview.Kinect.DepthFrame.CopyFrameDataToBuffer(Windows.Storage.Streams.IBuffer)
KeywordA : M:WindowsPreview.Kinect.DepthFrame.CopyFrameDataToBuffer(Windows.Storage.Streams.IBuffer)
AssetID : M:WindowsPreview.Kinect.DepthFrame.CopyFrameDataToBuffer(Windows.Storage.Streams.IBuffer)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.DepthFrame.CopyFrameDataToBuffer
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
