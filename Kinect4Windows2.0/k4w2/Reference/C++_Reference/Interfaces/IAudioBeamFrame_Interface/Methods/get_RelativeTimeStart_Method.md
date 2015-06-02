IAudioBeamFrame::get\_RelativeTimeStart Method  
==============================================  

AudioBeamフレームの最初のAudioBeamサブフレームの取得時間(相対時間)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_RelativeTimeStart(  
         TIMESPAN *relativeTime  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*relativeTime*    
Type: TIMESPAN  
[out] AudioBeamフレームの最初のAudioBeamサブフレームの取得時間(相対時間)。  

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
TOCTitle : get_RelativeTimeStart Method
RLTitle : IAudioBeamFrame::get_RelativeTimeStart Method
KeywordK : get_RelativeTimeStart method
KeywordK : IAudioBeamFrame::get_RelativeTimeStart method
KeywordF : IAudioBeamFrame::get_RelativeTimeStart
KeywordF : get_RelativeTimeStart
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrame.get_RelativeTimeStart(TIMESPAN@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_RelativeTimeStart(TIMESPAN@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_RelativeTimeStart(TIMESPAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrame::get_RelativeTimeStart
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
