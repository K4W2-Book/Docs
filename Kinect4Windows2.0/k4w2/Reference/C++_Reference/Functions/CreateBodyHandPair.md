CreateBodyHandPair  
==================  

人物と手を関係付ける[IBodyHandPair](../Interfaces/IBodyHandPair_Interface.md)を作成する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT CreateBodyHandPair(  
         UINT64 bodyTrackingId,  
         HandType handType,  
         IBodyHandPair **ppBodyHandPair  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*bodyTrackingId*    
Type: UINT64  
トラッキングID。  

*handType*    
Type: HandType  
手の種類。  

*ppBodyHandPair*    
Type: IBodyHandPair  
[out] [IBodyHandPair](../Interfaces/IBodyHandPair_Interface.md)のポインタのアドレス。  

<span id="ID4ER"></span>
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
TOCTitle : CreateBodyHandPair
RLTitle : CreateBodyHandPair
KeywordK : CreateBodyHandPair
KeywordF : CreateBodyHandPair
KeywordF : Microsoft.Kinect.kinect.CreateBodyHandPair(UINT64,HandType,IBodyHandPair@)
KeywordA : M:Microsoft.Kinect.kinect.CreateBodyHandPair(UINT64,HandType,IBodyHandPair@)
AssetID : M:Microsoft.Kinect.kinect.CreateBodyHandPair(UINT64,HandType,IBodyHandPair@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.CreateBodyHandPair
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
