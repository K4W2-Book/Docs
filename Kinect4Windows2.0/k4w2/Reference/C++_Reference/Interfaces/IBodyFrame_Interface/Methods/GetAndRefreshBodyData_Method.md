IBodyFrame::GetAndRefreshBodyData Method  
========================================  

最新のBodyデータを更新、取得する。 <span id="syntaxSection"></span>

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
HRESULT GetAndRefreshBodyData(  
         UINT capacity,  
         IBody **bodies  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*capacity*    
Type: UINT  
Bodyの配列のサイズ。(6)  

*bodies*    
Type: IBody  
[in, out] [IBody](../../IBody_Interface.md)の配列の先頭アドレス。  

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
TOCTitle : GetAndRefreshBodyData Method
RLTitle : IBodyFrame::GetAndRefreshBodyData Method
KeywordK : GetAndRefreshBodyData method
KeywordK : IBodyFrame::GetAndRefreshBodyData method
KeywordF : IBodyFrame::GetAndRefreshBodyData
KeywordF : GetAndRefreshBodyData
KeywordF : Microsoft.Kinect.kinect.IBodyFrame.GetAndRefreshBodyData(UINT,IBody@)
KeywordA : M:Microsoft.Kinect.kinect.IBodyFrame.GetAndRefreshBodyData(UINT,IBody@)
AssetID : M:Microsoft.Kinect.kinect.IBodyFrame.GetAndRefreshBodyData(UINT,IBody@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IBodyFrame::GetAndRefreshBodyData
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
