---
layout: post
title: Transferring DNS Domains to AWS
---
I transferred my personal domain, liquidchicken.org, to AWS today with little
issue.  It's important to follow Amazon's instructions very carefully.  See:
[Transferring Registration for a Domain to Amazon Route
53](http://docs.aws.amazon.com/Route53/latest/DeveloperGuide/domain-transfer-to-route-53.html)

There will be several steps on both the AWS Route53 console and on the current registrar's site, including:
  1. Verifying that the admin e-mail is correct and accessible
  2. Unlocking the domain so that the *clientTransferProhibited* flag does not appear in [**Whois**](https://whois.icann.org/en/lookup?name=liquidchicken.org) for the domain
  3. Approving the transfer with your registrar



