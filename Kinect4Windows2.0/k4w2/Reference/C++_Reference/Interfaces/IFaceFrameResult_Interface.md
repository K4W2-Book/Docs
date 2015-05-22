IFaceFrameResult Interface  
==========================  

Faceフレームの結果。 
<span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IFaceFrameResult : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IFaceFrameResult**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="IFaceFrameResult_Interface/Methods/get_FaceBoundingBoxInColorSpace.md">get_FaceBoundingBoxInColorSpace</a></td>
<td align="left">顔を囲むバウンディングボックス(Color座標系)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameResult_Interface/Methods/get.md">get_FaceBoundingBoxInInfraredSpace</a></td>
<td align="left">顔を囲むバウンディングボックス(Depth座標系)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameResult_Interface/Methods/get_FaceFrameFeatures_Method.md">get_FaceFrameFeatures</a></td>
<td align="left">Faceフレームの有効な機能を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameResult_Interface/Methods/get_FaceRotationQuaternion.md">get_FaceRotationQuaternion</a></td>
<td align="left">顔の回転方向(クォータニオン)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameResult_Interface/Methods/get_RelativeTime_Method.md">get_RelativeTime</a></td>
<td align="left">Faceフレームを取得した時間(相対時間)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameResult_Interface/Methods/get_TrackingId_Method.md">get_TrackingId</a></td>
<td align="left">トラッキングIDを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameResult_Interface/Methods/GetFacePointsInColorSpace.md">GetFacePointsInColorSpace</a></td>
<td align="left">顔パーツ(左右目、鼻、左右口角)の位置(Color座標系)を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceFrameResult_Interface/Methods/GetFacePointsInInfraredSpace.md">GetFacePointsInInfraredSpace</a></td>
<td align="left">顔パーツ(左右目、鼻、左右口角)の位置(Depth座標系)を取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceFrameResult_Interface/Methods/GetFaceProperties_Method.md">GetFaceProperties</a></td>
<td align="left">顔の付随情報を取得する。</td>
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
TOCTitle : IFaceFrameResult Interface
RLTitle : IFaceFrameResult Interface
KeywordK : IFaceFrameResult interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IFaceFrameResult
KeywordF : Microsoft.Kinect.face.IFaceFrameResult
KeywordA : T:Microsoft.Kinect.face.IFaceFrameResult
AssetID : T:Microsoft.Kinect.face.IFaceFrameResult
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameResult
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
