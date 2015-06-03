IColorCameraSettings::get\_FrameInterval Method  
===============================================  

Colorカメラのフレーム間隔時間を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FrameInterval(  
         TIMESPAN *frameInterval  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*frameInterval*    
Type: TIMESPAN  
[out] Colorカメラのフレーム間隔時間。  

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
TOCTitle : get_FrameInterval Method
RLTitle : IColorCameraSettings::get_FrameInterval Method
KeywordK : get_FrameInterval method
KeywordK : IColorCameraSettings::get_FrameInterval method
KeywordF : IColorCameraSettings::get_FrameInterval
KeywordF : get_FrameInterval
KeywordF : Microsoft.Kinect.kinect.IColorCameraSettings.get_FrameInterval(TIMESPAN@)
KeywordA : M:Microsoft.Kinect.kinect.IColorCameraSettings.get_FrameInterval(TIMESPAN@)
AssetID : M:Microsoft.Kinect.kinect.IColorCameraSettings.get_FrameInterval(TIMESPAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorCameraSettings::get_FrameInterval
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
