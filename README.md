# Terminology in IETF Documents

Some choices of terminology that might seem harmless to some members of the community have painful connotations for others.  

Here are some of the most common terms that have been identified by other organizations as problematic and some of the alternatives they have suggested:

| Term                                  | Alternative                                       | References                            |
|:--------------------------------------|:--------------------------------------------------|----------------------------------------
| Whitelist                             | Allowlist, approved list                          |[W3C](https://w3c.github.io/manual-of-style/#inclusive), [Ansible](https://www.redhat.com/en/blog/making-open-source-more-inclusive-eradicating-problematic-language), [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656), [Chromium](https://chromium.googlesource.com/chromium/src/+/master/styleguide/inclusive_code.md), [Apple](https://help.apple.com/applestyleguide/#/apsg1a3a0436), [UK NCSC](https://www.ncsc.gov.uk/blog-post/terminology-its-not-black-and-white)| 
| Blacklist	                            | Blocklist, denylist, unapproved list              |[W3C](https://w3c.github.io/manual-of-style/#inclusive), [Ansible](https://www.redhat.com/en/blog/making-open-source-more-inclusive-eradicating-problematic-language), [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656), [Chromium](https://chromium.googlesource.com/chromium/src/+/master/styleguide/inclusive_code.md), [Apple](https://help.apple.com/applestyleguide/#/apsg1a3a0436), [UK NCSC](https://www.ncsc.gov.uk/blog-post/terminology-its-not-black-and-white)| 
| Master/slave                          | Leader/follower, primary/replica, primary/secondary, active/standby, main/secondary  |[W3C](https://w3c.github.io/manual-of-style/#inclusive), [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656), [Apple](https://help.apple.com/applestyleguide/#/apsg72b28652), [Python](https://bugs.python.org/issue34605), [Postgres](https://www.postgresql.org/message-id/flat/E393EC88-377F-4C59-A67A-69F2A38D17C7@yesql.se), [Redis](https://github.com/redis/redis/issues/5335), [Django](https://github.com/django/django/pull/2692), [Drupal](https://www.drupal.org/node/2275877), [CouchDB](https://issues.apache.org/jira/browse/COUCHDB-2248)|
| Master (e.g., branch, key, server)    | Main, parent, server                              |[W3C](https://w3c.github.io/manual-of-style/#inclusive), [Ansible](https://www.redhat.com/en/blog/making-open-source-more-inclusive-eradicating-problematic-language), [GitLab](https://gitlab.com/gitlab-org/gitlab/-/issues/221164), [Python](https://bugs.python.org/issue34605), [Redis](https://github.com/redis/redis/issues/5335)|            
| Grandfathered	                        | Legacy status                                     |[W3C](https://w3c.github.io/manual-of-style/#inclusive), [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656)|
| Gendered terms (e.g., guys)           | People                                            |[Twitter](https://twitter.com/TwitterEng/status/1278733305190342656), [Chromium](https://chromium.googlesource.com/chromium/src/+/master/styleguide/inclusive_code.md)|
| Gendered pronouns (e.g., he/him/his)  | They, them, their                                 |[W3C](https://w3c.github.io/manual-of-style/#inclusive), [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656), [Google](https://developers.google.com/style/inclusive-documentation), [Chromium](https://chromium.googlesource.com/chromium/src/+/master/styleguide/inclusive_code.md)|
| Man in the middle                     | On-path attacker, impersonation attack            |
| Man hours	                            | Person hours, engineer hours, staff hours         |[Twitter](https://twitter.com/TwitterEng/status/1278733305190342656), [Google](https://developers.google.com/style/inclusive-documentation)|
| Sanity check                          | Quick check, confidence check, coherence check    |[W3C](https://w3c.github.io/manual-of-style/#inclusive), [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656), [Google](https://developers.google.com/style/inclusive-documentation)|
| Crazy                                 | Unexpected, surprising, puzzling                  |[Google](https://developers.google.com/style/inclusive-documentation)|
| Dummy value                           | Placeholder value, sample value                   |[W3C](https://w3c.github.io/manual-of-style/#inclusive), [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656), [Google](https://developers.google.com/style/inclusive-documentation)|
| Third world nation                    | Developing nation                                 |
| Balkanization                         | Bifurcation, segmentation                         |

This list is obviously not comprehensive.  In general, authors and reviewers
should be alert about uses of terminology that implies semantics based on:

* Gender
* Age
* Ability
* Ethnicity
* Race
* Socio-economic status

## References

Sometimes IETF documents need to refer to terminology from older IETF documents
or non-IETF documents. In such cases, the
author of the new IETF document should explain the mapping of previously used terms to new terms. 

## Background: Elsewhere on the Internet

The IETF is not alone in trying to make its terminology more inclusive.  Some
peer organizations have published guidelines for writing more inclusive
documentation, for example:

Several of the examples above are drawn from these guides, and they also include
more detailed considerations.

Other organizations working on the same goal include:
* [W3C](https://w3c.github.io/manual-of-style/#inclusive)
* [Twitter](https://twitter.com/TwitterEng/status/1278733305190342656)
* [Google](https://developers.google.com/style/inclusive-documentation)
* [Chromium](https://chromium.googlesource.com/chromium/src/+/master/styleguide/inclusive_code.md)
* [Apple](https://developer.apple.com/news/?id=1o9zxsxl)
* [NIST](https://www.politico.com/news/2020/06/25/agency-ends-use-technology-terms-racist-associations-339880)
* [RedHat](https://www.redhat.com/en/blog/making-open-source-more-inclusive-eradicating-problematic-language)
* [Splunk](https://www.splunk.com/en_us/blog/leadership/biased-language-has-no-place-in-tech.html)
* [GitLab](https://gitlab.com/gitlab-org/gitlab/-/issues/221164)
* [UK National Cyber Security Centre](https://www.ncsc.gov.uk/blog-post/terminology-its-not-black-and-white)
* [Python](https://bugs.python.org/issue34605)
* [Postgres](https://www.postgresql.org/message-id/flat/E393EC88-377F-4C59-A67A-69F2A38D17C7@yesql.se)
* [Redis](https://github.com/redis/redis/issues/5335)
* [Django](https://github.com/django/django/pull/2692)
* [Drupal](https://www.drupal.org/node/2275877)
* [Cisco](https://twitter.com/ChuckRobbins/status/1272977624185204741?s=20)
