IFaceFrameReader::get\_FaceFrameSource Method  
=============================================  

FaceフレームのSourceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FaceFrameSource(  
         IFaceFrameSource **faceFrameSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceFrameSource*    
Type: IFaceFrameSource  
[out] IFaceFrameSourceのポインタのアドレス。  

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
TOCTitle : get_FaceFrameSource Method
RLTitle : IFaceFrameReader::get_FaceFrameSource Method
KeywordK : get_FaceFrameSource method
KeywordK : IFaceFrameReader::get_FaceFrameSource method
KeywordF : IFaceFrameReader::get_FaceFrameSource
KeywordF : get_FaceFrameSource
KeywordF : Microsoft.Kinect.face.IFaceFrameReader.get_FaceFrameSource(IFaceFrameSource@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameReader.get_FaceFrameSource(IFaceFrameSource@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameReader.get_FaceFrameSource(IFaceFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameReader::get_FaceFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
