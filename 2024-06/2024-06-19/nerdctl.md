# containerd/nerdctl安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1803136771549147136.svg)](https://www.murphysec.com/console/report/1732102918361796608/1803136771549147136)

> 点击徽章可查看详细项目安全报告

仓库描述：contaiNERD CTL - Docker-compatible CLI for containerd, with support for Compose, Rootless, eStargz, OCIcrypt, IPFS, ...

仓库地址：[https://github.com/containerd/nerdctl](https://github.com/containerd/nerdctl)

| star：7575 | watch：48 | fork：564 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-06-18 23:06:47 | 许可证：Apache-2.0 |
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
|Apache-2.0|66|Low|
|BSD-3-Clause|18|Low|
|MIT|34|Low|
|CC-BY-SA-4.0|1|Medium|
|MPL-2.0|3|Low|
|BSD-2-Clause|2|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/moby/sys/symlink|v0.2.0|间接依赖|go|
|go.opentelemetry.io/otel|v1.19.0|间接依赖|go|
|google.golang.org/grpc|v1.62.0|间接依赖|go|
|github.com/moby/sys/sequential|v0.5.0|间接依赖|go|
|go.uber.org/mock|v0.4.0|直接依赖|go|
|github.com/imdario/mergo|v0.3.16|间接依赖|go|
|github.com/containerd/imgcrypt|v1.1.11|直接依赖|go|
|go.opentelemetry.io/otel/trace|v1.19.0|间接依赖|go|
|github.com/spaolacci/murmur3|v1.1.0|间接依赖|go|
|github.com/golang/groupcache|v0.0.0-20210331224755-41bb18bfe9da|间接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|github.com/google/go-cmp|v0.6.0|间接依赖|go|
|golang.org/x/sync|v0.7.0|直接依赖|go|
|github.com/containerd/stargz-snapshotter|v0.15.1|直接依赖|go|
|github.com/multiformats/go-multiaddr|v0.12.0|间接依赖|go|
|github.com/klauspost/cpuid/v2|v2.2.3|间接依赖|go|
|github.com/spf13/pflag|v1.0.5|直接依赖|go|
|github.com/gogo/protobuf|v1.3.2|间接依赖|go|
|github.com/go-jose/go-jose/v3|v3.0.3|间接依赖|go|
|github.com/containerd/errdefs|v0.1.0|间接依赖|go|
|github.com/fluent/fluent-logger-golang|v1.9.0|直接依赖|go|
|github.com/vbatts/tar-split|v0.11.5|间接依赖|go|
|github.com/stefanberger/go-pkcs11uri|v0.0.0-20230803200340-78284954bff6|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.2.0|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20240123012728-ef4313101c80|间接依赖|go|
|github.com/Azure/go-ansiterm|v0.0.0-20210617225240-d185dfc1b5a1|间接依赖|go|
|github.com/bmizerany/assert|v0.0.0-20160611221934-b7ed37b82869|间接依赖|go|
|github.com/tidwall/gjson|v1.17.1|直接依赖|go|
|github.com/pelletier/go-toml/v2|v2.2.2|直接依赖|go|
|google.golang.org/protobuf|v1.33.0|间接依赖|go|
|golang.org/x/term|v0.21.0|直接依赖|go|
|github.com/docker/go-connections|v0.5.0|直接依赖|go|
|golang.org/x/sys|v0.21.0|直接依赖|go|
|github.com/containerd/continuity|v0.4.3|直接依赖|go|
|github.com/opencontainers/go-digest|v1.0.0|直接依赖|go|
|github.com/hashicorp/go-multierror|v1.1.1|间接依赖|go|
|github.com/go-logr/logr|v1.4.1|间接依赖|go|
|lukechampine.com/blake3|v1.1.7|间接依赖|go|
|github.com/containernetworking/cni|v1.2.1|直接依赖|go|
|github.com/containerd/platforms|v0.2.1|直接依赖|go|
|github.com/moby/locker|v1.0.1|间接依赖|go|
|github.com/ipfs/go-cid|v0.4.1|直接依赖|go|
|github.com/moby/sys/mountinfo|v0.7.1|间接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|间接依赖|go|
|github.com/google/uuid|v1.6.0|间接依赖|go|
|github.com/coreos/go-iptables|v0.7.0|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|github.com/moby/sys/mount|v0.3.3|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|github.com/moby/term|v0.5.0|直接依赖|go|
|github.com/distribution/reference|v0.6.0|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20240123012728-ef4313101c80|间接依赖|go|
|github.com/containerd/typeurl|v1.0.3-0.20220422153119-7f6e6d160d67|间接依赖|go|
|github.com/multiformats/go-multibase|v0.1.1|间接依赖|go|
|go.opencensus.io|v0.24.0|间接依赖|go|
|github.com/AdaLogics/go-fuzz-headers|v0.0.0-20230811130428-ced1acdcaa24|间接依赖|go|
|github.com/multiformats/go-multihash|v0.2.1|间接依赖|go|
|github.com/awslabs/soci-snapshotter|v0.6.1|直接依赖|go|
|github.com/djherbis/times|v1.6.0|间接依赖|go|
|github.com/vishvananda/netlink|v1.2.1-beta.2|直接依赖|go|
|github.com/Masterminds/semver/v3|v3.2.1|直接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|github.com/containerd/typeurl/v2|v2.1.1|直接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|github.com/tidwall/pretty|v1.2.0|间接依赖|go|
|github.com/muesli/cancelreader|v0.2.2|直接依赖|go|
|gotest.tools/v3|v3.5.1|直接依赖|go|
|golang.org/x/net|v0.26.0|直接依赖|go|
|github.com/klauspost/compress|v1.17.9|直接依赖|go|
|github.com/containerd/stargz-snapshotter/estargz|v0.15.1|直接依赖|go|
|github.com/containerd/go-runc|v1.0.0|间接依赖|go|
|github.com/containerd/containerd|v1.7.18|直接依赖|go|
|github.com/containers/ocicrypt|v1.1.10|间接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|github.com/miekg/pkcs11|v1.1.1|间接依赖|go|
|github.com/cilium/ebpf|v0.11.0|间接依赖|go|
|github.com/multiformats/go-base32|v0.1.0|间接依赖|go|
|github.com/containernetworking/plugins|v1.5.1|直接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/net/http/otelhttp|v0.45.0|间接依赖|go|
|golang.org/x/crypto|v0.24.0|直接依赖|go|
|github.com/rootless-containers/bypass4netns|v0.4.1|直接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|直接依赖|go|
|github.com/moby/docker-image-spec|v1.3.1|间接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.5|直接依赖|go|
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/containerd/go-cni|v1.1.9|直接依赖|go|
|github.com/spf13/cobra|v1.8.1|直接依赖|go|
|github.com/multiformats/go-varint|v0.0.6|间接依赖|go|
|github.com/golang/protobuf|v1.5.4|间接依赖|go|
|github.com/containerd/stargz-snapshotter/ipfs|v0.15.1|直接依赖|go|
|github.com/fahedouch/go-logrotate|v0.2.1|直接依赖|go|
|github.com/felixge/httpsnoop|v1.0.3|间接依赖|go|
|github.com/minio/sha256-simd|v1.0.1|间接依赖|go|
|github.com/containerd/nydus-snapshotter|v0.13.13|直接依赖|go|
|github.com/compose-spec/compose-go|v1.20.2|直接依赖|go|
|github.com/opencontainers/image-spec|v1.1.0|直接依赖|go|
|github.com/AdamKorcz/go-118-fuzz-build|v0.0.0-20230306123547-8075edf89bb0|间接依赖|go|
|github.com/docker/go-events|v0.0.0-20190806004212-e31b211e4f1c|间接依赖|go|
|github.com/mattn/go-isatty|v0.0.20|直接依赖|go|
|github.com/Microsoft/go-winio|v0.6.2|直接依赖|go|
|github.com/pelletier/go-toml|v1.9.5|间接依赖|go|
|github.com/containerd/log|v0.1.0|直接依赖|go|
|github.com/philhofer/fwd|v1.1.1|间接依赖|go|
|github.com/containerd/console|v1.0.4|直接依赖|go|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/tidwall/match|v1.1.1|间接依赖|go|
|github.com/moby/sys/user|v0.1.0|间接依赖|go|
|github.com/fatih/color|v1.17.0|直接依赖|go|
|go.mozilla.org/pkcs7|v0.0.0-20200128120323-432b2356ecb1|间接依赖|go|
|github.com/tinylib/msgp|v1.1.6|间接依赖|go|
|github.com/docker/cli|v26.1.4+incompatible|直接依赖|go|
|golang.org/x/exp|v0.0.0-20231006140011-7918f672742d|间接依赖|go|
|github.com/multiformats/go-base36|v0.1.0|间接依赖|go|
|github.com/moby/sys/signal|v0.7.0|直接依赖|go|
|github.com/containerd/fifo|v1.1.0|直接依赖|go|
|github.com/docker/docker|v26.1.4+incompatible|直接依赖|go|
|github.com/opencontainers/selinux|v1.11.0|间接依赖|go|
|github.com/mr-tron/base58|v1.2.0|间接依赖|go|
|go.opentelemetry.io/otel/metric|v1.19.0|间接依赖|go|
|github.com/docker/go-units|v0.5.0|直接依赖|go|
|github.com/rootless-containers/rootlesskit/v2|v2.1.0|直接依赖|go|
|github.com/yuchanns/srslog|v1.1.0|直接依赖|go|
|github.com/containerd/cgroups/v3|v3.0.3|直接依赖|go|
|github.com/vishvananda/netns|v0.0.4|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|间接依赖|go|
|golang.org/x/text|v0.16.0|直接依赖|go|
|github.com/containerd/ttrpc|v1.2.4|间接依赖|go|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|github.com/docker/docker-credential-helpers|v0.7.0|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/containerd/accelerated-container-image|v1.1.3|直接依赖|go|
|github.com/Microsoft/hcsshim|v0.12.4|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|间接依赖|go|
|github.com/mattn/go-shellwords|v1.0.12|间接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)