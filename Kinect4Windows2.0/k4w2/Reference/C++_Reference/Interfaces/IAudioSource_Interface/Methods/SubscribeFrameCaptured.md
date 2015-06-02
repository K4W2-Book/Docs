IAudioSource::SubscribeFrameCaptured Method  
===========================================  

最新のフレームが準備できたとき、またはフレームを破棄したときに発効するイベントハンドルを登録する。 <span id="syntaxSection"></span>

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
HRESULT SubscribeFrameCaptured(  
         WAITABLE_HANDLE *waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[out] 登録するイベントハンドル。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

アプリケーションは、任意の時点で1つのフレームのみ保持することができます。  
このイベントは、最新のフレームがすべてのReaderで取得できるように、現在保持されているフレームを解放するために使用することができます。  
アプリケーションが古いフレームを解放しない場合、このイベントは最新のフレームを破棄したことを通知するために発効されます。  

このイベントが発効したとき、アプリケーションは[IFrameCapturedEventArgs](../../IFrameCapturedEventArgs.md)を取得するために[GetFrameCapturedEventData](GetFrameCapturedEventData.md)を呼ぶ必要があります。  
最新のフレームが準備できたのか破棄されたのかを知るためには[IFrameCapturedEventArgs::get_FrameStatus](../../IFrameCapturedEventArgs/Methods/get_FrameStatus_Method.md)でステータスを取得してください。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SubscribeFrameCaptured Method
RLTitle : IAudioSource::SubscribeFrameCaptured Method
KeywordK : SubscribeFrameCaptured method
KeywordK : IAudioSource::SubscribeFrameCaptured method
KeywordF : IAudioSource::SubscribeFrameCaptured
KeywordF : SubscribeFrameCaptured
KeywordF : Microsoft.Kinect.kinect.IAudioSource.SubscribeFrameCaptured(WAITABLE_HANDLE@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioSource.SubscribeFrameCaptured(WAITABLE_HANDLE@)
AssetID : M:Microsoft.Kinect.kinect.IAudioSource.SubscribeFrameCaptured(WAITABLE_HANDLE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource::SubscribeFrameCaptured
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
