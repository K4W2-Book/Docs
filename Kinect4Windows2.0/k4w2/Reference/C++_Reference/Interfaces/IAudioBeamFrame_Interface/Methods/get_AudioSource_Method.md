IAudioBeamFrame::get\_AudioSource Method  
========================================  

AudioBeamフレームのSourceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_AudioSource(  
         IAudioSource **audioSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*audioSource*    
Type: IAudioSource  
[out] [IAudioSource](../../IAudioSource_Interface.md)のポインタのアドレス。  

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
TOCTitle : get_AudioSource Method
RLTitle : IAudioBeamFrame::get_AudioSource Method
KeywordK : get_AudioSource method
KeywordK : IAudioBeamFrame::get_AudioSource method
KeywordF : IAudioBeamFrame::get_AudioSource
KeywordF : get_AudioSource
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrame.get_AudioSource(IAudioSource@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_AudioSource(IAudioSource@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_AudioSource(IAudioSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrame::get_AudioSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
