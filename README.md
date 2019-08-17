# Hello Mackerel k8s
Mackerel を k8s クラスタのそれぞれの Node にデプロイする設定です。

## 注意
公式ホームページから最新の情報を確認してください。
このレポジトリの内容は、2019年7月現在に公式レポジトリに記載されていた内容に沿ったものです。

## APIキー
mackerel.yaml 内の API キーを自分が Mackerel から発行されたものに置き換えてください。

## GKE でのテスト方法
```
  ./gke-cluster.sh
  kubectl -f mackeral.yaml
```
デプロイ後しばらくすると、Mackerel 上でモニタリングができるようになります。
