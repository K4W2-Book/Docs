IBody::get\_IsTracked Method  
============================  

身体のトラッキングステータスを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_IsTracked(  
         BOOLEAN *tracked  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*tracked*    
Type: BOOLEAN  
[out] トラッキングされている場合は**true**、トラッキングされていない場合は**false**。  

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
TOCTitle : get_IsTracked Method
RLTitle : IBody::get_IsTracked Method
KeywordK : get_IsTracked method
KeywordK : IBody::get_IsTracked method
KeywordF : IBody::get_IsTracked
KeywordF : get_IsTracked
KeywordF : Microsoft.Kinect.kinect.IBody.get_IsTracked(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_IsTracked(BOOLEAN@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_IsTracked(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_IsTracked
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
