IFaceFrame::get\_IsTrackingIdValid Method  
=========================================  

トラッキングIDが有効であるかを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_IsTrackingIdValid(  
         BOOLEAN *isTrackingIdValid  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isTrackingIdValid*    
Type: BOOLEAN  
[out] トラッキングIDが有効の場合はtrue、無効の場合はfalse。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_IsTrackingIdValid Method
RLTitle : IFaceFrame::get_IsTrackingIdValid Method
KeywordK : get_IsTrackingIdValid method
KeywordK : IFaceFrame::get_IsTrackingIdValid method
KeywordF : IFaceFrame::get_IsTrackingIdValid
KeywordF : get_IsTrackingIdValid
KeywordF : Microsoft.Kinect.face.IFaceFrame.get_IsTrackingIdValid(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrame.get_IsTrackingIdValid(BOOLEAN@)
AssetID : M:Microsoft.Kinect.face.IFaceFrame.get_IsTrackingIdValid(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrame::get_IsTrackingIdValid
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
