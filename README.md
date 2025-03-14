# fio test in Kubernetes

## ファイルの説明

fio-job-config.yaml
* fioパラメータをconfigMapとして作成

fio.yaml
* PersistentClaimVolumeの作成とfioを含むAlpine LinuxベースのPodをDeploymentで作成
* ログインの仕方：oc exec -it <pod_name> -- /bin/sh

centos.yaml
* CentOSベースの単純なLinux Pod (fioは含まず)
* ログインの仕方：oc exec -it <pod_name> -- /bin/bash
