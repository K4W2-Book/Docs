IColorFrame::CopyRawFrameDataToArray Method  
===========================================  

ColorフレームのRAWデータを取得する。(コピー) <span id="syntaxSection"></span>

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
HRESULT CopyRawFrameDataToArray(  
         UINT capacity,  
         BYTE *frameData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
データのサイズ。(Byte)  

*frameData*    
Type: BYTE  
[out] データをコピーする配列の先頭アドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

ColorフレームのRAWフォーマットはColorImageFormat\_Yuy2。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyRawFrameDataToArray Method
RLTitle : IColorFrame::CopyRawFrameDataToArray Method
KeywordK : CopyRawFrameDataToArray method
KeywordK : IColorFrame::CopyRawFrameDataToArray method
KeywordF : IColorFrame::CopyRawFrameDataToArray
KeywordF : CopyRawFrameDataToArray
KeywordF : Microsoft.Kinect.kinect.IColorFrame.CopyRawFrameDataToArray(UINT,BYTE@)
KeywordA : M:Microsoft.Kinect.kinect.IColorFrame.CopyRawFrameDataToArray(UINT,BYTE@)
AssetID : M:Microsoft.Kinect.kinect.IColorFrame.CopyRawFrameDataToArray(UINT,BYTE@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorFrame::CopyRawFrameDataToArray
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
