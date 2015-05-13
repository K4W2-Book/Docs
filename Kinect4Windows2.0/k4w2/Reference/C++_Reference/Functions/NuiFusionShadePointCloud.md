NuiFusionShadePointCloud  
========================  

Point Cloudデータにシェーディングしてレンダリングされた画像を取得する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionShadePointCloud(  
         const NUI_FUSION_IMAGE_FRAME *pPointCloudFrame,  
         const Matrix4 *pWorldToCameraTransform,  
         const Matrix4 *pWorldToBGRTransform,  
         const NUI_FUSION_IMAGE_FRAME *pShadedSurfaceFrame,  
         const NUI_FUSION_IMAGE_FRAME *pShadedSurfaceNormalsFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pPointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in] Point Cloudデータ。  

*pWorldToCameraTransform*    
Type: Matrix4  
[in] ワールド座標系からカメラ座標系への変換行列。  
Point Cloudデータを作成するときに使用した変換行列を指定する。  

*pWorldToBGRTransform*    
Type: Matrix4  
[in, optional] ワールド座標系からRGB色空間へのマッピング行列。  
Point Cloudデータの座標をもとにレンダリングされたフレームに色付けします。

*pShadedSurfaceFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in, optional] レンダリングされたSurface画像(Color)。  

*pShadedSurfaceNormalsFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in, optional] レンダリングされたNormal画像(Color)  

<span id="ID4EN"></span>
#### Return value  

Type: HRESULT FUSIONAPI  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusiondepthprocessor.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : NuiFusionShadePointCloud
RLTitle : NuiFusionShadePointCloud
KeywordK : NuiFusionShadePointCloud
KeywordF : NuiFusionShadePointCloud
KeywordF : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionShadePointCloud(NUI_FUSION_IMAGE_FRAME,Matrix4,Matrix4,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
KeywordA : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionShadePointCloud(NUI_FUSION_IMAGE_FRAME,Matrix4,Matrix4,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
AssetID : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionShadePointCloud(NUI_FUSION_IMAGE_FRAME,Matrix4,Matrix4,NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionShadePointCloud
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
