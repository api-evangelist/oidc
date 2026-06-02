---
title: 'Comment on Industry Leaders Lead: Google Asks Developers to Migrate from OpenID
  2.0 to OpenID Connect by Damian Yerrick'
url: https://openid.net/industry-leaders-lead-google-asks-developers-to-migrate-from-openid-2-0-to-openid-connect/#comment-970
date: '2015-04-12'
author: Damian Yerrick
feed_url: https://openid.net/comments/feed/
---
One difference I've found with OpenID Connect is that each relying party needs to obtain a client ID/secret pair from each provider. Not only is this an N^2 problem, but it's not even automatic, as key providers are declining to implement Dynamic Client Registration.
