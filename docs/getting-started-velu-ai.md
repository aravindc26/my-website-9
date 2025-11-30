---
sidebar_position: 0
title: Getting started with Velu AI
description: Onboard your team to Velu AI's autonomous documentation platform.
---

# Let's get you started with Velu AI

Velu AI is an autonomous documentation assistant that keeps product guides, API references, and support content aligned with your latest releases by ingesting knowledge from your operational tools and publishing safe, reviewable updates across your documentation stack.

Use this guide to connect your team's systems, run your first automated update, and establish the review controls that keep Velu AI trustworthy.

## Who this guide is for

This guide is written for:

- Technical writers responsible for documentation quality and governance.
- Product managers coordinating release communications.
- Engineering leads who own developer experience and API documentation.
- Support and customer success managers who maintain help centers and FAQs.

## Before you begin

Complete these prerequisites to participate in the Velu AI design partner program (as of November 30, 2025):

- **Secure early access credentials.** Invite-only access is provisioned by the Velu AI team. Ensure your workspace admin account is enabled for the beta environment.
- **Identify the systems Velu AI will monitor.** At minimum, confirm access to your Slack workspace and source code/documentation repositories (GitHub, Confluence, Notion, Google Drive, or equivalent).
- **Collect administrator approvals.** Velu AI requires permission to read release artifacts (Linear or Jira), support tickets (Zendesk), and existing documentation spaces so the platform can reconcile updates against the latest product changes.
- **Define your first automation target.** Pick a product area with known documentation gaps (for example, a recently released feature or a frequently updated API).

## Step 1. Confirm workspace access

1. Sign in with your provisioned Velu AI account.
2. Verify that your organization profile displays the correct Slack workspace, source repositories, and documentation destinations.
3. Add additional admins who will co-manage automation and approvals during the beta.

## Step 2. Connect context sources

Velu AI builds a context graph from your product knowledge. Connect the following sources to maximize coverage:

1. **Slack.** Authorize the Velu AI app so it can monitor tagged threads and power the `/velu update docs` command for manual triggers.
2. **Product planning tools.** Connect Linear or Jira projects where product specs and change logs are maintained. Velu AI uses these updates to detect stale documentation.
3. **Support systems.** Optionally connect Zendesk to surface recurring customer questions that warrant new FAQ entries.
4. **Files and knowledge bases.** Link existing documentation libraries in Confluence, Notion, GitHub repositories, or Google Drive folders. Velu AI will reconcile new drafts against these sources instead of duplicating content.

## Step 3. Choose documentation destinations

Decide where Velu AI should publish drafts and updates:

1. Select your primary documentation platform (for example, GitHub Markdown, Confluence, Mintlify, or Docusaurus).
2. Enable staging versus production destinations so automated updates land in review-first collections.
3. If you maintain multiple help centers, map each content collection to a corresponding Velu AI channel to keep updates organized.

## Step 4. Configure review and governance

Maintain trust by setting up explicit approval checkpoints:

1. Define required reviewers for each documentation collection (technical writers, product owners, or support leaders).
2. Customize style rules (such as Microsoft Style Guide or your internal style sheet) so Velu AI validates tone and terminology before surfacing drafts.
3. Enable audit logging to capture every generated diff, reviewer decision, and publish event for compliance.

## Step 5. Trigger your first documentation update

1. Use `/velu update docs` in Slack on a thread that links to the release or user feedback you want addressed.
2. Velu AI gathers the related Linear/Jira tickets, GitHub commits, and existing documentation pages to draft updates.
3. Review the generated diff in your documentation destination. Accept, edit, or request changes directly within the Velu AI interface.
4. Publish the approved update. Velu AI will record the change, push it live, and add a corresponding changelog or FAQ entry when applicable.

## Step 6. Monitor automation quality

1. Track completion metrics against your launch targets: keep stale documentation below 5% of your library, automate at least 70% of routine updates, and hold release-to-doc turnaround under 24 hours.
2. Inspect the hallucination score on each draft to decide whether future updates can skip manual review.
3. Iterate on connector coverage by adding new repositories or support channels as your product footprint grows.

## Next steps

- Expand coverage to additional products or customer segments once you are confident in the approval workflow.
- Pilot advanced features like GitHub pull request assistance and Chrome-based walkthrough capture as they become available.
- Share feedback with the Velu AI product team to influence roadmap items such as localization, deeper analytics, and on-prem deployments.
