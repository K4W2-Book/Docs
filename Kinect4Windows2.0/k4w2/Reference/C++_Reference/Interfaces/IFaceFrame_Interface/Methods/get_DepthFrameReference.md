IFaceFrame::get\_DepthFrameReference Method  
===========================================  

DepthフレームのReferenceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_DepthFrameReference(  
         IDepthFrameReference **depthFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthFrameReference*    
Type: IDepthFrameReference  
[out] IDepthFrameReferenceのポインタのアドレス。  

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
TOCTitle : get_DepthFrameReference Method
RLTitle : IFaceFrame::get_DepthFrameReference Method
KeywordK : get_DepthFrameReference method
KeywordK : IFaceFrame::get_DepthFrameReference method
KeywordF : IFaceFrame::get_DepthFrameReference
KeywordF : get_DepthFrameReference
KeywordF : Microsoft.Kinect.face.IFaceFrame.get_DepthFrameReference(IDepthFrameReference@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrame.get_DepthFrameReference(IDepthFrameReference@)
AssetID : M:Microsoft.Kinect.face.IFaceFrame.get_DepthFrameReference(IDepthFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrame::get_DepthFrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
