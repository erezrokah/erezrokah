# Hello lovely people 👋

Some of the nice things I did/doing

## Roles
- Lead maintainer at [CloudQuery](https://github.com/cloudquery/cloudquery)
- Previously lead maintainer [Netlify CLI](https://github.com/netlify/cli)
- Previously lead maintainer Netlify CMS, now [Decap CMS](https://github.com/decaporg/decap-cms)

## Open Source Contributions

### ClickHouse
- [3x improvement in memory allocations in ClickHouse Go SDK](https://github.com/ClickHouse/clickhouse-go/pull/1686). [Pushed](https://github.com/ClickHouse/ClickHouse/pull/80761#issuecomment-3460823094) ClickHouse to fix this on the server side
- [Fixed panic when scanning nullable JSON](https://github.com/ClickHouse/clickhouse-go/pull/1770)
- [5 fixes to the ClickHouse SQL parser](https://github.com/AfterShip/clickhouse-sql-parser/pulls?q=author%3Aerezrokah) — keyword handling, union distinct parsing, AST traversal

### Apache Arrow
- [Added configurable Timestamp output layout](https://github.com/apache/arrow-go/pull/510)
- [Fixed int8/uint8 JSON marshaling](https://github.com/apache/arrow/pull/35950) after discovering [int64/uint64 data loss](https://github.com/apache/arrow/issues/35948)

### Cloud SDKs
- [Discovered memory issues in AWS S3 Go SDK](https://github.com/aws/aws-sdk-go-v2/issues/2694) and suggested a fix that was later adopted
- [Discovered memory issues in Azure Go SDK](https://github.com/Azure/azure-sdk-for-go/issues/20470#issuecomment-2414374957) — plus [14 issues filed](https://github.com/Azure/azure-sdk-for-go/issues?q=author%3Aerezrokah) covering wrong API versions, pagination bugs, and missing data
- Reported breaking changes shipped as minor versions in [AWS SDK](https://github.com/aws/aws-sdk-go-v2/issues?q=author%3Aerezrokah) and [Google Cloud Go SDK](https://github.com/googleapis/google-cloud-go/issues?q=author%3Aerezrokah)
- [Fixed retry re-auth in Okta Go SDK](https://github.com/okta/okta-sdk-golang/pull/562)

### Go Libraries
- [Added rate limit blocking to google/go-github](https://github.com/google/go-github/pull/3117)
- [Fixed nil embedded struct panics in go-funk](https://github.com/thoas/go-funk/pull/159)
- Reported bugs in [go-ora](https://github.com/sijms/go-ora/issues/378), [sqlboiler](https://github.com/aarondl/sqlboiler/issues/1308), [bigquery-emulator](https://github.com/goccy/bigquery-emulator/issues/150)

### Infrastructure & DevOps
- [Added HTTP2 cleartext (h2c) support to Docker Registry](https://github.com/distribution/distribution/pull/4248). Needed to support deploying to GCP Cloud Run
- [Fixed sequential-calls bug in release-please](https://github.com/googleapis/release-please/pull/1865)
- [Clarified cache deletion limits in GitHub docs](https://github.com/github/docs/pull/26252)
- [Fixed branch name sanitization in repo-file-sync-action](https://github.com/BetaHuhn/repo-file-sync-action/pull/200)
- [2 fixes to OSSF package manager best practices](https://github.com/ossf/package-manager-best-practices/pulls?q=is%3Apr+author%3Aerezrokah+is%3Aclosed)
