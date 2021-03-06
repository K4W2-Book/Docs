IHighDefinitionFaceFrameReference::AcquireFrame Method  
======================================================  

HDFaceフレームを取得する。 <span id="syntaxSection"></span>

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
HRESULT AcquireFrame(  
         IHighDefinitionFaceFrame **highDefinitonFaceFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*highDefinitonFaceFrame*    
Type: IHighDefinitionFaceFrame  
[out] IHighDefinitionFaceFrameのポインタのアドレス。  

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
TOCTitle : AcquireFrame Method
RLTitle : IHighDefinitionFaceFrameReference::AcquireFrame Method
KeywordK : AcquireFrame method
KeywordK : IHighDefinitionFaceFrameReference::AcquireFrame method
KeywordF : IHighDefinitionFaceFrameReference::AcquireFrame
KeywordF : AcquireFrame
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameReference.AcquireFrame(IHighDefinitionFaceFrame@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReference.AcquireFrame(IHighDefinitionFaceFrame@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReference.AcquireFrame(IHighDefinitionFaceFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameReference::AcquireFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
