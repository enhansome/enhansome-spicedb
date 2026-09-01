# Awesome SpiceDB with stars

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![Docs](https://img.shields.io/badge/docs-authzed.com-%234B4B6C "Authzed Documentation")](https://docs.authzed.com)
[![Discord Server](https://img.shields.io/discord/844600078504951838?color=7289da\&logo=discord "Discord Server")](https://discord.gg/jTysUaxXzM)
[![Twitter](https://img.shields.io/badge/twitter-%40authzed-1D8EEE?logo=twitter "@authzed on Twitter")](https://twitter.com/authzed)

An awesome list for the [SpiceDB] ecosystem.

Have questions? Join our [Discord].

Looking to contribute? See [CONTRIBUTING.md].

[SpiceDB]: https://github.com/authzed/spicedb

[Discord]: https://authzed.com/discord

[CONTRIBUTING.md]: https://github.com/authzed/spicedb/blob/main/CONTRIBUTING.md

## Contents

* [Awesome SpiceDB](#awesome-spicedb)
  * [Contents](#contents)
  * [Blog Posts](#blog-posts)
    * [English](#english)
    * [日本語](#日本語)
    * [中文](#中文)
  * [Clients](#clients)
    * [Official Libraries](#official-libraries)
    * [Third-party Libraries](#third-party-libraries)
  * [Communities](#communities)
  * [Developer Tools](#developer-tools)
    * [Official Tools](#official-tools)
    * [Third-party Tools](#third-party-tools)
  * [Examples](#examples)
  * [Integrations](#integrations)
    * [Official Integrations](#official-integrations)
    * [Third-party Integrations](#third-party-integrations)
  * [Services](#services)
  * [Testing](#testing)

## Blog Posts

*Posts written about SpiceDB usage and development*

### English

* [Authzed's Official Blog](https://authzed.com/blog)
* [ABAC on SpiceDB: Enabling Netflix’s Complex Identity Types](https://netflixtechblog.com/abac-on-spicedb-enabling-netflixs-complex-identity-types-c118f374fa89)
* Abhishek Koserwal's SpiceDB Setup Guide: [Part 1](https://akoserwal.medium.com/a-comprehensive-guide-to-setting-up-spicedb-with-postgresql-and-a-monitoring-stack-b250f31d7775), [Part 2](https://akoserwal.medium.com/part-2-a-comprehensive-guide-to-setting-up-spicedb-operator-with-postgresql-and-a-monitoring-stack-3b3f92e20d77), [Performance vs. Accuracy Trade-offs](https://medium.com/@akoserwal/spicedb-consistency-a-deep-dive-into-performance-vs-accuracy-trade-offs-76e2fb2f29b9)
* [Modeling Google Drive in SpiceDB](https://www.mbilski.com/posts/fine-grained-authorization-made-easy-modeling-google-drive-in-spicedb)
* [KPMG: Getting Started with SpiceDB in .NET](https://medium.com/kpmg-uk-engineering/getting-started-with-spicedb-in-net-741e353a4d83)
* [Spicing up the Authorization Layer at Quizizz](https://eng.quizizz.com/p/spicing-up-the-authorization-layer)
* [SpiceDB HRBAC: A Practical Implementation](https://dev.to/irby/spicedb-hrbac-a-practical-implementation-1lbd)

### 日本語

* [SpiceDBで認可制御するLambda Authorizerを作ってみた](https://zenn.dev/manaty226/articles/96b6b693c6621c)
* [分散モノリスを解消して、モジュラモノリスとして扱うために](https://logmi.jp/tech/articles/329073)

### 中文

* [\[源码\]spicedb: 源码阅读之第一篇(热点缓存)](https://kylinlingh.github.io/2023/06/28/%E6%BA%90%E7%A0%81-spicedb-%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB%E4%B9%8B%E7%AC%AC%E4%B8%80%E7%AF%87-%E7%83%AD%E7%82%B9%E7%BC%93%E5%AD%98/)
* [\[源码\]spicedb: 源码阅读之第二篇(k8s 部署和运行)](https://kylinlingh.github.io/2023/07/19/%E6%BA%90%E7%A0%81-spicedb-%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB%E4%B9%8B%E7%AC%AC%E4%BA%8C%E7%AF%87-k8s-%E9%83%A8%E7%BD%B2/)
* [Chen Tian, SVP TubiTV China, presents SpiceDB](https://zhuanlan.zhihu.com/p/685603356)

## Clients

*Clients for interacting with SpiceDB*

### Official Libraries

* [authzed-go](https://github.com/authzed/authzed-go) ⭐ 104 | 🐛 22 | 🌐 Go | 📅 2026-07-25 - Official client library for Go
* [authzed-node](https://github.com/authzed/authzed-node) ⭐ 61 | 🐛 44 | 🌐 TypeScript | 📅 2026-05-26 - Official client library for NodeJS in JavaScript/TypeScript
* [authzed-py](https://github.com/authzed/authzed-py) ⭐ 51 | 🐛 17 | 🌐 Python | 📅 2026-07-14 - Official client library for Python
* [authzed-java](https://github.com/authzed/authzed-java) ⭐ 27 | 🐛 17 | 🌐 Java | 📅 2026-06-02 - Official client library for JVM languages in Java
* [authzed-rb](https://github.com/authzed/authzed-rb) ⭐ 21 | 🐛 2 | 🌐 Ruby | 📅 2026-07-20 - Official client library for Ruby
* [authzed-dotnet](https://github.com/authzed/authzed-dotnet) ⭐ 15 | 🐛 4 | 🌐 C# | 📅 2026-08-01 - Official client library for Dotnet/CSharp

### Third-party Libraries

* Golang
  * [danhtran94/authzed-codegen](https://github.com/danhtran94/authzed-codegen) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2026-05-10 - Type-Safe stubs code generator for your AuthZed schemas
* .NET
  * [jalexsocial/spicedb](https://github.com/JalexSocial/SpiceDb) ⭐ 24 | 🐛 1 | 🌐 C# | 📅 2025-09-12 - gRPC client library in C#
* BEAM
  * [goodhamgupta/authzed-ex](https://github.com/goodhamgupta/authzed_ex) ⭐ 23 | 🐛 0 | 🌐 Elixir | 📅 2026-04-08 - gRPC client library in Elixir
* JavaScript/Typescript
  * [yahiaosama/authz-schema-sync-check](https://github.com/yahiaosama/authz-schema-sync-check) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-01-26 - tool to generate Python and Node type definitions from SpiceDB Schema.
  * [SchoolAI/spicedb-zed-schema-parser](https://github.com/SchoolAI/spicedb-zed-schema-parser) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-19 - A tool to generate schema-aware typescript types and a type-safe wrapper for [authzed-node](https://github.com/authzed/authzed-node) ⭐ 61 | 🐛 44 | 🌐 TypeScript | 📅 2026-05-26
  * [quizizz/spicedb-wrapper](https://github.com/quizizz/spicedb-wrapper) ⭐ 0 | 🐛 2 | 🌐 TypeScript | 📅 2026-02-11 - Lightweight client wrapper of [authzed-node](https://github.com/authzed/authzed-node) ⭐ 61 | 🐛 44 | 🌐 TypeScript | 📅 2026-05-26
* JVM
  * [oviva-ag/spicegen](https://github.com/oviva-ag/spicegen) ⭐ 12 | 🐛 3 | 🌐 Java | 📅 2026-07-01 - type-safe client generator from a schema
  * [quarkiverse/quarkus-authzed-client](https://github.com/quarkiverse/quarkus-authzed-client) ⭐ 8 | 🐛 11 | 🌐 Java | 📅 2026-08-31 - gRPC client integration for Quarkus
* PHP
  * [alsbury/chiphpotle-rest](https://github.com/alsbury/chiphpotle-rest) ⭐ 7 | 🐛 1 | 🌐 PHP | 📅 2025-05-02 - HTTP client library in PHP
  * [linkorb/spicedb-php](https://github.com/linkorb/spicedb-php) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2026-07-17 - HTTP client library in PHP
  * [linkorb/spicedb-bundle](https://github.com/linkorb/spicedb-bundle) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2025-06-08 - SpiceDB client Symfony Bundle
* Python
  * [yahiaosama/authz-schema-sync-check](https://github.com/yahiaosama/authz-schema-sync-check) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-01-26 - tool to generate Python and Node type definitions from SpiceDB Schema.
* Rust
  * [Lur1an/spicedb-rust](https://github.com/Lur1an/spicedb-rust) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2024-12-01 - Opinionated SpiceDB gRPC client library in Rust
  * [bitskico/authzed-rs](https://github.com/BitskiCo/authzed-rs) ⚠️ Archived - gRPC client library in Rust
  * [structionsite/spicedb-client-rust](https://github.com/StructionSite/spicedb-client-rust) ⭐ 1 | 🐛 1 | 🌐 Rust | 📅 2023-09-08 - gRPC client library in Rust

## Communities

*Online forums for discussing SpiceDB and meeting other users*

* [SpiceDB Discord](https://authzed.com/discord) - Discord community for SpiceDB
* [Authzed Linen](https://linen.authzed.com) - Searchable archive for the SpiceDB Discord
* [StackOverflow](https://stackoverflow.com/questions/tagged/spicedb) - StackOverflow questions tagged with SpiceDB
* [Twitter](https://twitter.com/authzed) - Official Authzed Twitter account

## Developer Tools

*Tools that help enhance the experience of using SpiceDB*

### Official Tools

* [zed](https://github.com/authzed/zed) ⭐ 163 | 🐛 54 | 🌐 Go | 📅 2026-08-26 - Official command-line tool for managing SpiceDB
* [SpiceDB Operator](https://github.com/authzed/spicedb-operator) ⭐ 105 | 🐛 42 | 🌐 Go | 📅 2026-09-01 - Official Kubernetes Operator for running SpiceDB
* [Playground](https://play.authzed.com) - Official SpiceDB schema development environment
* Thumper (proprietary) - Official load generation tool for SpiceDB
* [VS Code extension](https://marketplace.visualstudio.com/items?itemName=authzed.spicedb-vscode) - Official SpiceDB Visual Studio Code Extension

### Third-party Tools

* [mejaz/spicedb-ui](https://github.com/mejaz/spicedb-ui) ⭐ 31 | 🐛 5 | 🌐 JavaScript | 📅 2026-07-16 - Third-party SpiceDB web interface that allows inspection and management of a running SpiceDB instance
* [umbrellaassociates/opa-spicedb](https://github.com/umbrellaassociates/opa-spicedb) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2025-10-11 - Third-party build of Open Policy Agent with a plugin to query SpiceDB
* [thomasdarimont/custom-opa-spicedb](https://github.com/thomasdarimont/custom-opa-spicedb) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2024-03-11 - Third-party build of Open Policy Agent with a plugin to query SpiceDB
* [mleonidas/tree-sitter-authzed](https://github.com/mleonidas/tree-sitter-authzed) ⭐ 12 | 🐛 3 | 🌐 JavaScript | 📅 2025-09-11 - Neovim tree-sitter grammar and syntax for SpiceDB schemas
* [chiperific/vscode\_authzed\_syntax](https://github.com/chiperific/vscode_authzed_syntax) ⭐ 6 | 🐛 0 | 📅 2025-08-07 - Third-party VSCode syntax highlighting
* [dguhr/keycloak-spicedb-eventlistener](https://github.com/DGuhr/keycloak-spicedb-eventlistener) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2026-03-04 - Syncs changes to [Keycloak](https://www.keycloak.org) users and groups to SpiceDB
* [bushelpowered/spicedb-operator-chart](https://github.com/bushelpowered/spicedb-operator-chart) ⭐ 4 | 🐛 6 | 🌐 Go Template | 📅 2026-08-26 - Helm chart to install the SpiceDB Operator
* [jeanlouhallee/intellij-spicedb-plugin](https://github.com/jeanlouhallee/intellij-spicedb-plugin) ⭐ 2 | 🐛 2 | 🌐 Java | 📅 2026-01-31 - Community IntelliJ plugin for SpiceDB schema files
* [spicedb-operator-libsonnet](https://github.com/jsonnet-libs/spicedb-operator-libsonnet) ⭐ 1 | 🐛 0 | 🌐 Jsonnet | 📅 2024-05-14 - Jsonnet library for the SpiceDB Operator

## Examples

*Example usage of SpiceDB and the tools in its ecosystem*

* [authzed/examples](https://github.com/authzed/examples) ⭐ 64 | 🐛 3 | 🌐 Python | 📅 2026-08-05 - Official examples repository
* [SpiceDB Helm Chart](https://github.com/jonwhitty/helm-charts/tree/master/charts/spicedb) ⭐ 5 | 🐛 1 | 🌐 Smarty | 📅 2022-03-03 - Helm Chart for an example 3-node deployment

## Integrations

*Projects that integrate with SpiceDB*

### Official Integrations

* [authzed/prom-authzed-proxy](https://github.com/authzed/prom-authzed-proxy) ⭐ 41 | 🐛 4 | 🌐 Go | 📅 2024-07-01 - Prometheus proxy that performs SpiceDB permission checks based on labels
* [authzed/connector-postgres](https://github.com/authzed/connector-postgresql) ⚠️ Archived - Deprecated synchronization between PostgreSQL and SpiceDB

### Third-party Integrations

* [gitpod-io/gitpod](https://github.com/gitpod-io/gitpod) ⭐ 13,760 | 🐛 452 | 🌐 TypeScript | 📅 2026-08-31 - GitPod's support for fine-grained authorization leverages SpiceDB
* [wolfi-dev/os](https://github.com/wolfi-dev/os/blob/main/spicedb.yaml) ⭐ 1,282 | 🐛 84 | 🌐 Shell | 📅 2026-09-01 - Container build toolchain that packages SpiceDB
* [raystack/frontier](https://github.com/raystack/frontier) ⭐ 343 | 🐛 46 | 🌐 Go | 📅 2026-09-01 - Cloud-native, role-based user management system and authorization server for your applications and API endpoints
* [infratographer/permissions-api](https://github.com/infratographer/permissions-api) ⭐ 11 | 🐛 36 | 🌐 Go | 📅 2026-09-01 - The default authorization strategy for Infratographer leverages SpiceDB
* [guicassolato/authorino-spicedb](https://github.com/guicassolato/authorino-spicedb) ⭐ 5 | 🐛 1 | 📅 2023-02-16 - Implementation of [Envoy external authz](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_authz_filter) that can be driven by SpiceDB
* [koralium/flowtide](https://koralium.github.io/flowtide/docs/connectors/spicedb) - Data streaming engine, can read/write data into SpiceDB and can also denormalize SpiceDB permissions when integrating with other databases/systems.
* [Redpanda connector - spicedb\_watch](https://docs.redpanda.com/redpanda-connect/components/inputs/spicedb_watch/) - Consumes messages from the Watch API of a SpiceDB instance. This input is useful if you have downstream applications that need to react to real-time changes in data managed by SpiceDB.

## Services

*Managed services that operate SpiceDB for you*

* [AuthZed Cloud](https://app.authzed.cloud/) - Self-service clusters operated by Authzed
* [AuthZed Dedicated](https://authzed.com/pricing) - Private, isolated clusters operated by the experts at Authzed

## Testing

*Tools and libraries used to test or validate usage of SpiceDB*

* [authzed/action-spicedb-validate](https://github.com/authzed/action-spicedb-validate) ⭐ 16 | 🐛 3 | 🌐 Dockerfile | 📅 2026-02-08 - GitHub Action for validating your SpiceDB schema
* [authzed/action-spicedb](https://github.com/authzed/action-spicedb) ⭐ 11 | 🐛 1 | 🌐 Shell | 📅 2026-07-06 - GitHub Action for integration testing your application with SpiceDB
* [northone-inc/local-spicedb](https://github.com/northone-inc/local-spicedb) ⚠️ Archived - Node library for running SpiceDB ephermally for testing
* [SpiceDB Testcontainer](https://testcontainers.com/modules/spicedb/) - Throwaway, lightweight instances of the SpiceDB Go library in a Docker container for testing.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
