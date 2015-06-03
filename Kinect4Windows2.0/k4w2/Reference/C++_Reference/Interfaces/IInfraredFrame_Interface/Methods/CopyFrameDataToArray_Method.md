IInfraredFrame::CopyFrameDataToArray Method  
===========================================  

Infraredフレームのデータを取得する。(コピー) <span id="syntaxSection"></span>

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
HRESULT CopyFrameDataToArray(  
         UINT capacity,  
         UINT16 *frameData  
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
Type: UINT16  
[out] データをコピーする配列の先頭アドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

配列はフレームデータを格納するのに十分な大きさを持っている必要があります。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CopyFrameDataToArray Method
RLTitle : IInfraredFrame::CopyFrameDataToArray Method
KeywordK : CopyFrameDataToArray method
KeywordK : IInfraredFrame::CopyFrameDataToArray method
KeywordF : IInfraredFrame::CopyFrameDataToArray
KeywordF : CopyFrameDataToArray
KeywordF : Microsoft.Kinect.kinect.IInfraredFrame.CopyFrameDataToArray(UINT,UINT16@)
KeywordA : M:Microsoft.Kinect.kinect.IInfraredFrame.CopyFrameDataToArray(UINT,UINT16@)
AssetID : M:Microsoft.Kinect.kinect.IInfraredFrame.CopyFrameDataToArray(UINT,UINT16@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IInfraredFrame::CopyFrameDataToArray
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
