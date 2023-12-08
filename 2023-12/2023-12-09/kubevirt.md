# kubevirt/kubevirt安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1733191628799565824.svg)](https://www.murphysec.com/console/report/1692600804770205696/1733191628799565824)

> 点击徽章可查看详细项目安全报告

仓库描述：Kubernetes Virtualization API and runtime in order to define and manage virtual machines.

仓库地址：[https://github.com/kubevirt/kubevirt](https://github.com/kubevirt/kubevirt)

| star：4725 | watch：109 | fork：1125 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-12-09 00:23:53 | 许可证：Apache-2.0 |
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
|Apache-2.0|87|Low|
|MIT|44|Low|
|BSD-3-Clause|49|Low|
|BSD-2-Clause|5|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|k8s.io/utils|v0.0.0-20230726121419-3b25d923346b|直接依赖|go|
|github.com/c9s/goprocinfo|v0.0.0-20210130143923-c95fcf8c64a8|直接依赖|go|
|golang.org/x/term|v0.13.0|直接依赖|go|
|github.com/k8snetworkplumbingwg/network-attachment-definition-client|v0.0.0-20191119172530-79f836b90111|直接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/prometheus/procfs|v0.8.0|间接依赖|go|
|github.com/vishvananda/netlink|v1.1.1-0.20210330154013-f5de75959ad5|直接依赖|go|
|github.com/google/goexpect|v0.0.0-20190425035906-112704a48083|直接依赖|go|
|github.com/vishvananda/netns|v0.0.0-20210104183010-2eb08e3e575f|间接依赖|go|
|github.com/povsister/scp|v0.0.0-20210427074412-33febfd9f13e|直接依赖|go|
|k8s.io/api|v0.28.1|直接依赖|go|
|github.com/containers/common|v0.50.1|直接依赖|go|
|github.com/pkg/diff|v0.0.0-20190930165518-531926345625|间接依赖|go|
|github.com/insomniacslk/dhcp|v0.0.0-20230908212754-65c27093e38a|直接依赖|go|
|github.com/imdario/mergo|v0.3.15|间接依赖|go|
|github.com/fatih/color|v1.10.0|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.0.3-0.20210326190908-1c3f411f0417|间接依赖|go|
|github.com/cilium/ebpf|v0.7.0|间接依赖|go|
|golang.org/x/net|v0.17.0|直接依赖|go|
|github.com/moby/spdystream|v0.2.0|间接依赖|go|
|github.com/u-root/uio|v0.0.0-20230220225925-ffce2a382923|间接依赖|go|
|github.com/go-openapi/errors|v0.19.9|间接依赖|go|
|github.com/k8snetworkplumbingwg/network-attachment-definition-client|v1.3.0|直接依赖|go|
|github.com/VividCortex/ewma|v1.2.0|间接依赖|go|
|github.com/opencontainers/runc|v1.1.9|直接依赖|go|
|github.com/go-stack/stack|v1.8.0|间接依赖|go|
|golang.org/x/sync|v0.3.0|直接依赖|go|
|github.com/google/pprof|v0.0.0-20210720184732-4bb14d4b1be1|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.6.0|直接依赖|go|
|golang.org/x/tools|v0.13.0|直接依赖|go|
|github.com/kisielk/errcheck|v1.6.2|直接依赖|go|
|github.com/krolaw/dhcp4|v0.0.0-20180925202202-7cead472c414|直接依赖|go|
|github.com/blang/semver|v3.5.1+incompatible|直接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|直接依赖|go|
|github.com/go-logr/logr|v0.2.1|间接依赖|go|
|github.com/google/gofuzz|v1.1.0|间接依赖|go|
|github.com/google/gofuzz|v1.2.0|直接依赖|go|
|github.com/gordonklaus/ineffassign|v0.0.0-20210209182638-d0e41b2fc8ed|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.4.1|间接依赖|go|
|github.com/josharian/intern|v1.0.0|间接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230905202853-d090da108d2f|直接依赖|go|
|k8s.io/client-go|v12.0.0+incompatible|直接依赖|go|
|github.com/google/go-github/v32|v32.0.0|直接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|k8s.io/apiextensions-apiserver|v0.28.1|直接依赖|go|
|k8s.io/kube-openapi|v0.0.0-20230501164219-8b0f38b5fd1f|间接依赖|go|
|github.com/go-openapi/runtime|v0.19.24|间接依赖|go|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|gopkg.in/inf.v0|v0.9.1|间接依赖|go|
|github.com/googleapis/gnostic|v0.2.2|间接依赖|go|
|github.com/golang/protobuf|v1.5.3|直接依赖|go|
|github.com/modern-go/concurrent|v0.0.0-20180306012644-bacd9c7ef1dd|间接依赖|go|
|github.com/mitchellh/go-vnc|v0.0.0-20150629162542-723ed9867aed|直接依赖|go|
|github.com/mattn/go-runewidth|v0.0.13|间接依赖|go|
|golang.org/x/tools|v0.9.3|间接依赖|go|
|github.com/cheggaaa/pb/v3|v3.1.0|直接依赖|go|
|github.com/emicklei/go-restful|v2.6.1+incompatible|间接依赖|go|
|github.com/google/uuid|v1.3.0|间接依赖|go|
|github.com/golang/mock|v1.6.0|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.12|间接依赖|go|
|kubevirt.io/qe-tools|v0.1.8|直接依赖|go|
|github.com/operator-framework/operator-lifecycle-manager|v0.0.0-20190725173916-b56e63a643cc|直接依赖|go|
|google.golang.org/grpc|v1.56.3|直接依赖|go|
|github.com/mdlayher/vsock|v1.2.1|直接依赖|go|
|github.com/go-toolsmith/astcopy|v1.1.0|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|github.com/nxadm/tail|v1.4.8|直接依赖|go|
|github.com/wadey/gocovmerge|v0.0.0-20160331181800-b5bfa59ec0ad|直接依赖|go|
|github.com/mdlayher/socket|v0.4.1|间接依赖|go|
|github.com/go-openapi/validate|v0.20.2|直接依赖|go|
|github.com/nunnatsa/ginkgolinter|v0.14.0|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.2-0.20180830191138-d8f796af33cc|间接依赖|go|
|go.mongodb.org/mongo-driver|v1.8.4|间接依赖|go|
|github.com/moby/sys/mountinfo|v0.6.2|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/go-openapi/loads|v0.20.2|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|间接依赖|go|
|google.golang.org/genproto|v0.0.0-20230410155749-daa745c078e1|间接依赖|go|
|k8s.io/apimachinery|v0.27.1|直接依赖|go|
|github.com/go-kit/kit|v0.9.0|直接依赖|go|
|github.com/kubernetes-csi/external-snapshotter/client/v4|v4.2.0|直接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.3.0|间接依赖|go|
|github.com/openshift/custom-resource-status|v1.1.2|间接依赖|go|
|golang.org/x/crypto|v0.14.0|直接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.3|间接依赖|go|
|kubevirt.io/controller-lifecycle-operator-sdk/api|v0.0.0-20220329064328-f3cc58c6ed90|直接依赖|go|
|github.com/kubevirt/monitoring/pkg/metrics/parser|v0.0.0-20230627123556-81a891d4462a|直接依赖|go|
|github.com/openshift/api|v0.0.0|直接依赖|go|
|golang.org/x/crypto|v0.0.0-20220321153916-2c7772ba3064|间接依赖|go|
|github.com/matttproud/golang_protobuf_extensions|v1.0.2|间接依赖|go|
|github.com/google/uuid|v1.3.1|直接依赖|go|
|github.com/rogpeppe/go-internal|v1.11.0|间接依赖|go|
|github.com/mailru/easyjson|v0.7.7|间接依赖|go|
|github.com/pkg/errors|v0.9.1|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.0.1|间接依赖|go|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/opencontainers/selinux|v1.10.2|直接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/pborman/uuid|v1.2.1|直接依赖|go|
|github.com/go-openapi/spec|v0.20.3|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.8|间接依赖|go|
|k8s.io/apimachinery|v0.28.1|直接依赖|go|
|github.com/openshift/client-go|v0.0.0-20210112165513-ebc401615f47|直接依赖|go|
|github.com/openshift/client-go|v0.0.0|直接依赖|go|
|github.com/kr/logfmt|v0.0.0-20210122060352-19f9bcb100e6|间接依赖|go|
|golang.org/x/text|v0.13.0|间接依赖|go|
|github.com/asaskevich/govalidator|v0.0.0-20200907205600-7a23bdc65eef|间接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/evanphx/json-patch|v5.6.0+incompatible|直接依赖|go|
|github.com/go-openapi/jsonpointer|v0.20.0|间接依赖|go|
|github.com/json-iterator/go|v1.1.12|间接依赖|go|
|kubevirt.io/containerized-data-importer-api|v1.57.0-alpha1|直接依赖|go|
|sigs.k8s.io/json|v0.0.0-20221116044647-bc3834ca7abd|间接依赖|go|
|k8s.io/kube-aggregator|v0.26.4|直接依赖|go|
|github.com/gregjones/httpcache|v0.0.0-20190611155906-901d90724c79|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.11.0|直接依赖|go|
|github.com/elazarl/goproxy|v0.0.0-20190911111923-ecfe977594f1|间接依赖|go|
|github.com/machadovilaca/operator-observability|v0.0.7|直接依赖|go|
|github.com/prometheus/common|v0.37.0|直接依赖|go|
|gopkg.in/cheggaaa/pb.v1|v1.0.28|直接依赖|go|
|k8s.io/apiextensions-apiserver|v0.26.3|直接依赖|go|
|k8s.io/klog/v2|v2.100.1|直接依赖|go|
|github.com/imdario/mergo|v0.3.16|直接依赖|go|
|kubevirt.io/client-go|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/google/goterm|v0.0.0-20190311235235-ce302be1d114|间接依赖|go|
|github.com/coreos/go-semver|v0.3.0|直接依赖|go|
|github.com/prometheus/client_model|v0.4.0|直接依赖|go|
|github.com/google/gnostic|v0.5.7|间接依赖|go|
|k8s.io/klog/v2|v2.90.1|间接依赖|go|
|google.golang.org/appengine|v1.6.8|间接依赖|go|
|github.com/mitchellh/go-ps|v0.0.0-20190716172923-621e5597135b|直接依赖|go|
|github.com/emicklei/go-restful/v3|v3.11.0|直接依赖|go|
|github.com/onsi/gomega|v1.27.10|直接依赖|go|
|mvdan.cc/editorconfig|v0.1.1-0.20200121172147-e40951bde157|间接依赖|go|
|github.com/willf/bitset|v1.1.11|间接依赖|go|
|github.com/go-kit/kit|v0.10.0|直接依赖|go|
|github.com/google/uuid|v1.1.5|间接依赖|go|
|golang.org/x/mod|v0.12.0|间接依赖|go|
|github.com/google/renameio|v0.1.0|间接依赖|go|
|github.com/gorilla/websocket|v1.5.0|直接依赖|go|
|golang.org/x/exp/typeparams|v0.0.0-20230203172020-98cc5a0785f9|间接依赖|go|
|mvdan.cc/sh/v3|v3.1.1|直接依赖|go|
|k8s.io/kubectl|v0.0.0-00010101000000-000000000000|直接依赖|go|
|github.com/prometheus-operator/prometheus-operator/pkg/apis/monitoring|v0.68.0|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.6.0|间接依赖|go|
|golang.org/x/time|v0.3.0|直接依赖|go|
|github.com/containernetworking/plugins|v1.1.1|直接依赖|go|
|libvirt.org/go/libvirt|v1.9004.0|直接依赖|go|
|github.com/spf13/cobra|v1.6.0|直接依赖|go|
|github.com/pmezard/go-difflib|v1.0.1-0.20181226105442-5d4384ee4fb2|间接依赖|go|
|kubevirt.io/client-go|v0.19.0|直接依赖|go|
|github.com/google/go-querystring|v1.0.0|间接依赖|go|
|github.com/pierrec/lz4/v4|v4.1.14|间接依赖|go|
|github.com/go-openapi/swag|v0.22.4|间接依赖|go|
|github.com/sirupsen/logrus|v1.9.0|间接依赖|go|
|github.com/go-openapi/jsonreference|v0.20.2|间接依赖|go|
|sigs.k8s.io/structured-merge-diff/v4|v4.2.3|间接依赖|go|
|k8s.io/klog|v0.3.3|间接依赖|go|
|github.com/prometheus/client_golang|v1.14.0|直接依赖|go|
|k8s.io/utils|v0.0.0-20230505201702-9f6742963106|直接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|github.com/go-openapi/strfmt|v0.20.0|直接依赖|go|
|golang.org/x/sys|v0.13.0|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|kubevirt.io/api|v0.0.0-00010101000000-000000000000|直接依赖|go|
|sigs.k8s.io/yaml|v1.3.0|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.4.0|间接依赖|go|
|github.com/seccomp/libseccomp-golang|v0.10.0|间接依赖|go|
|k8s.io/apimachinery|v0.20.15|直接依赖|go|
|github.com/Masterminds/semver|v1.5.0|直接依赖|go|
|github.com/openshift/api|v0.0.0-20230503133300-8bbcb7ca7183|间接依赖|go|
|github.com/go-openapi/analysis|v0.20.0|间接依赖|go|
|github.com/josharian/native|v1.1.0|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.4.0|间接依赖|go|
|github.com/golang/glog|v1.1.0|直接依赖|go|
|github.com/google/gnostic|v0.5.7-v3refs|间接依赖|go|
|k8s.io/api|v0.27.1|直接依赖|go|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|github.com/openshift/library-go|v0.0.0-20211220195323-eca2c467c492|直接依赖|go|
|golang.org/x/oauth2|v0.12.0|间接依赖|go|
|github.com/containernetworking/cni|v1.1.2|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)