# android_startup
Androidアプリ開発の準備（AndroidStudio）

## AndroidStudioって何?
Androidアプリ開発に最適化した統合開発環境(IDE)。  
統合開発環境っていうのは、Eclipseとかその部類。

## インストール
1. [公式サイト](http://developer.android.com/sdk/index.html)からAndroidStudioをダウンロード
2. 促されるままに進めていく
3. **Setup Wizard - Downloading Component** という画面が表示されたら、Finishをクリックしてインストール完了

## 起動して新規プロジェクトを作成する
1. AndroidStudioを起動 
2. **Start a new Android Studio Project** を選択
3. プロジェクトの設定（詳細は[こちらの記事](http://techacademy.jp/magazine/5238#sec3-1)を参照）  

**※プロジェクト作成の過程でJDKのエラーが発生した場合**

![JDK Error](https://github.com/mokumoku-idv/android_startup/blob/master/jdk_err.png)

* JDKのバージョンが低いのが原因らしいので、警告通りにJDK7を入れる  
[Oracle JDK7 Download Page](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html)  
* インストールが完了したら、AndroidStudioからJDK7の場所を指定する  
File > Project Structure > JDK location
```
/Library/Java/JavaVirtualMachines/jdk1.7.0_75.jdk/Contents/Home
```
