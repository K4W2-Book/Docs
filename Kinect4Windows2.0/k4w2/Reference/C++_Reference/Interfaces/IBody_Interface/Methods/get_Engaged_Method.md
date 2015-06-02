IBody::get\_Engaged Method  
==========================  

付随情報の検出結果を取得する。
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
HRESULT get_Engaged(  
         DetectionResult *detectionResult  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*detectionResult*    
Type: [DetectionResult](../../../Enumerations/DetectionResult_Enumeration.md)  
[out] 付随情報の検出結果。  

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
TOCTitle : get_Engaged Method
RLTitle : IBody::get_Engaged Method
KeywordK : get_Engaged method
KeywordK : IBody::get_Engaged method
KeywordF : IBody::get_Engaged
KeywordF : get_Engaged
KeywordF : Microsoft.Kinect.kinect.IBody.get_Engaged(DetectionResult@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_Engaged(DetectionResult@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_Engaged(DetectionResult@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_Engaged
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
