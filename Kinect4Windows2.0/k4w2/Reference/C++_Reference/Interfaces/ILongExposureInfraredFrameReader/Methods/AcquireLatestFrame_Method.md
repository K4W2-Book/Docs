ILongExposureInfraredFrameReader::AcquireLatestFrame Method  
===========================================================  

最新の長時間露光Infraredフレームを取得する。 <span id="syntaxSection"></span>

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
         ILongExposureInfraredFrame **longExposureInfraredFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*longExposureInfraredFrame*    
Type: ILongExposureInfraredFrame  
[out] [ILongExposureInfraredFrame](../../ILongExposureInfraredFrame_Interface.md)のポインタのアドレス。  

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
RLTitle : ILongExposureInfraredFrameReader::AcquireLatestFrame Method
KeywordK : AcquireLatestFrame method
KeywordK : ILongExposureInfraredFrameReader::AcquireLatestFrame method
KeywordF : ILongExposureInfraredFrameReader::AcquireLatestFrame
KeywordF : AcquireLatestFrame
KeywordF : Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader.AcquireLatestFrame(ILongExposureInfraredFrame@)
KeywordA : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader.AcquireLatestFrame(ILongExposureInfraredFrame@)
AssetID : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader.AcquireLatestFrame(ILongExposureInfraredFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ILongExposureInfraredFrameReader::AcquireLatestFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
