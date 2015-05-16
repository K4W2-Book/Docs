IDiscreteGestureResult::get\_FirstFrameDetected Method  
======================================================  

ジェスチャーが検出された最初のフレームかを取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FirstFrameDetected(  
         BOOLEAN *firstFrameDetected  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*firstFrameDetected*    
Type: BOOLEAN  
[out] 検出された最初のフレームの場合は**true**、それ以外の場合は**false**。  

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
TOCTitle : get_FirstFrameDetected Method
RLTitle : IDiscreteGestureResult::get_FirstFrameDetected Method
KeywordK : get_FirstFrameDetected method
KeywordK : IDiscreteGestureResult::get_FirstFrameDetected method
KeywordF : IDiscreteGestureResult::get_FirstFrameDetected
KeywordF : get_FirstFrameDetected
KeywordF : Microsoft.Kinect.visualgesturebuilder.IDiscreteGestureResult.get_FirstFrameDetected(BOOLEAN@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IDiscreteGestureResult.get_FirstFrameDetected(BOOLEAN@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IDiscreteGestureResult.get_FirstFrameDetected(BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IDiscreteGestureResult::get_FirstFrameDetected
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
