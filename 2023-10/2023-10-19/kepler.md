# sustainable-computing-io/kepler安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1714709835819909120.svg)](https://www.murphysec.com/console/report/1714709835488559104/1714709835819909120)

> 点击徽章可查看详细项目安全报告

仓库描述：Kepler (Kubernetes-based Efficient Power Level Exporter) uses eBPF to probe performance counters and other system stats, use ML models to estimate workload energy consumption based on these stats, and exports them as Prometheus metrics

仓库地址：[https://github.com/sustainable-computing-io/kepler](https://github.com/sustainable-computing-io/kepler)

| star：704 | watch：21 | fork：114 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-10-19 02:14:06 | 许可证：Apache-2.0 |
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
|Apache-2.0|38|Low|
|BSD-3-Clause|22|Low|
|MIT|20|Low|
|BSD-2-Clause-Views|1|Low|
|ISC|1|Low|
|GPL-2.0|1|Medium|
|BSD-2-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|golang.org/x/term|v0.13.0|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|howett.net/plist|v1.0.0|间接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|k8s.io/klog/v2|v2.80.0|直接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.4.0|间接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|间接依赖|go|
|github.com/jszwec/csvutil|v1.8.0|直接依赖|go|
|github.com/prometheus/common|v0.44.0|直接依赖|go|
|github.com/google/pprof|v0.0.0-20221102093814-76f304f74e5e|间接依赖|go|
|github.com/aquasecurity/libbpfgo|v0.4.9-libbpf-1.2.0|直接依赖|go|
|github.com/imdario/mergo|v0.3.12|间接依赖|go|
|golang.org/x/net|v0.17.0|间接依赖|go|
|github.com/emicklei/go-restful/v3|v3.8.0|间接依赖|go|
|github.com/containerd/cgroups/v3|v3.0.2|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/prometheus/client_model|v0.5.0|直接依赖|go|
|github.com/jaypipes/pcidb|v1.0.0|间接依赖|go|
|github.com/grafana/regexp|v0.0.0-20221005093135-b4c2bcb0a4b6|间接依赖|go|
|github.com/moby/sys/mountinfo|v0.5.0|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/PuerkitoBio/purell|v1.1.1|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.1.0|直接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|k8s.io/utils|v0.0.0-20220728103510-ee6ede2d64ed|间接依赖|go|
|github.com/containerd/cgroups|v1.1.0|直接依赖|go|
|github.com/google/gofuzz|v1.2.0|间接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20220803162953-67bda5d908f1|间接依赖|go|
|github.com/iovisor/gobpf|v0.2.1-0.20221005153822-16120a1bf4d4|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.19.6|间接依赖|go|
|k8s.io/client-go|v0.25.3|直接依赖|go|
|github.com/ghodss/yaml|v1.0.0|间接依赖|go|
|github.com/godbus/dbus/v5|v5.0.6|间接依赖|go|
|k8s.io/apimachinery|v0.25.3|直接依赖|go|
|github.com/docker/go-units|v0.5.0|间接依赖|go|
|github.com/onsi/gomega|v1.28.0|直接依赖|go|
|github.com/StackExchange/wmi|v1.2.1|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|golang.org/x/text|v0.13.0|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.13.0|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/go-ole/go-ole|v1.2.6|间接依赖|go|
|golang.org/x/tools|v0.12.0|间接依赖|go|
|golang.org/x/oauth2|v0.8.0|间接依赖|go|
|github.com/joho/godotenv|v1.5.1|直接依赖|go|
|golang.org/x/sys|v0.13.0|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/go-openapi/jsonpointer|v0.19.5|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|golang.org/x/time|v0.1.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/jaypipes/ghw|v0.12.0|直接依赖|go|
|github.com/prometheus/client_golang|v1.17.0|直接依赖|go|
|github.com/cilium/ebpf|v0.9.1|间接依赖|go|
|github.com/prometheus/procfs|v0.11.1|间接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/go-openapi/swag|v0.21.1|间接依赖|go|
|k8s.io/api|v0.25.3|直接依赖|go|
|github.com/NVIDIA/go-nvml|v0.11.6-0|直接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.4|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.4|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|google.golang.org/appengine|v1.6.7|间接依赖|go|
|sigs.k8s.io/json|v0.0.0-20220713155537-f223a00ba0e2|间接依赖|go|
|github.com/opencontainers/runc|v1.1.8|直接依赖|go|
|github.com/prometheus/prometheus|v0.40.3|直接依赖|go|
|github.com/PuerkitoBio/urlesc|v0.0.0-20170810143723-de5bf2ad4578|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)