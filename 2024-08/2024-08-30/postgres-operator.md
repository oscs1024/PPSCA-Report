# zalando/postgres-operator安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1829225207770025984.svg)](https://www.murphysec.com/console/report/1742993186638041088/1829225207770025984)

> 点击徽章可查看详细项目安全报告

仓库描述：Postgres operator creates and manages PostgreSQL clusters running in Kubernetes

仓库地址：[https://github.com/zalando/postgres-operator](https://github.com/zalando/postgres-operator)

| star：4208 | watch：65 | fork：965 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-08-28 21:26:13 | 许可证：MIT |
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
|Unlicense|1|Low|
|BSD-3-Clause|11|Low|
|MIT|18|Low|
|Apache-2.0|20|Low|
|BSD-2-Clause|6|Low|
|ISC|2|Low|
|MPL-2.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|client||间接依赖|pip|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|furl|2.1.3|间接依赖|pip|
|k8s.io/client-go|v0.30.4|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.11.0|间接依赖|go|
|github.com/sagikazarmark/slog-shim|v0.1.0|间接依赖|go|
|github.com/lib/pq|v1.10.9|直接依赖|go|
|github.com/spf13/afero|v1.11.0|间接依赖|go|
|github.com/mxk/go-flowrate|v0.0.0-20140419014527-cca7078d478f|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|golang.org/x/tools|v0.21.1-0.20240508182429-e35e4ccd0d2d|间接依赖|go|
|config||间接依赖|pip|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|间接依赖|go|
|golang.org/x/sys|v0.23.0|间接依赖|go|
|wal_e|1.1.1|间接依赖|pip|
|boto3|1.34.110|间接依赖|pip|
|golang.org/x/exp|v0.0.0-20240112132812-db7319d0e0e3|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|k8s.io/utils|v0.0.0-20230726121419-3b25d923346b|间接依赖|go|
|golang.org/x/time|v0.3.0|间接依赖|go|
|expo||间接依赖|pip|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/stretchr/testify|v1.9.0|直接依赖|go|
|python-json-logger|2.0.7|间接依赖|pip|
|github.com/fsnotify/fsnotify|v1.7.0|间接依赖|go|
|github.com/zalando/postgres-operator|v1.13.0|直接依赖|go|
|k8s.io/apiextensions-apiserver|v0.25.9|直接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|google.golang.org/appengine|v1.6.8|间接依赖|go|
|github.com/spf13/viper|v1.19.0|直接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.6|间接依赖|go|
|requirements.txt||间接依赖|pip|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/spf13/cast|v1.6.0|间接依赖|go|
|kubernetes|11.0.0|间接依赖|pip|
|golang.org/x/mod|v0.17.0|间接依赖|go|
|timeout_decorator|0.5.0|间接依赖|pip|
|golang.org/x/oauth2|v0.10.0|间接依赖|go|
|golang.org/x/time|v0.5.0|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|golang.org/x/crypto|v0.26.0|直接依赖|go|
|go.uber.org/multierr|v1.11.0|间接依赖|go|
|gevent|24.2.1|间接依赖|pip|
|github.com/pelletier/go-toml/v2|v2.2.2|间接依赖|go|
|github.com/go-openapi/swag|v0.22.3|间接依赖|go|
|setup||间接依赖|pip|
|golang.org/x/text|v0.17.0|间接依赖|go|
|k8s.io/gengo|v0.0.0-20220902162205-c0856e24416d|间接依赖|go|
|golang.org/x/oauth2|v0.18.0|间接依赖|go|
|gopkg.in/ini.v1|v1.67.0|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.2-0.20180830191138-d8f796af33cc|间接依赖|go|
|github.com/r3labs/diff|v1.1.0|直接依赖|go|
|k8s.io/apimachinery|v0.30.4|直接依赖|go|
|google.golang.org/protobuf|v1.33.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|k8s.io/code-generator|v0.25.9|直接依赖|go|
|github.com/sagikazarmark/locafero|v0.4.0|间接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/golang/protobuf|v1.5.4|间接依赖|go|
|kubernetes|29.2.0|间接依赖|pip|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/google/go-cmp|v0.6.0|间接依赖|go|
|golang.org/x/sync|v0.8.0|间接依赖|go|
|github.com/subosito/gotenv|v1.6.0|间接依赖|go|
|Flask|3.0.3|间接依赖|pip|
|boto|2.49.0|间接依赖|pip|
|click|8.1.7|间接依赖|pip|
|find_packages||间接依赖|pip|
|github.com/imdario/mergo|v0.3.6|间接依赖|go|
|k8s.io/api|v0.30.4|直接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|k8s.io/gengo/v2|v2.0.0-20240228010128-51d4e06bde70|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/sourcegraph/conc|v0.3.0|间接依赖|go|
|date||间接依赖|pip|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20240228011516-70dd3763d340|间接依赖|go|
|pyyaml|6.0.1|间接依赖|pip|
|sigs.k8s.io/structured-merge-diff/v4|v4.4.1|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|k8s.io/klog/v2|v2.120.1|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/hashicorp/hcl|v1.0.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|golang.org/x/term|v0.23.0|间接依赖|go|
|backoff|2.2.1|间接依赖|pip|
|github.com/evanphx/json-patch|v4.12.0+incompatible|间接依赖|go|
|github.com/spf13/cobra|v1.8.1|直接依赖|go|
|werkzeug|3.0.3|间接依赖|pip|
|golang.org/x/net|v0.25.0|间接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/google/uuid|v1.4.0|间接依赖|go|
|github.com/motomux/pretty|v0.0.0-20161209205251-b2aad2c9a95d|直接依赖|go|
|github.com/google/gnostic-models|v0.6.8|间接依赖|go|
|github.com/magiconair/properties|v1.8.7|间接依赖|go|
|requests|2.32.2|间接依赖|pip|
|github.com/go-logr/logr|v1.4.1|间接依赖|go|
|random_jitter||间接依赖|pip|
|stups-tokens|1.1.19|间接依赖|pip|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.53.8|直接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|jq|1.7.0|间接依赖|pip|
|json_delta|2.0.2|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)