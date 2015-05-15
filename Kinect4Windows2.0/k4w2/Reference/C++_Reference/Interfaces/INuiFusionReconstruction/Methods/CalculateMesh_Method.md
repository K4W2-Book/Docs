INuiFusionReconstruction::CalculateMesh Method  
==============================================  

再構成した3次元形状データからメッシュデータを計算してエクスポートする。 <span id="syntaxSection"></span>

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
HRESULT CalculateMesh(  
         UINT voxelStep,  
         INuiFusionMesh **ppMesh  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*voxelStep*    
Type: UINT  
再構成された3次元形状データをサンプリングするステップ値。  
大きな値を指定するとエクスポートされるメッシュデータの解像度が低くなります。  
このステップ値は、0より大きく、各軸の再構成に使われるボクセル数以下である必要があります。  
再構成された3次元形状データの解像度を落とさずにメッシュデータにエクスポートする場合は1を指定します。  

| ![](../../../../../../resources/note.gif)Note                                                                                        |
|--------------------------------------------------------------------------------------------------------------------------------------|
| 1より大きい値を指定すると3次元形状データの詳細な情報が失われる危険があります。 |

*ppMesh*    
Type: INuiFusionMesh  
INuiFusionMeshのポインタのアドレス。  

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
TOCTitle : CalculateMesh Method
RLTitle : INuiFusionReconstruction::CalculateMesh Method
KeywordK : CalculateMesh method
KeywordK : INuiFusionReconstruction::CalculateMesh method
KeywordF : INuiFusionReconstruction::CalculateMesh
KeywordF : CalculateMesh
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.CalculateMesh(UINT,INuiFusionMesh)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.CalculateMesh(UINT,INuiFusionMesh)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.CalculateMesh(UINT,INuiFusionMesh)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::CalculateMesh
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
