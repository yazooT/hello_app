# README

## 躓いたところ

ファイルの変更が反映されない
そもそもCloud9のIDEがオートセーブだと勘違いしていた。

bundle installでエラーが起こる
bundle updateで何故か動くようになった。

git pushでエラー
Permission denied (publickey). fatal: Could not read from remote repository.
git remoteがSSHとやらになっていた。
これの設定がよくわからないため、git remoteをHTTPSに変更した。