SetKinectOnePersonManualEngagement  
==================================  

手動で1人を指定してトラッキングする[IKinectSensor](../Interfaces/IKinectSensor_Interface.md)を設定する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT SetKinectOnePersonManualEngagement(  
         IBodyHandPair *pBodyHandPair  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pBodyHandPair*    
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
TOCTitle : SetKinectOnePersonManualEngagement
RLTitle : SetKinectOnePersonManualEngagement
KeywordK : SetKinectOnePersonManualEngagement
KeywordF : SetKinectOnePersonManualEngagement
KeywordF : Microsoft.Kinect.kinect.SetKinectOnePersonManualEngagement(IBodyHandPair)
KeywordA : M:Microsoft.Kinect.kinect.SetKinectOnePersonManualEngagement(IBodyHandPair)
AssetID : M:Microsoft.Kinect.kinect.SetKinectOnePersonManualEngagement(IBodyHandPair)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.SetKinectOnePersonManualEngagement
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
