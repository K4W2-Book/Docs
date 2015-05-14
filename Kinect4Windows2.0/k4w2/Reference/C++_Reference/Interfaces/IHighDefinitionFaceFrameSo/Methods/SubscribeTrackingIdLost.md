IHighDefinitionFaceFrameSource::SubscribeTrackingIdLost Method  
==============================================================  

トラッキングIDがロストしたとき発効するイベントハンドルを登録する。 <span id="syntaxSection"></span>

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
HRESULT SubscribeTrackingIdLost(  
         WAITABLE_HANDLE *waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[out] トラッキングIDがロストしたとき発効するイベントハンドル。  

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
TOCTitle : SubscribeTrackingIdLost Method
RLTitle : IHighDefinitionFaceFrameSource::SubscribeTrackingIdLost Method
KeywordK : SubscribeTrackingIdLost method
KeywordK : IHighDefinitionFaceFrameSource::SubscribeTrackingIdLost method
KeywordF : IHighDefinitionFaceFrameSource::SubscribeTrackingIdLost
KeywordF : SubscribeTrackingIdLost
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.SubscribeTrackingIdLost(WAITABLE_HANDLE@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.SubscribeTrackingIdLost(WAITABLE_HANDLE@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.SubscribeTrackingIdLost(WAITABLE_HANDLE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::SubscribeTrackingIdLost
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
