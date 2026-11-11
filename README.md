# Jackson Price

**OpenSearch · cloud infrastructure · backend systems**

I work on **OpenSearch at AWS** and contribute to [Floci](https://github.com/floci-io/floci), an open-source AWS emulator. My public contributions focus on AWS API compatibility, resource lifecycles, and Java concurrency.

## Open-source contributions

### Floci — AWS emulation

[**93 merged upstream pull requests**](https://github.com/floci-io/floci/pulls?q=is%3Apr+is%3Amerged+author%3Ajprice8), spanning infrastructure provisioning, service compatibility, and concurrency.

- **Infrastructure provisioning.** Added [CloudFormation support for four AppConfig resource types](https://github.com/floci-io/floci/pull/6791) and [EC2 key pairs with Parameter Store integration](https://github.com/floci-io/floci/pull/7128), including replacement and rollback handling.
- **Service compatibility.** Implemented [Auto Scaling standby transitions](https://github.com/floci-io/floci/pull/6955) and corrected [CloudWatch composite alarm evaluation](https://github.com/floci-io/floci/pull/6987) using documented and observed AWS behavior.
- **Concurrency and reliability.** Moved [blocking AWS protocol and Lambda invocation handlers onto virtual threads](https://github.com/floci-io/floci/pull/6576) to keep waiting requests from tying up shared workers. Fixed [races between CodePipeline action registration and cancellation](https://github.com/floci-io/floci/pull/7634).

## Selected projects

- **[Par Level Reset](https://github.com/jprice8/plr)** — A React and Django application for setting inventory replenishment levels from historical usage data.
- **[Pre-RFP (HyperSearch)](https://pre-rfp-web.vercel.app)** — A platform for discovering government contract opportunities through document ingestion, search, and lead tracking.

[All repositories](https://github.com/jprice8?tab=repositories)

*Contribution count checked November 11, 2026; merged upstream Floci PRs only.*
