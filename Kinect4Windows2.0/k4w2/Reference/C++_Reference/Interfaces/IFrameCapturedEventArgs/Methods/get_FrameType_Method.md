IFrameCapturedEventArgs::get\_FrameType Method  
==============================================  

フレームの種類を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FrameType(  
         FrameSourceTypes *frameType  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*frameType*    
Type: [FrameSourceTypes](../../../Enumerations/FrameSourceTypes_Enumeration.md)  
[out] フレームの種類。  

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
TOCTitle : get_FrameType Method
RLTitle : IFrameCapturedEventArgs::get_FrameType Method
KeywordK : get_FrameType method
KeywordK : IFrameCapturedEventArgs::get_FrameType method
KeywordF : IFrameCapturedEventArgs::get_FrameType
KeywordF : get_FrameType
KeywordF : Microsoft.Kinect.kinect.IFrameCapturedEventArgs.get_FrameType(FrameSourceTypes@)
KeywordA : M:Microsoft.Kinect.kinect.IFrameCapturedEventArgs.get_FrameType(FrameSourceTypes@)
AssetID : M:Microsoft.Kinect.kinect.IFrameCapturedEventArgs.get_FrameType(FrameSourceTypes@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IFrameCapturedEventArgs::get_FrameType
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
