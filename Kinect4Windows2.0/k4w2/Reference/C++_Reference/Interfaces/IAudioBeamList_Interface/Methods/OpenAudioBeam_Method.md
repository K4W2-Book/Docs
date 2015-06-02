IAudioBeamList::OpenAudioBeam Method  
====================================  

指定したインデックスのAudioBeamを取得する。 <span id="syntaxSection"></span>

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
HRESULT OpenAudioBeam(  
         UINT32 index,  
         IAudioBeam **audioBeam  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*index*    
Type: UINT32  
AudioBeamのインデックス。  

*audioBeam*    
Type: IAudioBeam  
[out] [IAudioBeam](../../IAudioBeam_Interface.md)のポインタのアドレス。  

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
TOCTitle : OpenAudioBeam Method
RLTitle : IAudioBeamList::OpenAudioBeam Method
KeywordK : OpenAudioBeam method
KeywordK : IAudioBeamList::OpenAudioBeam method
KeywordF : IAudioBeamList::OpenAudioBeam
KeywordF : OpenAudioBeam
KeywordF : Microsoft.Kinect.kinect.IAudioBeamList.OpenAudioBeam(UINT32,IAudioBeam@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamList.OpenAudioBeam(UINT32,IAudioBeam@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamList.OpenAudioBeam(UINT32,IAudioBeam@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamList::OpenAudioBeam
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
