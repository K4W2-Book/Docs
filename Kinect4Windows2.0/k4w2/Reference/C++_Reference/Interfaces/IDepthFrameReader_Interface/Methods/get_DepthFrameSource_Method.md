IDepthFrameReader::get\_DepthFrameSource Method  
===============================================  

DepthフレームのSourceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_DepthFrameSource(  
         IDepthFrameSource **depthFrameSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFrameSource*    
Type: IDepthFrameSource  
[out] [IDepthFrameSource](../../IDepthFrameSource_Interface.md)のポインタのアドレス。  

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
TOCTitle : get_DepthFrameSource Method
RLTitle : IDepthFrameReader::get_DepthFrameSource Method
KeywordK : get_DepthFrameSource method
KeywordK : IDepthFrameReader::get_DepthFrameSource method
KeywordF : IDepthFrameReader::get_DepthFrameSource
KeywordF : get_DepthFrameSource
KeywordF : Microsoft.Kinect.kinect.IDepthFrameReader.get_DepthFrameSource(IDepthFrameSource@)
KeywordA : M:Microsoft.Kinect.kinect.IDepthFrameReader.get_DepthFrameSource(IDepthFrameSource@)
AssetID : M:Microsoft.Kinect.kinect.IDepthFrameReader.get_DepthFrameSource(IDepthFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrameReader::get_DepthFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
