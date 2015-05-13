NuiFusionAlignPointClouds  
=========================  

Point Cloudデータを位置合わせして相対的なカメラ姿勢を計算する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionAlignPointClouds(  
         const NUI_FUSION_IMAGE_FRAME *pReferencePointCloudFrame,  
         const NUI_FUSION_IMAGE_FRAME *pObservedPointCloudFrame,  
         USHORT maxAlignIterationCount,  
         const NUI_FUSION_IMAGE_FRAME *pDeltaFromReferenceFrame,  
         Matrix4 *pReferenceToObservedTransform  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pReferencePointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in] 位置合わせの基準になるPoint Cloudデータ。  

*pObservedPointCloudFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[in] 位置合わせするPoint　Cloudデータ。  

*maxAlignIterationCount*    
Type: USHORT  
[in] 位置合わせのための反復アルゴリズムの最大反復回数。  

*pDeltaFromReferenceFrame*    
Type: NUI\_FUSION\_IMAGE\_FRAME  
[out, optional] オプションのカメラトラッキング結果を色分けした画像データを受け取る画像バッファ(Color)。  
この画像データはオブジェクトセグメンテーションなどのコンピュータビジョンのアルゴリズムへの入力データとして利用できます。  
このデータを必要としない場合、nullptrを指定します。  

画像データの値はカメラトラッキングに使用された有効な画素(インライア)か無効な画素(アウトトライア)かによって異なります。  
インライアの場合、値は位置合わせアルゴリズムの残留エネルギーによって色分けされます。  
頂点があまり一致しない画素は濃い色、頂点が一致している画素は薄い色で示されます。  
アウトライアの場合、値は以下の表のいずれかです。  

| Value      | Description                                                                                                                                                |
|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0xFF000000 | 入力された頂点が無効(値が0など)だった。または、2つのPoint Cloudデータの間に対応する頂点がなかった。 |
| 0xFF008000 | 頂点間の距離が離れすぎているため、この画素のデータは利用しませんでした。                                                                           |
| 0xFF800000 | 頂点間の角度が離れすぎているため、この画素のデータは利用しませんでした。                                                 |

*pReferenceToObservedTransform*    
Type: Matrix4  
[in, out] 位置合わせの初期推定に利用する変換行列。位置合わせが成功した場合、変換行列は更新されます。  

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
TOCTitle : NuiFusionAlignPointClouds
RLTitle : NuiFusionAlignPointClouds
KeywordK : NuiFusionAlignPointClouds
KeywordF : NuiFusionAlignPointClouds
KeywordF : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionAlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,Matrix4@)
KeywordA : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionAlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,Matrix4@)
AssetID : M:Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionAlignPointClouds(NUI_FUSION_IMAGE_FRAME,NUI_FUSION_IMAGE_FRAME,USHORT,NUI_FUSION_IMAGE_FRAME,Matrix4@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusiondepthprocessor.NuiFusionAlignPointClouds
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
