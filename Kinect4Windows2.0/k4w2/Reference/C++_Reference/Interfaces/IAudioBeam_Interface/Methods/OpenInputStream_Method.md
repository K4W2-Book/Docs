IAudioBeam::OpenInputStream Method  
==================================  

音声データの入力ストリームを開く。 <span id="syntaxSection"></span>

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
HRESULT OpenInputStream(  
         IStream **stream  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*stream*    
Type: IStream  
[out] IStreamのポインタのアドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

入力ストリームは、16kHz/32bit(float)でサンプリングされたモノラルPCMデータ[-1.0f, 1.0f]です。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : OpenInputStream Method
RLTitle : IAudioBeam::OpenInputStream Method
KeywordK : OpenInputStream method
KeywordK : IAudioBeam::OpenInputStream method
KeywordF : IAudioBeam::OpenInputStream
KeywordF : OpenInputStream
KeywordF : Microsoft.Kinect.kinect.IAudioBeam.OpenInputStream(IStream@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeam.OpenInputStream(IStream@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeam.OpenInputStream(IStream@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam::OpenInputStream
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
