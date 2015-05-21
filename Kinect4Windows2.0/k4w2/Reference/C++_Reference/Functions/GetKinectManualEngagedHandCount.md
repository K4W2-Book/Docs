GetKinectManualEngagedHandCount  
===============================  

手動で人物と手を関係付けている[IBodyHandPair](../Interfaces/IBodyHandPair_Interface.md)の数を取得する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT GetKinectManualEngagedHandCount(  
         UINT32 *pManualEngagedHandCount  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pManualEngagedHandCount*    
Type: UINT32  
[out] [IBodyHandPair](../Interfaces/IBodyHandPair_Interface.md)の数。  

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
TOCTitle : GetKinectManualEngagedHandCount
RLTitle : GetKinectManualEngagedHandCount
KeywordK : GetKinectManualEngagedHandCount
KeywordF : GetKinectManualEngagedHandCount
KeywordF : Microsoft.Kinect.kinect.GetKinectManualEngagedHandCount(UINT32@)
KeywordA : M:Microsoft.Kinect.kinect.GetKinectManualEngagedHandCount(UINT32@)
AssetID : M:Microsoft.Kinect.kinect.GetKinectManualEngagedHandCount(UINT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.GetKinectManualEngagedHandCount
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
