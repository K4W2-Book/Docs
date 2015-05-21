Functions  
=========  

<span id="ID4EM"></span>

Kinect Functions  
================  

[CreateBodyHandPair](Functions/CreateBodyHandPair.md)    
人物と手を関係付ける[IBodyHandPair](Interfaces/IBodyHandPair_Interface.md)を作成する。  

[CreateKinectGestureRecognizer](Functions/CreateKinectGestureRecogni.md)    
[IKinectGestureRecognizer](Interfaces/IKinectGestureRecognizer.md)を作成する。  

[GetDefaultKinectSensor](Functions/GetDefaultKinectSensor.md)    
デフォルトの[IKinectSensor](Interfaces/IKinectSensor_Interface.md)を作成する。  

[GetKinectCoreWindowForCurrentThread](Functions/GetKinectCoreWindowForCurr.md)    
現在のスレッドの[IKinectCoreWindow](Interfaces/IKinectCoreWindow_Interface.md)を作成する。  

[GetKinectEngagementMode](Functions/GetKinectEngagementMode.md)    
現在の人物と手を関係付けてトラッキングするモードを取得する。  

[GetKinectManualEngagedHand](Functions/GetKinectManualEngagedHand.md)    
手動で人物と手を関係付けた[IBodyHandPair](Interfaces/IBodyHandPair_Interface.md)を取得する。  

[GetKinectManualEngagedHandCount](Functions/GetKinectManualEngagedHandCount.md)    
手動で人物と手を関係付けている[IBodyHandPair](Interfaces/IBodyHandPair_Interface.md)の数を取得する。  

[GetMaximumKinectEngagedPersonCount](Functions/GetMaximumKinectEngagedPer.md)    
[IBodyHandPair](Interfaces/IBodyHandPair_Interface.md)の最大人数。  

[OverrideKinectInteractionMode](Functions/OverrideKinectInteractionM.md)    
インタラクションモードを上書き設定する。  

[SetKinectOnePersonManualEngagement](Functions/SetKinectOnePersonManualEn.md)    
手動で指定してトラッキングする1人の[IBodyHandPair](Interfaces/IBodyHandPair_Interface.md)を設定する。  

[SetKinectOnePersonSystemEngagement](Functions/SetKinectOnePersonSystemEn.md)    
システムが動的に任意の1人を検出してトラッキングするモードに設定する。  

[SetKinectTwoPersonManualEngagement](Functions/SetKinectTwoPersonManualEn.md)    
手動で指定してトラッキングする2人の[IBodyHandPair](Interfaces/IBodyHandPair_Interface.md)を設定する。  

[SetKinectTwoPersonSystemEngagement](Functions/SetKinectTwoPersonSystemEn.md)    
システムが動的に任意の2人を検出してトラッキングするモードに設定する。  

<span id="ID4EYB"></span>

Face Functions  
==============  

[CreateFaceAlignment](Functions/CreateFaceAlignment.md)    
[IFaceAlignment](Interfaces/IFaceAlignment_Interface.md)を作成する。  

[CreateFaceFrameSource](Functions/CreateFaceFrameSource.md)    
[IFaceFrameSource](Interfaces/IFaceFrameSource_Interface.md)を作成します。  

[CreateFaceModel](Functions/CreateFaceModel.md)    
[IFaceModel](Interfaces/IFaceModel_Interface.md)を作成する。  

[CreateHighDefinitionFaceFrameSource](Functions/CreateHighDefinitionFaceFr.md)    
[IHighDefinitionFaceFrameSource](Interfaces/IHighDefinitionFaceFrameSo.md)を作成する。  

[GetFaceModelTriangleCount](Functions/GetFaceModelTriangleCount.md)    
顔モデルの三角形の数を取得する。  

[GetFaceModelTriangles](Functions/GetFaceModelTriangles.md)    
顔モデルの三角形を取得する。  

[GetFaceModelVertexCount](Functions/GetFaceModelVertexCount.md)    
顔モデルの頂点の数を取得する。  

<span id="ID4EUC"></span>

Fusion Functions  
================  

[NuiFusionAlignPointClouds](Functions/NuiFusionAlignPointClouds.md)    
Point Cloudデータを位置合わせして相対的なカメラ姿勢を計算する。  

[NuiFusionCreateCameraPoseFinder](Functions/NuiFusionCreateCameraPoseF.md)    
[INuiFusionCameraPoseFinder](Interfaces/INuiFusionCameraPoseFinder.md)を作成する。  

[NuiFusionCreateColorReconstruction](Functions/NuiFusionCreateColorRecons.md)    
[INuiFusionColorReconstruction](Interfaces/INuiFusionColorReconstruct.md)を作成する。  

[NuiFusionCreateImageFrame](Functions/NuiFusionCreateImageFrame.md)    
[NUI_FUSION_IMAGE_FRAME](Structures/NUI_FUSION_IMAGE_FRAME.md)を作成する。  

[NuiFusionCreateReconstruction](Functions/NuiFusionCreateReconstruct.md)    
[INuiFusionReconstruction](Interfaces/INuiFusionReconstruction.md)を作成する。  

[NuiFusionDepthFloatFrameToPointCloud](Functions/NuiFusionDepthFloatFrameTo.md)    
DepthデータをPoint Cloudデータに変換する。  

[NuiFusionDepthToDepthFloatFrame](Functions/NuiFusionDepthToDepthFloat.md)    
Depthデータを[NUI_FUSION_IMAGE_FRAME](Structures/NUI_FUSION_IMAGE_FRAME.md)に変換する。  

[NuiFusionGetDeviceInfo](Functions/NuiFusionGetDeviceInfo.md)    
Kinect Fusionの3次元形状の再構成処理に使用するプロセッサーの情報を取得する。  

[NuiFusionShadePointCloud](Functions/NuiFusionShadePointCloud.md)    
Point Cloudデータにシェーディングしてレンダリングされた画像を取得する。  

[NuiFusionReleaseImageFrame](Functions/NuiFusionReleaseImageFrame.md)    
[NUI_FUSION_IMAGE_FRAME](Structures/NUI_FUSION_IMAGE_FRAME.md)に確保したメモリを解放する。  

<span id="ID4EXD"></span>

Visual Gesture Builder Functions  
================================  

[CreateVisualGestureBuilderDatabaseInstanceFromMemory](Functions/CreateVisualGestureBuilderDatabaseInstanceFromMemory.md)    
メモリから[IVisualGestureBuilderDatabase](Interfaces/IVisualGestureBuilderDatab.md)を作成する。  

[CreateVisualGestureBuilderDatabaseInstanceFromFile](Functions/CreateVisualGestureBuilderDatabaseInstanceFromFile.md)    
ファイルから[IVisualGestureBuilderDatabase](Interfaces/IVisualGestureBuilderDatab.md)を作成する。  

[CreateVisualGestureBuilderFrameSource](Functions/CreateVisualGestureBuilder.md)    
[IVisualGestureBuilderFrameSource](Interfaces/IVisualGestureBuilderFrameSource.md)を作成する。  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : Functions
RLTitle : Functions
KeywordA : O:Microsoft.Kinect.kinect.k4w_ref_functions
KeywordA : 91a9c287-d1c4-72d0-5419-fcde8ca20bf1
KeywordK : Functions
AssetID : 91a9c287-d1c4-72d0-5419-fcde8ca20bf1
Locale : en-us
CommunityContent : 1
TopicType : kbOrient
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->
