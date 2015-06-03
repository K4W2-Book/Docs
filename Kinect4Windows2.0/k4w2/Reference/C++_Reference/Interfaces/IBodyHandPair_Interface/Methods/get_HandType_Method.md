IBodyHandPair::get\_HandType Method  
===================================  

手の種類(右手・左手)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_HandType(  
         HandType *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: HandType  
[out] 手の種類(右手・左手)。  

<span id="ID4EP"></span>
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
TOCTitle : get_HandType Method
RLTitle : IBodyHandPair::get_HandType Method
KeywordK : get_HandType method
KeywordK : IBodyHandPair::get_HandType method
KeywordF : IBodyHandPair::get_HandType
KeywordF : get_HandType
KeywordF : Microsoft.Kinect.kinect.IBodyHandPair.get_HandType(HandType@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyHandPair.get_HandType(HandType@)
AssetID : M:Microsoft.Kinect.kinect.IBodyHandPair.get_HandType(HandType@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyHandPair::get_HandType
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
