IAudioSource::get\_AudioCalibrationState Method  
===============================================  

Audioセンサーのキャリブレーションステータスを取得する。
この機能はKinect for Windowsアプリケーションではサポートされません。
この列挙体はXbox One SDKとのクロスコンパイルをサポートするために含まれています。 <span id="syntaxSection"></span>

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
HRESULT get_AudioCalibrationState(  
         KinectAudioCalibrationState *audioCalibrationState  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*audioCalibrationState*    
Type: KinectAudioCalibrationState  
[out] Audioセンサーのキャリブレーションステータス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

Kinect for Windowsアプリケーションでは常にKinectAudioCalibrationState\_Calibratedです。 

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_AudioCalibrationState Method
RLTitle : IAudioSource::get_AudioCalibrationState Method
KeywordK : get_AudioCalibrationState method
KeywordK : IAudioSource::get_AudioCalibrationState method
KeywordF : IAudioSource::get_AudioCalibrationState
KeywordF : get_AudioCalibrationState
KeywordF : Microsoft.Kinect.kinect.IAudioSource.get_AudioCalibrationState(KinectAudioCalibrationState@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioSource.get_AudioCalibrationState(KinectAudioCalibrationState@)
AssetID : M:Microsoft.Kinect.kinect.IAudioSource.get_AudioCalibrationState(KinectAudioCalibrationState@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioSource::get_AudioCalibrationState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
