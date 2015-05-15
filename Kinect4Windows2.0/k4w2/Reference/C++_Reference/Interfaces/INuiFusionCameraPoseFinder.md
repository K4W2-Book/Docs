INuiFusionCameraPoseFinder Interface  
====================================  

フレームとカメラ姿勢を蓄積するデータベースCameraPoseFinder。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface INuiFusionCameraPoseFinder : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**INuiFusionCameraPoseFinder**は以下のメンバー関数を持ちます。  

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
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/FindCameraPose_Method.md">FindCameraPose</a></td>
<td align="left">現在のフレームと最も類似するフレームのカメラポーズをデータベースから取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/GetCameraPoseFinderParamet.md">GetCameraPoseFinderParameters</a></td>
<td align="left">データベースのパラメーターを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/GetStoredPoseCount_Method.md">GetStoredPoseCount</a></td>
<td align="left">データベースに含まれるカメラポーズの数を取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/LoadCameraPoseFinderDatabase.md">LoadCameraPoseFinderDatabase</a></td>
<td align="left">ファイルからデータベースを読み込む。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/ProcessFrame_Method.md">ProcessFrame</a></td>
<td align="left">データベースに含まれるフレーム・カメラ姿勢と十分に異なる場合、新たにデータベースに登録する。</td>
</tr>
<tr class="even">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/ResetCameraPoseFinder_Method.md">ResetCameraPoseFinder</a></td>
<td align="left">データベースをリセットする。</td>
</tr>
<tr class="odd">
<td align="left"><a href="INuiFusionCameraPoseFinder/Methods/SaveCameraPoseFinderDatabase.md">SaveCameraPoseFinderDatabase</a></td>
<td align="left">データベースをファイルに保存する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** nuikinectfusioncameraposefinder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : INuiFusionCameraPoseFinder Interface
RLTitle : INuiFusionCameraPoseFinder Interface
KeywordK : INuiFusionCameraPoseFinder interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : INuiFusionCameraPoseFinder
KeywordF : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder
KeywordA : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder
AssetID : T:Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.nuikinectfusioncameraposefinder.INuiFusionCameraPoseFinder
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
