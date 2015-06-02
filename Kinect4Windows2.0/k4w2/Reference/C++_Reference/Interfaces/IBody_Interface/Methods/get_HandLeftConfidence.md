IBody::get\_HandLeftConfidence Method  
=====================================  

左手のトラッキングの信頼度を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_HandLeftConfidence(  
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
TOCTitle : get_HandLeftConfidence Method
RLTitle : IBody::get_HandLeftConfidence Method
KeywordK : get_HandLeftConfidence method
KeywordK : IBody::get_HandLeftConfidence method
KeywordF : IBody::get_HandLeftConfidence
KeywordF : get_HandLeftConfidence
KeywordF : Microsoft.Kinect.kinect.IBody.get_HandLeftConfidence(TrackingConfidence@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_HandLeftConfidence(TrackingConfidence@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_HandLeftConfidence(TrackingConfidence@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_HandLeftConfidence
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
