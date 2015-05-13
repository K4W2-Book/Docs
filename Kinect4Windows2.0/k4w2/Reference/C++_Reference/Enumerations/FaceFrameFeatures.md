FaceFrameFeatures Enumeration  
=============================  

Faceの機能を示すフラグ。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _FaceFrameFeatures  
{  
    FaceFrameFeatures_None = 0,  
    FaceFrameFeatures_BoundingBoxInInfraredSpace = 0x1,  
    FaceFrameFeatures_PointsInInfraredSpace = 0x2,  
    FaceFrameFeatures_BoundingBoxInColorSpace = 0x4,  
    FaceFrameFeatures_PointsInColorSpace = 0x8,  
    FaceFrameFeatures_RotationOrientation = 0x10,  
    FaceFrameFeatures_Happy = 0x20,  
    FaceFrameFeatures_RightEyeClosed = 0x40,  
    FaceFrameFeatures_LeftEyeClosed = 0x80,  
    FaceFrameFeatures_MouthOpen = 0x100,  
    FaceFrameFeatures_MouthMoved = 0x200,  
    FaceFrameFeatures_LookingAway = 0x400,  
    FaceFrameFeatures_Glasses = 0x800,  
    FaceFrameFeatures_FaceEngagement = 0x1000  
} FaceFrameFeatures, FaceFrameFeatures_None, FaceFrameFeatures_BoundingBoxInInfraredSpace, FaceFrameFeatures_PointsInInfraredSpace, FaceFrameFeatures_BoundingBoxInColorSpace, FaceFrameFeatures_PointsInColorSpace, FaceFrameFeatures_RotationOrientation, FaceFrameFeatures_Happy, FaceFrameFeatures_RightEyeClosed, FaceFrameFeatures_LeftEyeClosed, FaceFrameFeatures_MouthOpen, FaceFrameFeatures_MouthMoved, FaceFrameFeatures_LookingAway, FaceFrameFeatures_Glasses, FaceFrameFeatures_FaceEngagement;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ELC"></span>

Constants  
=========  

| Constant                                      | Description                                  |
|-----------------------------------------------|----------------------------------------------|
| FaceFrameFeatures\_None                       | 無効。                                        |
| FaceFrameFeatures\_BoundingBoxInInfraredSpace | 顔を囲むバウンディングボックス(Depth座標系)。            |
| FaceFrameFeatures\_PointsInInfraredSpace      | 顔パーツ(左右目、鼻、左右口角)の位置(Depth座標系)。   |
| FaceFrameFeatures\_BoundingBoxInColorSpace    | 顔を囲むバウンディングボックス(Color座標系)。            |
| FaceFrameFeatures\_PointsInColorSpace         | 顔パーツ(左右目、鼻、左右口角)の位置(Color座標系)。   |
| FaceFrameFeatures\_RotationOrientation        | 顔の回転方向(クォータニオン)。                       |
| FaceFrameFeatures\_Happy                      | 笑顔の状態。                                    |
| FaceFrameFeatures\_RightEyeClosed             | 右目が閉じている状態。                             |
| FaceFrameFeatures\_LeftEyeClosed              | 左目が閉じている状態。                             |
| FaceFrameFeatures\_MouthOpen                  | 口が開いている状態。                               |
| FaceFrameFeatures\_MouthMoved                 | 口が動いている状態。                              |
| FaceFrameFeatures\_LookingAway                | 顔がセンサーの方向を向いていない状態。                 |
| FaceFrameFeatures\_Glasses                    | 眼鏡を掛けている状態。                            |
| FaceFrameFeatures\_FaceEngagement             | 顔の付随情報を取得できている状態。                  |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : FaceFrameFeatures Enumeration
RLTitle : FaceFrameFeatures Enumeration
KeywordK : FaceFrameFeatures enumeration
HelpPriority : 2
KeywordF : FaceFrameFeatures
KeywordF : Microsoft.Kinect.face.FaceFrameFeatures
KeywordA : T:Microsoft.Kinect.face.FaceFrameFeatures
AssetID : T:Microsoft.Kinect.face.FaceFrameFeatures
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.FaceFrameFeatures
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
