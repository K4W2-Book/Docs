IHighDefinitionFaceFrameSource::GetTrackingIdLostEventData Method  
=================================================================  

トラッキングIDがロストしたとき、イベントデータを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetTrackingIdLostEventData(  
         WAITABLE_HANDLE waitableHandle,  
         ITrackingIdLostEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] トラッキングIDがロストしたとき発効するイベントハンドル。  

*eventData*    
Type: ITrackingIdLostEventArgs  
[out] トラッキングIDがロストしたときのイベントデータ。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetTrackingIdLostEventData Method
RLTitle : IHighDefinitionFaceFrameSource::GetTrackingIdLostEventData Method
KeywordK : GetTrackingIdLostEventData method
KeywordK : IHighDefinitionFaceFrameSource::GetTrackingIdLostEventData method
KeywordF : IHighDefinitionFaceFrameSource::GetTrackingIdLostEventData
KeywordF : GetTrackingIdLostEventData
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.GetTrackingIdLostEventData(WAITABLE_HANDLE,ITrackingIdLostEventArgs@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.GetTrackingIdLostEventData(WAITABLE_HANDLE,ITrackingIdLostEventArgs@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.GetTrackingIdLostEventData(WAITABLE_HANDLE,ITrackingIdLostEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::GetTrackingIdLostEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
