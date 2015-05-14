IHighDefinitionFaceFrameReader::AcquireLatestFrame Method  
=========================================================  

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
HRESULT AcquireLatestFrame(  
         IHighDefinitionFaceFrame **hdFaceFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*hdFaceFrame*    
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
TOCTitle : AcquireLatestFrame Method
RLTitle : IHighDefinitionFaceFrameReader::AcquireLatestFrame Method
KeywordK : AcquireLatestFrame method
KeywordK : IHighDefinitionFaceFrameReader::AcquireLatestFrame method
KeywordF : IHighDefinitionFaceFrameReader::AcquireLatestFrame
KeywordF : AcquireLatestFrame
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.AcquireLatestFrame(IHighDefinitionFaceFrame@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.AcquireLatestFrame(IHighDefinitionFaceFrame@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.AcquireLatestFrame(IHighDefinitionFaceFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader::AcquireLatestFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
