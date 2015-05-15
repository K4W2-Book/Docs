INuiFusionMesh::GetTriangleIndices Method  
=========================================  

メッシュデータの三角形を取得する。 <span id="syntaxSection"></span>

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
HRESULT GetTriangleIndices(  
         const int **pTriangleVertexIndices  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pTriangleVertexIndices*    
Type: int  
メッシュデータの三角形の配列のアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetTriangleIndices Method
RLTitle : INuiFusionMesh::GetTriangleIndices Method
KeywordK : GetTriangleIndices method
KeywordK : INuiFusionMesh::GetTriangleIndices method
KeywordF : INuiFusionMesh::GetTriangleIndices
KeywordF : GetTriangleIndices
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh.GetTriangleIndices(int)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh.GetTriangleIndices(int)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh.GetTriangleIndices(int)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh::GetTriangleIndices
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
