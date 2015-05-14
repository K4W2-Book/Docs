IFaceModel Interface  
====================  

顔モデル。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IFaceModel : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IFaceModel**は以下のメンバー関数を持ちます。  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="IFaceModel_Interface/Methods/CalculateVerticesForAlignm.md">CalculateVerticesForAlignment</a></td>
<td align="left">位置合わせされた顔モデルから頂点の座標(Camera座標系)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModel_Interface/Methods/get_HairColor_Method.md">get_HairColor</a></td>
<td align="left">髪の色を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModel_Interface/Methods/get_Scale_Method.md">get_Scale</a></td>
<td align="left">顔モデルの相対的なスケールを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModel_Interface/Methods/get_SkinColor_Method.md">get_SkinColor</a></td>
<td align="left">肌の色を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModel_Interface/Methods/GetFaceShapeDeformations.md">GetFaceShapeDeformations</a></td>
<td align="left">シェイプユニットを取得する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IFaceModel Interface
RLTitle : IFaceModel Interface
KeywordK : IFaceModel interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IFaceModel
KeywordF : Microsoft.Kinect.face.IFaceModel
KeywordA : T:Microsoft.Kinect.face.IFaceModel
AssetID : T:Microsoft.Kinect.face.IFaceModel
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModel
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
