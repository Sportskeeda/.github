## Details & link to the story card

A brief of what is the change all about. Always advised to attach Trello card for this change.

> Adding the TLS support to the Web server.

## What is changed

What exactly got changed in this PR? It could be multiple things as well, try to list them down.

- Adapted the Web server to support TLS 1.2.
- Generated & added the private Key & certificate in the repository.

## Before / After

What was the state of the system before the change & what is the state after the change that you are proposing?

> Before the system was not able to receive traffic from https scheme, but now it can serve https traffic.

## Proof of not breaking related things

Any screenshots or video recording would help the reviewer to find out if this change didn't cause any regressions.

> Screenshots from before & after the change

## Demo links

Where to verify the changes? Help the reviewer by providing as many as possible links to the reviewer.

E.g. CDN link, A/B test variant link, etc.

> Any staging env link would help

## How to test the acceptance criteria?

Steps to test the acceptance criteria to acknowledge the feature/bug-fix.

- Visit `https://demo-site.com`.
- You shouldn't see 404 page, rather you should see the homepage of the website served via `https`.

## Dependent Pull Requests

Include the links to the pull requests which may have some dependent changes or some pre-requisite sort of changes

> Infra repo: https://foo.com/bar

## Rollout plan

What are the next steps after the reviewers review this pull request?

- We need to deploy the website. Once deployed, we will check if the website is being served via `https`.

## Area of improvement in future

Include list of potential improvements or technical debt that can/should be addressed in future.

- We can improve storing the TLS certificates & private key somewhere secured.
