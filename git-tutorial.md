# 基本的なGitコマンド

## リポジトリの作成と初期化
git init

## ファイルの追加
git add <ファイル名>
git add .  # すべての変更をステージング

## コミット
git commit -m "コミットメッセージ"

## リモートリポジトリの追加
git remote add origin <リポジトリURL>

## プッシュ
git push -u origin main

## プル
git pull origin main

## ブランチの作成と切り替え
git branch <ブランチ名>
git checkout <ブランチ名>
git checkout -b <新しいブランチ名>  # 作成と切り替えを同時に行う

## ステータス確認
git status

## 変更履歴の確認
git log