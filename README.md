# くりまんじゅう Notionマスコット

## ファイル
- `index.html`: ウィジェット本体
- `assets/normal.gif`: 通常時（常時表示）
- `assets/drink.gif`: クリック反応・飲酒
- `assets/hangover.gif`: クリック反応・二日酔い
- `assets/charge.gif`: クリック反応・ため攻撃

## GitHub Pagesで公開してNotionに埋め込む
1. GitHubで新しいリポジトリを作成する（Public推奨）。
2. `index.html` と `assets` フォルダをリポジトリ直下にアップロードする。ZIPファイル自体をアップロードするだけでは動かないので、必ず展開した中身をアップロードしてください。
3. リポジトリの Settings → Pages → Build and deployment で `Deploy from a branch` を選ぶ。
4. Branchを `main`、フォルダを `/(root)` にして Save。
5. 公開された `https://ユーザー名.github.io/リポジトリ名/` を開いて動作確認。
6. Notionで `/embed` と入力し、公開URLを貼り付ける。

## 動作
通常GIFを表示し、クリックするたびに「飲酒」「二日酔い」「ため攻撃」のいずれかをランダム再生します。リアクション中の連続クリックは無効になり、アニメーション終了後に通常GIFへ戻ります。GIFの表示時間は素材のフレーム時間を参考に設定しています。
