IFaceAlignment::put\_HeadPivotPoint Method  
==========================================  

顔の回転軸の中心座標(Camera座標系)を設定する。 <span id="syntaxSection"></span>

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
HRESULT put_HeadPivotPoint(  
         CameraSpacePoint headPivotPoint  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*headPivotPoint*    
Type: CameraSpacePoint  
顔の回転軸の中心座標(Camera座標系)。  

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
TOCTitle : put_HeadPivotPoint Method
RLTitle : IFaceAlignment::put_HeadPivotPoint Method
KeywordK : put_HeadPivotPoint method
KeywordK : IFaceAlignment::put_HeadPivotPoint method
KeywordF : IFaceAlignment::put_HeadPivotPoint
KeywordF : put_HeadPivotPoint
KeywordF : Microsoft.Kinect.face.IFaceAlignment.put_HeadPivotPoint(CameraSpacePoint)
KeywordA : M:Microsoft.Kinect.face.IFaceAlignment.put_HeadPivotPoint(CameraSpacePoint)
AssetID : M:Microsoft.Kinect.face.IFaceAlignment.put_HeadPivotPoint(CameraSpacePoint)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceAlignment::put_HeadPivotPoint
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
