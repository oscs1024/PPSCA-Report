# containerd/nerdctl安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1835383801129549824.svg)](https://www.murphysec.com/console/report/1732102918361796608/1835383801129549824)

> 点击徽章可查看详细项目安全报告

仓库描述：contaiNERD CTL - Docker-compatible CLI for containerd, with support for Compose, Rootless, eStargz, OCIcrypt, IPFS, ...

仓库地址：[https://github.com/containerd/nerdctl](https://github.com/containerd/nerdctl)

| star：7913 | watch：48 | fork：587 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-09-14 13:01:10 | 许可证：Apache-2.0 |
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
|MIT|22|Low|
|BSD-3-Clause|9|Low|
|BSD-2-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|lukechampine.com/blake3|v1.3.0|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.20|直接依赖|go|
|github.com/coreos/go-iptables|v0.8.0|直接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|直接依赖|go|
|golang.org/x/exp|v0.0.0-20240719175910-8a7402abbf56|间接依赖|go|
|go.opentelemetry.io/otel|v1.28.0|间接依赖|go|
|github.com/containerd/accelerated-container-image|v1.2.2|直接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.3.2|直接依赖|go|
|golang.org/x/crypto|v0.27.0|直接依赖|go|
|github.com/docker/go-connections|v0.5.0|直接依赖|go|
|github.com/containerd/errdefs|v0.1.0|直接依赖|go|
|github.com/golang/protobuf|v1.5.4|间接依赖|go|
|github.com/opencontainers/runtime-tools|v0.9.1-0.20221107090550-2e043c6bd626|间接依赖|go|
|github.com/containerd/continuity|v0.4.3|直接依赖|go|
|github.com/mattn/go-shellwords|v1.0.12|间接依赖|go|
|github.com/containerd/fifo|v1.1.0|直接依赖|go|
|github.com/minio/sha256-simd|v1.0.1|间接依赖|go|
|github.com/containerd/typeurl/v2|v2.2.0|直接依赖|go|
|github.com/rootless-containers/bypass4netns|v0.4.1|直接依赖|go|
|github.com/moby/sys/mount|v0.3.4|直接依赖|go|
|github.com/multiformats/go-multibase|v0.2.0|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.2.0|直接依赖|go|
|google.golang.org/grpc|v1.65.0|间接依赖|go|
|github.com/multiformats/go-multihash|v0.2.3|间接依赖|go|
|github.com/containernetworking/cni|v1.2.3|直接依赖|go|
|github.com/google/go-cmp|v0.6.0|间接依赖|go|
|github.com/containers/ocicrypt|v1.2.0|间接依赖|go|
|github.com/containerd/containerd/api|v1.8.0-rc.3|直接依赖|go|
|github.com/moby/docker-image-spec|v1.3.1|间接依赖|go|
|golang.org/x/sys|v0.25.0|直接依赖|go|
|github.com/Masterminds/semver/v3|v3.3.0|直接依赖|go|
|golang.org/x/mod|v0.20.0|间接依赖|go|
|github.com/felixge/httpsnoop|v1.0.4|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.8|间接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/compose-spec/compose-go/v2|v2.2.0|直接依赖|go|
|golang.org/x/sync|v0.8.0|直接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20240805194559-2c9e96a0b5d4|间接依赖|go|
|google.golang.org/protobuf|v1.34.2|间接依赖|go|
|github.com/yuchanns/srslog|v1.1.0|直接依赖|go|
|github.com/multiformats/go-varint|v0.0.7|间接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0|直接依赖|go|
|github.com/multiformats/go-base32|v0.1.0|间接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|github.com/vishvananda/netns|v0.0.4|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|github.com/moby/term|v0.5.0|直接依赖|go|
|golang.org/x/term|v0.24.0|直接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.53.0|间接依赖|go|
|github.com/vishvananda/netlink|v1.3.0|直接依赖|go|
|github.com/spf13/cobra|v1.8.1|直接依赖|go|
|github.com/ipfs/go-cid|v0.4.1|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/syndtr/gocapability|v0.0.0-20200815063812-42c35b437635|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.28.0|间接依赖|go|
|github.com/containerd/stargz-snapshotter|v0.15.2-0.20240709063920-1dac5ef89319|直接依赖|go|
|github.com/moby/sys/symlink|v0.3.0|间接依赖|go|
|github.com/fluent/fluent-logger-golang|v1.9.0|直接依赖|go|
|github.com/djherbis/times|v1.6.0|间接依赖|go|
|github.com/muesli/cancelreader|v0.2.2|直接依赖|go|
|github.com/containerd/stargz-snapshotter/estargz|v0.15.2-0.20240709063920-1dac5ef89319|直接依赖|go|
|github.com/containerd/ttrpc|v1.2.5|间接依赖|go|
|github.com/containerd/cgroups/v3|v3.0.3|直接依赖|go|
|github.com/docker/docker|v27.2.1+incompatible|直接依赖|go|
|github.com/pelletier/go-toml/v2|v2.2.3|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/go-jose/go-jose/v4|v4.0.4|间接依赖|go|
|github.com/containerd/console|v1.0.4|直接依赖|go|
|github.com/philhofer/fwd|v1.1.3-0.20240612014219-fbbf4953d986|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/miekg/pkcs11|v1.1.1|间接依赖|go|
|github.com/fahedouch/go-logrotate|v0.2.1|直接依赖|go|
|go.opentelemetry.io/otel/metric|v1.28.0|间接依赖|go|
|github.com/cilium/ebpf|v0.16.0|间接依赖|go|
|github.com/AdamKorcz/go-118-fuzz-build|v0.0.0-20231105174938-2b5cbb29f3e2|间接依赖|go|
|github.com/containerd/go-cni|v1.1.10|直接依赖|go|
|github.com/containerd/log|v0.1.0|直接依赖|go|
|github.com/AdaLogics/go-fuzz-headers|v0.0.0-20240806141605-e8a1dd7889d6|间接依赖|go|
|github.com/docker/go-units|v0.5.0|直接依赖|go|
|github.com/vbatts/tar-split|v0.11.5|间接依赖|go|
|github.com/fsnotify/fsnotify|v1.7.0|直接依赖|go|
|github.com/opencontainers/selinux|v1.11.0|间接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|直接依赖|go|
|github.com/go-logr/logr|v1.4.2|间接依赖|go|
|golang.org/x/text|v0.18.0|直接依赖|go|
|sigs.k8s.io/yaml|v1.4.0|间接依赖|go|
|github.com/moby/sys/sequential|v0.6.0|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/go-viper/mapstructure/v2|v2.1.0|直接依赖|go|
|github.com/moby/sys/userns|v0.1.0|直接依赖|go|
|tags.cncf.io/container-device-interface/specs-go|v0.8.0|间接依赖|go|
|tags.cncf.io/container-device-interface|v0.8.0|间接依赖|go|
|github.com/containerd/plugin|v0.1.0|间接依赖|go|
|github.com/containerd/platforms|v0.2.1|直接依赖|go|
|github.com/containerd/stargz-snapshotter/ipfs|v0.15.2-0.20240709063920-1dac5ef89319|直接依赖|go|
|github.com/klauspost/compress|v1.17.9|直接依赖|go|
|github.com/mr-tron/base58|v1.2.0|间接依赖|go|
|github.com/multiformats/go-base36|v0.2.0|间接依赖|go|
|go.mozilla.org/pkcs7|v0.0.0-20210826202110-33d05740a352|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/containerd/containerd/v2|v2.0.0-rc.4|直接依赖|go|
|github.com/moby/sys/user|v0.3.0|间接依赖|go|
|github.com/Microsoft/hcsshim|v0.12.6|直接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20230124172434-306776ec8161|间接依赖|go|
|github.com/containerd/imgcrypt|v1.2.0-rc1.0.20240709223013-f3769dc3e47f|直接依赖|go|
|golang.org/x/net|v0.29.0|直接依赖|go|
|go.uber.org/mock|v0.4.0|直接依赖|go|
|github.com/moby/sys/mountinfo|v0.7.2|直接依赖|go|
|github.com/rootless-containers/rootlesskit/v2|v2.3.1|直接依赖|go|
|github.com/moby/sys/signal|v0.7.1|直接依赖|go|
|github.com/stefanberger/go-pkcs11uri|v0.0.0-20230803200340-78284954bff6|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/multiformats/go-multiaddr|v0.13.0|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/containernetworking/plugins|v1.5.1|直接依赖|go|
|github.com/docker/docker-credential-helpers|v0.8.2|间接依赖|go|
|github.com/distribution/reference|v0.6.0|直接依赖|go|
|github.com/fatih/color|v1.17.0|直接依赖|go|
|gotest.tools/v3|v3.5.1|直接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|github.com/docker/cli|v27.2.1+incompatible|直接依赖|go|
|github.com/containerd/nydus-snapshotter|v0.14.1-0.20240806063146-8fa319bfe9c5|直接依赖|go|
|github.com/Microsoft/go-winio|v0.6.2|直接依赖|go|
|github.com/containerd/go-runc|v1.1.0|间接依赖|go|
|github.com/bmizerany/assert|v0.0.0-20160611221934-b7ed37b82869|间接依赖|go|
|github.com/tinylib/msgp|v1.2.0|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)