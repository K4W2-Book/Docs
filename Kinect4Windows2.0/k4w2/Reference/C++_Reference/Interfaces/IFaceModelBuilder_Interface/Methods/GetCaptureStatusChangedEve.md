IFaceModelBuilder::GetCaptureStatusChangedEventData Method  
==========================================================  

キャプチャステータスが変更されたとき、イベントデータを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetCaptureStatusChangedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         ICaptureStatusChangedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] キャプチャステータスが変更されたとき発効するイベントハンドル。  

*eventData*    
Type: ICaptureStatusChangedEventArgs  
[out] キャプチャステータスが変更されたときのイベントデータ。  

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
TOCTitle : GetCaptureStatusChangedEventData Method
RLTitle : IFaceModelBuilder::GetCaptureStatusChangedEventData Method
KeywordK : GetCaptureStatusChangedEventData method
KeywordK : IFaceModelBuilder::GetCaptureStatusChangedEventData method
KeywordF : IFaceModelBuilder::GetCaptureStatusChangedEventData
KeywordF : GetCaptureStatusChangedEventData
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder.GetCaptureStatusChangedEventData(WAITABLE_HANDLE,ICaptureStatusChangedEventArgs@)
KeywordA : M:Microsoft.Kinect.face.IFaceModelBuilder.GetCaptureStatusChangedEventData(WAITABLE_HANDLE,ICaptureStatusChangedEventArgs@)
AssetID : M:Microsoft.Kinect.face.IFaceModelBuilder.GetCaptureStatusChangedEventData(WAITABLE_HANDLE,ICaptureStatusChangedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder::GetCaptureStatusChangedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
