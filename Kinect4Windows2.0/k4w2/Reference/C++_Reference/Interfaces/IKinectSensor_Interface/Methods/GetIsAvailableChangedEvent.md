IKinectSensor::GetIsAvailableChangedEventData Method  
====================================================  

Kinectセンサーが変更されたとき、イベントデータを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetIsAvailableChangedEventData(  
         WAITABLE_HANDLE waitableHandle,  
         IIsAvailableChangedEventArgs **eventData  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*waitableHandle*    
Type: WAITABLE\_HANDLE  
[in] Kinectセンサーが変更されたとき発効するイベントハンドル。  

*eventData*    
Type: IIsAvailableChangedEventArgs  
[out] [IIsAvailableChangedEventArgs](../../IIsAvailableChangedEventArgs.md)のポインタのアドレス。  

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
TOCTitle : GetIsAvailableChangedEventData Method
RLTitle : IKinectSensor::GetIsAvailableChangedEventData Method
KeywordK : GetIsAvailableChangedEventData method
KeywordK : IKinectSensor::GetIsAvailableChangedEventData method
KeywordF : IKinectSensor::GetIsAvailableChangedEventData
KeywordF : GetIsAvailableChangedEventData
KeywordF : Microsoft.Kinect.kinect.IKinectSensor.GetIsAvailableChangedEventData(WAITABLE_HANDLE,IIsAvailableChangedEventArgs@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectSensor.GetIsAvailableChangedEventData(WAITABLE_HANDLE,IIsAvailableChangedEventArgs@)
AssetID : M:Microsoft.Kinect.kinect.IKinectSensor.GetIsAvailableChangedEventData(WAITABLE_HANDLE,IIsAvailableChangedEventArgs@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectSensor::GetIsAvailableChangedEventData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
