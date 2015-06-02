IAudioBeamFrameList::OpenAudioBeamFrame Method  
==============================================  

指定したインデックスのAudioBeamフレームを取得する。 <span id="syntaxSection"></span>

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
HRESULT OpenAudioBeamFrame(  
         UINT32 index,  
         IAudioBeamFrame **audioBeamFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*index*    
Type: UINT32  
Audioビームフレームのインデックス。  

*audioBeamFrame*    
Type: IAudioBeamFrame  
[out] [IAudioBeamFrame](../../IAudioBeamFrame_Interface.md)のポインタのアドレス。  

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
TOCTitle : OpenAudioBeamFrame Method
RLTitle : IAudioBeamFrameList::OpenAudioBeamFrame Method
KeywordK : OpenAudioBeamFrame method
KeywordK : IAudioBeamFrameList::OpenAudioBeamFrame method
KeywordF : IAudioBeamFrameList::OpenAudioBeamFrame
KeywordF : OpenAudioBeamFrame
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrameList.OpenAudioBeamFrame(UINT32,IAudioBeamFrame@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrameList.OpenAudioBeamFrame(UINT32,IAudioBeamFrame@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrameList.OpenAudioBeamFrame(UINT32,IAudioBeamFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrameList::OpenAudioBeamFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
