# Clearstream (clearstream)

Clearstream is a leading provider of post-trade infrastructure services for international securities transactions. They offer settlement, custody, and collateral management services for bonds, equities, and investment funds.

The Clearstream developer surface is built on regulated post-trade messaging rather than a public REST API. Clients connect through ClearstreamXact (Web Portal, File Transfer via SWIFTNet FileAct, and Xact via SWIFT FIN), CASCADE via SWIFT and MQ, the CreationOnline / CreationDirect channels, Vestima for fund order routing, and the CmaX triparty collateral platform. Messages follow ISO 15022 and ISO 20022 standards, with ongoing migration toward ISO 20022 driven by the SWIFT CBPR+ programme.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/clearstream/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **x-type:** company

## Tags

Capital Markets, Collateral Management, Custody, Financial Services, ISO 15022, ISO 20022, Post-Trade Infrastructure, Securities, Settlement, SWIFT

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-23

## APIs

### Clearstream Xact via SWIFT
Settlement, custody, asset servicing and reporting messages over the SWIFTNet FIN network. Uses ISO 15022 MT messages today, migrating to ISO 20022 MX in line with the SWIFT CBPR+ schedule.

- [Documentation](https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/xact-via-swift--1276378)
- [User Guides](https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/xact-via-swift-user-guides-1289256)
- [SWIFT MyStandards](https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/swift-mystandards-1277070)

### Clearstream Xact File Transfer
Bulk and report-style exchange of settlement, custody, and collateral messages over SWIFTNet FileAct. Files may be delivered in ISO 15022, ISO 20022, PDF, XML or XLS.

- [Documentation](https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/xact-file-transfer)
- [Connectivity Manuals](https://www.clearstream.com/clearstream-en/keydocuments-1-/icsd-1-/connectivity-manuals)

### Clearstream Xact Web Portal
Browser-based interface to ClearstreamXact for instructing settlement, custody and collateral activity, monitoring status, and reviewing reports.

- [Documentation](https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/clearstreamxact)
- [Testing](https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/clearstreamxact/testing)

### Clearstream CASCADE (CSD)
German central securities depository (CSD) settlement platform. Reachable via SWIFT FIN/FileAct messages and via MQ-based host-to-host connectivity.

- [Documentation](https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/cascade)
- [CASCADE via SWIFT](https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/cascade/cascade-via-swift)

### Clearstream Vestima
Investment fund processing platform that routes subscription, redemption, switch and transfer orders for mutual funds, ETFs, hedge funds and alternatives.

- [Documentation](https://www.clearstream.com/clearstream-en/securities-services/funds-services-1-/vestima)

### Clearstream CmaX (Triparty Collateral)
Triparty collateral management platform that automates allocation, optimisation, margining and substitution across repo, securities lending, and OTC derivatives exposures.

- [Documentation](https://www.clearstream.com/clearstream-en/securities-services/collateral-management)

## Common Properties

- [Website](https://www.clearstream.com/)
- [Portal](https://www.clearstream.com/clearstream-en/products-and-services)
- [Documentation](https://www.clearstream.com/clearstream-en/keydocuments-1-/icsd-1-/connectivity-manuals)
- [Support](https://www.clearstream.com/clearstream-en/contact)
- [Terms of Service](https://www.clearstream.com/clearstream-en/legal-and-regulatory)
- [JSON-LD](json-ld/clearstream-context.jsonld)
- [Spectral](rules/clearstream-rules.yml)
- [Naftiko Capabilities](capabilities/clearstream-post-trade.yaml)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
