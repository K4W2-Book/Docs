IKinectSensor::get\_InfraredFrameSource Method  
==============================================  

InfraredフレームのSourceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_InfraredFrameSource(  
         IInfraredFrameSource **infraredFrameSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*infraredFrameSource*    
Type: IInfraredFrameSource  
[out] [IInfraredFrameSource](../../IInfraredFrameSource.md)のポインタのアドレス。  

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
TOCTitle : get_InfraredFrameSource Method
RLTitle : IKinectSensor::get_InfraredFrameSource Method
KeywordK : get_InfraredFrameSource method
KeywordK : IKinectSensor::get_InfraredFrameSource method
KeywordF : IKinectSensor::get_InfraredFrameSource
KeywordF : get_InfraredFrameSource
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.get_InfraredFrameSource(IInfraredFrameSource@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.get_InfraredFrameSource(IInfraredFrameSource@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.get_InfraredFrameSource(IInfraredFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::get_InfraredFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
