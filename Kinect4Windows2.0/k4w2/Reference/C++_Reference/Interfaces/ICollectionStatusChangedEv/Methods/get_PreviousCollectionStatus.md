ICollectionStatusChangedEventArgs::get\_PreviousCollectionStatus Method  
=======================================================================  

[IFaceModelBuilder](../../IFaceModelBuilder_Interface.md)のデータ収集ステータスが更新されたとき、ステータスを取得します。 <span id="syntaxSection"></span>

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
HRESULT get_PreviousCollectionStatus(  
         FaceModelBuilderCollectionStatus *pCollectionStatus  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*pCollectionStatus*    
Type: FaceModelBuilderCollectionStatus  
[out] FaceModelBuilderのデータ収集ステータス。  

<span id="ID4ET"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_PreviousCollectionStatus Method
RLTitle : ICollectionStatusChangedEventArgs::get_PreviousCollectionStatus Method
KeywordK : get_PreviousCollectionStatus method
KeywordK : ICollectionStatusChangedEventArgs::get_PreviousCollectionStatus method
KeywordF : ICollectionStatusChangedEventArgs::get_PreviousCollectionStatus
KeywordF : get_PreviousCollectionStatus
KeywordF : Microsoft.Kinect.face.ICollectionStatusChangedEventArgs.get_PreviousCollectionStatus(FaceModelBuilderCollectionStatus@)
KeywordA : M:Microsoft.Kinect.face.ICollectionStatusChangedEventArgs.get_PreviousCollectionStatus(FaceModelBuilderCollectionStatus@)
AssetID : M:Microsoft.Kinect.face.ICollectionStatusChangedEventArgs.get_PreviousCollectionStatus(FaceModelBuilderCollectionStatus@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.ICollectionStatusChangedEventArgs::get_PreviousCollectionStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
