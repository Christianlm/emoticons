# Emoticons #

* Authors: Chris Leo, Noelia Ruiz Martínez, Mesar Hameed, Francisco Javier
  Estrada Martínez
* ダウンロード [安定版][1]
* ダウンロード [開発版][2]

Using this add-on, spoken text containing emoticon characters will be
replaced by its more human friendly description.

For example: the sequence ":)" will be spoken as "smiling smiley", or for
example NVDA will recognize the meaning of each emoji.

次のような機能があります:

## Insert Emoticon ##

When you are unsure of the characters for a particular smiley, this addon
enables you to select and insert it into your text such as in a chat.

Press NVDA+I, or from menu Preferences -> Manage emoticons -> Insert emoticon, to open a dialog with the provided emoticons or emoji.

This dialog allows you to choose an emoticon and to view the emoticons that
interest you:

*	An editable field allows you to filter the search for the desired emoticon
  among the emoticons available.
*	Through a set of radio buttons, you can choose to view    only emoji category (alt+E) or view only standard emoticon category (alt+s) or view all emoticons available (alt+A).
*	In the list of emoticons (alt+L) are displayed  on three columns respectively: the name of emoticon, the type of emoticon (standard emoticon or emoji), the  corresponding character.

When you press OK, the characters for the chosen emoticon will be copied to
your clipboard, ready for pasting.

## エモーティコンの編集 ##

From NVDA MENU, Preferences -> Manage emoticons -> Customize emoticons, you can open a dialog setting to add or to edit available emoticons.

This dialog allows you to save an emoticons speech dictionary with your
customizations.

「辞書を保存してエクスポート」ボタンを押すと、NVDAユーザー設定フォルダーの speechDicts サブフォルダーにファイル名
emoticons.dic で保存されます。

## 設定の有効化 ##

From menu Preferences -> Manage Emoticons -> Activation settings, you can choose whether to Activate speaking of emoticons when starting NVDA. By default it is disabled.
It is also possible to save your choice for this setting.

## キーコマンド: ##

These are the key command available by default, you can edit those or add
new key to open Activation settings dialog or Emoticon Dictionary dialog:

* NVDA+E: テキストを書かれた文字のまま読み上げるか、エモーティコンを理解しやすい読み方に置き換えるかを切り替えます。
* NVDA+I: show a dialog to select an emoticon you want to copy.


## Changes for 5.0 ##

* Added support for emojis.
* Improvements for Insert Emoticon dialog with a filter field and radio
  buttons to choose displayed emoticons.
* Using guiHelper for Activation settings dialog and Insert Emoticon dialog:
  requires NVDA 2016.4 or higher versions

## 4.0 での変更点 ##

* 他の設定ダイアログが開いている状態で「顔文字の挿入」ダイアログを開くとエラーメッセージが表示されるようになりました。


## 3.0 での変更点 ##

* エモーティコンの編集ダイアログにおいて、パターンを単語全体にだけ適用するかどうかを指定できるようになりました。これは NVDA 2014.4
  の読み上げ辞書で追加された機能です。


## 2.0 での変更点 ##

* アドオンマネージャーからアドオンのヘルプが利用できるようになりました。


## 1.1 の変更点 ##

* 重複したエモーティコンを消去しました。
* 顔文字を追加しました。

## 1.0 での変更点 ##

* 最初のバージョンです。

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=emo

[2]: http://addons.nvda-project.org/files/get.php?file=emo-dev
