IMultiSourceFrameReader::GetMultiSourceFrameArrivedEventData Method  
===================================================================  

新しい長時間露光MultiSourceフレームが準備できたとき、イベントデータを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetMultiSourceFrameArrivedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         IMultiSourceFrameArrivedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] MultiSourceフレームの更新を待つイベントハンドル。  

*eventData*    
Type: IMultiSourceFrameArrivedEventArgs  
[out] [IMultiSourceFrameArrivedEventArgs](../../IMultiSourceFrameArrivedEv.md)のポインタのアドレス。  

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
TOCTitle : GetMultiSourceFrameArrivedEventData Method
RLTitle : IMultiSourceFrameReader::GetMultiSourceFrameArrivedEventData Method
KeywordK : GetMultiSourceFrameArrivedEventData method
KeywordK : IMultiSourceFrameReader::GetMultiSourceFrameArrivedEventData method
KeywordF : IMultiSourceFrameReader::GetMultiSourceFrameArrivedEventData
KeywordF : GetMultiSourceFrameArrivedEventData
KeywordF : Microsoft.Kinect.kinect.IMultiSourceFrameReader.GetMultiSourceFrameArrivedEventData(WAITABLE_HANDLE,IMultiSourceFrameArrivedEventArgs@)
KeywordA : M:Microsoft.Kinect.kinect.IMultiSourceFrameReader.GetMultiSourceFrameArrivedEventData(WAITABLE_HANDLE,IMultiSourceFrameArrivedEventArgs@)
AssetID : M:Microsoft.Kinect.kinect.IMultiSourceFrameReader.GetMultiSourceFrameArrivedEventData(WAITABLE_HANDLE,IMultiSourceFrameArrivedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IMultiSourceFrameReader::GetMultiSourceFrameArrivedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
