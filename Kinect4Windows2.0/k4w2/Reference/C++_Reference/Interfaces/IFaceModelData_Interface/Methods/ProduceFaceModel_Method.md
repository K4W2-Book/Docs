IFaceModelData::ProduceFaceModel Method  
=======================================  

顔形状データから顔モデルを生成する。 <span id="syntaxSection"></span>

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
HRESULT ProduceFaceModel(  
         IFaceModel **faceModel  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceModel*    
Type: IFaceModel  
[out] IFaceModelのポインタのアドレス。  

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
TOCTitle : ProduceFaceModel Method
RLTitle : IFaceModelData::ProduceFaceModel Method
KeywordK : ProduceFaceModel method
KeywordK : IFaceModelData::ProduceFaceModel method
KeywordF : IFaceModelData::ProduceFaceModel
KeywordF : ProduceFaceModel
KeywordF : Microsoft.Kinect.face.IFaceModelData.ProduceFaceModel(IFaceModel@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelData.ProduceFaceModel(IFaceModel@)
AssetID : M:Microsoft.Kinect.face.IFaceModelData.ProduceFaceModel(IFaceModel@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelData::ProduceFaceModel
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
