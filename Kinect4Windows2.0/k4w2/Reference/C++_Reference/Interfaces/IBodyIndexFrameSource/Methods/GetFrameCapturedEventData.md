IBodyIndexFrameSource::GetFrameCapturedEventData Method  
=======================================================  

最新のフレームが準備できたとき、イベントデータを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetFrameCapturedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         IFrameCapturedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] 最新のフレームの更新を待つイベントハンドル。  

*eventData*    
Type: IFrameCapturedEventArgs  
[out] [IFrameCapturedEventArgs](../../IFrameCapturedEventArgs.md)のポインタのアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetFrameCapturedEventData Method
RLTitle : IBodyIndexFrameSource::GetFrameCapturedEventData Method
KeywordK : GetFrameCapturedEventData method
KeywordK : IBodyIndexFrameSource::GetFrameCapturedEventData method
KeywordF : IBodyIndexFrameSource::GetFrameCapturedEventData
KeywordF : GetFrameCapturedEventData
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrameSource.GetFrameCapturedEventData(WAITABLE_HANDLE,IFrameCapturedEventArgs@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyIndexFrameSource.GetFrameCapturedEventData(WAITABLE_HANDLE,IFrameCapturedEventArgs@)
AssetID : M:Microsoft.Kinect.kinect.IBodyIndexFrameSource.GetFrameCapturedEventData(WAITABLE_HANDLE,IFrameCapturedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrameSource::GetFrameCapturedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
