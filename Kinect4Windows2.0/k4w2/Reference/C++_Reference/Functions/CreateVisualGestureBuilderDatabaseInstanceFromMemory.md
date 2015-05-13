CreateVisualGestureBuilderDatabaseInstanceFromMemory  
====================================================  

メモリから[IVisualGestureBuilderDatabase](../Interfaces/IVisualGestureBuilderDatab.md)を作成する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT CreateVisualGestureBuilderFrameSource(  
         UINT capacity,  
         BYTE* buffer,  
         IVisualGestureBuilderDatabase** instance  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EL"></span>
#### Parameters  

*capacity*    
Type: UINT  
[in] ジェスチャーデータベースのサイズ。  

*buffer*    
Type: BYTE  
[in] ジェスチャーデータベースのアドレス。  

*instance*    
Type: IVisualGestureBuilderDatabase  
[out] IVisualGestureBuilderDatabaseのポインタのアドレス。  

<span id="ID4ES"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.visualgesturebuilder.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : CreateVisualGestureBuilderFrameSource
RLTitle : CreateVisualGestureBuilderFrameSource
KeywordK : CreateVisualGestureBuilderFrameSource
KeywordF : CreateVisualGestureBuilderFrameSource
KeywordF : Microsoft.Kinect.visualgesturebuilder.CreateVisualGestureBuilderFrameSource(IKinectSensor,UINT64,IVisualGestureBuilderFrameSource@)
KeywordA : M:Microsoft.Kinect.visualgesturebuilder.CreateVisualGestureBuilderFrameSource(IKinectSensor,UINT64,IVisualGestureBuilderFrameSource@)
AssetID : M:Microsoft.Kinect.visualgesturebuilder.CreateVisualGestureBuilderFrameSource(IKinectSensor,UINT64,IVisualGestureBuilderFrameSource@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.visualgesturebuilder.CreateVisualGestureBuilderFrameSource
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
