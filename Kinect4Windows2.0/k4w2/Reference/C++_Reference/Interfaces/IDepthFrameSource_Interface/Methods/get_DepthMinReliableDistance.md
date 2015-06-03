IDepthFrameSource::get\_DepthMinReliableDistance Method  
=======================================================  

Depthフレームの精度が確保できる最小距離を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_DepthMinReliableDistance(  
         UINT16 *depthMinReliableDistance  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthMinReliableDistance*    
Type: UINT16  
[out] Depthフレームの精度が確保できる最小距離。(500)  

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
TOCTitle : get_DepthMinReliableDistance Method
RLTitle : IDepthFrameSource::get_DepthMinReliableDistance Method
KeywordK : get_DepthMinReliableDistance method
KeywordK : IDepthFrameSource::get_DepthMinReliableDistance method
KeywordF : IDepthFrameSource::get_DepthMinReliableDistance
KeywordF : get_DepthMinReliableDistance
KeywordF : Microsoft.Kinect.kinect.IDepthFrameSource.get_DepthMinReliableDistance(UINT16@)
KeywordA : M:Microsoft.Kinect.kinect.IDepthFrameSource.get_DepthMinReliableDistance(UINT16@)
AssetID : M:Microsoft.Kinect.kinect.IDepthFrameSource.get_DepthMinReliableDistance(UINT16@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrameSource::get_DepthMinReliableDistance
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
