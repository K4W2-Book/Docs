IBodyFrameSource::UnsubscribeFrameCaptured Method  
=================================================  

最新のフレームが準備できたとき、またはフレームを破棄したときに発効するイベントハンドルを解除する。 <span id="syntaxSection"></span>

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
HRESULT UnsubscribeFrameCaptured(  
         WAITABLE_HANDLE waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] 解除するイベントハンドル。  

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
TOCTitle : UnsubscribeFrameCaptured Method
RLTitle : IBodyFrameSource::UnsubscribeFrameCaptured Method
KeywordK : UnsubscribeFrameCaptured method
KeywordK : IBodyFrameSource::UnsubscribeFrameCaptured method
KeywordF : IBodyFrameSource::UnsubscribeFrameCaptured
KeywordF : UnsubscribeFrameCaptured
KeywordF : Microsoft.Kinect.kinect.IBodyFrameSource.UnsubscribeFrameCaptured(WAITABLE_HANDLE)
KeywordA : M:Microsoft.Kinect.kinect.IBodyFrameSource.UnsubscribeFrameCaptured(WAITABLE_HANDLE)
AssetID : M:Microsoft.Kinect.kinect.IBodyFrameSource.UnsubscribeFrameCaptured(WAITABLE_HANDLE)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrameSource::UnsubscribeFrameCaptured
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
