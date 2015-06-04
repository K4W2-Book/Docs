IKinectSensor::get\_KinectCapabilities Method  
=============================================  

Kinectセンサーがサポートする機能を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_KinectCapabilities(  
         DWORD *capabilities  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capabilities*    
Type: DWORD  
[out] Kinectセンサーがサポートする[KinectCapabilities](../../../Enumerations/KinectCapabilities.md)。  

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
TOCTitle : get_KinectCapabilities Method
RLTitle : IKinectSensor::get_KinectCapabilities Method
KeywordK : get_KinectCapabilities method
KeywordK : IKinectSensor::get_KinectCapabilities method
KeywordF : IKinectSensor::get_KinectCapabilities
KeywordF : get_KinectCapabilities
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.get_KinectCapabilities(DWORD@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.get_KinectCapabilities(DWORD@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.get_KinectCapabilities(DWORD@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::get_KinectCapabilities
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
