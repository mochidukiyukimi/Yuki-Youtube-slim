ASGIで動く  
deployボタンは追加していく予定です  
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。  
画像は使えません。  
cookieにyuki=Trueを設定すると認証されます。  
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。  

Renderを使用する場合の手順  
1.githubアカウントを作成する  
2.リポジトリを作る(名前はなんでもいい)(プライベートリポジトリにすることをおすすめします)  
3.import codeを押して https://github.com/mochidukiyukimi/Yuki-Youtube-slim/ と入力  
4.render.yamlを開いて編集(鉛筆のマーク)を押し、nameの横のyuki-youtube-slimをサイトのurlの最初の部分にしたい文字列に変更する。(yuki-yだったらurlはhttps://yuki-y.onrender.comになる)  
5.Deploy to renderボタンを押し、Service Group Nameに適当な文字列を入れてapply(事前にrenderのアカウントを作っておく)
<a href="https://render.com/deploy?repo=https://github.com/mochidukiyukimi/Yuki-Youtube-slim">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/dSxuA8)
