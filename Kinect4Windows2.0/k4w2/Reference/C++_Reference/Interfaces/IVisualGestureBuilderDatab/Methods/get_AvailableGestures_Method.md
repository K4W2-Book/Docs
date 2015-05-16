IVisualGestureBuilderDatabase::get\_AvailableGestures Method  
============================================================  

データベースに含まれる識別器を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_AvailableGestures(  
         UINT32 capacity,  
         IGesture **availableGestures  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT32  
[in] 識別器の配列のサイズ。  

*availableGestures*    
Type: IGesture  
[out] 識別器の配列のアドレス。  

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
TOCTitle : get_AvailableGestures Method
RLTitle : IVisualGestureBuilderDatabase::get_AvailableGestures Method
KeywordK : get_AvailableGestures method
KeywordK : IVisualGestureBuilderDatabase::get_AvailableGestures method
KeywordF : IVisualGestureBuilderDatabase::get_AvailableGestures
KeywordF : get_AvailableGestures
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderDatabase.get_AvailableGestures(UINT32,IGesture@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderDatabase.get_AvailableGestures(UINT32,IGesture@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderDatabase.get_AvailableGestures(UINT32,IGesture@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderDatabase::get_AvailableGestures
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
