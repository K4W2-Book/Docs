IDepthFrameSource::OpenReader Method  
====================================  

Creates a frame reader for the depth frame source. <span id="syntaxSection"></span>

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
HRESULT OpenReader(  
         IDepthFrameReader **reader  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*reader*    
Type: IDepthFrameReader  
[out] A new frame reader for the depth frame source.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OpenReader Method
RLTitle : IDepthFrameSource::OpenReader Method
KeywordK : OpenReader method
KeywordK : IDepthFrameSource::OpenReader method
KeywordF : IDepthFrameSource::OpenReader
KeywordF : OpenReader
KeywordF : Microsoft.Kinect.kinect.IDepthFrameSource.OpenReader(IDepthFrameReader@)
KeywordA : M:Microsoft.Kinect.kinect.IDepthFrameSource.OpenReader(IDepthFrameReader@)
AssetID : M:Microsoft.Kinect.kinect.IDepthFrameSource.OpenReader(IDepthFrameReader@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrameSource::OpenReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
