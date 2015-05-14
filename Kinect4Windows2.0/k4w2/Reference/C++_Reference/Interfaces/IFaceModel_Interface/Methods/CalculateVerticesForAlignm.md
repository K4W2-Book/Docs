IFaceModel::CalculateVerticesForAlignment Method  
================================================  

位置合わせされた顔モデルから頂点の座標(Camera座標系)を取得する。 <span id="syntaxSection"></span>

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
HRESULT CalculateVerticesForAlignment(  
         IFaceAlignment *faceAlignment,  
         UINT capacity,  
         CameraSpacePoint *vertices  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceAlignment*    
Type: IFaceAlignment  
IFaceAlignmentのアドレス。  

*capacity*    
Type: UINT  
顔モデルの頂点の配列のサイズ。(1347)  

*vertices*    
Type: CameraSpacePoint  
[out] 顔モデルの頂点(Camera座標系)の配列のアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

HDFaceの顔モデルは1347点の頂点で構成されています。<br/>受け取る配列は頂点数のサイズを確保する必要があります。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculateVerticesForAlignment Method
RLTitle : IFaceModel::CalculateVerticesForAlignment Method
KeywordK : CalculateVerticesForAlignment method
KeywordK : IFaceModel::CalculateVerticesForAlignment method
KeywordF : IFaceModel::CalculateVerticesForAlignment
KeywordF : CalculateVerticesForAlignment
KeywordF : Microsoft.Kinect.face.IFaceModel.CalculateVerticesForAlignment(IFaceAlignment,UINT,CameraSpacePoint@)
KeywordA : M:Microsoft.Kinect.face.IFaceModel.CalculateVerticesForAlignment(IFaceAlignment,UINT,CameraSpacePoint@)
AssetID : M:Microsoft.Kinect.face.IFaceModel.CalculateVerticesForAlignment(IFaceAlignment,UINT,CameraSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModel::CalculateVerticesForAlignment
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
