TODO
- [x] モック画面の作成
- [x] とりあえずstaticなpathでいいから jscpd を実行して値をパースして一覧画面に飛ばす
  - パース結果はメモリに保持しておく
- [x] 一覧画面でそれを受け取り、リスト表示する
- [x] 詳細画面に遷移する
  - 遷移時にメモリに保持しておいたパース結果をID or indexでサーチして渡す
- [x] ChatGPTをコールしてマークダウンとして表示する
- [x] diffを表示する -> 一旦できたが使いずらいのでモナコを使う
- [x] 節約できるコードのポテンシャルは重複コードの行数とイコールで良い（アバウトでOK）
  - 一覧画面上ではポテンシャルセーブで並び替えするべき
- [x] clocと組み合わせると良さそう
  - 全体を把握するのに役に立つ
  - プロジェクト全体の行数と重複コードの行数を比較すると良さそう
  - 増えた減ったが後から追えると見える化ができて良さそう
- [x] 複数(2つ)の調査対象に対応する
- [ ] How it works とかHow to useの説明を README, ページに書きたい
- [ ] watchで指定しているディレクトリが更新されたら診断を再実行する
- [ ] カスタマイズ系
  - Open AIのトークンを設定できるようにする(ローカルストレージ)
  - jscpdのオプションをカスタマイズできるよにする
  - ChatGPTのプロンプトをカスタマイズできるようにする
- [ ] npx で起動してローカルでサーバーが立ち上がる(インストール不要)
- [ ] FIXMEを直す
- [ ] betaリリース
- [ ] ts-prune を使う
- clocをスナップショットを撮れるようにする？