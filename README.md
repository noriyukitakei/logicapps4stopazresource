## 使ってないAzureリソースを停止するLogic Apps
こちらは使ってないAzureリソースを停止するLogic AppのARM Templateになります。

以下の機能があります。


- 起動しているVirtual Machineの割り当て解除
- 起動しているAzure Database  for MySQLの停止
- 特定のタグ(名前:deallocate、値:false)がついているリソースは停止対象外


詳細は以下のブログをご覧下さい。機能の詳細や利用方法などの記載があります。

https://tech-lab.sios.jp/archives/29525
