# haya finance Contract Audit Report

This repository contains the smart contract security audit report for the haya finance project, conducted by Beosin Security.

## About the Project

haya finance is a decentralized protocol on the Arbitrum blockchain. It comprises several key smart contracts:

- Controller: Manages system contracts, modules, factories, and protocol fee configurations.
- IntegrationRegistry: Manages module adapters.
- PriceOracle: Provides functions for fetching token prices.
- SetToken: An extended ERC20 token with custom components and modules.
- SetTokenCreator: A factory for creating SetToken contracts.
- SetValuer: Calculates the valuation of a SetToken.
- AuctionRebalanceModule: A rebalance auction contract for SetToken components.
- BasicIssuanceModule: A module for converting between SetToken and its components.

## Audit

The security audit was conducted by Beosin Security from April 18, 2024, to May 1, 2024. It covered formal verification, manual review, and static analysis of the codebase.

### Findings

A total of 2 low-risk and 1 informational issues were identified and fixed by the haya finance team.

### Issue Resolution

All identified issues have been fixed and verified by Beosin Security. Details of the fixes are included in the audit report.

## Full Report

The full audit report from Beosin Security is available in this repository: [haya-finance-contract-audit-202405011013_M5JSMM.pdf](https://beosin.com/audits/haya-finance_202405011013.pdf)
