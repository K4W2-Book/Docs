IVisualGestureBuilderFrameReader::CalculateAndAcquireLatestFrame Method  
=======================================================================  

最新のVGBフレームを取得する。 <span id="syntaxSection"></span>

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
HRESULT CalculateAndAcquireLatestFrame(  
         IVisualGestureBuilderFrame **gestureFrame  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*gestureFrame*    
Type: IVisualGestureBuilderFrame  
[out] IVisualGestureBuilderFrameのポインタのアドレス。  

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
TOCTitle : CalculateAndAcquireLatestFrame Method
RLTitle : IVisualGestureBuilderFrameReader::CalculateAndAcquireLatestFrame Method
KeywordK : CalculateAndAcquireLatestFrame method
KeywordK : IVisualGestureBuilderFrameReader::CalculateAndAcquireLatestFrame method
KeywordF : IVisualGestureBuilderFrameReader::CalculateAndAcquireLatestFrame
KeywordF : CalculateAndAcquireLatestFrame
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReader.CalculateAndAcquireLatestFrame(IVisualGestureBuilderFrame@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReader.CalculateAndAcquireLatestFrame(IVisualGestureBuilderFrame@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReader.CalculateAndAcquireLatestFrame(IVisualGestureBuilderFrame@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameReader::CalculateAndAcquireLatestFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
