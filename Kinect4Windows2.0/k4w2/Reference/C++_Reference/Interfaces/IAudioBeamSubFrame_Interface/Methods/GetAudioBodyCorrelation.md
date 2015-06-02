IAudioBeamSubFrame::GetAudioBodyCorrelation Method  
==================================================  

AudioBeamサブフレームに関連するBodyを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetAudioBodyCorrelation(  
         UINT index,  
         IAudioBodyCorrelation **ppAudioBodyCorrelation  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*index*    
Type: UINT  
[in] AudioBeamサブフレームに関連するBodyのインデックス。  

*ppAudioBodyCorrelation*    
Type: IAudioBodyCorrelation  
[out] [IAudioBodyCorrelation](../../IAudioBodyCorrelation.md)のポインタのアドレス。  

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
TOCTitle : GetAudioBodyCorrelation Method
RLTitle : IAudioBeamSubFrame::GetAudioBodyCorrelation Method
KeywordK : GetAudioBodyCorrelation method
KeywordK : IAudioBeamSubFrame::GetAudioBodyCorrelation method
KeywordF : IAudioBeamSubFrame::GetAudioBodyCorrelation
KeywordF : GetAudioBodyCorrelation
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame.GetAudioBodyCorrelation(UINT,IAudioBodyCorrelation@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.GetAudioBodyCorrelation(UINT,IAudioBodyCorrelation@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.GetAudioBodyCorrelation(UINT,IAudioBodyCorrelation@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame::GetAudioBodyCorrelation
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
