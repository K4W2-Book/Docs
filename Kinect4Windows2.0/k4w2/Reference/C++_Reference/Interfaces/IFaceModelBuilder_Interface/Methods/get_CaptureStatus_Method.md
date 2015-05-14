IFaceModelBuilder::get\_CaptureStatus Method  
============================================  

キャプチャステータスを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_CaptureStatus(  
         FaceModelBuilderCaptureStatus *currentCaptureStatus  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*currentCaptureStatus*    
Type: FaceModelBuilderCaptureStatus  
[out] キャプチャステータス。  

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
TOCTitle : get_CaptureStatus Method
RLTitle : IFaceModelBuilder::get_CaptureStatus Method
KeywordK : get_CaptureStatus method
KeywordK : IFaceModelBuilder::get_CaptureStatus method
KeywordF : IFaceModelBuilder::get_CaptureStatus
KeywordF : get_CaptureStatus
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.get_CaptureStatus(FaceModelBuilderCaptureStatus@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.get_CaptureStatus(FaceModelBuilderCaptureStatus@)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.get_CaptureStatus(FaceModelBuilderCaptureStatus@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::get_CaptureStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
