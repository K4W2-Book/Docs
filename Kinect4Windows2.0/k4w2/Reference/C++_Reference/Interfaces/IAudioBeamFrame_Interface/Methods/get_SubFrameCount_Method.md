IAudioBeamFrame::get\_SubFrameCount Method  
==========================================  

AudioBeamサブフレームの数を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_SubFrameCount(  
         UINT32 *pSubFrameCount  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*pSubFrameCount*    
Type: UINT32  
[out] AudioBeamサブフレームの数。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

この値は[1, 8]の範囲です。(最大値8は[get\_MaxSubFrameCount](../../IAudioSource_Interface/Methods/get_MaxSubFrameCount_Method.md)で取得した値です。)  
通常フレームは1~3のサブフレームを持ちます。  
この数はフレームによって異なります。  
計算リソースが限られている場合、Kinect Serviceはより多くのサブフレームを生成します。(遅延が発生します。)  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_SubFrameCount Method
RLTitle : IAudioBeamFrame::get_SubFrameCount Method
KeywordK : get_SubFrameCount method
KeywordK : IAudioBeamFrame::get_SubFrameCount method
KeywordF : IAudioBeamFrame::get_SubFrameCount
KeywordF : get_SubFrameCount
KeywordF : Microsoft.Kinect.kinect.IAudioBeamFrame.get_SubFrameCount(UINT32@)
KeywordA : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_SubFrameCount(UINT32@)
AssetID : M:Microsoft.Kinect.kinect.IAudioBeamFrame.get_SubFrameCount(UINT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IAudioBeamFrame::get_SubFrameCount
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
