# Emoticons #

* Authors: Chris Leo, Noelia Ruiz Martínez, Mesar Hameed, Francisco Javier
  Estrada Martínez

このアドオンを使うと、顔文字を含むテキストを読み上げるときに人間がもっと理解しやすい表現に置き換えます。

例えば: ":)" は「ほほえんでいる顔文字」と読み上げられるか、または、例えばNVDAはそれぞれの絵文字の意味を認識します。

次のような機能を利用出来ます:

## 顔文字の挿入 ##

Sometimes an image is worth a 1000 words: use the new emoji to liven up your
instant message and to let your friends know how you’re feeling.

特定の笑った顔文字の文字がわからない時、このアドオンにより、選んで、チャットなどのテキストに挿入出来るようになります。

Press NVDA+Iを押す、または、ツール->Emoticons>顔文字を挿入のメニューから、提供された顔文字や絵文字のあるダイアログを開きます。

このダイアログから、顔文字を選択し、興味のある絵文字について閲覧することが出来ます:

*	編集可能なフィールドにより、利用可能な顔文字の中から、使用したい顔文字を検索してフィルターすることが出来ます。
*	ラジオボタンのセットにより、絵文字カテゴリのみ(alt+E)を閲覧、標準顔文字カテゴリのみを閲覧(alt+s)、または、全ての利用可能な顔文字を閲覧(alt+A)を選択することが出来ます。
*	顔文字のリスト(alt+L)には、3つの列が表示されています。それぞれ、: 顔文字の名前、顔文字の種類(標準顔文字または絵文字)、対応する文字です。

OKを押すと、選択された顔文字の文字がクリップボードにコピーされて、貼り付け可能になります。

## 記号の挿入 ##

This dialog allows you to choose one of the symbols available in the
Punctuation/symbol pronunciation dialog of NVDA. You can use the Filter edit
box or the arrow keys to select an item from the symbols list.

If you want to copy various symbols, use the Add button to append them to
the Symbols to copy edit box.

Then, press OK and the selected emoji or symbol, or the symbols contained in
the mentioned edit box, will be copied to your clipboard, ready for pasting.

## Associate gestures to symbols ##

From NVDA's menu, Preferences submenu, Input gestures dialog, category
Insert symbols or Copy symbols, you can configure NVDA to type symbols
through associated gestures.

You can use the Edit field edit box to reduce the number of symbols
presented, so that this category can be expanded faster.

## 顔文字辞書 ##

Emoticonsアドオンは、設定プロファイルを使用して、異なる読み上げ辞書を持てるようになります。

これは、それぞれのカスタムプロファイルに、特定の読み上げ辞書を作成または編集出来るということです。

NVDAメニュー、設定(P) - > 読み上げ辞書 - > Emoticons辞書から、利用可能な顔文字を追加または編集するダイアログを開けます。

カスタマイズを保存すると、顔文字の新しい読み上げ設定が、現在編集しているプロファイルのみに適用されます。

例えば、NVDAがカスタム絵文字をXxチャットプログラムだけで読んでほしいけれど、他のチャットプログラムで読んでほしくないと思うかもしれません:
これは、Xxチャットアプリケーション用のプロファイルを作成し、これに読み上げ辞書メニュー、Emoticons辞書オプションから、読み上げ辞書を割り当てすることで可能です。設定プロファイルに関するEmoticon設定については、以下を参照して下さい。

"辞書を保存してエクスポート"ボタンを押して、それぞれのカスタム読み上げ辞書のエクスポートも出来ます:
この方法で読み上げ辞書がユーザーのconfigフォルダのspeechDicts/emoticonsサブフォルダに保存されます。

辞書ファイルの正確な名称と位置は、編集している設定プロファイルに基づき、Emoticon辞書ダイアログのタイトルに表示されます。

## Emoticon設定 ##

設定(P) -> 設定(S) ->Emoticonsメニューから、それぞれのプロファイルで有効にする読み上げ辞書を設定するパネルを開きます。

Emoticons設定パネルにて、NVDAが現在編集しているプロファイルに切り替える時に、読み上げ辞書を自動的に有効にするかどうか、選択出来ます。初期設定では、NVDAの標準設定と新しいプロファイルの全てで無効となっています。 

さらに、アドオンの絵文字が読み上げされるかを、決定することが出来ます。これは、NVDAの設定に絵文字が含まれている場合に、記号読み上げを保持するのに便利です。

If symbols inserted using associated gestures aren't spoken in your system,
even when NVDA is configured to speak typed characters, you can try to
enable a checkbox to ensure the speaking of inserted symbols.


設定フォルダーをきれいに保ちたい場合は、このダイアログで、使用されていない辞書(存在しないプロファイルに関連付けられている)を、アンロード時に、アドオンから除去することを選択することも出来ます。

## キーコマンド: ##

これらは初期設定で利用可能なキーコマンドです。これらを編集したり、Emoticons設定パネルまたはEmoticon辞書ダイアログを開く、新しいキーを追加したりすることが出来ます:

* NVDA+E: 書かれた通りのテキスト、または、人による表現に置き換えられた顔文字による読み上げの間で、絵文字の読み上げのオンオフを切り替えます。
* NVDA+I: コピーしたい顔文字を選択するダイアログを表示します。
* 割り当てなし: コピーしたいNVDAの記号を選択するダイアログを表示します。
* 割り当てなし: 表現全体がブラウズモードで閲覧出来るように、レビューカーソルが位置している記号を表示する、閲覧可能なメッセージを開きます。
* 割り当てなし: 表現全体がブラウズモードで閲覧出来るように、キャレットが位置している記号を表示する閲覧可能なメッセージを開きます。

備考: Windows 10以降では、搭載の絵文字パネルを使用することも可能です。

## Changes for 34.0.0

* Added ability to copy to clipboard, and paste individual symbols, useful
  when gestures associated with Insert symbols scripts don't work.


## Changes for 33.0.0

* Fixed bug in Save and export dictionaries.
* Added copy and close buttons to messages presented in browse mode.
* When using commands to insert symbols, they may be spoken according to the
  speak typed characters option.

## Changes for 22.0.0 ##

* Requires NVDA 2023.2 or later.

## Changes for 17.0 ##

* Added ability to associate gestures to type symbols.
* Added ability to copy various symbols at the same time.

## Changes for 16.0 ##

* Compatible with NVDA 2023.1.

## 15.0の変更点 ##

* NVDA 2022.1以降が必要。
* セキュアモードで使用不能。

## 14.0の変更点 ##

* NVDA 2021.1に互換。

## 13.0の変更点 ##

* 絵文字挿入ダイアログでのエラーを修正しました。
* NVDAの句読点/記号の読み上げで利用可能な記号を挿入するダイアログを追加しました。

## 12.0の変更点 ##

* NVDA 2019.3以降が必要です。

## 11.0の変更点 ##

* アドオンが更新される時、NVDAのメイン辞書フォルダに保存された辞書のインポートを好む場合を除き、アドオンの前のバージョンで保存された辞書は自動的に新しいバージョンにコピーされます。
* キャレッドまたはレビューカーソルが位置する記号を表示する時、記号そのものと、ブラウズモードでの表現を区別するために、文字や置換という言葉が使用され、読み上げユーザーに便利です。

## 10.0の変更点 ##

* レビューカーソルまたはキャレットが位置している記号を表示するコマンドを追加しました。これらのコマンドのジェスチャーは入力ジェスチャーダイアログ、Text
  reviewカテゴリーから割り当て出来ます。

## 9.0の変更点 ##

* このアドオンの絵文字が読み上げされるべきか選択出来るようになりました。
* 辞書名に適切なエンコードを使用し、特定の文字を含んでいる時のエラーを修正しました。
* 翻訳されたこのアドオンについての概要が、アドオンヘルプに表示されるタイトルに適切に使用され、アドオンマネージャーからアクセス出来るようになりました。
* Windows 10で利用可能な絵文字パネルについての説明を追加しました。

## 8.0の変更点 ##

* NVDA 2018.3以降に互換(必要)。

## 7.0の変更点 ##

* 現在のプロファイルがNVDAの設定ダイアログのタイトルに表示されるように、NVDA設定のパネルに動作設定ダイアログを移動しました。
* 顔文字管理メニューが除去されました:
  顔文字の挿入は、ツールメニューの下に見つかり、Emoticon辞書のような読み上げ辞書の下に、顔文字のカスタマイズが見つかるようになりました。
* NVDA 2018.2以降が必要。

## 6.0の変更点 ##

* 設定プロファイルのサポートを追加しました。
* NVDA 2017.4以降では、
  設定やカスタム辞書は、選択されたプロファイルによって、自動的に変わるようになりました。2017.3以前では、プラグインを再読み込みして(control+NVDA+f3を押す)、変更を適用出来ます。
* アドオンを更新する時、設定のインポートを選択すると、使用されなくなるファイル(emoticons.iniとemoticons.dic)は削除されるか、このバージョンに適合されます。

## 5.0の変更点 ##

* 絵文字のサポートを追加しました。
* 顔文字挿入ダイアログの、表示される顔文字を選択するためのフィルターフィールドとラジオボタンの改善。
* 動作設定ダイアログと顔文字挿入ダイアログにguiHelperを使用: NVDA 2016.4以降が必要

## 4.0の変更点 ##

* 他の設定ダイアログが開いている状態で「顔文字の挿入」ダイアログを開くとエラーメッセージが表示されるようになりました。


## 3.0の変更点 ##

* エモーティコンの編集ダイアログにおいて、パターンを単語全体にだけ適用するかどうかを指定できるようになりました。これは NVDA 2014.4
  の読み上げ辞書で追加された機能です。


## 2.0の変更点 ##

* アドオンマネージャーからアドオンのヘルプが利用できるようになりました。


## 1.1の変更点 ##

* 重複した顔文字を消去しました。
* 顔文字を追加しました。

## 1.0の変更点 ##

* 最初のバージョン。

[[!tag dev stable]]

