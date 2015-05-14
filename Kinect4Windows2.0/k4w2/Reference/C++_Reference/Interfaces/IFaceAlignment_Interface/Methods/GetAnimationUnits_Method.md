IFaceAlignment::GetAnimationUnits Method  
========================================  

顔のアニメーションユニットを取得する。<br/>アニメーションユニットは顔アバターのための各顔パーツの動きを表す。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>public:  
HRESULT GetAnimationUnits(  
         UINT capacity,  
         float *animationUnits  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
アニメーションユニットの配列のサイズ。(17)  

*animationUnits*    
Type: float  
[out] アニメーションユニットの配列のアドレス。  

<span id="ID4EP"></span>
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
TOCTitle : GetAnimationUnits Method
RLTitle : IFaceAlignment::GetAnimationUnits Method
KeywordK : GetAnimationUnits method
KeywordK : IFaceAlignment::GetAnimationUnits method
KeywordF : IFaceAlignment::GetAnimationUnits
KeywordF : GetAnimationUnits
KeywordF : Microsoft.Kinect.face.IFaceAlignment.GetAnimationUnits(UINT,float@)
KeywordA : M:Microsoft.Kinect.face.IFaceAlignment.GetAnimationUnits(UINT,float@)
AssetID : M:Microsoft.Kinect.face.IFaceAlignment.GetAnimationUnits(UINT,float@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceAlignment::GetAnimationUnits
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
