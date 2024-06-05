# opencontainers/runc安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1798419905070202880.svg)](https://www.murphysec.com/console/report/1735363780369932288/1798419905070202880)

> 点击徽章可查看详细项目安全报告

仓库描述：CLI tool for spawning and running containers according to the OCI specification

仓库地址：[https://github.com/opencontainers/runc](https://github.com/opencontainers/runc)

| star：11508 | watch：385 | fork：2056 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-06-05 19:19:31 | 许可证：Apache-2.0 |
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
|MIT|4|Low|
|Apache-2.0|9|Low|
|BSD-3-Clause|4|Low|
|BSD-2-Clause|4|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/urfave/cli|v1.22.14|直接依赖|go|
|github.com/vishvananda/netns|v0.0.0-20191106174202-0a2b9b5464df|间接依赖|go|
|golang.org/x/net|v0.24.0|直接依赖|go|
|github.com/syndtr/gocapability|v0.0.0-20200815063812-42c35b437635|直接依赖|go|
|github.com/cilium/ebpf|v0.12.3|直接依赖|go|
|golang.org/x/sys|v0.19.0|直接依赖|go|
|github.com/mrunalp/fileutils|v0.5.1|直接依赖|go|
|github.com/checkpoint-restore/go-criu/v6|v6.3.0|直接依赖|go|
|github.com/seccomp/libseccomp-golang|v0.10.0|直接依赖|go|
|github.com/moby/sys/mountinfo|v0.7.1|直接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/vishvananda/netlink|v1.1.0|直接依赖|go|
|github.com/sirupsen/logrus|v1.9.3|直接依赖|go|
|golang.org/x/exp|v0.0.0-20230224173230-c95f2b4c22f2|间接依赖|go|
|github.com/opencontainers/runtime-spec|v1.2.0|直接依赖|go|
|github.com/godbus/dbus/v5|v5.1.0|直接依赖|go|
|github.com/cyphar/filepath-securejoin|v0.2.4|直接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/opencontainers/selinux|v1.11.0|直接依赖|go|
|github.com/moby/sys/user|v0.1.0|直接依赖|go|
|github.com/containerd/console|v1.0.4|直接依赖|go|
|github.com/coreos/go-systemd/v22|v22.5.0|直接依赖|go|
|github.com/docker/go-units|v0.5.0|直接依赖|go|
|google.golang.org/protobuf|v1.33.0|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)