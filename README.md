# Hello Mackerel k8s
Mackerel を k8s クラスタのそれぞれの Node にデプロイする設定です。

## APIキー
mackerel.yaml 内の API キーを自分が Mackerel から発行されたものに置き換えてください。

## GKE でのテスト方法
```
  ./gke-cluster.sh
  kubectl -f mackeral.yaml
```
デプロイ後しばらくすると、Mackerel 上でモニタリングができるようになります。
