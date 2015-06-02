IBody::GetExpressionDetectionResults Method  
===========================================  

Expressionの検出結果を取得する。
この機能はKinect for Windowsアプリケーションではサポートされません。
このメンバ関数はXbox One SDKとのクロスコンパイルをサポートするために含まれています。 <span id="syntaxSection"></span>

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
HRESULT GetExpressionDetectionResults(  
         _Pre_equal_to_(Expression_Count)UINT capacity,  
         DetectionResult *detectionResults  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: \_Pre\_equal\_to\_(Expression\_Count)UINT  
Expressionの配列のサイズ。(2)  

*detectionResults*    
Type: DetectionResult  
[out] Expressionの配列の先頭アドレス。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

常にDetectionResult\_Unknownを示す。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetExpressionDetectionResults Method
RLTitle : IBody::GetExpressionDetectionResults Method
KeywordK : GetExpressionDetectionResults method
KeywordK : IBody::GetExpressionDetectionResults method
KeywordF : IBody::GetExpressionDetectionResults
KeywordF : GetExpressionDetectionResults
KeywordF : Microsoft.Kinect.kinect.IBody.GetExpressionDetectionResults(_Pre_equal_to_(Expression_Count)UINT,DetectionResult@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.GetExpressionDetectionResults(_Pre_equal_to_(Expression_Count)UINT,DetectionResult@)
AssetID : M:Microsoft.Kinect.kinect.IBody.GetExpressionDetectionResults(_Pre_equal_to_(Expression_Count)UINT,DetectionResult@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::GetExpressionDetectionResults
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
