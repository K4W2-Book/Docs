IHighDefinitionFaceFrameSource::get\_IsOnline Method  
====================================================  

HDFaceフレームのSourceのオンラインステータスを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_IsOnline(  
         BOOLEAN *isOnline  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isOnline*    
Type: BOOLEAN  
[out] HDFaceフレームのSourceがオンラインの場合は**true**、オフラインの場合は**false**。  

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
TOCTitle : get_IsOnline Method
RLTitle : IHighDefinitionFaceFrameSource::get_IsOnline Method
KeywordK : get_IsOnline method
KeywordK : IHighDefinitionFaceFrameSource::get_IsOnline method
KeywordF : IHighDefinitionFaceFrameSource::get_IsOnline
KeywordF : get_IsOnline
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.get_IsOnline(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.get_IsOnline(BOOLEAN@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.get_IsOnline(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::get_IsOnline
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
