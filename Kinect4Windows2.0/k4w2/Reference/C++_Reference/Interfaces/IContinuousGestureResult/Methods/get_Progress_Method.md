IContinuousGestureResult::get\_Progress Method  
==============================================  

ジェスチャーの進行状況を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_Progress(  
         float *progress  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*progress*    
Type: float  
[out] ジェスチャーの進行状況。  

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
TOCTitle : get_Progress Method
RLTitle : IContinuousGestureResult::get_Progress Method
KeywordK : get_Progress method
KeywordK : IContinuousGestureResult::get_Progress method
KeywordF : IContinuousGestureResult::get_Progress
KeywordF : get_Progress
KeywordF : Microsoft.Kinect.visualgesturebuilder.IContinuousGestureResult.get_Progress(float@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IContinuousGestureResult.get_Progress(float@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IContinuousGestureResult.get_Progress(float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IContinuousGestureResult::get_Progress
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
