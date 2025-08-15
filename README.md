参考にしたサイト

https://tailwindcss.com/docs/installation/framework-guides/ruby-on-rails


新型らんてくん

🚀 TailwindCSS導入の具体的手順
Step 1: Gemを追加
公式ドキュメントの内容をDockerコンテナ環境に合わせて実行します：

# tailwindcss-rubyを追加
docker compose exec web bundle add tailwindcss-ruby

# tailwindcss-railsを追加  
docker compose exec web bundle add tailwindcss-rails
Step 2: TailwindCSSを初期化
docker compose exec web rails tailwindcss:install