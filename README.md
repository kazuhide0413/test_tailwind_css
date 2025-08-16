# 公式
https://tailwindcss.com/docs/installation/framework-guides/ruby-on-rails
# 新型らんてくん
🚀 TailwindCSS導入の具体的手順
# Step 1: Gemを追加
公式ドキュメントの内容をDockerコンテナ環境に合わせて実行します：
tailwindcss-rubyを追加
docker compose exec web bundle add tailwindcss-ruby
tailwindcss-railsを追加  
docker compose exec web bundle add tailwindcss-rails
# Step 2: TailwindCSSを初期化
docker compose exec web rails tailwindcss:install



# ついでにdaisy uiも導入　
https://daisyui.com/

①どっかーコンテナ入る
②yarn add -D daisyui@latest
③app/assets/tailwind/application.cssに追記する
@import "tailwindcss";
@plugin "daisyui";
④https://daisyui.com/components/button/?lang=ja
いろんなボタンある
