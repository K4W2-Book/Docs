IFaceFrameResult::get\_FaceBoundingBoxInInfraredSpace Method  
============================================================  

顔を囲むバウンディングボックス(Depth座標系)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FaceBoundingBoxInInfraredSpace(  
         RectI *boundingBox  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*boundingBox*    
Type: RectI  
[out] 顔を囲むバウンディングボックス(Depth座標系)  

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
TOCTitle : get_FaceBoundingBoxInInfraredSpace Method
RLTitle : IFaceFrameResult::get_FaceBoundingBoxInInfraredSpace Method
KeywordK : get_FaceBoundingBoxInInfraredSpace method
KeywordK : IFaceFrameResult::get_FaceBoundingBoxInInfraredSpace method
KeywordF : IFaceFrameResult::get_FaceBoundingBoxInInfraredSpace
KeywordF : get_FaceBoundingBoxInInfraredSpace
KeywordF : Microsoft.Kinect.face.IFaceFrameResult.get_FaceBoundingBoxInInfraredSpace(RectI@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameResult.get_FaceBoundingBoxInInfraredSpace(RectI@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameResult.get_FaceBoundingBoxInInfraredSpace(RectI@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameResult::get_FaceBoundingBoxInInfraredSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
