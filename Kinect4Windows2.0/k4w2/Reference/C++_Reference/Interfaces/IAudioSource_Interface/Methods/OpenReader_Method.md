IAudioSource::OpenReader Method  
===============================  

AudioBeamフレームのReaderを開く。 <span id="syntaxSection"></span>

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
         IAudioBeamFrameReader **reader  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*reader*    
Type: IAudioBeamFrameReader  
[out] [IAudioBeamFrameReader](../../IAudioBeamFrameReader.md)のポインタのアドレス。  

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
TOCTitle : OpenReader Method
RLTitle : IAudioSource::OpenReader Method
KeywordK : OpenReader method
KeywordK : IAudioSource::OpenReader method
KeywordF : IAudioSource::OpenReader
KeywordF : OpenReader
KeywordF : Microsoft.Kinect.kinect.IAudioSource.OpenReader(IAudioBeamFrameReader@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioSource.OpenReader(IAudioBeamFrameReader@)
AssetID : M:Microsoft.Kinect.kinect.IAudioSource.OpenReader(IAudioBeamFrameReader@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource::OpenReader
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
