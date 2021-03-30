# related-atom
ATOMエディタとの連携確認で使用したリポジトリ。

## 連携できた
ので、ここに記載した。

## どうやったか
1. AtomのGitHubタブにあるCloneは使用せず、MacのTerminalからCloneする。
2. CloneしたディレクトリをAtomで開く
3. Project内のファイルを編集(今回の場合はREADME.md)。
4. Gitタブを開いてUnstagedChangesからCommitしたいファイルをStagedChangesに移動。
5. CommitMessageを記載してCommit to xxx(選択中のブランチ)。
6. Pushを押す。

## この後の課題
* AtomのGitHubタブにあるCloneを使用できるようにしたい。
* 作成中にGit対象としたいプロジェクトになったとき、GitHubに空のプロジェクトを作ってそこに叩き込めるようにしたい。
