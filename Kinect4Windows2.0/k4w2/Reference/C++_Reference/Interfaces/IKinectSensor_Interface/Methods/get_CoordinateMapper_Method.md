IKinectSensor::get\_CoordinateMapper Method  
===========================================  

Coordinate Mapperを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_CoordinateMapper(  
         ICoordinateMapper **coordinateMapper  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*coordinateMapper*    
Type: ICoordinateMapper  
[out] [ICoordinateMapper](../../ICoordinateMapper_Interface.md)のポインタのアドレス。  

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
TOCTitle : get_CoordinateMapper Method
RLTitle : IKinectSensor::get_CoordinateMapper Method
KeywordK : get_CoordinateMapper method
KeywordK : IKinectSensor::get_CoordinateMapper method
KeywordF : IKinectSensor::get_CoordinateMapper
KeywordF : get_CoordinateMapper
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.get_CoordinateMapper(ICoordinateMapper@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.get_CoordinateMapper(ICoordinateMapper@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.get_CoordinateMapper(ICoordinateMapper@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::get_CoordinateMapper
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
