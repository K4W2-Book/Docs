INuiFusionReconstruction::ExportVolumeBlock Method  
==================================================  

再構成した3次元形状データを配列にエクスポートする。 <span id="syntaxSection"></span>

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
HRESULT ExportVolumeBlock(  
         UINT sourceOriginX,  
         UINT sourceOriginY,  
         UINT sourceOriginZ,  
         UINT destinationResolutionX,  
         UINT destinationResolutionY,  
         UINT destinationResolutionZ,  
         UINT voxelStep,  
         UINT cbVolumeBlock,  
         SHORT *pVolumeBlock  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sourceOriginX*    
Type: UINT  
出力を開始するX座標。  
この値は、0以上、X軸の再構成に使われるボクセル数以下である必要があります。  
再構成された3次元形状データをすべて出力するには0を指定する。  

*sourceOriginY*    
Type: UINT  
出力を開始するY座標。  
この値は、0以上、Y軸の再構成に使われるボクセル数以下である必要があります。  
再構成された3次元形状データをすべて出力するには0を指定する。  

*sourceOriginZ*    
Type: UINT  
出力を開始するZ座標。  
この値は、0以上、Z軸の再構成に使われるボクセル数以下である必要があります。  
再構成された3次元形状データをすべて出力するには0を指定する。  

*destinationResolutionX*    
Type: UINT  
出力先のX軸方向の解像度。  
この値は、0より大きく、X軸の再構成に使われるボクセル数以下である必要があります。  
また、X軸の出力される大きさ(sourceOriginX + (destinationResolutionX × voxelStep))がX軸の再構成に使われるボクセル数を超えることはできません。  

*destinationResolutionY*    
Type: UINT  
出力先のY軸方向の解像度。  
この値は、0より大きく、Y軸の再構成に使われるボクセル数以下である必要があります。  
また、Y軸の出力される大きさ(sourceOriginY + (destinationResolutionY × voxelStep))がY軸の再構成に使われるボクセル数を超えることはできません。  

*destinationResolutionZ*    
Type: UINT  
出力先のZ軸方向の解像度。  
この値は、0より大きく、Z軸の再構成に使われるボクセル数以下である必要があります。  
また、Z軸の出力される大きさ(sourceOriginZ + (destinationResolutionZ × voxelStep))がZ軸の再構成に使われるボクセル数を超えることはできません。  

*voxelStep*    
Type: UINT  
再構成された3次元形状データをサンプリングするステップ値。  
このステップ値は、0より大きく、各軸の再構成に使われるボクセル数以下である必要があります。  
再構成された3次元形状データの解像度を落とさずに配列にエクスポートする場合は1を指定します。  
大きな値を指定するとエクスポートされるデータの解像度が低くなります。  
たとえば、再構成された3次元形状データが640×640×640の解像度であるときに320×320×320の解像度で配列にエクスポートしたい場合は、2を指定します。  
ただし、スキップされたデータは失われます。  

| ![](../../../../../../resources/note.gif)Note                                                                                    |
|----------------------------------------------------------------------------------------------------------------------------------|
| 1より大きい値を指定すると3次元形状データの詳細な情報が失われる危険があります。 |

*cbVolumeBlock*    
Type: UINT  
再構成された3次元形状データを出力する配列のサイズ。(Byte)  

*pVolumeBlock*    
Type: SHORT  
再構成された3次元形状データを出力する配列のアドレス。  
この配列は(destinationResolutionX × destinationResolutionY × destinationResolutionZ)の要素数で確保する必要があります。  
座標(x, y, z)のデータには、  

    SHORT voxel = pVolumeBlock[z][y][x];  

または、  

    UINT pitch = destinationResolutionX;  
    UINT slice = (destinationResolutionY * pitch);  
    UINT index = (z * slice) + (y * pitch) + x;  
    SHORT voxel = pVolumeBlock[index];  

としてアクセスします。  

| ![](../../../../../../resources/note.gif)Note                                                                                                                                                                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 右手座標系で立方体の前面左上(0, 0, 0)が原点です。X軸は原点より右側にいくにつれ増加、Y軸は原点より下側にいくにつれ増加、Z軸は原点から手前にいくにつれ増加します。 |

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
TOCTitle : ExportVolumeBlock Method
RLTitle : INuiFusionReconstruction::ExportVolumeBlock Method
KeywordK : ExportVolumeBlock method
KeywordK : INuiFusionReconstruction::ExportVolumeBlock method
KeywordF : INuiFusionReconstruction::ExportVolumeBlock
KeywordF : ExportVolumeBlock
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ExportVolumeBlock(UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,SHORT)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ExportVolumeBlock(UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,SHORT)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction.ExportVolumeBlock(UINT,UINT,UINT,UINT,UINT,UINT,UINT,UINT,SHORT)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.INuiFusionReconstruction::ExportVolumeBlock
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
