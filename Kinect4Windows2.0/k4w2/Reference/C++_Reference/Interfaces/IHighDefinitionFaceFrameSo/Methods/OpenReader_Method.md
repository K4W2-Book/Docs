IHighDefinitionFaceFrameSource::OpenReader Method  
=================================================  

HDFaceフレームのReaderを開く。 <span id="syntaxSection"></span>

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
         IHighDefinitionFaceFrameReader **highDefinitionFaceFrameReader  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*highDefinitionFaceFrameReader*    
Type: IHighDefinitionFaceFrameReader  
[out] IHighDefinitionFaceFrameReaderのポインタのアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OpenReader Method
RLTitle : IHighDefinitionFaceFrameSource::OpenReader Method
KeywordK : OpenReader method
KeywordK : IHighDefinitionFaceFrameSource::OpenReader method
KeywordF : IHighDefinitionFaceFrameSource::OpenReader
KeywordF : OpenReader
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.OpenReader(IHighDefinitionFaceFrameReader@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.OpenReader(IHighDefinitionFaceFrameReader@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.OpenReader(IHighDefinitionFaceFrameReader@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::OpenReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
