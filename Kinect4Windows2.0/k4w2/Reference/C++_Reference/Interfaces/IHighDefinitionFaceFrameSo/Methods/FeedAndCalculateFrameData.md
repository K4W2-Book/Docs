IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData Method  
================================================================  

HDFaceフレームを計算する。 <span id="syntaxSection"></span>

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
HRESULT FeedAndCalculateFrameData(  
         IBody *body,  
         UINT infraredCapacity,  
         UINT16 *infraredFrameBuffer,  
         UINT colorCapacity,  
         BYTE *colorFrameBuffer,  
         UINT depthCapacity,  
         UINT16 *depthFrameBuffer  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*body*    
Type: IBody  
[in] 計算に使用するBodyデータ。  

*infraredCapacity*    
Type: UINT  
Infrared画像バッファのサイズ。  

*infraredFrameBuffer*    
Type: UINT16  
[in] 計算に使用するInfrared画像バッファ。  

*colorCapacity*    
Type: UINT  
Color画像バッファのサイズ。  

*colorFrameBuffer*    
Type: BYTE  
[in] 計算に使用するColor画像バッファ。  

*depthCapacity*    
Type: UINT  
Depth画像バッファのサイズ。  

*depthFrameBuffer*    
Type: UINT16  
[in] 計算に使用するDepth画像バッファ。  

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
TOCTitle : FeedAndCalculateFrameData Method
RLTitle : IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData Method
KeywordK : FeedAndCalculateFrameData method
KeywordK : IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData method
KeywordF : IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData
KeywordF : FeedAndCalculateFrameData
KeywordF : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.FeedAndCalculateFrameData(IBody,UINT,UINT16,UINT,BYTE,UINT,UINT16)
KeywordA : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.FeedAndCalculateFrameData(IBody,UINT,UINT16,UINT,BYTE,UINT,UINT16)
AssetID : M:Microsoft.Kinect.face.IHighDefinitionFaceFrameSource.FeedAndCalculateFrameData(IBody,UINT,UINT16,UINT,BYTE,UINT,UINT16)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IHighDefinitionFaceFrameSource::FeedAndCalculateFrameData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
