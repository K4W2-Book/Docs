IBodyFrameSource::OverrideAndReplaceHandTracking Method  
=======================================================  

トラッキングする手を変更する。(トラッキングをやめる古いトラッキングIDを指定する。) <span id="syntaxSection"></span>

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
HRESULT OverrideAndReplaceHandTracking(  
         UINT64 oldTrackingId,  
         UINT64 newTrackingId  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*oldTrackingId*    
Type: UINT64  
手のトラッキングをやめる古いトラッキングID。  

*newTrackingId*    
Type: UINT64  
手をトラッキングする新しいトラッキングID。  

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
TOCTitle : OverrideAndReplaceHandTracking Method
RLTitle : IBodyFrameSource::OverrideAndReplaceHandTracking Method
KeywordK : OverrideAndReplaceHandTracking method
KeywordK : IBodyFrameSource::OverrideAndReplaceHandTracking method
KeywordF : IBodyFrameSource::OverrideAndReplaceHandTracking
KeywordF : OverrideAndReplaceHandTracking
KeywordF : Microsoft.Kinect.kinect.IBodyFrameSource.OverrideAndReplaceHandTracking(UINT64,UINT64)
KeywordA : M:Microsoft.Kinect.kinect.IBodyFrameSource.OverrideAndReplaceHandTracking(UINT64,UINT64)
AssetID : M:Microsoft.Kinect.kinect.IBodyFrameSource.OverrideAndReplaceHandTracking(UINT64,UINT64)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrameSource::OverrideAndReplaceHandTracking
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
