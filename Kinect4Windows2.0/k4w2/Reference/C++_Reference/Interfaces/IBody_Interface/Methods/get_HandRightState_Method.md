IBody::get\_HandRightState Method  
=================================  

右手のハンドステータスを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_HandRightState(  
         HandState *handState  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*handState*    
Type: [HandState](../../../Enumerations/HandState_Enumeration.md)  
[out] 右手のハンドステータス。  

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
TOCTitle : get_HandRightState Method
RLTitle : IBody::get_HandRightState Method
KeywordK : get_HandRightState method
KeywordK : IBody::get_HandRightState method
KeywordF : IBody::get_HandRightState
KeywordF : get_HandRightState
KeywordF : Microsoft.Kinect.kinect.IBody.get_HandRightState(HandState@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_HandRightState(HandState@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_HandRightState(HandState@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_HandRightState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
