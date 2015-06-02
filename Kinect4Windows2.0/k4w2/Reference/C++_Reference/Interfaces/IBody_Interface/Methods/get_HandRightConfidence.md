IBody::get\_HandRightConfidence Method  
======================================  

右手のトラッキングの信頼度を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_HandRightConfidence(  
         TrackingConfidence *confidence  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*confidence*    
Type: [TrackingConfidence](../../../Enumerations/TrackingConfidence.md)  
[out] トラッキングの信頼度。  

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
TOCTitle : get_HandRightConfidence Method
RLTitle : IBody::get_HandRightConfidence Method
KeywordK : get_HandRightConfidence method
KeywordK : IBody::get_HandRightConfidence method
KeywordF : IBody::get_HandRightConfidence
KeywordF : get_HandRightConfidence
KeywordF : Microsoft.Kinect.kinect.IBody.get_HandRightConfidence(TrackingConfidence@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_HandRightConfidence(TrackingConfidence@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_HandRightConfidence(TrackingConfidence@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_HandRightConfidence
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
