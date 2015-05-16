IVisualGestureBuilderFrameSource::SetIsEnabled Method  
=====================================================  

指定した識別器の有効・無効を設定する。 <span id="syntaxSection"></span>

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
HRESULT SetIsEnabled(  
         IGesture *gesture,  
         BOOLEAN isEnabled  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*gesture*    
Type: IGesture  
[in] 識別器。  

*isEnabled*    
Type: BOOLEAN  
識別器を有効に設定する場合は**true**、無効に設定する場合は**false**。  

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
TOCTitle : SetIsEnabled Method
RLTitle : IVisualGestureBuilderFrameSource::SetIsEnabled Method
KeywordK : SetIsEnabled method
KeywordK : IVisualGestureBuilderFrameSource::SetIsEnabled method
KeywordF : IVisualGestureBuilderFrameSource::SetIsEnabled
KeywordF : SetIsEnabled
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.SetIsEnabled(IGesture,BOOLEAN)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.SetIsEnabled(IGesture,BOOLEAN)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.SetIsEnabled(IGesture,BOOLEAN)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource::SetIsEnabled
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
