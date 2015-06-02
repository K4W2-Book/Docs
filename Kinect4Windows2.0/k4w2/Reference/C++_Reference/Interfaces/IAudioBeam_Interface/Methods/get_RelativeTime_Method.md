IAudioBeam::get\_RelativeTime Method  
====================================  

AudioBeamを取得した時間(相対時間)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_RelativeTime(  
         TIMESPAN *relativeTime  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*relativeTime*    
Type: TIMESPAN  
[out] AudioBeamを取得した時間(相対時間)。  

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
TOCTitle : get_RelativeTime Method
RLTitle : IAudioBeam::get_RelativeTime Method
KeywordK : get_RelativeTime method
KeywordK : IAudioBeam::get_RelativeTime method
KeywordF : IAudioBeam::get_RelativeTime
KeywordF : get_RelativeTime
KeywordF : Microsoft.Kinect.kinect.IAudioBeam.get_RelativeTime(TIMESPAN@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeam.get_RelativeTime(TIMESPAN@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeam.get_RelativeTime(TIMESPAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeam::get_RelativeTime
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
