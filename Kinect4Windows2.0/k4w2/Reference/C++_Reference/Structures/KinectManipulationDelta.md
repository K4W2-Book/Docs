KinectManipulationDelta Structure  
=================================  

現在の操作の累積変化量。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef struct _KinectManipulationDelta {  
    PointF Translation;  
    float Scale;  
    float Rotation;  
    float Expansion;  
} KinectManipulationDelta;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Members  

**Translation**    
対象のウィンドウの座標系([0,1]に正規化)におけるX軸、Y軸の画面座標の変化量。  

**Scale**    
拡大倍率の変化量。(乗法)  

**Rotation**    
回転角度の変化量。(度数法)  
常に0.0f。

**Expansion**    
拡張パラメータ。  
常に0.0f。

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : KinectManipulationDelta Structure
RLTitle : KinectManipulationDelta Structure
KeywordK : KinectManipulationDelta structure
KeywordF : KinectManipulationDelta
KeywordF : Microsoft.Kinect.kinect.KinectManipulationDelta
KeywordA : T:Microsoft.Kinect.kinect.KinectManipulationDelta
AssetID : T:Microsoft.Kinect.kinect.KinectManipulationDelta
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.KinectManipulationDelta
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
