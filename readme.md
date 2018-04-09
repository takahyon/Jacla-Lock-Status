# Jaclaの部室の鍵の状態を自動でlineとTwitterに投稿するIoT

## 1. 要件定義
これは工科大総合音楽部Jaclaの部室の鍵を開け閉めした際に自分でLineやTwitterに投稿することは非効率というか面倒くさいので自動化した。

## 2. 使ったもの
nodemcu v1.0(wifi搭載 arduino互換ボード)
MPU-6050 (6軸ジャイロセンサー)
単三電池4本(バッテリー)

## 3.　ソースコード
以下の2サイトを参考にしながら書きました(githubに載せてなかったのでURLの紹介に留めます)

http://cranberrytree.blogspot.jp/2014/06/gy-521mpu-6050.html
https://qiita.com/key/items/8c6b684e6308cc5f451f

## 4. 使用ライブラリ
Arduino Json
https://github.com/bblanchon/ArduinoJson

kriswiner/MPU6050
https://github.com/kriswiner/MPU6050

witnessmenow/arduino-ifttt-maker
https://github.com/witnessmenow/arduino-ifttt-maker

## 5. 最後に
コーディングについてコメントアウトなどは後々追加していきます。
いい機能が書けましたらプルリク送ってください。
