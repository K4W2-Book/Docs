IFaceFrameSource::get\_FaceFrameFeatures Method  
===============================================  

Gets the flags that indicate which face frame features data are present in this face frame. <span id="syntaxSection"></span>

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
HRESULT get_FaceFrameFeatures(  
         DWORD *faceFrameFeatures  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*faceFrameFeatures*    
Type: DWORD  
[out] The flags that indicate which face frame features data are present in this face frame.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_FaceFrameFeatures Method
RLTitle : IFaceFrameSource::get_FaceFrameFeatures Method
KeywordK : get_FaceFrameFeatures method
KeywordK : IFaceFrameSource::get_FaceFrameFeatures method
KeywordF : IFaceFrameSource::get_FaceFrameFeatures
KeywordF : get_FaceFrameFeatures
KeywordF : Microsoft.Kinect.face.IFaceFrameSource.get_FaceFrameFeatures(DWORD@)
KeywordA : M:Microsoft.Kinect.face.IFaceFrameSource.get_FaceFrameFeatures(DWORD@)
AssetID : M:Microsoft.Kinect.face.IFaceFrameSource.get_FaceFrameFeatures(DWORD@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceFrameSource::get_FaceFrameFeatures
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
