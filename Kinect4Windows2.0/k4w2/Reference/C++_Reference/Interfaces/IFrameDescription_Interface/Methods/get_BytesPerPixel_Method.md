IFrameDescription::get\_BytesPerPixel Method  
============================================  

画素のサイズ(Byte)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_BytesPerPixel(  
         unsigned int *bytesPerPixel  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bytesPerPixel*    
Type: unsigned int  
画素のサイズ(Byte)。  

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
TOCTitle : get_BytesPerPixel Method
RLTitle : IFrameDescription::get_BytesPerPixel Method
KeywordK : get_BytesPerPixel method
KeywordK : IFrameDescription::get_BytesPerPixel method
KeywordF : IFrameDescription::get_BytesPerPixel
KeywordF : get_BytesPerPixel
KeywordF : Microsoft.Kinect.kinect.IFrameDescription.get_BytesPerPixel(unsigned int)
KeywordA : M:Microsoft.Kinect.kinect.IFrameDescription.get_BytesPerPixel(unsigned int)
AssetID : M:Microsoft.Kinect.kinect.IFrameDescription.get_BytesPerPixel(unsigned int)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IFrameDescription::get_BytesPerPixel
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
