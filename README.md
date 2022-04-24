# PrefabInstanceOverrideScanner
Unityで、全シーンの全プレハブインスタンス（Hierarchy上のプレハブ）からオーバーライドを検出するエディタ拡張です。  
作成時のバージョン：Unity 2020.3.5f1

## 使い方
1. 当リポジトリをダウンロードし、PrefabInstanceOverrideScanner-mainフォルダをAssetsフォルダに配置します。
2. 上部メニューのToolsからPrefab Instance Override Scanをクリックすると、スキャンが開始します。
![image](https://user-images.githubusercontent.com/20467560/164953672-bf3220d8-d8c9-41a7-a119-6b2fffd7ff8a.png)

3. スキャンが終了すると、結果がConsoleに表示されます。
![image](https://user-images.githubusercontent.com/20467560/164953614-c10ee960-e6c8-453d-bcde-2e9091ebb269.png)

## 使用したコード
kan.kikuchiさんの[複数のSceneを順に読み込み、各Sceneの全GameObjectを取得する【Unity】【エディタ拡張】](https://kan-kikuchi.hatenablog.com/entry/GameObjectGetterOfAllScenes)のエディタ拡張を  
一部修正して（66行目にスキャン終了を伝えるログ出力を追加）、使用させていただいております。  
この場を借りてお礼申し上げます。


