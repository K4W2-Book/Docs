ColorImageFormat Enumeration  
============================  

Color画像のフォーマットの種類。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>typedef enum _ColorImageFormat  
{  
    ColorImageFormat_None = 0,  
    ColorImageFormat_Rgba = 1,  
    ColorImageFormat_Yuv = 2,  
    ColorImageFormat_Bgra = 3,  
    ColorImageFormat_Bayer = 4,  
    ColorImageFormat_Yuy2 = 5  
} ColorImageFormat, ColorImageFormat_None, ColorImageFormat_Rgba, ColorImageFormat_Yuv, ColorImageFormat_Bgra, ColorImageFormat_Bayer, ColorImageFormat_Yuy2;</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4ELB"></span>

Constants  
=========  

| Constant                | Description           |
|-------------------------|-----------------------|
| ColorImageFormat\_None  | 未指定。 |
| ColorImageFormat\_Rgba  | RGBAフォーマット<br/>R(赤)、G(緑)、B(青)、A(透過)           |
| ColorImageFormat\_Yuv   | YUVフォーマット<br/>U(B−Yの色差)、Y(輝度)、V(R−Yの色差)、Y(輝度)            |
| ColorImageFormat\_Bgra  | BGRAフォーマット<br/>B(青)、G(緑)、R(赤)、A(透過)           |
| ColorImageFormat\_Bayer | ベイヤーパターン<br/>2行目の2，3番目の成分はG(緑)、B(青)          |
| ColorImageFormat\_Yuy2  | YUY2フォーマット<br/>Y(輝度)、U(B−Yの色差)、Y(輝度)、V(R−Yの色差)           |

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** kinect20.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : ColorImageFormat Enumeration
RLTitle : ColorImageFormat Enumeration
KeywordK : ColorImageFormat enumeration
HelpPriority : 2
KeywordF : ColorImageFormat
KeywordF : Microsoft.Kinect.kinect.ColorImageFormat
KeywordA : T:Microsoft.Kinect.kinect.ColorImageFormat
AssetID : T:Microsoft.Kinect.kinect.ColorImageFormat
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.ColorImageFormat
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
