IAudioSource::get\_KinectSensor Method  
======================================  

AudioフレームのSourceを取得したセンサーを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_KinectSensor(  
         IKinectSensor **sensor  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sensor*    
Type: IKinectSensor  
[out] [IKinectSensor](../../IKinectSensor_Interface.md)のポインタのアドレス。  

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
TOCTitle : get_KinectSensor Method
RLTitle : IAudioSource::get_KinectSensor Method
KeywordK : get_KinectSensor method
KeywordK : IAudioSource::get_KinectSensor method
KeywordF : IAudioSource::get_KinectSensor
KeywordF : get_KinectSensor
KeywordF : Microsoft.Kinect.kinect.IAudioSource.get_KinectSensor(IKinectSensor@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioSource.get_KinectSensor(IKinectSensor@)
AssetID : M:Microsoft.Kinect.kinect.IAudioSource.get_KinectSensor(IKinectSensor@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource::get_KinectSensor
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
