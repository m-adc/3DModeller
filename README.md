# 3DModeller
## 概要
端末のカメラを用いて3Dモデルを生成、複製して平面に配置する

## 開発環境
- Xcode(Mac)
- iOS(iPhone/iPad)

## 言語/使用技術
- ARKit
- Swift

## 基本設計
### 機能
- カメラ起動
- ARマーカー読取
  - 座標(center, extent, scale)の設定
- 物体認識 [[ドキュメント](https://developer.apple.com/documentation/arkit/arreferenceobject)]
  - 特徴点の抽出
- 3Dオブジェクトの生成
- 平面認識
- 3Dオブジェクトの配置