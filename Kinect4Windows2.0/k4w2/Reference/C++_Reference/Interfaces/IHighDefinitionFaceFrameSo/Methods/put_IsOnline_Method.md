IHighDefinitionFaceFrameSource::put\_IsOnline Method  
====================================================  

HDFaceフレームのSourceのオンラインステータスを設定する。 <span id="syntaxSection"></span>

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
HRESULT put_IsOnline(  
         BOOLEAN isOnline  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isOnline*    
Type: BOOLEAN  
HDFaceフレームのSourceをオンラインに設定する場合は**true**、オフラインに設定する場合は**false**。  

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
TOCTitle : put_IsOnline Method
RLTitle : IHighDefinitionFaceFrameSource::put_IsOnline Method
KeywordK : put_IsOnline method
KeywordK : IHighDefinitionFaceFrameSource::put_IsOnline method
KeywordF : IHighDefinitionFaceFrameSource::put_IsOnline
KeywordF : put_IsOnline
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.put_IsOnline(BOOLEAN)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.put_IsOnline(BOOLEAN)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.put_IsOnline(BOOLEAN)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::put_IsOnline
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
