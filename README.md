# Driver Receipt Generator — deprecated

**Status: retired after [ReceAI PR #77](https://github.com/bptravel2017/receai-platform/pull/77), merged on 2026-10-07. Do not install or use this skill to create, share, or email new receipts.**

## Why it was retired

This repository contained instructions and package metadata only, with no executable receipt-generation or email integration. Its main workflow depended on ReceAI's standalone public Receipt maker, which has been retired. The advertised anonymous receipt creation, automatic sending, receipt history, and income/tax summaries are not supported capabilities of this skill.

## Current ReceAI entry points

- [Public invoice editor](https://receai.com/invoice-generator): create and download an invoice PDF to request payment; send the downloaded file yourself. An invoice is not proof of payment. This is a separate product, not a replacement receipt workflow for this skill.
- [Accounting workspace sign in](https://receai.com/login?next=%2Fdashboard): use existing authorized account features, including Daytime. This retired skill does not automate the workspace.
- Existing valid shared receipt links remain available through ReceAI's compatibility view. Open the original link unchanged. Do not manufacture new shared links to bypass retirement of public receipt creation.

## Distribution status

This repository and [driver-receipt-generator](https://github.com/bptravel2017/driver-receipt-generator) are both deprecated; neither is an active receipt skill or a supported canonical distribution. Their formerly conflicting `driver-receipt-generator` package manifests now have distinct retired names and `private: true` to prevent accidental npm publication. ClawHub installation commands and promotional metadata have been removed.

`SKILL.md` remains solely as a deprecation notice for agents that load existing copies. Replace or disable older installed copies; their instructions and feature promises are obsolete. This repository change does not withdraw previously published third-party registry versions or update downloaded copies.
