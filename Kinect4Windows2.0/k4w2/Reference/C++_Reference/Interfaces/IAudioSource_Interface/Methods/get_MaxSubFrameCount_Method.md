IAudioSource::get\_MaxSubFrameCount Method  
==========================================  

AudioBeamサブフレームの最大数を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_MaxSubFrameCount(  
         UINT *count  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*count*    
Type: UINT  
[out] AudioBeamサブフレームの最大数。(8)  

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
TOCTitle : get_MaxSubFrameCount Method
RLTitle : IAudioSource::get_MaxSubFrameCount Method
KeywordK : get_MaxSubFrameCount method
KeywordK : IAudioSource::get_MaxSubFrameCount method
KeywordF : IAudioSource::get_MaxSubFrameCount
KeywordF : get_MaxSubFrameCount
KeywordF : Microsoft.Kinect.kinect.IAudioSource.get_MaxSubFrameCount(UINT@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioSource.get_MaxSubFrameCount(UINT@)
AssetID : M:Microsoft.Kinect.kinect.IAudioSource.get_MaxSubFrameCount(UINT@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource::get_MaxSubFrameCount
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
