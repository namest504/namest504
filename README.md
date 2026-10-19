### Open Source Contributions

**[Apache Pulsar](https://github.com/apache/pulsar)**
* Added `createMapped`/`createMappedAsync` to build a `TableView` from full messages via `TableViewMessageMapper` (PIP-445) ([#24809](https://github.com/apache/pulsar/pull/24809))
* Replaced the blocking `Thread.sleep` in `TableView` tail-read retries with a scheduled backoff; pending refreshes now fail on close ([#26672](https://github.com/apache/pulsar/pull/26672))
* Fixed a v5 producer send hanging when the client closes mid-send ([#26686](https://github.com/apache/pulsar/pull/26686))
* Fixed flaky `V5StreamConsumerAckWatermarkTest`: cursor rewind raced the cumulative ack ([#26684](https://github.com/apache/pulsar/pull/26684))

**[OpenClaw](https://github.com/openclaw/openclaw)**
* Added a one-time retry when the model emits a tool call as plain text, instead of ending the run with "couldn't generate a response" ([#156342](https://github.com/openclaw/openclaw/pull/156342))

**[Gradle](https://github.com/gradle/gradle)**
* Added Windows Terminal (`WT_SESSION`) detection to report build progress on the taskbar, including from WSL ([#39260](https://github.com/gradle/gradle/pull/39260))

**[Spring Boot](https://github.com/spring-projects/spring-boot)**
* Removed redundant stream opening in `BootZipCopyAction` ([#47902](https://github.com/spring-projects/spring-boot/pull/47902))

**[Spring Security](https://github.com/spring-projects/spring-security)**
* Made the `JwtTypeValidator` `typ` check case-insensitive, fixing a regression from Nimbus `JOSEObjectTypeVerifier` ([#18101](https://github.com/spring-projects/spring-security/pull/18101))

**[Elastic Kibana](https://github.com/elastic/kibana)**
* Fixed default `perPage` in Saved Objects `PointInTimeFinder` ([#239073](https://github.com/elastic/kibana/pull/239073))

**[Apache Beam](https://github.com/apache/beam)**
* Added `@SchemaFieldDescription` to Bigtable read/write schema-transform configs ([#36344](https://github.com/apache/beam/pull/36344))

**[Apache Gravitino](https://github.com/apache/gravitino)**
* Added alias/version validation to model version CLI commands ([#8737](https://github.com/apache/gravitino/pull/8737))

**[Apache Hadoop](https://github.com/apache/hadoop)**
* Fixed a missing space in the HDFS client error for negative `dfs.domain.socket.disable.interval.seconds` ([#8603](https://github.com/apache/hadoop/pull/8603))

**[Exercises Dataset](https://github.com/hasaneyldrm/exercises-dataset)**
* Added Korean translations for all 1,324 exercises and a viewer language selector ([#27](https://github.com/hasaneyldrm/exercises-dataset/pull/27), merged via [118e4bd](https://github.com/hasaneyldrm/exercises-dataset/commit/118e4bd))

**[Nuclei Burp Plugin](https://github.com/projectdiscovery/nuclei-burp-plugin)**
* Added a GitHub Actions workflow running unit tests on PRs ([#124](https://github.com/projectdiscovery/nuclei-burp-plugin/pull/124))

**[First Contributions](https://github.com/firstcontributions/first-contributions)**
* Updated Korean image alt text ([#105473](https://github.com/firstcontributions/first-contributions/pull/105473))

### Personal Projects

**[CVE-2025-66478-Exploit-Poc](https://github.com/namest504/CVE-2025-66478-Exploit-Poc)**
* PoC exploit for CVE-2025-66478

**[termtype](https://github.com/namest504/termtype)**
* Terminal typing practice tool, Homebrew tap

**[web-graph-agent](https://github.com/namest504/web-graph-agent)**
* LangGraph-based LLM agent for web graph analysis

**[ddakji](https://github.com/namest504/ddakji)**
* Markdown sticky notes desktop app (Tauri), replacing Windows 11 Sticky Notes

**[dua](https://github.com/namest504/dua)**
* Disk usage analyzer CLI in Go, size-sorted list and tree view

**[ts-go-benchmark](https://github.com/namest504/ts-go-benchmark)**
* Benchmark of `tsc` vs Microsoft's Go port `tsgo`
