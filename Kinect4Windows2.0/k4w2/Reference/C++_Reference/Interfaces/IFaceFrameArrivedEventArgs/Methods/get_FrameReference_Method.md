IFaceFrameArrivedEventArgs::get\_FrameReference Method  
======================================================  

FaceフレームのReferenceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FrameReference(  
         IFaceFrameReference **faceFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceFrameReference*    
Type: IFaceFrameReference  
[out] IFaceFrameReferenceのポインタのアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合、エラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_FrameReference Method
RLTitle : IFaceFrameArrivedEventArgs::get_FrameReference Method
KeywordK : get_FrameReference method
KeywordK : IFaceFrameArrivedEventArgs::get_FrameReference method
KeywordF : IFaceFrameArrivedEventArgs::get_FrameReference
KeywordF : get_FrameReference
KeywordF : Microsoft.Kinect.face.IFaceFrameArrivedEventArgs.get_FrameReference(IFaceFrameReference@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameArrivedEventArgs.get_FrameReference(IFaceFrameReference@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameArrivedEventArgs.get_FrameReference(IFaceFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameArrivedEventArgs::get_FrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
