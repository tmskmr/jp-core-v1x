## 事前条件
事前にデフォルトWebブラウザにてGitHubにログインをすること
VSCodeのコマンドパレット「Ctrl(windows)」/「Command(mac)」+「Shift」+「P」の呼び出しについてはコマンドパレットと書略するので注意のこと。

## ローカルにgitクローン作成
1. git cloneの実行（Visual Studio Code）<br/>
コマンドパレットより、```git: Clone```を実行する。

1. repository urlの入力<br/>
repositoryの先の問合せがあるので、GitHubよりgit repositoryのurlをコピーしペーストし実行する。

1. ログイン関係の許可（Webサイト）<br/>
gitとvs codeの認証の問い合わせがあるが「許可」を行なう。

1. フォルダ指定（Visual Studio Code）<br/>
プロジェクトフォルダを作成する位置の問合せがあるので、配置したいフォルダを指定します。

1. クローン終了後（Visual Studio Code）<br/>
「開く」を選択してください。

### ローカルブランチの作成
1. 現在の選択しているブランチの確認

1. コマンド実行（Visual Studio Code）<br/>
「コマンドパレット」 `git: Create Branch`

1. ブランチ名の入力（Visual Studio Code）
`fearture/swg1-修正`


### ローカルブランチに対するコミット
1. ソース修正（Visual Studio Code）

1. git コミット（ローカルのみ）（Visual Studio Code）


### リモートブランチへの発行
1. git push（リモートサーバ反映）（Visual Studio Code）


### Pull Request作成（webサイト）
* 
* 

### Pull Requestのマージ（webサイト）
* 
* 


## 各操作に関する権限テーブル

|ブランチ \ チーム名|SWG-Leader|SWG-Editor|SWG-Member|
|:---|:---:|:---:|:---:|
|feartureブランチ作成|○|○|○|
|feartureブランチに対するプッシュ|○|○|○|
|developブランチに対するPull Request発行|○|○|○|
|developブランチに対するPull Requestクローズ|○|○|○|
|developブランチに対するプッシュ|○|✕|✕|
|developブランチに対するPull Requestマージ|○|○|✕|
|mainブランチに対するPull request発行|○|○|✕|
|mainブランチに対するPull Requestクローズ|○|○|✕|
|mainブランチに対するプッシュ|○|✕|✕|
|mainブランチに対するPull Requestマージ|○|✕|✕|