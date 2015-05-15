INuiFusionColorMesh::GetColors Method  
=====================================  

メッシュデータに含まれる頂点カラーを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetColors(  
         const int **pColors  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pColors*    
Type: int  
頂点カラーの配列のアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncolorvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetColors Method
RLTitle : INuiFusionColorMesh::GetColors Method
KeywordK : GetColors method
KeywordK : INuiFusionColorMesh::GetColors method
KeywordF : INuiFusionColorMesh::GetColors
KeywordF : GetColors
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorMesh.GetColors(int)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorMesh.GetColors(int)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorMesh.GetColors(int)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorMesh::GetColors
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
