IDepthFrame::get\_DepthMinReliableDistance Method  
=================================================  

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
         USHORT *depthMinReliableDistance  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*depthMinReliableDistance*    
Type: USHORT  
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
RLTitle : IDepthFrame::get_DepthMinReliableDistance Method
KeywordK : get_DepthMinReliableDistance method
KeywordK : IDepthFrame::get_DepthMinReliableDistance method
KeywordF : IDepthFrame::get_DepthMinReliableDistance
KeywordF : get_DepthMinReliableDistance
KeywordF : Microsoft.Kinect.kinect.IDepthFrame.get_DepthMinReliableDistance(USHORT@)
KeywordA : M:Microsoft.Kinect.kinect.IDepthFrame.get_DepthMinReliableDistance(USHORT@)
AssetID : M:Microsoft.Kinect.kinect.IDepthFrame.get_DepthMinReliableDistance(USHORT@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrame::get_DepthMinReliableDistance
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
