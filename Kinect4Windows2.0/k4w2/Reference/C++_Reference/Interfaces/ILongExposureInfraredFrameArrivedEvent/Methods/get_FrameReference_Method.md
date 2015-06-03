ILongExposureInfraredFrameArrivedEventArgs::get\_FrameReference Method  
======================================================================  

長時間露光InfraredフレームのReferenceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FrameReference(  
         ILongExposureInfraredFrameReference **longExposureInfraredFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*longExposureInfraredFrameReference*    
Type: ILongExposureInfraredFrameReference  
[out] [ILongExposureInfraredFrameReference](../../ILongExposureInfraredFrameReference.md)のポインタのアドレス。  

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
TOCTitle : get_FrameReference Method
RLTitle : ILongExposureInfraredFrameArrivedEventArgs::get_FrameReference Method
KeywordK : get_FrameReference method
KeywordK : ILongExposureInfraredFrameArrivedEventArgs::get_FrameReference method
KeywordF : ILongExposureInfraredFrameArrivedEventArgs::get_FrameReference
KeywordF : get_FrameReference
KeywordF : Microsoft.Kinect.kinect.ILongExposureInfraredFrameArrivedEventArgs.get_FrameReference(ILongExposureInfraredFrameReference@)
KeywordA : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameArrivedEventArgs.get_FrameReference(ILongExposureInfraredFrameReference@)
AssetID : M:Microsoft.Kinect.kinect.ILongExposureInfraredFrameArrivedEventArgs.get_FrameReference(ILongExposureInfraredFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ILongExposureInfraredFrameArrivedEventArgs::get_FrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
