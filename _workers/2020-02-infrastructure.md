---
language: en
layout: worker
type: budget
category: Network
bfid: 202002-infrastructure
workerid: 1.14.253
title: "Renewal 3: Deploy and maintain independent BitShares infrastructure"
name: Milos Preocanin
company:
 name: AP Asia Tech Co., LTD.
 url: http://apasia.tech
status: voting
discussions:
 - name: bitsharestalk
   url: "https://bitsharestalk.org/index.php?topic=32149.0"
price: 30,600 USD (215,179 CNY)
price_division:
    fixed: 12,600 USD (88,603 CNY)
    variable: 18,000 USD (126,575 CNY)
duration: 12 months
start: 2020/03/01
end: 2021/02/28

---

# **Worker Proposal**

Given the advancement of the BitShares ecosystem, the continuation of the infrastructure that has been deployed with the previous [infrastructure worker](https://www.bitshares.foundation/workers/2019-02-infrastructure) that was operated by Blockchain Projects B.V. seems imperative.

The existing infrastructure of the previous worker will be reused which has the benefit that there are no setup fees or person hours necessary to continue. We (AP Asia Tech) are appointed the new manager for this worker proposal to reduce conflict of interest and ensure
an independent review. We want to ensure that those services are continuously provided and are proposing a renewal of the worker.

In addition to the previously offered services

  * Distributed Network of BitShares nodes
  * Elasticsearch BitShares nodes for public use

this worker proposal will in addition offer

  * Geolocation-based DNS loadbalancing
  * Insight API for statistics and crypto-ranking websites (publicly available endpoints to be consumed by websites like CoinMarketCap, CoinGecko, Nomics & Feixiaohao (etc.))

## **Distributed Network of BitShares nodes**

The core component of this proposal is the distribution of the BitShares network by means of deploying multiple nodes and offer public API endpoints to improve latency,
robustness and availability for the BitShares ecosystem. Since this proposal is funded by the BitShares ecosystem, we limit the use of the APIs to non-commercial activity.

### **Distributed Network for BitShares Nodes**

The three deployed BitShares nodes

	eu.nodes.bitshares.ws
	us.nodes.bitshares.ws
	hk.nodes.bitshares.ws

will be continuously operated within the description of the last worker. Furthermore, the deployed BitShares testnet node

	testnet.nodes.bitshares.ws

will be continuously operated within the description of the last worker. If necessary, additional testnet nodes and/or witnesses will be deployed.

### **Public Uptime Tracking and Statistics**

The deployed overview provided with Grafana

    https://stats.bitshares.ws

will be continuously operated as is. Uptime tracking will be provided in the frame that the [exotic infrastrucute worker](https://www.bitshares.foundation/workers/201903-bitshares-org-exotic-infrastructure) has laid out.

### **Maintenance of Automation of Docker Container Builds**

The **automated builds** using docker containers will continue to be available and maintained. These containers allow a very easy and fast deployment of BitShares nodes. The automation docker cloud ensures that the public sources of BitShares-core on Github are compiled in a transparent way, additionally, the inclusion of further nodes will be greatly facilitated.

## **Elasticsearch BitShares nodes for public use**

Advanced features of the reference wallet require full history and advanced searching capabilities to function smoothly, which requires publicly available nodes with Elasticsearch support. This worker continues to provide a ES entry points for three major geographical regions:

**Direct and read-only ES access** (http authentification BitShares:Infrastructure)

     https://eu.elasticsearch.bitshares.ws
     https://us.elasticsearch.bitshares.ws
     https://hk.elasticsearch.bitshares.ws

**ES wrapper** (https://github.com/oxarbitrage/bitshares-es-wrapper)

This will greatly simplify the workflow of developers and business administration for BitShares and enable easy access to statistical data processing and charting.
Since the Elastic Search plugin from the bitshares-core is now stable, this will be used more extensively in the future. Furthermore, the same structure will be available for the testnet

    https://testnet.elasticsearch.bitshares.ws
    https://testnet.wrapper.elasticsearch.bitshares.ws (API)
    https://testnet.wrapper.elasticsearch.bitshares.ws/apidocs/ (docs)

## **Geolocation-based DNS loadbalancing**

The above nodes and ES instances are available for each version, and will continue to do that to avoid single points of failure. Still,
to enhance connectivity a geolocated entrypoint comes to mind. This would mean that the following domains

    wss://nodes.bitshares.ws
    https://elasticsearch.bitshares.ws
    https://wrapper.elasticsearch.bitshares.ws (API)
    https://wrapper.elasticsearch.bitshares.ws/apidocs/ (docs)

will redirect to one of the three regions (or any other trusted public node) based on the geolocation of the request on a DNS basis, which also allows to do that for WebSocket connections for the BitShares UI. Within this worker proposal this will be analyzed and, if proven successful, be made available to the community. Currently, the domains above are available but merely redirect to the european instances.

## **Insights API for statistics and crypto-ranking websites**

This worker will deploy an API tailored for statistics and crypto-ranking websites to provide up-to-date and reliable information for BTS and the BitShares DEX, called BitShares Insight API. The current development version of this API is available through

    http://88.198.69.93:1235/docs

and will be deployed at `api.bitshares.ws`. As of right now, most of these websites have been using CryptoFresh or other proprietary and potentially unstable APIs, or simply don't have data for BTS and/or the BitShares DEX due to the lack of a tailored API.

# **Commercial use**

In the past there have been several instances of extensive for-profit use of the services provided in this proposal that degraded availability for the broader BitShares community.
Any commercial usage of the nodes and elastic search endpoints included in this proposal will be recognized, and we
will contact the offending party to either cease the usage or seek an agreement. The agreement can be simply a fee
for the increased costs (which will directly flow into the budget of this worker) or provision of additional nodes through the offending party (decided case by case)..

# **Milestones**

1. Maintain deployed infrastructure
2. Maintain ES cluster deployment
3. Maintain ES wrapper / api-explorer deployment
4. Monitoring and Statistics
5. Deploy Insight API for crypto-rankings

As time progresses, more nodes may be added in the most economical manner if needed.

# **Budget**

Operating the nodes:

* **USD (Fee):** Fixed fee (i.a. for knowledge, availability and maintenance) - **1,050 USD/month**
* **USD (Expense):** Payment of the server costs (Hetzner, EC2, Google Cloud, …) - estimated at **150 USD/month/server**

As you can see, we distinguish between fees and expenses. Note that while the total fees are fixed (12,000 USD) for the whole duration of the worker proposal, the expenses (approx. 18,000 USD) may change depending on network growth, server availability and actual hours spent on a task, this includes expenses for server costs starting February 2020. Obviously, as the BitShares network grows, we expect growth of share price which allows this worker to obtain new servers to match bandwidth demands.

### **Cost Overview**

The total costs are summarized again (marked with ~ where estimated expense)

          12 * 1,050 USD     (fixed fee)
     + 12 * 10 * 150 USD ~   (server costs / expenses)
     ===============================================
     =        30,600 USD
       or     28,330 EUR (exchange rate 0.925 EUR/USD)
       or    215,179 CNY (exchange rate 7.03 CNY/USD)

Thus, we are asking for **30,600 USD** for the next 12 months and keep the option to add additional servers as we grow and if economically useful. Please note that this amount includes variable cost (expenses) for servers and actual hours and for those only actual expenses will be billed. We will also optimize existing server costs and switch hosters if necessary.

The payments will happen preferably in bitEUR, but may also happen in any alternative BitAsset or BTS directly depending on market conditions. The value indicated here and on later invoices represent FIAT values, and will be paid in equivalent value of the chosen crypto-currency. The BitShares Blockchain Foundation runs the escrow operations and earns 3% of the overall paid out amounts.

### Daily pay

     Daily worker payout rate 5275 BTS

The daily BTS payout is set to 5275 BTS, which contains a devaluation multiplier of 1.5. In theory, if the price remains the same and the worker is voted active, it will take two thirds of the time to collect the budget for the whole year.
All unused BTS are returned at the end of the worker.

# **Key Performance Indicator (KPI)**

The following KPIs apply

* Availability and latency of load balanced public API servers
* Availability of ElasticSearch access
* Availability of Statistics overview (Grafana)
* Availability of uptime tracker
* Availability of Insight API

If after 12 months, the BTS holders consider this worker a success, we intend to extend our efforts with another worker proposal to keep the deployed infrastructure up and running.

# **Summary to the BTS holder**

This proposal maintains the reliable infrastructure that was built with the  have built with previous [infrastructure worker](https://www.bitshares.foundation/workers/2019-02-infrastructure), builds on top an easy global point of entry (although more centralized) and includes an API for statistics and crypto-ranking websites like CoinMarketCap, CoinGecko, Nomics & Feixiaohao.

# **Remarks**
* The infrastructure and servers are up and running and produce costs. In the case that this proposal is not approved until 15th March 2020, all services rendered will need to be stopped and servers shutdown. Re-enabling it will produce setup fees for maintainers and server providers
* The worker mentions all deployment under the `bitshares.ws` domain. Those deployments may also be available through the `bitshares.org` domain
* Terms & Conditions of APAsia apply with the BitShares DAC being referred to as Client
