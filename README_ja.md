# Kubernetes 30日チャレンジ

**言語:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ja/courses/30-days-of-kubernetes-challenges">
    <img src="https://course-cover.labex.io/30-days-of-kubernetes-challenges.png?lang=ja" alt="Kubernetes 30日チャレンジ">
  </a>
</p>

CKA、CKAD、CKS の模擬試験タスクから選んだ 30 日間の Kubernetes チャレンジです。アプリ運用からクラスタ管理、トラブルシューティング、セキュリティへ進みます。

[LabEx でコースを開始](https://labex.io/ja/courses/30-days-of-kubernetes-challenges)

## 演習

|   インデックス | 名前                                             | 難易度   | 練習                                                                                                                                                                 |
|----------|------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | ローカルアプリケーションイメージのビルドと実行                        | 中級    | <a target='_blank' href='https://labex.io/ja/labs/build-and-run-a-local-application-image-663095?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>             |
|       02 | スケジュールされたクリーンアップ CronJob の作成                   | 中級    | <a target='_blank' href='https://labex.io/ja/labs/create-a-scheduled-cleanup-cronjob-663098?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                  |
|       03 | Init コンテナとサイドカーコンテナの追加                         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/add-init-and-sidecar-containers-663093?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                     |
|       04 | ConfigMap と Secret の注入                         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/inject-configmaps-and-secrets-663105?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                       |
|       05 | Service を使用した Deployment の公開                   | 中級    | <a target='_blank' href='https://labex.io/ja/labs/expose-a-deployment-with-a-service-663102?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                  |
|       06 | 安全なローリングアップデートの実行                              | 中級    | <a target='_blank' href='https://labex.io/ja/labs/perform-a-safe-rolling-update-663106?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                       |
|       07 | ヘルスプローブの設定                                     | 中級    | <a target='_blank' href='https://labex.io/ja/labs/configure-health-probes-663096?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                             |
|       08 | CrashLooping アプリケーションのデバッグ                     | 中級    | <a target='_blank' href='https://labex.io/ja/labs/debug-a-crashlooping-application-663100?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                    |
|       09 | リソースリクエストとクォータの適用                              | 中級    | <a target='_blank' href='https://labex.io/ja/labs/apply-resource-requests-and-quotas-663094?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                  |
|       10 | エフェメラルボリュームと永続ボリュームの使用                         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/use-ephemeral-and-persistent-volumes-663112?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                |
|       11 | PersistentVolumeClaim を使用したアプリケーションデータのマウント    | 中級    | <a target='_blank' href='https://labex.io/ja/labs/mount-application-data-with-a-persistentvolumeclaim-663017?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a> |
|       12 | RBAC を使用したネームスペースオペレーター権限の付与                   | 中級    | <a target='_blank' href='https://labex.io/ja/labs/grant-namespace-operator-permissions-with-rbac-663016?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>      |
|       13 | テイント（Taint）が設定されたノードへの Pending 状態の Pod のスケジュール | 中級    | <a target='_blank' href='https://labex.io/ja/labs/schedule-pending-pods-on-a-tainted-node-663026?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>             |
|       14 | ノードの安全なドレインと復旧                                 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/safely-drain-and-restore-a-node-663025?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                     |
|       15 | etcd スナップショットバックアップの作成                         | 上級    | <a target='_blank' href='https://labex.io/ja/labs/create-an-etcd-snapshot-backup-663010?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                      |
|       16 | アーカイブデータ用の静的 PersistentVolume のバインド            | 中級    | <a target='_blank' href='https://labex.io/ja/labs/bind-a-static-persistentvolume-for-archive-data-663007?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>     |
|       17 | 停止したサービスへのトラフィック復旧                             | 中級    | <a target='_blank' href='https://labex.io/ja/labs/restore-traffic-to-a-broken-service-663022?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                 |
|       18 | Ingress を使用した HTTP トラフィックのルーティング               | 中級    | <a target='_blank' href='https://labex.io/ja/labs/route-http-traffic-with-ingress-663024?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                     |
|       19 | 名前空間間の NetworkPolicy アクセスを修復する                 | 上級    | <a target='_blank' href='https://labex.io/ja/labs/repair-networkpolicy-access-between-namespaces-663021?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>      |
|       20 | CoreDNS 名前解決の復旧                                | 上級    | <a target='_blank' href='https://labex.io/ja/labs/restore-coredns-name-resolution-663023?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                     |
|       21 | 失敗したデプロイメントのロールアウトを復旧する                        | 中級    | <a target='_blank' href='https://labex.io/ja/labs/recover-a-failing-deployment-rollout-663020?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                |
|       22 | クラスターリソース負荷の診断                                 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/diagnose-cluster-resource-pressure-663013?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                  |
|       23 | 壊れた kubelet イメージプルパスの修復                        | 中級    | <a target='_blank' href='https://labex.io/ja/labs/repair-a-broken-kubelet-image-pull-path-663040?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>             |
|       24 | クラッシュする静的 Pod マニフェストの復元                        | 上級    | <a target='_blank' href='https://labex.io/ja/labs/restore-a-crashing-static-pod-manifest-663043?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>              |
|       25 | メトリクスベースのスケーリングシグナルの復旧                         | 上級    | <a target='_blank' href='https://labex.io/ja/labs/recover-metrics-based-scaling-signals-663039?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>               |
|       26 | NetworkPolicy を使用した名前空間トラフィックの制限               | 中級    | <a target='_blank' href='https://labex.io/ja/labs/restrict-namespace-traffic-with-networkpolicy-663191?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>       |
|       27 | 過剰な権限を持つ ClusterRoleBinding の削減                | 中級    | <a target='_blank' href='https://labex.io/ja/labs/reduce-an-overprivileged-clusterrolebinding-663190?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>         |
|       28 | デフォルトの ServiceAccount トークンマウントの無効化             | 中級    | <a target='_blank' href='https://labex.io/ja/labs/disable-default-serviceaccount-token-mounts-663178?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>         |
|       29 | 制限付き Pod セキュリティの強制                             | 中級    | <a target='_blank' href='https://labex.io/ja/labs/enforce-restricted-pod-security-663181?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                     |
|       30 | 最小限の承認済みイメージの構築                                | 中級    | <a target='_blank' href='https://labex.io/ja/labs/build-a-minimal-approved-image-663176?course=30-days-of-kubernetes-challenges'>チャレンジを開始</a>                      |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

