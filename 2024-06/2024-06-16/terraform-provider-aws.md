# hashicorp/terraform-provider-aws安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1802141128748937216.svg)](https://www.murphysec.com/console/report/1701296950972383232/1802141128748937216)

> 点击徽章可查看详细项目安全报告

仓库描述：The AWS Provider enables Terraform to manage AWS resources.

仓库地址：[https://github.com/hashicorp/terraform-provider-aws](https://github.com/hashicorp/terraform-provider-aws)

| star：9566 | watch：448 | fork：8965 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-06-15 23:47:45 | 许可证：MPL-2.0 |
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
|Apache-2.0|292|Low|
|BSD-3-Clause|16|Low|
|MIT|35|Low|
|MPL-2.0|28|Low|
|Dom4J|1|Low|
|OpenSSL|1|Low|
|LicenseRef-scancode-ssleay|1|Low|
|LicenseRef-scancode-public-domain|1|Low|
|BSD-2-Clause|8|Low|
|curl|1|Low|
|WTFPL|1|Low|
|The New BSD License|1|Low|
|ISC|1|Low|
|MPL-1.1|1|Low|
|LGPL-2.1-only|1|Medium|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/aws/aws-sdk-go-v2/service/secretsmanager|v1.30.0|直接依赖|go|
|golang.org/x/tools|v0.22.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codegurureviewer|v1.25.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/mediaconnect|v1.28.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/s3shared|v1.17.9|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssmsap|v1.13.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/datazone|v1.8.6|直接依赖|go|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/resourceexplorer2|v1.10.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/applicationinsights|v1.24.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/wafregional|v1.21.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/healthlake|v1.24.6|直接依赖|go|
|gopkg.in/yaml.v3|v3.0.1|间接依赖|go|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.10.1|间接依赖|maven|
|go.opentelemetry.io/otel/metric|v1.26.0|间接依赖|go|
|github.com/go-logr/stdr|v1.2.2|间接依赖|go|
|golang.org/x/text|v0.16.0|直接依赖|go|
|com.amazonaws:aws-java-sdk-kinesis|1.11.603|直接依赖|maven|
|github.com/hashicorp/go-cleanhttp|v0.5.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/costoptimizationhub|v1.4.10|直接依赖|go|
|org.apache.commons:commons-lang3|3.3.2|间接依赖|maven|
|github.com/boombuler/barcode|v1.0.1|间接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/datasync|v1.38.4|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/docdbelastic|v1.9.9|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssmcontacts|v1.22.10|直接依赖|go|
|github.com/frankban/quicktest|v1.14.6|间接依赖|go|
|github.com/hashicorp/terraform-plugin-framework-jsontypes|v0.1.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codecatalyst|v1.13.7|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ecrpublic|v1.23.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/schemas|v1.24.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/budgets|v1.23.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sns|v1.29.11|直接依赖|go|
|github.com/pquerna/otp|v1.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/verifiedpermissions|v1.15.0|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20240227224415-6ceb2ff114de|间接依赖|go|
|github.com/hashicorp/terraform-registry-address|v0.2.3|间接依赖|go|
|github.com/mattbaird/jsonpatch|v0.0.0-20230413205102-771768614e91|直接依赖|go|
|github.com/hashicorp/logutils|v1.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.6.9|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/computeoptimizer|v1.34.7|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudwatchlogs|v1.35.7|直接依赖|go|
|dom4j:dom4j|1.6.1|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/emr|v1.39.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/lakeformation|v1.33.3|直接依赖|go|
|github.com/bgentry/speakeasy|v0.1.0|间接依赖|go|
|openssl|1.0.1m|间接依赖||
|github.com/aws/aws-sdk-go-v2/service/appstream|v1.34.10|直接依赖|go|
|github.com/hashicorp/go-hclog|v1.6.3|直接依赖|go|
|github.com/hashicorp/terraform-plugin-go|v0.23.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.27.2|直接依赖|go|
|aopalliance:aopalliance|1.0|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cognitoidentity|v1.23.13|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/bedrock|v1.8.8|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codeguruprofiler|v1.20.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/mq|v1.22.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/account|v1.17.1|直接依赖|go|
|com.fasterxml.jackson.core:jackson-core|2.10.1|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/lookoutmetrics|v1.27.10|直接依赖|go|
|github.com/armon/go-radix|v1.0.0|间接依赖|go|
|com.amazonaws:aws-java-sdk-logs|1.11.903|直接依赖|maven|
|com.amazonaws:aws-java-sdk-kms|1.11.603|直接依赖|maven|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|github.com/hashicorp/cli|v1.1.6|直接依赖|go|
|golang.org/x/sync|v0.7.0|间接依赖|go|
|github.com/hashicorp/terraform-plugin-framework-timeouts|v0.4.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/mediastore|v1.20.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticbeanstalk|v1.23.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/lambda|v1.54.6|直接依赖|go|
|libm.so.6||间接依赖||
|github.com/imdario/mergo|v0.3.16|间接依赖|go|
|github.com/google/go-cmp|v0.6.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/comprehend|v1.31.10|直接依赖|go|
|com.amazonaws:aws-java-sdk-cloudwatch|1.11.603|直接依赖|maven|
|com.google.guava:failureaccess|1.0.1|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/applicationautoscaling|v1.27.10|直接依赖|go|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|com.amazonaws:amazon-kinesis-producer|0.14.0|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.9|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cloudsearch|v1.22.10|直接依赖|go|
|github.com/zclconf/go-cty|v1.14.4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloud9|v1.24.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sqs|v1.32.6|直接依赖|go|
|github.com/mitchellh/reflectwalk|v1.0.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/qldb|v1.21.10|直接依赖|go|
|github.com/ProtonMail/go-crypto|v1.1.0-alpha.2|直接依赖|go|
|github.com/dlclark/regexp2|v1.11.0|直接依赖|go|
|org.slf4j:slf4j-api|1.7.7|间接依赖|maven|
|github.com/xeipuuv/gojsonschema|v1.2.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codeartifact|v1.27.6|直接依赖|go|
|javax.inject:javax.inject|1|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cloudfront|v1.36.6|直接依赖|go|
|software.amazon.ion:ion-java|1.0.2|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/kms|v1.33.0|直接依赖|go|
|github.com/hashicorp/terraform-plugin-sdk/v2|v2.34.0|直接依赖|go|
|gopkg.in/dnaeon/go-vcr.v3|v3.2.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssm|v1.50.6|直接依赖|go|
|golang.org/x/mod|v0.18.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/lightsail|v1.38.3|直接依赖|go|
|github.com/huandu/xstrings|v1.4.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codecommit|v1.22.10|直接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.2|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/dynamodb|v1.32.8|直接依赖|go|
|github.com/pkg/errors|v0.9.1|间接依赖|go|
|io.codearte.jfairy:jfairy|0.5.3|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/chatbot|v1.2.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.8.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/fms|v1.33.7|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/eventbridge|v1.31.5|直接依赖|go|
|org.slf4j:slf4j-api|1.7.24|直接依赖|maven|
|libdl.so.2||间接依赖||
|github.com/aws/aws-sdk-go-v2/config|v1.27.18|直接依赖|go|
|github.com/cedar-policy/cedar-go|v0.0.0-20240318205125-470d1fe984bb|直接依赖|go|
|github.com/hashicorp/aws-sdk-go-base/v2/awsv1shim/v2|v2.0.0-beta.54|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/glacier|v1.22.10|直接依赖|go|
|github.com/shopspring/decimal|v1.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/costandusagereportservice|v1.23.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/scheduler|v1.8.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/workspacesweb|v1.18.6|直接依赖|go|
|com.amazonaws:aws-java-sdk-s3|1.11.603|直接依赖|maven|
|librt.so.1||间接依赖||
|github.com/aws/aws-sdk-go-v2/service/vpclattice|v1.8.6|直接依赖|go|
|com.github.jcustenborder.kafka.connect:connect-utils|0.4.164|直接依赖|maven|
|com.amazonaws:aws-kinesisanalytics-runtime|1.2.0|直接依赖|maven|
|joda-time:joda-time|2.8.1|直接依赖|maven|
|golang.org/x/sys|v0.21.0|间接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|3.0.0-SNAPSHOT|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/credentials|v1.17.18|直接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.10.1|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cloudhsmv2|v1.22.0|直接依赖|go|
|github.com/gertd/go-pluralize|v0.2.1|直接依赖|go|
|com.google.guava:guava|26.0-jre|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/appconfig|v1.29.8|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/osis|v1.10.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/redshiftdata|v1.25.10|直接依赖|go|
|com.google.code.gson:gson|2.8.0|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/chimesdkmediapipelines|v1.15.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/pipes|v1.12.1|直接依赖|go|
|org.codehaus.mojo:animal-sniffer-annotations|1.14|间接依赖|maven|
|com.amazonaws:jmespath-java|1.11.603|直接依赖|maven|
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|github.com/aws/aws-sdk-go-v2/service/mediapackagev2|v1.12.0|直接依赖|go|
|com.fasterxml.jackson.dataformat:jackson-dataformat-cbor|2.6.7|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/globalaccelerator|v1.24.1|直接依赖|go|
|com.amazonaws:aws-java-sdk-kinesis|1.11.754|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/devicefarm|v1.22.10|直接依赖|go|
|libcurl|7.47.0|间接依赖||
|github.com/go-logr/logr|v1.4.1|间接依赖|go|
|com.fasterxml.jackson.core:jackson-annotations|2.10.0.pr1|直接依赖|maven|
|libgcc_s.so.1||间接依赖||
|com.amazonaws:jmespath-java|1.11.754|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/securityhub|v1.49.2|直接依赖|go|
|golang.org/x/crypto|v0.24.0|直接依赖|go|
|github.com/hashicorp/terraform-exec|v0.21.0|间接依赖|go|
|com.fasterxml.jackson.core:jackson-core|2.6.7|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.11.11|间接依赖|go|
|go.opentelemetry.io/otel/trace|v1.26.0|间接依赖|go|
|syreclabs.com/go/faker|v1.2.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudwatch|v1.38.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cleanrooms|v1.12.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/firehose|v1.29.1|直接依赖|go|
|com.amazonaws:aws-java-sdk-core|1.11.312|直接依赖|maven|
|github.com/golang/protobuf|v1.5.4|间接依赖|go|
|com.amazonaws:aws-java-sdk-sts|1.11.754|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.16.5|直接依赖|go|
|github.com/hashicorp/aws-sdk-go-base/v2|v2.0.0-beta.53|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/workspaces|v1.39.6|直接依赖|go|
|golang.org/x/exp|v0.0.0-20240222234643-814bf88cf225|直接依赖|go|
|github.com/hashicorp/terraform-plugin-framework|v1.9.0|直接依赖|go|
|com.fasterxml.jackson.core:jackson-annotations|2.10.1|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cloudfrontkeyvaluestore|v1.4.10|直接依赖|go|
|github.com/mitchellh/go-homedir|v1.1.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/iam|v1.32.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.164.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/acm|v1.26.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/costexplorer|v1.38.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codepipeline|v1.28.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/neptunegraph|v1.8.7|直接依赖|go|
|github.com/evanphx/json-patch|v0.5.2|间接依赖|go|
|com.amazonaws:aws-java-sdk-core|1.11.754|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.10.0.pr1|直接依赖|maven|
|/usr/lib/libc++.1.dylib||间接依赖||
|github.com/hashicorp/errwrap|v1.1.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/guardduty|v1.43.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ivschat|v1.12.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/amp|v1.25.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codestarnotifications|v1.22.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/appfabric|v1.7.10|直接依赖|go|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|github.com/mitchellh/go-wordwrap|v1.0.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/inspector2|v1.26.6|直接依赖|go|
|com.google.code.findbugs:jsr305|3.0.2|直接依赖|maven|
|joda-time:joda-time|2.3|间接依赖|maven|
|github.com/xeipuuv/gojsonreference|v0.0.0-20180127040603-bd5ef7bd5415|间接依赖|go|
|com.fasterxml.jackson.core:jackson-annotations|2.6.0|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.24.5|间接依赖|go|
|github.com/Masterminds/goutils|v1.1.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/mediaconvert|v1.53.7|直接依赖|go|
|github.com/hashicorp/go-version|v1.7.0|直接依赖|go|
|github.com/hashicorp/terraform-plugin-mux|v0.16.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/groundstation|v1.27.6|直接依赖|go|
|github.com/YakDriver/go-version|v0.1.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internetmonitor|v1.14.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/fis|v1.24.8|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssmincidents|v1.30.10|直接依赖|go|
|com.amazonaws:amazon-kinesis-client|1.11.2|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/waf|v1.20.10|直接依赖|go|
|org.joda:joda-convert|1.2|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/rolesanywhere|v1.11.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/wafv2|v1.49.3|直接依赖|go|
|google.golang.org/protobuf|v1.34.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudtrail|v1.40.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ecr|v1.28.5|直接依赖|go|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|直接依赖|maven|
|org.checkerframework:checker-qual|2.5.2|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/ram|v1.25.10|直接依赖|go|
|libc.so.6||间接依赖||
|github.com/aws/aws-sdk-go-v2/service/pcaconnectorad|v1.5.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/route53profiles|v1.0.7|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticache|v1.38.8|直接依赖|go|
|com.google.errorprone:error_prone_annotations|2.1.3|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cloudcontrol|v1.18.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sesv2|v1.30.0|直接依赖|go|
|go.opentelemetry.io/contrib/instrumentation/github.com/aws/aws-sdk-go-v2/otelaws|v0.51.0|间接依赖|go|
|com.google.protobuf:protobuf-java|2.6.1|直接依赖|maven|
|org.iban4j:iban4j|2.1.1|间接依赖|maven|
|golang.org/x/mod|v0.17.0|间接依赖|go|
|github.com/spf13/cobra|v1.8.0|直接依赖|go|
|commons-io:commons-io|2.4|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/wellarchitected|v1.30.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudformation|v1.51.3|直接依赖|go|
|github.com/hashicorp/aws-cloudformation-resource-schema-sdk-go|v0.23.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/connectcases|v1.17.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kinesis|v1.27.10|直接依赖|go|
|org.apache.httpcomponents:httpcore|4.4.11|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/timestreaminfluxdb|v1.0.8|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/athena|v1.41.2|直接依赖|go|
|joda-time:joda-time|2.5|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/codedeploy|v1.25.10|直接依赖|go|
|com.google.inject.extensions:guice-assistedinject|4.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/apigatewayv2|v1.20.10|直接依赖|go|
|org.apache.httpcomponents:httpcore|4.4.9|间接依赖|maven|
|/usr/lib/libSystem.B.dylib||间接依赖||
|com.fasterxml.jackson.core:jackson-databind|2.6.7.1|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/controltower|v1.14.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/route53domains|v1.23.10|直接依赖|go|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.4|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/lexmodelsv2|v1.43.10|直接依赖|go|
|github.com/hashicorp/terraform-svchost|v0.1.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/evidently|v1.19.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codebuild|v1.37.3|直接依赖|go|
|github.com/hashicorp/terraform-plugin-framework-timetypes|v0.4.0|直接依赖|go|
|com.amazonaws:dynamodb-streams-kinesis-adapter|1.5.0|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/cloudhsmv2|v1.21.10|间接依赖|go|
|github.com/hashicorp/go-uuid|v1.0.3|直接依赖|go|
|github.com/inconshreveable/mousetrap|v1.1.0|间接依赖|go|
|org.slf4j:slf4j-simple|1.7.24|直接依赖|maven|
|github.com/hashicorp/go-checkpoint|v0.5.0|间接依赖|go|
|github.com/bufbuild/protocompile|v0.6.0|间接依赖|go|
|com.google.errorprone:error_prone_annotations|2.2.0|直接依赖|maven|
|github.com/oklog/run|v1.1.0|间接依赖|go|
|github.com/mitchellh/go-testing-interface|v1.14.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/m2|v1.13.6|直接依赖|go|
|org.freemarker:freemarker|2.3.28|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/appintegrations|v1.25.10|直接依赖|go|
|org.reflections:reflections|0.9.11|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.6.7.3|直接依赖|maven|
|github.com/fatih/color|v1.16.0|间接依赖|go|
|github.com/cloudflare/circl|v1.3.7|间接依赖|go|
|github.com/xeipuuv/gojsonpointer|v0.0.0-20190905194746-02993c407bfb|间接依赖|go|
|golang.org/x/tools|v0.21.1-0.20240508182429-e35e4ccd0d2d|直接依赖|go|
|org.apache.flink:flink-connector-kinesis_2.12||直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/timestreamwrite|v1.25.11|直接依赖|go|
|github.com/vmihailenco/tagparser/v2|v2.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticloadbalancingv2|v1.31.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.28.12|直接依赖|go|
|github.com/posener/complete|v1.2.3|间接依赖|go|
|commons-codec:commons-codec|1.11|直接依赖|maven|
|github.com/vmihailenco/msgpack/v5|v5.4.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/apigateway|v1.23.12|直接依赖|go|
|github.com/mitchellh/mapstructure|v1.5.0|直接依赖|go|
|github.com/hashicorp/yamux|v0.1.1|间接依赖|go|
|github.com/YakDriver/regexache|v0.23.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/mediapackage|v1.30.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/opensearchserverless|v1.11.13|直接依赖|go|
|github.com/hashicorp/terraform-plugin-log|v0.9.0|直接依赖|go|
|github.com/apparentlymart/go-textseg/v15|v15.0.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/keyspaces|v1.10.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3control|v1.44.13|直接依赖|go|
|google.golang.org/appengine|v1.6.8|间接依赖|go|
|golang.org/x/net|v0.25.0|间接依赖|go|
|org.apache.commons:commons-lang3|3.7|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/dax|v1.19.10|直接依赖|go|
|github.com/vmihailenco/msgpack|v4.0.4+incompatible|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rekognition|v1.40.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/devopsguru|v1.30.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kms|v1.32.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/route53|v1.40.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/chimesdkvoice|v1.15.6|直接依赖|go|
|com.google.guava:guava|20.0|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/accessanalyzer|v1.30.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/amplify|v1.21.11|直接依赖|go|
|github.com/hashicorp/awspolicyequivalence|v1.6.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kafka|v1.33.2|直接依赖|go|
|github.com/mitchellh/copystructure|v1.2.0|直接依赖|go|
|github.com/hashicorp/terraform-plugin-framework-validators|v0.12.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/oam|v1.11.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/emrserverless|v1.21.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/polly|v1.40.5|直接依赖|go|
|logkit:logkit|1.0.1|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/acmpca|v1.30.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/medialive|v1.52.6|直接依赖|go|
|github.com/hashicorp/go-cty|v1.4.1-0.20200723130312-85980079f637|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/mediapackagev2|v1.11.6|间接依赖|go|
|github.com/hashicorp/hcl/v2|v2.20.1|直接依赖|go|
|go.opentelemetry.io/otel|v1.26.0|间接依赖|go|
|org.codehaus.mojo:animal-sniffer-annotations|1.17|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/rds|v1.79.6|直接依赖|go|
|org.apache.flink:force-shading|1.11.1|直接依赖|maven|
|xml-apis:xml-apis|1.0.b2|间接依赖|maven|
|com.amazonaws:aws-java-sdk-kinesis|1.11.803|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/synthetics|v1.24.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/resourcegroups|v1.22.6|直接依赖|go|
|github.com/aws-cloudformation/cloudformation-cli-go-plugin|v1.0.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/autoscaling|v1.40.11|直接依赖|go|
|ld-linux-x86-64.so.2||间接依赖||
|github.com/aws/aws-sdk-go-v2/service/servicecatalogappregistry|v1.26.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/servicediscovery|v1.29.12|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.20.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codestarconnections|v1.25.8|直接依赖|go|
|github.com/beevik/etree|v1.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/organizations|v1.27.9|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/mwaa|v1.27.4|直接依赖|go|
|github.com/davecgh/go-spew|v1.1.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/paymentcryptography|v1.10.6|直接依赖|go|
|org.apache.httpcomponents:httpclient|4.5.5|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/internal/endpoint-discovery|v1.9.10|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/customerprofiles|v1.36.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/auditmanager|v1.33.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rbin|v1.16.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/directoryservice|v1.24.10|直接依赖|go|
|com.amazonaws:aws-java-sdk-dynamodb|1.11.603|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/drs|v1.26.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/batch|v1.38.1|直接依赖|go|
|commons-codec:commons-codec|1.10|间接依赖|maven|
|github.com/aws/aws-sdk-go|v1.54.1|直接依赖|go|
|github.com/hashicorp/go-plugin|v1.6.0|间接依赖|go|
|github.com/rogpeppe/go-internal|v1.11.0|间接依赖|go|
|com.google.code.findbugs:jsr305|1.3.9|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/bcmdataexports|v1.3.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/securitylake|v1.14.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/apprunner|v1.28.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ecs|v1.42.0|直接依赖|go|
|commons-logging:commons-logging|1.1.3|直接依赖|maven|
|com.google.guava:guava|27.1-jre|直接依赖|maven|
|com.google.j2objc:j2objc-annotations|1.1|直接依赖|maven|
|com.google.inject:guice|4.0|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/redshift|v1.44.7|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/appflow|v1.41.10|直接依赖|go|
|github.com/hashicorp/terraform-json|v0.22.1|直接依赖|go|
|com.amazonaws:aws-java-sdk-core|1.11.903|直接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.6|间接依赖|maven|
|github.com/Masterminds/semver/v3|v3.2.1|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kendra|v1.50.7|直接依赖|go|
|github.com/hashicorp/terraform-plugin-testing|v1.8.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/xray|v1.25.10|直接依赖|go|
|github.com/agext/levenshtein|v1.2.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/aws/protocol/eventstream|v1.6.2|间接依赖|go|
|github.com/hashicorp/hc-install|v0.6.4|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/autoscalingplans|v1.20.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/transfer|v1.48.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/pricing|v1.28.7|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/transcribe|v1.37.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/launchwizard|v1.4.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3|v1.55.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssoadmin|v1.25.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/signer|v1.22.13|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/eks|v1.43.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/servicequotas|v1.21.10|直接依赖|go|
|log4j:log4j|1.2.17|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/redshiftserverless|v1.18.8|直接依赖|go|
|github.com/go-test/deep|v1.1.0|间接依赖|go|
|org.javassist:javassist|3.21.0-GA|直接依赖|maven|
|com.google.guava:guava|18.0|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/qbusiness|v1.6.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.3.9|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/checksum|v1.3.11|间接依赖|go|
|commons-lang:commons-lang|2.6|直接依赖|maven|
|github.com/Masterminds/sprig/v3|v3.2.3|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/dlm|v1.24.10|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/resourcegroupstaggingapi|v1.21.10|直接依赖|go|
|org.yaml:snakeyaml|2.0-SNAPSHOT|间接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.11.2|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/docdb|v1.34.7|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/s3/manager|v1.16.24|直接依赖|go|
|github.com/spf13/pflag|v1.0.5|间接依赖|go|
|github.com/spf13/cast|v1.5.1|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/finspace|v1.24.7|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/identitystore|v1.23.12|直接依赖|go|
|com.amazonaws:aws-java-sdk-iam|1.11.803|间接依赖|maven|
|com.amazonaws:aws-kinesisanalytics-flink|2.0.0|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/swf|v1.23.2|直接依赖|go|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|github.com/aws/aws-sdk-go|v1.54.0|间接依赖|go|
|github.com/google/uuid|v1.6.0|间接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/v4a|v1.3.9|间接依赖|go|
|avalon-framework:avalon-framework|4.1.5|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/configservice|v1.46.11|直接依赖|go|
|github.com/mattn/go-isatty|v0.0.20|间接依赖|go|
|google.golang.org/grpc|v1.63.2|间接依赖|go|
|libpthread.so.0||间接依赖||
|com.amazonaws:aws-java-sdk-core|1.11.603|直接依赖|maven|
|github.com/hashicorp/terraform-provider-aws|v1.60.1-0.20220322001452-8f7a597d0c24|直接依赖|go|
|com.amazonaws:jmespath-java|1.11.903|直接依赖|maven|
|github.com/aws/aws-sdk-go-v2/service/bedrockagent|v1.12.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/shield|v1.25.10|直接依赖|go|
|github.com/aws/smithy-go|v1.20.2|直接依赖|go|
|com.amazonaws:aws-java-sdk-sts|1.11.803|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)