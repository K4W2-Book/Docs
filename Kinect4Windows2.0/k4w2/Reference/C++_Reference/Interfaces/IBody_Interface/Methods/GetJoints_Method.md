IBody::GetJoints Method  
=======================  

Jointを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetJoints(  
         _Pre_equal_to_(JointType_Count)UINT capacity,  
         Joint *joints  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: \_Pre\_equal\_to\_(JointType\_Count)UINT  
Jointの配列のサイズ。(25)  

*joints*    
Type: Joint  
[out] Jointの配列の先頭アドレス。  

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
TOCTitle : GetJoints Method
RLTitle : IBody::GetJoints Method
KeywordK : GetJoints method
KeywordK : IBody::GetJoints method
KeywordF : IBody::GetJoints
KeywordF : GetJoints
KeywordF : Microsoft.Kinect.kinect.IBody.GetJoints(_Pre_equal_to_(JointType_Count)UINT,Joint@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.GetJoints(_Pre_equal_to_(JointType_Count)UINT,Joint@)
AssetID : M:Microsoft.Kinect.kinect.IBody.GetJoints(_Pre_equal_to_(JointType_Count)UINT,Joint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::GetJoints
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
