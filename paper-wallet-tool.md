# Paper Wallet Tool

### Overview

This project is one piece of the overall [scope of work](https://github.com/dashcommunity/proposal-dash-hive/blob/master/proposal.md#scope) of the [Dash Hive proposal](https://www.dashcentral.org/p/dash-hive).  It would continue to build out [this tool](https://github.com/riongull/paper_wallet_tools).

The tool helps track the status of paper wallet give-aways.  Right now it simply checks the balances of paper wallets by running a node.js script from a command line.  That's not very user friendly or feature full.  

The main deliverable would be a **user-friendly web site/application that guides users through the process of administering a paper wallet give-away**.  This would include instructions, tools, and best practices for creating, funding, and giving out paper wallets.  The site/app would also include tools to track balances over time as well as reclaim funds from those who did not (due to loss, disinterest, etc) sweep funds from the paper wallets into their own wallet.

The budgetary estimate for this project is currently **$5,000**, estimated to be **complete within 3 weeks** of commencement.  Details regarding the project motivations, scope of work, schedule, and buget are given below.

##### Background & Motivation

Paper wallet give-aways are a great way to introduce people to Dash.  Prominent past, present, and upcoming paper wallet give-aways include:

* [Arizona Dash Core headquarters open house](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwje-MnM8tjXAhXnxlQKHWeODGIQFggoMAA&url=https%3A%2F%2Fwww.dashcentral.org%2Fp%2FSkySong-Open-House-Reimbursement&usg=AOvVaw3abc2eEGqxLCS2jkMUzh6P)
* [TEDx Salt Lake City event](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=0ahUKEwj74Nnx8tjXAhXis1QKHaMZBZ8QFgg0MAI&url=https%3A%2F%2Fwww.dashcentral.org%2Fp%2FTEDxSLC2017giveaway&usg=AOvVaw3fT-okBwHf8_lpDJs990wm)
* [Tron's 5 DASH/month give-away](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwics7WC89jXAhVqqlQKHa1bCCEQFggoMAA&url=https%3A%2F%2Fwww.dashcentral.org%2Fp%2FIntroduction-to-New-Users&usg=AOvVaw14EJUfsXKcks1GrnOnafGl)

Paper wallet give-aways offer many benefits:

* The issuer has **flexibility** with respect to moving value
  * Issuer can **pre-load** *and/or* **post-load** value to the paper wallet
  * Issuer can **reclaim funds** from unswept wallets
    * The back of a paper wallet can have instructions and an 'expiration date' for claiming funds
    * Funds not swept from paper to phone can be pulled back (after a grace period following 'expiration') by the issuer
* Paper wallets are **very secure**, assuming the recipient trusts the issuer (why wouldn't they; it's a giveaway) 
* Paper wallets are very **fast and simple** to hand out
  * You don't need hardware or internet at the time of the event to make the transfer
  * Recipients walk away with something tangible, akin to cash, which they are familiar with
  * You can hand them out quickly, and rely on instructions/links on the back of the wallet instead of lengthy explanation

There are also several challenges/annoyances relating to paper wallets: 

* **Wallets** created from paper.dash.org **don't have any instructions** 
* **Funding** large quantities of paper wallets **is time consuming**
* **Reclaiming funds** from unswept paper wallets **is time consuming**

### Scope

The scope of work involves creating a user-friendly web site/application with content and tools relating to paper wallet give-aways.

The site would include the following:

* A landing page with overall project description and features
* Content sections with:
  * past/example paper wallet give-aways
  * best practices for paper wallet give-aways
  * instructions for creating paper wallets from paper.dash.org
* Tools for:
  * composing and printing custom instructions sheet
    * to show on back of paper wallets
  * importing public/private key pairs from paper.dash.org output
    * all done client-side, for security
  * funding paper wallets in bulk 
  * displaying stats and plots
    * number of swept wallets over time
    * average time to sweep wallet
  * extracting funds from paper wallets in bulk
    * from those who did not (due to loss, disinterest, etc) sweep funds from the paper wallets into their own wallet.

### Schedule

Work can commence as soon as the Dash Hive proposal passes.  Project can be completed within **3 weeks** of commencement.  More granular project milestones may be added later.

### Budget

The budget is based on time and materials estimates required to complete the scope of work.  Itemized cost estimates are shown below.

> Note: These costs are **rough estimates**, meant for budgetary purposes only.  Items may be added and/or edited up until completion:

* Project managment: **$1,000**
  * refine customer requirments
  * coordinate work assignments
  * community reporting, internal communications, documentation
* Web content development:  **$1,000**
  * past/future event research
  * best practices
* Web site/application development: **$3,000**
  * architecture
  * application development
  * testing, etc

Total cost is **$5,000**, requested in full upon completion.

### Closing

We estimate this tool to save ~10 hours of labor for each sizable paper wallet give-away.  Assuming a labor rate of $50/hr for a paper wallet event administer, this project would pay itself back (considering labor alone) after 10 paper wallet events.  Assuming one event per month, that's a 10-month simple payback.  These are conservative, round-number/ballpark estimates.  Adjust the assumptions to make your own assessment.

Of course the raw project payback is not the only purpose behind the project.  This tool will encourage more people to have give-aways, increasing Dash awareness and investment.  That is likely far more impactful (although less quantifiable) than the simple labor payback analysis above.

With this tool we can analyze data to see how people respond to different give-away amounts (for example, 10% of people may claim funds if $5/wallet is given, where 90% of people may claim funds when $50/wallet is given.  There are additional benefits that justify funding this project.

Thank you for your time and consideration.

\- Dash Hive
