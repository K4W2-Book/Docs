IColorFrameReader::get\_ColorFrameSource Method  
===============================================  

ColorフレームのSourceを取得する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
HRESULT get_ColorFrameSource(  
         IColorFrameSource **colorFrameSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*colorFrameSource*    
Type: IColorFrameSource  
[out] [IColorFrameSource](../../IColorFrameSource_Interface.md)  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_ColorFrameSource Method
RLTitle : IColorFrameReader::get_ColorFrameSource Method
KeywordK : get_ColorFrameSource method
KeywordK : IColorFrameReader::get_ColorFrameSource method
KeywordF : IColorFrameReader::get_ColorFrameSource
KeywordF : get_ColorFrameSource
KeywordF : Microsoft.Kinect.kinect.IColorFrameReader.get_ColorFrameSource(IColorFrameSource@)
KeywordA : M:Microsoft.Kinect.kinect.IColorFrameReader.get_ColorFrameSource(IColorFrameSource@)
AssetID : M:Microsoft.Kinect.kinect.IColorFrameReader.get_ColorFrameSource(IColorFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrameReader::get_ColorFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
