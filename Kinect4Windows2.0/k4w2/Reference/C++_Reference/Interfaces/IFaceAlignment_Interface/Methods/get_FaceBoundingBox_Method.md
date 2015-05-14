IFaceAlignment::get\_FaceBoundingBox Method  
===========================================  

顔を囲むバウンディングボックス(Color座標系)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FaceBoundingBox(  
         RectI *boundingBox  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*boundingBox*    
Type: RectI  
[out] 顔を囲むバウンディングボックス(Color座標系)。  

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
TOCTitle : get_FaceBoundingBox Method
RLTitle : IFaceAlignment::get_FaceBoundingBox Method
KeywordK : get_FaceBoundingBox method
KeywordK : IFaceAlignment::get_FaceBoundingBox method
KeywordF : IFaceAlignment::get_FaceBoundingBox
KeywordF : get_FaceBoundingBox
KeywordF : Microsoft.Kinect.face.IFaceAlignment.get_FaceBoundingBox(RectI@)
KeywordA : M:Microsoft.Kinect.face.IFaceAlignment.get_FaceBoundingBox(RectI@)
AssetID : M:Microsoft.Kinect.face.IFaceAlignment.get_FaceBoundingBox(RectI@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceAlignment::get_FaceBoundingBox
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
