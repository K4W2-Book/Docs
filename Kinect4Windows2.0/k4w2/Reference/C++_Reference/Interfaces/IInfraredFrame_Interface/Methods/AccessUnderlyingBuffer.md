IInfraredFrame::AccessUnderlyingBuffer Method  
=============================================  

Infraredフレームのデータを取得する。(ポインタ参照) <span id="syntaxSection"></span>

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
HRESULT AccessUnderlyingBuffer(  
         UINT *capacity,  
         UINT16 **buffer  
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
Type: UINT16  
[out] データへのポインタ。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

このポインタはIInfraredFrameが解放されるまで有効です。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : AccessUnderlyingBuffer Method
RLTitle : IInfraredFrame::AccessUnderlyingBuffer Method
KeywordK : AccessUnderlyingBuffer method
KeywordK : IInfraredFrame::AccessUnderlyingBuffer method
KeywordF : IInfraredFrame::AccessUnderlyingBuffer
KeywordF : AccessUnderlyingBuffer
KeywordF : Microsoft.Kinect.kinect.IInfraredFrame.AccessUnderlyingBuffer(UINT@,UINT16@)
KeywordA : M:Microsoft.Kinect.kinect.IInfraredFrame.AccessUnderlyingBuffer(UINT@,UINT16@)
AssetID : M:Microsoft.Kinect.kinect.IInfraredFrame.AccessUnderlyingBuffer(UINT@,UINT16@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IInfraredFrame::AccessUnderlyingBuffer
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
