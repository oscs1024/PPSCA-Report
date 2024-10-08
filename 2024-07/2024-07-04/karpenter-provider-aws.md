# aws/karpenter-provider-aws安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1808566488717590528.svg)](https://www.murphysec.com/console/report/1735003060270223360/1808566488717590528)

> 点击徽章可查看详细项目安全报告

仓库描述：Karpenter is a Kubernetes Node Autoscaler built for flexibility, performance, and simplicity.

仓库地址：[https://github.com/aws/karpenter-provider-aws](https://github.com/aws/karpenter-provider-aws)

| star：6155 | watch：78 | fork：849 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-07-04 01:36:55 | 许可证：Apache-2.0 |
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
|ISC|2|Low|
|MIT|32|Low|
|Apache-2.0|91|Low|
|BSD-3-Clause|22|Low|
|BSD-2-Clause|2|Low|
|MPL-2.0|1|Low|
|LGPL-3.0-only|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/blendle/zapdriver|v1.3.1|间接依赖|go|
|github.com/gobuffalo/flect|v1.0.2|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.23.0|直接依赖|go|
|k8s.io/klog/v2|v2.130.1|直接依赖|go|
|github.com/awslabs/operatorpkg|v0.0.0-20240701195752-116cbcffbcb4|直接依赖|go|
|sigs.k8s.io/yaml|v1.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.8.0|间接依赖|go|
|golang.org/x/term|v0.20.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/go-openapi/swag|v0.22.4|间接依赖|go|
|google.golang.org/protobuf|v1.33.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.11.2|间接依赖|go|
|github.com/awslabs/operatorpkg|v0.0.0-20240605172541-88cf99023fa4|间接依赖|go|
|github.com/patrickmn/go-cache|v2.1.0+incompatible|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.6.5|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.7.0|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.20.0|间接依赖|go|
|github.com/pelletier/go-toml/v2|v2.2.2|直接依赖|go|
|github.com/Masterminds/semver/v3|v3.2.1|直接依赖|go|
|github.com/avast/retry-go|v3.0.0+incompatible|直接依赖|go|
|k8s.io/apiextensions-apiserver|v0.30.2|直接依赖|go|
|k8s.io/api|v0.30.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.5.2|间接依赖|go|
|github.com/google/gnostic-models|v0.6.8|间接依赖|go|
|github.com/google/docsy/dependencies|v0.6.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.19.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.2.2|间接依赖|go|
|golang.org/x/sync|v0.7.0|直接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/olekukonko/tablewriter|v0.0.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudformation|v1.50.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/iam|v1.32.0|直接依赖|go|
|github.com/spf13/cobra|v1.6.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.11.7|间接依赖|go|
|github.com/go-logr/zapr|v1.3.0|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|直接依赖|go|
|knative.dev/pkg|v0.0.0-20231010144348-ca8c009405dd|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/timestreamwrite|v1.25.5|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.11.0|间接依赖|go|
|contrib.go.opencensus.io/exporter/ocagent|v0.7.1-0.20200907061046-05415f1de66d|间接依赖|go|
|github.com/google/pprof|v0.0.0-20240424215950-a892ee059fd6|间接依赖|go|
|sigs.k8s.io/karpenter|v0.37.1-0.20240605225346-c7c5068db687|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20231009173412-8bfb1ae86b6c|间接依赖|go|
|github.com/prometheus/statsd_exporter|v0.24.0|间接依赖|go|
|golang.org/x/text|v0.16.0|间接依赖|go|
|github.com/go-task/slim-sprig/v3|v3.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.16.1|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/google/go-cmp|v0.6.0|间接依赖|go|
|github.com/grpc-ecosystem/grpc-gateway/v2|v2.18.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.26.1|直接依赖|go|
|golang.org/x/text|v0.15.0|间接依赖|go|
|k8s.io/component-base|v0.30.2|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.17.11|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.3.5|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/evanphx/json-patch|v5.7.0+incompatible|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/prometheus/client_model|v0.6.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.23.4|间接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/eks|v1.32.0|直接依赖|go|
|github.com/aws/smithy-go|v1.16.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20231006140011-7918f672742d|间接依赖|go|
|github.com/rivo/uniseg|v0.4.4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/endpoint-discovery|v1.9.6|间接依赖|go|
|sigs.k8s.io/controller-runtime|v0.18.3|直接依赖|go|
|golang.org/x/exp|v0.0.0-20240416160154-fe59bbe5cc7f|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.9|间接依赖|go|
|k8s.io/api|v0.30.0|直接依赖|go|
|k8s.io/apimachinery|v0.30.1|间接依赖|go|
|k8s.io/api|v0.30.1|直接依赖|go|
|github.com/samber/lo|v1.39.0|直接依赖|go|
|sigs.k8s.io/controller-runtime|v0.18.4|直接依赖|go|
|k8s.io/client-go|v0.30.2|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/prometheus/procfs|v0.12.0|间接依赖|go|
|github.com/census-instrumentation/opencensus-proto|v0.4.1|间接依赖|go|
|go.uber.org/zap|v1.27.0|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|contrib.go.opencensus.io/exporter/prometheus|v0.4.2|间接依赖|go|
|k8s.io/csi-translation-lib|v0.30.1|间接依赖|go|
|golang.org/x/time|v0.5.0|间接依赖|go|
|golang.org/x/net|v0.25.0|间接依赖|go|
|google.golang.org/api|v0.146.0|间接依赖|go|
|github.com/aws/smithy-go|v1.20.2|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/google/docsy|v0.6.0|间接依赖|go|
|google.golang.org/appengine|v1.6.8|间接依赖|go|
|github.com/aws/karpenter-provider-aws|v0.37.1-0.20240607201537-69a807081c7f|直接依赖|go|
|golang.org/x/net|v0.24.0|间接依赖|go|
|golang.org/x/tools|v0.21.1-0.20240508182429-e35e4ccd0d2d|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.160.0|直接依赖|go|
|github.com/samber/lo|v1.44.0|直接依赖|go|
|github.com/hashicorp/golang-lru|v1.0.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.17.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.27.11|直接依赖|go|
|sigs.k8s.io/karpenter|v0.37.1-0.20240629051434-89a81c3ae853|直接依赖|go|
|k8s.io/utils|v0.0.0-20240102154912-e7106e64919e|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.28.6|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/aws/aws-sdk-go|v1.53.14|间接依赖|go|
|github.com/awslabs/amazon-eks-ami/nodeadm|v0.0.0-20240229193347-cfab22a10647|直接依赖|go|
|k8s.io/klog/v2|v2.120.1|间接依赖|go|
|go.uber.org/multierr|v1.11.0|直接依赖|go|
|github.com/kelseyhightower/envconfig|v1.4.0|间接依赖|go|
|github.com/spf13/cobra|v1.8.0|间接依赖|go|
|go.uber.org/automaxprocs|v1.5.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.14.3|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|k8s.io/csi-translation-lib|v0.30.2|间接依赖|go|
|golang.org/x/oauth2|v0.18.0|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.30.1|间接依赖|go|
|github.com/go-logr/logr|v1.4.2|间接依赖|go|
|github.com/PuerkitoBio/goquery|v1.9.2|直接依赖|go|
|gomodules.xyz/jsonpatch/v2|v2.4.0|间接依赖|go|
|k8s.io/apimachinery|v0.30.2|直接依赖|go|
|k8s.io/component-base|v0.30.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.10.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.22.2|间接依赖|go|
|PyGithub|1.55|间接依赖|pip|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/andybalholm/cascadia|v1.3.2|间接依赖|go|
|github.com/mitchellh/hashstructure/v2|v2.0.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.25.1|间接依赖|go|
|github.com/samber/lo|v1.38.1|直接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/go-kit/log|v0.2.1|间接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/go-logr/logr|v1.4.1|间接依赖|go|
|github.com/onsi/gomega|v1.33.1|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.15|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.15.2|间接依赖|go|
|google.golang.org/grpc|v1.58.3|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/imdario/mergo|v0.3.16|直接依赖|go|
|k8s.io/cloud-provider|v0.30.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.6.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.4.1|间接依赖|go|
|k8s.io/utils|v0.0.0-20240502163921-fe8a2dddb1d0|间接依赖|go|
|k8s.io/apimachinery|v0.30.0|间接依赖|go|
|github.com/robfig/cron/v3|v3.0.1|间接依赖|go|
|golang.org/x/sys|v0.20.0|间接依赖|go|
|golang.org/x/exp|v0.0.0-20220303212507-bbda1eaf7a17|间接依赖|go|
|github.com/evanphx/json-patch/v5|v5.9.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20240228011516-70dd3763d340|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.20.5|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|k8s.io/client-go|v0.30.1|直接依赖|go|
|github.com/aws/aws-sdk-go|v1.54.11|直接依赖|go|
|github.com/aws/aws-sdk-go|v1.47.9|直接依赖|go|
|github.com/prometheus/common|v0.53.0|间接依赖|go|
|github.com/blang/semver/v4|v4.0.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/aws/karpenter-provider-aws/tools/kompat|v0.0.0-20240410220356-6b868db24881|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/google/uuid|v1.6.0|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20231009173412-8bfb1ae86b6c|间接依赖|go|
|github.com/golang/protobuf|v1.5.4|间接依赖|go|
|github.com/jonathan-innis/aws-sdk-go-prometheus|v0.1.0|直接依赖|go|
|github.com/Pallinder/go-randomdata|v1.2.0|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.6.0|间接依赖|go|
|k8s.io/cloud-provider|v0.30.1|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.19.0|直接依赖|go|
|google.golang.org/genproto/googleapis/api|v0.0.0-20231009173412-8bfb1ae86b6c|间接依赖|go|
|github.com/prometheus/client_golang|v1.19.1|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)