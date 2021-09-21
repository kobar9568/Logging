# Logging

## ビルド (IntelliJ IDEA)

1. Gradleのプロジェクトを読み込む

![Load](https://user-images.githubusercontent.com/38117745/134157377-0944cb52-d52a-4553-be1e-6419ed30b414.png)

2. セキュリティの警告が表示されるので、"Trust Project"をクリックする

![Trust](https://user-images.githubusercontent.com/38117745/134157465-fa9a2a00-c927-46c6-9d73-b40a7f4306ea.png)

3. 依存関係の解決が行われるので、完了するまで待機する

![Dependencies](https://user-images.githubusercontent.com/38117745/134157542-fef5ba31-bf1e-4f8e-940c-199281247142.png)

4. Gradleメニューから"jar"タスクを選択すると、ビルドが行われる

![Build](https://user-images.githubusercontent.com/38117745/134157663-520f12a3-caa7-443d-bb2f-0937afcdf6dd.png)

## ビルド (CLI)

```
$ gradle build
```

- 初回の実行時に依存関係の解決が行われる
- Gradleでのビルドを想定
- 現状Gradle 7系に未対応であり、Gradle 6.9.1を指定している
  - Gradle 6.9.1がJDK15に依存
