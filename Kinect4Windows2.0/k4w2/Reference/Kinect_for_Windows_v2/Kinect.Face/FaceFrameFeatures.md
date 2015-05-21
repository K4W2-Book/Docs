FaceFrameFeatures 列挙体  
=============================  

Faceフレームの機能を示すフラグ。
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
<td align="left"><pre><code>[FlagsAttribute]  
public enum class FaceFrameFeatures</code></pre></td>
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
<td align="left"><pre><code>[FlagsAttribute]  
public enum FaceFrameFeatures</code></pre></td>
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
<td align="left"><pre><code>var faceFrameFeatures = Microsoft.Kinect.Face.FaceFrameFeatures.none;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EOC"></span>

Members  
=======  

| Member                         | Value | Description                                  |
|--------------------------------|-------|----------------------------------------------|
| **None**                       | 0     | 無効。                        |
| **BoundingBoxInInfraredSpace** | 1     | 顔を囲むバウンディングボックス(Depth座標系)。 |
| **PointsInInfraredSpace**      | 2     | 顔パーツ(左右目、鼻、左右口角)の位置(Depth座標系)。        |
| **BoundingBoxInColorSpace**    | 4     | 顔を囲むバウンディングボックス(Color座標系)。    |
| **PointsInColorSpace**         | 8     | 顔パーツ(左右目、鼻、左右口角)の位置(Color座標系)。          |
| **RotationOrientation**        | 16    | 顔の回転方向(クォータニオン)。        |
| **Happy**                      | 32    | 笑顔の状態。                  |
| **RightEyeClosed**             | 64    | 右目が閉じている状態。                 |
| **LeftEyeClosed**              | 128   | 左目が閉じている状態。              |
| **MouthOpen**                  | 256   | 口が開いている状態。                |
| **MouthMoved**                 | 512   | 口が動いている状態。              |
| **LookingAway**                | 1024  | 顔がセンサーの方向を向いていない状態。              |
| **Glasses**                    | 2048  | 眼鏡を掛けている状態。                  |
| **FaceEngagement**             | 4096  | 顔の付随情報を取得できている状態。             |

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Face  
**Assembly:**Microsoft.Kinect.Face (in microsoft.kinect.face.dll)  

<span id="ID4EVC"></span>

See also  
========  

<span id="ID4EXC"></span>
#### Reference  

[Microsoft.Kinect.Face Namespace](../Kinect.Face.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceFrameFeatures Enumeration
RLTitle : FaceFrameFeatures Enumeration
KeywordK : FaceFrameFeatures enumeration
KeywordK : Microsoft.Kinect.Face.FaceFrameFeatures enumeration
HelpPriority : 2
KeywordF : Microsoft.Kinect.Face.FaceFrameFeatures
KeywordF : FaceFrameFeatures
KeywordF : Microsoft.Kinect.Face.FaceFrameFeatures
KeywordA : T:Microsoft.Kinect.Face.FaceFrameFeatures
AssetID : T:Microsoft.Kinect.Face.FaceFrameFeatures
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.face.dll
APIName : Microsoft.Kinect.Face.FaceFrameFeatures
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
