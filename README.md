# README
"blister"はコレクターによるコレクターの為の写真投稿サイトです。<br><br>
服やtoy、骨董品など世界中には様々な物のコレクターが存在しております。<br>
そしてコレクターには以下の気持ちがあると考え本アプリを制作しました。<br>
・自分のコレクションを見て欲しい。<br>
・他の人の収集したコレクションを見てみたい。存在する貴重なアイテムを見てみたい。<br><br>
現在Instagramなどのサイトではタグ検索も１つのワードでしかできず、検索ワードによれば莫大な結果がヒットしてしまう。<br>その為上記のようなコレクションのアイテムを見たい場合はコレクターのアカウントをまず見つけ、そこから投稿写真を見る他なくとても手間がかかっていまいます。<br>
そこで今後はタグ付け・複数タグ検索、お気に入り、DM等機能を実装し世界中のコレクターが互いのアイテムを見ることで刺激を受け、時にはトレードや売買などコミュニケーションの取れるアプリにしていきます。

"blister" is a image contribution browsing for collector with Ruby.
 
# DEMO
 
You can show your collection and communicate with collector of the world .
 
[![Image from Gyazo](https://i.gyazo.com/0a24bfe2784bddf18978f69d0d4f889b.gif)](https://gyazo.com/0a24bfe2784bddf18978f69d0d4f889b)
 
# Features
Post image

Search function
[![Image from Gyazo](https://i.gyazo.com/623580da248e7077f94142354bf1d608.gif)](https://gyazo.com/623580da248e7077f94142354bf1d608)

comment function
[![Image from Gyazo](https://i.gyazo.com/50571782312c36cf628b40953ed59cb0.gif)](https://gyazo.com/50571782312c36cf628b40953ed59cb0)
 
# Requirement
 
* ruby 2.5.1

# Usage
 
http://52.194.103.116/

test account
  Email:test1@test.com
  Password:00000000

# ERD
![blister](https://user-images.githubusercontent.com/59860393/77816617-4d12aa00-7107-11ea-81ef-3da40ac2d64f.jpeg)

# usersテーブル
|Column|Type|Options|
|------|----|-------|
|nickname|string|null: false|
|email|string|null: false|
|encrypted_password|string|null: false|
|iamge|text|null: false|

# tweetsテーブル
|Column|Type|Options|
|------|----|-------|
|name|string|null: false|
|text|string|null: false|
|image|text|null: false|
|user_id|integer|null: false|

# commentsテーブル
|Column|Type|Options|
|------|----|-------|
|text|text|null: false|
|tweet_id|integer|null: false|
|user_id|integer|null: false|


Thank you!