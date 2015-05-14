IFaceAlignment::put\_FaceOrientation Method  
===========================================  

顔の回転方向(クォータニオン)を設定する。 <span id="syntaxSection"></span>

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
HRESULT put_FaceOrientation(  
         Vector4 faceOrientation  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceOrientation*    
Type: Vector4  
顔の回転方向(クォータニオン)。  

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
TOCTitle : put_FaceOrientation Method
RLTitle : IFaceAlignment::put_FaceOrientation Method
KeywordK : put_FaceOrientation method
KeywordK : IFaceAlignment::put_FaceOrientation method
KeywordF : IFaceAlignment::put_FaceOrientation
KeywordF : put_FaceOrientation
KeywordF : Microsoft.Kinect.face.IFaceAlignment.put_FaceOrientation(Vector4)
KeywordA : M:Microsoft.Kinect.face.IFaceAlignment.put_FaceOrientation(Vector4)
AssetID : M:Microsoft.Kinect.face.IFaceAlignment.put_FaceOrientation(Vector4)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceAlignment::put_FaceOrientation
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
