IFaceModelBuilder::GetCollectionStatusChangedEventData Method  
=============================================================  

データ収集ステータスが変更されたとき、イベントデータを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetCollectionStatusChangedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         ICollectionStatusChangedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] データ収集ステータスが変更されたとき発行するイベントハンドル。  

*eventData*    
Type: ICollectionStatusChangedEventArgs  
[out] データ収集ステータスが変更されたときのイベントデータ。  

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
TOCTitle : GetCollectionStatusChangedEventData Method
RLTitle : IFaceModelBuilder::GetCollectionStatusChangedEventData Method
KeywordK : GetCollectionStatusChangedEventData method
KeywordK : IFaceModelBuilder::GetCollectionStatusChangedEventData method
KeywordF : IFaceModelBuilder::GetCollectionStatusChangedEventData
KeywordF : GetCollectionStatusChangedEventData
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.GetCollectionStatusChangedEventData(WAITABLE_HANDLE,ICollectionStatusChangedEventArgs@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.GetCollectionStatusChangedEventData(WAITABLE_HANDLE,ICollectionStatusChangedEventArgs@)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.GetCollectionStatusChangedEventData(WAITABLE_HANDLE,ICollectionStatusChangedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::GetCollectionStatusChangedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
