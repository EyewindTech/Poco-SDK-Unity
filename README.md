# Unity3D Integration Guide
PocoSDK supports Unity3D version 2019.4 and above, ngui & ugui & fairygui, C# only for now. 

1. 修改 Unity 工程 `Packages/manifest.json` ，将依赖添加到 `dependencies`
```json
"com.netease.airtest.poco.unity": "https://github.com/EyewindTech/Poco-SDK-Unity.git#ew-unity-ugui-tmp"
```
2. 添加 `Unity3D/PocoManager.cs` 组件到一个活动对象，一般附加在主相机之上。