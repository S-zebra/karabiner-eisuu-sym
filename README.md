# これは何ですか？
プログラミングで多用する記号を、楽に打つためのKarabiner-Elements用スクリプトです。
多くのプログラミング言語では、カッコや記号類を多用します。しかし多くのキーボードでは、記号類がホームポジションから最も遠い数字(最上)段にあるため、手全体を大きく移動させなければ届きません。また、小指にあるシフトキーも同時に押さねばならず、疲れを感じる原因となるでしょう。
お手持ちのKarabiner-Elementsにこのスクリプトを導入すれば、ホームポジションから手を動かさずに記号類を打てるようになるため、疲労の低減が期待できます。

具体的には、左手の親指で「英数」キーを押したままにすると、右手側のキーで下図の記号が入力されます。多くのプログラミング言語で快適になるよう考慮しましたが、もしご不満点があれば各自で改変いただくか、「Issues」ページまでご投稿いただければ、変更を検討いたします。
![Shifted layout](https://github.com/S-zebra/karabiner-eisuu-sym/master/readme-images/shift.png)

# 導入方法

0. Karabiner-Elenentsをインストールします。
Karabiner-Elenentsは、macOS用のキーリマップソフトです。
まず、[こちら(https://pqrs.org)](https://pqrs.org/osx/karabiner/)からダウンロード・インストールしてください。

1. `programmer_syms.json`を`~/.config/karabiner/assets/complex_modifications/`にコピーします。
![Copy to Karabiner settings](https://github.com/S-zebra/karabiner-eisuu-sym/master/readme-images/copy.png)
または、ターミナルで
```
$ cp [path_to_repo]/programmer_syms.json ~/.config/karabiner/assets/complex_modifications
```
としてもOKです。

2. Karabiner-Elementsを開き、「`Complex Modifications`」タブ左下の「`(+) Add rule`」をクリックします。
![Karabiner 1](https://github.com/S-zebra/karabiner-eisuu-sym/master/readme-images/kara1.png)

3. 「`英数キーによるシフトで、記号入力を省力化する`」の「`(+) Enable`」をクリックします。
![Karabiner 2](https://github.com/S-zebra/karabiner-eisuu-sym/master/readme-images/kara2.png)

以上で導入作業は完了です。Enjoy Programming!