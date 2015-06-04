IKinectSensor::get\_IsOpen Method  
=================================  

Kinectセンサーがストリームを開いているかを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_IsOpen(  
         BOOLEAN *isOpen  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*isOpen*    
Type: BOOLEAN  
[out] Kinectセンサーがストリームを開いている場合は**true**、そうでない場合は**false**。  

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
TOCTitle : get_IsOpen Method
RLTitle : IKinectSensor::get_IsOpen Method
KeywordK : get_IsOpen method
KeywordK : IKinectSensor::get_IsOpen method
KeywordF : IKinectSensor::get_IsOpen
KeywordF : get_IsOpen
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.get_IsOpen(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.get_IsOpen(BOOLEAN@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.get_IsOpen(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::get_IsOpen
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
