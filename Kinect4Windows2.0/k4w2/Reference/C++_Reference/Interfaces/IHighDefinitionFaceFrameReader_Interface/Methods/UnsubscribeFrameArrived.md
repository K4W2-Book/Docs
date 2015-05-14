IHighDefinitionFaceFrameReader::UnsubscribeFrameArrived Method  
================================================  

HDFaceフレームの更新を待つイベントハンドルを解除する。 <span id="syntaxSection"></span>

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
HRESULT UnsubscribeFrameArrived(  
         WAITABLE_HANDLE waitableHandle  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] HDFaceフレームの更新を待つイベントハンドル。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : UnsubscribeFrameArrived Method
RLTitle : IHighDefinitionFaceFrameReader::UnsubscribeFrameArrived Method
KeywordK : UnsubscribeFrameArrived method
KeywordK : IHighDefinitionFaceFrameReader::UnsubscribeFrameArrived method
KeywordF : IHighDefinitionFaceFrameReader::UnsubscribeFrameArrived
KeywordF : UnsubscribeFrameArrived
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.UnsubscribeFrameArrived(WAITABLE_HANDLE)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.UnsubscribeFrameArrived(WAITABLE_HANDLE)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.UnsubscribeFrameArrived(WAITABLE_HANDLE)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader::UnsubscribeFrameArrived
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
