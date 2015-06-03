IBodyIndexFrameReader::AcquireLatestFrame Method  
================================================  

最新のBodyIndexフレームを取得する。 <span id="syntaxSection"></span>

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
HRESULT AcquireLatestFrame(  
         IBodyIndexFrame **bodyIndexFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bodyIndexFrame*    
Type: IBodyIndexFrame  
[out] [IBodyIndexFrame](../../IBodyIndexFrame_Interface.md)のポインタのアドレス。  

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
TOCTitle : AcquireLatestFrame Method
RLTitle : IBodyIndexFrameReader::AcquireLatestFrame Method
KeywordK : AcquireLatestFrame method
KeywordK : IBodyIndexFrameReader::AcquireLatestFrame method
KeywordF : IBodyIndexFrameReader::AcquireLatestFrame
KeywordF : AcquireLatestFrame
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrameReader.AcquireLatestFrame(IBodyIndexFrame@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyIndexFrameReader.AcquireLatestFrame(IBodyIndexFrame@)
AssetID : M:Microsoft.Kinect.kinect.IBodyIndexFrameReader.AcquireLatestFrame(IBodyIndexFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrameReader::AcquireLatestFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
