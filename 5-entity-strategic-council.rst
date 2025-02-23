:: 

  ZIP: unassigned.
  Title: Dev Fund Proposal -- 5 Entity Strategic Council Approach
  Owner: Avichal Garg (avichalgarg@electriccapital.com)
  ZIP Status: Draft
  Discussions-To: https://forum.zcashcommunity.com/t/dev-fund-proposal-5-entity-strategic-council-approach/34801/28
  Community Status: Request for comments
  Category: Process
  Created: 2019-08-28
  License: MIT  
  

Terminology
===============
To understand this ZIP it is critical that people understand the right terminology so their requirements can be quickly checked.

The key words “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and "OPTIONAL"

Have special meaning and people should familiarize themselves with it. - https://tools.ietf.org/html/rfc2119

*Key terms*

* Developer Fund - 20% of the mined ZEC in the four-year period from approximately October 2020 to October 2024 during which at most 5,250,000 ZEC will be minted.
* Strategic Council - five person committee that determines how to allocate the Developer Fund. Held accountable to the community via regular elections.
* Executing Entity - an individual, group, company, or other organization that receives funding from the Strategic Council. Responsible for excellent execution and held held accountable by the Strategic Council.

Out of Scope for this proposal
==================================
* How to do 1 person = 1 vote (and perhaps we cannot or should not do this)
* How to structure the Strategic Council legally, i.e. should it be a Swiss Foundation and what sorts of legally binding responsibilities do the Strategic Council members have?

Abstract
==================================
This proposal reserves 20% of newly minted coins in each block for a Developer Fund. A five-person Strategic Council would be elected by the community every two years. The Strategic Council would determine the high level strategy, goals, and metrics to evaluate progress for the ecosystem on a six-month cadence. The Strategic Council would be responsible for allocating funding to Executing Entities for the subsequent six months and summarizing the performance of Executing Entities in the prior six months. Executing Entities would submit proposals to the Strategic Council on a six-month cadence which include project plans, funding plans, and how they will measure success on a scale from 1-10. At the end of six months, Executing Entities will grade themselves and the Strategic Council will summarize what was accomplished with a target of 7/10 in every quarter on a roll up basis (a simple average of all of the outstanding projects for that six months).

Motivation
==================================
This is an attempt to put on my startup CEO hat and address the strategic and execution challenges I believe have held back Zcash from realizing its full potential.

Requirements
==================================

**Principles & Observations Based on My Experiences (aka Biases?)**

Because layer 1 protocols are network-effect driven, without a quickly growing network-effect in miners, developers, users, and liquidity, a layer 1 protocol will ultimately collapse. 

The primary driver of success in a network-effect business is how quickly you grow the network effects.

To grow a network effect, you must have both the correct strategy and excellent execution. If you strategy is not correct, no matter how well you execute, you will fail. If your execution is not excellent, you will not be able to assess whether lack of progress is due to poor execution or poor strategy.

Thus, to build the network effects Zcash needs to succeed, we must answer 5 questions:

1. Who determines the strategy?
2. How do they decide on the strategy?
3. How are they held accountable to having the correct strategy?
4. Who executes?
5. How are the executors held accountable to executing excellently?

*1. Who determines the strategy?*

* Volunteer based approaches require the ability for individuals or entities to accumulate significant quantities of the underlying coin. Bitcoin did this through obscurity and Grin is accomplishing this through extremely high inflation in the early years. Zcash has moved beyond this phase and thus I do not believe a volunteer based approach could be effective. Thus, a developer fund (or similar approach) is the only realistic option for Zcash today.
* Independent, high quality governance enables better decisions and higher quality execution.
* We should ideally have the recipients of the funds be different entities than the governance body that allocates funds to avoid conflicts.
* Too few people in a decision making process and people can collude. Too many and nothing gets done.
* Good governance and leadership is a significant time commitment and requires significant support/resources.
* There are a variety of perspectives that should be represented, including miners, developers, regulators, and users.

*2. How do they decide on the strategy?*

* Flexibility in how funds are used is important. Strategies and markets change over time and we should be able to evolve. Thus, we should not constrain how funds are used up front.
* There should be no constraint to using all of the funds in any given time frame.
* Creating and fostering decentralized ecosystem of miners and developers is important for the long term health of the ecosystem.
* A regular and predictable cadence in planning and goal setting makes it easy for teams to build, ship, and recharge between intense periods of building.
* Transparency in the strategy, decision making of fund recipients, and how funds are distributed is paramount.

*3. How are they held accountable to having the correct strategy?*

* No organization or individual should have a permanent seat on a decision making body. Regular elections enforce good behavior.
* Third party audits of financial behavior enforce good behavior and create transparency.
* Bad actors should be able to be removed from any decision making body for egregious violations of trust or misbehavior.

*4. Who executes?*

* Anyone should be able to participate in the execution.
* Over time the best executors should have reputation accrue and be able to receive more funds.
* There is value in having distributed executors across geographies and across entities
* There is value in identifying Executors who have long term commitments to Zcash and will be available for long term support and maintenance of their work

5. How are executors held accountable to excellent execution?

* Excellent execution comes from having verifiable hypotheses, backed up with data, and clear milestones.
* Executors need to submit concrete plans, with clear goals and metrics, and be judged according to both whether or not the goals were reasonable and whether they accomplished those goals (ideally in a measurable way using metrics).
* Execution is best measured by pre-defining success and failure criteria, prior to having been influenced by the challenges of the task at hand.

Specification
==================================

*1. Who determines strategy?*

* A five person/entity board -- Five people is better than three to minimize collusion.
* Strategic Council should get two-year term so we can pivot people in the middle if necessary. No permanent seats.
* For the purposes of voting to determine seats (not having seats vote on issues): 1 of the 5 seats should be allocated for miners and signaled through nodes. 1 of the 5 should be ZEC holding weighted so 1 ZEC = 1 vote. 3 of the 5 should be 1 person = 1 vote.
* Elections should be open such that any person or entity can run for a seat.
* The board is a paid position from Dev Fund emissions. Compensation TBD.

*2. How do they decide?*

* 20% of block rewards are allocated for the Developer Fund.
* There should not be any limit up front on where money can go. Perhaps one year it makes sense to invest entirely in protocol and another year it makes sense to invest in user adoption via content marketing, SEO, SEM, etc.
* Every six months, the board has a responsibility to publish an update to the strategy, key metrics that are being tracked, and key metrics to hit as goals in the next six months. This will require feedback from the community but ultimately the board needs to decide on and own the strategy.
* Every six months, the board runs a process whereby anyone can submit proposals for how they would best accomplish these strategic objectives and hit those metrics and milestones.
* No more than 33% of funds can go to one entity for development purposes. This enforces broad decentralization and encourages the ecosystem to identify new participants.

*How are they held accountable for having the correct strategy?*

* Elections every two years from the community.
* All decisions and finances are audited by a third party audit firm.
* There is an annual meeting of all stakeholders (perhaps Zcon?) for feedback, q and a of the board, and a walk through of what has been accomplished in the last six months and what the proposals are for the next six months for feedback. The other six-month cadence meeting for the Strategic Council to present its plans and receive feedback can be virtual.

*4. Who executes?*

* Individuals, teams, or companies from anywhere can submit a proposal that aligns with the strategy (or doesn’t), a budget for what they want to do, and their success criteria on a scale of 1-10 (see below).
* Executing Entities can submit plans that may take longer than 6 months to complete as the reality of hiring and funding employees may dictate longer term financing commitment. The Strategic Committee should have discretion to allow for these sorts of investments but should require intermediate milestones and grading on the 6 month time horizon as well.
* Companies that have sustainable business models and can support or subsidize engineers to work on Zcash or that have adjacent businesses that would benefit from investment in this technology should be encouraged to participate, i.e. the way Square is supporting Bitcoin we should have companies supporting Zcash.
* Ideally the board also encourages non-technical execution such as education, video series, regulatory progress, etc.

*5. How are they held accountable to excellent execution?*

* At the end of six months all proposals are graded 1-10. Each team would pre-agree to what would would result in a 0, 3, 7, 10/10 and then they can move it up or down a little once results are due in 6 months. If they pre-agreed to some definition of results that is a 3 and then tried to give themselves an 8, it would look fishy and could impact future funding.
* The Strategic Council should target an average score of 7/10 for that six months across all Executors. If we score too high, we are not being ambitious enough in our goals. If we score too low, we were trying to do too much or had a fundamental misunderstanding of our goals.
* Over time the Strategic Council decides who gets funds so under-performers will be culled. Thus Executors are held accountable by the board and the board is held accountable by the community.

Issues & Further Discussion
==================================
*Raised objections, issues, and open questions:*

* How might we create a process to amending this process? We may want 4/5 of the Strategic Council to approve changes or 2/3 of ZEC holders to be able to amend the Strategic Council’s charter.
* How do we recall or impeach the members of the Strategic Committee prior to the end of their term if necessary?
* I’m sure there are many other points of ambiguity and improvements we could make. There may even be critical design flaws or failures in this system. Feedback is appreciated.

References / Background
==================================
* https://www.zfnd.org/blog/multisig-governance/ https://forum.zcashcommunity.com/t/placeholder-considerations-resources-governance-and-legitimacy-in-nu4/34045
* https://electriccoin.co/blog/ecc-initial-assessment-of-community-proposals/
* https://medium.com/@socrates1024/here-are-a-couple-of-points-on-framing-the-discussion-of-a-potential-new-dev-fund-in-zcash-c13bcbf4ed5b
* https://www.grin-forum.org/t/solved-early-disappointments/3682
* [www.electriccapital.com](http://www.electriccapital.com) (For disclosure of investments we’ve made)

Changelog
==================================
* 2019-08-27 initial draft - thanks to @jubos, @puntium, @zooko, @joshs, and Jack Gavigan for helping me more clearly articulating my ideas and helping get them formatted properly for a ZIP. These ideas are solely mine and were not influenced by any of these individuals.
* 2019-08-28 updated to be in ZIP format
* 2019-09-15 finally turned in to a pull request on github and incorporated feedback from @daira and @str4d
