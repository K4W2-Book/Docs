IFaceModelBuilder Interface  
===========================  

FaceModelBuilder。 <span id="syntaxSection"></span>

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
<td align="left"><pre><code>interface IFaceModelBuilder : public IUnknown</code></pre></td>
</tr>
</tbody>
</table>

<span id="classMembersSection"></span>

Members  
=======  

**IFaceModelBuilder**は以下のメンバー関数を持ちます。  

<span id="publicmethodsSection"></span>

Methods  
=======  

<table>
<colgroup>
<col width="30%" />
<col width="60%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Name</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/BeginFaceDataCollection.md">BeginFaceDataCollection</a></td>
<td align="left">顔モデルのフィッティングに必要な顔形状データの収集を開始する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/CollectFaceDataAsync_Method.md">CollectFaceDataAsync</a></td>
<td align="left">非同期で顔形状データを収集する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/get_CaptureStatus_Method.md">get_CaptureStatus</a></td>
<td align="left">キャプチャステータスを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/get_CollectionStatus_Method.md">get_CollectionStatus</a></td>
<td align="left">データ収集ステータスを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/GetCaptureStatusChangedEve.md">GetCaptureStatusChangedEventData</a></td>
<td align="left">キャプチャステータスが変更されたとき、イベントデータを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/GetCollectionStatusChanged.md">GetCollectionStatusChangedEventData</a></td>
<td align="left">データ収集ステータスが変更されたとき、イベントデータを取得する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/GetFaceData_Method.md">GetFaceData</a></td>
<td align="left">収集した顔形状データを取得する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/SubscribeCaptureStatusChan.md">SubscribeCaptureStatusChanged</a></td>
<td align="left">キャプチャステータスが変更されたとき発効するイベントハンドルを登録する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/SubscribeCollectionStatusC.md">SubscribeCollectionStatusChanged</a></td>
<td align="left">データ収集ステータスが変更されたとき発効するイベントハンドルを登録する。</td>
</tr>
<tr class="even">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/UnsubscribeCaptureStatusCh.md">UnsubscribeCaptureStatusChanged</a></td>
<td align="left">キャプチャステータスが変更されたとき発効するイベントハンドルを解除する。</td>
</tr>
<tr class="odd">
<td align="left"><a href="IFaceModelBuilder_Interface/Methods/UnsubscribeCollectionStatu.md">UnsubscribeCollectionStatusChanged</a></td>
<td align="left">データ収集ステータスが変更されたとき発効するイベントハンドルを解除する。</td>
</tr>
</tbody>
</table>

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.face.h  
**Library:** Kinect20.face.lib  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : IFaceModelBuilder Interface
RLTitle : IFaceModelBuilder Interface
KeywordK : IFaceModelBuilder interface, about
HelpPriority : 2
TopicType : apiref
KeywordF : IFaceModelBuilder
KeywordF : Microsoft.Kinect.face.IFaceModelBuilder
KeywordA : T:Microsoft.Kinect.face.IFaceModelBuilder
AssetID : T:Microsoft.Kinect.face.IFaceModelBuilder
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.face.IFaceModelBuilder
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
