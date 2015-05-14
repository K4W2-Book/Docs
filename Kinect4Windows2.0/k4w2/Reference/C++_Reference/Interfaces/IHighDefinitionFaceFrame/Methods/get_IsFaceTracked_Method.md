IHighDefinitionFaceFrame::get\_IsFaceTracked Method  
===================================================  

顔のトラッキング状態を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_IsFaceTracked(  
         BOOLEAN *isFaceTracked  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isFaceTracked*    
Type: BOOLEAN  
[out] 顔がトラッキングされている場合はtrue、トラッキングされていない場合はfalse。  

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
TOCTitle : get_IsFaceTracked Method
RLTitle : IHighDefinitionFaceFrame::get_IsFaceTracked Method
KeywordK : get_IsFaceTracked method
KeywordK : IHighDefinitionFaceFrame::get_IsFaceTracked method
KeywordF : IHighDefinitionFaceFrame::get_IsFaceTracked
KeywordF : get_IsFaceTracked
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrame.get_IsFaceTracked(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrame.get_IsFaceTracked(BOOLEAN@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrame.get_IsFaceTracked(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrame::get_IsFaceTracked
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
