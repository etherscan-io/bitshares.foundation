---
layout: worker
language: en
category: UI Development
bfid: 202002-bitshares-ui
type: budget
workerid:
title: BitShares UI Team
name: Magnus Anderson
company:
  name:
  url:
status: finished
discussions:
 - name: Bitshares Talk
   url: https://bitsharestalk.org/index.php?topic=28705.0
 - name: steemit/@sc-steemit
   url: https://steemit.com/bitshares/@sc-steemit/bitshares-ui-first-6-months-of-worker-results
 - name: whaleshares/@startail
   url: https://whaleshares.io/@startail/bitshares-ui-first-6-months-of-worker-results
payments:
price: up to XXX
duration: 49 weeks
start: 2020/02/24
end: 2021/01/31
---

# BitShares UI Reference Wallet

The BitShares UI Reference Wallet (later mentioned as BitShares UI) is a significant part the current network and enables the use of the core functionality of the network. The BitShares UI primary goal is to follow and work together with the core team to incorporate as much of the functionality as possible and to act as a reference for other development teams.

Its secondary goal is to improve and evolve the BitShares UI to ease onboarding, forking and overall usage for all users regardless of previous experience.



## **Worker Scope**

This worker will last for 46 weeks, starting from 3<sup>rd</sup> of February 2020 until 31<sup>st</sup> of December 2020.

As previous, the worker will be used to support development on a number of BitShares repositories. These are the main repositories (others may be added in the future). Beet is a stand-alone, multi-chain key/identity-manager and signing app for BitShares.

*   [https://github.com/bitshares/bitshares-ui](https://github.com/bitshares/bitshares-ui)
*   [https://github.com/bitshares/bitshares-ui-style-guide](https://github.com/bitshares/bitshares-ui-style-guide)
*   [https://github.com/bitshares/bitsharesjs](https://github.com/bitshares/bitsharesjs)
*   [https://github.com/bitshares/bitsharesjs-ws](https://github.com/bitshares/bitsharesjs-ws)
*   [https://github.com/bitshares/beet](https://github.com/bitshares/beet)
*   [https://github.com/bitshares/beet-js](https://github.com/bitshares/beet-js)

## **Worker Schedule**

To decrease costs for the worker we will no longer include any community bounty payments, nor any travel funds to conferences. The cost will be focused on experienced developers that know the code well enough to make good commits to the code base.

The team will consist of at least a project manager, a release manager and a funds manager. These will have fixed hours to meet the demands of the required work for a release. The team will also consist of a number of skilled developers that can be assigned issues to work on within the GitHub repository mentioned in worker scope above.

Aim for release schedule is  every 8 week. It will be based on four 2 week sprints. During the first three sprints the team will assess and work on new features, enhancements and improvements that can be finalized within the 6 week window. The last 2 week sprint will be focusing on testing, bug fixes and fine tuning before the final release. All efforts for a release are organized and reflected in [GitHub as “Projects”](https://github.com/bitshares/bitshares-ui/projects).Each task will be reflected in [GitHub as an Issue](https://github.com/bitshares/bitshares-ui/issues).

Bugs will always take priority, and critical releases may be released before the 8 week release schedule if required. In general, Releases may be delayed depending on test results to ensure only polished releases are published.



## **Estimated Roadmap 2020**

The roadmap for the BitShares UI during 2020 will be highly dependant on the various BSIP implementations that the BitShares core team will be able to release. With that in mind, these will be the main parts

*   Implement as many new BSIP implementations as possible
*   Continuation on UX improvement and performance
*   Integration of  Beet and seamless user experience
*   User security improvements

## **Prioritization**

There are many opinions across the BitShares community about what is most important. These opinions vary due to the broad range of individual capabilities. Some users want to see new features developed as soon as possible while others would like to see a refined user interface with reliable, less ambiguous controls and helpful documentation.

The team will pursue improvements to the UI by low-hanging-fruits to make the most change for the least required time first. These can be to add new useful features, as well as removing existing ones. The goal will be to have as many core features as possible to allow the community to utilize the full feature of the network.

Prioritization to all work will be done in the following aspects

* **Bugs**

    These are top priority for the team and are top priority to ensure the application meets users expectations.

*   **Low Hanging Fruit**

    This represents features or tweaks that give the application a lot of bang for very little effort. By focusing on low hanging fruit, we can drastically improve the UI for many people very quickly and cross these items off the to-do list.

*   **Application Consistency**

    Past efforts have sought to improve the overall look and feel and have attempted to group similar functions. We recognize there is still room for improvement.

*   **New Features**

    The BitShares core is ever evolving and anything new that comes out of it will need to be reflected in the UI as well.

*   **Community Feedback**

    In addition to that, all community feedback will be considered and groomed into issues where feasible.

## **Team**

The following are the main team members with the fixed roles. The team may have more members during the course of the worker that does coding work.

### **Project Manager - Magnus Anderson (@startail)**

*   Main Duties: Team leader,  release and milestone coordinator, issue grooming..
*   Crypto Experience: 6 years of trading and using, 4 years of community building, 3 years of DPOS Node Maintainer
*   Development Experience: 20 years of website development in various forms, 15 years of server management, 5 years of Git experience
*   Languages: PHP, jQuery, mySQL, HTML, Javascript, React, Python, Bash, many more

Duties will be to create and coordinate release schedules and prioritize issues with developers. Issue grooming on repository with the possibility for community input.

Report progress on updates and releases and various other communicational tasks will also be included within this role.

### **Code Review / Release Manager - Stefan Schiessl**

*   Main Duties: Code review for submitted PRs and coordinate new releases
*   Development Experience: Maintainer of BitShares UI, strong applied mathematics background and developing and managing software development since 2005, for crypto since 2017
*   Languages: NodeJS, React, and others

Duties will be to review submitted PRs together with developers and coordinate new releases at the end of release schedules set by Project Manager.

### **Funds Manager - Alex M (@clockwork)**

*   Main Duties: Funds, Invoice and Timesheet verifications
*   Development Experience: Over 16 years web-development experience in both front-end and back-end. Been involved in BitShares development since the beginning of 2018. Maintainer of Beet. Current BitShares witness & committee member.

Duties are to review and approve submitted timesheets, as verified by closed issues or merged PRs (referred by the invoices). Invoices that can be approved are sent to, and approved on, BitShares Blockchain Foundation for release of funds from escrow to contributor’s account.

### **Core Coordination Manager - Milos (Digital Lucifer)**

*   Main Duties: Ensure that efforts of UI and core team are in sync and breaking changes are communicated and accounted for

Duties are to sync and review progress and discuss priorities for inter-team efforts.


### **Developers (Misc)**

All developers will coordinate efforts to follow prioritization of issues attached by Project Manager or Release Manager based on requirements needed for following the Release Schedule set. At the start and end of all milestones the developers should make sure they follow the plan set out for them.
Bounties are not free for all, and only hand-picked motivated developers that finish the task will be selected. Failure to finish within the agreed timeline may result in loss of compensation.

### **Budget**

TODO

Budget includes fixed positions and development costs for the team.

#### **Table 1 – Fixed Team Expenses**

<table>
  <tr>
   <td>
Role
   </td>
   <td>Rate (USD)
   </td>
   <td>Team Member
   </td>
   <td>Estimated Hours
   </td>
  </tr>
  <tr>
   <td>Project Manager
   </td>
   <td>$80/hour
   </td>
   <td>Magnus Anderson
   </td>
   <td>up to 6 hours weekly
   </td>
  </tr>
  <tr>
   <td>Code Review and Release Manager
   </td>
   <td>$80/hour
   </td>
   <td>Stefan Schiessl
   </td>
   <td>up to 8 hours weekly
   </td>
  </tr>
  <tr>
   <td>Funds Manager
   </td>
   <td>$50/hour
   </td>
   <td>Alex M
   </td>
   <td>up to 1 hour weekly
   </td>
  </tr>
  <tr>
   <td>Core Communications
   </td>
   <td>$50/hour
   </td>
   <td>Milos
   </td>
   <td>up to 2 hour weekly
   </td>
  </tr>
  <tr>
   <td>Total
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>up to 17 hours weekly</strong>
   </td>
  </tr>
</table>

#### **Table 2 – Development Expenses**

<table>
  <tr>
   <td>
Role
   </td>
   <td>Rate (USD)
   </td>
   <td>Team Member
   </td>
   <td>Estimated Hours
   </td>
  </tr>
  <tr>
   <td>Development
   </td>
   <td>up to $75/hour
   </td>
   <td>- all developers -
   </td>
   <td>up to 40 hours weekly
   </td>
  </tr>
</table>

_Rates for developers may differ depending on experience. Maximum costs are at full rate_

####  **Table 3 – Summary**

<table>
  <tr>
   <td>Role</td>
   <td>Up to hours</td>
   <td>Up to amount</td>
   <td>Period</td>
  </tr>
  <tr>
   <td>Fixed Team Expenses</td>
   <td>17 hours</td>
   <td>$ 1,270</td>
   <td>Weekly
   </td>
  </tr>
  <tr>
   <td>Development
   </td>
   <td>40 hours</td>
   <td>$ 3,000
   </td>
   <td>Weekly
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Total Budget
   </td>
   <td></td>
   <td>$ 148,270
   </td>
   <td>49 weeks
   </td>
  </tr>
  <tr>
   <td>Escrow Fee (3%)
   </td>
   <td></td>
   <td>$ 4,448
   </td>
   <td>49 weeks
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Total asking 2020
   </td>
   <td></td>
   <td><strong>$ 152,718</strong>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>BTS per day
   </td>
   <td><strong>22,555 BTS</strong>
   </td>
   <td>Daily worker pay
   </td>
  </tr>
</table>

**Remarks**

*   This worker funds are **not to exceed** budget for development according to _Table 3_.
*   The BitShares Blockchain Foundation seeks a management fee of 3% of paid invoices for dealing with the on-chain worker proposal, providing a legal framework, perform review of deliveries and invoices, and offer transparent accounting.
*   All accumulated and unallocated BTS returned to the Reserve Pool at the conclusion of the Worker

The daily payout is set to 22,555 BTS, which contains a devaluation multiplier of 2. In theory, if the price remains the same and the worker is voted active, it will take only half the time to collect the budget for the whole period.

### **Payments**

Payment cycles will aligned with sprints. This way the BTS holders can have a tangible and visible overview of the spendings.

Eligible for payment are all tasks (reflected by [issues in GitHub](https://github.com/bitshares/bitshares-ui/issues)) that have been accepted and merged within the corresponding release (reflected by [projects in GitHub](https://github.com/bitshares/bitshares-ui/projects)).

Funds Manager will review and approve submitted time sheets, then forward invoices to BitShares Blockchain Foundation for release of funds from escrow to contributor’s account.

The payments will happen preferably in bitEUR, but may also happen in any alternative BitAsset, BTS directly, or in BTC depending on market conditions. The value indicated here and on later invoices represent FIAT values, and will be paid in equivalent value of the chosen crypto-currency.
