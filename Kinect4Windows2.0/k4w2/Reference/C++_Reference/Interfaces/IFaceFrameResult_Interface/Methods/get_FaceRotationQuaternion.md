IFaceFrameResult::get\_FaceRotationQuaternion Method  
====================================================  

顔の回転方向(クォータニオン)を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FaceRotationQuaternion(  
         Vector4 *rotationQuaternion  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*rotationQuaternion*    
Type: Vector4  
[out] 顔の回転方向(クォータニオン)  

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
TOCTitle : get_FaceRotationQuaternion Method
RLTitle : IFaceFrameResult::get_FaceRotationQuaternion Method
KeywordK : get_FaceRotationQuaternion method
KeywordK : IFaceFrameResult::get_FaceRotationQuaternion method
KeywordF : IFaceFrameResult::get_FaceRotationQuaternion
KeywordF : get_FaceRotationQuaternion
KeywordF : Microsoft.Kinect.face.IFaceFrameResult.get_FaceRotationQuaternion(Vector4@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameResult.get_FaceRotationQuaternion(Vector4@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameResult.get_FaceRotationQuaternion(Vector4@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameResult::get_FaceRotationQuaternion
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
