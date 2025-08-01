# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.3] - 2025-06-23

### Changed

- Library updates to address [cve-2025-23206](https://avd.aquasec.com/nvd/2025/cve-2025-23206/)
- Library updates to address [cve-2025-27789](https://avd.aquasec.com/nvd/2025/cve-2025-27789/)
- Javascript SDK migration v2 to v3
- Node js update to 22

### Added

- Add cdk-solution-helper, responsible for converting standard 'cdk synth' output into solution assets.

## [1.1.2] - 2025-03-14

### Changed

- Library updates to address [Possible SSRF and Credential Leakage via Absolute URL in axios Requests](https://avd.aquasec.com/nvd/cve-2025-27152)

## [1.1.1] - 2024-11-21

### Changed

- Library updates to address [Regular Expression Denial of Service (ReDoS) in cross-spawn](https://avd.aquasec.com/nvd/cve-2024-21538)

## [1.1.0] - 2024-10-24

### Changed

- Replacing CodeCommit with S3 bucket as source code respository for network firewall configurations.

## [1.0.8] - 2024-09-15

### Changed

- Library updates to address [path-to-regexp outputs backtracking regular expressions](https://avd.aquasec.com/nvd/cve-2024-45296)
- Library updates to address [AWS CDK RestApi not generating authorizationScope correctly in resultant CFN template](https://avd.aquasec.com/nvd/cve-2024-45037)
- Library updates to address [micromatch: vulnerable to Regular Expression Denial of Service](https://avd.aquasec.com/nvd/cve-2024-4067)

## [1.0.7] - 2024-08-22

### Changed

- Library updates to address [axios 1.7.2 allows SSRF via unexpected behavior where requests for path relative URLs get processed as protocol relative URLs.](https://avd.aquasec.com/nvd/cve-2024-39338)

## [1.0.6] - 2024-07-15

### Changed

- Bump up minor versions of dependencies
- Library updates to address [braces: fails to limit the number of characters it can handle]( https://avd.aquasec.com/nvd/cve-2024-4068)

## [1.0.5] - 2024-05-22

### Changed

- Rename the solution to Centralized Network Inspection on AWS
- Bump up minor versions of dependencies

## [1.0.4] - 2023-11-10

### Changed

- Update NodeJS environment for CodeBuild from NodeJS16 to NodeJS18.

## [1.0.3] - 2023-10-27

### Changed

- Library updates to address [Babel vulnerable to arbitrary code execution when compiling specifically crafted malicious code](https://nvd.nist.gov/vuln/detail/CVE-2023-45133)
- Library updates to address [xml2js vulnerable to improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')](https://nvd.nist.gov/vuln/detail/CVE-2023-0842)

## [1.0.2] - 2022-12-19

### Changed

- Name change to Firewall Automation for Network Traffic on AWS
- Upgrade to CDK v2
- Fix NPM security warnings
- Fix SonarQube bugs and increase unit test coverage

## [1.0.1] - 2021-04-10

### Changed

- Updated default branch name to 'main'. [Change branch settings in your existing AWS CodeCommit repository.](https://docs.aws.amazon.com/codecommit/latest/userguide/how-to-change-branch.html)

## [1.0.0] - 2021-02-24

### Added

- New solution AWS Network Firewall Deployment Automations for AWS Transit Gateway, initial version
