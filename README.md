# compilemql4 README

MT4のmql4ファイル, mqhファイル, ついでのmql5ファイルをVSCodeでコンパイルするための拡張機能。

## Requirements

この拡張機能を使用するには、MetaEditorがインストールされている必要があります。
metaeditor.exe (MT5の場合はmetaeditor64.exe) がインストールされたPCでご利用下さい。
metaeditor.exeはMT4をインストールした際に一緒にインストールされています。

## Extension Settings

ファイルを保存したときに自動でコンパイルを行うには、Compile After Saveにチェックを入れて下さい。

使用前に拡張機能の設定からMetaeditor Dirにmetaeditor.exeのパスを入力して下さい。※必須

ヘッダーファイルを使用した開発を行う場合は、IncludeフォルダのパスをInclude Dirへ入力して下さい。

この拡張機能はコンパイルログを出力します。
デフォルトではコンパイルファイルと同じディレクトリにcompilemql4.logという名前のファイルで出力します。
任意のディレクトリ、ファイル名にログを出力したい場合はLog Dirを設定して下さい。

**Enjoy!**

# compilemql4 README (English)

An extension for compiling MT4 mql4 files, mqh files, and subsequent mql5 files with VSCode.

## Requirements

To use this extension, MetaEditor must be installed.
Please use this extension on a PC with metaeditor.exe (metaeditor64.exe for MT5) installed.
metaeditor.exe is installed when you install MT4.

## Extension Settings

Check Compile After Save to automatically compile when you save a file.

Before use, enter the path of metaeditor.exe in Metaeditor Dir in the extension settings. *Required

If you are developing using header files, enter the path of the Include folder in Include Dir.

This extension outputs a compilation log.
By default, it outputs a file named compilemql4.log in the same directory as the compilation file.
If you want to output the log to a directory or file name of your choice, set Log Dir.

**Enjoy!**