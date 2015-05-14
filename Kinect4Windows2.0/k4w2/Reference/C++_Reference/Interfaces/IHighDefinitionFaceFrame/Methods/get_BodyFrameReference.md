IHighDefinitionFaceFrame::get\_BodyFrameReference Method  
========================================================  

BodyフレームのReferenceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_BodyFrameReference(  
         IBodyFrameReference **bodyFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bodyFrameReference*    
Type: IBodyFrameReference  
[out] IBodyFrameReferenceのポインタのアドレス。  

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
TOCTitle : get_BodyFrameReference Method
RLTitle : IHighDefinitionFaceFrame::get_BodyFrameReference Method
KeywordK : get_BodyFrameReference method
KeywordK : IHighDefinitionFaceFrame::get_BodyFrameReference method
KeywordF : IHighDefinitionFaceFrame::get_BodyFrameReference
KeywordF : get_BodyFrameReference
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrame.get_BodyFrameReference(IBodyFrameReference@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrame.get_BodyFrameReference(IBodyFrameReference@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrame.get_BodyFrameReference(IBodyFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrame::get_BodyFrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
