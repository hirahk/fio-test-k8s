# fio test in Kubernetes

## ファイルの説明

fio-job-config.yaml
* fioパラメータをconfigMapとして作成

fio.yaml
* PersistentClaimVolumeの作成とfioを含むAlpine LinuxベースのPodをDeploymentで作成
