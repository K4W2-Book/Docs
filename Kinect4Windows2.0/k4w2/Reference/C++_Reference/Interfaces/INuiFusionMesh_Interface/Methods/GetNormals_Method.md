INuiFusionMesh::GetNormals Method  
=================================  

メッシュデータの法線を取得する。 <span id="syntaxSection"></span>

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
HRESULT GetNormals(  
         const Vector3 **pNormals  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pNormals*    
Type: Vector3  
メッシュデータの法線の配列のアドレス。  

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
TOCTitle : GetNormals Method
RLTitle : INuiFusionMesh::GetNormals Method
KeywordK : GetNormals method
KeywordK : INuiFusionMesh::GetNormals method
KeywordF : INuiFusionMesh::GetNormals
KeywordF : GetNormals
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh.GetNormals(Vector3)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh.GetNormals(Vector3)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh.GetNormals(Vector3)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionMesh::GetNormals
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
