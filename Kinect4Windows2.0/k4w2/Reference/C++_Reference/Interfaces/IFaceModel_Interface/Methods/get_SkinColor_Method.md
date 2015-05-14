IFaceModel::get\_SkinColor Method  
=================================  

肌の色を取得する。  
無効(X)、青(B)、緑(G)、赤(R)の順に上から各8bitずつ色が格納される。  
有効な値はFaceModelBuilderでフィッティングされたあとに取得できる。 <span id="syntaxSection"></span>

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
HRESULT get_SkinColor(  
         UINT32 *skinColor  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*skinColor*    
Type: UINT32  
[out] 肌の色。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

以下のように色の値(0~255)を取り出すことができる。

<table>
<td align="left"><pre><code>UINT32 skinColor;  
HRESULT hr = faceModel->get_SkinColor( &skinColor ) );  
if( SUCCEEDED( hr ) ){  
    UCHAR blue  = ( skinColor & 0x00ff0000 ) >> 16;  
    UCHAR green = ( skinColor & 0x0000ff00 ) >>  8;  
    UCHAR red   = ( skinColor & 0x000000ff ) >>  0;  
}  
</code></pre>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_SkinColor Method
RLTitle : IFaceModel::get_SkinColor Method
KeywordK : get_SkinColor method
KeywordK : IFaceModel::get_SkinColor method
KeywordF : IFaceModel::get_SkinColor
KeywordF : get_SkinColor
KeywordF : Microsoft.Kinect.face.IFaceModel.get_SkinColor(UINT32@)
KeywordA : M:Microsoft.Kinect.face.IFaceModel.get_SkinColor(UINT32@)
AssetID : M:Microsoft.Kinect.face.IFaceModel.get_SkinColor(UINT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModel::get_SkinColor
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
