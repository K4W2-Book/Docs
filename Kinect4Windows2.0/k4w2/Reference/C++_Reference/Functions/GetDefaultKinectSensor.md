GetDefaultKinectSensor  
======================  

デフォルトの[IKinectSensor](../Interfaces/IKinectSensor_Interface.md)を作成する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT GetDefaultKinectSensor(  
         IKinectSensor **defaultKinectSensor  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*defaultKinectSensor*    
Type: IKinectSensor  
[out] [IKinectSensor](../Interfaces/IKinectSensor_Interface.md)のポインタのアドレス。  

<span id="ID4EN"></span>
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
TOCTitle : GetDefaultKinectSensor
RLTitle : GetDefaultKinectSensor
KeywordK : GetDefaultKinectSensor
KeywordF : GetDefaultKinectSensor
KeywordF : Microsoft.Kinect.kinect.GetDefaultKinectSensor(IKinectSensor@)
KeywordA : M:Microsoft.Kinect.kinect.GetDefaultKinectSensor(IKinectSensor@)
AssetID : M:Microsoft.Kinect.kinect.GetDefaultKinectSensor(IKinectSensor@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.GetDefaultKinectSensor
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
