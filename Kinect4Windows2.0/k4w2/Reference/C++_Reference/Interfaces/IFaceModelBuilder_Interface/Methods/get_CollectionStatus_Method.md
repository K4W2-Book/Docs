IFaceModelBuilder::get\_CollectionStatus Method  
===============================================  

データ収集ステータスを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_CollectionStatus(  
         FaceModelBuilderCollectionStatus *currrentCollectionStatus  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*currrentCollectionStatus*    
Type: FaceModelBuilderCollectionStatus  
[out] データ収集ステータス。  

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
TOCTitle : get_CollectionStatus Method
RLTitle : IFaceModelBuilder::get_CollectionStatus Method
KeywordK : get_CollectionStatus method
KeywordK : IFaceModelBuilder::get_CollectionStatus method
KeywordF : IFaceModelBuilder::get_CollectionStatus
KeywordF : get_CollectionStatus
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.get_CollectionStatus(FaceModelBuilderCollectionStatus@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.get_CollectionStatus(FaceModelBuilderCollectionStatus@)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.get_CollectionStatus(FaceModelBuilderCollectionStatus@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::get_CollectionStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
