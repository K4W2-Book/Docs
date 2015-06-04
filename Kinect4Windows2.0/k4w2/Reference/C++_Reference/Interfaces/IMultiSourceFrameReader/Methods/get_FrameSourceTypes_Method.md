IMultiSourceFrameReader::get\_FrameSourceTypes Method  
=====================================================  

フレームの種類を取得する。 <span id="syntaxSection"></span>

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
HRESULT get_FrameSourceTypes(  
         DWORD *enabledFrameSourceTypes  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*enabledFrameSourceTypes*    
Type: DWORD  
[out] フレームの種類。([FrameSourceTypes](../../../Enumerations/FrameSourceTypes_Enumeration.md))  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_FrameSourceTypes Method
RLTitle : IMultiSourceFrameReader::get_FrameSourceTypes Method
KeywordK : get_FrameSourceTypes method
KeywordK : IMultiSourceFrameReader::get_FrameSourceTypes method
KeywordF : IMultiSourceFrameReader::get_FrameSourceTypes
KeywordF : get_FrameSourceTypes
KeywordF : Microsoft.Kinect.kinect.IMultiSourceFrameReader.get_FrameSourceTypes(DWORD@)
KeywordA : M:Microsoft.Kinect.kinect.IMultiSourceFrameReader.get_FrameSourceTypes(DWORD@)
AssetID : M:Microsoft.Kinect.kinect.IMultiSourceFrameReader.get_FrameSourceTypes(DWORD@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IMultiSourceFrameReader::get_FrameSourceTypes
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
