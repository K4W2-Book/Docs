IFaceAlignment Interface  
========================  

位置合わせされた顔データ。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IFaceAlignment : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IFaceAlignment**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IFaceAlignment_Interface/Methods/get_FaceBoundingBox_Method.md">get_FaceBoundingBox</a></td>
<td align="left">顔を囲むバウンディングボックス(Color座標系)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceAlignment_Interface/Methods/get_FaceOrientation_Method.md">get_FaceOrientation</a></td>
<td align="left">顔の回転方向(クォータニオン)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceAlignment_Interface/Methods/get_HeadPivotPoint_Method.md">get_HeadPivotPoint</a></td>
<td align="left">顔の回転軸の中心座標(Camera座標系)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceAlignment_Interface/Methods/get_Quality_Method.md">get_Quality</a></td>
<td align="left">顔の位置合わせの品質を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceAlignment_Interface/Methods/GetAnimationUnits_Method.md">GetAnimationUnits</a></td>
<td align="left">顔のアニメーションユニットを取得する。<br/>アニメーションユニットは顔アバターのための各顔パーツの動きを表す。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceAlignment_Interface/Methods/put_FaceOrientation_Method.md">put_FaceOrientation</a></td>
<td align="left">顔の回転方向(クォータニオン)を設定する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceAlignment_Interface/Methods/put_HeadPivotPoint_Method.md">put_HeadPivotPoint</a></td>
<td align="left">顔の回転軸の中心座標(Camera座標系)を設定する。</td>
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
TOCTitle : IFaceAlignment Interface
RLTitle : IFaceAlignment Interface
KeywordK : IFaceAlignment interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IFaceAlignment
KeywordF : Microsoft.Kinect.face.IFaceAlignment
KeywordA : T:Microsoft.Kinect.face.IFaceAlignment
AssetID : T:Microsoft.Kinect.face.IFaceAlignment
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceAlignment
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
