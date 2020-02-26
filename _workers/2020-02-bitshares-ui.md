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

# The BitShares UI Worker Proposal

As the first and quite a long time only user interface (UI) for the BitShares Blockchain, the so-called [BitShares UI](https://github.com/bitshares/bitshares-ui) has established itself
as the reference for other visualizations. It provides by far the most complete list of features available within the backend of the BitShares Blockchain, presented in a point-and-click
style of way for users not familiar with command line interfaces. On top of that various second level uses like Signed Messages and Asset Bartering are available.

## What is the intention of the BitShares UI?

The BitShares UI is often called the Reference UI. And it seeks to be exactly that:
A reference that seeks to showcase any and all features that the BitShares Blockchain offers. Easily onboarded, forked and branded.
The idea is that gateways or business have an easy entry-point and to be able to give them sample code on how to interact with the blockchain.
The idea was not to provide a simple, slick, use-case targeted UI for depicted target groups like traders.

Anyone should be able to get a grasp on the feature set while being able to quickly try things out.
The user experience is of course always one key driver for development of the BitShares UI, but it will never be as simply or focused as a tailored UI with a specific use-case in mind.

## **Scope**

This worker will last for half a year, starting from 9<sup>th</sup> of March 2020 (Calender Week 11) until 13<sup>th</sup> of September 2020 (Calender Week 37).

As previous, the worker will be used to support development on a number of BitShares repositories. These are the main repositories (others may be added in the future). Beet is a stand-alone, multi-chain key/identity-manager and signing app for BitShares.

*   [https://github.com/bitshares/bitshares-ui](https://github.com/bitshares/bitshares-ui)
*   [https://github.com/bitshares/bitshares-ui-style-guide](https://github.com/bitshares/bitshares-ui-style-guide)
*   [https://github.com/bitshares/bitsharesjs](https://github.com/bitshares/bitsharesjs)
*   [https://github.com/bitshares/bitsharesjs-ws](https://github.com/bitshares/bitsharesjs-ws)
*   [https://github.com/bitshares/beet](https://github.com/bitshares/beet)
*   [https://github.com/bitshares/beet-js](https://github.com/bitshares/beet-js)

## **Estimated Schedule**

To decrease costs for the worker we will no longer include any community bounty payments, nor any travel funds to conferences. The cost will be focused on experienced developers that
know the code well enough to make good commits to the code base.

Aim for release schedule is every 12 weeks (i.e. two releases for this worker). It will be based on six sprints, each 2 weeks. During the first four sprints the team will assess and work on
new features, enhancements and improvements that can be finalized within the release. The last two sprints will be focusing on testing, bug fixes and fine tuning before the final release.
All efforts for a release are organized and reflected in [GitHub as “Projects”](https://github.com/bitshares/bitshares-ui/projects). Each task will be reflected
in [GitHub as an Issue](https://github.com/bitshares/bitshares-ui/issues).

Bugs will always take priority, and critical releases may be released inbetween if required. In general, Releases may be delayed depending on test results to ensure only polished releases are published.

## **Estimated Roadmap**

The roadmap for this worker will contain three main parts:

1.  Maintenance of the code base (security issues, bugfixes & small UX improvements)

    Keeping the UI usable and secure for the users is certainly a top priority. Especially in the crypto space, outdated software, libraries of bad (formerly best) practices can lead to severe consequences with loss of funds.
    NodeJS dependencies need to be maintained and bugs that surface fixed. On top of that, small tweaks on the right end can greatly facilitate the user experience.

2.  Implementation of features/changes of upcoming BSIPs as they become available

    With feature and api releases of the BitShares Core adjustments and/or extension to the JS codebase is necessary to keep up with the development.
    This may range from performance improvements allowed by new core endpoints to new features enabled through BSIP development. In particular for now:

    * Use of new subscription system to the client light-weight in terms of node load
    * Use of new api limitation to reduce loading time, reduce load and enhance UX through lazy loading
    * BSIP40: Implementation of an easy way to create named keys, e.g. a trading key
    * Custom operation plugin: Allow user configuration and other payload to be stored on chain together with your account. This will also be used by the mobile app by BTS++

3.  Integration of Beet and seamless user experience

    The biggest concern for users when interacting with a use interface is security of their own private keys. The BitShares UI offers cloud login (account and password) and a local wallet.
    Very common in the crypto space is the use of external key managers and completely extract the issue of key security from the website / light wallet. For the BitShares UI that means
    to enable a new way of logging in with Beet, a standalone key manager tailored for Graphene Blockchains, and possible other key managers like Scatter. That way the user only has to trust
    his private keys to the key manager that can be installed locally, and the private key is never exposed to the website requesting the key.

While the first two parts are an ongoing basis, the third one is a defined milestone. In particular, that means that the actual development for 1, 2 is dynamic and needs contant evaluation whereas
the integration of Beet for 3 is a fixed goal to be achieved within this worker.

**Remark on Prioritization**

There are many opinions across the BitShares community about what is most important.
These opinions vary due to the broad range of individual capabilities. Some users want to see new features developed as soon as possible while others would like
to see a refined user interface with reliable, less ambiguous controls and helpful documentation. The feedback from the community will be heard and if possible
accounted for in the chronological order of the roadmap.

## **Team**

The following are the main team members. The team may have more members during the course of the worker that do development.

### **Magnus Anderson (@startail)**

*   Main Duties: Team leader & development
*   Crypto Experience: 6 years of trading and using, 4 years of community building, 3 years of DPOS Node Maintainer
*   Development Experience: 20 years of website development in various forms, 15 years of server management, 5 years of Git experience
*   Languages: PHP, jQuery, mySQL, HTML, Javascript, React, Python, Bash, many more

Duties will be to create and coordinate release schedules, prioritize issues with developers and development.

### **Stefan Schiessl (@sschiessl-bcp)**

*   Main Duties: Development, code review for submitted PRs & coordinate releases
*   Development Experience: Maintainer of BitShares UI, strong applied mathematics background and developing and managing software development since 2005, for crypto since 2017
*   Languages: NodeJS, React, and others

Duties will be development, to review submitted PRs together with developers and coordinate new releases at the end of release schedules.

### **Alex M (@clockwork)**

*   Main Duties: Invoice and Timesheet verifications
*   Development Experience: Over 16 years web-development experience in both front-end and back-end. Been involved in BitShares development since the beginning of 2018. Maintainer of Beet. Current BitShares witness & committee member.

Duties are to review and approve submitted timesheets, as verified by closed issues or merged PRs (referred by the invoices).

### **Milos (Digital Lucifer)**

*   Main Duties: Ensure that efforts of UI and core team are in sync and breaking changes are communicated and accounted for

Duties are to sync and review progress and discuss priorities for inter-team efforts. This is paid by the core worker, if voted in.


### **Developers (Misc)**

Both committed developers (Magnus and Stefan) will coordinate efforts to follow prioritization of issues for the current release based on requirements needed for following the schedule set.
At the start and end of all milestones the developers should make sure they follow the plan set out for them.
Bounties are not free for all, and in case there are applicants only hand-picked motivated developers that finish the tasks will be added.
Failure to finish within the agreed timeline may result in loss of compensation.

### **Budget & Roles**

Budget includes fixed positions and development costs

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
   <td>up to 2 hours weekly
   </td>
  </tr>
  <tr>
   <td>Code Review and Release Manager
   </td>
   <td>$80/hour
   </td>
   <td>Stefan Schiessl
   </td>
   <td>up to 4 hours weekly
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
   <td>Commmitted Development
   </td>
   <td>$75/hour
   </td>
   <td>Stefan Schiessl
   </td>
   <td>8 hours weekly
   </td>
  </tr>
  <tr>
   <td>Commmitted Development
   </td>
   <td>$75/hour
   </td>
   <td>Magnus Anderson
   </td>
   <td>8 hours weekly
   </td>
  </tr>
  <tr>
   <td>Development
   </td>
   <td>up to $75/hour
   </td>
   <td>- Split between all developers -
   </td>
   <td>up to 24 hours weekly
   </td>
  </tr>
  <tr>
   <td>Total
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>up to 48 hours weekly</strong>
   </td>
  </tr>
</table>

In total for the 26 weeks this worker is seeking for **$ 91,780**.

**Remarks**

*   This worker funds are a **not to exceed** budget
*   The BitShares Blockchain Foundation seeks a management fee of 3% of paid invoices for dealing with the on-chain worker proposal, providing a legal framework, perform review of deliveries and invoices, and offer transparent accounting
*   All accumulated and unallocated BTS returned to the Reserve Pool at the conclusion of the Worker

The daily payout is set to **20,000 BTS**, which contains a devaluation multiplier of 2. In theory, if the price remains the same and the worker is voted active, it will take only half the time to collect the budget for the whole period.

### **Payments**

Payment cycles will aligned with sprints. This way the BTS holders can have a tangible and visible overview of the spendings.

Eligible for payment are all tasks (reflected by [issues in GitHub](https://github.com/bitshares/bitshares-ui/issues)) that have been accepted and merged within the corresponding release (reflected by [projects in GitHub](https://github.com/bitshares/bitshares-ui/projects)).

Funds Manager will review and approve submitted time sheets, then forward invoices to BitShares Blockchain Foundation for release of funds from escrow to contributor’s account.

The payments will happen preferably in bitEUR, but may also happen in any alternative BitAsset, BTS directly, or in BTC depending on market conditions. The value indicated here and on later invoices represent FIAT values, and will be paid in equivalent value of the chosen crypto-currency.
