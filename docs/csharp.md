# C&#x23;

* [Microsoft Learn: キャリアの扉を開くスキルを身につける](https://learn.microsoft.com/ja-jp/)
* [.NET のドキュメント | Microsoft Learn](https://learn.microsoft.com/ja-jp/dotnet/)
* [C# 言語リファレンス | Microsoft Learn](https://learn.microsoft.com/ja-jp/dotnet/csharp/language-reference/)
* [C# 関連のドキュメント - 概要、チュートリアル、リファレンス｡ | Microsoft Learn](https://learn.microsoft.com/ja-jp/dotnet/csharp/tour-of-csharp/)
* [概要 - A tour of C# | Microsoft Learn](https://learn.microsoft.com/ja-jp/dotnet/csharp/tour-of-csharp/overview)

## 言語標準

* [.NET の Ecma 標準 - .NET | Microsoft Learn](https://learn.microsoft.com/ja-jp/dotnet/fundamentals/standards)

> C# 言語および共通言語基盤 (CLI) の仕様は､ Ecma International® を介して標準化されています｡ これらの標準の初版は､ 2001 年 12 月に Ecma によって公開されました｡

* [ECMA-334 - Ecma International](https://ecma-international.org/publications-and-standards/standards/ecma-334/)

> **This specification describes the form and establishes the interpretation of programs written in the C# programming language.**

## ターゲットフレームワークと既定の言語バージョン

* [言語のバージョン管理 - C# reference | Microsoft Learn](https://learn.microsoft.com/ja-jp/dotnet/csharp/language-reference/language-versioning)

> | ターゲット      | バージョン    | 既定の言語バージョン
> | --------------- | ------------- | ----
> | .NET            | 9.x           | C# 13
> | .NET            | 8.x           | C# 12
> | .NET            | 7.x           | C# 11
> | .NET            | 6.x           | C# 10
> | .NET            | 5.x           | C# 9.0
> | .NET Core       | 3.x           | C# 8.0
> | .NET Core       | 2.x           | C# 7.3
> | .NET Standard   | 2.1           | C# 8.0
> | .NET Standard   | 2.0           | C# 7.3
> | .NET Standard   | 1.x           | C# 7.3
> | .NET Framework  | すべて        | C# 7.3

# ユーザ定義の checked 演算子

* [C# 11 の新機能 - C# ガイド - C# | Microsoft Learn](https://learn.microsoft.com/ja-jp/dotnet/csharp/whats-new/csharp-11#generic-math-support)

> ## ジェネリック型数値演算のサポート
>
> ... 開発者は `checked` および `unchecked` 算術演算子を定義できるようになりました｡ コンパイラにより､ 現在のコンテキストに基づいて正しいバリアントの呼び出しが生成されます｡ `checked` 演算子の詳細については､ [算術演算子](https://learn.microsoft.com/ja-jp/dotnet/csharp/language-reference/operators/arithmetic-operators) に関する記事を参照してください｡

* [算術演算子 - C# reference | Microsoft Learn](https://learn.microsoft.com/ja-jp/dotnet/csharp/language-reference/operators/arithmetic-operators#user-defined-checked-operators)

> C# 11 以降では､ 算術演算子をオーバーロードするとき､ `checked` キーワードを使用してその演算子の _checked_ バージョンを定義できます｡
