IAudioBeamSubFrame::get\_FrameLengthInBytes Method  
==================================================  

AudioBeamサブフレームのサイズ(Byte)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FrameLengthInBytes(  
         UINT *length  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*length*    
Type: UINT  
[out] AudioBeamサブフレームのサイズ(Byte)を取得する。  

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
TOCTitle : get_FrameLengthInBytes Method
RLTitle : IAudioBeamSubFrame::get_FrameLengthInBytes Method
KeywordK : get_FrameLengthInBytes method
KeywordK : IAudioBeamSubFrame::get_FrameLengthInBytes method
KeywordF : IAudioBeamSubFrame::get_FrameLengthInBytes
KeywordF : get_FrameLengthInBytes
KeywordF : Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_FrameLengthInBytes(UINT@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_FrameLengthInBytes(UINT@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamSubFrame.get_FrameLengthInBytes(UINT@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamSubFrame::get_FrameLengthInBytes
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
