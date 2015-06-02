IBody::GetJointOrientations Method  
==================================  

Jointの向きを取得する。 <span id="syntaxSection"></span>

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
HRESULT GetJointOrientations(  
         _Pre_equal_to_(JointType_Count)UINT capacity,  
         JointOrientation *jointOrientations  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: \_Pre\_equal\_to\_(JointType\_Count)UINT  
Jointの向きの配列のサイズ。(25)  

*jointOrientations*    
Type: JointOrientation  
[out] Jointの向きの配列の先頭アドレス。  

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
TOCTitle : GetJointOrientations Method
RLTitle : IBody::GetJointOrientations Method
KeywordK : GetJointOrientations method
KeywordK : IBody::GetJointOrientations method
KeywordF : IBody::GetJointOrientations
KeywordF : GetJointOrientations
KeywordF : Microsoft.Kinect.kinect.IBody.GetJointOrientations(_Pre_equal_to_(JointType_Count)UINT,JointOrientation@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.GetJointOrientations(_Pre_equal_to_(JointType_Count)UINT,JointOrientation@)
AssetID : M:Microsoft.Kinect.kinect.IBody.GetJointOrientations(_Pre_equal_to_(JointType_Count)UINT,JointOrientation@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::GetJointOrientations
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
