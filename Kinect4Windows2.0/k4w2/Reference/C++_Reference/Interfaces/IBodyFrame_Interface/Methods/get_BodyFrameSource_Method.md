IBodyFrame::get\_BodyFrameSource Method  
=======================================  

BodyフレームのSourceを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_BodyFrameSource(  
         IBodyFrameSource **bodyFrameSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*bodyFrameSource*    
Type: IBodyFrameSource  
[out] [IBodyFrameSource](../../IBodyFrameSource_Interface.md)のポインタのアドレス。  

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
TOCTitle : get_BodyFrameSource Method
RLTitle : IBodyFrame::get_BodyFrameSource Method
KeywordK : get_BodyFrameSource method
KeywordK : IBodyFrame::get_BodyFrameSource method
KeywordF : IBodyFrame::get_BodyFrameSource
KeywordF : get_BodyFrameSource
KeywordF : Microsoft.Kinect.kinect.IBodyFrame.get_BodyFrameSource(IBodyFrameSource@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyFrame.get_BodyFrameSource(IBodyFrameSource@)
AssetID : M:Microsoft.Kinect.kinect.IBodyFrame.get_BodyFrameSource(IBodyFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrame::get_BodyFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
