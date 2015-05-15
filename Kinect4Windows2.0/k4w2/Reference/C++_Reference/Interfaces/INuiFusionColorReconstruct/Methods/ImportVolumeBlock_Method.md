INuiFusionColorReconstruction::ImportVolumeBlock Method  
=======================================================  

配列から3次元形状データと色データをインポートする。 <span id="syntaxSection"></span>

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
HRESULT ImportVolumeBlock(  
         UINT cbVolumeBlock,  
         UINT cbColorVolumeBlock,  
         const SHORT *pVolumeBlock,  
         const INT *pColorVolumeBlock  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*cbVolumeBlock*    
Type: UINT  
インポートする3次元形状データの配列のサイズ。(Byte)    

*cbColorVolumeBlock*    
Type: UINT  
インポートする色データの配列のサイズ。(Byte)  

*pVolumeBlock*    
Type: SHORT  
インポートする3次元形状データの配列のアドレス。  

*pColorVolumeBlock*    
Type: INT  
インポートする色データの配列のアドレス。  

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
TOCTitle : ImportVolumeBlock Method
RLTitle : INuiFusionColorReconstruction::ImportVolumeBlock Method
KeywordK : ImportVolumeBlock method
KeywordK : INuiFusionColorReconstruction::ImportVolumeBlock method
KeywordF : INuiFusionColorReconstruction::ImportVolumeBlock
KeywordF : ImportVolumeBlock
KeywordF : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ImportVolumeBlock(UINT,UINT,SHORT,INT)
KeywordA : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ImportVolumeBlock(UINT,UINT,SHORT,INT)
AssetID : M:Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction.ImportVolumeBlock(UINT,UINT,SHORT,INT)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncolorvolume.INuiFusionColorReconstruction::ImportVolumeBlock
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
