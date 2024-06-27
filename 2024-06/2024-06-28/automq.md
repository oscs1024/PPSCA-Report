# AutoMQ/automq安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1806396685447061504.svg)](https://www.murphysec.com/console/report/1785371524796239872/1806396685447061504)

> 点击徽章可查看详细项目安全报告

仓库描述：AutoMQ is a cloud-native fork of Kafka by separating storage to S3 and EBS. 10x cost-effective. Autoscale in seconds. Single-digit ms latency.

仓库地址：[https://github.com/AutoMQ/automq](https://github.com/AutoMQ/automq)

| star：1864 | watch：23 | fork：88 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2024-06-27 18:54:10 | 许可证：- |
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
|BSD-3-Clause|17|Low|
|Apache-2.0|239|Low|
|LGPL-2.1-or-later|2|Medium|
|LGPL-2.1-only|11|Medium|
|EPL-1.0|12|Low|
|EDL-1.0|9|Low|
|GPL-2.0-with-classpath-exception|31|Medium|
|CDDL-1.1|8|Low|
|MIT|30|Low|
|BSD-2-Clause|10|Low|
|WTFPL|2|Low|
|GPL-1.0-only|2|Medium|
|CC0-1.0|5|Low|
|LicenseRef-scancode-public-domain|7|Low|
|W3C|5|Low|
|LGPL, version 2.1|3|Low|
|EPL-2.0|27|Low|
|EPL 2.0|6|Low|
|Apache License, 2.0|4|Low|
|The GNU General Public License (GPL), Version 2, With Classpath Exception|4|Low|
|Modified BSD|2|Low|
|)|3|Low|
|LGPL-3.0-only|1|Medium|
|GNU Lesser General Public License version 3|1|Low|
|GPL2 w/ CPE|2|Low|
|CDDL-1.0|2|Low|
|GPL-2.0-only|2|Medium|
|MIT-0|1|Low|
|Public Domain, per Creative Commons CC0|2|Low|
|MPL-1.1|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.eclipse.jetty:jetty-continuation|9.4.54.v20240208|间接依赖|maven|
|org.ow2.asm:asm-util|9.2|间接依赖|maven|
|com.google.guava:failureaccess|1.0.1|间接依赖|maven|
|software.amazon.awssdk:http-client-spi||直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-jmx-metrics||直接依赖|maven|
|com.github.jnr:jnr-constants|0.10.4|间接依赖|maven|
|net.java.dev.jna:jna-platform||直接依赖|maven|
|org.eclipse.jetty:jetty-servlet||直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations|2.16.2|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2|2.39.1|直接依赖|maven|
|software.amazon.awssdk:aws-query-protocol||直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine||直接依赖|maven|
|io.netty:netty-codec||直接依赖|maven|
|io.netty:netty-handler|4.1.94.Final|间接依赖|maven|
|jakarta.activation:jakarta.activation-api||直接依赖|maven|
|io.netty:netty-codec-http2|4.1.94.Final|间接依赖|maven|
|io.netty:netty-transport-native-epoll||直接依赖|maven|
|io.netty:netty-common||直接依赖|maven|
|::connect:json||直接依赖|maven|
|software.amazon.awssdk:utils|2.20.127|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind||直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk8|1.9.10|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8|2.16.2|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-runtime-telemetry-java8||直接依赖|maven|
|software.amazon.awssdk:annotations|2.20.127|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-scala||直接依赖|maven|
|org.ow2.asm:asm-commons|9.2|间接依赖|maven|
|javax.activation:javax.activation-api||直接依赖|maven|
|com.typesafe.scala-logging:scala-logging||直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp|1.32.0|直接依赖|maven|
|com.google.guava:guava||直接依赖|maven|
|io.netty:netty-resolver|4.1.94.Final|间接依赖|maven|
|org.pcollections:pcollections||直接依赖|maven|
|ch.qos.reload4j:reload4j||直接依赖|maven|
|org.jline:jline||直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv||直接依赖|maven|
|org.eclipse.jetty:jetty-continuation||直接依赖|maven|
|org.objenesis:objenesis|3.3|间接依赖|maven|
|org.apache.maven:maven-artifact||直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common||直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-logging||直接依赖|maven|
|org.checkerframework:checker-qual||直接依赖|maven|
|org.pcollections:pcollections|4.0.1|直接依赖|maven|
|org.eclipse.jetty:jetty-servlets||直接依赖|maven|
|software.amazon.awssdk:protocol-core|2.20.127|间接依赖|maven|
|org.mockito:mockito-core|5.10.0|直接依赖|maven|
|org.reflections:reflections|0.10.2|直接依赖|maven|
|software.amazon.awssdk:regions||直接依赖|maven|
|software.amazon.awssdk:netty-nio-client|2.20.127|直接依赖|maven|
|org.apache.zookeeper:zookeeper|3.8.4|直接依赖|maven|
|org.eclipse.jetty:jetty-http||直接依赖|maven|
|io.netty:netty-resolver||直接依赖|maven|
|org.scala-lang:scala-library|2.13.14|直接依赖|maven|
|io.netty:netty-transport|4.1.94.Final|间接依赖|maven|
|software.amazon.awssdk:utils||直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core||直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-logging|1.32.0|直接依赖|maven|
|software.amazon.awssdk:netty-nio-client||直接依赖|maven|
|org.ow2.asm:asm||直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-sender-okhttp|1.32.0|间接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.94.Final|间接依赖|maven|
|net.java.dev.jna:jna|5.8.0|间接依赖|maven|
|org.eclipse.jetty:jetty-util|9.4.54.v20240208|间接依赖|maven|
|io.opentelemetry:opentelemetry-extension-incubator|1.32.0-alpha|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|software.amazon.awssdk:annotations||直接依赖|maven|
|org.aspectj:aspectjweaver||直接依赖|maven|
|org.apache.yetus:audience-annotations|0.12.0|间接依赖|maven|
|com.google.protobuf:protobuf-java||直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk|1.32.0|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-jdk7|1.9.10|间接依赖|maven|
|commons-cli:commons-cli||直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet|2.39.1|直接依赖|maven|
|javax.xml.bind:jaxb-api|2.3.1|直接依赖|maven|
|com.github.spotbugs:spotbugs-annotations|4.8.0|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp-common|1.32.0|间接依赖|maven|
|::automq-shell||直接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.53.Final|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-prometheus|1.32.0-alpha|直接依赖|maven|
|org.glassfish.hk2:hk2-utils|2.6.1|间接依赖|maven|
|com.bucket4j:bucket4j-core||直接依赖|maven|
|io.netty:netty-transport||直接依赖|maven|
|software.amazon.awssdk:apache-client|2.20.127|间接依赖|maven|
|net.java.dev.jna:jna-platform|5.8.0|间接依赖|maven|
|org.apache.httpcomponents:httpcore|4.4.13|间接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api|2.1.6|间接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|com.google.code.findbugs:jsr305|3.0.2|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-api||直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider||直接依赖|maven|
|software.amazon.awssdk:regions|2.20.127|间接依赖|maven|
|org.glassfish.jersey.core:jersey-common|2.39.1|间接依赖|maven|
|io.netty:netty-buffer||直接依赖|maven|
|org.openjdk.jmh:jmh-core||直接依赖|maven|
|io.opentelemetry.semconv:opentelemetry-semconv||直接依赖|maven|
|software.amazon.awssdk:metrics-spi|2.20.127|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base||直接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|org.ow2.asm:asm-tree|9.2|间接依赖|maven|
|org.glassfish.jersey.core:jersey-server|2.39.1|间接依赖|maven|
|::storage:storage-api||直接依赖|maven|
|io.netty:netty-handler|4.1.110.Final|间接依赖|maven|
|software.amazon.awssdk:arns||直接依赖|maven|
|com.fasterxml.jackson:jackson-bom|2.16.2|间接依赖|maven|
|::streams||直接依赖|maven|
|io.swagger.core.v3:swagger-annotations|2.2.8|直接依赖|maven|
|com.squareup.okhttp3:okhttp|4.12.0|间接依赖|maven|
|org.scala-lang:scala-reflect||直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace|1.32.0|间接依赖|maven|
|com.github.jnr:jffi||直接依赖|maven|
|org.mockito:mockito-core||直接依赖|maven|
|org.slf4j:slf4j-api|2.0.9|直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute||直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-api-semconv|1.32.0-alpha|间接依赖|maven|
|io.opentelemetry:opentelemetry-api|1.32.0|直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-afterburner||直接依赖|maven|
|javax.servlet:javax.servlet-api|3.1.0|间接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-base|2.16.2|间接依赖|maven|
|org.glassfish.hk2:hk2-locator|2.6.1|间接依赖|maven|
|org.slf4j:slf4j-reload4j||直接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator|1.0.3|间接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core|2.20.127|间接依赖|maven|
|com.github.jnr:jnr-posix|3.1.19|直接依赖|maven|
|software.amazon.awssdk:s3|2.20.127|直接依赖|maven|
|org.reactivestreams:reactive-streams|1.0.3|间接依赖|maven|
|javax.activation:activation|1.1.1|直接依赖|maven|
|software.amazon.awssdk:aws-query-protocol|2.20.127|间接依赖|maven|
|org.rocksdb:rocksdbjni||直接依赖|maven|
|com.github.jnr:jnr-a64asm|1.0.0|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol||直接依赖|maven|
|commons-digester:commons-digester|2.1|间接依赖|maven|
|software.amazon.awssdk:aws-xml-protocol|2.20.127|间接依赖|maven|
|org.glassfish.hk2:osgi-resource-locator||直接依赖|maven|
|commons-cli:commons-cli|1.4|直接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject||直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api||直接依赖|maven|
|commons-beanutils:commons-beanutils||直接依赖|maven|
|javax.activation:javax.activation-api|1.2.0|间接依赖|maven|
|net.java.dev.jna:jna-platform-jpms||直接依赖|maven|
|io.netty:netty-codec|4.1.94.Final|间接依赖|maven|
|::s3stream||直接依赖|maven|
|org.ow2.asm:asm-commons||直接依赖|maven|
|io.netty:netty-codec|4.1.110.Final|间接依赖|maven|
|commons-io:commons-io|2.15.1|直接依赖|maven|
|javax.annotation:javax.annotation-api|1.3.2|直接依赖|maven|
|com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider|2.16.2|直接依赖|maven|
|info.picocli:picocli||直接依赖|maven|
|org.apache.commons:commons-lang3|3.12.0|直接依赖|maven|
|software.amazon.awssdk:aws-core|2.20.127|间接依赖|maven|
|software.amazon.awssdk:sdk-core|2.20.127|间接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-jaxb-annotations||直接依赖|maven|
|net.java.dev.jna:jna-platform-jpms|5.13.0|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.16.2|间接依赖|maven|
|com.github.jnr:jnr-posix||直接依赖|maven|
|com.github.jnr:jnr-ffi||直接依赖|maven|
|org.xerial.snappy:snappy-java||直接依赖|maven|
|org.reactivestreams:reactive-streams||直接依赖|maven|
|org.scala-lang:scala-reflect|2.13.14|直接依赖|maven|
|software.amazon.awssdk:sdk-core||直接依赖|maven|
|software.amazon.awssdk:json-utils|2.20.127|间接依赖|maven|
|org.glassfish.jersey.inject:jersey-hk2||直接依赖|maven|
|net.bytebuddy:byte-buddy|1.14.11|间接依赖|maven|
|commons-beanutils:commons-beanutils|1.9.4|间接依赖|maven|
|com.google.code.findbugs:jsr305||直接依赖|maven|
|com.google.guava:guava|32.0.1-jre|直接依赖|maven|
|software.amazon.awssdk:http-client-spi|2.20.127|间接依赖|maven|
|org.hdrhistogram:HdrHistogram||直接依赖|maven|
|software.amazon.awssdk:auth|2.20.127|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-api-semconv||直接依赖|maven|
|software.amazon.awssdk:endpoints-spi||直接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged|2.6.1|间接依赖|maven|
|::metadata||直接依赖|maven|
|::core||直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-extension-autoconfigure-spi|1.32.0|间接依赖|maven|
|org.codehaus.plexus:plexus-utils|3.5.1|间接依赖|maven|
|org.rocksdb:rocksdbjni|7.9.2|直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core|2.16.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-context||直接依赖|maven|
|com.github.luben:zstd-jni|1.5.6-3|直接依赖|maven|
|io.opentelemetry.semconv:opentelemetry-semconv|1.21.0-alpha|间接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax|9.4.54.v20240208|间接依赖|maven|
|io.netty:netty-codec-http|4.1.94.Final|间接依赖|maven|
|org.eclipse.jetty:jetty-servlet|9.4.54.v20240208|直接依赖|maven|
|org.eclipse.jetty:jetty-security|9.4.54.v20240208|间接依赖|maven|
|org.eclipse.jetty:jetty-http|9.4.54.v20240208|间接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.9.10|间接依赖|maven|
|::raft||直接依赖|maven|
|io.opentelemetry:opentelemetry-context|1.32.0|间接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.65.Final|间接依赖|maven|
|ch.qos.reload4j:reload4j|1.2.25|直接依赖|maven|
|org.eclipse.jetty:jetty-client|9.4.54.v20240208|直接依赖|maven|
|commons-logging:commons-logging|1.2|间接依赖|maven|
|com.github.jnr:jnr-ffi|2.2.16|间接依赖|maven|
|net.bytebuddy:byte-buddy-agent||直接依赖|maven|
|jakarta.validation:jakarta.validation-api|2.0.2|间接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.94.Final|间接依赖|maven|
|::server-common||直接依赖|maven|
|org.slf4j:jul-to-slf4j||直接依赖|maven|
|com.github.spotbugs:spotbugs-annotations||直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-prometheus||直接依赖|maven|
|software.amazon.eventstream:eventstream||直接依赖|maven|
|com.github.ben-manes.caffeine:caffeine|2.9.3|直接依赖|maven|
|org.scala-lang.modules:scala-java8-compat||直接依赖|maven|
|io.dropwizard.metrics:metrics-core||直接依赖|maven|
|org.lz4:lz4-java||直接依赖|maven|
|org.apache.commons:commons-math3||直接依赖|maven|
|javax.annotation:javax.annotation-api||直接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations||直接依赖|maven|
|::connect:runtime||直接依赖|maven|
|commons-digester:commons-digester||直接依赖|maven|
|io.netty:netty-transport-classes-epoll|4.1.110.Final|间接依赖|maven|
|org.openjdk.jmh:jmh-core-benchmarks|1.37|直接依赖|maven|
|org.apache.httpcomponents:httpclient|4.5.13|间接依赖|maven|
|org.apache.commons:commons-lang3||直接依赖|maven|
|org.glassfish.hk2:hk2-utils||直接依赖|maven|
|io.netty:netty-resolver|4.1.110.Final|间接依赖|maven|
|software.amazon.awssdk:auth||直接依赖|maven|
|org.glassfish.hk2.external:aopalliance-repackaged||直接依赖|maven|
|:+--- org.bitbucket.b_c:jose4j:0.9.4||直接依赖|maven|
|org.glassfish.jersey.core:jersey-client||直接依赖|maven|
|org.javassist:javassist||直接依赖|maven|
|io.netty:netty-transport-classes-epoll||直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|直接依赖|maven|
|org.ow2.asm:asm|9.2|间接依赖|maven|
|commons-validator:commons-validator||直接依赖|maven|
|org.glassfish.jersey.core:jersey-common||直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics||直接依赖|maven|
|com.thoughtworks.paranamer:paranamer||直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-runtime-telemetry-java8|1.32.0-alpha|直接依赖|maven|
|com.google.protobuf:protobuf-java|3.23.4|直接依赖|maven|
|net.sf.jopt-simple:jopt-simple|5.0.4|直接依赖|maven|
|com.google.errorprone:error_prone_annotations|2.18.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-common|1.32.0|间接依赖|maven|
|software.amazon.awssdk:profiles|2.20.127|间接依赖|maven|
|com.squareup.okio:okio-jvm|3.6.0|间接依赖|maven|
|com.github.oshi:oshi-core-java11||直接依赖|maven|
|org.aspectj:aspectjrt||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.16.0|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs||直接依赖|maven|
|org.eclipse.jetty:jetty-util-ajax||直接依赖|maven|
|net.sourceforge.argparse4j:argparse4j|0.9.0|直接依赖|maven|
|::connect:mirror-client||直接依赖|maven|
|info.picocli:picocli|4.7.6|直接依赖|maven|
|net.sourceforge.argparse4j:argparse4j||直接依赖|maven|
|javax.xml.bind:jaxb-api||直接依赖|maven|
|org.apache.maven:maven-artifact|3.9.6|直接依赖|maven|
|com.yammer.metrics:metrics-core|2.2.0|直接依赖|maven|
|software.amazon.awssdk:s3||直接依赖|maven|
|io.netty:netty-codec-http2||直接依赖|maven|
|org.apache.zookeeper:zookeeper-jute|3.8.4|间接依赖|maven|
|org.glassfish.jersey.containers:jersey-container-servlet-core|2.39.1|间接依赖|maven|
|com.github.jnr:jffi|1.3.13|间接依赖|maven|
|javax.activation:activation||直接依赖|maven|
|jakarta.validation:jakarta.validation-api||直接依赖|maven|
|org.ow2.asm:asm-analysis|9.2|间接依赖|maven|
|:+--- org.bitbucket.b_c:jose4j:{strictly 0.9.4} -> 0.9.4 (c)||直接依赖|maven|
|com.fasterxml.jackson:jackson-bom||直接依赖|maven|
|org.apache.commons:commons-lang3|3.13.0|直接依赖|maven|
|io.netty:netty-transport-native-epoll|4.1.110.Final|间接依赖|maven|
|io.netty:netty-codec-http||直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-trace||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.16.2|直接依赖|maven|
|org.ow2.asm:asm-tree||直接依赖|maven|
|org.eclipse.jetty:jetty-security||直接依赖|maven|
|::clients||直接依赖|maven|
|com.google.guava:listenablefuture|9999.0-empty-to-avoid-conflict-with-guava|间接依赖|maven|
|org.lz4:lz4-java|1.8.0|直接依赖|maven|
|io.opentelemetry:opentelemetry-bom|1.29.0|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-annotations||直接依赖|maven|
|io.netty:netty-transport|4.1.110.Final|间接依赖|maven|
|io.dropwizard.metrics:metrics-core|4.1.12.1|直接依赖|maven|
|com.github.jnr:jnr-constants||直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-api|1.32.0|间接依赖|maven|
|software.amazon.awssdk:profiles||直接依赖|maven|
|org.eclipse.jetty:jetty-util||直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api|2.3.3|间接依赖|maven|
|com.fasterxml.jackson.datatype:jackson-datatype-jdk8||直接依赖|maven|
|::transaction-coordinator||直接依赖|maven|
|org.checkerframework:checker-qual|3.19.0|间接依赖|maven|
|com.google.guava:listenablefuture||直接依赖|maven|
|io.netty:netty-tcnative-boringssl-static|2.0.65.Final|直接依赖|maven|
|net.bytebuddy:byte-buddy||直接依赖|maven|
|org.ow2.asm:asm-util||直接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.glassfish.hk2:hk2-api||直接依赖|maven|
|io.netty:netty-tcnative-classes|2.0.53.Final|间接依赖|maven|
|net.sf.jopt-simple:jopt-simple||直接依赖|maven|
|io.netty:netty-buffer|4.1.94.Final|间接依赖|maven|
|commons-collections:commons-collections||直接依赖|maven|
|jakarta.xml.bind:jakarta.xml.bind-api||直接依赖|maven|
|org.scala-lang.modules:scala-collection-compat||直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.9.10|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk||直接依赖|maven|
|com.github.oshi:oshi-core-java11|6.4.7|直接依赖|maven|
|jakarta.ws.rs:jakarta.ws.rs-api||直接依赖|maven|
|software.amazon.awssdk:protocol-core||直接依赖|maven|
|net.java.dev.jna:jna-jpms|5.13.0|间接依赖|maven|
|org.ow2.asm:asm-analysis||直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-instrumentation-annotations|1.32.0|直接依赖|maven|
|com.github.jnr:jnr-x86asm|1.0.2|间接依赖|maven|
|org.glassfish.jersey.core:jersey-client|2.39.1|间接依赖|maven|
|org.aspectj:aspectjweaver|1.9.20.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-api||直接依赖|maven|
|com.bucket4j:bucket4j-core|8.5.0|直接依赖|maven|
|io.netty:netty-common|4.1.94.Final|间接依赖|maven|
|commons-validator:commons-validator|1.7|直接依赖|maven|
|org.jline:jline|3.25.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-logs|1.32.0|间接依赖|maven|
|software.amazon.awssdk:crt-core|2.20.127|间接依赖|maven|
|com.google.j2objc:j2objc-annotations|2.8|间接依赖|maven|
|jakarta.activation:jakarta.activation-api|1.2.2|间接依赖|maven|
|org.eclipse.jetty:jetty-io|9.4.54.v20240208|间接依赖|maven|
|commons-logging:commons-logging||直接依赖|maven|
|net.java.dev.jna:jna|5.2.0|直接依赖|maven|
|javax.ws.rs:javax.ws.rs-api|2.1.1|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-oshi||直接依赖|maven|
|io.netty:netty-codec-http2|4.1.110.Final|直接依赖|maven|
|software.amazon.awssdk:third-party-jackson-core||直接依赖|maven|
|org.checkerframework:checker-qual|3.33.0|间接依赖|maven|
|io.netty:netty-handler||直接依赖|maven|
|org.apache.yetus:audience-annotations||直接依赖|maven|
|::log4j-appender||直接依赖|maven|
|commons-collections:commons-collections|3.2.2|间接依赖|maven|
|com.github.jnr:jnr-a64asm||直接依赖|maven|
|org.scala-lang:scala-library||直接依赖|maven|
|org.xerial.snappy:snappy-java|1.1.10.5|直接依赖|maven|
|io.netty:netty-transport-native-unix-common|4.1.110.Final|间接依赖|maven|
|org.snakeyaml:snakeyaml-engine|2.7|间接依赖|maven|
|software.amazon.awssdk:metrics-spi||直接依赖|maven|
|org.eclipse.jetty:jetty-client||直接依赖|maven|
|commons-codec:commons-codec|1.15|间接依赖|maven|
|com.google.j2objc:j2objc-annotations||直接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|::connect:api||直接依赖|maven|
|com.fasterxml.jackson.dataformat:jackson-dataformat-csv|2.16.2|直接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-metrics|1.32.0|直接依赖|maven|
|io.netty:netty-codec-http|4.1.110.Final|间接依赖|maven|
|io.opentelemetry:opentelemetry-sdk-common|1.32.0|间接依赖|maven|
|software.amazon.awssdk:crt-core||直接依赖|maven|
|org.codehaus.plexus:plexus-utils||直接依赖|maven|
|software.amazon.awssdk:endpoints-spi|2.20.127|间接依赖|maven|
|software.amazon.eventstream:eventstream|1.0.1|间接依赖|maven|
|org.slf4j:slf4j-log4j12||直接依赖|maven|
|org.slf4j:slf4j-log4j12|1.7.36|直接依赖|maven|
|io.opentelemetry.proto:opentelemetry-proto||直接依赖|maven|
|::tools:tools-api||直接依赖|maven|
|net.bytebuddy:byte-buddy-agent|1.14.11|间接依赖|maven|
|org.glassfish.hk2:hk2-api|2.6.1|间接依赖|maven|
|com.yammer.metrics:metrics-core||直接依赖|maven|
|io.swagger.core.v3:swagger-annotations||直接依赖|maven|
|org.slf4j:slf4j-reload4j|1.7.36|间接依赖|maven|
|com.google.errorprone:error||直接依赖|maven|
|com.github.luben:zstd-jni||直接依赖|maven|
|org.eclipse.jetty:jetty-servlets|9.4.54.v20240208|直接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-oshi|1.32.0-alpha|直接依赖|maven|
|com.thoughtworks.paranamer:paranamer|2.8|间接依赖|maven|
|com.fasterxml.jackson.core:jackson-annotations|2.16.2|直接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|
|org.reflections:reflections||直接依赖|maven|
|io.netty:netty-transport-native-unix-common||直接依赖|maven|
|org.apache.zookeeper:zookeeper||直接依赖|maven|
|::connect:transforms||直接依赖|maven|
|org.openjdk.jmh:jmh-core|1.37|直接依赖|maven|
|::server||直接依赖|maven|
|net.java.dev.jna:jna-jpms||直接依赖|maven|
|javax.ws.rs:javax.ws.rs-api||直接依赖|maven|
|io.opentelemetry.proto:opentelemetry-proto|1.0.0-alpha|直接依赖|maven|
|io.opentelemetry:opentelemetry-api-events|1.32.0-alpha|间接依赖|maven|
|org.aspectj:aspectjrt|1.9.20.1|直接依赖|maven|
|io.opentelemetry:opentelemetry-exporter-otlp||直接依赖|maven|
|::group-coordinator||直接依赖|maven|
|software.amazon.awssdk:json-utils||直接依赖|maven|
|com.squareup.okio:okio|3.6.0|间接依赖|maven|
|org.slf4j:slf4j-api||直接依赖|maven|
|org.glassfish.jersey.core:jersey-server||直接依赖|maven|
|:+--- org.bitbucket.b_c:jose4j:0.9.4 (*)||直接依赖|maven|
|org.eclipse.jetty:jetty-server|9.4.54.v20240208|直接依赖|maven|
|software.amazon.awssdk:arns|2.20.127|间接依赖|maven|
|com.github.jnr:jnr-x86asm||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-core||直接依赖|maven|
|org.eclipse.jetty:jetty-server||直接依赖|maven|
|javax.servlet:javax.servlet-api||直接依赖|maven|
|org.hdrhistogram:HdrHistogram|2.1.12|直接依赖|maven|
|:No dependencies||直接依赖|maven|
|:|    +--- org.bitbucket.b_c:jose4j:0.9.4||间接依赖|maven|
|net.java.dev.jna:jna||直接依赖|maven|
|commons-io:commons-io||直接依赖|maven|
|com.fasterxml.jackson.module:jackson-module-afterburner|2.16.2|直接依赖|maven|
|org.javassist:javassist|3.29.2-GA|间接依赖|maven|
|org.eclipse.jetty:jetty-io||直接依赖|maven|
|io.netty:netty-buffer|4.1.110.Final|直接依赖|maven|
|org.glassfish.hk2:hk2-locator||直接依赖|maven|
|com.fasterxml.jackson.core:jackson-databind|2.16.0|直接依赖|maven|
|io.netty:netty-common|4.1.110.Final|直接依赖|maven|
|org.openjdk.jmh:jmh-core-benchmarks||直接依赖|maven|
|org.glassfish.hk2.external:jakarta.inject|2.6.1|间接依赖|maven|
|io.opentelemetry.instrumentation:opentelemetry-jmx-metrics|1.32.0-alpha|直接依赖|maven|
|com.google.guava:failureaccess||直接依赖|maven|
|software.amazon.awssdk:aws-core||直接依赖|maven|
|::storage||直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)