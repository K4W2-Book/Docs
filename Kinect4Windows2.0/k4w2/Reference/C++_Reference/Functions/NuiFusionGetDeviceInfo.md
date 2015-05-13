NuiFusionGetDeviceInfo  
======================  

Kinect Fusionの3次元形状の再構成処理に使用するプロセッサーの情報を取得する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT FUSIONAPI NuiFusionGetDeviceInfo(  
         _NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE type,  
         INT index,  
         PWSTR pDescription,  
         UINT descriptionSizeInChars,  
         PWSTR pInstancePath,  
         UINT instancePathSizeInChars,  
         UINT *pMemoryKB  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*type*    
Type: \_NUI\_FUSION\_RECONSTRUCTION\_PROCESSOR\_TYPE  
[in] 3次元形状の再構成処理に使用するプロセッサー。  

*index*    
Type: INT  
[in] 3次元形状の再構成処理に使用するプロセッサーのID。  
-1を指定するとデフォルトのプロセッサーが使用されます。  

*pDescription*    
Type: PWSTR  
プロセッサーの名前。  
不要な場合はnullptrを指定する。

*descriptionSizeInChars*    
Type: UINT  
[in] プロセッサーの名前のサイズ(Byte)。  

*pInstancePath*    
Type: PWSTR  
プロセッサーのインスタントパス。  

*instancePathSizeInChars*    
Type: UINT  
[in] プロセッサーのインスタントパスのサイズ(Byte)。  

*pMemoryKB*    
Type: UINT  
[out, optional] プロセッサーの利用できるメモリサイズ(KByte)。  

<span id="ID4EN"></span>
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
TOCTitle : NuiFusionGetDeviceInfo
RLTitle : NuiFusionGetDeviceInfo
KeywordK : NuiFusionGetDeviceInfo
KeywordF : NuiFusionGetDeviceInfo
KeywordF : Microsoft.Kinect.nuikinectfusionvolume.NuiFusionGetDeviceInfo(_NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,PWSTR,UINT,PWSTR,UINT,UINT@)
KeywordA : M:Microsoft.Kinect.nuikinectfusionvolume.NuiFusionGetDeviceInfo(_NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,PWSTR,UINT,PWSTR,UINT,UINT@)
AssetID : M:Microsoft.Kinect.nuikinectfusionvolume.NuiFusionGetDeviceInfo(_NUI_FUSION_RECONSTRUCTION_PROCESSOR_TYPE,INT,PWSTR,UINT,PWSTR,UINT,UINT@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusionvolume.NuiFusionGetDeviceInfo
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
