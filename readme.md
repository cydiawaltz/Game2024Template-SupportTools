# マイコン部2024年度ゲーム提出用テンプレート
## はじめに
このテンプレートは文化祭に提出するゲーム「MonitorMan Shooting」を一例とします。<br>
各自参考にして下さい。<br>
## 文字が読みたくない人向け
特に凝る気がない方は文字入りのロゴマークを「logo.png」、文字なしのロゴを「side.png」、ゲームのプレイ動画（2,3秒が望ましい）を「monitor.mp4」とし、それらを同一フォルダにまとめて高1渡邉に提出。<br>
## フォルダ構成について
「テクスチャ」フォルダにはテクスチャファイルを入れて下さい。(こちらで加工します) <br>
「本体」フォルダにはゲームの本体とreadmeを入れて下さい。(後述) <br>
「ゲーム説明」フォルダはゲームのタイトルや説明などを入れるフォルダです。<br>
## 「テクスチャ」フォルダについて
それぞれどの部分のテクスチャなのかは基本的に名前で判断するため、ファイル名はサンプル通りにしてください。 <br>
テクスチャはpng,jpeg,gifのどれかにしてください。（透過が使用でき、色数を多く使えるpngをおすすめします。また、gifはpngに変換します）<br>
<命名規則（拡張子は今回pngとして表記してありますが、以上の通りで構いません）> <br>
正面ロゴ→logo.png <br>
筐体横に入れるロゴ→side.png <br>
ゲーム画面→monitor.png（ここのみmp4でも可能、連番PNGに変換する可能性あり？）<br>
尚、テクスチャ画像を自作する場合は(このフォルダ)\制作補助ツール\テクスチャ自作勢向けフォルダ\UV にUVイメージ類が格納されているのでお使いください。<br>
実際のモデルはこちらから→ https://github.com/HongoMCC/GameLuncher2024/blob/master/Assets/Models/Working/%E6%96%87%E5%8C%96%E7%A5%ADAC%E7%AD%90%E4%BD%93.blend <br>
AC筐体又はテクスチャを自作する場合は完成したものををこのフォルダに**テクスチャ画像を付けて**お入れ下さい。（Unityで使用する関係上）<br>
## 「本体」フォルダについて
ゲームの本体とreadmeファイルはここに格納してください。<br>
本体はexeもしくはhtmlで提出して下さい。（Pythonやjavaなど特殊環境下でしか動かないものは認められません。）<br>
実装の都合上、必ず本体はmain.exeもしくはmain.htmlとして下さい。<br>
Mac版やLinux版を出したい方は交渉していただければオプションとして用意できる可能性があります。ただ、基本的にはwindowsのゲームとなります。（Macユーザーにはwineを使っていただきます）<br>
readmeファイル添付してください。しない場合はこちらで勝手に作成します。<br>
## 「ゲーム説明」フォルダについて
ゲームの説明を入れて下さい。書式はtext.txtを参考。<br>
## ルール
ディスコにもありますが、ゲーム作成時のルールを再掲。<br>
https://discord.com/channels/701055806317264976/749541026019934220/1230457425866395698 <br>
>＜提出するゲームで守られたい事項＞<br>
>・別途で入れるべきものはこっちでは実装しない<br>
>・上限は20まで(要検討)、それ以上だったら部長郡(+俺)の独断と偏見で判断（文化祭では全て載る）<br>
>・提出する際はコメント（ゲームの説明等）、タイトル、実行ファイル等と中身が記載されたReadMe <br>
>・全体で4GB以内なので過度に重いゲームはオンラインインストーラーにするなどで対応求（守ってない場合rejectする）<br>
>・ゲームは起動、そして終了ができるようにすること <br>
>・Pythonやjavaのインストール必須など特殊環境上でしか動かないものは認められない、必ずexe,html等Winの標準機能で開けるものに <br>
>・フォルダの名前はあとから変更する、プログラム本体はフォルダ直下にmain.exe(main.html)、ReadMeはreadme.txt1とすべき（readmeがないものは受け付けない、配置に関しては要相談）<br>
>・タイトルロゴ、ゲームのプレイ画面もしくはアイコンを提出すべき（いい感じにするのでサイズについては不問だが、解像度は落としたり上げたりしたりすることもある）<br>
>・必ずWindows8.1以上で動く状態で提出（Mac,Linux版などは付けてもよいがwin版は必須）<br>
>・エロ/グロ表現などの非全年齢対象ゲームは認められない <br>
>・同じく課金要素を伴うものは禁止、可能ならゲーム内ミッションにより開放されるステージなどもない方が良い<br>
>・ホスティングはしないのでオンラインゲームは不可（自分でホスティングできるなら可）<br>
>＜ゲーム数が足りないとき＞ <br>
>・去年度以前のものからいいかんじの反応だったやつを抜粋して数を埋め合わせる <br>
>＜ゲームが多いときの選考基準（改訂アリ？）＞ <br>
>・主にグラフィックス・操作性・面白さ等クオリティ、次いでやりこみ要素の有無・軽量or重量などを重視 <br>
>・＜提出するゲームで守られたい事項＞内を守っていないものはrejectする可能性が大いにあり <br>
>＜ゲームの並び順＞ <br>
>・まだきまってねぇ <br>
>＜ゲームブラウザの形式＞ <br>
>・ナムコミュージアム アーケードHITS! みたいな感じでいきたい <br>
>・今年も俺が作るゾ<br>
>・またGitHubに上げるんで各自cloneしたりして開発に協力してくれるとありがたい（特にUnity技術者？各自）<br>
