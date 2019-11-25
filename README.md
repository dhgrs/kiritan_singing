# 東北きりたん歌唱データベースのラベルデータ
東北きりたん歌唱データベース（きりたん歌唱DB）の最新ラベルデータを共有するためのリポジトリです．データベースの本体は[こちら](https://zunko.jp/kiridev/login.php)からダウンロードできます．

## 本リポジトリで配布するデータとGitHubで公開する動機
本データベースのラベルにはmidi_labelとmono_labelとがあり，それぞれ譜面データと音素境界のデータとなります．MIDIについてはMelodyneで自動採譜した後に手動で調整したものを配布していますが，楽曲によっては採譜そのものが困難な場合や，キーが曖昧でずれてしまっている場合があります．これら以外にも，実際に利用してみて判明する問題もあると考えられることから，ご利用者の皆様の修正案をここで議論できればと思い，ラベルデータのみGitHubで管理することにしました．

ラベルデータは本リポジトリで修正できますが，歌唱ファイルを修正する前処理はここで処理できません．修正のアイディアをissueで投げて頂ければ，本readmeに反映するように致します．明確なミスの場合はすぐ差し換えますが，微妙な差についてはissue内で差し換え・掲載するべきか議論する形にさせてください．以下の例のように情報は逐次更新していき，修正にご協力頂いた皆様のお名前はできるだけクレジットさせて頂く予定です．なお，本データベースはあくまでも改正著作権法30条の4に定められた範囲での利用に限定されていますので，本リポジトリやそれ以外の場所においても範囲を逸脱した使途にならないようにお気をつけください．

## 現時点で判明しているラベルの問題点
- 08: 前半部分の採譜が極めて困難なため，MIDIそのものが存在しない

## その他データベースについて品質を上げるための工夫
- 08: 歌声そのものについて，推定されたF0がMIDIとずれているため学習前にF0をMIDIに寄せたほうが良い

## 修正履歴
- 2019/11/25: 06の後半部分のMIDIラベルが無かったので追加しました．
- 2019/11/22: MIDIラベルの13と14が逆だったので入れ替えました．

## ご協力頂いた皆様
ある程度人数が集まったタイミングでまとめて更新致します．Twitterでコメント下さった方はTwitterIDを記載致します．
