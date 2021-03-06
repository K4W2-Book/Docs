IDepthFrame::get\_FrameDescription Method  
=========================================  

Depthフレームの情報を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FrameDescription(  
         IFrameDescription **frameDescription  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*frameDescription*    
Type: IFrameDescription  
[out] [IFrameDescription](../../IFrameDescription_Interface.md)のポインタのアドレス。  

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
TOCTitle : get_FrameDescription Method
RLTitle : IDepthFrame::get_FrameDescription Method
KeywordK : get_FrameDescription method
KeywordK : IDepthFrame::get_FrameDescription method
KeywordF : IDepthFrame::get_FrameDescription
KeywordF : get_FrameDescription
KeywordF : Microsoft.Kinect.kinect.IDepthFrame.get_FrameDescription(IFrameDescription@)
KeywordA : M:Microsoft.Kinect.kinect.IDepthFrame.get_FrameDescription(IFrameDescription@)
AssetID : M:Microsoft.Kinect.kinect.IDepthFrame.get_FrameDescription(IFrameDescription@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IDepthFrame::get_FrameDescription
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
