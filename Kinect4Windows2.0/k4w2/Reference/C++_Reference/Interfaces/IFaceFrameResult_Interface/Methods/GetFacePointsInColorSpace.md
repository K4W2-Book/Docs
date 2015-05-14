IFaceFrameResult::GetFacePointsInColorSpace Method  
==================================================  

顔パーツ(左右目、鼻、左右口角)の位置(Color座標系)を取得する。 <span id="syntaxSection"></span>

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
HRESULT GetFacePointsInColorSpace(  
         const UINT capacity,  
         PointF *facePoints  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
[in] 顔パーツの位置の配列のサイズ。(5)  

*facePoints*    
Type: PointF  
[out] 顔パーツ(左右目、鼻、左右口角)の位置(Color座標系)の配列のアドレス。  

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
TOCTitle : GetFacePointsInColorSpace Method
RLTitle : IFaceFrameResult::GetFacePointsInColorSpace Method
KeywordK : GetFacePointsInColorSpace method
KeywordK : IFaceFrameResult::GetFacePointsInColorSpace method
KeywordF : IFaceFrameResult::GetFacePointsInColorSpace
KeywordF : GetFacePointsInColorSpace
KeywordF : Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInColorSpace(UINT,PointF@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInColorSpace(UINT,PointF@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInColorSpace(UINT,PointF@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameResult::GetFacePointsInColorSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
