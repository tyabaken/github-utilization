# github-utilization
github活用

## 活用法

■ルール
---

・作業内容はissueにあげる  
 → ブランチ、コミット管理を容易にするため
 
・issueで使用できるタグを作成する。

・環境構築の手段はreadme.mdに記述する。  
 → redmineでもいいけど多重管理になるからやめておいたほうがいい・・・

---

ブランチ

・Masterブランチは触らない。  
　→masterブランチは基本的にリリースされているモジュールが存在するようにする。
 
・developブランチを作成する

・developブランチから各issue名を含めたブランチを作成する  
　 featureを作成  
　例)feature/#000-xxxsss  
 
・ブランチ名はわかりやすく

・リリースタイミングでmasterに対してdevelopをマージする。

---

コミット

・コミットコメントはissueの該当する番号を含める。  
例)#xxx 〇〇を修正しました。  
　→該当のissue内でコミットの内容が確認できるようになる。
 
・コミットする際は、差分を必ず確認する。

---

マージ

・developブランチへマージする時はプルリクエストを使用する。  
　→ プロジェクト管理者がソースレビューを行う。(これは適宜が変えてもいい)
 
・プルリクエストタイトルはissue番号を含める  
　→ソースレビューしてほしい事項などあればコメントにて記載する。

---
リリース

・developブランチからmasterブランチへマージする。  
　→ マージは管理者が行うこと(プルリクエストを使用)
 
・タグを作成し後々の管理に役立てる。


■他

・プルリクエストマージ権限  
http://yourmystar-engineer.hatenablog.jp/entry/2017/05/08/113147

・redmineとgithubの連携  
https://qiita.com/n_slender/items/54cd282c140fadbbb322

・プルリクエスト、issueのコメントテンプレートの使用方法  
https://qiita.com/nyamogera/items/3fe6985b45fbd5377184


