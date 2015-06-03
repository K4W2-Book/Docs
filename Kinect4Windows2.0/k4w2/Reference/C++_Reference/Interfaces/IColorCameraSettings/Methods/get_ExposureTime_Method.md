IColorCameraSettings::get\_ExposureTime Method  
==============================================  

Colorカメラの露光時間を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_ExposureTime(  
         TIMESPAN *exposureTime  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*exposureTime*    
Type: TIMESPAN  
[out] Colorカメラの露光時間。  

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
TOCTitle : get_ExposureTime Method
RLTitle : IColorCameraSettings::get_ExposureTime Method
KeywordK : get_ExposureTime method
KeywordK : IColorCameraSettings::get_ExposureTime method
KeywordF : IColorCameraSettings::get_ExposureTime
KeywordF : get_ExposureTime
KeywordF : Microsoft.Kinect.kinect.IColorCameraSettings.get_ExposureTime(TIMESPAN@)
KeywordA : M:Microsoft.Kinect.kinect.IColorCameraSettings.get_ExposureTime(TIMESPAN@)
AssetID : M:Microsoft.Kinect.kinect.IColorCameraSettings.get_ExposureTime(TIMESPAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IColorCameraSettings::get_ExposureTime
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
