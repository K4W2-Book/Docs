IFaceAlignment::get\_Quality Method  
===================================  

顔の位置合わせの品質を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_Quality(  
         FaceAlignmentQuality *quality  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*quality*    
Type: FaceAlignmentQuality  
[out] 顔の位置合わせの品質。  

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
TOCTitle : get_Quality Method
RLTitle : IFaceAlignment::get_Quality Method
KeywordK : get_Quality method
KeywordK : IFaceAlignment::get_Quality method
KeywordF : IFaceAlignment::get_Quality
KeywordF : get_Quality
KeywordF : Microsoft.Kinect.face.IFaceAlignment.get_Quality(FaceAlignmentQuality@)
KeywordA : M:Microsoft.Kinect.face.IFaceAlignment.get_Quality(FaceAlignmentQuality@)
AssetID : M:Microsoft.Kinect.face.IFaceAlignment.get_Quality(FaceAlignmentQuality@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceAlignment::get_Quality
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
