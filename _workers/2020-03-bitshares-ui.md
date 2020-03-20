---
layout: worker
language: en
category: UI Development
bfid: 202003-bitshares-ui
type: budget
workerid:
title: BitShares UI Team
name: Magnus Anderson
company:
  name:
  url:
status: draft
discussions:
 - name: Bitshares Talk
   url: https://bitsharestalk.org/index.php?topic=28705.0
 - name: steemit/@sc-steemit
   url: https://steemit.com/bitshares/@sc-steemit/bitshares-ui-first-6-months-of-worker-results
 - name: whaleshares/@startail
   url: https://whaleshares.io/@startail/bitshares-ui-first-6-months-of-worker-results
payments:
price: up to $ 107,380
duration: 26 weeks
start: 2020/03/09
end: 2020/09/13
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

## **Worker Scope**

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

Critical bugs will always take priority, and hotfix releases may be released inbetween if required. In general, releases may be delayed depending on test results to ensure only polished releases are published.

## **Estimated Roadmap**

The roadmap for this worker will contain three main parts:

1.  Integration of Beet and seamless user experience

    The biggest concern for users when interacting with a use interface is security of their own private keys. The BitShares UI offers cloud login (account and password) and a local wallet.
    Very common in the crypto space is the use of external key managers and completely extract the issue of key security from the website / light wallet. For the BitShares UI that means
    to enable a new way of logging in with Beet, a standalone key manager tailored for Graphene Blockchains, and possible other key managers like Scatter. That way the user only has to trust
    his private keys to the key manager that can be installed locally, and the private key is never exposed to the website requesting the key.

2.  Maintenance of the code base (security issues, bugfixes & small UX improvements)

    Keeping the UI usable and secure for the users is certainly a top priority. Especially in the crypto space, outdated software, libraries of bad (formerly best) practices can lead to severe consequences with loss of funds.
    NodeJS dependencies need to be maintained and bugs that surface fixed. On top of that, small tweaks on the right end can greatly facilitate the user experience.

3.  Implementation of features/changes of upcoming BSIPs as they become available

    With feature and api releases of the BitShares Core adjustments and/or extension to the JS codebase is necessary to keep up with the development.
    This may range from performance improvements allowed by new core endpoints to new features enabled through BSIP development. In particular for now:

    * Use of new subscription system to the client light-weight in terms of node load
    * Use of new api limitation to reduce loading time, reduce load and enhance UX through lazy loading
    * BSIP40: Implementation of an easy way to create named keys, e.g. a trading key
    * Custom operation plugin: Allow user configuration and other payload to be stored on chain together with your account. This will also be used by the mobile app by BTS++

While the last two parts are an ongoing basis, the third one is a defined milestone. In particular, that means that 
the actual development for 2, 3 is dynamic and needs contant evaluation whereas the integration of Beet for 3 is a 
fixed goal to be achieved within this worker.

**Remark on Prioritization**

1. There are many opinions across the BitShares community about what is most important.
These opinions vary due to the broad range of individual capabilities. Some users want to see new features developed as soon as possible while others would like
to see a refined user interface with reliable, less ambiguous controls and helpful documentation. 

2. Engagement towards the chinese community will be strengthened and feedback collected.

3. Release planning will happen before the development. The feedback from the community and BTS holders will be heard and accounted for reasonably in the chronological order of the roadmap and releases.

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

### **bench (@froooze)**

*   Main Duties: Unit and integration testing, Bug reports and development
*   Development Experience: Webdesign since 2005, active BitShares community member since 2017 with engineer background in mechatronic systems
*   Languages: HTML, CSS, PHP, Python, SQL and recently JS with React

Duties include testing of release candidates and development builds, writing of bug reports as reported through GitHub issues and development.

### **ety001**

*   Main Duties: Development and facilitation of communication with chinese community
*   Development Experience: Former software engineer at Institue of Computing Technology Chinese Academy of Sciences, now freelancer for web development and focusing on Graphene-based and related blockchains and tools.

### **Developers (Misc)**

All committed developers will coordinate efforts to follow prioritization of issues for the current release based on requirements needed for following the schedule set.
At the start and end of all milestones the developers should make sure they follow the plan set out for them.
Bounties are not free for all, and in case there are applicants only hand-picked motivated developers that finish the tasks will be added.
Failure to finish within the agreed timeline may result in loss of compensation.

## **Budget & Roles**

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
   <td>Commmitted Development
   </td>
   <td>$75/hour
   </td>
   <td>ety001
   </td>
   <td>16 hours weekly
   </td>
  </tr>
  <tr>
   <td>Commmitted Development
   </td>
   <td>$75/hour
   </td>
   <td>bench
   </td>
   <td>8 hours weekly
   </td>
  </tr>
  <tr>
   <td>Development
   </td>
   <td>up to $75/hour
   </td>
   <td>- Split between all developers as needed -
   </td>
   <td>up to 8 hours weekly
   </td>
  </tr>
  <tr>
   <td>Total
   </td>
   <td>
   </td>
   <td>
   </td>
   <td><strong>up to 56 hours weekly</strong>
   </td>
  </tr>
</table>

In total for the 26 weeks this worker is seeking for **$ 107,380**.

**Remarks**

*   This worker funds are a **not to exceed** budget
*   The BitShares Blockchain Foundation seeks a management fee of 3% of paid invoices for dealing with the on-chain worker proposal, providing a legal framework, perform review of deliveries and invoices, and offer transparent accounting
*   All accumulated and unallocated BTS returned to the Reserve Pool at the conclusion of the Worker

The daily payout is set to **25,000 BTS**, which contains a devaluation multiplier of 1.25. In theory, if the price remains the same and the worker is voted active, it will take 21 weeks to collect the budget for the whole period.

## **Payments**

Payment cycles will aligned with sprints. This way the BTS holders can have a tangible and visible overview of the spendings.

Eligible for payment are all tasks (reflected by [issues in GitHub](https://github.com/bitshares/bitshares-ui/issues)) that have been accepted and merged within the corresponding release (reflected by [projects in GitHub](https://github.com/bitshares/bitshares-ui/projects)).

Funds Manager will review and approve submitted time sheets, then forward invoices to BitShares Blockchain Foundation for release of funds from escrow to contributor’s account.

The payments will happen preferably in bitEUR, but may also happen in any alternative BitAsset, BTS directly, or in BTC depending on market conditions. The value indicated here and on later invoices represent FIAT values, and will be paid in equivalent value of the chosen crypto-currency.
