---
name: driver-receipt-retired
description: >-
  Deprecated Driver Receipt Generator notice. Use only when an existing installation
  or request refers to this retired skill, to explain its unavailable public receipt
  workflow and point to current ReceAI entry points without claiming automation.
---

# Driver Receipt Generator — retired

Treat this file as a deprecation notice, not an operational receipt-generation skill.

1. Explain that ReceAI retired its standalone public Receipt maker in [PR #77](https://github.com/bptravel2017/receai-platform/pull/77). Do not promise anonymous receipt creation, automatic email sending, share-link generation, saved receipt history, income tracking, mileage tracking, or tax summaries through this skill.
2. Do not direct users to the former Create Receipt action or a blank receipt route. Do not construct synthetic shared receipt links or call retained receipt APIs to recreate the retired public workflow.
3. For an existing shared receipt, use only the original valid link supplied by the user; the compatibility view preserves historical links. Do not treat that view as a public creation entry point.
4. If the user needs to request payment, explain that the separate [invoice editor](https://receai.com/invoice-generator) creates a downloadable invoice PDF for the user to send manually. Do not substitute an invoice for proof of payment or claim to have generated, emailed, or shared a receipt.
5. For existing account business, direct the user to [workspace sign in](https://receai.com/login?next=%2Fdashboard). Daytime and other signed-in accounting features are separate from this retired skill; do not claim workspace integration or access.
6. Recommend disabling or replacing older installed copies of this skill. Do not offer a registry installation or publishing command.

Read [README.md](README.md) for the retirement and distribution status. Both driver receipt repositories are deprecated; neither offers a supported active receipt workflow.
