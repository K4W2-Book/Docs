IBody::get\_Lean Method  
=======================  

身体の傾きを取得する。<br/>左右方向、前後方向の傾きを取得できる。<br/>左側または後方に傾いている場合は-1.0f、右側または前方に傾いている場合は1.0fを示す。 <span id="syntaxSection"></span>

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
HRESULT get_Lean(  
         PointF *amount  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*amount*    
Type: PointF  
[out] 身体の傾き。[-1.0f, 1.0f]  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

X成分は左右方向の傾き、Y成分は前後方向の傾きを示す。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_Lean Method
RLTitle : IBody::get_Lean Method
KeywordK : get_Lean method
KeywordK : IBody::get_Lean method
KeywordF : IBody::get_Lean
KeywordF : get_Lean
KeywordF : Microsoft.Kinect.kinect.IBody.get_Lean(PointF@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_Lean(PointF@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_Lean(PointF@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_Lean
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
