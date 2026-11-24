AI_clip 2026/0609 sabakanf

Adobe Illustrator用の選択データ切り出し・分割補助ツールです。


使い方:
1. AI_clipフォルダを丸ごとつかいます。
2. Illustratorで枠または切断線と、処理したいオブジェクトを選択します。
3. ファイル > スクリプト > その他のスクリプト から AI_clip.jsx を実行します。


注意:
　Jsxで動いていますが計算処理はPythonで行っています。そのため下記の注意事項が存在します

- フォルダ構成を変更しないでください。
- JSXファイル名は変更しても構いません。
- AI_clip_engine フォルダ名と中身は変更しないでください。
- Pythonのインストールは不要です。
- 本ツールは無保証です。実行前に元データを保存してください。

配布物にはPython/PyInstaller由来のコンポーネントが含まれます。詳細は同梱のNOTICE.txtをご確認ください。


Copyright (c) 2026 sabakanf

AI_clip の著作権は制作者に帰属します。

本ツールは無保証です。
本ツールの使用によって生じたいかなる損害についても、制作者は責任を負いません。

知人・関係者向けの利用を想定しています。
再配布・改変・商用利用を行う場合は、事前に制作者へ確認してください。

---

## English

AI_clip is a tool by **sabakanF** for extracting and splitting vector artwork in Adobe Illustrator. It is designed for drawings with many layers. Select a boundary to extract the artwork within it, or select a cut line to split the artwork. You can copy the extracted region into another Illustrator document, where the layer organization helps you continue editing individual paths.

### How to run AI_clip

1. Keep the entire `AI_clip` folder together.
2. In Illustrator, select the boundary or cut line along with the objects you want to process.
3. Choose **File → Scripts → Other Script…** and run `AI_clip.jsx`.

### Setup notes

The Illustrator script uses a bundled Python engine for calculations. You do not need to install Python.

- Keep the folder structure intact.
- You can rename the JSX file.
- Keep the `AI_clip_engine` folder name and its contents as supplied.
- Save your original artwork before running the tool.

The package includes components from Python and PyInstaller. See the included `NOTICE.txt` for details.

### Copyright and terms of use

Copyright © 2026 sabakanF. The author retains the copyright to AI_clip.

The tool is provided without warranty. The author is not liable for damages arising from its use. The tool is intended for acquaintances and related parties. Contact the author in advance regarding redistribution, modification, or commercial use.
