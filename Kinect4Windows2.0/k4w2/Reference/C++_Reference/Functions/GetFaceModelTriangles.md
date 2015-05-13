GetFaceModelTriangles  
=====================  

顔モデルの三角形を取得する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT GetFaceModelTriangles(  
         UINT32 capacity,  
         UINT32 *triangeVertices  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT32  
三角形の配列のサイズ。（2630）  

*triangeVertices*    
Type: UINT32  
[out] 三角形の配列。  

<span id="ID4EN"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetFaceModelTriangles
RLTitle : GetFaceModelTriangles
KeywordK : GetFaceModelTriangles
KeywordF : GetFaceModelTriangles
KeywordF : Microsoft.Kinect.face.GetFaceModelTriangles(UINT32,UINT32@)
KeywordA : M:Microsoft.Kinect.face.GetFaceModelTriangles(UINT32,UINT32@)
AssetID : M:Microsoft.Kinect.face.GetFaceModelTriangles(UINT32,UINT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.GetFaceModelTriangles
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
