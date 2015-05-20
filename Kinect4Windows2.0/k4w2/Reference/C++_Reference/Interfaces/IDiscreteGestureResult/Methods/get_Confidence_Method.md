IDiscreteGestureResult::get\_Confidence Method  
==============================================  

ジェスチャー検出の信頼値を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_Confidence(  
         float *confidence  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*confidence*    
Type: float  
[out] 検出の信頼値。[0.0f,1.0f]  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_Confidence Method
RLTitle : IDiscreteGestureResult::get_Confidence Method
KeywordK : get_Confidence method
KeywordK : IDiscreteGestureResult::get_Confidence method
KeywordF : IDiscreteGestureResult::get_Confidence
KeywordF : get_Confidence
KeywordF : Microsoft.Kinect.visualgesturebuilder.IDiscreteGestureResult.get_Confidence(float@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IDiscreteGestureResult.get_Confidence(float@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IDiscreteGestureResult.get_Confidence(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IDiscreteGestureResult::get_Confidence
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
