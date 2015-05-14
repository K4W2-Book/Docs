IFaceModelBuilder::SubscribeCollectionStatusChanged Method  
==========================================================  

データ収集ステータスが変更されたとき発効するイベントハンドルを登録する。 <span id="syntaxSection"></span>

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
HRESULT SubscribeCollectionStatusChanged(  
         WAITABLE_HANDLE *waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[out] データ収集ステータスが変更されたとき発効するイベントハンドル。  

<span id="ID4EP"></span>
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
TOCTitle : SubscribeCollectionStatusChanged Method
RLTitle : IFaceModelBuilder::SubscribeCollectionStatusChanged Method
KeywordK : SubscribeCollectionStatusChanged method
KeywordK : IFaceModelBuilder::SubscribeCollectionStatusChanged method
KeywordF : IFaceModelBuilder::SubscribeCollectionStatusChanged
KeywordF : SubscribeCollectionStatusChanged
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.SubscribeCollectionStatusChanged(WAITABLE_HANDLE@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.SubscribeCollectionStatusChanged(WAITABLE_HANDLE@)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.SubscribeCollectionStatusChanged(WAITABLE_HANDLE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::SubscribeCollectionStatusChanged
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
