IVisualGestureBuilderFrame::get\_ContinuousGestureResult Method  
===============================================================  

Continuous(連続的)ジェスチャーの結果を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_ContinuousGestureResult(  
         IGesture *gesture,  
         _COM_Outptr_result_maybenull_ IContinuousGestureResult **result  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*gesture*    
Type: IGesture  
[in] 識別器。  

*result*    
Type: \_COM\_Outptr\_result\_maybenull\_ IContinuousGestureResult  
IContinuousGestureResultのポインタのアドレス。  
この値はNULLになることがあります。  

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
TOCTitle : get_ContinuousGestureResult Method
RLTitle : IVisualGestureBuilderFrame::get_ContinuousGestureResult Method
KeywordK : get_ContinuousGestureResult method
KeywordK : IVisualGestureBuilderFrame::get_ContinuousGestureResult method
KeywordF : IVisualGestureBuilderFrame::get_ContinuousGestureResult
KeywordF : get_ContinuousGestureResult
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame.get_ContinuousGestureResult(IGesture,_COM_Outptr_result_maybenull_ IContinuousGestureResult)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame.get_ContinuousGestureResult(IGesture,_COM_Outptr_result_maybenull_ IContinuousGestureResult)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame.get_ContinuousGestureResult(IGesture,_COM_Outptr_result_maybenull_ IContinuousGestureResult)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrame::get_ContinuousGestureResult
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
