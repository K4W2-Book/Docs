SetKinectTwoPersonManualEngagement  
==================================  

手動で指定してトラッキングする2人の[IBodyHandPair](../Interfaces/IBodyHandPair_Interface.md)を設定する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT SetKinectTwoPersonManualEngagement(  
         IBodyHandPair *pBodyHandPair1,  
         IBodyHandPair *pBodyHandPair2  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pBodyHandPair1*    
Type: IBodyHandPair  
[in] トラッキングする[IKinectSensor](../Interfaces/IKinectSensor_Interface.md)。  

*pBodyHandPair2*    
Type: IBodyHandPair  
[in] トラッキングする[IKinectSensor](../Interfaces/IKinectSensor_Interface.md)。  

<span id="ID4EN"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : SetKinectTwoPersonManualEngagement
RLTitle : SetKinectTwoPersonManualEngagement
KeywordK : SetKinectTwoPersonManualEngagement
KeywordF : SetKinectTwoPersonManualEngagement
KeywordF : Microsoft.Kinect.kinect.SetKinectTwoPersonManualEngagement(IBodyHandPair,IBodyHandPair)
KeywordA : M:Microsoft.Kinect.kinect.SetKinectTwoPersonManualEngagement(IBodyHandPair,IBodyHandPair)
AssetID : M:Microsoft.Kinect.kinect.SetKinectTwoPersonManualEngagement(IBodyHandPair,IBodyHandPair)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.SetKinectTwoPersonManualEngagement
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
