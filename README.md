# my_original_catalog
Rancher catalog for myself

# 使い方

## MySQL Asynchrouns Replication

現時点では何も考えずに起動すればなんとか動く。

masterのサイドキックコンテナ(master-sidekick)の処理でレプリケーション
ユーザの設定に失敗していることがあるので、その時は master-sidekickコンテナをサイド動かす。

### 注意
現時点ではMySQLのコンテナのIPアドレスにmasterは10.42.2.10、slaveは10.42.2.11を
ハードコーディングしているのでそのIPアドレスが空いていないと即死。