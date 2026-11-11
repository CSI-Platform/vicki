# What to build and how to submit

The build bar and the submission checklist for the AWS MSP AI Hackathon. Tracks at a glance, dates, and the prize pool are on [AWS MSP AI Hackathon](aws-msp-hackathon.md). Scoring is on [Judging, prizes, and ownership](aws-msp-judging.md).

## Sources

- Rules §4 (project and submission requirements): [`../raw/aws-msp-ai-hackathon-rules-2026-11-10.md`](../raw/aws-msp-ai-hackathon-rules-2026-11-10.md)
- FAQ, Eligibility (qualifying services) and Submission Requirements: [`../raw/aws-msp-ai-hackathon-faq-2026-11-10.md`](../raw/aws-msp-ai-hackathon-faq-2026-11-10.md)

## Tracks

Name the track on the submission. Each submission is in one track.

**Track 1 — Run Your MSP Better.** Show AI improving internal MSP operations, with measurable efficiency gains. The rules' examples are automated triage and self-healing, multi-agent incident response, and AI-driven FinOps.

**Track 2 — Deliver AI-Driven Outcomes for Customers.** The rules title this “Track 2: External: Deliver AI-Driven Outcomes for Customers.” The FAQ drops the word “External.” Show differentiated AI-powered services for end customers:

- build and deploy customer-facing AI solutions
- modernize business applications with embedded AI
- launch new managed AI offerings with recurring revenue

More than one project is allowed. Each must be unique and substantially different from the entrant's other submissions, as AWS and Devpost decide, and each picks its own track.

## What the project has to be

A working, publicly hosted AI solution that uses at least one required AWS AI service.

| Requirement | What it means here |
| --- | --- |
| Functionality | Installs and runs consistently on the platform it was built for, and behaves as the video and the text description show |
| Production-ready | Not a proof of concept. The rules require a high-level design (HLD) document. The FAQ also requires an architecture diagram with every submission. The Design score separately asks whether it can scale and be reproduced across partner and customer environments |
| New or updated | Created for the hackathon, or, if it already existed, significantly updated after the submission period opened (Nov 2, 2026, 7:00 am PT). Explain the update in the text description and on the form |
| Third-party pieces | SDKs, APIs, and data may be used only within their terms. Open source may be used when the license is followed and the submission builds on it. See [Ownership](aws-msp-judging.md#ownership-and-promotion) |

If the software runs on proprietary or uncommon hardware (not a phone, tablet, or desktop), AWS or Devpost may require physical access to that hardware.

## Qualifying AWS AI services

At least one service has to do real work in the solution. One is enough to enter. Judges look more favorably on solutions that use more than one layer of the AWS generative AI stack — infrastructure, tools for models and agents, and applications — use each service for what it is for, and connect the layers.

The FAQ's named set:

| Service | Notes in the FAQ |
| --- | --- |
| Amazon Bedrock | Includes Amazon Bedrock AgentCore. Aliases that count: AgentCore Runtime, Gateway, and Memory |
| Strands Agents | Alias: Strands SDK |
| Amazon Quick | Alias: Quick Suite |
| Kiro | Aliases: Kiro IDE and Kiro CLI. Promotional credits apply to Kiro |
| AWS Frontier Agents | Examples named: AWS DevOps Agent, FinOps Agent, and AWS Security Agent |
| Amazon SageMaker AI | Alias: SageMaker |
| AWS Transform | Named in the FAQ list |
| Amazon Q Developer | Alias: Q Developer |
| Amazon Nova models | Named in the FAQ list |

The FAQ also counts other AWS AI/ML or generative AI services when they do real work. Examples it gives: Amazon Bedrock Knowledge Bases, Guardrails, Flows, and Agents; AWS Trainium; AWS Inferentia; Amazon Transcribe; Amazon Textract; Amazon Comprehend; Amazon Rekognition; Amazon Kendra.

The rules state the requirement as “at least one of the required AWS AI services, such as Amazon Bedrock, AgentCore, Strands Agents, Amazon Quick, Kiro or the AWS Frontier Agents.” The FAQ list is the more specific public list. Where they disagree, the rules control. See [When sources differ](aws-msp-judging.md#when-sources-differ).

### What does not qualify

- A third-party or open-source model called directly, instead of through Amazon Bedrock or Amazon SageMaker AI.
- AWS used only as general infrastructure (compute, storage, networking, databases) with no AWS AI service in the solution.
- Naming a service in the README and never calling it. The repository must show a runtime use: a library import, an app or backend entry point, or a loaded agent, flow, or MCP config.

Shallow use is a different case. The FAQ says that naming a service, using it as a simple pass-through, using AWS only for hosting, or using AWS only as a model inference endpoint can still meet the minimum and is viewed less favorably. The repository rule is stricter than a README mention: the code has to call the service. Depth is then scored under [Technological Implementation](aws-msp-judging.md#judging-criteria).

## Submission checklist

Enter on the hackathon site during the submission window: Nov 2, 2026, 7:00 am PT through Dec 11, 2026, 12:00 pm PT.

| # | Item | Constraint |
| --- | --- | --- |
| 1 | Track | One track per submission |
| 2 | AWS AI service | Name the service used to build the project |
| 3 | Public project URL | Working and publicly hosted. Free and unrestricted for AWS, Devpost, and the judges until Jan 22, 2027, 5:00 pm PT. If the site is private, put login credentials in the testing instructions |
| 4 | Text description | Features and functionality. If the project existed before the hackathon, explain the update |
| 5 | Code repository | Private GitHub or GitLab URL. See below |
| 6 | Demo video | About 3 minutes, public on YouTube. See below |
| 7 | Architecture diagram | How the components and AWS services connect |
| 8 | HLD document | High-level design showing the solution is ready for a production environment |
| 9 | Language | English, or an English translation of the video, text, testing instructions, and every other material |
| 10 | Ownership | Original work, solely owned by the entrant, no one else's rights violated |

Judges do not have to run the project. They may score from the text, images, and video alone, so those three have to stand on their own.

### Repository

The repo must contain the source, the assets, and the instructions needed to run the project, and it must show the AWS AI service being called at runtime.

Share the private repository with `testing@devpost.com` and `aws-msp@amazon.com`.

If screening flags the repo as inaccessible, the FAQ's causes are a wrong URL, a repo that was not shared with those two addresses, or a repo that was removed. Fix the link or the sharing before the submission period ends.

### Demo video

- About 3 minutes. Judges are not required to watch past 3 minutes.
- Upload to YouTube, set it publicly visible, and paste the link on the form. Upload early; processing can take time.
- Show the project functioning on the device it was built for.
- Include footage of the internal accounts, including all upstream and downstream environments.
- Do not include third-party trademarks, or copyrighted music or other material, without permission.

## Testing access

Provide a link to a website, a functioning demo, or a test build. Keep that access free and unrestricted for the sponsor, Devpost, and the judges until judging ends. Private sites need credentials in the testing instructions.

## Edits after the deadline

Until Dec 11, 2026 at 12:00 pm PT, drafts can be saved in the Devpost portfolio and the submission can still be changed.

After that, the submission is frozen. The project page in the Devpost portfolio may still be updated, but that does not change the submission under judging.

AWS and Devpost may allow a later edit only to add, remove, or replace material that may infringe a third-party right, discloses personal information, or is otherwise inappropriate. The submission has to stay substantively the same.

## Related

- [Eligibility and registration](aws-msp-eligibility.md) — including the $200 credits and the region check
- [Judging criteria](aws-msp-judging.md#judging-criteria)
- [Help](aws-msp-judging.md#help)
