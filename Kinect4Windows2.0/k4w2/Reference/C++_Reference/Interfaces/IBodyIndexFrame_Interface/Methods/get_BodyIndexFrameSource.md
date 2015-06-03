IBodyIndexFrame::get\_BodyIndexFrameSource Method  
=================================================  

BodyIndexフレームのSourceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_BodyIndexFrameSource(  
         IBodyIndexFrameSource **bodyIndexFrameSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bodyIndexFrameSource*    
Type: IBodyIndexFrameSource  
[out] [IBodyIndexFrameSource](../../IBodyIndexFrameSource.md)のポインタのアドレス。  

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
TOCTitle : get_BodyIndexFrameSource Method
RLTitle : IBodyIndexFrame::get_BodyIndexFrameSource Method
KeywordK : get_BodyIndexFrameSource method
KeywordK : IBodyIndexFrame::get_BodyIndexFrameSource method
KeywordF : IBodyIndexFrame::get_BodyIndexFrameSource
KeywordF : get_BodyIndexFrameSource
KeywordF : Microsoft.Kinect.kinect.IBodyIndexFrame.get_BodyIndexFrameSource(IBodyIndexFrameSource@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyIndexFrame.get_BodyIndexFrameSource(IBodyIndexFrameSource@)
AssetID : M:Microsoft.Kinect.kinect.IBodyIndexFrame.get_BodyIndexFrameSource(IBodyIndexFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyIndexFrame::get_BodyIndexFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
