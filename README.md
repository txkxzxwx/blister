# README
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
 
Thank you!

## usersテーブル
|Column|Type|Options|
|------|----|-------|
|nickname|string|null: false|
|email|string|null: false|
|encrypted_password|string|null: false|
|iamge|text|null: false|

## tweetsテーブル
|Column|Type|Options|
|------|----|-------|
|name|string|null: false|
|text|string|null: false|
|image|text|null: false|
|user_id|integer|null: false|