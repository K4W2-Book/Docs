IBody::get\_HandLeftState Method  
================================  

左手のハンドステータスを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_HandLeftState(  
         HandState *handState  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*handState*    
Type: [HandState](../../../Enumerations/HandState_Enumeration.md)  
[out] 左手のハンドステータス。  

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
TOCTitle : get_HandLeftState Method
RLTitle : IBody::get_HandLeftState Method
KeywordK : get_HandLeftState method
KeywordK : IBody::get_HandLeftState method
KeywordF : IBody::get_HandLeftState
KeywordF : get_HandLeftState
KeywordF : Microsoft.Kinect.kinect.IBody.get_HandLeftState(HandState@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_HandLeftState(HandState@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_HandLeftState(HandState@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_HandLeftState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
