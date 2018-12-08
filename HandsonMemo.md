#mvc とは  
model, view, controller の略
順序としては c m v

##model  
アプリケーションデータ  
データに関する内容はここに書く
→ データベースに保存する内容  
 → 今回は idea  
 → データの操作などをする  
基本的に model と table が一対一

##view  
どういうふうにデータを表示するか  
 → モデルから見れる状態に変換する

##controller  
リクエストを受け取って指示する  
model の内部データを直接操作しない

#データベース  
→ テーブル(Sheet)とカラム(列)

#Generate コマンド
template から一気に何かを生成する  
　 → 何か：コマンドで指定したモノ

#OSS  
open sourcee software の略
Linux の多くもこれにあてはまる  
複数人で編集，見る  
問題が起きても見れるから安全というわけでもない...  
問題がないか確認できるのは良い所

#Picture のアップロード  
`mount_uploader :picture, PictureUploader`  
→picture:カラム

#コマンド  
##scaffold  
カラムの名前と種類(型)の指定
