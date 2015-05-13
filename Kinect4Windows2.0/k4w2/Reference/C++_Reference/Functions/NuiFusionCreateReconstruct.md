NuiFusionCreateReconstruction  
=============================  

[INuiFusionReconstruction](../Interfaces/INuiFusionReconstruction.md)を作成する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionCreateReconstruction(  
         const NUI_FUSION_RECONSTRUCTION_PARAMETERS *pReconstructionParameters,  
         NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE reconstructionProcessorType,  
         INT deviceIndex,  
         const Matrix4 *pInitialWorldToCameraTransform,  
         INuiFusionReconstruction **ppNuiFusionReconstruction  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EL"></span>
#### Parameters  

*pReconstructionParameters*    
Type: NUI\_FUSION\_RECONSTRUCTION\_PARAMETERS  
[in] 3次元形状の再構成パラメーター。  

*reconstructionProcessorType*    
Type: NUI\_FUSION\_RECONSTRUCTION\_PROCESSOR\_TYPE  
[in] 3次元形状の再構成処理に使用するプロセッサー。  

*deviceIndex*    
Type: INT  
[in] 3次元形状の再構成処理に使用するプロセッサーのID。  
-1を指定するとデフォルトのプロセッサーが使用されます。  

*pInitialWorldToCameraTransform*    
Type: Matrix4  
[in, optional] ワールド座標系からカメラ座標系への初期変換行列。  

*ppNuiFusionReconstruction*    
Type: INuiFusionReconstruction  
[out] INuiFusionReconstructionのポインタのアドレス。  

<span id="ID4ES"></span>
#### Return value  

Type: HRESULT FUSIONAPI  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusionvolume.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NuiFusionCreateReconstruction
RLTitle : NuiFusionCreateReconstruction
KeywordK : NuiFusionCreateReconstruction
KeywordF : NuiFusionCreateReconstruction
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.NuiFusionCreateReconstruction(NUI_FUSION_RECONSTRUCTION_PARAMETERS,NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,Matrix4,INuiFusionReconstruction@)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.NuiFusionCreateReconstruction(NUI_FUSION_RECONSTRUCTION_PARAMETERS,NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,Matrix4,INuiFusionReconstruction@)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.NuiFusionCreateReconstruction(NUI_FUSION_RECONSTRUCTION_PARAMETERS,NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,Matrix4,INuiFusionReconstruction@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.NuiFusionCreateReconstruction
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
