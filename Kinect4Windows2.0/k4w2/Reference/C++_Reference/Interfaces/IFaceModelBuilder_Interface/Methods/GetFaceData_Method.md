IFaceModelBuilder::GetFaceData Method  
=====================================  

収集した顔形状データを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetFaceData(  
         IFaceModelData **faceModelData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceModelData*    
Type: IFaceModelData  
[out] IFaceModelDataのポインタのアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetFaceData Method
RLTitle : IFaceModelBuilder::GetFaceData Method
KeywordK : GetFaceData method
KeywordK : IFaceModelBuilder::GetFaceData method
KeywordF : IFaceModelBuilder::GetFaceData
KeywordF : GetFaceData
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.GetFaceData(IFaceModelData@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.GetFaceData(IFaceModelData@)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.GetFaceData(IFaceModelData@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::GetFaceData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
