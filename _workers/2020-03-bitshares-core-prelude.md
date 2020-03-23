---
language: en
layout: worker
type: budget
category: Core Development
bfid: 202003-bitshares-core-prelude
workerid: 1.14.255
title: BitShares Core Prelude (Release 4.0)
name: Milos Preocanin
company:
 name:
 url:
status: voting
discussions:
 - name: BitSharesTalk
   url: https://bitsharestalk.org/index.php?topic=32148.msg341578#msg341578
price: up to 5,263,369.50000 BTS
duration: 9 weeks
start: 2020/03/25
end: 2020/05/26
paymentaccount:
---

Worker Intent
==========

The intent of this worker is to provide funding and solution for development, testing, and deployment of mainnet 4.0 release with urgent fixes and additional BSIP's within 2 months, as a **prelude** to Main Core 2020 Worker.


Detailed Roadmap and Estimates
==============================

- [x] Fix `negative balances` (Reimbursement Abitmore)
- [ ] Development for [BSIP 64: Operational HTLC preimage length, HASH160 addition, and memo field](https://github.com/bitshares/bsips/blob/master/bsip-0064.md) (up to 12 hours)
- [ ] Development for [BSIP 74: Margin Call Fee Ratio](https://github.com/bitshares/bsips/blob/master/bsip-0074.md) (up to 60 hours)
- [ ] Development for [BSIP 81: Simple Maker-Taker Market Fees](https://github.com/bitshares/bsips/blob/master/bsip-0081.md) (up to 100 hours)
- [ ] Development for [BSIP 86: Share market fee to the network](https://github.com/bitshares/bsips/blob/master/bsip-0086.md) (up to 60 hours)
- [ ] Development for [BSIP 87: Force Settlement Fee](https://github.com/bitshares/bsips/blob/master/bsip-0087.md) (up to 60 hours)
- [ ] Final Development for NanoLedger BTS Integration and testing (up to 30 hours)
- [ ] Testnet re-deployment and Testing 4.x (up to 250 hours)
- [ ] Deployment of final BitShares Mainnet 4.0 release (50-75 hours)
- [ ] Documentation (BSIP, User and Dev) and GitHub/Wiki maintenance and updates (up to 150 hours for entire team)

Remark: Please have a look at the important notice with regards to the workability at the end of this worker proposal

BitShares Core Team Members, Roles and Budgeted Effort
======================================================
BitShares Core Team constitutes a small, dedicated, and seasoned group of professionals.  These are highly-skilled engineers, some with doctorate level education in the programming and logic design industry.  As such, they are prized assets of the BitShares community who should be retained.   Understanding the aforementioned devalued state of the chain, these committed members of the BitShares community are prepared to accept substantially lower hourly rates than previously contracted.


 **Table 1. BitShares Core Team Positions, Availability and Rates (Weekly)**

| Roles (described below)           | Rate (USD)| BTS Value @ $0.015 USD | Team Member             | Available Hours   |
|:--------------------------------- | ---------:|:----------------------- |:----------------------- |:----------------- |
| Worker Manager                    | $35/hour  | 2333 BTS                | Milos Preocanin         | 20 hours weekly   |
| Documentation specialist          | $35/hour  | 2333 BTS                | ---------------         | 20 hours weekly   |
| Audit/Senior Core Developer       | $75/hour  | 5000 BTS                | Abit More               | 20 hours weekly   |
| Senior Core Developer             | $75/hour  | 5000 BTS                | Christopher Sanborn     | 20 hours weekly   |
| Senior Core Developer             | $75/hour  | 5000 BTS                | John Jones              | 30 hours weekly   |
| Senior Core Developer/BA          | $75/hour  | 5000 BTS                | Michel Santos           | 30 hours weekly   |
| ZHS Translation specialist        | $35/hour  | 2333 BTS                | Linda Tian              |  5 hours weekly   |

Total max. possible time on project: **~1250 hours** *(with safety buffer 15% and potential issues with final releases/production)*

**Team Roles and Rates**

| Roles (described below)         | Rate (USD) | Job Position |
|:------------------------------- | :---------:| ------------:|
| Manager                         |  $35/hour  |  Closed |
| Senior Core Developer           |  $75/hour  |  Open   |
| Quality Assurance Auditor       |  $75/hour  |  Closed |
| Documentation Specialist        |  $35/hour  |  Closed |
| ZHS Translation specialist      |  $35/hour  |  Closed |


**Hardcap/premium definition:**
This Worker reintroduces payouts in BTS, instead of fiat equivalent BitAssets. As such, in the case of appreciation in value of the BTS token over time, this worker will cap employee pay at the value of 0.015 USD per 1 BTS token, and the paid BTS amount will be calculated by this formula：

`hourly paid BTS amount = min(cap amount, 1.5 * Rate_in_USD/BTS_market_price)`

In other words, BTS payouts are considered fixed (per table 1) as long as the price is <0.0225 USD per 1 BTS token. In case of the price >0.0225 USD, amount of BTS used for payout will worth 1.5 times of the rates in USD based on the BTS market price.

Terms of Worker/Agreement
==================

1) Team hour reports and code audit will be done once every 3 weeks. A single collective team invoice will be issued by the Worker Manager (Milos Preocanin) with previous approval by the Audit Manager (Abit More), then followed by the review of the BBF

2) This worker max budget is calculated by the max amount of hours available by each team member. **All unused BTS will be returned to the reserve pool**.

3) Milos Preocanin will be held as the principal responsible contact for this worker, on behalf of “Zavod Premik”.

4) This worker's agreement is crafted as a quick and urgent mini project with pre-defined estimates.

5) This worker budget has calculated 3% escrow fees.

6) If at any point the price of BTS:USD is beneath $0.0075, each member of the team individually reserves the right to cease their contribution to development, process audit and their outstanding invoices to for all work to date, and exit the contract without any further constraints. (Worker Manager position excluded)

6.1. In case of Point 6), Worker Manager will look for alternative resources to join the team in order to deliver release.

6.2. Releases will not be postponed in case of Point 6), but just exclude missing deliveries

## Important Notice to BTS Core Token Holders

By approving this worker you're not implicitly approving the BSIPs that are listed in the roadmap of this worker.
To avoid any delays with mainnet release upon delivery of this worker, please provide vote of support to the listed BSIP's within 30 days from the worker start. BSIPs that are not approved by BTS holders must be excluded otherwise (leading to a reduction of cost and features delivered with release 4.0).
