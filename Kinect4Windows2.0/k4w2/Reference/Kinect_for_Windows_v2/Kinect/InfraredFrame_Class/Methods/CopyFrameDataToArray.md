InfraredFrame.CopyFrameDataToArray メソッド  
=========================================  

赤外線フレームデータを配列にコピーする。
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
void CopyFrameDataToArray(  
         out Array&lt;uint16&gt;^ frameData  
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
<td align="left"><pre><code>public void CopyFrameDataToArray (  
         out Array&lt;UInt16&gt;[] frameData  
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
<td align="left"><pre><code>infraredFrame.copyFrameDataToArray();</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### 引数  

*frameData*    
[C++] Type: uint16  
  [C\#] Type: [UInt16](http://msdn.microsoft.com/en-us/library/system.uint16.aspx)  
  [JavaScript] Type: Number  
   

赤外線フレームデータをコピーする配列。
  

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

[InfraredFrame Class](../../InfraredFrame_Class.md)  
 [WindowsPreview.Kinect Namespace](../../../Kinect.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyFrameDataToArray Method
RLTitle : InfraredFrame.CopyFrameDataToArray Method
KeywordK : CopyFrameDataToArray method
KeywordK : InfraredFrame.CopyFrameDataToArray method
KeywordF : WindowsPreview.Kinect.InfraredFrame.CopyFrameDataToArray
KeywordF : InfraredFrame.CopyFrameDataToArray
KeywordF : CopyFrameDataToArray
KeywordF : WindowsPreview.Kinect.InfraredFrame.CopyFrameDataToArray(System.UInt16[]@)
KeywordA : M:WindowsPreview.Kinect.InfraredFrame.CopyFrameDataToArray(System.UInt16[]@)
AssetID : M:WindowsPreview.Kinect.InfraredFrame.CopyFrameDataToArray(System.UInt16[]@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : windowspreview.kinect.winmd
APIName : WindowsPreview.Kinect.InfraredFrame.CopyFrameDataToArray
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
