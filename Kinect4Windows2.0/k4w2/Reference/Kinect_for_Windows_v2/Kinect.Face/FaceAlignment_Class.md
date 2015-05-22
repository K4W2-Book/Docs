FaceAlignment クラス  
===================  

位置合わせされた顔データ。
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
<td align="left"><pre><code>public ref class FaceAlignment sealed</code></pre></td>
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
<td align="left"><pre><code>public sealed class FaceAlignment</code></pre></td>
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
<td align="left"><pre><code>var faceAlignment = Microsoft.Kinect.Face.FaceAlignment;</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

メンバ
=======  

**FaceAlignment** has the following members.  

<span id="publicconstructorsSection"></span>

コンストラクタ
============  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">名前</th>
<th align="left">説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="FaceAlignment_Class/Constructor.md">FaceAlignment</a></td>
<td align="left">FaceAlignmentクラスの新しいインスタンスを生成する。</td>
</tr>
</tbody>
</table>

<span id="publicpropertiesSection"></span>

プロパティ
==========  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">名前</th>
<th align="left">説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="FaceAlignment_Class/Properties/AnimationUnits_Property.md">AnimationUnits</a></td>
<td align="left">顔のアニメーションユニットを取得する。<br/>アニメーションユニットは顔アバターのための各顔パーツの動きを表す。</td>
</tr>
<tr class="even">
<td align="left"><a href="FaceAlignment_Class/Properties/FaceBoundingBox_Property.md">FaceBoundingBox</a></td>
<td align="left">顔を囲むバウンディングボックス(Color座標系)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="FaceAlignment_Class/Properties/FaceOrientation_Property.md">FaceOrientation</a></td>
<td align="left">顔の回転方向(クォータニオン)を取得/設定する。</td>
</tr>
<tr class="even">
<td align="left"><a href="FaceAlignment_Class/Properties/HeadPivotPoint_Property.md">HeadPivotPoint</a></td>
<td align="left">顔の回転軸の中心座標(Camera座標系)を取得/設定する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="FaceAlignment_Class/Properties/Quality_Property.md">Quality</a></td>
<td align="left">顔の位置合わせの品質を取得する。</td>
</tr>
</tbody>
</table>

<span id="remarks"></span>

Remarks  
=======  

Point calculation is performed in class [HighDefinitionFaceFrame](HighDefinitionFaceFrame.md).  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4E5"></span>

See also  
========  

<span id="ID4EAB"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceAlignment Class
RLTitle : FaceAlignment Class
KeywordK : FaceAlignment class, about
HelpPriority : 2
TopicType : apiref
KeywordF : Microsoft.Kinect.Face.FaceAlignment
KeywordF : FaceAlignment
KeywordF : Microsoft.Kinect.Face.FaceAlignment
KeywordA : T:Microsoft.Kinect.Face.FaceAlignment
AssetID : T:Microsoft.Kinect.Face.FaceAlignment
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceAlignment
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
