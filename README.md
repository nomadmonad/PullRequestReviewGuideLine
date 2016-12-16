# Summary
このリポジトリはPull Request Reviewのサンプルです。

# Description
積極的にPull Request Reviewを使っていきましょうという目的のために作成したサンプル用のリポジトリです。

## Merit
Pull Requestのレビュー時、レビュアーの意図やレビュー結果をわかりやすく示せます。

### レビューの結果をわかりやすく示せる
レビュー結果の判断を、"Request Changes"（要変更）・"Approved"（OK）の形で示すことができます。

Pull Request Reviewが導入される前は、コメントを読み進めないとレビューのOK/NGがわからない状態でした。
レビューコメントをひと通りつけ終わったあと、"Review Changes"から"Request Changes"・"Approved"のどちらかを指定すると、OK/NGのどちらかを示すことができます。

コメントだけ付けたいという場合でも、"Comment"という形でレビューについてのコメントを残すことができます。

### コメント形式で対話しやすい
Pull Request Review形式で進めると、指摘に対してコメントを返せるようになるので、後で見返した時にどう対応したのか追いやすくできます。

Pull Request ReviewはSingle Commentとは違い、指摘された箇所と対応について、コメント形式でのやり取りを示せます。
導入される前、レビュアーはSingle Comment形式で指摘することが多かったと思います。
この形式は簡単ですが、コメントに対してコメントを付けることができないので、対話が必要な場合は解りづらくることがありました。
