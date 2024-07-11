# nerdswords/yet-another-cloudwatch-exporter安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1811469411928096768.svg)](https://www.murphysec.com/console/report/1811469403996667904/1811469411928096768)

> 点击徽章可查看详细项目安全报告

仓库描述：Prometheus exporter for AWS CloudWatch - Discovers services through AWS tags, gets CloudWatch metrics data and provides them as Prometheus metrics with AWS tags as labels

仓库地址：[https://github.com/nerdswords/yet-another-cloudwatch-exporter](https://github.com/nerdswords/yet-another-cloudwatch-exporter)

| star：927 | watch：21 | fork：323 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-07-09 16:32:15 | 许可证：Apache-2.0 |
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
|Apache-2.0|31|Low|
|MIT|11|Low|
|BSD-3-Clause|5|Low|
|BSD-2-Clause|3|Low|
|ISC|1|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/aws/aws-sdk-go-v2/credentials|v1.17.23|直接依赖|go|
|github.com/prometheus/common|v0.55.0|直接依赖|go|
|github.com/xrash/smetrics|v0.0.0-20240312152122-5f08fbb34913|间接依赖|go|
|github.com/prometheus/client_model|v0.6.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/shield|v1.27.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/storagegateway|v1.31.1|直接依赖|go|
|github.com/beorn7/perks|v1.0.1|间接依赖|go|
|github.com/go-kit/log|v0.2.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/apigateway|v1.25.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudwatch|v1.40.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.30.1|直接依赖|go|
|golang.org/x/sync|v0.7.0|直接依赖|go|
|github.com/cpuguy83/go-md2man/v2|v2.0.4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/databasemigrationservice|v1.40.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.3.13|间接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|golang.org/x/sys|v0.21.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/apigatewayv2|v1.22.1|直接依赖|go|
|github.com/urfave/cli/v2|v2.27.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.30.1|直接依赖|go|
|github.com/prometheus/client_golang|v1.19.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.11.3|间接依赖|go|
|github.com/aws/smithy-go|v1.20.3|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/kr/text|v0.2.0|间接依赖|go|
|github.com/stretchr/testify|v1.9.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.22.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/autoscaling|v1.43.1|直接依赖|go|
|google.golang.org/protobuf|v1.34.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.11.15|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.6.13|间接依赖|go|
|github.com/munnerz/goautoneg|v0.0.0-20191010083416-a7dc8b61c822|间接依赖|go|
|github.com/aws/aws-sdk-go|v1.54.12|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.8.0|间接依赖|go|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|github.com/cespare/xxhash/v2|v2.2.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/resourcegroupstaggingapi|v1.23.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/iam|v1.34.1|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.26.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.168.0|直接依赖|go|
|github.com/grafana/regexp|v0.0.0-20221123153739-15dc172cd2db|直接依赖|go|
|github.com/go-logfmt/logfmt|v0.5.1|间接依赖|go|
|github.com/pmezard/go-difflib|v1.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.27.23|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.16.9|间接依赖|go|
|github.com/prometheus/procfs|v0.15.1|间接依赖|go|
|github.com/vmihailenco/msgpack/v5|v5.3.5|间接依赖|go|
|github.com/r3labs/diff/v3|v3.0.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/amp|v1.27.1|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)