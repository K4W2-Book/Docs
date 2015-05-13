CreateFaceFrameSource  
=====================  

IFaceFrameSourceを作成します。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT CreateFaceFrameSource(  
         IKinectSensor *sensor,  
         const UINT64 initialTrackingId,  
         const DWORD initialFaceFrameFeatures,  
         IFaceFrameSource **ppSource  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*sensor*    
Type: IKinectSensor  
[in] IFaceFrameSourceを作成するセンサー。  

*initialTrackingId*    
Type: UINT64  
[in] トラッキングID。(0)  

*initialFaceFrameFeatures*    
Type: DWORD  
[in] 有効にするFaceの機能。  
複数の機能を有効にするには論理和(|)で繋げて指定する。

*ppSource*    
Type: IFaceFrameSource  
[out] IFaceFrameSourceへのポインタのポインタ。  

<span id="ID4EN"></span>
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
TOCTitle : CreateFaceFrameSource
RLTitle : CreateFaceFrameSource
KeywordK : CreateFaceFrameSource
KeywordF : CreateFaceFrameSource
KeywordF : Microsoft.Kinect.face.CreateFaceFrameSource(IKinectSensor,UINT64,DWORD,IFaceFrameSource@)
KeywordA : M:Microsoft.Kinect.face.CreateFaceFrameSource(IKinectSensor,UINT64,DWORD,IFaceFrameSource@)
AssetID : M:Microsoft.Kinect.face.CreateFaceFrameSource(IKinectSensor,UINT64,DWORD,IFaceFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.CreateFaceFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
