# NullSec CloudAudit

**Multi-Cloud Security Auditor**

[![Go](https://img.shields.io/badge/go-1.21+-00ADD8.svg)](https://golang.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-7289da.svg)](https://discord.gg/killers)

> Part of the **NullSec Linux** security distribution  
> Discord: [discord.gg/killers](https://discord.gg/killers)

## Features

- Multi-cloud support (AWS, GCP, Azure)
- IAM misconfigurations
- S3/Storage bucket exposure
- Network security groups audit
- Compliance checking (CIS, SOC2, PCI-DSS)

## Installation

```bash
go install github.com/bad-antics/nullsec-cloudaudit@latest
```

## Usage

```bash
nullsec-cloudaudit --provider aws --profile default
nullsec-cloudaudit --provider gcp --project myproject
nullsec-cloudaudit --provider azure --subscription mysub
```

## License

MIT License - [@bad-antics](https://github.com/bad-antics)
