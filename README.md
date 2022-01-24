# MobileHotspot
Windows 起動時にモバイルホットスポットを On にするための powershell スクリプトです。

# 前提
* Windows10
* PSVersion 5.1.19041.1320

# 使い方
1. c:\somewhere\hotspot.ps1 に置きます。（どこにおいても大丈夫です。フォルダはサンプルです。）
2. windows + r でファイル名を指定して実行を起動
3. shell:Startup を実行
4. hotspot.bat を作成して、中に `powershell c:\somewhere\hotspot.ps1` を記載して保存します。

# 参考
* [Enable Windows 10 built-in hotspot by cmd/batch/powershell](https://stackoverflow.com/questions/45833873/enable-windows-10-built-in-hotspot-by-cmd-batch-powershell)
* [https://superuser.com/questions/1341997/using-a-uwp-api-namespace-in-powershell/1342416#1342416](https://superuser.com/questions/1341997/using-a-uwp-api-namespace-in-powershell/1342416#1342416)
* [PowerShellで「スクリプトの実行が無効になっています」と出てしまいます。](https://cloudsteady.jp/post/28760/)
