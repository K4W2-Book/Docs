IBodyIndexFrameSource::OpenReader Method  
========================================  

BodyIndexフレームのReaderを開く。 <span id="syntaxSection"></span>

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
         IBodyIndexFrameReader **reader  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*reader*    
Type: IBodyIndexFrameReader  
[out] [IBodyIndexFrameReader](../../IBodyIndexFrameReader.md)のポインタのアドレス。  

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
RLTitle : IBodyIndexFrameSource::OpenReader Method
KeywordK : OpenReader method
KeywordK : IBodyIndexFrameSource::OpenReader method
KeywordF : IBodyIndexFrameSource::OpenReader
KeywordF : OpenReader
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrameSource.OpenReader(IBodyIndexFrameReader@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyIndexFrameSource.OpenReader(IBodyIndexFrameReader@)
AssetID : M:Microsoft.Kinect.kinect.IBodyIndexFrameSource.OpenReader(IBodyIndexFrameReader@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrameSource::OpenReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
