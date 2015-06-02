IAudioBeamFrameReference::AcquireBeamFrames Method  
==================================================  

AudioBeamフレームのリストを取得する。 <span id="syntaxSection"></span>

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
HRESULT AcquireBeamFrames(  
         IAudioBeamFrameList **audioBeamFrameList  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*audioBeamFrameList*    
Type: IAudioBeamFrameList  
[out] [IAudioBeamFrameList](../../IAudioBeamFrameList.md)のポインタのアドレス。  

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
TOCTitle : AcquireBeamFrames Method
RLTitle : IAudioBeamFrameReference::AcquireBeamFrames Method
KeywordK : AcquireBeamFrames method
KeywordK : IAudioBeamFrameReference::AcquireBeamFrames method
KeywordF : IAudioBeamFrameReference::AcquireBeamFrames
KeywordF : AcquireBeamFrames
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrameReference.AcquireBeamFrames(IAudioBeamFrameList@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrameReference.AcquireBeamFrames(IAudioBeamFrameList@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrameReference.AcquireBeamFrames(IAudioBeamFrameList@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrameReference::AcquireBeamFrames
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
