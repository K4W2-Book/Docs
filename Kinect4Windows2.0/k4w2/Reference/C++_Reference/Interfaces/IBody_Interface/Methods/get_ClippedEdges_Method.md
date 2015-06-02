IBody::get\_ClippedEdges Method  
===============================  

人物がカメラの視野に収まっていない端を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_ClippedEdges(  
         DWORD *clippedEdges  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*clippedEdges*    
Type: DWORD  
[out] 人物がカメラの視野に収まっていない端。([FrameEdges](../../../Enumerations/FrameEdges_Enumeration.md))  

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
TOCTitle : get_ClippedEdges Method
RLTitle : IBody::get_ClippedEdges Method
KeywordK : get_ClippedEdges method
KeywordK : IBody::get_ClippedEdges method
KeywordF : IBody::get_ClippedEdges
KeywordF : get_ClippedEdges
KeywordF : Microsoft.Kinect.kinect.IBody.get_ClippedEdges(DWORD@)
KeywordA : M:Microsoft.Kinect.kinect.IBody.get_ClippedEdges(DWORD@)
AssetID : M:Microsoft.Kinect.kinect.IBody.get_ClippedEdges(DWORD@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBody::get_ClippedEdges
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
