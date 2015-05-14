IHighDefinitionFaceFrameReader::get\_IsPaused Method  
======================================  

HDFaceフレームのReaderの動作状態を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_IsPaused(  
         BOOLEAN *isPaused  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isPaused*    
Type: BOOLEAN  
[out] 停止している場合は**true**、動作している場合は**false**。  

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
TOCTitle : get_IsPaused Method
RLTitle : IHighDefinitionFaceFrameReader::get_IsPaused Method
KeywordK : get_IsPaused method
KeywordK : IHighDefinitionFaceFrameReader::get_IsPaused method
KeywordF : IHighDefinitionFaceFrameReader::get_IsPaused
KeywordF : get_IsPaused
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.get_IsPaused(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.get_IsPaused(BOOLEAN@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.get_IsPaused(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader::get_IsPaused
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
