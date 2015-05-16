IVisualGestureBuilderFrameSource::AddGestures Method  
====================================================  

複数の識別器を追加する。 <span id="syntaxSection"></span>

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
HRESULT AddGestures(  
         UINT capacity,  
         IGesture **gestures  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
[in] 識別器の配列のサイズ。  

*gestures*    
Type: IGesture  
[in] 識別器の配列のアドレス。  

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
TOCTitle : AddGestures Method
RLTitle : IVisualGestureBuilderFrameSource::AddGestures Method
KeywordK : AddGestures method
KeywordK : IVisualGestureBuilderFrameSource::AddGestures method
KeywordF : IVisualGestureBuilderFrameSource::AddGestures
KeywordF : AddGestures
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.AddGestures(UINT,IGesture)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.AddGestures(UINT,IGesture)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.AddGestures(UINT,IGesture)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource::AddGestures
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
