# VrmViewerForQuest
**※Oculus Questの実機が届いていないため、Oculus GOでしか動作確認を行っていません。**

Oculus Quest(及びGo)向けのVRMビューワーサンプルです。

・DonwloadフォルダにあるVRMを読み込みし、一覧表示可能<br>
　PCからファイル転送、Oculusブラウザからダウンロードしたものなどを利用できます。

・DonwloadフォルダにあるVRMにお帰り頂くことが可能<br>
　Oculus標準アプリにダウンロードフォルダのVRMを操作する機能がないためアプリ内に用意しています。

・選択したVRMの表示<br>
　VRMの表示を行います。負荷の関係上、表示は1人、VRMの裏待機（キャッシュ）数は3人としています。ポーズ変更や表情変更機能はまだついていません。

# 実行ファイル(.apk)
[VrmViewerForOculusGo_v0_1_0.apk](https://drive.google.com/file/d/1yEGjO7CK7rAQLlg7wjeF9Bg9_lhtbxM-/view?usp=sharing)

Oculus Quest用はまだありません。

# 動作環境
Unity 2018.4.0f1 にて確認

# 使い方
プロジェクトを開いたらエラーが大量に表示されるため、下記の作業を行ってください。

## プラットフォームの設定
OculusQuest及びOculusGoを対象としているため、<br>
対象のプラットフォームをAndroidに切り替えてください。

## UniVRMのインポート
UniVRM v0.51.0を利用しています。<br>
下記のリリースページから「UniVRM-0.51.0_1b36.unitypackage」をダウンロードしてインポートしてください。<br>
https://github.com/vrm-c/UniVRM/releases

## Oculus Integrationのインポート
Oculus Integration　v1.36を利用しています。<br>
Unity Asset StoreからOculus Integrationをインポートしてください。<br>
https://assetstore.unity.com/packages/tools/integration/oculus-integration-82022

下記の2つのフォルダは最低限インポートしてください。<br>
（他のフォルダもインポートして問題ないですが、ビルド時間に大きく影響します。）<br>
　Oculus\Spatializer <br>
　Oculus\VR <br>

# ライセンスについて
MITライセンスにてご利用ください。
