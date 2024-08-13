# kubernetes-sigs/karpenter安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1823423113856724992.svg)](https://www.murphysec.com/console/report/1728116123712839680/1823423113856724992)

> 点击徽章可查看详细项目安全报告

仓库描述：Karpenter is a Kubernetes Node Autoscaler built for flexibility, performance, and simplicity.

仓库地址：[https://github.com/kubernetes-sigs/karpenter](https://github.com/kubernetes-sigs/karpenter)

| star：479 | watch：24 | fork：165 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-08-13 20:06:33 | 许可证：Apache-2.0 |
| 最近检测时间： | 组件总数： | 漏洞总数： |




## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |





## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |





## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|41|Low|
|ISC|2|Low|
|BSD-3-Clause|19|Low|
|MIT|23|Low|
|BSD-2-Clause|1|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|k8s.io/api|v0.30.3|直接依赖|go|
|k8s.io/apiextensions-apiserver|v0.30.3|直接依赖|go|
|k8s.io/utils|v0.0.0-20240102154912-e7106e64919e|直接依赖|go|
|github.com/blendle/zapdriver|v1.3.1|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/mitchellh/hashstructure/v2|v2.0.2|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|直接依赖|go|
|golang.org/x/sync|v0.8.0|直接依赖|go|
|github.com/prometheus/common|v0.53.0|间接依赖|go|
|k8s.io/klog/v2|v2.130.1|直接依赖|go|
|golang.org/x/tools|v0.24.0|间接依赖|go|
|golang.org/x/net|v0.28.0|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/avast/retry-go|v3.0.0+incompatible|直接依赖|go|
|github.com/go-logr/zapr|v1.3.0|直接依赖|go|
|github.com/go-logr/logr|v1.4.2|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|github.com/prometheus/statsd_exporter|v0.21.0|间接依赖|go|
|github.com/google/pprof|v0.0.0-20240727154555-813a5fbdbec8|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/awslabs/operatorpkg|v0.0.0-20240805231134-67d0acfb6306|直接依赖|go|
|github.com/prometheus/client_model|v0.6.1|直接依赖|go|
|go.uber.org/automaxprocs|v1.4.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/google/go-cmp|v0.6.0|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|knative.dev/pkg|v0.0.0-20230712131115-7051d301e7f4|直接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230822172742-b8732ec3820d|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.4.1|间接依赖|go|
|google.golang.org/protobuf|v1.34.1|间接依赖|go|
|github.com/spf13/cobra|v1.7.0|间接依赖|go|
|github.com/onsi/gomega|v1.34.1|直接依赖|go|
|github.com/go-task/slim-sprig/v3|v3.0.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20240719175910-8a7402abbf56|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/google/gnostic-models|v0.6.8|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.9.0|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/imdario/mergo|v0.3.16|直接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.16.0|间接依赖|go|
|go.uber.org/atomic|v1.10.0|间接依赖|go|
|k8s.io/csi-translation-lib|v0.30.3|直接依赖|go|
|k8s.io/client-go|v0.30.3|直接依赖|go|
|contrib.go.opencensus.io/exporter/prometheus|v0.4.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|sigs.k8s.io/yaml|v1.4.0|间接依赖|go|
|golang.org/x/time|v0.6.0|直接依赖|go|
|github.com/google/uuid|v1.6.0|间接依赖|go|
|golang.org/x/text|v0.17.0|直接依赖|go|
|github.com/kelseyhightower/envconfig|v1.4.0|间接依赖|go|
|github.com/go-kit/log|v0.2.1|间接依赖|go|
|google.golang.org/api|v0.124.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20240228011516-70dd3763d340|间接依赖|go|
|go.uber.org/zap|v1.27.0|直接依赖|go|
|k8s.io/component-base|v0.30.3|直接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|k8s.io/apimachinery|v0.30.3|直接依赖|go|
|k8s.io/cloud-provider|v0.30.3|直接依赖|go|
|go.uber.org/multierr|v1.11.0|直接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|间接依赖|go|
|github.com/prometheus/procfs|v0.12.0|间接依赖|go|
|golang.org/x/oauth2|v0.18.0|间接依赖|go|
|google.golang.org/grpc|v1.58.3|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/docker/docker|v27.1.1+incompatible|直接依赖|go|
|github.com/census-instrumentation/opencensus-proto|v0.4.1|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|github.com/hashicorp/golang-lru|v0.5.4|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|golang.org/x/term|v0.23.0|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.20.0|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20230726155614-23370e0ffb3e|间接依赖|go|
|github.com/golang/protobuf|v1.5.4|间接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.4.0|间接依赖|go|
|github.com/Pallinder/go-randomdata|v1.2.0|直接依赖|go|
|github.com/fsnotify/fsnotify|v1.7.0|间接依赖|go|
|contrib.go.opencensus.io/exporter/ocagent|v0.7.1-0.20200907061046-05415f1de66d|间接依赖|go|
|github.com/prometheus/client_golang|v1.19.1|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.11.0|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.18.5|直接依赖|go|
|golang.org/x/sys|v0.23.0|间接依赖|go|
|github.com/samber/lo|v1.46.0|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)