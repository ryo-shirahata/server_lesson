# サーバレッスン
Linuxプラクティス
----------------

## ls (LiSt)
現在位置しているディレクトリ内に存在するディレクトリやファイルを一覧表示するコマンド

### 使用できるオプション
- -a
不可視ファイルも表示

- -l
タイプや権限、所有者や所有グループなどの詳細情報を表示

※オプションは -la といった形でまとめて指定することが可能


## pwd (Print Working Directory)
現在自分が位置しているディレクトリ = ワーキングディレクトリ がどこであるかを出力


## cd (Change Directory)
ワーキングディレクトリを指定したディレクトリに変更するコマンド

### 以下を指定で特定のディレクトリに移動することが可能
- ~
ホームディレクトリ

- /
ルートディレクトリ

- -
移動前に位置していたディレクトリ

- .
ワーキングディレクトリ

- ..
ワーキングディレクトリの一階層上のディレクトリ

- ../../
ワーキングディレクトリの二階層上のディレクトリ


## mkdir (MaKe DIRectory)
ディレクトリを作成するコマンド


## touch
ファイルを作成するコマンド


## cp (CoPy)
ファイルあるいはディレクトリのコピーを行うコマンド


## mv (MoVe)
mvはファイル名やディレクトリ名を変更する、またファイルやディレクトリの移動を行うコマンド


## rm (ReMove)
ファイルやディレクトリの削除を行うコマンド

※-f というオプションは削除実行の際に警告メッセージを表示せずに削除してしまう為、取り扱い注意