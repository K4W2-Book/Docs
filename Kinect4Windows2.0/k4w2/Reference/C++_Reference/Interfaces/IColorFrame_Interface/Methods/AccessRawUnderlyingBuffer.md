IColorFrame::AccessRawUnderlyingBuffer Method  
=============================================  

Colorフレームのデータを取得する。(ポインタ参照) <span id="syntaxSection"></span>

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
HRESULT AccessRawUnderlyingBuffer(  
         UINT *capacity,  
         BYTE **buffer  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
[out] データのサイズ。(Byte)  

*buffer*    
Type: BYTE  
[out] データへのポインタ。  

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
TOCTitle : AccessRawUnderlyingBuffer Method
RLTitle : IColorFrame::AccessRawUnderlyingBuffer Method
KeywordK : AccessRawUnderlyingBuffer method
KeywordK : IColorFrame::AccessRawUnderlyingBuffer method
KeywordF : IColorFrame::AccessRawUnderlyingBuffer
KeywordF : AccessRawUnderlyingBuffer
KeywordF : Microsoft.Kinect.kinect.IColorFrame.AccessRawUnderlyingBuffer(UINT@,BYTE@)
KeywordA : M:Microsoft.Kinect.kinect.IColorFrame.AccessRawUnderlyingBuffer(UINT@,BYTE@)
AssetID : M:Microsoft.Kinect.kinect.IColorFrame.AccessRawUnderlyingBuffer(UINT@,BYTE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrame::AccessRawUnderlyingBuffer
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
