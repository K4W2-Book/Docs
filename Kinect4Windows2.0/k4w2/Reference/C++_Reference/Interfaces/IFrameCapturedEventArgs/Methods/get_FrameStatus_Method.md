IFrameCapturedEventArgs::get\_FrameStatus Method  
================================================  

フレームのキャプチャーステータスを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FrameStatus(  
         FrameCapturedStatus *frameStatus  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*frameStatus*    
Type: [FrameCapturedStatus](../../../Enumerations/FrameCapturedStatus.md)  
[out] フレームのキャプチャステータス。  

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
TOCTitle : get_FrameStatus Method
RLTitle : IFrameCapturedEventArgs::get_FrameStatus Method
KeywordK : get_FrameStatus method
KeywordK : IFrameCapturedEventArgs::get_FrameStatus method
KeywordF : IFrameCapturedEventArgs::get_FrameStatus
KeywordF : get_FrameStatus
KeywordF : Microsoft.Kinect.kinect.IFrameCapturedEventArgs.get_FrameStatus(FrameCapturedStatus@)
KeywordA : M:Microsoft.Kinect.kinect.IFrameCapturedEventArgs.get_FrameStatus(FrameCapturedStatus@)
AssetID : M:Microsoft.Kinect.kinect.IFrameCapturedEventArgs.get_FrameStatus(FrameCapturedStatus@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IFrameCapturedEventArgs::get_FrameStatus
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
