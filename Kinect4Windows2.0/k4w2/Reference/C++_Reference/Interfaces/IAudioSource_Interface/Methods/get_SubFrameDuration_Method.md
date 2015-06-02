IAudioSource::get\_SubFrameDuration Method  
==========================================  

AudioBeamサブフレームのサンプリング時間を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_SubFrameDuration(  
         TIMESPAN *duration  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*duration*    
Type: TIMESPAN  
[out] AudioBeamサブフレームのサンプリング時間。  

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
TOCTitle : get_SubFrameDuration Method
RLTitle : IAudioSource::get_SubFrameDuration Method
KeywordK : get_SubFrameDuration method
KeywordK : IAudioSource::get_SubFrameDuration method
KeywordF : IAudioSource::get_SubFrameDuration
KeywordF : get_SubFrameDuration
KeywordF : Microsoft.Kinect.kinect.IAudioSource.get_SubFrameDuration(TIMESPAN@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioSource.get_SubFrameDuration(TIMESPAN@)
AssetID : M:Microsoft.Kinect.kinect.IAudioSource.get_SubFrameDuration(TIMESPAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource::get_SubFrameDuration
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
