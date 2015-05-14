IFaceAlignment::get\_HeadPivotPoint Method  
==========================================  

顔の回転軸の中心座標(Camera座標系)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_HeadPivotPoint(  
         CameraSpacePoint *headPivotPoint  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*headPivotPoint*    
Type: CameraSpacePoint  
[out] 顔の回転軸の中心座標(Camera座標系)。  

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
TOCTitle : get_HeadPivotPoint Method
RLTitle : IFaceAlignment::get_HeadPivotPoint Method
KeywordK : get_HeadPivotPoint method
KeywordK : IFaceAlignment::get_HeadPivotPoint method
KeywordF : IFaceAlignment::get_HeadPivotPoint
KeywordF : get_HeadPivotPoint
KeywordF : Microsoft.Kinect.face.IFaceAlignment.get_HeadPivotPoint(CameraSpacePoint@)
KeywordA : M:Microsoft.Kinect.face.IFaceAlignment.get_HeadPivotPoint(CameraSpacePoint@)
AssetID : M:Microsoft.Kinect.face.IFaceAlignment.get_HeadPivotPoint(CameraSpacePoint@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceAlignment::get_HeadPivotPoint
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
