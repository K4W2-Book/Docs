IMultiSourceFrameReader::SubscribeMultiSourceFrameArrived Method  
================================================================  

MultiSourceフレームの更新を待つイベントハンドルを登録する。 <span id="syntaxSection"></span>

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
HRESULT SubscribeMultiSourceFrameArrived(  
         WAITABLE_HANDLE *waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[out] MultiSourceフレームの更新を待つイベントハンドル。  

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
TOCTitle : SubscribeMultiSourceFrameArrived Method
RLTitle : IMultiSourceFrameReader::SubscribeMultiSourceFrameArrived Method
KeywordK : SubscribeMultiSourceFrameArrived method
KeywordK : IMultiSourceFrameReader::SubscribeMultiSourceFrameArrived method
KeywordF : IMultiSourceFrameReader::SubscribeMultiSourceFrameArrived
KeywordF : SubscribeMultiSourceFrameArrived
KeywordF : Microsoft.Kinect.kinect.IMultiSourceFrameReader.SubscribeMultiSourceFrameArrived(WAITABLE_HANDLE@)
KeywordA : M:Microsoft.Kinect.kinect.IMultiSourceFrameReader.SubscribeMultiSourceFrameArrived(WAITABLE_HANDLE@)
AssetID : M:Microsoft.Kinect.kinect.IMultiSourceFrameReader.SubscribeMultiSourceFrameArrived(WAITABLE_HANDLE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IMultiSourceFrameReader::SubscribeMultiSourceFrameArrived
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
