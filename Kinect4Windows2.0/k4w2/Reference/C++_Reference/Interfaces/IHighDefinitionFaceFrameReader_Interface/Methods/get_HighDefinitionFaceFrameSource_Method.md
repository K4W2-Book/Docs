IHighDefinitionFaceFrameReader::get\_HighDefinitionFaceFrameSource Method  
=============================================  

HDFaceフレームのSourceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_HighDefinitionFaceFrameSource(  
         IHighDefinitionFaceFrameSource **hdFaceFrameSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*hdFaceFrameSource*    
Type: IHighDefinitionFaceFrameSource  
[out] IHighDefinitionFaceFrameSourceのポインタのアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_HighDefinitionFaceFrameSource Method
RLTitle : IHighDefinitionFaceFrameReader::get_HighDefinitionFaceFrameSource Method
KeywordK : get_HighDefinitionFaceFrameSource method
KeywordK : IHighDefinitionFaceFrameReader::get_HighDefinitionFaceFrameSource method
KeywordF : IHighDefinitionFaceFrameReader::get_HighDefinitionFaceFrameSource
KeywordF : get_HighDefinitionFaceFrameSource
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.get_HighDefinitionFaceFrameSource(IHighDefinitionFaceFrameSource@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.get_HighDefinitionFaceFrameSource(IHighDefinitionFaceFrameSource@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.get_HighDefinitionFaceFrameSource(IHighDefinitionFaceFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader::get_HighDefinitionFaceFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
