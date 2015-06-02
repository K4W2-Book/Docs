IBody::get\_LeanTrackingState Method  
====================================  

身体の傾きのトラッキングステータスを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_LeanTrackingState(  
         TrackingState *trackingState  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*trackingState*    
Type: [TrackingState](../../../Enumerations/TrackingState_Enumeration.md)  
[out] 身体の傾きのトラッキングステータス。  

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
TOCTitle : get_LeanTrackingState Method
RLTitle : IBody::get_LeanTrackingState Method
KeywordK : get_LeanTrackingState method
KeywordK : IBody::get_LeanTrackingState method
KeywordF : IBody::get_LeanTrackingState
KeywordF : get_LeanTrackingState
KeywordF : Microsoft.Kinect.kinect.IBody.get_LeanTrackingState(TrackingState@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_LeanTrackingState(TrackingState@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_LeanTrackingState(TrackingState@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_LeanTrackingState
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
