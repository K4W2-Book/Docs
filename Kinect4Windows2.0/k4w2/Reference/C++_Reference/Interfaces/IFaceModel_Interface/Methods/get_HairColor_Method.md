IFaceModel::get\_HairColor Method  
=================================  

髪の色を取得する。  
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
HRESULT get_HairColor(  
         UINT32 *hairColor  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*hairColor*    
Type: UINT32  
[out] 髪の色。  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
成功した場合はS\_OKを返します。それ以外の場合はエラーコードを返します。  

<span id="remarks"></span>

Remarks  
=======  

以下のように色の値(0~255)を取り出すことができる。

    UINT32 hairColor;  
    HRESULT hr = faceModel->get_HairColor( &hairColor ) );  
    if( SUCCEEDED( hr ) ){  
        UCHAR blue  = ( hairColor & 0x00ff0000 ) >> 16;  
        UCHAR green = ( hairColor & 0x0000ff00 ) >>  8;  
        UCHAR red   = ( hairColor & 0x000000ff ) >>  0;  
    }  


<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_HairColor Method
RLTitle : IFaceModel::get_HairColor Method
KeywordK : get_HairColor method
KeywordK : IFaceModel::get_HairColor method
KeywordF : IFaceModel::get_HairColor
KeywordF : get_HairColor
KeywordF : Microsoft.Kinect.face.IFaceModel.get_HairColor(UINT32@)
KeywordA : M:Microsoft.Kinect.face.IFaceModel.get_HairColor(UINT32@)
AssetID : M:Microsoft.Kinect.face.IFaceModel.get_HairColor(UINT32@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModel::get_HairColor
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
