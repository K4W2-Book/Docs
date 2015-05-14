IHighDefinitionFaceFrame::GetAndRefreshFaceAlignmentResult Method  
=================================================================  

位置合わせされた顔データを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetAndRefreshFaceAlignmentResult(  
         IFaceAlignment *faceAlignmentResults  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceAlignmentResults*    
Type: IFaceAlignment  
[in] IFaceAlignmentのポインタのアドレス。  

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
TOCTitle : GetAndRefreshFaceAlignmentResult Method
RLTitle : IHighDefinitionFaceFrame::GetAndRefreshFaceAlignmentResult Method
KeywordK : GetAndRefreshFaceAlignmentResult method
KeywordK : IHighDefinitionFaceFrame::GetAndRefreshFaceAlignmentResult method
KeywordF : IHighDefinitionFaceFrame::GetAndRefreshFaceAlignmentResult
KeywordF : GetAndRefreshFaceAlignmentResult
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrame.GetAndRefreshFaceAlignmentResult(IFaceAlignment)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrame.GetAndRefreshFaceAlignmentResult(IFaceAlignment)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrame.GetAndRefreshFaceAlignmentResult(IFaceAlignment)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrame::GetAndRefreshFaceAlignmentResult
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
