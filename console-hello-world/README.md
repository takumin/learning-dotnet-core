# .Net Core 3.1 Console Hello World

# プロジェクトを作成する時

```sh
 $ dotnet new console
The template "Console Application" was created successfully.

Processing post-creation actions...
Running 'dotnet restore' on ~/learning-dotnet-core/console-hello-world/console-hello-world.csproj...
  復元対象のプロジェクトを決定しています...
  ~/learning-dotnet-core/console-hello-world/console-hello-world.csproj を復元しました (200 ms)。

Restore succeeded.
```

# プロジェクトをビルドする時

```sh
 $ dotnet build
.NET Core 向け Microsoft (R) Build Engine バージョン 16.6.0+5ff7b0c9e
Copyright (C) Microsoft Corporation.All rights reserved.

  復元対象のプロジェクトを決定しています...
  復元対象のすべてのプロジェクトは最新です。
  console-hello-world -> ~/learning-dotnet-core/console-hello-world/bin/Debug/netcoreapp3.1/console-hello-world.dll

ビルドに成功しました。
    0 個の警告
    0 エラー

経過時間 00:00:01.67
```

# テスト実行

```sh
 $ ./bin/Debug/netcoreapp3.1/console-hello-world
Hello World!
```
