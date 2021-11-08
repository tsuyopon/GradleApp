# 概要
Gradleを使ったサンプルレポジトリです。

# 詳細
以下のコマンドにより生成したサンプルプロジェクトです
```
$ gradle init --type java-application
```

初回レポジトリ取得時はGradle Wrapperスクリプトからインストールを行います。
```
$ gradlew -v
```

アプリのビルドと実行を手動で実施する場合には以下のようにbuildとrunを実行すればよい。
```
[~/GraddleApp]$ ./gradlew build

BUILD SUCCESSFUL in 2s
7 actionable tasks: 7 executed
[~/GraddleApp]$ ./gradlew run


> Task :app:run
Hello World2!

BUILD SUCCESSFUL in 780ms
2 actionable tasks: 1 executed, 1 up-to-date
```
