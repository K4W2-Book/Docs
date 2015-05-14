IFaceFrame::get\_InfraredFrameReference Method  
==============================================  

InfraredフレームのReferenceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_InfraredFrameReference(  
         IInfraredFrameReference **infraredFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*infraredFrameReference*    
Type: IInfraredFrameReference  
[out] IInfraredFrameReferenceのポインタのアドレス。  

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
TOCTitle : get_InfraredFrameReference Method
RLTitle : IFaceFrame::get_InfraredFrameReference Method
KeywordK : get_InfraredFrameReference method
KeywordK : IFaceFrame::get_InfraredFrameReference method
KeywordF : IFaceFrame::get_InfraredFrameReference
KeywordF : get_InfraredFrameReference
KeywordF : Microsoft.Kinect.face.IFaceFrame.get_InfraredFrameReference(IInfraredFrameReference@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrame.get_InfraredFrameReference(IInfraredFrameReference@)
AssetID : M:Microsoft.Kinect.face.IFaceFrame.get_InfraredFrameReference(IInfraredFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrame::get_InfraredFrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
