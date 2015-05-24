FaceModel.CalculateVerticesForAlignment メソッド  
==============================================  

位置合わせされた顔モデルから頂点の座標(Camera座標系)を取得する。
<span id="syntaxSection"></span>

構文
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
IVectorView&lt;<a href="../../../Kinect/CameraSpacePoint_Structure.md">CameraSpacePoint</a>, &gt;^ CalculateVerticesForAlignment(  
         <a href="../../FaceAlignment_Class.md">FaceAlignment</a>^ faceAlignment  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public IReadOnlyList&lt;<a href="../../../Kinect/CameraSpacePoint_Structure.md">CameraSpacePoint</a>, &gt;CalculateVerticesForAlignment (  
         <a href="../../FaceAlignment_Class.md">FaceAlignment</a>faceAlignment  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var iVectorView = faceModel.calculateVerticesForAlignment(faceAlignment);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### 引数  

*faceAlignment*    
Type: [FaceAlignment](../../FaceAlignment_Class.md)  
位置合わせされたFaceAlignmentクラス。

<span id="ID4EP"></span>
#### 戻り値

[C++]   
 [C\#]   
 [JavaScript]   

Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[CameraSpacePoint](../../../Kinect/CameraSpacePoint_Structure.md), \>
Type: [IReadOnlyList](http://msdn.microsoft.com/en-us/library/hh192385.aspx)\<[CameraSpacePoint](../../../Kinect/CameraSpacePoint_Structure.md), \>
Type: [IVectorView](http://msdn.microsoft.com/en-us/library/br226058.aspx)\<[CameraSpacePoint](../../../Kinect/CameraSpacePoint_Structure.md), \>

顔モデルの頂点(Camera座標系)の配列。  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4ELB"></span>

See also  
========  

<span id="ID4ENB"></span>
#### Reference  

[FaceModel Class](../../FaceModel_Class.md)  
 [Microsoft.Kinect.Face Namespace](../../../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CalculateVerticesForAlignment Method
RLTitle : FaceModel.CalculateVerticesForAlignment Method
KeywordK : CalculateVerticesForAlignment method
KeywordK : FaceModel.CalculateVerticesForAlignment method
KeywordF : Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment
KeywordF : FaceModel.CalculateVerticesForAlignment
KeywordF : CalculateVerticesForAlignment
KeywordF : Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment(Microsoft.Kinect.Face.FaceAlignment)
KeywordA : M:Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment(Microsoft.Kinect.Face.FaceAlignment)
AssetID : M:Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment(Microsoft.Kinect.Face.FaceAlignment)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceModel.CalculateVerticesForAlignment
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
