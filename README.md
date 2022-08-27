# PokemonDP_youtube
視聴者操作型　ポケモン ブリリアントダイヤモンドをYoutubeで配信しています。  
チャット欄から指定のコマンドを入力していただくと、ゲームを操作していただくことができます。　　
## Youtube LIVE 動画　　
### (チャット欄からキャラ操作可能) みんなで進めるポケモン　ブリリアントダイヤモンド  
※下の画像をクリックするとライブ動画を見ることができます。
[![pokemonDaiamond](/img/thumbnail_youtube.jpg)](https://www.youtube.com/channel/UC_G0xSWO83Xp1h-dtJDePRw/live)　　

## チャット欄での操作方法
![操作方法](/img/pro-controler-explanation.png)  
画像は[任天堂株式会社の画像](https://www.nintendo.co.jp/hardware/switch/accessories/procon.html?width=960)を引用の上、追記

### コマンド等の詳細な仕様について
#### !pushコマンドについて
- 指定した回数ボタンを連続で押す
- ボタンを押す間隔は現在、1.5秒  
- 回数を指定しなかった場合はボタンが１回のみ押される。
- 例（Aボタンを３回押す）：`!push A 4`    


#### !pressコマンドについて
- 指定した秒数ボタンを押し続ける
- 秒数を指定しなかった場合は0.3秒間押し続ける。
- 例（５秒間左方向に移動する）：`!press left 5`  

#### 特殊コマンド（自動コマンド）について
[こちら](https://github.com/AI-switch-programming/PokemonDP_youtube/wiki/%E7%89%B9%E6%AE%8A%E3%82%B3%E3%83%9E%E3%83%B3%E3%83%89)を参照

#### コマンドの細かい仕様について
【細かい仕様等について】：
・回数と秒数はオプションです。指定しない場合や誤った入力をした場合はそれぞれ１回、0.3秒が入力されます。  
・コマンド名、ボタン名、（回数/秒数）の間には空白を入れてください。  
・回数/秒数は半角数字を入力してください。入力できる最大数は10です。  
・簡易コマンドによる入力の場合はNightbotが代わりにコマンドを入力してくれます。  
・コメントによる操作がない場合はランダムなコマンドが実行されます。  
・１度コメント欄でコマンドを打つと最後にコマンドが実行されてから約６０秒間はランダムコマンドは実行されません。（視聴者のみなさまの操作が優先されます。）  
・コメント欄に連続で入力した場合は、それらのコマンドが順番に実行されます。ばんばん入力してください！  
・8秒に一回、コメント欄の皆さんのコマンドを確認しているため、実行されるまで多少のラグがあります。  
・左上にコマンドとコマンドの書き込み主が表示されます。Random action はランダムなコマンドが実行されている場合です。  
・通信機能、ポケモンをにがす、設定の変更はできないようにしております。  
・バグで操作不能になる場合もあります。ご了承ください。  

## 仕組みについて
どのようにして、Switchを操作しているか、仕組みをご説明します。[仕様等](https://github.com/AI-switch-programming/PokemonDP_youtube/wiki/Wiki)

## ポケモンが初めてという方へ
作成中。。。


## ご質問・ご要望等
[github](https://github.com/AI-switch-programming/PokemonDP_youtube/discussions/8), [Youtubeのチャット欄](https://www.youtube.com/channel/UC_G0xSWO83Xp1h-dtJDePRw/live), [Discordサーバー](https://discord.gg/kAjhKGYx9Y)　　
上記のサイト、どれでも結構ですので、お気軽にご連絡下さい。  
