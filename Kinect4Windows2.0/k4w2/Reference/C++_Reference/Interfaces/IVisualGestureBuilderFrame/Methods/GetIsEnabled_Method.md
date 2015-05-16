IVisualGestureBuilderFrameSource::GetIsEnabled Method  
=====================================================  

指定した識別器の設定状況を取得する。 <span id="syntaxSection"></span>

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
HRESULT GetIsEnabled(  
         IGesture *gesture,  
         BOOLEAN *isEnabled  
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
[out] 識別器が有効の場合は**true**、無効の場合は**false**。  

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
TOCTitle : GetIsEnabled Method
RLTitle : IVisualGestureBuilderFrameSource::GetIsEnabled Method
KeywordK : GetIsEnabled method
KeywordK : IVisualGestureBuilderFrameSource::GetIsEnabled method
KeywordF : IVisualGestureBuilderFrameSource::GetIsEnabled
KeywordF : GetIsEnabled
KeywordF : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.GetIsEnabled(IGesture,BOOLEAN@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.GetIsEnabled(IGesture,BOOLEAN@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource.GetIsEnabled(IGesture,BOOLEAN@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.IVisualGestureBuilderFrameSource::GetIsEnabled
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
