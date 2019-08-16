---
layout: default
---

# security.ac.nz Bug Bounty

## Partiticpation 
To participate in this bug bounty, you must be a student enrolled in the School of Engineering and Computer Science at Victoria University of Wellington.
This is due to having agreed to the acceptable use policy of the School computer system. The bug bounty program will only be open during the security.ac.nz event, and after the conclusion of the event students should not be attempting to do any unauthorised security testing.
By participating in this event, you are agreeing to the scope and ethics requirements set below.

## Ethics 
Bug bounties are a tool that can be used by organisations to determine security issues present if any. Usually, unauthorised security testing is illegal under New Zealand law, but the university is generously allowing students to perform testing under controlled situations as part of the security.ac.nz event.
Students must agree that any security issue found is to be reported, and best effort is taken to not abuse the computer systems without authorisation.

## Scope
The scope for this bug bounty is anything running on the ECS network, defined by being part of the following IP ranges:
- 130.195.4.0/22
- 130.195.8.0/22
- 2404:2000:2000::/48

Take care to not perform any tests against systems not in the above scope.

The following issues are outside the scope of our vulnerability rewards program (either ineligible or false positives):

* Attacks requiring physical access to a user's device
* Any physical attacks against Victoria University property or data centers
* Forms missing CSRF tokens (we require evidence of actual CSRF vulnerability)
* Logout CSRF
* Password and account recovery policies, such as reset link expiration or password complexity
* Invalid or missing SPF (Sender Policy Framework) records
* Content spoofing / text injection
* Issues related to software or protocols not under ECS control
* Vulnerabilities only affecting users of outdated or unpatched browsers and platforms
* Social engineering of ECS staff or contractors
* Issues without clearly identified security impact, such as clickjacking on a static website, missing security headers, or descriptive error messages

## Reporting

Take good care in writing up your finding. If you are unsure whether you have found an issue, don't hesistate to ask us. A well written report is an excellent way to get across the details of the issue you have found.
Examples of what your report should include:
- Brief summary of the issue.
- IP address of affected system.
- URL(s) showing the issue if appropriate.
- Full reproduction steps on how to show the issue. Assume the reader does not know anything about the system.
- Screenshots can be useful to show what the reader of the report should expect.

You can make a report at [https://forms.gle/qZLz4QNzKc3ybv8L6](https://forms.gle/qZLz4QNzKc3ybv8L6)

## Prizes

There are some prizes available to award to some participants of the bug bounty. These may be for a really good writeup, a good finding, or some other critiria.