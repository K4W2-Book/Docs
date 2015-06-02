IAudioSource::get\_SubFrameLengthInBytes Method  
===============================================  

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
HRESULT get_SubFrameLengthInBytes(  
         UINT *length  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*length*    
Type: UINT  
[out] AudioBeamサブフレームのサイズ(Byte)。  

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
TOCTitle : get_SubFrameLengthInBytes Method
RLTitle : IAudioSource::get_SubFrameLengthInBytes Method
KeywordK : get_SubFrameLengthInBytes method
KeywordK : IAudioSource::get_SubFrameLengthInBytes method
KeywordF : IAudioSource::get_SubFrameLengthInBytes
KeywordF : get_SubFrameLengthInBytes
KeywordF : Microsoft.Kinect.kinect.IAudioSource.get_SubFrameLengthInBytes(UINT@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioSource.get_SubFrameLengthInBytes(UINT@)
AssetID : M:Microsoft.Kinect.kinect.IAudioSource.get_SubFrameLengthInBytes(UINT@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource::get_SubFrameLengthInBytes
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
