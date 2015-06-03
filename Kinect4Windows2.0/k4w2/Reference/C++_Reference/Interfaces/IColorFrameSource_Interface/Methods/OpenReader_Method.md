IColorFrameSource::OpenReader Method  
====================================  

ColorフレームのReaderを開く。 <span id="syntaxSection"></span>

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
HRESULT OpenReader(  
         IColorFrameReader **reader  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*reader*    
Type: IColorFrameReader  
[out] [IColorFrameReader](../../IColorFrameReader_Interface.md)のポインタのアドレス。  

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
TOCTitle : OpenReader Method
RLTitle : IColorFrameSource::OpenReader Method
KeywordK : OpenReader method
KeywordK : IColorFrameSource::OpenReader method
KeywordF : IColorFrameSource::OpenReader
KeywordF : OpenReader
KeywordF : Microsoft.Kinect.kinect.IColorFrameSource.OpenReader(IColorFrameReader@)
KeywordA : M:Microsoft.Kinect.kinect.IColorFrameSource.OpenReader(IColorFrameReader@)
AssetID : M:Microsoft.Kinect.kinect.IColorFrameSource.OpenReader(IColorFrameReader@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrameSource::OpenReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
