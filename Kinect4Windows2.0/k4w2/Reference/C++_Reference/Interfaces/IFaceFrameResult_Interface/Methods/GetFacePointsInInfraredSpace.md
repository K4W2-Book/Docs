IFaceFrameResult::GetFacePointsInInfraredSpace Method  
=====================================================  

顔パーツ(左右目、鼻、左右口角)の位置(Depth座標系)を取得する。 <span id="syntaxSection"></span>

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
HRESULT GetFacePointsInInfraredSpace(  
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
[out] 顔パーツ(左右目、鼻、左右口角)の位置(Depth座標系)の配列のアドレス。  

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
TOCTitle : GetFacePointsInInfraredSpace Method
RLTitle : IFaceFrameResult::GetFacePointsInInfraredSpace Method
KeywordK : GetFacePointsInInfraredSpace method
KeywordK : IFaceFrameResult::GetFacePointsInInfraredSpace method
KeywordF : IFaceFrameResult::GetFacePointsInInfraredSpace
KeywordF : GetFacePointsInInfraredSpace
KeywordF : Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInInfraredSpace(UINT,PointF@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInInfraredSpace(UINT,PointF@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameResult.GetFacePointsInInfraredSpace(UINT,PointF@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameResult::GetFacePointsInInfraredSpace
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
