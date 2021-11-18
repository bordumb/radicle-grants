> This is the official draft and [Snapshot poll](https://snapshot.org/#/gov.radicle.eth/proposal/0xe9158c0e656918f207f76af0b05feefce2cf07c02e582944825373eebd4ddaff) for the Radicle Grants Program proposal. With this post, the proposal has entered the third phase of the governance process.
>
>Please formally review the proposal and [vote in the Snapshot poll](https://snapshot.org/#/gov.radicle.eth/proposal/0xe9158c0e656918f207f76af0b05feefce2cf07c02e582944825373eebd4ddaff) by 🚨**17:00 CET - Thursday, November 25** 🚨

# **Functional Description** 

The proposal is to start the Radicle Grants Program (RGP). The purpose of which will be to collect, assess, approve, and fund solutions to problems within the Radicle ecosystem.

In other words, the aim is to directly support open source initiatives that help grow the Radicle product, community, and the greater Free and Open Source Software (FOSS) and Web3 community at large.

## **Budget & Timeline**

**Amount:** $1,000,000 (USDC)
**Length:** 6 months

> *Grant funding and compensation for committee members will be controlled by the RGP's multi-sig. As Radicle decentralizes, the budget may fall under a different group entirely and/or utilize Radicle Funding/Drips. Any new arrangements will be assessed at the end of the 6 months. See the Compensation section below for more details.*

## **🐕🦴 Implementation**

**A fundamental goal for the RGP is to dogfood Radicle in order to build a web3-wide model for sustainable software development.** This comes down to 3 main uses of Radicle:

The RGP Committee will be its own [Org](https://radicle.community/t/feature-update-orgs/2132). 
Committee members will be added as [members of the Org](https://docs.radicle.xyz/docs/connecting-to-ethereum/adding-members). 

Grantees post work to relevant [Projects](https://docs.radicle.xyz/docs/using-radicle/creating-projects) within Radicle's core codebase for assessment by Core Dev maintainers. This workflow would be handled with [forks + patches](https://docs.radicle.xyz/docs/using-radicle/viewing-and-merging-patches) with the final anchored commits acting as the "proof of work" for grantees.

Finally, once Radicle Funding is ready, RGP's Org could pay out to grantee Orgs for their work via 
[Drips](https://radicle.community/t/feedback-on-nft-community-tokens/2455).

Below is a high-level diagram of the proposed framework.

![image|375x500](upload://yY5mQw6vjSd2LJi8czLshk1Gamh.png)

> **Note** 
> 
> In the short term, I see all of these pieces being substitute-able by any combination of off-chain tools (GitHub, AirTable, etc.) in order to lower friction for grantees. However, in the long term, the goal is to get as much of this activity on-chain. This is not just for the sake of having things on-chain. It is so that the entire process is natively transparent, highly automated, and so that any learnings and pain points from the on-chain process are fed back to the Radicle product itself. We want a virtuous cycle! 

## **Team & Responsibilities**

### RGP Committee

The group outlined below will act as the RGP committee and will be the signers of the RGP Org's [multi-sig](https://docs.radicle.xyz/docs/connecting-to-ethereum/creating-an-org#creating-an-org). These committee members will be responsible for approving grants and distributing funding to grant projects.

The Radicle Grants Committee is made up of core Radicle team members, Radicle community members, and outside individuals who have related domain expertise within the Web3 ecosystem.

Committed members include:

- [Abbey Titcomb](https://twitter.com/abbey_titcomb) (Core Team)
- [Bordumb](https://twitter.com/bordumbb) (Radicle Community)
- [Kei Kreutler](https://twitter.com/keikreutler) (Ecosystem)
- [Nader Dabit](https://twitter.com/dabit3) (Ecosystem)
- [Nassar Hayat](https://twitter.com/nassarhayat) (Core Team)
- Reverie (comprised of [Derek Hsue](https://twitter.com/derek_hsue) and [Larry Sukernik](https://twitter.com/lsukernik) from the Radicle Community)

### Compensation

Committee members will all be paid at a rate of $150/hour of work.

The rationale behind an hourly rate is that it creates the greatest opportunity for learning
* We will learn how much each committee member actually works
* We will learn whether we need less or more committee members

In either case above, an hourly rate is likely the best mechanism to not overpay, but also not underpay committee members

The rationale behind the rate itself is that we want to make sure we can recruit Committee members who can contribute well behind simple operational tasks. For example, the types of people who can bring a high degree of domain expertise around governance, documentation/education, and recruiting for & management of software development.

This will be paid out in RAD, with the conversion being made based on the average spot price in the last 7 days of each month. The payment will be made at the end of each month. For example, if the average spot price were $15:1RAD at the end of the month and a committee member reported 10 hours of work for the month, they would receive 100RAD for the month (10 hours x 10 RAD, at $15:1RAD).

Committee members must self-report their hours worked by uploading a log to RGP's repository, either on GitHub or Radicle Upstream. Committee members shall not be paid until they have logged their hours.

The committee members themselves will use the multi-sig vote around the end of each month to approve compensation.

As noted above, the goal is **not** to keep compensation decisions contained within the RGP committee. We will move compensation decisions to some sort of external committee (e.g. Compensation Committee) as soon as possible.

### Core Development Team

This section is independent of whether a Core Team member is on the Committee.

Any technical work (i.e. code) will be posted to the respective Project/repo. For example, if a grant project touches Radicle Upstream, the work will need to be posted to either the [Radicle](radicle://link/v0/rad:git:hnrk8ueib11sen1g9n1xbt71qdns9n4gipw1o) or [GitHub](https://github.com/radicle-dev/radicle-upstream) repo.

It will be up to any [maintainer(s)]([maintainers](https://docs.radicle.xyz/docs/connecting-to-ethereum/adding-members)) of the respective repo to review, give feedback, and ultimately approve the work.

Once the work is completed and approved, the grantee will can share the Project ID + anchored commit hash as proof of 
work to the Grant Committee for final payment.

The Core Development Team may at any time join the process to give feedback or guidance on any application. 

### Grants Lead

As mentioned in the forums, the Radicle Governance Working Group decided it would be best to hire a Grants Lead to create and manage the RGP. 

https://radicle.community/t/looking-for-a-radicle-grants-program-lead/2489

After applying, I was chosen to lead the program by the RGWP. I've already introduced myself a bit in [the application here](https://radicle.community/t/looking-for-a-radicle-grants-program-lead/2489). 

I will be responsible for the following:

- Organizing and disseminating project ideas: this will include RFPs from core Radicle members or open applications from the community (e.g. product requests from partners or straight from individual users)
- Building channels for recruiting applicants: this might include things like putting forth RFPs to hackathons or posting bounties on [GitCoin](https://gitcoin.co/)
- Initial screening of applications: the Grant Lead will be the first line of defence for bad applications. Committee Members and Core Dev Team members should trust that they will only have to assess candidates who have met a high bar.
- Scheduling assessments/interviews: this will include scheduling between grant candidates and any relevant Committee Members and/or Core Dev Team
- Planning milestones/check-ins: milestones expected to be written by the grant candidates in their application. The Grant Lead will be responsible to have regular check-ins, depending on the tier of the project (see tiers below)
- Multi-Sig voting: the Grant Lead will communicate to relevant Committee Members when a vote for finalized work is in order.

The core goal of the Grants Lead is to build the Radicle ecosystem.

## **Program Structure & Process**

The entire structure and process is meant to evolve over time, with the long-term goal to push as much of the work onto 
Radicle.

### Project Ideas

RFPs will be the main source of project ideas. RFPs can come from core Radicle members or can be written by users and other community members (e.g. a feature request that another platform's team is keen to have). RFPs from community members must follow the same format as the format established by Radicle. They cannot be free-form. This is to ensure some level of equality when assessing multiple applicants. And the more technical details, the better. This is to ensure we have enough detail to assess an application with as little back-and-forth as possible.

We expect that in Wave 1 of the Radicle Grants Program, most RFPs will come from the core Radicle team. Over time, the line between core member based RFPs and community RFPs should blur. This will be a key part of Radicle's progressive decentralization. Canonical RFPs will be organized within RGP's Org in its own Project. Copies will be made available elsewhere, such as mirroring on GitHub, blog posts, etc. Budget Estimates will be made at this point.

### Scope

The first grants wave will last **6 months**. 

Applications will be reviewed on a rolling basis. Every 2 weeks applications will be assessed by Committee Members. 

Multiple teams may apply for the same grant/RFP. This has several implications. It means applicants are in competition. But Committee Members may also (a) recommend to combine teams or (b) split the RFP into sub-tasks to be divided amongst each grantee.

There will be 3 tiers to help organize and prioritize projects:

- Tier 1
    - Target: individuals/small teams
    - Budget: < $25,000
    - Requirements: 20% of multi-sig approval
    - Time commitment from Committee members: voting pre/post, assessment of work
- Tier 2
    - Target: small teams/start-ups
    - Budget: $25,000 - $50,000
    - Time commitment from Committee members: 1-2 interviews, voting pre/post, assessment of work
- Tier 3
    - Target: small teams/start-ups
    - Budget:  > $50,000
    - Time commitment from Committee members: 1-2 interviews, voting pre/post, assessment of work

> **Note:** Details above are subject to change based on our experience providing grants. 

### Application Process

Grantees may choose from any of the application processes below. Both application processes follow the same form.

**Non-Technical Applications**

*Location:* there will be an [AirTable](https://www.airtable.com/) based application. 

*Process:* it will ask the Applicant for things like their name/pseudonym, GitHub or other previous work material, ask for a URL/name of the RFP they are applying to, or in the case of their own RFP/feature request, will ask them to fill in more details. It will also ask for details on how they plan to address the RFP's work.


**Technical Applications**

This application process is recommended for anyone who wants to immediately start organizing their work with a Git client.

*Location:* the RGP Org will run applications through a Project called "applications." In the example below, there is an rfps folder where all RFPs live. A standard template `[template.md](http://template.md)` , an RFP for Japanese localization posted by the Core Dev Team, and an RFP/application posted by a community member.

```bash
RGP-ORG
  | - applications (project)
  |  | - rfps (folder)
  |  | - | - application-template.md
  |  | - | - japanese-localization (folder)
  |  | - | - | - rfp.md
  |  | - | - | - your-application.md
  |  | - | - my-custom-application (folder)
  |  | - | - | - your-application.md
```

*Process:* to apply, Grant Applicants can [fork + patch](https://docs.radicle.xyz/docs/using-radicle/viewing-and-merging-patches) into an existing RFP's folder or they can create their own RFP folder. In either case, the only thing an applicant should be adding is a new application file (`your-application.md`)

> **Note**
>
> In the short-term (this grant wave), Applicants may substitute this workflow with GitHub using PRs. We will mirror RFPs there. But canonical RFPs will be on Radicle. 

### Milestones

Milestones will either be explicitly written in the RFP and if not, should be addressed by the Grant Applicant in the application.

The purpose of milestones is to break down projects into functional components. In short, the main goal is to mitigate the risk of projects not being 100% complete. If 1 usable component is done and 2 are not, we can restart from square 2, rather than square 1. Second, the simple exercise of creating milestone components organizes the work for the grantee into manageable chunks. Lastly, milestones also help us measure the completion status of the project in a simple way. 

### Grant Approval

The Grant Lead is to communicate Multi-Sig voting due dates and any required secondary assessments, such as interviews.

As noted above, this will occur on every 2nd Friday for Tier 1 grants. For Tier 2/3 grants, this may be on either the 3rd or 4th Friday, subject to Committee Member availability. 

In leu of synchronous interviews, Committee Members may assess applicants asynchronously by providing written questions for the applicant(s) to respond to. This must be done in a timely manner (i.e. several days prior to when the final assessment takes place).

### Project Support

The Grant Lead will directly or indirectly (through other Committee Members) provide grantees with the following:

- Feedback before/during the application process
- Funding
- Feedback on delivered milestones

Outside of these 3 Fs, the RGP will not be a hands-on assistance or mentorship program. We are expecting individuals and teams who are planning to own the work from start to finish.

In cases where there is close integration with the product, Grantees should expect interaction and can get details clarified and pointers via our [community channels](https://radicle.xyz/community.html) (Discord, Matrix, etc.). 

### Posting Work

**Technical Work**

Any technical work (i.e. code) must be posted as a [fork + patch](https://docs.radicle.xyz/docs/using-radicle/viewing-and-merging-patches) if done using Radicle or as a pull request (PR) if on GitHub

For example, if a grant project touches Radicle Upstream, the work will need to be posted as a patch to [Radicle project](radicle://link/v0/rad:git:hnrk8ueib11sen1g9n1xbt71qdns9n4gipw1o) or as a PR in the [GitHub repo](https://github.com/radicle-dev/radicle-upstream).

The maintainer(s) of the respective repo (likely Core Dev Team) will review, give feedback, and ultimately approve the work. 

Grantees will use the Project ID and anchored commit as "proof of work" for final payment (see *Work Approval* and *Payment* below).

> **Note**
> 
> In the short-term (i.e. this first grant wave) Grantees can expect some flexibility to this process. For example, we will allow you to post your final draft to GitHub for assessment. But we will still end up forking it ourselves to bring it into the Radicle Grant Program's own Org.


**Non-Technical Work**

Any non-technical (i.e. non-code) work can be shared in any manner that makes sense.

For example, if the work is to write a blog post, simply sharing a link to the content and a text file will suffice. If it is a video tutorial, a link to the video and a file of the video will work. 

The details for posting non-technical work will be on a case-by-case basis.

> **Note**
> 
> All work **must** adhere to the following criteria:
> - All code produced during your grant must be **open-sourced** with proper licensing (Apache 2.0, but GPLv3, MIT or Unlicense).
> - All code must not rely on closed-sourced software or infrastructure to be fully functioning.

### Work Approval

There are 3 possible approvals, initial grant approval, technical approval, and non-technical approval.

**Initial Approval**

All projects will go through the initial approval. This will be managed entirely by the RGP Committee. An approval in this case is any multi-sig vote on a project that reaches quorum for the initial payment (see *Payment* section below).

**Technical Approval**

Technical approval will include an assessment by relevant Core Dev Team member(s).

For example, if a grant project touches Radicle Upstream, the work will need to be posted as a patch to [Radicle](radicle://link/v0/rad:git:hnrk8ueib11sen1g9n1xbt71qdns9n4gipw1o) or as a pull request in the [GitHub](https://github.com/radicle-dev/radicle-upstream) repo.

The maintainer(s) of the respective repo (likely Core Dev Team) will review, give feedback, and ultimately approve the work to be merged.

The RGP Committee will use this approval as the "proof of work" to disburse final funds from the multi-sig (see *Payment* below).

**Non-Technical Approval**

Technical approval will include an assessment by relevant Core Dev Team member(s).

### Payment

**Schedule**: when a grantees application is approved 40% of the grant will be disbursed upfront to provide immediate funding to grantees. Once 
the work is complete (i.e. gone through Approvals as noted above), the remaining 60% will be disbursed.

**Process for Final Payment**: 
* Technical work: grantees must provide the Project ID + anchored commit showing the work has been approved by a Core Dev Team maintainer. RGP Committee will then disburse funds via the multi-sig.
* Non-technical work: grantees must share the finalized work, which will then be assessed by the RGP Committee, and funds will be disbursed via the multi-sig.

## Communications

Communications will be key and made fairly uniform and consistent. The major steps where communications will be made are:

### 1. Grants Dissemination

As Radicle-based RFPs become available, they should be posted with their budget through the following channels:

- Twitter + other social
- RFP + budgets posted on GitHub, Radicle Grants Program's repo, Blog, and the [#garden channel on Discord](https://discord.gg/AejcRxNJ)

For community-based RFPs, they will be posted if they pass the initial screening.

### 2. Grant Applications

No communications by us. 

But these will be naturally public due to the [fork + patch](https://docs.radicle.xyz/docs/using-radicle/viewing-and-merging-patches) workflow mentioned above (or as PRs in the mirrored repo on GitHub).

### 3. Grant Approvals

As grants are approved on a rolling basis, 

- Approvals of grants (per grant)
    - Added to GitHub, Radicle, Blog on rolling basis as they come in

### 4. Grant Completion

- Completion of individual grant projects (per grant)
    - Twitter + other social (celebrate!)
    - Will be naturally public due to the patch workflow mentioned above

# **Purpose**

The purpose of this entire exercise comes down to three main goals.

First and foremost is **progressive decentralization**. Radicle is meant to enable the decentralization of governance and contributions to free and open-source software. As a result, Radicle itself should be self-governed, self-funded, and self-built for and by the Radicle community. This also aligns with the third high-level objective of the Radicle Foundation, 

Second is that the **team growth** of contributors will mean **product growth**. There is a natural limit to what the Core Dev Team can develop, so new contributors will mean more attention to more features, an improved experience for users, and more innovation. The Radicle Grants Program won't just be a space for peripheral tasks. It will also be a part of Radicle's own recruiting pipeline to bring on new core members. 

Lastly, if we’re successful, the RGP will become a **model for all DAOs**. It will be a model for building self-sustaining, open source projects, DAO-funded project development, as well as DAO-to-DAO (D2D) "business". The RGP will become a hub for sharing best practices around organizing and funding projects, as well as how best to use Radicle to drive governance and development for FOSS. It will do this in a more codified, automated, and in an on-chain way that only Radicle can do.

The RGP is also an initiative that contributes to two of the Radicle Foundation's high level objectives for the project (see full post below):

3. Increase the number of devs building and contributing to Radicle #grants ##progressive-decentralization

4. Strengthen the core teams #people

https://radicle.community/t/radicle-2021-strategy-objectives/2424#high-level-objectives-2

# **Background** (what is the reasoning behind the proposal?)

Radicle is currently run by a couple dozen core members. 

The Radicle Grants Program will be a major towards progressive decentralization.

The reasoning behind starting a grants program is to add structure, process, and automation to the onboarding of new contributors, all of which is powered by Radicle's software itself. This will help us put our best foot forward in decentralizing Radicle.

# **Link to Temperature Check**

https://radicle.community/t/temperature-check-radicle-grants-program/2461/8

# **Reasoning & analysis** (what is the case for the proposal? what are the pros and cons?)

Pros

- The pros largely follow the *Purpose* section above
    - Progressive decentralization: almost by definition, a grants program decentralizes
    - Team growth: the RGP can become a powerful channel for attracting community contributors as well as new core members
    - Product growth: the RGP will bring in more contributions to development of Radicle, which should mean more innovation
    - Feature ideation: the RGP can be a hub for users and contributors to meet where people can share best practices, product requests, and anything else that helps the ecosystem
    - Model for DAOs: the RGP will be a model — both from a process and technological point of view — for other DAOs to adopt

Cons

- There is a risk of projects not working out as expected

# **Technical implementation** (who will be writing the code? what is the scope required?)

### Treasury Funding

- Amount: $1,000,000
- Period: 6 months
- At the end of the period, the money should be sent back to the Treasury
- Would need someone from Core Dev Team + Treasury to implement this

At the end of the 6 months, a new grants wave must be announced, go through [the normal governance process](https://radicle.community/t/readme-radicle-governance-process/526). 

### Execution of Grant Work

(Note: summarized from *Implementation & Setup* above)

The Radicle Grants Program will have its own Org, with a structure like below:

```bash
RGP-ORG
  | - applications (project)
  | - project-one (project)
  | - project-two (project)
```

The Org will be managed by the Grant Lead.

Grant Applicants will use the [fork + patch](https://docs.radicle.xyz/docs/using-radicle/viewing-and-merging-patches) workflow to apply for grants (i.e `applications` project). If applicants use an airflow application, the Grant Lead will post their application publicly to the RGP Org.

Grantees will post work to the respective Radicle Project using [fork + patch](https://docs.radicle.xyz/docs/using-radicle/viewing-and-merging-patches) or as a PR in the respective GitHub repo. Core Dev maintainers will have final say on technical work. Non-technical work will be shared in a way that makes sense for the given work.

Once work is finally approved, the RGP Committee will use voting via multi-sig to disburse funds.

>**Note** 
> 
> In cases where grantees do their work on GitHub or elsewhere, that is fine. But the final draft will be uploaded to 
> Radicle in the relevant Project as noted above. This is what RGP Committee members will use to determine their 
> multi-sig vote for funding.

# **Impact** (how does this contribute to the long-term resilience, sustainability and/or growth of the Radicle network?)

(Note: largely covered above in the *Purpose* section, so summarized below)

- Progressive decentralization: self-sustaining (community funded/community built) growth from community contributors
- Team Growth: will become a pipeline for recruiting new core members
- DAO model: will provide a model for others DAOs to be self-sustaining, both from a process standpoint as well as technological

>Please formally review the proposal and [vote in the Snapshot poll](https://snapshot.org/#/gov.radicle.eth/proposal/0xe9158c0e656918f207f76af0b05feefce2cf07c02e582944825373eebd4ddaff) by 🚨**HH:mm CET - Thursday, November 25** 🚨