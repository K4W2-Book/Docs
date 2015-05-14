IHighDefinitionFaceFrameReader::GetFrameArrivedEventData Method  
=================================================  

新しいHDFaceフレームが準備できたとき、イベントデータを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetFrameArrivedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         IHighDefinitionFaceFrameArrivedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] HDFaceフレームの更新を待つイベントハンドル。  

*eventData*    
Type: IHighDefinitionFaceFrameArrivedEventArgs  
[out] HDFaceフレームのイベントデータ。  

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
TOCTitle : GetFrameArrivedEventData Method
RLTitle : IHighDefinitionFaceFrameReader::GetFrameArrivedEventData Method
KeywordK : GetFrameArrivedEventData method
KeywordK : IHighDefinitionFaceFrameReader::GetFrameArrivedEventData method
KeywordF : IHighDefinitionFaceFrameReader::GetFrameArrivedEventData
KeywordF : GetFrameArrivedEventData
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.GetFrameArrivedEventData(WAITABLE_HANDLE,IHighDefinitionFaceFrameArrivedEventArgs@)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.GetFrameArrivedEventData(WAITABLE_HANDLE,IHighDefinitionFaceFrameArrivedEventArgs@)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameReader.GetFrameArrivedEventData(WAITABLE_HANDLE,IHighDefinitionFaceFrameArrivedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameReader::GetFrameArrivedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
