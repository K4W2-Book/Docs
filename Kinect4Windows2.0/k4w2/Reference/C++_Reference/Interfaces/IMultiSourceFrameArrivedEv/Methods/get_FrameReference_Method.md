IMultiSourceFrameArrivedEventArgs::get\_FrameReference Method  
=============================================================  

MultiSourceフレームのReferenceを取得する。 <span id="syntaxSection"></span>

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
         IMultiSourceFrameReference **frames  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*frames*    
Type: IMultiSourceFrameReference  
[out] [IMultiSourceFrameReference](../../IMultiSourceFrameReference.md)のポインタのアドレス。  

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
RLTitle : IMultiSourceFrameArrivedEventArgs::get_FrameReference Method
KeywordK : get_FrameReference method
KeywordK : IMultiSourceFrameArrivedEventArgs::get_FrameReference method
KeywordF : IMultiSourceFrameArrivedEventArgs::get_FrameReference
KeywordF : get_FrameReference
KeywordF : Microsoft.Kinect.kinect.IMultiSourceFrameArrivedEventArgs.get_FrameReference(IMultiSourceFrameReference@)
KeywordA : M:Microsoft.Kinect.kinect.IMultiSourceFrameArrivedEventArgs.get_FrameReference(IMultiSourceFrameReference@)
AssetID : M:Microsoft.Kinect.kinect.IMultiSourceFrameArrivedEventArgs.get_FrameReference(IMultiSourceFrameReference@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IMultiSourceFrameArrivedEventArgs::get_FrameReference
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
