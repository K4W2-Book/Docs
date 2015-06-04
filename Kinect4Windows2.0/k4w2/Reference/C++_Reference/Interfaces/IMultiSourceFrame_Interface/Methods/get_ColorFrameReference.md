IMultiSourceFrame::get\_ColorFrameReference Method  
==================================================  

ColorフレームのReferenceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_ColorFrameReference(  
         IColorFrameReference **colorFrameReference  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*colorFrameReference*    
Type: IColorFrameReference  
[out] [IColorFrameReference](../../IColorFrameReference.md)のポインタのアドレス。  

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
TOCTitle : get_ColorFrameReference Method
RLTitle : IMultiSourceFrame::get_ColorFrameReference Method
KeywordK : get_ColorFrameReference method
KeywordK : IMultiSourceFrame::get_ColorFrameReference method
KeywordF : IMultiSourceFrame::get_ColorFrameReference
KeywordF : get_ColorFrameReference
KeywordF : Microsoft.Kinect.kinect.IMultiSourceFrame.get_ColorFrameReference(IColorFrameReference@)
KeywordA : M:Microsoft.Kinect.kinect.IMultiSourceFrame.get_ColorFrameReference(IColorFrameReference@)
AssetID : M:Microsoft.Kinect.kinect.IMultiSourceFrame.get_ColorFrameReference(IColorFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IMultiSourceFrame::get_ColorFrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
