# NullSec CloudAudit

**Multi-Cloud Security Auditor**

[![Go](https://img.shields.io/badge/go-1.21+-00ADD8.svg)](https://golang.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![X/Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2.svg)](https://x.com/AnonAntics)

> Part of the **NullSec Linux** security distribution  
> Twitter: [x.com/AnonAntics](https://x.com/AnonAntics)

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
