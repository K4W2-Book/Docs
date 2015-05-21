GetKinectCoreWindowForCurrentThread  
===================================  

現在のスレッドの[IKinectCoreWindow](../Interfaces/IKinectCoreWindow_Interface.md)を作成する。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>HRESULT GetKinectCoreWindowForCurrentThread(  
         IKinectCoreWindow **ppKinectCoreWindow  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*ppKinectCoreWindow*    
Type: IKinectCoreWindow  
[out] [IKinectCoreWindow](../Interfaces/IKinectCoreWindow_Interface.md)のポインタのアドレス。  

<span id="ID4ER"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : GetKinectCoreWindowForCurrentThread
RLTitle : GetKinectCoreWindowForCurrentThread
KeywordK : GetKinectCoreWindowForCurrentThread
KeywordF : GetKinectCoreWindowForCurrentThread
KeywordF : Microsoft.Kinect.kinect.GetKinectCoreWindowForCurrentThread(IKinectCoreWindow@)
KeywordA : M:Microsoft.Kinect.kinect.GetKinectCoreWindowForCurrentThread(IKinectCoreWindow@)
AssetID : M:Microsoft.Kinect.kinect.GetKinectCoreWindowForCurrentThread(IKinectCoreWindow@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.GetKinectCoreWindowForCurrentThread
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
