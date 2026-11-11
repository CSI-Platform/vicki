# Judging, prizes, and ownership

How entries are scored, what the $64,000 pool pays, and which ownership and support rules change what you can submit. The build checklist is on [What to build and how to submit](aws-msp-submission.md).

## Sources

- Rules §6 through §15: [`../raw/aws-msp-ai-hackathon-rules-2026-11-10.md`](../raw/aws-msp-ai-hackathon-rules-2026-11-10.md)
- FAQ, Judging & Prizes and Need Help: [`../raw/aws-msp-ai-hackathon-faq-2026-11-10.md`](../raw/aws-msp-ai-hackathon-faq-2026-11-10.md)

## How judging works

AWS and Devpost decide eligibility and the judging method. They may use expert panels, peer review, automated AI-driven analysis, or a combination, in one or more rounds.

Judges are a panel selected by AWS. They may be AWS employees or third parties, they may change before or during judging (Jan 5, 2027, 9:00 am PT – Jan 22, 2027, 5:00 pm PT), and they may not all be listed on the site. Anyone who employs a judge is ineligible. See [Who cannot enter](aws-msp-eligibility.md#who-cannot-enter).

Judges are not required to run the project.

**Stage 1 is pass/fail.** The project must reasonably fit the theme and reasonably apply the required AWS AI services (the rules say “the required APIs/SDKs featured in the Hackathon”).

**Stage 2 scores everything that passed.** Four criteria, weighted equally. The highest overall scores win the prizes those submissions are eligible for. A winner is still only a potential winner until identity, qualifications, role in creating the submission, and the prize affidavit are verified.

## Judging criteria

| Criterion | Weight | What the rules ask |
| --- | --- | --- |
| Technological Implementation | 25% | How well it is built. How deeply it uses the required AWS AI services. Whether the service is a working, essential part rather than a surface add-on. Whether the project shows technical depth and production readiness |
| Design | 25% | Whether it is a complete product ready for production, not a proof of concept. Whether it is built to scale. Whether it can be reproduced across partner and customer environments |
| Potential Impact | 25% | Whether it makes a credible case for a real MSP problem, backed by measurable business outcomes, and whether the demo shows those outcomes |
| Innovation/Idea | 25% | Whether the use of AWS AI in MSP operations or customer delivery is creative and novel, and whether the project understands the MSP problem |

One qualifying service is enough. Using more than one layer of the stack, and using each service for its intended job, is looked on more favorably under Technological Implementation. Shallow patterns (a pass-through, hosting-only, or a bare inference endpoint) can still clear Stage 1 and score lower here. A README mention with no runtime call fails the [repository rule](aws-msp-submission.md#repository) before scoring.

### Tie break

Compare the tied submissions on Technological Implementation first, then Design, then Potential Impact, then Innovation/Idea. If they are still tied on every criterion, the judges vote.

## Prizes

Published total: **$64,000**. Each track has the same ladder. If a prize has no eligible submission, it is not awarded. Prizes are not transferable. The sponsor may substitute a prize of equal or greater value.

Cash plus benefits for the top three in each track:

| Place | Cash | Also |
| --- | --- | --- |
| 1st | $10,000 | Inclusion in the MSP AI Use Case Library (published reference architectures). Priority consideration for AWS go-to-market support and partner marketing. White-glove enablement for a potential AWS Marketplace listing, where applicable |
| 2nd | $7,000 | Same non-cash benefits as 1st |
| 3rd | $5,000 | Same non-cash benefits as 1st |

Special prizes are cash only, one each per track, open to eligible submissions in that track:

| Special prize | Cash |
| --- | --- |
| Best Amazon Bedrock AgentCore Implementation | $2,000 |
| Best Amazon Bedrock Application | $2,000 |
| Best Amazon Quick Application | $2,000 |
| Best Strands SDK Implementation | $2,000 |
| Best AWS Frontier Agents Application (DevOps Agent, Security Agent, FinOps Agent) | $2,000 |

Per track that is $10,000 + $7,000 + $5,000 + five times $2,000 = $32,000. Both tracks sum to $64,000.

### One prize per project

- A project can win only one prize.
- The top three projects in a track cannot also win that track's special prizes.

There is no participation certificate. The project page on Devpost is the record of participation.

## How prizes are paid

| Entrant type | Payee |
| --- | --- |
| Individual | The entrant |
| Team | The Representative, who decides the split |
| Organization | The organization |

A cash prize is mailed or sent to a bank account only after the winner affidavit and other required forms come back. The deadline to return those forms is **10 business days** after they are sent. Prizes are delivered within **60 days** of AWS or Devpost receiving the completed forms. Wrong information can delay delivery, disqualify the entrant, or forfeit the prize.

Winners, and for a team or organization every participating member, owe the taxes and the fees in their jurisdiction (including wire and currency-exchange fees). U.S. residents may have to provide a W-9. Residents of other countries may have to provide a W-8BEN. AWS, Devpost, or the prize provider may withhold part of the prize to meet tax law. Winners also handle any foreign-exchange or banking reporting their own jurisdiction requires.

## Ownership and promotion

The people or organizations who developed a submission keep the intellectual property.

By entering, the entrant gives AWS a non-exclusive license to use the entry for judging. AWS and Devpost may promote the submission and use the name, likeness, voice, and image of everyone who contributed, in materials about the hackathon and its results, during the hackathon and for **three years** after. Some components may be shown to the public. Other materials may be seen by AWS, Devpost, and the judges for screening and evaluation.

The submission must:

- be the original work of the entrant, team, or organization
- be solely owned by them, with no other person or entity holding a right or interest
- not violate copyright, trademark, patent, contract, privacy, or publicity rights

Contracting a third party for technical help is allowed when the submission is still the entrant's work and the entrant owns all rights in it. Open source software or hardware is allowed when the entrant follows the license and the submission enhances that underlying project. Third-party SDKs, APIs, and data have to be used inside their terms.

By submitting or accepting a prize, the entrant also warrants that the content is not under someone else's copyright, trade secret, or other proprietary right unless they own it or have permission, and that it contains no viruses, Trojan horses, worms, spyware, or other harmful code.

Publicity consent covers name, likeness, photograph, voice, opinions, comments, and hometown and country of residence, worldwide, in existing or new media, without further payment or a right of review, unless the law prohibits that.

Hackathon branding, trademarks, and site materials stay owned or licensed by AWS and Devpost. Using their marks in a submission is limited to what the rules allow.

Other agreements incorporated by reference: [Devpost Terms of Service](https://info.devpost.com/terms) (“Poster” there means the sponsor here) and the [Devpost privacy policy](https://info.devpost.com/privacy). If those conflict with the official rules, the official rules control for this hackathon.

## Support that can disqualify a project

A project must not have been developed, or derived from a project developed, with financial or preferential support from AWS or Devpost. The rules include funding or investment for development, work done under contract, or a commercial license from AWS or Devpost any time before the submission period ends. AWS may disqualify a project when giving it a prize would create a real or apparent conflict of interest.

The hackathon's own [$200 promotional credits](aws-msp-eligibility.md#aws-credits) are offered in the entry instructions. They are not the prior funding, investment, development contract, or commercial license this section describes.

## Disputes and changes

Except where the law prohibits it, disputes are resolved individually (not as a class action) by binding arbitration under the American Arbitration Association rules, at the AAA regional office nearest the contestant. The Federal Arbitration Act governs that arbitration. The rules are construed under New York substantive law, without New York choice-of-law rules.

The published rules limit recovery to actual out-of-pocket costs of entering, and they waive punitive, incidental, and consequential damages. Some jurisdictions do not allow those limits.

AWS and Devpost can cancel, suspend, or change the hackathon for technical failure, fraud, or events outside their control. They can disqualify an entrant for tampering, rule violations, or conduct they consider inappropriate or against the event's interests. The official rules prevail over the submission form, the website, and advertising. The rules can be amended by posting on the hackathon site. Someone who thinks a term is ambiguous before the deadline must ask for a written clarification.

## When sources differ

The official rules say that if the rules and any other hackathon material disagree, the rules win. Two differences matter for this wiki:

| Topic | Rules | FAQ |
| --- | --- | --- |
| Track 2 name | “Track 2: External: Deliver AI-Driven Outcomes for Customers” | “Track 2, Deliver AI-Driven Outcomes for Customers” |
| Qualifying services | “Such as” Bedrock, AgentCore, Strands Agents, Amazon Quick, Kiro, or the AWS Frontier Agents | Names those plus SageMaker AI, AWS Transform, Amazon Q Developer, and Amazon Nova, and counts other AWS AI/ML services when they do real work |
| Non-cash benefits | Listed on the 1st, 2nd, and 3rd rows only | Says track winners also receive the library, go-to-market consideration, and Marketplace enablement |

This wiki follows the rules on the prize table. It keeps the FAQ service list because the rules' “such as” does not close the list, and the FAQ is the more specific public statement of what counts.

## Help

| Need | Where |
| --- | --- |
| Build questions during the event | Devpost Discord, `#hackathon-help`, filtered or tagged AWS MSP. Invite linked from the FAQ: <https://discord.gg/pTseWVRyPJ>. Announcements are in `#aws-msp-announcements` |
| Technical and product questions | aws-msp@amazon.com |
| Hackathon questions | The hackathon manager at keshya@devpost.com |
| Devpost platform issues, and questions about the rules | support@devpost.com |
| Credit requests | The [promo credit form](https://app.smartsheet.com/b/form/01a17df24684796aa33f75c461d03210) only, not Discord |
| Service availability | Current AWS documentation for the region you plan to use |

## Related

- [AWS MSP AI Hackathon](aws-msp-hackathon.md)
- [Eligibility and registration](aws-msp-eligibility.md)
- [What to build and how to submit](aws-msp-submission.md)
