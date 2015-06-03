IColorFrame::get\_RawColorImageFormat Method  
============================================  

ColorフレームのRAWデータのフォーマットを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_RawColorImageFormat(  
         ColorImageFormat *rawColorImageFormat  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*rawColorImageFormat*    
Type: [ColorImageFormat](../../../Enumerations/ColorImageFormat_Enumeration.md)  
[out] ColorフレームのRAWデータのフォーマット。(ColorImageFormat\_Yuy2)  

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
TOCTitle : get_RawColorImageFormat Method
RLTitle : IColorFrame::get_RawColorImageFormat Method
KeywordK : get_RawColorImageFormat method
KeywordK : IColorFrame::get_RawColorImageFormat method
KeywordF : IColorFrame::get_RawColorImageFormat
KeywordF : get_RawColorImageFormat
KeywordF : Microsoft.Kinect.kinect.IColorFrame.get_RawColorImageFormat(ColorImageFormat@)
KeywordA : M:Microsoft.Kinect.kinect.IColorFrame.get_RawColorImageFormat(ColorImageFormat@)
AssetID : M:Microsoft.Kinect.kinect.IColorFrame.get_RawColorImageFormat(ColorImageFormat@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrame::get_RawColorImageFormat
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
